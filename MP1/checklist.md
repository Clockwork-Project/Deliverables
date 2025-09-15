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


## **How We Came Up With This Idea**

1. **Team Brainstorming**  
   - Sat together as a group and generated potential ideas.  

2. **Personal Reflection**  
   - Drew on our own experiences balancing coursework, co-op, and personal responsibilities.  
   - Identified pain points like missed deadlines, scattered reminders, and lack of structured focus time.

3. **Reviewing Past Capstone Projects**  
   - Examined the abstract booklist of past SE Capstone projects.  
   - Found that while there were scheduling or reminder apps, there were **few (if any) intelligent productivity assistants** that combine **task capture, prioritization, and automated scheduling**.  
   - This showed an opportunity for originality and practical impact.

4. **External Research**  
   - Looked at online articles, studies, and surveys highlighting **time-management challenges** faced by students and full-time workers.  
   - Confirmed through credible resources (APA studies, Gallup workplace surveys) that managing time and workload is a widespread problem.
   - https://pmc.ncbi.nlm.nih.gov/articles/PMC10297372/
   - https://news.gallup.com/poll/690881/work-schedules-fail-millions-employees.aspx?utm_source=chatgpt.com

5. **AI-Assisted Exploration**  
   - Used **ChatGPT** to expand and refine our brainstorming outcomes.  
   - Explored variations of task managers, focus tools, and scheduling engines before converging on the **Clockwork productivity assistant** idea.
  
## **Team Organization**

- **Current Meeting Schedule**  
  - Monday @ 4:00 PM  
  - Thursday @ 4:30 PM  

- **Communication Channel**  
  - Primary: **Discord** (for day-to-day coordination and quick updates)  

- **Task Management**  
  - Using **GitHub Projects (Kanban board)** to track tasks and progress  
  - Link: [Clockwork Project Board](https://github.com/orgs/Clockwork-Project/projects/1)

## **Success Criteria**

1. **Functionality**  
   - End-to-end flow works: **capture → prioritize → schedule → focus → track**  
   - Reliable **Google Calendar integration** (read/write)

2. **User Adoption**  
   - At least **500 external users** test the prototype  
   - Positive feedback that scheduling feels **useful and accurate**  
   - **Metrics:**  
     - Percentage of tasks completed on time after using Clockwork  
     - Improvement in timely task completion compared to before usage

3. **Usability**  
   - Easy to get started: first task scheduled within **3 minutes**  
   - Users rate usability/trust positively in surveys (**≥ 4/5 average**)

---

## **Risks**

### Technical
- **Calendar API limits or token failures**  
  - *Impact:* Could block scheduling functionality  
  - *Mitigation:* Use minimal scopes, batch requests, test early with seeded accounts  

- **Scheduling conflicts**  
  - *Impact:* Risk of overwriting user’s personal events  
  - *Mitigation:* Only modify **Clockwork-tagged events**, always provide **undo option**

### Project Management
- **Scope creep**  
  - *Impact:* Trying to do too much (e.g., Outlook integration) may prevent MVP completion  
  - *Mitigation:* Focus only on **Google Calendar MVP** for SE390  

- **Team coordination issues**  
  - *Impact:* Misaligned tasks or responsibilities could cause sprint delays  
  - *Mitigation:* Weekly scrums, GitHub Projects board, and **clear task assignments**

### User / Strategic
- **Low adoption**  
  - *Impact:* Users may prefer established apps (e.g., Todoist, Notion)  
  - *Mitigation:* Keep prototype **lightweight, fast**, and highlight **unique intelligent scheduling**

- **Privacy concerns**  
  - *Impact:* Users may hesitate to grant calendar access  
  - *Mitigation:* Be transparent that Clockwork only edits its own events and use **encrypted tokens** for security


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
