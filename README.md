# Hey, I'm Dev Krishan 👋

**Product Manager · AI-first builder · Prototype-driven thinker**

I build products at the intersection of AI and real user pain. My work lives in live prototypes, shipped features, and measurable outcomes — not slide decks. Every product decision I make is grounded in discovery, shaped by data, and pressure-tested against the people who actually use it.

📎 **Full portfolio, case studies & prototypes → [linktr.ee/devkrishan.r](https://linktr.ee/devkrishan.r)**

---

## 🚀 SparrowGenie — AI RFP Automation (Flagship Product)

**Role:** Sole PM · End-to-end ownership from 0 → 1

SparrowGenie is SurveySparrow's AI-first RFP automation product. I owned discovery, roadmap, and delivery.

**What I shipped:**
- AI first-draft generation → improved RFP completeness from **0% to 80–90%**
- Confidence scoring + continuous-learning feedback loop (reviewer edits improve retrieval quality)
- Compliance-aligned design: no customer data used in base model training — helped unblock enterprise security-sensitive deals
- SOC 2 Type 2, ISO 27001, and GDPR readiness requirements translated into product specs

**Results:**
- 🎯 Drove adoption from **0 → 100%** (40 teams across Sales, InfoSec, CS) in **3 months**
- ⚡ Reduced average RFP response time by **~60%**
- 📦 Delivered **5 major releases** across 20 sprints with 8 engineers and 2 designers

🔗 **[Try the live prototype → sparrowgenie.netlify.app](https://sparrowgenie.netlify.app/)**

---

## 🧠 Discovery Mind Maps — How I Think Before I Build

Before any prototype, I work the problem on a canvas. Each mind map turns a vague brief into a prioritized, role-indexed inventory of what to build — and what *not* to. The four below each fed directly into a shipped prototype or product surface.

### 🏠 Home Dashboard for General Users

**Problem.** General users (60–80% of the base) dig into individual proposals and RFPs just to know what's going on. Surface that on a home screen — using only existing features, simple engineering, and still land a wow factor.

**Breakdown.**
- 4 lenses: *avoiding deep navigation · aggregate visibility · early alerts · progress tracking*
- Crossed each against every actor (owners, collaborators, reviewers, assignees, viewers, guests) to map role-specific needs

**Findings.**
- Wow doesn't need new features → comes from recombining existing signals (comments, deadlines, deal values, question states, Genie answers) into role-aware widgets
- Output: prioritized, role-indexed widget inventory → fed into the [Home Dashboard prototype](https://aloha-jungle-69298189.figma.site/)

🔗 **[View the mind map →](https://whimsical.com/dev-s-workspace372/home-widgets-UaGV4vqeHVvFFagARoEfRG)**

---

### 📚 Content Upkeep — Knowledge Review Lifecycle

**Problem.** Knowledge content goes stale silently. Reviewers, owners, and viewers all need one shared signal — across content with very different shelf lives.

**Breakdown.**
- State machine: *Active · Pending Review · Reviewed · Expired*, with *Archived* as a side state (explicit Unarchive path back to Active)
- 3 review-schedule paradigms — **One-Time · Repeating · Evergreen** — stress-tested across multiple cycles to confirm the same states + transitions held

**Findings.**
- One state model covers three lifecycles → no per-type logic for users or engineers
- Every state is observable and actionable → shipped into the live Knowledge Hub on the [SparrowGenie prototype](https://sparrowgenie.netlify.app/)

🔗 **[View the mind map →](https://whimsical.com/dev-s-workspace372/content-upkeep-KeXYefijc7X3a2Yh8JD3pv)**

---

### 💬 SparrowGenie ↔ Slack Integration

**Problem.** Make SparrowGenie work natively in Slack — push updates *and* pull search — without permission chaos, duplicate accounts, or notification spam. Across every user state and channel type.

**Breakdown.**
- Workspace cardinality call: Many:Many → **1:1** (with bring-your-own-workspace queued for later)
- Two clean capabilities: **Project Updates** (push) and **Search** (pull)
- User-state matrix (Non-Genie · Genie-not-installed · installed-not-connected · connected) + 3-layer permission model (Admin → Project → User, user-level overrides)
- Benchmarked against Guru's Slack bot to validate capability scope

**Findings.**
- 1:1 mapping kills permission tangles while leaving room to scale
- User-level priority over project-level → no notification spam without admin micromanagement
- Domain-allowlist + hub-scoping makes search safe in mixed-domain channels → shipped as part of the [SparrowGenie integrations track](https://sparrowgenie.netlify.app/)

🔗 **[View the mind map →](https://whimsical.com/dev-s-workspace372/slack-C29Kz72ND7L4TqTbJCXtvb)**

---

### 🔐 Sign Up & Login Flow — Internal vs External Users

**Problem.** One auth surface for wildly different users: internal vs external, new vs returning, single-account vs multi-account, invited vs uninvited. Every path has to dead-end into success — no wrong-door errors, no orphans, no duplicates.

**Breakdown.**
- Mapped every entry-state combination (account exists or not · single/multi · added/not · internal/external · SSO/OTP)
- Single state machine branching on email domain → routes to direct login, account picker, request-to-join, sign-up, or create-new

**Findings.**
- One unified flow serves every user state → smaller engineering surface, more personalized feel
- **Email-domain routing is the linchpin** — decides "join your org" vs "start a trial" before any click
- Output: full state diagram + working [Login Portal prototype](https://edit-plasma-21481919.figma.site/)

🔗 **[View the mind map →](https://whimsical.com/dev-s-workspace372/sign-up-login-flow-F3WstawyKHkjWbf1o8aLV)**

---

## 🧩 Working Prototypes — My Living Specs

Beyond the mind-mapped flows above, I build fully interactive prototypes for individual feature surfaces. Engineering, design, sales, and leadership can open them in a browser and walk through end-to-end. The prototype *is* the spec — ambiguity gets resolved before sprint planning, not mid-sprint.

| Prototype | Link |
|-----------|------|
| 📊 Proposal Engagement Dashboard | [figma.site →](https://free-admin-57678777.figma.site/) |
| 🏠 Home Dashboard (alternate exploration) | [figma.site →](https://lovely-dairy-78049841.figma.site/) |
| 📤 Document Share Module | [figma.site →](https://flat-adjust-93584589.figma.site/) |
| ✅ Tasks Module | [figma.site →](https://dimly-chroma-71980777.figma.site/) |
| 🔍 Search | [figma.site →](https://flaky-banana-45401484.figma.site/) |
| 🧠 Knowledge Hub Settings | [figma.site →](https://gutter-laurel-53087744.figma.site/) |
| 👥 Invite Team as Trial User | [figma.site →](https://scuff-kernel-10401746.figma.site/) |
| ✨ Genie Shortcut | [figma.site →](https://spiral-scrum-54353724.figma.site/) |
| 📋 Balsamiq Wireframe | [balsamiq.cloud →](https://balsamiq.cloud/sfwp3yg/p4s7chj) |

---

## 📦 Third-Party Integrations — Full Lifecycle Ownership

**At SurveySparrow**, I owned the integration track end-to-end across HubSpot, Salesforce, Intercom, Freshdesk, and Slack.

- Ran competitor teardowns of category leaders — mapped UX patterns, auth models, and gaps
- Designed the full OAuth flow, partial-state handling, leave-screen behaviour, and background fetch logic myself
- Made the key pre-build architecture call: account-level vs user-level integration → avoided a costly rewrite
- Built parameterised connection logic across all 5 integrations (not hard-coded per tool)
- Post-launch: added granular scoping (content categories, ordering, bulk ops) based on usage data → lifted post-integration engagement

> Discovery for the Slack integration is documented in detail in the [Discovery Mind Maps section](#-sparrowgenie--slack-integration) above.

---

## 📚 Knowledge Base — AI-Assisted at Scale

🔗 **[support.sparrowgenie.com/hc/en](https://support.sparrowgenie.com/hc/en/)**

Generated 50+ knowledge articles covering all 5 major SparrowGenie features in **2 days**, using AI with strict human governance. Support and self-serve docs shipped *alongside* the product — not 6 weeks after. Earned high CSAT scores and leadership appreciation.

---

## 🤖 How I Use AI (Actually)

AI is a core part of my PM craft — not a buzzword I drop in interviews. Here's what that looks like in practice:

| What | How | Outcome |
|------|-----|---------|
| **Prototyping** | Claude, Cursor, Figma Make, Balsamiq AI | ~85% reduction in prototyping cycle (1 week → 1 day per feature) |
| **Documentation** | Claude Cowork + governance | 50+ knowledge articles for 5 major features shipped in 2 days |
| **Discovery & synthesis** | LLM-assisted teardowns, persona definition, PRD drafting | Days of manual synthesis compressed into hours |
| **Internal tooling** | Claude Code + Google App Scripts | Bespoke lunch distribution system with automated logging for non-technical staff |

> My philosophy: AI is only as useful as the operator's judgment. I direct it with sharp prompts, review every output critically, and treat it as a force multiplier — not a replacement for my own thinking.

<img width="1536" height="1024" alt="How I ship with AI" src="https://github.com/user-attachments/assets/ce36328a-43b6-4039-9241-70a43d5df616" />

---

#### 🛠️ Work History

**Product Manager — SurveySparrow** *(May 2022 – Apr 2025)*
Building SparrowGenie + owning integrations, discovery, and cross-functional delivery.

**Associate Product Manager / Engineer — Cisco** *(Sep 2020 – Apr 2022)*
- Led a 3-engineer POC for remote server temperature monitoring
- Reduced partner integration time by **66%** (3 hrs → 1 hr) via a cross-platform toolkit
- Cut support tickets by **50%** by owning end-to-end documentation for Domain Messaging Service
- Refactored legacy modules and closed **5 CVE-rated** security vulnerabilities in Cisco Meeting Server

---

## 🌱 Beyond the Job

- **ProductHood member** — active in peer-learning case-study huddles and product teardowns
- **Heartfulness Institute** — Event Coordinator & Visual Media Lead; led early planning of the Green Kanha initiative
- Heavy user of LLM-assisted product workflows: prototyping, synthesis, competitive analysis, documentation

---

## 📬 Let's Connect

🌐 [linktr.ee/devkrishan.r](https://linktr.ee/devkrishan.r) — portfolio, case studies, prototypes, certifications
