# 🏀 **Trego — MP2 Feature Specification (Web-Based Prototype)**

## 📘 **Scope & Objective**

**Goal:** Deliver a **web-based prototype** that allows players to:
- Create and manage personal profiles  
- Add friends  
- Create and join open games  
- Mark attendance (*Present / Not Present*) for games they created  

**Platform:** Web application (desktop-first, responsive for browser use).  
**Out of Scope (MP2):** Mobile app, chat/messaging, notifications, tournaments, advanced reputation metrics.

---

## ⚙️ **1. Core Features**

### 🧍 **F1. Player Profile**

**Purpose:**  
Let players customize their identity and sports preferences for better matching.

**Functional Requirements**
- Create and edit personal profile:
  - Display name, profile picture, sports played, self-rated skill (1–5), preferred position(s)
  - Weekly availability (simple day/hour preferences)
  - Optional short bio (max 140 chars)
- View other players’ public profiles (name, sports, skill, reliability tag)
- Control profile visibility (**Public** or **Friends-only**)

**Data Structure**
```json
Player {
  id,
  display_name,
  photo_url,
  bio,
  sports: [ { sport, skill_level, positions[] } ],
  availability: { weekday, start_time, end_time },
  visibility,
  reliability_score
}
```

**Acceptance Criteria**
- Profile can be created/edited within 3 steps  
- Public profiles hide sensitive info (email, contact)  
- Default visibility is **Public**

---

### 🤝 **F2. Friends System**

**Purpose:**  
Build lightweight player connections for trust and discovery.

**Functional Requirements**
- Send, accept, or decline friend requests  
- View friend list and mutual friends  
- Remove friends at any time  
- Filter game list to show **friends’ games only**

**Rules**
- Duplicate or cross requests automatically merge into one accepted friendship  
- Expire unaccepted requests after 30 days  
- Removing a friend also hides visibility-limited content  

**Acceptance Criteria**
- Friend status updates in real-time (no full page reload)  
- Users cannot send requests to the same person twice  

---

### ⚽ **F3. Create Game**

**Purpose:**  
Allow players to host new pickup games and recruit participants.

**Functional Requirements**
- Create game with:
  - Sport type  
  - Title and short description  
  - Date/time and duration  
  - Skill range (min–max)  
  - Location (manual pin drop or place search)  
  - Capacity (# of players)  
  - Visibility (**Public / Friends-only**)  
- Edit or cancel the game before start time  
- See a list of games created by the player  

**Validations**
- Date/time must be in the future  
- Capacity must be ≥ 2  
- Required fields: sport, date/time, location, capacity  

**Data Structure**
```json
Game {
  id,
  creator_id,
  sport,
  title,
  description,
  date_start,
  duration_min,
  location: { lat, lng, place_name },
  skill_min,
  skill_max,
  capacity,
  visibility,
  status
}
```

**Acceptance Criteria**
- Game creation successful within 2 seconds  
- Game appears on the discovery page immediately after creation  

---

### 🏆 **F4. Join Game**

**Purpose:**  
Let players discover and participate in open games.

**Functional Requirements**
- Browse upcoming games with filters:
  - Sport, date/time, distance, skill range, friends-only toggle  
- Request to join game (auto-accepted if space available)  
- Leave a joined game before it starts  
- Prevent overlapping participation (warn if joining another game at same time)  

**Flow**
1. Player views game → clicks **Join**  
2. If slot available → auto-confirm  
3. If game full → show message _“This game is full.”_  

**Acceptance Criteria**
- Joining or leaving updates the player list instantly  
- Joined game appears in player’s **My Games** section  

---

### 🕓 **F5. Attendance (Simplified Reliability System)**

**Purpose:**  
Enable game creators to track attendance after each event.

**Functional Requirements**
- Only the **creator of a game** can mark participants as:
  - **Present** or **Not Present**
- No complex scoring or weighted formula  
- Each player’s profile shows a simple ratio of games attended vs. missed  
  _(e.g., “8/10 games attended”)_

**Data Structure**
```json
Attendance {
  game_id,
  player_id,
  status: "PRESENT" | "NOT_PRESENT",
  marked_by_creator: true,
  updated_at
}
```

**Acceptance Criteria**
- Only the game creator can mark attendance  
- Attendance updates reflected in player profiles  
- Unmarked after 48 hours → defaults to _“Unmarked”_ (no effect)
