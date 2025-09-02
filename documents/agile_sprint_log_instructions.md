# Agile Sprint Log – Instructions

This guide explains how to complete each section of the Agile Sprint Log.  
Use this as a reference when filling out your Sprint Log.  

---

## 0. Review of Previous Sprint (Core)
- **Purpose:** Capture what was expected last Sprint, and how it turned out.  
- **What to include:**  
  - The goal of the previous Sprint.  
  - Whether it was achieved or not.  
  - Problems or bottlenecks that arose.  
  - Feedback received from peers/faculty/AI.  
  - Any tasks that are being carried over.  
- **Example:**  
  - Goal: Build first sound prototype.  
  - Achieved: Partially — oscillator worked, but filters not functional.  
  - Bottleneck: Didn’t know how to configure audio routing.  
  - Feedback: Faculty suggested simpler signal chain.  
  - Carry-over: Implement filter section in next Sprint.  

---

## 1. Speculate / Plan (Core)
- **Purpose:** Define this Sprint’s focus and what you hope to achieve.  
- **What to include:**  
  - A clear Sprint Goal (SMART if possible).  
  - A short checklist of tasks.  
  - Planned deliverables (prototype, doc, demo, etc.).  
  - **Research Needed:** Knowledge gaps identified in last Assessment.  
- **Example:**  
  - Goal: Implement filter stage for prototype.  
  - Tasks:  
    - [ ] Study basic filter design.  
    - [ ] Build circuit in simulation.  
    - [ ] Integrate with oscillator prototype.  
  - Planned Deliverable: Working oscillator+filter test rig.  
  - Research Needed: How digital filter cutoff frequencies are calculated.  

---

## 2. Active Areas (Optional, based on checklist)

### Research
- **Purpose:** Show what questions you investigated this Sprint.  
- **What to include:**  
  - Questions taken from “Research Needed” in Speculate.  
  - Sources consulted (Zotero, articles, tutorials, AI).  
  - Key insights or results.  
- **Example:**  
  - Question: How to implement low-pass filter in Pure Data.  
  - Sources: Pd manual, StackExchange, YouTube tutorial.  
  - Finding: Use `[lop~]` object, cutoff in Hz.  

### Design
- **Purpose:** Record design work done this Sprint.  
- **What to include:**  
  - New diagrams, mockups, or mediation pathways.  
  - Key design choices and why they were made.  
  - Criteria for success.  
- **Example:**  
  - Added mediation diagram showing audio flow.  
  - Decision: Use Pd filters instead of writing custom C externals.  

### Make / Produce
- **Purpose:** Capture production work.  
- **What to include:**  
  - What was built or coded.  
  - Tools/technologies used.  
  - Evidence: screenshots, commits, repo links.  
- **Example:**  
  - Built oscillator+filter patch in Pure Data.  
  - Tools: Pure Data, GitHub repo.  
  - Evidence: commit hash `123abc` + screenshot.  

### Publish / Present
- **Purpose:** Track what you shared externally.  
- **What to include:**  
  - Updates pushed to GitHub.  
  - Slide deck, poster draft, demo, etc.  
- **Example:**  
  - Uploaded Pd patch + README to GitHub.  
  - Presented prototype in seminar, received critique.  

---

## 3. Assess (Core)
- **Purpose:** Reflect on successes, bottlenecks, and lessons.  
- **What to include:**  
  - Successes (what worked well).  
  - Current bottlenecks (tools, skills, time, clarity).  
  - Feedback received.  
  - Adjustments for next Sprint.  
- **Example:**  
  - Success: Filter worked as intended.  
  - Bottleneck: Oscillator aliasing issue.  
  - Feedback: Try higher sample rate.  
  - Adjustment: Research anti-aliasing techniques next Sprint.  

---

## 4. Reflection (Optional but Encouraged)
- **Purpose:** Broader learning, beyond just tasks.  
- **What to include:**  
  - Personal or team reflection.  
  - AI use (what you tried, how you validated it).  
- **Example:**  
  - Reflection: Realized I underestimated complexity of digital filters.  
  - AI Use: Asked ChatGPT for Pure Data filter examples, tested in patch, only kept the ones that matched manual documentation.  

---

# Key Notes
- **Core Sections (always required):** Review of Previous Sprint, Speculate/Plan, Assess.  
- **Optional Sections (only if active):** Research, Design, Make, Publish.  
- The **form is short**; use this **instruction guide for detail/examples**.  
