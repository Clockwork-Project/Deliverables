# Trego — Project

## **Project Vision**

Trego is a **location-based sports connection platform** designed to help students, recreational players, and community clubs reliably find teammates, join teams, and access tryouts.  
Today, many players rely on fragmented tools such as group chats, Instagram posts, or posters, which often result in empty courts, unfilled rosters, or last-minute cancellations.  

Trego solves this by creating a **dedicated hub for sports connections**, where:  
- Players build profiles highlighting their sports, skill levels, and availability.  
- Teams and clubs can schedule tryouts, recruit new members, and request substitutes.  
- Coaches can advertise services, book training sessions, and connect directly with players.  
### **Key Vision Elements**
- **Reliable Matchmaking**: Connects players with teams, games, and tryouts based on intent, skill, and availability.  
- **Tryout Scheduling**: Enables teams to run structured, open tryouts and evaluate players easily.  
- **Substitution Support**: Lets teams find last-minute fill-ins to prevent forfeits or empty games.  
- **Coach Integration**: Coaches can promote services, advertise training events, and manage bookings.  
- **Community Engagement**: Fosters a trustworthy sports ecosystem through reputation scores and feedback.  
- **Scalability for the Future**: Starts with university and community sports; future iterations may expand to leagues, tournaments, and venue integration.  

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
