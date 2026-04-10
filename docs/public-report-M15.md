# **PUBLIC REPORT: OLI — MODULE 15 (PRODUCT DEVELOPMENT & PMF ASSESSMENT)**

---

## 1. EXECUTIVE SUMMARY

This report describes **Module 15** of **OLI (Optimized Lead Intelligence)**, an AI-assisted B2B platform for small and medium-sized retail and service businesses in Brazil. While earlier modules focused on **market research** (Module 13) and on **building a working MVP** (Module 14), Module 15 concentrated on **product development** and **product–market fit (PMF)**: documenting how the platform should scale and operate safely, and validating value with **real businesses** through structured pilots.

OLI is today a **functional product**: teams can **authenticate**, use a **web dashboard** to run day-to-day operations, and rely on a **backend** that executes **conversational workflows** tied to **WhatsApp** and **AI-assisted replies** configured per business.

The **next and final module** (Module 16) is framed as the **conclusion of the venture track**: presenting OLI as a **solid, coherent solution** and delivering a **pitch to a board of professors** that states the **original goal**, **what was achieved** across the project, and **how the work may continue** after graduation—without overstating commitments.

---

## 2. PROJECT CONTEXT AND JOURNEY

### 2.1 What OLI Is

OLI helps small businesses **answer WhatsApp faster**, **organize leads and conversations**, and **reduce repetitive manual work** in customer interactions. The design assumption is that Brazilian SMBs already live on WhatsApp; the platform **augments** that habit rather than asking owners to replace it with an unfamiliar stack overnight.

### 2.2 How the Academic Project Evolved

- **Module 13** established **strategic grounding**: interviews, personas, competitive context, and a clear view of pain points in segments such as beauty, clinics, and neighborhood services.
- **Module 14** turned that insight into a **working proof of concept**: inbound WhatsApp traffic, AI-supported dialogue, persistence of leads and context, and a path toward a credible demo.
- **Module 15** treated OLI as a **pilot-stage product**: multiple businesses on a shared platform, written expectations for **security**, **reliability**, and **cost**, and a **formal PMF exercise** (hypotheses, pilots, synthesis).

This progression mirrors how real ventures move from **idea** to **build** to **evidence-based iteration**.

---

## 3. PROBLEM AND OPPORTUNITY

Small retailers and service providers often lose revenue because **first responses arrive too late**, especially outside business hours, or because **no single place** holds threads, notes, and follow-ups. Staff juggle phones, spreadsheets, and memory.

OLI targets that gap with a **tenant-specific dashboard** and **automated first-line handling** on WhatsApp, while keeping humans in the loop where trust and exceptions matter. The opportunity is strongest where **appointment-driven** businesses (aesthetics, wellness-adjacent clinics, pet services, and similar) already depend on messaging for bookings and questions.

---

## 4. CURRENT PRODUCT STATUS

### 4.1 What Runs Today

The platform is **operational** for demonstration and pilot use:

- **Access control:** Each business (tenant) has its own space; staff sign in and only see **their** organization’s data.
- **Dashboard:** A web application where teams monitor activity, open **contacts** and **conversation history**, manage **appointments**, maintain a **services catalog** (so the assistant can stay aligned with what the business actually offers), and adjust **how the AI speaks and behaves** (tone, hours, instructions).
- **Backend and workflows:** Server-side logic receives messages from the messaging channel, maintains conversation state, calls AI when appropriate, stores structured data, and sends replies back through the same channel.

Module 15 **did not** replace this stack; it **clarified**, **documented**, and **stress-tested** it with real users so that growth and grading both rest on something concrete.

### 4.2 Who It Is For (Pilot Focus)

Pilot businesses were chosen from priority segments—**aesthetics**, **clinic-related wellness**, and **pet services**—with an interest in WhatsApp-heavy operations and willingness to give structured feedback over several weeks.

---

## 5. MODULE 15 — WHAT WAS DONE

### 5.1 Architecture and Data Picture

The team described how OLI should support **many customers on one deployment**: a shared technical base with **strict separation** of each tenant’s data, diagrams for major components, and data models covering entities such as businesses, users, leads, conversations, and messages. The intent is to make future engineering and onboarding **predictable**, not ad hoc.

### 5.2 Security, Privacy, and Channel Reality

Documentation addressed **how access is enforced**, how **credentials and integrations** should be handled, and how to think about **abuse and dependency** on a third-party messaging channel—topics that matter for both ethics and continuity. The level of detail is appropriate for a **pilot**, not for a full enterprise audit, but it sets expectations for Module 16 and beyond.

### 5.3 Reliability, Performance, and Cost Awareness

The module defined **internal targets** for responsiveness and availability and outlined how **cost per customer** should stay understandable as usage grows (especially where AI usage scales with message volume). The goal is to avoid discovering economics only after scaling.

### 5.4 Integrations and Onboarding

Written material describes how **WhatsApp-style** traffic enters the system, how **outbound** messages and delivery feedback work at a logical level, and how a **new pilot** is brought online technically—so onboarding is repeatable, not purely heroic support.

### 5.5 Product–Market Fit Method

Module 15 formalized **testable hypotheses**: whether businesses perceive **faster response and usefulness**, whether they show **willingness to pay** at a plausible SMB price, whether they **activate** within a short window after go-live, whether they **keep using** the product during the test, whether **lead handling** improves in their view, and whether **onboarding** is feasible without excessive hand-holding.

A **multi-week pilot** with **three businesses** followed a planned rhythm (expanded below). Qualitative notes were synthesized into **themes** (value, onboarding friction, trust in the AI, control, concerns about the messaging channel) and a **short list of prioritized improvements** balancing impact and effort.

### 5.6 Pilot methodology (at a glance)

Each pilot followed the **same cadence** so results could be compared. There was an **onboarding or kickoff conversation** at the start to align expectations, collect baseline impressions, and walk through setup. Around **the middle of the active test window**, a **short check-in** captured early friction, sentiment, and any blockers. At the **end**, a **closing interview** explored value, pricing perceptions, what would make them continue using the tool, and improvement ideas. Immediately afterward, participants completed a **brief structured survey** (Likert-style items plus a few closed questions) so some signals could be aggregated alongside the interview notes. **Roles and segments** are described in this report at a high level; **quotes and attributions** in the underlying coursework materials are kept **anonymized** (e.g. by role and segment) to protect privacy. The emphasis is on **qualitative depth and consistency of process**, not on a large statistical sample.

### 5.7 Closure artifacts

The module ends with a **consolidated picture** for evaluators: an index of deliverables, a **prioritized engineering backlog** informed by pilots, and **high-level** views of how the system might evolve after the course—without pretending those plans are already executed.

### 5.8 Documentation available for evaluation

For grading and review, Module 15 produced **written artifacts** (submitted through the course channels) that complement this public report. Together they cover: the **module project plan**; **architecture and tenancy** descriptions with diagrams; **data / integration models**; **security and privacy-oriented design**; **stability, performance, and cost** expectations; **API and channel integration** documentation and onboarding guidance; **PMF hypotheses and testing plan**; **synthesized customer feedback** from pilots; **technical debt and prioritization**; **migration/refactoring and evolution** views at a high level; a **detailed submission index** tying deliverables together; and **this public report** as the outward-facing summary. No single document replaces the others: the public report states outcomes at a readable level, while the rest supports traceability and depth.

---

## 6. RESULTS, LEARNINGS, AND LIMITATIONS

### 6.1 Results and learnings

**Value:** Pilots consistently linked benefit to **speed of first reply** and **fewer missed opportunities** on WhatsApp, including evenings and weekends.

**Engagement:** Participants reached **meaningful use** within the intended timeframe; there was **no unplanned dropout** during the pilot window.

**Onboarding:** Getting live typically took on the order of **a week** when one engaged contact owned the process. Pain clustered around **connecting WhatsApp** and varying **digital comfort**—signals to invest in **clearer guided steps** and lightweight tutorials rather than only live support.

**Pricing narrative:** Reactions were **more positive** when the product was compared to **hiring or stretching staff time** than when it was implicitly compared to **large hospital or enterprise software** pricing—a lesson for how the offer is **framed** commercially later.

**Product direction:** Requests recurred for **stronger alignment** between AI answers and the **official service catalog**, **better visibility** when the AI should step back for a human, and **notifications** so owners notice important leads quickly. These themes now anchor the near-term product story.

Overall, evidence supports **continuing** with the current segment focus and core value proposition while **tightening** onboarding, **control**, and **truthfulness** of automated replies.

### 6.2 Limitations and scope of evidence

The pilot cohort is **small by design** (three businesses), which is appropriate for a **deep, supervised** academic exercise but **not** for statistical generalization to the whole SMB market. Findings are **predominantly qualitative**, supported by structured interviews and a short survey—not by a separate, fully instrumented analytics product with published dashboards for every hypothesis. Some **numeric** indicators (response times, volumes, activation dates) may exist in the system or in notes, but this public report does **not** claim a complete, automated metrics suite; strengthening **measurement and reporting** is part of realistic **next steps**. Finally, conclusions reflect **a specific moment** in the product lifecycle; different segments, seasons, or channel policy changes could shift outcomes. These limits are intentional transparency for readers and for the **board evaluation** in Module 16.

---

## 7. PRIORITIES MOVING FORWARD (HIGH LEVEL)

Without turning this report into an internal specification, the next wave of work—whether inside Module 16 or afterward—naturally clusters around:

- **Trust and safety:** Verifying tenant isolation end-to-end and monitoring message delivery health.
- **User control:** Letting staff **pause automation** per conversation when promotions or exceptions apply.
- **Grounding:** Reducing cases where the assistant cites prices or facts that are not in the business’s configured catalog.
- **Onboarding experience:** Checklists or short guided content so the first week is smoother.
- **Exports and continuity:** Simple ways for businesses to **take their contact data** when needed, in line with good privacy practice.

Longer-term ideas—such as abstracting the messaging channel or adding new integrations—remain on the horizon once the core demo and narrative are airtight.

---

## 8. MODULE 16 — CONCLUSION, SOLID SOLUTION, AND BOARD PITCH

Module 16 is designed as **one integrated closing period**, not a sequence of hidden sub-phases. Its purposes are:

1. **Solid solution:** Polish OLI into a **coherent, demo-ready** whole that a non-specialist committee can understand: sign-in, dashboard, a realistic conversation flow, and a credible explanation of **what happens under the hood** at a conceptual level.
2. **Board pitch:** A structured presentation for **professors** that covers:
   - The **original project goal** and how it evolved from research to product.
   - **Concrete outcomes** through Module 15 (working software, pilots, documentation, learnings).
   - **Honest options for continuation**—product iteration, go-to-market experiments, technical hardening, or handoff—without promising a roadmap the team cannot sustain.

Success is measured by **clarity**, **integrity of the demo**, and **intellectual honesty** about achievements and limits.

---

## 9. CONCLUSION

Module 15 positioned OLI as more than a student prototype: a **pilot-informed product** with documented architecture, operational expectations, integration clarity, and **real customer evidence**. The system **runs today** as an authenticated, dashboard-centered platform with backend workflows suitable for academic demonstration and external conversation.

**Module 16** will **consolidate** that outcome into a **final, defensible solution** and **communicate** it through a **board-facing pitch**—closing the venture module while leaving a readable path for what may come next.

---

Institution: [Inteli — Instituto de Tecnologia e Liderança](https://www.inteli.edu.br)
