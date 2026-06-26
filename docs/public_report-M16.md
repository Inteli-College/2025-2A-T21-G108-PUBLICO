# **PUBLIC REPORT: OLI — COMPLETE PROJECT OVERVIEW (MODULES 13–16)**

---

## 1. EXECUTIVE SUMMARY

This report is the **final public document** of the OLI venture track at Inteli. It tells the full story of **OLI (Optimized Lead Intelligence)** — what the project is, why it exists, what was researched, built, tested, and presented across **four academic modules**, and how the work concluded in a board presentation to professors and evaluators.

OLI is an **AI-powered virtual receptionist** for small and medium-sized service businesses in Brazil. It works where these businesses already operate: **WhatsApp**. When a client sends a message — asking about a service, checking prices, or trying to book an appointment — OLI can respond immediately, even when the owner is busy or the shop is closed. Behind the scenes, a **web dashboard** lets the business owner and their team see conversations, manage appointments, configure how the assistant behaves, and step in when a human is needed.

The project did not start as a product. It started as a **research question** and grew step by step across **four modules**, each with a distinct purpose:

| Module | Focus | Central Question |
| ------ | ----- | ---------------- |
| **Module 13** | Market research and validation | *Is there a real problem worth solving?* |
| **Module 14** | MVP development | *Can we actually build this?* |
| **Module 15** | Product development and PMF assessment | *Do real customers find this valuable?* |
| **Module 16** | Consolidation, pitch, and business model | *Can we present this as a coherent venture?* |

By the end of Module 16, all four questions had been answered — with evidence, not assumptions.

This document is written for **any reader** — professors, potential partners, future team members, or anyone curious about the project — without assuming technical knowledge. It focuses on **what was done, why it mattered, and what was learned** across the entire journey from first interview to final pitch, rather than on code or infrastructure details.

---

## 2. WHAT OLI IS

### 2.1 In Plain Terms

Imagine a small beauty salon in São Paulo. The owner, Maria, is doing a client's hair when three WhatsApp messages arrive: someone asking about manicure prices, someone wanting to book for Saturday, and someone who wrote at 10 p.m. last night and never got a reply. Maria cannot stop mid-service to answer every message. By the time she responds, the Saturday slot may already be taken and the late-night lead may have gone to a competitor.

**OLI exists to solve that everyday problem.**

OLI is a digital assistant that sits on the business's WhatsApp number. It reads incoming messages, understands what the client wants, replies in a natural and friendly tone, and can book appointments directly into the business's calendar. All of this happens automatically — but the owner always retains control. From a dashboard on their computer or phone, they can read every conversation, pause the assistant when they want to handle a chat personally, manage their list of services and prices, and see today's appointments at a glance.

The design philosophy is simple: **meet businesses where they already are**. Brazilian small businesses do not want to abandon WhatsApp and learn a complicated new system. They want WhatsApp to work better for them — faster replies, fewer missed opportunities, and less repetitive work.

### 2.2 What OLI Is Not

OLI is not a replacement for the business owner or their staff. It is not a mass-messaging tool for spamming clients. It is not enterprise hospital software priced out of reach for a neighborhood salon. It is not a chatbot that gives generic answers disconnected from what the business actually offers.

OLI is a **first line of contact** — intelligent, configurable, and designed to hand off to a human whenever the situation requires personal attention, trust, or an exception to the usual rules.

### 2.3 The Name

**OLI** stands for **Optimized Lead Intelligence**. In practice, "lead" means any person who reaches out with interest — a potential client asking about a service, checking availability, or trying to schedule. "Intelligence" refers to the assistant's ability to understand intent, remember context within a conversation, and respond appropriately rather than with canned scripts.

---

## 3. THE PROBLEM OLI ADDRESSES

### 3.1 A Communication Gap, Not a Technology Gap

Small service businesses in Brazil — beauty salons, aesthetic clinics, pet grooming shops, wellness practices, and similar establishments — are not lacking phones or WhatsApp accounts. They use these tools every day. The problem is **operational**:

- **Slow first replies.** When the owner is serving a client, at lunch, or off-hours, messages sit unanswered. Clients who do not hear back quickly often move on.
- **No single place for everything.** Conversations live on WhatsApp, appointments may be in a paper book or a separate app, client notes are in someone's memory, and follow-ups depend on whoever remembers to send them.
- **High no-show rates.** Without timely confirmations and reminders, clients forget appointments — especially in segments like manicures and aesthetic procedures where no-show rates can reach 30–40%.
- **Repetitive manual work.** The same questions — "How much is it?", "Do you have time on Friday?", "Where are you located?" — are answered over and over by hand.

### 3.2 Why Existing Solutions Fall Short

Many customer relationship tools exist, but they often fail this market for predictable reasons:

- They are **expensive**, priced for larger companies.
- They are **disconnected from WhatsApp**, forcing businesses to change how they communicate.
- They are **complex**, requiring training and dedicated staff to operate.
- They do **not speak Portuguese** or understand Brazilian business habits well enough.

OLI was designed specifically for businesses that live on WhatsApp, have limited time and budget, and need something that **augments** their current workflow rather than replacing it overnight.

### 3.3 Who Feels This Pain Most

Module 13 research — through field interviews, persona development, and pain point mapping — identified three representative customer profiles. These were not invented in a classroom; they were derived from real conversations with business owners:

1. **Health and beauty service providers** — clinics, salons, and aesthetic practices where scheduling, confirmations, and client records are daily challenges. Interview evidence showed 100% manual WhatsApp scheduling even when clinic software was already in use.
2. **Neighborhood small business owners** — local shops and service providers with recurring clients, inventory concerns, and no-show rates reaching 30–40% for short services like manicures.
3. **Creative and professional enterprises** — studios and agencies that need visibility, reliability, and better coordination. WhatsApp is less central here, but manual processes and fragmented tools remain a burden.

The competitive analysis in Module 13 confirmed that existing tools (salon systems, clinic platforms, booking apps) cover basic scheduling but fail on **WhatsApp integration**, **affordable AI automation**, and **simplicity for small teams**. The strongest product–market fit signals came from the **first two profiles**, especially businesses where appointments drive revenue and WhatsApp is the primary client channel.

---

## 4. THE PROJECT JOURNEY

The venture followed a path that mirrors how real startups move from idea to evidence: **research, build, test, consolidate, present**. Each module built directly on the previous one — nothing was wasted, and nothing was assumed without evidence.

---

### 4.1 Module 13 — Market Research and Validation

Module 13 was the **starting point** of the entire venture. Before a single line of product code was written, ten weeks were dedicated to understanding the market, talking to real business owners, analyzing competitors, and defining what a first version of the product should look like.

The module did not produce software. It produced **evidence** — and that evidence shaped every decision in Modules 14, 15, and 16.

#### Sprint 1 — Project foundation

The module opened with a master project plan defining the strategic direction: an AI-powered automation platform targeting small retail and service businesses in Brazil, with a focus on WhatsApp integration, affordable pricing, and enhancement of existing workflows rather than system replacement.

#### Sprint 2 — Field research and competitive analysis

This sprint brought the project into the real world through **direct conversations with business owners**.

Three in-depth interviews were conducted across different segments:

- **An aesthetics and dermatology clinic** — using clinic software for over two years but still scheduling 100% manually via WhatsApp. Staff juggled CRM, WhatsApp, spreadsheets, and paper records daily. The owner wanted a WhatsApp assistant for pre-triage and appointment confirmations, with targets of 30% no-show reduction and 40% faster confirmation times.
- **A beauty salon** — using a salon-focused system for over 20 years, but with poor search and integration. Scheduling was fully manual, with 30–40% no-show rates for manicures. Inventory of 200+ hair color products was tracked by hand, leading to stockouts. The owner wanted automated confirmations, waitlist management, and inventory alerts.
- **A media production house** — using project management tools but lacking predictive insights. Manual file transfer and backup processes were unreliable. The team wanted AI risk detection and automated file management, with targets of 48-hour advance alerts and 95% on-time delivery.

Across all three interviews, a consistent pattern emerged: **WhatsApp is the operational hub** for customer communication. Records are fragmented. Scheduling is manual and error-prone. No-shows waste capacity. Existing software is rigid, poorly integrated, or too expensive.

A **competitive analysis** was also conducted, benchmarking existing tools (scheduling platforms, salon systems, clinic software, project management tools) against the needs of three customer segments. The analysis found that most solutions cover basic scheduling but lack **WhatsApp-first integration**, **predictive automation**, **affordable pricing for small businesses**, and **compliance designed for Brazilian regulations (LGPD)**.

#### Sprint 3 — Personas and pain point mapping

Based on interview insights and secondary research, three **customer personas** were defined to guide all future product decisions:

1. **Health and beauty service provider** — clinics, spas, and wellness establishments focused on maximizing bookings, reducing no-shows, and maintaining compliant client records.
2. **Neighborhood small business owner** — local salons and service shops with recurring clients, inventory concerns, and high no-show rates.
3. **Creative and professional enterprise** — studios and agencies needing visibility, reliability, and better coordination across projects.

A dedicated **pain point document** consolidated recurring challenges across all segments:

- Manual, repetitive workflows consuming staff time
- High no-show rates directly impacting revenue
- Fragmented systems with poor integration between scheduling, WhatsApp, and records
- Limited visibility into business performance metrics
- Compliance and data privacy concerns (LGPD)
- Lack of proactive or predictive tools

The strongest opportunity was identified in the **first two personas** — businesses where WhatsApp drives revenue and appointments are the core transaction.

#### Sprint 4 — MVP definition and technology direction

With research complete, the team defined what the **first version of the product** should do. The MVP was scoped around four core areas:

- **WhatsApp AI assistant** — natural conversations in Portuguese, intent recognition, automated scheduling, and smart confirmations/reminders
- **Lead management** — automatic lead capture from conversations, follow-up sequences, and integration with existing business tools
- **Business dashboard** — real-time view of conversations, appointments, and basic performance metrics
- **Automation workflows** — lead processing, appointment confirmations, and inventory alerts tied to bookings

A preliminary **technology direction** was also documented, selecting tools suited for WhatsApp integration, AI conversation management, and affordable operation — laying the groundwork for Module 14 development.

#### Sprint 5 — Public research report

Module 13 closed with a comprehensive public report summarizing the market analysis, strategic opportunity, customer validation, solution design, business model concepts, development roadmap, and risk assessment. This document served as the **strategic handoff** to Module 14.

#### What Module 13 proved

| Finding | Implication for the product |
| ------- | --------------------------- |
| WhatsApp is the hub of daily operations | The product must be WhatsApp-first, not an afterthought |
| Businesses prefer integration over replacement | OLI should augment existing habits, not force migration |
| No-shows and slow replies cost real revenue | Speed of first reply and appointment management are core value drivers |
| Willingness to pay: R$50–200/month | Pricing must feel affordable compared to staff time, not enterprise software |
| All interviewed businesses wanted pilots | Genuine demand existed before any product was built |
| International tools lack Brazilian focus | A locally developed, Portuguese-first solution has a natural advantage |

Module 13 answered the question: *Is there a real problem worth solving?*  
The answer was yes — and it defined **who** the product is for, **what** it should do first, and **why** it would matter.

---

### 4.2 Module 14 — Building the First Working Version

Module 14 was the **entrepreneurship and MVP development** phase — ten weeks focused on turning the research into something real that could hold a conversation on WhatsApp and capture leads.

**What was done:**

**Early infrastructure and integration**

The first milestone was connecting the essential pieces: a messaging channel (WhatsApp), an AI service capable of understanding and responding in Portuguese, a system to manage conversation flows, and a database to store leads. All of this was set up on affordable, self-hosted infrastructure — a deliberate choice to keep operational costs low and suitable for small business pricing.

**WhatsApp conversational assistant**

The core product emerged: an assistant that could receive WhatsApp messages, maintain conversation context across multiple messages, extract structured information (name, interest, availability, intent), and reply naturally. The assistant could distinguish between different types of requests — booking a consultation, asking about prices, asking clarifying questions, or expressing uncertainty — and adapt its responses accordingly.

**Landing page and public presence**

A public-facing website was created at OLI's domain, with content in Portuguese and English. It explained the problem, how OLI solves it, and included a lead capture form connected to the same backend workflows. This gave the project a credible market presence beyond a technical demo.

**Performance and reliability work**

Throughout the module, the system was refined for faster response times, better memory management during conversations, improved error handling, and more reliable data storage. By the end, the proof of concept demonstrated strong success rates in lead capture with responsive performance at an operational cost appropriate for the target market.

**Business planning**

A preliminary business plan was drafted, outlining the value proposition, target segments, revenue model (subscription-based SaaS), and market entry strategy through pilot programs with beauty salons, clinics, and wellness centers.

**What was learned:**

- AI-powered automation **can be built cost-effectively** for the SMB market using modern tools and self-hosted infrastructure.
- **Structured data extraction** from natural conversations works reliably enough for real-world use.
- A **WhatsApp-first approach** is validated for the Brazilian market.
- The proof of concept was ready for the next phase: **testing with real businesses**.

Module 14 answered the question: *Can we actually build this?* The answer was yes — OLI went from concept to a production-ready proof of concept.

---

### 4.3 Module 15 — Testing with Real Businesses

Module 15 shifted focus from **building** to **proving value**. The question was no longer "does it work?" but "does it matter to real customers, and would they pay for it?"

**What was done:**

**Platform evolution toward a multi-business product**

The single-demo setup from Module 14 was reimagined as a platform where **multiple businesses could coexist**, each with their own isolated space, users, and data. Architecture diagrams, data models, and design documents described how this would work — covering businesses, users, conversations, messages, appointments, services, and clients.

**Security, reliability, and integration documentation**

Written materials addressed how access control works, how sensitive credentials should be handled, what happens if WhatsApp policies change, and what internal targets exist for responsiveness and uptime. Integration guides described how new pilot businesses would be onboarded step by step.

**Structured product–market fit testing**

The team formalized **testable hypotheses**:

- Do businesses perceive faster responses and find the assistant useful?
- Would they pay at a plausible small-business price?
- Can they activate within a short window after setup?
- Do they keep using it during the test period?
- Does lead handling improve in their view?
- Is onboarding feasible without excessive hand-holding?

**Three-business pilot program**

Three businesses participated in a multi-week pilot — one in aesthetics, one in clinic-adjacent wellness, and one in pet services. Each followed the same rhythm:

1. **Onboarding conversation** at the start — aligning expectations and walking through setup.
2. **Mid-pilot check-in** around week two — capturing early friction and sentiment.
3. **Closing interview** at the end — exploring value, pricing perceptions, and improvement ideas.
4. **Brief structured survey** — aggregating some signals alongside interview notes.

Participants were kept anonymous in documentation (identified by role and segment only).

**What was learned from pilots:**

| Theme | Finding |
| ----- | ------- |
| **Value** | Pilots consistently linked benefit to faster first replies and fewer missed WhatsApp leads, especially after hours and on weekends. |
| **Engagement** | All three participants reached meaningful use within the intended timeframe; there was no unplanned dropout. |
| **Onboarding** | Getting live typically took about a week when one engaged contact owned the process. Main friction: connecting WhatsApp and varying levels of digital comfort. |
| **Trust and control** | Owners wanted to read full conversation threads, annotate contacts, and pause the assistant when promotions or exceptions applied. |
| **AI accuracy** | Answers were trusted when prices and services matched the configured catalog; mismatches caused concern. |
| **Pricing framing** | Reactions were more positive when compared to hiring part-time help than when compared to large hospital software. |
| **WhatsApp dependency** | Ban and policy risk remained an explicit concern; reassurance about reactive-first behavior was important. |

**Top improvement priorities identified:**

1. Notifications when important leads arrive.
2. Easy "pause AI" or human takeover per conversation.
3. Stricter alignment between assistant answers and the official services catalog.
4. Clearer onboarding guides and checklists.
5. Simple contact data export for business continuity.

Module 15 answered the question: *Do real customers find this valuable?*  
The answer was yes, with clear conditions — onboarding must improve, control must be visible, and answers must stay grounded in what the business actually offers.

---

### 4.4 Module 16 — Bringing It All Together

Module 16 was the **final module** — the closing chapter of the venture track. It had two parallel goals: finish the product into a coherent, demo-ready whole, and present the venture to a board of professors with a clear business story.

**Sprint 1 — Planning**

The module opened with a project plan defining the work across five sprints: platform consolidation, pitch preparation, business model documentation, rehearsal and version freeze, and the final public report (this document).

**Sprint 2 — Platform consolidation**

The most significant technical evolution of the entire project happened here. The earlier workflow-based prototype (built with visual automation tools) was **migrated to a unified, full-code application** called **oli-app**. The reasons were practical:

- Multiple businesses on one platform required architecture that visual tools could not support cleanly.
- A coded application is easier for developers to collaborate on and maintain.
- Modern AI development tools work better with structured code than with visual flow diagrams.

The consolidated platform connected everything end to end:

- **User accounts and login** — each business signs in and sees only their own data.
- **Database** — all business information stored securely with strict separation between tenants.
- **WhatsApp integration** — incoming messages flow into the system and replies go back through the same channel.
- **AI assistant** — configured per business, with tools to check availability, create appointments, and access the services catalog.
- **Google Calendar** — appointments sync automatically; email confirmations go to clients and professionals.
- **Dashboard shell** — navigation, layout, and core screens in place.

**Sprint 3 — Demo-ready platform and mentoring**

By Sprint 3, the dashboard screens were fully implemented and demonstrated to the professor in a development environment:

- **Home** — overview of today's appointments, recent activity, and active conversations.
- **Agenda** — calendar view integrated with Google Calendar, filterable by professional.
- **Conversations** — real-time chat view with **transfer to human** — when triggered, the assistant pauses and the team is notified by email.
- **Clients** — contact records with conversation history and notes.
- **Professionals** — team members, each able to connect their own Google Calendar.
- **Services** — catalog of what the business offers (name, description, duration, price) — the assistant only quotes prices from this list.
- **Agent Settings** — name, tone (friendly, formal, or neutral), instructions, business hours, and whether bookings need manual confirmation.
- **Metrics** — indicators such as total appointments and unique clients.
- **Users** — invite and manage operators and administrators.

Business model feedback from the professor led to refining the pricing metric: instead of ambiguous "conversations per month," the model moved toward **MAU (Monthly Active Users)** — unique clients contacting the business per month — as a clearer and fairer basis for subscription tiers.

**Sprint 4 — Board presentation and version freeze**

The venture was presented to invited professors and evaluators at Inteli in a demo-day format: approximately **ten minutes of pitch** followed by **ten minutes of questions and answers**.

The presentation followed a clear story arc:

1. **The problem** — small businesses lose WhatsApp leads when nobody is available to reply.
2. **The solution** — OLI: AI virtual receptionist on WhatsApp plus a business dashboard.
3. **Live demo** — login, home, conversations (transfer to human), agenda (calendar sync), services (catalog), agent settings.
4. **Business model** — monthly subscription with MAU-based tiers (R$97 / R$197 / custom), anchored to pilot feedback and cost transparency.
5. **Closing** — honest summary of what was achieved, under what conditions, and realistic next steps.

Final deliverables were frozen: pitch decks in Portuguese and English, a recorded product demo video, and this sprint's documentation.

**Sprint 5 — Public Report**

This document completes the venture track — a comprehensive, readable summary of the entire project for anyone who was not present through every sprint and module.

Module 16 answered the question: *Can we present this as a coherent venture with integrity?*  
The answer was yes — with honest disclosure of limitations and a clear path forward.

---

## 5. WHAT THE PRODUCT DOES TODAY

For a reader who has never seen OLI, here is what the platform offers in everyday terms:

### 5.1 For the Business Owner

- **Sign in** to a private dashboard for their business.
- **Configure the assistant** — give it a name, choose a tone, set business hours, and write instructions about how it should behave.
- **Manage services** — list what the business offers, with descriptions, durations, and prices. The assistant uses this as its source of truth.
- **See conversations** — read every WhatsApp thread in real time, exactly as clients experience them.
- **Take over when needed** — pause the assistant for a specific conversation and reply personally, either from the dashboard or from WhatsApp directly.
- **Manage appointments** — view the daily and weekly agenda, synced with Google Calendar, with email confirmations sent automatically.
- **Track clients** — see contact details, conversation history, and add notes or tags (for example, "VIP client" or "allergy to product X").
- **Invite team members** — add operators and administrators who can help manage conversations and appointments.
- **View basic metrics** — total appointments, unique clients, and activity indicators.

### 5.2 For the Client (End User on WhatsApp)

- **Instant replies** — even outside business hours, the client receives a response instead of silence.
- **Natural conversation** — the assistant speaks in Portuguese, in a tone configured by the business (friendly, formal, or neutral).
- **Accurate information** — prices and service details come from the business's own catalog, not from generic guesses.
- **Appointment booking** — the assistant can check availability and schedule appointments, with confirmations by email.
- **Human escalation** — if the client asks to speak with a person, or if the situation requires it, the conversation transfers to the business team.

### 5.3 For Multiple Businesses on One Platform

Each business operates in its own isolated space. A salon in one neighborhood and a clinic in another can both use OLI on the same platform without ever seeing each other's data, conversations, or clients. This multi-business architecture is what makes OLI a **product** rather than a one-off demo.

---

## 6. WHAT WAS LEARNED — KEY INSIGHTS ACROSS THE PROJECT

### 6.1 About the Market

- **WhatsApp is non-negotiable** for Brazilian SMB service businesses. Any solution that ignores it will struggle to gain adoption.
- **Affordability matters.** These businesses compare software costs to staff costs, not to enterprise budgets. Pricing must feel fair for a salon or clinic, not a hospital.
- **Integration beats replacement.** Businesses want their existing habits enhanced, not overturned.
- **Trust is earned through visibility.** Owners need to see what the assistant said, be able to intervene, and know that prices match their catalog.

### 6.2 About the Product

- **Speed of first reply** is the single most valued benefit. Clients who get an immediate response are far more likely to convert.
- **Control mechanisms** (pause AI, transfer to human, view full threads) are not optional extras — they are core to adoption.
- **Catalog grounding** — tying assistant answers to the business's configured services — dramatically reduces anxiety about incorrect information.
- **Onboarding is the bottleneck.** The product can work well, but if connecting WhatsApp or understanding the dashboard takes too long, businesses lose patience. Guided steps and short tutorials matter as much as features.

### 6.3 About the Venture

- **Incremental validation works.** Building a minimal flow first, testing it, then expanding based on evidence produced better results than trying to build everything at once.
- **Real pilot feedback is irreplaceable.** Three businesses testing for several weeks revealed priorities that no amount of desk research could have surfaced with the same clarity.
- **Honesty builds credibility.** Presenting limitations — small pilot sample, WhatsApp dependency, areas still pending — strengthens rather than weakens the venture narrative.
- **The project mirrors real startup stages.** Research → build → test → consolidate → pitch is exactly how ventures evolve outside academia too.

---

## 7. BUSINESS MODEL

### 7.1 How OLI Makes Money

OLI follows a **subscription model** — businesses pay a monthly fee to use the platform. There is no per-message charge to the customer; the subscription covers access to the assistant, dashboard, and core features.

### 7.2 Pricing Approach

Pricing is based on **MAU (Monthly Active Users)** — the number of unique clients who contact the business through WhatsApp in a given month. This metric was chosen because it is:

- **Understandable** — business owners know how many different clients reach out each month.
- **Fair** — a salon with 50 clients per month pays less than a busy clinic with 500.
- **Aligned with costs** — more active clients mean more AI usage, so pricing scales with actual value delivered.

Indicative tiers discussed during the project:

| Tier | Approximate MAU | Indicative Price |
| ---- | --------------- | ---------------- |
| Starter | Up to ~300 active clients/month | R$97/month |
| Professional | Up to ~600 active clients/month | R$197/month |
| Enterprise | Custom volume | Custom pricing |

These numbers were informed by pilot feedback (where owners compared the cost favorably to part-time staff) and require further validation against actual AI and infrastructure costs before commercial launch.

### 7.3 Cost Structure (High Level)

The main costs of running OLI are:

- **AI usage** — each conversation consumes AI processing; cost scales with message volume.
- **Infrastructure** — servers, database, and messaging channel hosting.
- **Email notifications** — confirmations and alerts sent to clients and staff.

The project maintained a cost-conscious approach throughout — self-hosted infrastructure in early stages, efficient AI usage patterns, and architecture designed to keep per-customer costs predictable.

### 7.4 Sustainability Considerations

For the business model to be sustainable:

- Subscription prices must **cover AI and infrastructure costs** at each tier, with margin for support and development.
- **Onboarding must be efficient** — if every new customer requires hours of manual support, unit economics break down.
- **Churn must be managed** — the pilot evidence suggests businesses stay when they see daily value; the product must continue delivering that value consistently.

---

## 8. KEY ACHIEVEMENTS

What the project accomplished across all four modules, stated plainly:

**Module 13 — Research and Validation**

1. Conducted **field interviews** with business owners across aesthetics, beauty, and creative services — validating pain points with real evidence.
2. Produced a **competitive benchmarking analysis** identifying gaps in WhatsApp integration, AI automation, and affordable pricing for Brazilian SMBs.
3. Defined **three customer personas** and a consolidated **pain point map** that guided every product decision in later modules.
4. Scoped the **MVP feature set** and technology direction based on research, not assumptions.
5. Published a **comprehensive research report** establishing the strategic foundation for the venture.

**Module 14 — MVP Development**

6. Built a **working AI assistant** that captures leads and holds natural conversations on WhatsApp in Portuguese.
7. Implemented **intent classification** — distinguishing booking requests, pricing questions, and general inquiries.
8. Launched a **public landing page** (bilingual) establishing OLI's brand and multi-channel lead capture.
9. Achieved a **production-ready proof of concept** with strong lead capture success rates at affordable operational cost.
10. Drafted a **preliminary business plan** with subscription model, target segments, and pilot program strategy.

**Module 15 — Product Development and PMF**

11. Designed a **multi-business platform architecture** with documented security, reliability, and integration plans.
12. Formalized **testable PMF hypotheses** and ran a structured **three-business pilot program**.
13. Synthesized **qualitative customer feedback** into actionable product priorities (notifications, human takeover, catalog grounding, onboarding).
14. Documented **API integrations, onboarding flows, and stability requirements** for scalable operation.

**Module 16 — Consolidation and Pitch**

15. **Consolidated the product** into a unified application (`oli-app`) with authentication, full dashboard, calendar integration, and real-time conversations.
16. Migrated from workflow-based prototype to **full-code multi-tenant platform** supporting multiple businesses with isolated data.
17. Prepared and delivered a **board presentation** to professors and evaluators with pitch decks (PT-BR and EN), live demo, and business model.
18. **Documented the entire journey** across modules, sprints, and deliverables — creating a traceable record from first interview to final pitch.

---

## 9. HONEST LIMITATIONS

A credible venture narrative includes what was **not** achieved or what remains open:

- **Small pilot sample.** Three businesses over several weeks provide deep qualitative insight but cannot statistically represent the entire SMB market.
- **Academic context.** The project was conducted within an academic program with defined timelines, not as a commercial startup with unlimited runway.
- **WhatsApp dependency.** The platform relies on WhatsApp as its primary channel. Changes in Meta's policies or messaging restrictions remain a real risk that must be monitored and mitigated.
- **Production deployment.** At the time of the board presentation, the platform was fully functional in development and staging environments. A full production deployment pipeline was planned but not completed within the module timeline.
- **Measurement gaps.** While pilot feedback was rich in qualitative terms, a fully instrumented analytics suite with automated dashboards for every business metric was not yet in place.
- **Some requested features remain on the roadmap** — such as assigning conversations to specific operators, first-call resolution tracking, and internal AI cost dashboards.

These limitations are stated intentionally. They do not diminish what was built; they define the boundary between what the project proved and what would require continued work beyond graduation.

---

## 10. WHAT COMES NEXT

The venture track ends with Module 16, but the project itself has a natural continuation path. Based on everything learned, the highest-priority next steps would be:

**Product**

- Complete production deployment with a stable, accessible URL for customers.
- Strengthen onboarding with guided checklists and short video tutorials.
- Implement per-conversation "pause AI" and operator assignment.
- Enforce strict catalog grounding so the assistant never quotes prices outside the configured services.
- Add notifications for new priority leads and AI escalations.

**Business**

- Validate pricing tiers against actual AI billing and infrastructure costs.
- Expand pilot program to a larger cohort across aesthetics, wellness, and pet services.
- Develop sales materials that frame pricing against staff cost, not enterprise software.
- Address WhatsApp policy concerns proactively in customer conversations.

**Technical**

- Complete end-to-end security verification of tenant data isolation.
- Build automated monitoring for message delivery health.
- Plan a contingency path toward WhatsApp's official Business API if channel policies tighten.

These are directions, not commitments. The project demonstrated that the foundation is solid, the market need is real, and the path forward is clear — whether pursued by the current team after graduation, handed to future collaborators, or used as a portfolio piece for further venture development.

---

## 11. CONCLUSION

OLI began in Module 13 as a research question: *Can AI automation help small Brazilian service businesses that struggle with WhatsApp communication, manual scheduling, and missed leads?*

Over four modules, that question was answered through action — not speculation:

- **Module 13 (Research)** went into the field, interviewed real business owners, mapped competitors, defined personas, and scoped the MVP. It confirmed the problem is real, widespread, and worth building for.
- **Module 14 (Build)** turned research into a working proof of concept — a WhatsApp assistant that captures leads, classifies intent, and operates at a cost suitable for small businesses.
- **Module 15 (Test)** ran structured pilots with three real businesses, documented how the platform should scale, and gathered evidence that faster replies and fewer missed leads genuinely matter — with clear conditions around control, accuracy, and onboarding.
- **Module 16 (Consolidate and Present)** unified everything into a coherent product with a full dashboard, presented the venture to a board of evaluators, and closed the academic track with integrity — achievements, limitations, business model, and next steps stated honestly.

OLI is not a finished commercial product ready for mass market launch. It is something arguably more valuable for an academic venture track: a **thoroughly researched, built, tested, and documented foundation** for a business that addresses a genuine need in a large and underserved market — with a clear paper trail from the first interview to the final pitch.

For any reader encountering this project for the first time — whether a professor reviewing the final submission, a potential partner evaluating collaboration, or a future developer picking up the codebase — the story spans four modules and one consistent thread:

**Small businesses in Brazil lose clients every day because nobody answers WhatsApp fast enough. OLI was researched, built, tested, and presented to change that — one conversation at a time.**

---

**Institution:** [Inteli — Instituto de Tecnologia e Liderança](https://www.inteli.edu.br)  
**Project:** OLI — Optimized Lead Intelligence  
**Author:** Antonio Barone Nassar  
**Report Date:** June 2025  
**Status:** Module 16 Complete — Venture Track Final Public Report  
**Modules Covered:** 13 (research), 14 (MVP), 15 (PMF), 16 (consolidation and pitch)

---

## 12. REFERENCE INDEX

For readers who want deeper detail on specific topics, the following documents support this report:

| Topic | Document |
| ----- | -------- |
| M13 project plan and strategy | [M13 Project Plan (PDF)](../../Module%2013/sprint_01/Docs%20-%20Project%20Plan%20-%20M13.pdf) |
| Field interviews (Sprint 2) | [M13 Interview Report](../../Module%2013/sprint_02/Interview%20Report%20%E2%80%93%20Sprint%202.md) |
| Competitive analysis | [M13 Competitive Breakdown](../../Module%2013/sprint_03/competitive_analysis_breakdown.md) |
| Personas and pain points | [M13 Personas](../../Module%2013/sprint_03/personas_definition.md), [Pain Points](../../Module%2013/sprint_03/common_pain_points.md) |
| MVP feature definition | [M13 MVP Key Features](../../Module%2013/sprint_04/mvp_key_features.md) |
| M13 public research report | [M13 Public Report](../../Module%2013/sprint_05/public-report.md) |
| M14 MVP development journey | [M14 Public Report](../../Module%2014/sprint_05/public-report-general.md) |
| M15 PMF pilots and architecture | [M15 Public Report](../../Module%2015/sprint_05/public_report.md) |
| Platform consolidation (M16) | [M16 Sprint 2 Evolution Report](../sprint_02/module16_sprint_02_evolution_report.md) |
| Board presentation (M16) | [M16 Sprint 4 Board Report](../sprint_04/sprint04_board_presentation_report.md) |
| Customer feedback (pilots) | [M15 Customer Feedback](../../Module%2015/sprint_04/customer_feedback_pmf.md) |
| Pitch narrative | [M16 Pitch Deck Outline](../sprint_03/pitch_deck_draft_outline.md) |
| Business plan (draft) | [M14 Business Plan Draft](../../Module%2014/sprint_05/business-plan-draft.md) |
