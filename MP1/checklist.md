# Trego — Project

## **Project Vision**

Trego is a **location-based sports connection platform** designed to help students, recreational players, and community clubs reliably find teammates, join teams, and access tryouts.  
Today, many players rely on fragmented tools such as group chats, Instagram posts, or posters, which often result in empty courts, unfilled rosters, or last-minute cancellations.  

Trego solves this by creating a **dedicated hub for sports connections**, where:  
- Players build profiles highlighting their sports, skill levels, and availability.  
- Teams and clubs can schedule tryouts, recruit new members, and request substitutes.  
- Coaches can advertise services, book training sessions, and connect directly with players.
- 
### **Key Vision Elements**

- **Player Profiles**  
  - Each user maintains a personal profile with:  
    - Sports played and self-rated skill levels (beginner → advanced).  
    - Availability windows (weekly schedule preferences).  
    - Game history (matches attended, reliability %).  
  - Profiles are visible to teams, clubs, and coaches for evaluation.  

- **Team & Club Management**  
  - Teams can create shared profiles with:  
    - Roster list (current players and positions).  
    - Open positions and recruitment posts.  
    - Past performance records (e.g., games played, win/loss).  
    - Managed by a designated team captain or manager.  
  - Clubs can host recurring events (e.g., weekly practice or pickup nights).  

- **Reliable Matchmaking**  
  - Location-based game discovery using maps and filters (sport, skill, distance, time).  
  - Smart suggestions matching players to games or teams based on profile data.  
  - Availability matching: app cross-checks schedules to recommend best fit.  
  - Dynamic updates (notifications when nearby games need players).  

- **Tryout Scheduling**  
  - Teams create structured tryout events with:  
    - Date, time, and location.  
    - Desired player attributes (positions, skill levels, experience).  
  - Players register and confirm attendance.  
  - After the tryout:  
    - Teams evaluate players (Accepted / Rejected / Shortlist).  

- **Substitution Support**  
  - Teams post last-minute requests for substitutes  
  - Nearby players receive push notifications based on location and skill fit.  
  - Substitutes can accept instantly; team gets confirmation.  
  - Attendance tracked to boost substitute’s reliability score.  

- **Reliability & Reputation System**  
  - Attendance automatically tracked (via QR code check-in or captain confirmation).  
  - Reliability Score shown on each profile (% of games attended vs. missed).  
  - Peer feedback 
  - High-reliability players prioritized in matchmaking.  

- **Game & Event Management**  
  - Organizers can create pickup games or tournaments with:  
    - Location, date/time, sport, skill requirement, and # of players needed.  
    - Auto-waitlist system when games fill up with private or public game.  
  - Games sync to player/team calendars with reminders.  

- **Community Engagement**  
  - Leaderboards (most active players, best attendance, multi-sport athletes).  
  - Optional “friend system” to follow teammates and join their games.  

---

## **How We Came Up With This Idea**

1. **Team Brainstorming**  
   - Sat together and explored unmet needs in campus and community life.  

2. **Personal Reflection**  
   - Drew on our own experiences where finding reliable teammates or filling empty courts was a constant struggle.  

3. **Reviewing Past Capstone Projects**  
   - Checked the SE Capstone abstract booklets for inspiration.  
   - Found no dedicated projects addressing **sports matchmaking, tryouts, and recruitment** — highlighting a gap.  

4. **External Research**  
   - Observed that many students and community members cite **difficulty in organizing games and finding reliable players** as a top barrier to staying active.  
   - Looked at apps in other regions (China super-apps, niche sports apps) and noted a lack of unified, intent-driven solutions.  

5. **AI-Assisted Exploration**  
   - Used **ChatGPT** to refine and expand on early concepts.  
   - Iterated toward the idea of a **sports-specific, reliability-focused connection app** instead of a generic social network.  

---

## **Team Organization**

- **Current Meeting Schedule**  
  - Monday @ 4:00 PM  
  - Thursday @ 4:30 PM  

- **Communication Channel**  
  - Primary: **Discord** (for day-to-day coordination and quick updates)  

- **Task Management**  
  - Using **GitHub Projects (Kanban board)** to track tasks and progress  
  - Link: [Trego Project Board](https://github.com/orgs/Clockwork-Project/projects/1)  

---

## **Success Criteria**

1. **Functionality**  
   - End-to-end flow works: **profile → find game/team → join or tryout → confirm attendance**  
   - Teams can reliably schedule **tryouts, recruit players, and request substitutes**  

2. **User Adoption**  
   - At least **500 external users** test the prototype  
   - Positive feedback that matchmaking feels **reliable and useful**  
   - **Metrics:**  
     - Number of games successfully filled via Trego  
     - Percentage of users who find and join a team/game within first 2 weeks  

3. **Usability**  
   - Easy onboarding: first game/join request within **3 minutes**  
   - Players and teams rate usability positively in surveys (**≥ 4/5 average**)  

---

## **Risks**
https://docs.google.com/spreadsheets/d/1SgYo7QBFXjS-gqshAIte5Evx2Y1gjnLvZAcL1flzNGQ/edit?gid=904221976#gid=904221976  

### Technical
- **Location & API constraints**  
  - *Impact:* Map/geo APIs may limit free usage or fail in certain regions  
  - *Mitigation:* Use open-source maps (OpenStreetMap) alongside Google Maps; cache data locally  

- **Real-time reliability tracking**  
  - *Impact:* Missed check-ins may misrepresent attendance  
  - *Mitigation:* Provide multiple verification methods (QR check-in, captain confirmation)  

### Project Management
- **Scope creep**  
  - *Impact:* Trying to add advanced features (wearable data, tournaments) may delay MVP  
  - *Mitigation:* Focus first on **profiles, games, tryouts, substitutions**  

- **Team coordination issues**  
  - *Impact:* Misaligned deliverables or task ownership may slow down sprints  
  - *Mitigation:* Weekly scrums, clear Kanban tracking, defined sprint goals  

### User / Strategic
- **Low adoption**  
  - *Impact:* Players may stick to existing group chats or social media  
  - *Mitigation:* Emphasize **unique features** like tryout scheduling, substitution support, and reliability scores  

- **Trust and safety concerns**  
  - *Impact:* Users may hesitate to meet strangers via the app  
  - *Mitigation:* Add **reputation scores, verification options, and peer feedback**  
