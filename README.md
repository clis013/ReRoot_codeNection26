# 🌱 ReRoot by Chilli PanMee

**Team:** Nicole Lee · Crystal Yap Wen Jing  
**Problem Statement:** Stress & Workload Manager  

🎥 **Video Presentation:** https://youtu.be/y8J-EQBxr4Q  
📊 **Presentation Slides:** https://canva.link/1mewsuir2oo7zmh  

---

# 1. Project Overview

## The Problem

University students often juggle classes, assignments, examinations, extracurricular responsibilities, social commitments and personal needs at the same time.

When these demands accumulate, the problem becomes more than simply having **“too much to do.”**

Students can lose the mental space to:

- step back from immediate deadlines,
- understand their overall condition,
- recognise when their workload is becoming unsustainable,
- decide what should actually change.

Instead, they may simply react to whichever task feels most urgent and continue pushing through limited time and energy.

This can lead to **poor prioritisation, ignored mental and physical strain, and an increasingly unsustainable workload.**

Our primary target users are:

> **University students managing multiple overlapping commitments, especially those who are still trying to keep everything running but are beginning to feel overloaded.**

### Where Existing Solutions Fall Short

Existing tools often address only one side of the problem.

| Productivity Tools | Wellness Tools |
| --- | --- |
| Organise tasks, schedules and deadlines | Support mindfulness, stress management and emotional wellbeing |
| Example: **Todoist** | Example: **Headspace** |

However, when stress comes from an imbalance between a student's workload and the resources they currently have available, the key question remains:

> **“Given what I am carrying right now, what should actually change within what I can realistically handle?”**

**ReRoot is designed around this gap.**

Rather than maximising productivity, ReRoot helps students recognise imbalance earlier and make more sustainable decisions about **workload, priorities and recovery**.

---

## 🌱 Our Solution

**ReRoot is a stress and workload decision-support app that represents the user's situation as a living virtual garden.**

It combines:

- workload information,
- daily self-reported state,
- natural stress-dump conversations,

to help determine whether the user's current situation is:

**🟢 Manageable · 🟡 Strained · 🔴 Overloaded**

Instead of asking an already overwhelmed student to organise and analyse everything manually, ReRoot helps turn unstructured thoughts into clearer information and actionable guidance.

It then helps the user decide what should **stay, move, change or pause**.

### Core Experience

> **Dump → Recognise → Rebalance**

---

## Core Features

### 🌳 1. Interactive Garden

The garden gives users an immediate visual overview of their current condition.

| Garden Element | Meaning |
| --- | --- |
| 🌳 **Tree condition** | Workload state: manageable, strained or overloaded |
| ☀️🌥️🌧️ **Weather** | Current stress level |
| 🍎 **Apples** | Workload records |
| 🧑‍🌾 **Gardener** | The user |

Instead of starting with numbers and dashboards, users can first **recognise their condition at a glance**.

### 🕳️🐿️ 2. Tree Hole & Squirrel AI Companion

The **Tree Hole** is a chatroom where users can dump stressful thoughts naturally without organising everything first.

The Squirrel AI helps to:

- identify possible workloads and deadlines,
- identify demands and major stressors,
- connect new information with existing records,
- explain what is contributing to the user's current condition,
- guide the user toward an appropriate next step.

The squirrel also stays available throughout ReRoot as a **floating contextual AI companion**, allowing users to ask questions and adjust plans across the app.

### ⚖️ 3. Balance Planner

The Balance Planner turns understanding into **decisions**.

Instead of only telling users that they are overloaded, ReRoot helps them review what should be:

**Keep · Delay · Reconsider · Reduce · Remove · Recover**

The planner considers:

- deadlines,
- workload demands,
- available time,
- user condition,
- available resources.

> **The goal is not to fill every free hour, but to create a plan the user can realistically sustain.**

---

## Supporting Features

| Feature | Purpose |
| --- | --- |
| **Daily Check-In** | Captures perceived stress, control, mental demand, coping confidence, emotion and energy |
| **Stress & Workload Analysis Map** | Provides deeper analysis of stressors, demands, workload distribution, feasibility and trends |
| **Workload Records & Calendar** | Provides structured workload and scheduling information |
| **Recovery Activities** | Optional Tree Vent and Colouring Reflection activities when recovery is needed |

<br>

---

<p align="center">
  <strong>FROM THE PROBLEM → TO HOW REROOT EVOLVED</strong>
</p>

---

# 2. Ideation & Process

## 2.1 Evolution of Our Idea

ReRoot did not begin as a virtual garden.

It evolved through multiple rounds of **discussion → research → mentor feedback → prototyping → refinement**.

Throughout the process, we kept asking:

> **“How can we help an overwhelmed student not only feel better, but actually understand what is happening and decide what should change?”**

---

### Stage 1 — Two Different Starting Directions

Our first ideas approached the challenge from two perspectives.

#### 📋 Workload & Decision-Making

We noticed that students may understand every individual task, yet lose sight of their overall condition once everything piles up.

Our initial flow was:

> **Dump → Understand → Reality Check → Balance → Recover**

The aim was to understand what was weighing on the user, compare demands with available resources and help them decide what to do next.

#### 💭 Emotional Support & Stress Relief

Our second direction explored:

- AI chat companion,
- personalised AI comics,
- colouring,
- Tree Hole stress release,
- music recommendations,
- community sharing.

Neither direction was enough on its own.

> **ReRoot should connect a student's workload with their current state instead of treating work and wellbeing as two separate problems.**

---

### Stage 2 — Turning “Balance” Into a Structured Concept

Our next question was:

**What do stress, capacity and balance actually mean?**

We could not assume:

> **More tasks = more stress.**

People can experience the same workload differently depending on their coping ability, energy, control, recovery and available resources.

We therefore researched:

- **Job Demands–Resources (JD-R) Model**
- **Transactional Model of Stress and Coping**
- **Conservation of Resources (COR) Theory**
- **Effort–Recovery Model**

Using JD-R as one of our main references:

> **Demands = what the user currently has to handle**  
> **Resources = what the user currently has available to cope with those demands**

We also recognised that **perceived stress matters**.

A workload can appear manageable on paper while still feeling overwhelming to the person carrying it.

#### Research-Informed Concept

```text
                 USER'S CURRENT SITUATION

      DEMANDS                         RESOURCES
         │                                │
  Cognitive Demand                  Energy / Recovery
  Emotional Demand                 Control / Flexibility
  Physical Demand                  Coping Confidence
         │                                │
         └──────────────┬─────────────────┘
                        ↓
                 PERCEIVED STRESS
                        ↓
          Manageable / Strained / Overloaded
```

> **Key shift:** We stopped looking only at how much work a user has and started considering the relationship between **demands, resources and perceived stress**.

---

### Stage 3 — Turning Theory Into App Inputs

Theory alone was not enough. We needed realistic ways to collect this information **without giving users long daily assessments**.

| What We Need | ReRoot Input |
| --- | --- |
| Perceived stress | Daily Check-In |
| Control | Daily Check-In |
| Energy & coping | Daily Check-In |
| Workload demands | Workload Records |
| Hidden workloads / concerns | Stress Dump Chat |
| Existing commitments & available time | Calendar Context |

#### Daily Check-In

Inspired by an **EMA-adapted Perceived Stress Scale**, capturing:

**Stress · Control · Mental Demand · Coping Confidence · Emotion · Energy**

#### Workload Records

Capture structured workload information such as:

**Deadline · Estimated Effort · Flexibility · Demand Type**

NASA-TLX concepts were also referenced when considering workload assessment.

#### Stress Dump Chat

Allows users to describe their situation naturally while AI identifies:

- possible workloads,
- major stress sources,
- demands.

#### Calendar Context

Adds:

- existing commitments,
- available time,
- scheduling constraints.

### Our First Complete System

> **Daily Check-In + Stress Dump + Workload Records + Calendar → Analysis → Workload Management / Recovery**

At this stage, ReRoot had become structured enough to collect information, analyse the user's situation and recommend actions.

But another problem appeared:

**We had too many features.**

---

### Stage 4 — From Many Features to One Clear Purpose

**After Mentor Consultation #1**

We realised that **adding more solutions did not automatically make ReRoot stronger**.

Features such as AI comics, community functions and multiple recovery ideas made the product broader, but distracted from the key question:

> **“What should the user actually do when their current situation is no longer sustainable?”**

So we reduced the scope.

**Dropped**
- AI Comic

**Kept as optional**
- Tree Vent
- Colouring Reflection

**Strengthened**
- Balance Planner

The Balance Planner helps users decide whether something should be:

**Keep · Delay / Move · Reconsider · Reduce · Remove · Recover**

Rather than looking only at urgency and importance, ReRoot also considers the user's current condition and resources.

> **Key shift: Analysis should not be the final output. Analysis should lead to a decision.**

---

### Stage 5 — Complete, But Not Yet Distinctive

With these decisions made, we began building the prototype.

Our system now consisted of:

**Daily Check-In · Stress Dump · Workload Records · Analysis · Balance Planning · Recovery**

Functionally, the concept worked.

However, after our second mentor consultation we identified another weakness:

> **ReRoot had useful functions, but the experience did not yet have a strong identity that made it immediately memorable.**

The prototype still felt like a collection of:

`dashboards` · `cards` · `charts` · `analysis` · `planning tools`

So we began rethinking **how users should experience the system**, rather than changing the underlying logic.

---

### Stage 6 — From Dashboard to a Living Ecosystem 🌳

During earlier brainstorming, we noticed similarities between **apple-tree growth cycles** and sustainable workload management.

When an apple tree carries too much fruit, it consumes significant resources. Orchard management practices such as **fruit thinning** reduce excessive load and help support healthier long-term growth.

This inspired the visual metaphor for ReRoot.

| Apple Tree | ReRoot |
| --- | --- |
| 🍎 Apples | Workload records |
| 🌳 Tree condition | Overall workload state |
| ☀️🌧️ Weather | Stress level |
| 🧑‍🌾 Gardener | User |
| ✂️ Fruit thinning | Reduce, delay or remove unnecessary workload |
| 🌱 Recovery | Restore resources before taking on more demand |

#### Original Apple-Tree Brainstorm

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1O8Q2ZJqxIsL7SMV8dMNYccr076AuLjxF" width="500">
</p>

<p align="center">
  <em>Our brainstorming around the apple-tree sustainability metaphor.</em>
</p>

<p align="center">
  <a href="https://drive.google.com/file/d/1O8Q2ZJqxIsL7SMV8dMNYccr076AuLjxF/view?usp=sharing">View full brainstorm</a>
</p>

The old dashboard-style homepage became an **interactive living garden**.

The garden also connected previously separate features into one experience:

- The original **Tree Hole release idea** became the **Tree Hole Chatroom**
- The original chatbot became the **Squirrel AI Companion**
- The tree became a visual representation of workload condition
- Weather became a visual representation of stress

The squirrel now stays with the user throughout ReRoot to:

**Listen → Explain → Answer → Guide**

We deliberately kept the metaphor simple rather than turning ReRoot into a full game.

> **The garden is not the analysis itself. It is a simpler way for users to recognise what the underlying system is telling them.**

Detailed analysis and planning remain available when users want to go deeper.

---

## Final Direction — Dump, Recognise, Rebalance 🌱

Throughout this process, ReRoot evolved from a broad collection of stress and task-management ideas into a **decision-support system**.

| Stage | Purpose |
| --- | --- |
| 🕳️ **Dump** | Express what is happening without organising everything first |
| 🌳 **Recognise** | See the current state while AI and deeper analysis explain what contributes to it |
| ⚖️ **Rebalance** | Decide what to keep, move, reduce, reconsider or recover from |

### Detailed User Flow

[🔗 **View our detailed ReRoot user flow**](https://drive.google.com/file/d/1O5Q74aSra-o3s00Z0CBu8FnmH1LWOup7/view?usp=sharing)

---

> **ReRoot is not designed to push students to complete as much as possible.** It helps them recognise when their current way of working is becoming unsustainable, step outside the immediate chaos, and make better decisions about what they can realistically carry.
