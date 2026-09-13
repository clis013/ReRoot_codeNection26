# 🌱 ReRoot by Chilli PanMee

**Team:** Nicole Lee · Crystal Yap Wen Jing  
**Problem Statement:** Stress & Workload Manager  
🎥 **Video Presentation:** https://youtu.be/y8J-EQBxr4Q  
📊 **Presentation Slides:** https://canva.link/1mewsuir2oo7zmh

---

# 1. Project Overview

## 💭 The Problem

University students often juggle classes, assignments, examinations, extracurricular responsibilities, social commitments and personal needs at the same time.

When these demands accumulate, the problem becomes more than simply having **“too much to do.”** Students can lose the mental space to step back, understand their overall condition, recognise when their workload is becoming unsustainable, and decide what should actually change.

Instead, they may simply react to whichever task feels most urgent and continue pushing through limited time and energy. This can lead to **poor prioritisation, ignored mental and physical strain, and an increasingly unsustainable workload.**

### 🎯 Our Target Users

> **University students managing multiple overlapping commitments, especially those who are still trying to keep everything running but are beginning to feel overloaded.**

### ❓Where Existing Solutions Fall Short

Existing tools often address only one side of the problem.

| Productivity Tools | Wellness Tools |
| --- | --- |
| Organise tasks, schedules and deadlines | Support mindfulness, stress management and emotional wellbeing |
| Example: **Todoist** | Example: **Headspace** |

However, when stress comes from an imbalance between a student's workload and the resources they currently have available, the key question remains:

> **“Given what I am carrying right now, what should actually change within what I can realistically handle?”**

**ReRoot is designed around this gap.** Rather than maximising productivity, ReRoot helps students recognise imbalance earlier and make more sustainable decisions about **workload, priorities and recovery**.
<br> <br>
## 🌱 Our Solution

**ReRoot is a stress and workload decision-support app that represents the user's situation as a living virtual garden.**

It combines **workload information, daily self-reported state and natural stress-dump conversations** to help determine whether the user's current situation is:

**🟢 Manageable · 🟡 Strained · 🔴 Overloaded**

Instead of asking an already overwhelmed student to organise and analyse everything manually, ReRoot helps turn unstructured thoughts into clearer information and actionable guidance. It then helps the user decide what should **stay, move, change or pause**.

### Core Experience

> **Dump → Recognise → Rebalance**
<br> <br>
## ✨ Core Features

### Interactive Garden 🌳

The garden gives users an immediate visual overview of their current condition.

| Garden Element | Meaning |
| --- | --- |
| 🌳 **Tree condition** | Workload state: manageable, strained or overloaded |
| ☀️🌥️🌧️ **Weather** | Current stress level |
| 🍎 **Apples** | Workload records |
| 🧑‍🌾 **Gardener** | The user |

Instead of starting with numbers and dashboards, users can first **recognise their condition at a glance**.

### Tree Hole & Squirrel AI Companion 🕳️🐿️

The **Tree Hole** is a chatroom where users can dump stressful thoughts naturally without organising everything first.

The Squirrel AI helps to:
- identify possible workloads and deadlines,
- identify demands and major stressors,
- connect new information with existing records,
- explain what is contributing to the user's current condition,
- guide the user toward an appropriate next step.

The squirrel also stays available throughout ReRoot as a **floating contextual AI companion**, allowing users to ask questions and adjust plans across the app.

### Balance Planner 📝

The Balance Planner turns understanding into **decisions**.

Instead of only telling users that they are overloaded, ReRoot helps them review what should be:

**Keep · Delay · Reconsider · Reduce · Remove · Recover**

The planner considers **deadlines, workload demands, available time, user condition and available resources**.

> **The goal is not to fill every free hour, but to create a plan the user can realistically sustain.**

## 🧩 Supporting Features

| Feature | Purpose |
| --- | --- |
| **Daily Check-In** | Captures perceived stress, control, mental demand, coping confidence, emotion and energy |
| **Stress & Workload Analysis Map** | Provides deeper analysis of stressors, demands, workload distribution, feasibility and trends |
| **Workload Records & Calendar** | Provides structured workload and scheduling information |
| **Recovery Activities** | Optional Tree Vent and Colouring Reflection activities when recovery is needed |


---

<p align="center"><strong>FROM THE PROBLEM → TO HOW REROOT EVOLVED</strong></p>

---


# 2. 🧠 Ideation & Process

## 2.1 Evolution of Our Idea

ReRoot did not begin as a virtual garden. It evolved through multiple rounds of **discussion → research → mentor feedback → prototyping → refinement**.

Throughout the process, we kept asking:

> **“How can we help an overwhelmed student not only feel better, but actually understand what is happening and decide what should change?”**
<br><br>
### 🚩 Stage 1 — Two Different Starting Directions

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
<br><br>
### 🚩 Stage 2 — Turning “Balance” Into a Structured Concept

Our next question was: **What do stress, capacity and balance actually mean?**

We could not assume:

> **More tasks = more stress.**

People can experience the same workload differently depending on their coping ability, energy, control, recovery and available resources.

We therefore researched:
- **Job Demands–Resources (JD-R) Model**
- **Transactional Model of Stress and Coping**
- **Conservation of Resources (COR) Theory**
- **Effort–Recovery Model**

Using the **JD-R model** as one of our main references:

> **Demands = what the user currently has to handle**  
> **Resources = what the user currently has available to cope with those demands**

#### JD-R Concept Diagram

<img src="https://drive.google.com/uc?export=view&id=1DnkpBYxexwNB_klci1oWHfKYPyO7hpM3" width="420">

*How the relationship between demands and resources informed ReRoot's concept.*

[🔗 View full JD-R diagram](https://drive.google.com/file/d/1DnkpBYxexwNB_klci1oWHfKYPyO7hpM3/view?usp=sharing)

We also recognised that **perceived stress matters**. A workload can appear manageable on paper while still feeling overwhelming to the person carrying it.

> **Key shift:** We stopped looking only at how much work a user has and started considering the relationship between **demands, resources and perceived stress**.
<br><br>
### 🚩 Stage 3 — Turning Theory Into App Inputs

Theory alone was not enough. We needed realistic ways to collect meaningful information **without asking overwhelmed users to complete long assessments every day**.

We therefore translated the concepts from our research into lightweight app inputs:

| **App Input** | **Purpose** | **What It Provides** |
| --- | --- | --- |
| 📝 **Daily Check-In** | Understand the user's current subjective condition | Perceived stress, control, mental demand, coping confidence, emotion and energy |
| 💬 **Stress Dump Chat** | Surface concerns without requiring users to organise everything first | Possible workloads, major stress sources and demands identified from natural conversation |
| 📋 **Workload Records** | Understand the demands the user is currently carrying | Deadlines, estimated effort, flexibility and different types of workload demand |
| 📅 **Calendar Context** | Understand real scheduling constraints | Existing commitments, available time and scheduling context |

The **Daily Check-In** was inspired by an EMA-adapted Perceived Stress Scale, while **NASA-TLX concepts** were referenced when considering workload assessment.

### 🔥 Our First Complete System

> **Daily Check-In + Stress Dump + Workload Records + Calendar → Analysis → Workload Management / Recovery**

At this stage, ReRoot had become structured enough to:
- collect information,
- analyse the user's situation from multiple perspectives,
- suggest possible actions.

But another problem appeared...

**We had too many features.**
<br><br>
### 🚩 Stage 4 — From Many Features to One Clear Purpose

**After Mentor Consultation #1**

We realised that **adding more solutions did not automatically make ReRoot stronger**. Some features were interesting, but they distracted from the main question:

> **“What should the user actually do when their current situation is no longer sustainable?”**

So we reduced the scope.

| Decision | Features | Why |
| --- | --- | --- |
| ❌ **Dropped** | AI Comic | Interesting emotionally, but had a weaker connection to the core workload-balancing problem |
| 🌿 **Kept as Optional** | Tree Vent, Colouring Reflection | Useful for recovery but not central to the main decision-support flow |
| 💪 **Strengthened** | Balance Planner | Directly helps users turn analysis into decisions and action |

The Balance Planner helps users decide whether something should be:

**Keep · Delay / Move · Reconsider · Reduce · Remove · Recover**

Rather than looking only at urgency and importance, ReRoot also considers the user's current condition and resources.

> **Key shift: Analysis should not be the final output. Analysis should lead to a decision.**
<br><br>
### 🚩 Stage 5 — Complete, But Not Yet Distinctive

With these decisions made, we began building the prototype.

Our system now consisted of:

**Daily Check-In · Stress Dump · Workload Records · Analysis · Balance Planning · Recovery**

Functionally, the concept worked.

However, after our second mentor consultation we identified another weakness:

> **ReRoot had useful functions, but the experience did not yet have a strong identity that made it immediately memorable.**

The prototype still felt like a collection of:

`dashboards` · `cards` · `charts` · `analysis` · `planning tools`

So we began rethinking **how users should experience the system**, rather than changing the underlying logic.
<br><br>
### 🚩 Stage 6 — From Dashboard to a Living Ecosystem 🌳

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

<img src="https://drive.google.com/uc?export=view&id=1O8Q2ZJqxIsL7SMV8dMNYccr076AuLjxF" width="420">

*Our brainstorming around the apple-tree sustainability metaphor.*

[🔗 View full brainstorm](https://drive.google.com/file/d/1O8Q2ZJqxIsL7SMV8dMNYccr076AuLjxF/view?usp=sharing)

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
<br><br>
## 🌱 Final Direction — Dump, Recognise, Rebalance

Throughout this process, ReRoot evolved from a broad collection of stress and task-management ideas into a **decision-support system**.

| Stage | Purpose |
| --- | --- |
| 🕳️ **Dump** | Express what is happening without organising everything first |
| 🌳 **Recognise** | See the current state while AI and deeper analysis explain what contributes to it |
| ⚖️ **Rebalance** | Decide what to keep, move, reduce, reconsider or recover from |

### Detailed User Flow

[🔗 **View our detailed ReRoot user flow**](https://drive.google.com/file/d/1O5Q74aSra-o3s00Z0CBu8FnmH1LWOup7/view?usp=sharing)

---

> *ReRoot is not designed to push students to complete as much as possible. It helps them recognise when their current way of working is becoming unsustainable, step outside the immediate chaos, and make better decisions about what they can realistically carry.*
