# Clockwork — Project

## **Project Vision**

Clockwork is an **intelligent personal productivity assistant** designed to help students and young professionals manage their workload effectively.  
Many users rely on scattered tools (sticky notes, Discord reminders, or basic calendar apps), leading to missed deadlines and reduced productivity.  
Clockwork addresses this by combining **task capture, smart prioritization, and automatic scheduling** into a single lightweight platform.

### **Key Vision Elements**
- **Unified Workspace**: One place to capture, view, and manage tasks from multiple sources (typed or voice input).
- **Intelligent Scheduling**: Automatically suggests focus blocks by analyzing user availability, task urgency, and deadlines.
- **Calendar Integration**: Syncs seamlessly with Google Calendar (read/write), ensuring schedules remain consistent across tools.
- **Focus & Productivity Support**: Provides focus modes (timers, progress tracking) to encourage deep work and build study/working habits.
- **Trust & Transparency**: Clockwork explains *why* it scheduled a task in a given slot and only modifies events it creates, avoiding conflicts with personal calendars.
- **Scalability for the Future**: Initial prototype focuses on individuals; future iterations may extend to small teams with shared tasks and collaborative planning.



1. Done



2. Current meeting schedule:
Monday 4:00PM
Thursday 4:30PM

Communication channel: Discord

Tasklist: Github projects (kanban) board. https://github.com/orgs/Clockwork-Project/projects/1

3. 
?

4. 
Team 26 in the year 2022: https://ece.uwaterloo.ca/~se_capstone/se2022-abstract-booklet.pdf

Time limit for internet/web access. We might have something similar, 

5. 
- Sat together and brainstormed ideas.
- Reflect on our own experiences as students/co-op students. "What are the things that we need that would help improve our daily workflow?"
- Go through past Capstone Projects to get inspirations. We noticed there were not many dedicated intelligent personal productivity assistants that combine task capture, prioritization, and scheduling.
- Search online for examples/external resources.
- Used ChatGPT to elaborate on ideas

6.
Done

7. 
What are the success criteria? What are potential risks? 

Success Criteria:

  1) Functionality
  
  End-to-end flow works: capture → prioritize → schedule → focus → track.
  
  Reliable Google Calendar integration (read/write).
  
  2) User Adoption
  
  At least 500 external users test the prototype.
  
  Positive feedback that scheduling feels useful and accurate.

  Metrics: 
  How many people finish their tasks on time, and what percentage of their tasks get finished on time (after using our app).
  
  3) Usability
  
  Easy to get started (first task scheduled within 3 minutes).
  
  Users rate usability/trust positively in quick surveys (≥ 4/5).
 
Risks Technical

1) Calendar API limits or token failures → Could block scheduling.
Mitigation: Use minimal scopes, test with seeded accounts early.

2) Scheduling conflicts → Risk of overwriting user’s events.
Mitigation: Only modify Clockwork-tagged events, provide undo.

Project Management

1) Scope creep → Trying to do too much (e.g., Outlook integration) and failing core features.
Mitigation: Focus on Google Calendar MVP only for SE390.

2) Team coordination issues → Delays in sprints.
Mitigation: Weekly scrums, clear task assignments.

User/Strategic

1) Low adoption → Users may prefer existing apps.
Mitigation: Keep prototype lightweight, fast, and highlight unique “intelligent scheduling” feature.

2) Privacy concerns → Hesitation to share calendar access.
Mitigation: Be transparent: Clockwork only edits its own events, encrypt tokens.
