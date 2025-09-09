# Agile Techniques for Effective Reporting and Feedback

This document expands on the basic Agile Sprint Instructions by introducing **techniques that make Agile Reports more collaborative, detailed, and actionable**. Students should use these approaches to strengthen their weekly reports and to provide meaningful feedback to classmates.

## 1. Retrospective

Each Agile Report begins with a **retrospective on the previous sprint**. Reflection helps you recognize progress, identify challenges, and decide what to improve next. Keep this brief and honest — it connects your past work to your current sprint.  

**Format:**  
- *What went well?*  
- *What didn’t go well?*  
- *What can I improve next week?*  

**Example (Puppet Story):**  
- What went well? The prototype successfully tracked puppet movement in Unity.  
- What didn’t go well? Latency was consistently around 500ms, making control difficult.  
- What can I improve next week? Investigate Unity OSC plugins and optimize settings to reduce delay.  


## 2. Current State  

Every Agile Report begins with a snapshot of **where the project is right now**. This section provides context for your new sprint and helps your peers and instructor understand what you are building on. Keep it short and factual — 2–3 bullet points are enough. Think of it as saying: *“Here’s the ground I’m standing on.”*  

**Format:**  
*Summarize in 2–3 bullet points the concrete progress since last week (prototype results, tests, observed problems).*  

**Example (Puppet Story):**  
- Puppet prototype runs in Unity.  
- Current response time is ~500ms, which makes control feel laggy.  
- Testing shows consistent delay across multiple trial runs.  

## 3. User Stories

As humans, we respond instinctively to stories.  This is useful, as our profession, by and large, is to communicate by story.  Agile projects often describe work in terms of **user stories**, which frame goals from the perspective of a user or stakeholder.  Much has already been written about this, so I defer repetition and refer you to some of these.  To me, the important part is that **The perspective of the Agile Story is the End User**: get in the head of your hypothetical user and think about teh project freom THEIR point of view.  

- [Wikipedia entry on user story](https://en.wikipedia.org/wiki/User_story)
- [Atlassian:User Stories](https://www.atlassian.com/agile/project-management/user-stories) 

**Format:**

* *As a \[user type], I want \[feature] so that \[reason/value].*

**Example:**

* *As a performer, I want the puppet tracking system to respond smoothly so that I can control the character in real time.*

## 4. Acceptance Criteria

Each user story or sprint goal should include **acceptance criteria** that define when the work can be considered complete.  One approach to Acceptance is the "Given-When-Then" approach.  

**Format:**

*Given* [starting condition or context],  
*When* [action or event occurs],  
*Then* [expected measurable outcome].

**Example Criteria:**

*Given* the performer moves the puppet,  
*When* the tracking system processes the input,  
*Then* the puppet should update on screen within 200ms.

Acceptance criteria give peers and the instructor something specific to respond to when reviewing progress.

[Product Plan's definition and explanations](https://www.productplan.com/glossary/acceptance-criteria/)  
This link describes the Given-When-Then approach to acceptance criteria and how to tie it to the User Story.  


## 5. Definition of Done (DoD)

A **Definition of Done** (DoD) clarifies what it means for a task or milestone to be finished.  If YOU can't describe when you are done, then how can someone else, and how do you know that you have met the criteria?  

**Format:**

*The work is considered done when [specific measurable conditions for this story/sprint are met].*

**Example (Puppet Movement Story):**

*The puppet movement feature is considered done when:  
- The puppet responds to performer movement within 200ms,  
- The response remains stable for at least 2 minutes of continuous motion,  
- The puppet stops smoothly without jitter when the performer stops.*


This reduces confusion and helps the class give focused feedback, as they can test based on your criteria.    

[Product Plan DoD](https://www.productboard.com/glossary/agile-definition-of-done/)  


## 6. Blockers as Help Requests

When reporting blockers, frame them as **requests for collaboration** rather than just obstacles.

**Format:**

*Blocker: [describe the problem]*  
*Help Request: [specific question or request for assistance]*

**Example (Puppet Movement Story):**

*Blocker: The puppet response currently lags by 500ms, making it difficult to control in real time.*  
*Help Request: Does anyone know Unity plugins or methods to reduce latency in OSC message handling?*


This invites classmates to contribute solutions, and makes it explicit WHERE you need or request help.

## 7. Goals  

Goals describe the **outcomes you intend to achieve in this sprint**. Unlike the Definition of Done (the full finish line), goals are the *steps toward* that finish line.  

**Format:**  
*List 2–3 outcomes for this sprint that move you toward your Definition of Done.*  

**Example (Puppet Story):**  
- Reduce latency by testing Unity OSC plugins.  
- Collect timing data to measure response accuracy.  
- Document findings in the Iteration Plan.  

## 8. Next Steps  

Next Steps are **specific, immediate tasks** you will complete before the next class/report. They are tactical “to-do” style items that can be checked off.  

**Format:**  
*List 2–4 concrete, actionable tasks you will complete by the next class/report.*  

**Example (Puppet Story):**  
- Install and configure Unity OSC plugin.  
- Run latency tests and record ms results.  
- Compare at least two plugin options for performance.  


---  

## Peer Feedback Framework

When responding to classmates’ Agile Reports, use:

* **Acknowledge:** Identify one clear strength.
* **Suggest:** Offer one improvement or adjustment.
* **Ask:** Pose one clarifying question.

This ensures every peer comment adds value and encourages dialogue.

---

**Name:** Jane Doe  
**Repository Link:** https://github.com/janedoe/ENT4501-Project  

**Agile Report #3 Summary:**  

- **Retrospective:** Last week I built a Unity prototype to test puppet movement. What went well: the puppet responds to tracking input. What didn’t: latency is ~500ms, making it difficult to control. Improvement: break down testing into smaller experiments to isolate the delay.  
- **Current State:** Puppet prototype runs in Unity; latency consistently around 500ms across multiple trial runs.  
- **User Story (Next Sprint Focus):** As a performer, I want the puppet to respond quickly so that I can control it naturally.  
- **Acceptance Criteria (GWT):**  
  - Given the performer moves the puppet,  
  - When the tracking system processes the input,  
  - Then the puppet should update on screen within 200ms.  
- **Definition of Done:** Puppet responds within 200ms, remains stable for 2 minutes of continuous movement, and stops smoothly when performer input ceases.  
- **Goals (Steps Toward DoD):** Test Unity OSC plugins, collect timing data, and document results in Iteration Plan.  
- **Blockers/Help Request:** Latency currently ~500ms using default OSC plugin. Help Request: does anyone know Unity OSC plugins or techniques to reduce delay?  
- **Next Steps:** Install and configure new Unity OSC plugin; run latency tests; compare performance of at least two plugin options.  

**Peer Feedback Example:**  
- **Acknowledge:** Clear latency problem is identified with measurable testing.  
- **Suggest:** Try breaking down testing into shorter sessions to see if latency increases over time.  
- **Ask:** Are you planning to test latency on different machines or only one setup?  
