# 🌱 ReRoot by Chilli PanMee
<img src="https://drive.google.com/file/d/1SEbyP7D1rTgkbAb0KoTXyvC3ku263U_M/view?usp=drive_link" width="420">

**Team:** Nicole Lee · Crystal Yap Wen Jing  
**Problem Statement:** Stress & Workload Manager  
🎥 **Video Presentation:** https://youtu.be/y8J-EQBxr4Q  
📊 **Presentation Slides:** https://canva.link/1mewsuir2oo7zmh

---
## 📌 Table of Contents

- [1. Project Overview](#project-overview)
  - [The Problem](#the-problem)
  - [Our Solution](#our-solution)
  - [Core Features](#core-features)
  - [Supporting Features](#supporting-features)
- [2. Ideation & Process](#ideation-process)
  - [2.1 Evolution of Our Idea](#evolution)
  - [2.2 Ideas We Considered](#ideas-considered)
  - [2.3 Mentor Consultation](#mentor-consultation)
- [3. Design & Prototype](#design-prototype)
- [4. What Makes It Different](#different)
- [5. Technical Architecture & Feasibility](#technical)
---
<a id="project-overview"></a>
# 1. Project Overview
<a id="the-problem"></a>
## 💭 The Problem

University students often juggle classes, assignments, examinations, extracurricular responsibilities, social commitments and personal needs at the same time. When these demands accumulate, the problem becomes more than simply having **“too much to do.”** Students can lose the mental space to step back, understand their overall condition, recognise when their workload is becoming unsustainable, and decide what should actually change. Instead, they may simply react to whichever task feels most urgent and continue pushing through limited time and energy. This can lead to **poor prioritisation, ignored mental and physical strain, and an increasingly unsustainable workload.**

### 🎯 Our Target Users

> <i>**University students managing multiple overlapping commitments, especially those who are still trying to keep everything running but are beginning to feel overloaded.**</i>

### ❓Where Existing Solutions Fall Short

Existing tools often address only one side of the problem.

| Productivity Tools | Mental Wellness App |
| --- | --- |
| Example: **Todoist** | Example: **Headspace** |
| Organise tasks, schedules and deadlines | Support mindfulness, stress management and emotional wellbeing |


However, when stress comes from an imbalance between a student's workload and the resources they currently have available, the key question remains:

> “Given what I am carrying right now, what should actually change within what I can realistically handle?”**

**Let's see how ReRoot is designed around this gap!** 
<br> <br>
## 🌱 Our Solution

ReRoot is a stress and **workload decision-support app** that represents the user's situation as a **living virtual garden.**

It combines **workload information, daily self-reported state and natural stress-dump conversations** to help determine whether the user's current situation is: 

**🟢 Manageable · 🟡 Strained · 🔴 Overloaded**

Instead of asking an already overwhelmed student to organise and analyse everything manually, ReRoot helps turn unstructured thoughts into clearer information and actionable guidance. It then helps the user decide what should **stay, move, change or pause**.

### Core Experience

> **Dump → Recognise → Rebalance**

<br>

## ✨ Core Features

### 1. Interactive Garden 🌳

The garden gives users an immediate visual overview of their current condition.

| Garden Element | Meaning |
| --- | --- |
| 🌳 **Tree condition** | Workload state: manageable, strained or overloaded |
| ☀️🌥️🌧️ **Weather** | Current stress level |
| 🍎 **Apples** | Workload records |
| 🧑‍🌾 **Gardener** | The user |

Instead of starting with numbers and dashboards, users can first **recognise their condition at a glance**.

### 2. Tree Hole & Squirrel AI Companion 🕳️🐿️

The **Tree Hole** is a chatroom where users can dump stressful thoughts naturally without organising everything first.

The Squirrel AI helps to:
- identify possible workloads and deadlines,
- identify demands and major stressors,
- connect new information with existing records,
- explain what is contributing to the user's current condition,
- guide the user toward an appropriate next step.

The squirrel also stays available throughout ReRoot as a **floating contextual AI companion**, allowing users to ask questions and adjust plans across the app.

### 3. Balance Planner 📝

The Balance Planner turns understanding into **decisions**.

Instead of only telling users that they are overloaded, ReRoot helps them review what should be:

<i>**Keep · Delay · Reconsider · Reduce · Remove · Recover**</i>

The planner considers **deadlines, workload demands, available time, user condition and available resources**.

<br>

## 🧩 Supporting Features

| Feature | Purpose |
| --- | --- |
| **Daily Check-In** | Captures perceived stress, control, mental demand, coping confidence, emotion and energy |
| **Stress & Workload Analysis Map** | Provides deeper analysis of stressors, demands, workload distribution, feasibility and trends |
| **Workload Records & Calendar** | Provides structured workload and scheduling information |
| **Recovery Activities** | Optional Tree Vent and Colouring Reflection activities when recovery is needed |

<br>

---

<p align="center"><strong>FROM THE PROBLEM → TO HOW REROOT EVOLVED</strong></p>

---
<br>

<a id="ideation-process"></a>
# 2. 🧠 Ideation & Process
<a id="evolution"></a>
## 2.1 Evolution of Our Idea

ReRoot did not begin as a virtual garden. It evolved through multiple rounds of **discussion → research → mentor feedback → prototyping → refinement**.

Throughout the process, we kept asking:

> <i>“How can we help an overwhelmed student not only feel better, but actually understand what is happening and decide what should change?”</i>

<br>
<details>
<summary><strong><h3> 🚩 Stage 1 — <i>Two Different Starting Directions</i> </h3></strong></summary>

<br>
Our ideas start from two perspectives. 

#### 📋 A) Workload & Decision-Making

We noticed that students may understand every individual task, yet lose sight of their overall condition once everything piles up. Our initial flow was: 

Dump → Understand → Reality Check → Balance → Recover

The aim was to understand what was weighing on the user, compare demands with available resources and help them decide what to do next.

#### 💭 B) Emotional Support & Stress Relief

Our second direction explored:
- AI chat companion,
- personalised AI comics,
- colouring,
- Tree Hole stress release,
- music recommendations,
- community sharing.

Neither direction was enough on its own. We decided to create an app that **connect a student's workload with their current state** instead of treating work and wellbeing as two separate problems.
</details>

<details>
<summary><strong><h3> 🚩 Stage 2 — <i>Turning “Balance” Into a Structured Concept</i> </h3></strong></summary>

<br>

Our next question was: **What do stress, capacity and balance actually mean?**

🚫We could not assume: **More tasks = more stress.**

People can experience the same workload differently depending on their coping ability, energy, control, recovery and available resources.

We therefore researched:
- **Job Demands–Resources (JD-R) Model**
- **Transactional Model of Stress and Coping**
- **Conservation of Resources (COR) Theory**
- **Effort–Recovery Model**

Using the **JD-R model** as one of our main references:

> Demands = what the user currently has to handle  
> Resources = what the user currently has available to cope with those demands

#### JD-R Concept Diagram

<img src="https://drive.google.com/uc?export=view&id=1DnkpBYxexwNB_klci1oWHfKYPyO7hpM3" width="420">

*How the relationship between demands and resources informed ReRoot's concept.*

[🔗 View full JD-R diagram](https://drive.google.com/file/d/1DnkpBYxexwNB_klci1oWHfKYPyO7hpM3/view?usp=sharing)

We also recognised that **perceived stress matters**. A workload can appear manageable on paper while still feeling overwhelming to the person carrying it.

> <i>**Key shift:** We stopped looking only at how much work a user has and started considering the relationship between **demands, resources and perceived stress**.</i>

</details>

<details>
<summary><strong><h3> 🚩 Stage 3 — <i>Turning Theory Into App Inputs</i> </h3></strong></summary>

<br>

Theory alone was not enough. We needed realistic ways to collect meaningful information **without asking overwhelmed users to complete long assessments every day**. We therefore translated the concepts from our research into lightweight app inputs:

| **App Input** | **Purpose** | **What It Provides** |
| --- | --- | --- |
| 📝 **Daily Check-In** | Understand the user's current subjective condition | Perceived stress, control, mental demand, coping confidence, emotion and energy |
| 💬 **Stress Dump Chat** | Surface concerns without requiring users to organise everything first | Possible workloads, major stress sources and demands identified from natural conversation |
| 📋 **Workload Records** | Understand the demands the user is currently carrying | Deadlines, estimated effort, flexibility and different types of workload demand |
| 📅 **Calendar Context** | Understand real scheduling constraints | Existing commitments, available time and scheduling context |

The **Daily Check-In** was inspired by an EMA-adapted Perceived Stress Scale, while **NASA-TLX concepts** were referenced when considering workload assessment.

<br>

### 🔥 Our First Complete System

> **Daily Check-In + Stress Dump + Workload Records + Calendar → Analysis → Workload Management / Recovery**

At this stage, ReRoot had become structured enough to:
- collect information,
- analyse the user's situation from multiple perspectives,
- suggest possible actions.

But another problem appeared...
**We had too many features.**🤯
</details>

<details>
<summary><strong><h3> 🚩 Stage 4 — <i>From Many Features to One Clear Purpose</i> </h3></strong></summary>

<br>

**After Mentor Consultation #1**, we realised that **adding more solutions did not automatically make ReRoot stronger**. Some features were interesting, but they distracted from the main question:

> <i>“What should the user actually do when their current situation is no longer sustainable?”</i>

So we reduced the scope.

| Decision | Features | Why |
| --- | --- | --- |
| ❌ **Dropped** | AI Comic | Interesting emotionally, but had a weaker connection to the core workload-balancing problem |
| 🌿 **Kept as Optional** | Tree Vent, Colouring Reflection | Useful for recovery but not central to the main decision-support flow |
| 💪 **Strengthened** | Balance Planner | Directly helps users turn analysis into decisions and action |

The Balance Planner helps users decide whether something should be:

**<i>Keep · Delay / Move · Reconsider · Reduce · Remove · Recover**</i>

Rather than looking only at urgency and importance, ReRoot also considers the user's current condition and resources.

> **Key shift:** Analysis should not be the final output. Analysis should lead to a decision.
</details>

<details>
<summary><strong><h3> 🚩 Stage 5 — <i>Complete, But Not Yet Distinctive</i> </h3></strong></summary>

<br>

With these decisions made, we began building the prototype. Our system now consisted of:

- Daily Check-In
- Stress Dump
- Workload Records 
- Analysis
- Balance Planning
- Recovery

Functionally, the concept worked. However, after our second mentor consultation we identified another weakness... ReRoot had useful functions, but the experience **did not yet have a strong identity that made it immediately memorable.**

The prototype still felt like a collection of:

`dashboards` + `cards` + `charts` + `analysis` + `planning tools`

So we began rethinking **how users should experience the system**, rather than changing the underlying logic.
</details>

<details>
<summary><strong><h3> 🚩 Stage 6 — <i>From Dashboard to a Living Ecosystem 🌳</i> </h3></strong></summary>

<br>

During earlier brainstorming, we noticed similarities between **apple-tree growth cycles🍎** and sustainable workload management.

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

The old dashboard-style homepage became an **interactive living garden!** The garden also connected previously separate features into one experience:
- The original **Tree Hole release idea** became the **Tree Hole Chatroom**
- The original chatbot became the **Squirrel AI Companion**
- The tree became a visual representation of workload condition
- Weather became a visual representation of stress

The squirrel now stays with the user throughout ReRoot to:

**Listen → Explain → Answer → Guide**

We deliberately kept the metaphor simple rather than turning ReRoot into a full game. Detailed analysis and planning remain available when users want to go deeper.
</details>

<details>
<summary><strong><h3> 🌱 Final Direction — <i>Dump, Recognise, Rebalance</i> </h3></strong></summary>

<br>

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
</details>
<br>

<br>

<a id="ideas-considered"></a>

## 2.2 Ideas We Considered

We focused on one main goal throughout our refinement:

> <i>Help users recognise overload and make better decisions about what should change.</i>

Ideas that directly supported this goal were **kept, strengthened or redesigned**. Others were reduced to supporting features or removed to keep ReRoot focused and feasible.

| **Idea** | **Decision & Reason** |
| --- | --- |
| **Stress Dump Chat** | ✅ **Kept & Redesigned — Core**<br>We kept it as an easy entry point for users to express stressful thoughts without organising everything first. AI identifies possible workloads, stressors and demands. It later evolved into the **Tree Hole Chatroom**. |
| **Balance Planner** | ✅ **Kept & Strengthened — Core**<br>Analysis alone does not solve the problem. The Balance Planner turns insights into decisions and guides users toward the next action. |
| **Interactive Garden** | ✨ **Added — Core**<br>Provides an interactive visual representation of the user's state and connects previously separate features into one cohesive experience. |
| **Squirrel AI Companion** | ✨ **Added — Core**<br>The AI originally existed only inside Stress Dump Chat. We expanded it into a persistent companion that provides explanations, answers questions and guides users throughout ReRoot. |
| **Stress & Workload Analysis** | ✅ **Kept — Strong Supporting Feature**<br>Provides deeper perspectives on major stressors, workload demands, time feasibility and trends. We kept the detailed analysis behind the simpler garden overview so users can explore it when needed without being overwhelmed immediately. |
| **Daily Check-In** | ✅ **Kept — Supporting Feature**<br>Provides lightweight self-reported information about stress, control, mental demand, coping confidence, emotion and energy without requiring a long daily assessment. |
| **Workload Records** | ✅ **Kept — Supporting Feature**<br>Structured workload information is necessary for understanding demands and generating realistic analysis and planning recommendations. |
| **Calendar Integration** | ✅ **Kept — Supporting Context**<br>Provides additional context about existing commitments, available time and scheduling constraints to improve planning feasibility. |
| **Tree Hole Vent** | 🌿 **Kept — Optional Recovery Feature**<br>A simple stress-release interaction where users can shout and trigger animations. It remains optional because it supports emotional release but is not central to workload balancing. |
| **Colouring Reflection** | 🌿 **Kept — Optional Recovery Feature**<br>Provides a simple pause and recovery activity, so it remains a secondary feature rather than part of the main decision-support flow. |
| **AI-Generated Comic** | ❌ **Dropped**<br>The comic aimed to turn the user's situation into an encouraging story and provide emotional support. However, it required more complex implementation, had a weaker connection to the core workload-balancing problem and risked distracting from the main solution. |
| **Community Sharing** | ❌ **Dropped**<br>Community interaction could provide emotional support, but it expanded the scope without strongly contributing to ReRoot's main decision-support purpose. |
| **Music Recommendations** | ❌ **Dropped**<br>Music could support relaxation, but it was a relatively generic wellness feature and contributed less to the core purpose compared with other ideas. |

<br>
<br>
<a id="mentor-consultation"></a>

## 2.3 🤝 Mentor Consultation


### Mentor Feedback 


<details>
<summary><strong>🧑‍🏫 Mentor Session 1 — Marcus Mah Qing Fung  📅 2/9/2026 </strong></summary>

### 💬 Feedback Received

**Comments**
- Reduce some features.
- Users may overestimate the effort required for a workload. The app should help them reconsider how much work is actually needed.
- UI/UX is important; use stronger UI components and reference platforms such as Dribbble and Motion.

**Suggestions**
- Connect the AI chatbot with other features in the app.
- Structure the prototype demo as **scenario → solution → impact**.
- Record the product and present it clearly in the demo.
- Consider a Progressive Web App instead of a native mobile app.

**For Later Phases**
- If we expand beyond university students, frame this as future scalability rather than changing the current target user.

### 🔧 What We Changed

- ❌ Removed the **AI Comic** feature.
- 📋 Added **subtask recommendations and records** so users can better estimate how much work a workload may require.
- 🔗 Connected the **AI Stress Dump Chat** to other features such as **Map, Balance and Recovery**.
- 🎛️ Improved UI components by using more visual and interactive controls rather than relying mainly on text-field input.
- 🌐 Decided to use **Vercel / Netlify** for prototype deployment during this phase.

</details>

<details>
<summary><strong>🧑‍🏫 Mentor Session 2 — Sim Hong Bin  📅 9/9/2026 </strong></summary>

### 💬 Feedback Received

**Comments**
- The app contained too much text.
- The UI was clean but could make better use of icons and visual elements.
- The solution was functional, but nothing immediately stood out as distinctive.

**Suggestions**
- Consider adding a **character or mascot**.
- Add more **real-time interaction**, including AI responses throughout the user experience.
- Focus the presentation on only **2–3 main features** to avoid confusing judges.
- Add something that improves user experience and gives the product a stronger identity.
- Refine the product with a more competition-focused mindset.

### 🔧 What We Changed

- 🌳 Built the **interactive garden ecosystem** to visualise the user's condition.
- 🐿️ Introduced the **Squirrel AI Companion**, which stays with users throughout the ReRoot journey and can provide contextual responses and guidance.
- 🎬 Restructured the demo to focus on a small number of strong core features and follow a clearer **scenario → solution → impact** flow.
- 👁️ Reduced reliance on text-heavy interfaces and strengthened visual interaction.

</details>



> **Notes:** The first mentor session helped us **reduce and connect the system**, while the second pushed us to make ReRoot **more distinctive, visual and competition-focused**.

