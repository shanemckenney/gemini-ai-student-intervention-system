# AI Student Intervention System

## Overview

The **AI Student Intervention System** is a prompt-driven workflow designed to help instructors, mentors, and training programs quickly identify struggling students and generate structured, actionable intervention plans.

This system transforms simple student inputs into:

- **Root cause analysis** (skill vs behavior vs mindset)  
- **Coaching strategy**  
- **Instructor and student action plans**  
- **Risk classification**  
- **Communication templates**  
- **Documentation-ready summaries**  

---

> 💡 This project demonstrates how to build a **custom Gemini Gem** that converts student performance data into structured coaching interventions and execution plans.

---

## Problem

Instructors often struggle with:

- Inconsistent intervention approaches  
- Difficulty identifying the real issue behind poor performance  
- Time-consuming coaching decisions  
- Lack of structured workflows for student recovery  

This leads to:

- Lower certification pass rates  
- Student disengagement  
- Inefficient use of instructor time  

---

## Solution

This project provides a **repeatable AI-powered workflow** that:

1. Analyzes student performance and behavior  
2. Identifies root causes  
3. Generates structured intervention plans  
4. Produces execution-ready outputs  

---

## ⚠️ Required Configuration (Important)

This system is **not plug-and-play by itself**.

It is designed to work alongside **your organization’s policies, standards, and coaching framework**.

Before using this system, you must define:

- Your **student success or intervention policies**  
- Your **performance expectations and thresholds**  
- Your **coaching or mentoring framework**  
- Your **documentation standards** (CRM, logs, etc.)  

### Why this matters

The system does not replace your organization’s process—it **structures and executes it**.

Without this context, outputs may be generic and less effective.

### Example Inputs You Should Provide to the AI

- Internal training policies  
- Escalation procedures  
- Coaching models (e.g., A-OO-A, GROW, etc.)  
- Performance benchmarks  

> Think of this system as a **decision engine**, not the source of truth.

---

## How It Works


INPUT → ANALYSIS → COACHING LOGIC → ACTIONABLE OUTPUT


---

## Input Template

Use the following template when working with the system:


Student Name:
Current Course:
Issue:

Recent Behavior:
(What you’ve observed – attitude, participation, effort, communication)

Performance Data:
(Scores, attempts, assignments missing, attendance, etc.)

Context (if any):
(Job, family, tech issues, prior conversations, mindset concerns, etc.)

What I’m Considering (optional):


---

## Example Output

### Situation Breakdown  
Student is underperforming due to inconsistent study habits and low engagement, not lack of ability.

---

### Coaching Strategy  
Focus on accountability and structure.

**Coaching Questions:**

- What’s been getting in the way of your study time?  
- What does your current routine actually look like?  

---

### Action Plan  

**Instructor Actions**

- Schedule 1:1 session within 24 hours  
- Assign targeted remediation  

**Student Actions**

- Complete 2 practice exams before next class  
- Attend support session  

---

### Risk Level  
**Medium** – performance and engagement decline  

---

### Suggested Message  
“Hey [Name], I want to connect quickly. We’re close here—just need to tighten up a few things.”

---

### Documentation Log  
Student showing performance decline and reduced engagement. Outreach completed and intervention plan established.

---

## Core Frameworks Used

- **A-OO-A Coaching Model**  
  *(Agenda → Obstacles → Options → Action)*

- **Root Cause Analysis**
  - Skill gap  
  - Behavior gap  
  - Mindset barrier  

- **Execution-First Coaching**
  - Clear actions  
  - Measurable outcomes  
  - Immediate next steps  

---

## Key Features

- Fast, repeatable intervention planning  
- Action-oriented outputs (not just analysis)  
- Built-in prioritization and risk identification  
- Communication + documentation generation  
- Scales instructor effectiveness  

---

## Use Cases

- Technical training programs  
- Certification-based education  
- Workforce development programs  
- Mentorship and coaching environments  

---

## Why This Matters

This system demonstrates how AI can be used to:

- Improve coaching consistency  
- Reduce decision fatigue  
- Scale instructor effectiveness  
- Increase focus on execution and student success  

---

## 🚀 Setup & Usage

### Step 1: Create a Gemini Gem

1. Open Gemini  
2. Navigate to **Gems**  
3. Click **Create a new Gem**

---

### Step 2: Configure the Gem

- Paste your instruction set into the **Gem Instructions/System Prompt** field  
- Customize it with:
  - Your organization’s policies  
  - Your coaching framework  
  - Your documentation standards  

---

### Step 3: Use the Input Template

Paste the template into your Gem and fill it out for each student case.

---

### Step 4: Execute the Plan

Use the output to:

- Conduct coaching conversations  
- Send student communication  
- Create tasks and follow-ups  
- Document interventions  

---

## 🧠 Gemini Instruction Set

Below is a **generalized instruction framework** used to power this system.

This should be placed inside your Gemini Gem configuration.

---

### Role

You are an expert coach and instructor responsible for analyzing student performance and generating structured intervention plans.

---

### Core Responsibilities

- Identify root cause (skill vs behavior vs mindset)  
- Apply a structured coaching framework  
- Generate actionable plans  
- Provide communication and documentation outputs  

---

### Required Output Format

1. Situation Breakdown  
2. Coaching Strategy  
3. Action Plan  
   - Instructor Actions  
   - Student Actions  
4. Risk Level  
5. Suggested Message  
6. Documentation Log  

---

### Behavior Rules

- Be direct and actionable  
- Avoid generic advice  
- Prioritize execution  
- Do not ask unnecessary follow-up questions before providing value  

---

### ⚠️ Customization Required

You must adapt this instruction set by adding:

- Your organization’s policies  
- Your intervention procedures  
- Your coaching framework  
- Your documentation requirements  

> This instruction set is the **engine**, but your policies are the **rules of the road**.

---

## Disclaimer

This project represents a generalized coaching and intervention framework.

It does **not** include proprietary systems, internal documents, or confidential processes from any organization.

---

## License

MIT License
