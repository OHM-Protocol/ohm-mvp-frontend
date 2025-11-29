# OHM MVP Development Plan

This document serves as the central reference for the OHM platform MVP, synthesizing our
development journey, core philosophy, and agreed-upon next steps.

It is designed to help contributors connect:

- The **video walkthrough** of the MVP frontend, and  
- The **code snippet PDFs / source files**  

into a coherent understanding of how the platform should behave.

---

## 1. Core Philosophy: The Global Good River

The guiding metaphor for OHM is the **“river of global good.”**

Each user's contribution is a current flowing from their **Global Good Vision** to their
real-world impact through their **Mission** and **Projects**.

The platform is designed as a decentralized, purpose-led ecosystem that empowers individuals
to create their own currents, which join to form a **collective river of positive change**.

---

## 1.1 The OHM Manifesto: A Framework for a Purpose-Driven Economy

### Introduction: An Age of Upliftment

Our world is in a state of profound transition. While old systems grapple with complexity and
division, a new potential is emerging—the potential for a smooth, intentional, and AI-assisted
elevation of human purpose. Our story begins here.

We envision a global ecosystem not just for goods and services, but for **goodwill**.

A **purpose-driven economy** that reshapes human productivity towards the collective benefit
of all life on Earth. Our mission is to build the operating system for this new economy.

This is **OHM**—a simple, clean conduit for the greater good.

### The AI Guide: Empowering the Individual

This smooth transition is enhanced by AI.

The AI Guide is the individual's **private partner**, designed to remove friction and empower
purpose. This partnership between human intention and AI assistance ensures that every person
has the tools to become a powerful force for global good, creating a world where every
contribution, no matter how small, is a step in the right direction.

---

## 1.2 The Choice: A Mandate for a Purpose-Driven Humanity

We are entering an era where the fate of humanity rests in each and every one of our hands.

In a decentralized world, old layers of hierarchical structures are starting to wear thin, and
it is increasingly **humanity itself** that must govern its own actions.

With the added power of technology, we must ensure we use our personal empowerment for
good to create a better world together.

OHM is built upon this fundamental choice.

Our purpose is to provide the tools for humanity to **consciously choose good**, and we have
architected the system itself to be an engine of its amplification.

Through a continuous feedback loop, the **collective intelligence of the whole** is used to
advance the individual's ability to create more, and more effective, good.

We want to enable people to see that they are part of the whole, and that their individual
contributions create positive ripples within that whole.

Every tiny contribution elevates the collective by creating a positive current within a bigger
river, enabling that river to flow more seamlessly in the right direction—lifting life on Earth.

Every new project launched is a cause for celebration, a new drop of good that starts a
positive wave.

The platform is designed to make this connection **visible, tangible, and inspiring**.

---

## 2. Platform Architecture: The Infinite Loop of Goodwill

The OHM platform is an interconnected ecosystem architected as an **infinite elevating cycle**.

The user flow is designed to seamlessly guide an individual from personal inspiration to
collective action, which in turn generates collective intelligence that flows back to inspire the
next, more impactful, individual action.

At MVP level, this is implemented primarily in the **frontend flows and data structures**.

---

## 2.1 The Project Lifecycle: From Spark to Archive

The core of the platform is the **project**, which follows a clear, four-stage lifecycle.

Use this lifecycle when reading the code snippets and watching the walkthrough.

### 1. Creation – *Global Good Project Creation (Form I)*

- A **Project Leader**, guided by their Mission, uses the Global Good Project Creation form
  to structure their idea.
- The form captures:
  - Project purpose.  
  - Logistics (where, when, how).  
  - Specific activities collaborators can join.
- Upon completion, the system automatically generates and publishes a **Project Invite Post**
  to the Feed.

### 2. Signup – *Volunteer Signup (Form I.A)*

- When a user clicks **“Join”** on a Project Invite, they are taken to the Signup Form.
- The form:
  - Presents a summary of the project.  
  - Requires the user to commit to at least **one specific activity**.
- This selection is crucial: it forms the basis of the **verification chain** for awarding
  Global Good Credits.

### 3. Collaboration – *The Project Hub*

- After signup, the user is added to the private **Project Hub** as a collaborator.
- The Hub is the command center for the project, including:
  - Project summary.  
  - Group chat.  
  - Participant lists.
- The Project Leader can:
  - Manage the team.  
  - Re-assign collaborators to different activities.  
  - These changes update the verification record used later in the impact report.

### 4. Impact & Verification – *Global Good Project Impact (Form II)*

- After completion, the Leader fills out the **Global Good Project Impact** form.
- Key elements:
  - Attendance verification (confirming participation against the activity roster).  
  - Robust verification mechanisms (examples for future implementation):
    - Unique QR code check-ins for in-person events.  
    - Automated logging for online/remote participation.
- Submitting this form triggers:
  1. A **Project Impact Post** published to the Feed.  
  2. Archiving of the project as a permanent, curated **Project Card** in the Living Library.

---

## 2.2 The Feed: The River of Global Good

The **Feed** is the platform’s social heart, designed to foster connection and inspire action.

In the MVP, Feed-related components should reflect this structure.

### Feed Tabs

- **The River**  
  - Main feed: a single, clean, vertical stream showing all post types.  
  - Used for holistic discovery and connection.

- **Opportunities**  
  - Action-oriented feed.  
  - Shows only **Project Invite Posts**.  
  - Fully customizable:
    - Filters by location.  
    - Filters by format (in-person, remote, online).

### Post Types

The Feed supports three uniform post types:

1. **Project Invite Post**
   - System-generated call to action to join a new project.
   - Created automatically from the Project Creation form.

2. **Project Impact Post**
   - User-curated summary of a completed project’s success.
   - Acts as a gateway to the full Project Card in the Living Library.

3. **Project Story Post**
   - Personal, social-media-style post from any verified project participant
     (leader or collaborator).  
   - Can only be created after the official Impact Post is live.  
   - Shares the human, narrative side of the project.

---

## 2.3 The Living Library: The Collective Repository

The **Living Library** is the permanent repository of the collective’s wisdom and success.

- Every completed project becomes a **Project Card**.
- A Project Card contains:
  - Full project plan.  
  - Impact narrative.  
  - Curated media.  
  - Key insights gathered from the Impact Form.

All Project Cards and Story Posts link back to this definitive record, completing the cycle from
individual action to collective, shared intelligence.

### Project Duplication

The Library is the engine for the **“infinite growth cycle.”**

- Each Project Card includes a **“Use as Inspiration”** button.
- This allows a user to duplicate a successful project’s structure.
- Result: proven successes feed directly back into the creation of new individual actions.

---

## 2.4 My Global Good: The Individual in the Collective

**My Global Good** is the user’s personal space, with a crucial distinction between:

- **Public management / storytelling**, and  
- **Private command center / tools.**

### Public View

A clean, single-column showcase designed to inspire visitors.

Visitors can:

- Follow the user to see future activity.  
- Message the user to connect directly.  
- Join any **active projects** the user is currently leading.  
- Explore the user’s impact through three tabs:
  - **Impact Resume**  
  - **Portfolio**  
  - **Story**

Each project links back to the **Living Library**.

Additional future feature:

- **Set Notifications** – allow visitors to subscribe to alerts when a specific user launches
  a new project.

### Private View – “My Suite”

The user’s **command center** with a persistent left-hand navigation sidebar.

#### Navigation Links (conceptual)

- **Inspire Me** – the AI-powered launchpad for discovering the next act of goodwill.  
- **Current Project** – dashboard for managing any project the user is currently active in
  (as leader or collaborator).  
- **Edit Impact Resume** – tools (with AI assistance) for shaping the public-facing narrative.  
- **My Bookmarks** – saved posts for future inspiration.  
- **My Community** – manage Followers, Following, and notification alerts.  
- **Account Settings** – profile and security management.

#### Primary Tabs

- **Impact Resume** – living narrative of purpose-led impact.  
- **Portfolio** – visual grid of completed projects.  
- **Story** – collection of personal, text-based story thumbnails.

---

## 2.5 AI for Advancement of Global Good

The **AI Guide** is the intelligence layer that transforms the platform into a **self-evolving
ecosystem**, powering the infinite loop.

### Taxonomy & Data Purity

From launch, the platform uses a curated, internal taxonomy for all tags:

- Project types, causes, skills, locations, etc.
- Ensures all captured data (from project creation, participation, and impact forms) is:
  - Structured.  
  - Clean.  
  - Ready for machine learning.

### “Inspire Me” Hub

The AI acts as a proactive partner:

- Analyses:
  - The user’s unique contributions and history.  
  - Collective intelligence from the Living Library.
- Provides tailored suggestions for:
  - Collaborations to join.  
  - Projects to create.  
  - Learning and evolution paths.

### Continuous Advancement: The Infinite Growth Cycle

1. **Inspire Me** – AI synthesises collective wisdom + personal contribution to inspire an
   individual.
2. **Action** – individual creates or joins a project, generating new data.
3. **Completion & Data Capture** – project impact and learnings are captured in a structured
   way.
4. **Collective Learning** – new data is absorbed by the system, enriching the Living Library
   and the AI.
5. **Inspire Me (again)** – enhanced intelligence provides new, higher-leverage inspiration,
   starting the cycle anew.

---

## 2.6 User-to-User Messaging

Beyond group chat within each Project Hub, the MVP includes **direct messaging**:

- Any two users can communicate privately, one-on-one.  
- Users can initiate a message from another user’s **public profile**.

Purpose:

- Enable deeper connections and trust.  
- Allow people to:
  - Discuss potential collaborations before creating a formal project.  
  - Ask questions.  
  - Build the social fabric of the goodwill community.

---

## How to Use This Plan with the MVP Code & Walkthrough

- **Watch the MVP walkthrough video** to get a feel for flows and screens.  
- **Browse the code snippet PDFs** in `docs/` to see how individual pages/components are
  implemented.  
- Use this **MVP Development Plan** as the narrative and structural map:
  - Sections 2.1–2.6 correspond roughly to:
    - Project creation, signup, and hub.  
    - Feed & Library views.  
    - My Global Good area.  
    - AI entry points (“Inspire Me”).  
    - Messaging components.

As the implementation evolves, this document should be updated to reflect **what actually
exists** in the code and UI, and to note which parts are still conceptual / to be built.
