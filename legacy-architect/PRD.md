# Legacy Architect — Product Requirements Document

**Version:** 1.0  
**Status:** Draft — Awaiting Founder Review  
**Prepared by:** The Signal Product Studio  
**Date:** March 16, 2026  
**Owner:** Aidan Uttinger  

---

## Table of Contents

1. [Product Vision](#1-product-vision)
2. [Problem Statement](#2-problem-statement)
3. [Target Users](#3-target-users)
4. [Jobs To Be Done](#4-jobs-to-be-done)
5. [Core Features — Full Spec](#5-core-features--full-spec)
6. [User Flows](#6-user-flows)
7. [Technical Requirements](#7-technical-requirements)
8. [Monetization Model](#8-monetization-model)
9. [Competitive Analysis](#9-competitive-analysis)
10. [Go-to-Market Strategy](#10-go-to-market-strategy)
11. [Success Metrics (KPIs)](#11-success-metrics-kpis)
12. [Risks & Mitigations](#12-risks--mitigations)
13. [Roadmap](#13-roadmap)
14. [Open Questions](#14-open-questions)

---

## 1. Product Vision

Legacy Architect is the platform where love defeats time. It gives people the ability to speak to the people they love most — not just now, but at the exact moment those people need to hear it most: when they graduate, when they marry, when they hold their first child, or when they stand at an inheritance threshold wondering what their family truly valued. In an era where technology has accelerated human disconnection and the average person dies without having said the most important things to the people who matter most, Legacy Architect becomes the infrastructure for emotional continuity across generations — a digital ethical will that holds not just instructions, but presence, wisdom, and love — backed by blockchain permanence, AI-guided articulation, and physical gift delivery to make the moment undeniably real. For wealth managers, it is the relationship bridge that turns a transactional inheritance event into a moment of profound family alignment. For families, it is the archive of everything that should never be lost.

---

## 2. Problem Statement

### The B2C Problem

Most people die having never said the things that mattered most. Not because they didn't feel them — but because they didn't know how, didn't think they had time, or assumed there would be a better moment later. Children grow up without access to a grandparent's voice. Parents miss the chance to speak to a child at their wedding. Wisdom accumulated over a lifetime dissolves within a generation.

Existing solutions are inadequate. Writing a letter is analog and fragile. Video recordings sit unwatched on hard drives. Legal wills are transactional, cold, and contested. There is no platform purpose-built for the emotional, time-specific delivery of a person's most important words.

**Who this is for:** Parents, grandparents, adults of any age who have people they love and things they want to say — and want those words delivered at the right moment, not lost in a shoebox.

**Why now:** Aging millennials (now 30-45) are entering the years when mortality becomes real — parents dying, children being born, inheritance events approaching. Gen X is hitting peak estate planning age. Both generations are digital-native and emotionally literate in ways previous generations were not. They will embrace this.

### The B2B Problem

Wealth managers face a structural crisis: **90% of inherited wealth changes advisors within two years of a wealth transfer event.** The relationship is with the parent — not the heir. When the parent dies, the heir takes the money elsewhere.

There is no good tool for advisors to bridge that generational relationship proactively. Generic CRM outreach is cold. Estate planning documents are clinical. Legacy Architect gives wealth managers a high-intimacy, differentiated service offering: a family legacy vault that anchors the heir emotionally to the family's values and, by extension, to the advisor who helped build it.

**Who this is for:** Wealth managers, estate attorneys, family offices managing multigenerational relationships.

**Why now:** The $84 trillion Great Wealth Transfer is underway. The advisors who build heir relationships now will retain those assets. Legacy Architect is the tool that makes that possible.

---

## 3. Target Users

### Persona 1 — The Parent (B2C Core User)

| Field | Detail |
|---|---|
| **Name** | Michael Chen |
| **Age** | 42 |
| **Situation** | Married with two kids, ages 8 and 11. Both parents work. Life is full, fast, and feels permanent — even though it isn't. His father died suddenly two years ago without leaving anything meaningful behind. |
| **Goals** | Want his kids to know who he really was — not just "Dad." Wants to speak to them at their graduations, their weddings, their hardest days. Wants his wisdom to outlive him. |
| **Pain Points** | Doesn't know where to start. Feels like it's morbid to record a message "in case he dies." Worries about the right words. Assumes he'll do it later. |
| **What Legacy Architect gives him** | A structured, guided process that makes recording feel natural and life-affirming — not morbid. A vault that he builds over years, knowing it will be there. The AI coach helps him find the words. The Time Collapse feature lets him speak to his daughter at age 42, when she's 42, as a peer. |

---

### Persona 2 — The Grandparent (B2C Emotional User)

| Field | Detail |
|---|---|
| **Name** | Dorothy Harmon |
| **Age** | 71 |
| **Situation** | Retired. Three adult children, six grandchildren. Husband passed five years ago. Deeply aware of her own mortality. Has stories, recipes, hard-won wisdom, and a lifetime of love she's never been able to fully express. |
| **Goals** | Leave something real for her grandchildren — not just belongings. Wants them to know her voice, her face, her values. Wants to be present at their milestones even after she's gone. |
| **Pain Points** | Not technically sophisticated. Worried it's complicated. Doesn't have a clear structure. Wants someone to guide her through it. Worried about the messages getting lost or the platform disappearing. |
| **What Legacy Architect gives her** | A dead-simple mobile interface. Guided prompts that feel like a conversation. Arweave-backed permanence she can explain to her kids as "forever storage." A Legacy Gift option so her granddaughter receives both a locket and a personal video message on her 18th birthday. |

---

### Persona 3 — The Wealth Manager (B2B Buyer)

| Field | Detail |
|---|---|
| **Name** | Larry Harvey |
| **Age** | 58 |
| **Situation** | Principal at HFG Wealth Management. Manages 80+ high-net-worth families, assets in the $2M–$50M range. Has watched generational wealth transfers destroy relationships and lose his firm assets. Deeply values the human side of financial planning. |
| **Goals** | Retain assets across generational transitions. Differentiate his practice with a premium, emotionally resonant service offering. Give clients a reason to bring their adult children into the conversation early. |
| **Pain Points** | Has no tool built for this. CRM systems are transactional. Estate documents are cold. Heirs are disengaged. He's tried onboarding adult children but has no compelling reason to pull them in. |
| **What Legacy Architect gives him** | A white-glove dashboard to create and manage client legacy vaults. Talking points for bringing this up with clients ("We're now offering a Legacy Vault as part of your estate planning package"). A soft introduction to heirs that creates a warm relationship before the transfer event. A powerful differentiator for client acquisition. |

---

### Persona 4 — The Young Adult (Time Collapse Use Case)

| Field | Detail |
|---|---|
| **Name** | Zara Williams |
| **Age** | 23 |
| **Situation** | Recent college graduate. No kids yet. But she grew up without her mother, who died when Zara was 7. She knows what it's like to not have those messages. She is determined her future children will never feel that absence. |
| **Goals** | Record herself now — at 23, full of energy and clarity — so her future children can meet her at this age. Leave a record of who she is before life changes her. |
| **Pain Points** | Feels like it's "too early" — she doesn't even have kids yet. No clear way to assign recipients who don't exist yet. Uncertain the platform will still exist in 20 years. |
| **What Legacy Architect gives her** | The Time Collapse feature, designed exactly for her. Placeholder recipients ("My future daughter," "My future son") that she can assign when the time comes. Arweave-backed permanence with a blockchain proof she can hold. A freemium entry point so the barrier to starting is zero. |

---

## 4. Jobs To Be Done

Using the JTBD framework: *"When [situation], I want to [motivation], so I can [outcome]."*

| # | Job | Emotional Layer |
|---|---|---|
| **J1** | When I realize I might not always be here, I want to record my love and wisdom in a way that will actually reach my children at the right moment, so I can be present at their milestones even if I'm gone. | Fear of absence → Desire for presence |
| **J2** | When I sit down to record something meaningful, I want to be guided through what to say, so I don't freeze up or feel like what I said wasn't enough. | Creative paralysis → Confidence |
| **J3** | When I want to leave a lasting record for the next generation, I want to know that my messages will survive platform shutdowns, company failures, and technology changes, so I can trust the system with something irreplaceable. | Fear of impermanence → Trust |
| **J4** | When a major life event happens (inheritance, graduation, marriage), I want the right message and gift to arrive automatically, so the moment feels intentional — like I planned it — not accidental. | Anxiety about missing moments → Orchestration of love |
| **J5** | When I'm a wealth manager preparing a family for an inheritance transition, I want to help my clients embed their values into the handoff process, so heirs receive wealth with context and the family stays together — and with me. | Relationship risk → Relationship continuity |
| **J6** | When I'm young and healthy and full of life, I want to preserve who I am right now for the people who will come into my life later, so they can know me not just as an older version of myself, but as I am today. | Transience → Continuity |
| **J7** | When something happens to me unexpectedly, I want trusted people to be able to release important messages quickly, so my loved ones are not left without my words at the worst possible time. | Unpreparedness → Emergency preparedness |

---

## 5. Core Features — Full Spec

---

### Feature 1: Message Recording

**Name:** Message Recording  
**Priority:** P1 — MVP  

**Description:**  
The core creation feature. Users record and upload messages in four formats: video (up to 10 min/clip), voice (audio-only), written letter (rich text editor), and photo/document uploads. All media is processed, encrypted, and stored in object storage, then mirrored to Arweave for permanent archival.

**User Story:**  
> As a creator, I want to record a video message, write a letter, attach a photo, or leave a voice note — and have it securely stored and linked to a specific recipient and trigger — so I can build my legacy vault over time.

**Spec Notes:**
- Video: max 10 min per clip, 4K accepted, transcoded to 1080p for delivery. H.264 output.
- Voice: max 30 min, MP3/WAV input, AAC output.
- Letter: rich text editor (bold, italic, lists, blockquote, no external embeds). 10,000 char limit (P1), unlimited (P2).
- Photo/Doc: JPG, PNG, PDF, up to 50MB per file. PDF rendering in-app.
- All media watermarked with creation timestamp (invisible metadata).
- All recordings tagged: creator ID, recipient ID (can be placeholder), trigger ID, creation date, last modified.
- Draft state before finalizing. Once "sealed," message is locked from editing unless explicitly re-opened by creator.
- Unsealing a message generates an audit log entry.
- Mobile: native camera/mic access via React Native.

---

### Feature 2: Unlock Triggers

**Name:** Unlock Triggers  
**Priority:** P1 — MVP  

**Description:**  
The delivery engine. Each message is assigned one or more triggers that determine when it becomes available to the recipient. Supported triggers: specific date (e.g., "December 25, 2040"), recipient age (e.g., "when Maya turns 18"), life event (predefined events: graduation, wedding, birth of first child, 18th birthday, 21st birthday, inheritance event, death of creator), and a custom text event (P2).

**User Story:**  
> As a creator, I want to set exactly when and why a message gets unlocked, so it arrives at the moment it will mean the most — not randomly, not too early.

**Spec Notes:**
- Triggers are set during message creation or editing (before sealing).
- Date trigger: calendar picker, UTC stored, local timezone shown.
- Age trigger: requires recipient birthdate (stored encrypted). System calculates unlock date dynamically.
- Life event trigger: system waits for guardian/executor confirmation OR recipient self-report (both logged). Two-factor confirmation required for events other than inheritance.
- Inheritance trigger: linked to wealth manager confirmation OR guardian confirmation.
- Multiple triggers per message supported (e.g., "on my daughter's wedding day OR when she turns 30 — whichever comes first").
- Trigger state: pending → confirmed → release queue → delivered.
- Guardian can mark a life event as confirmed within the app.
- Notification to creator 90 days before any date-based trigger fires, with option to update.

---

### Feature 3: Time Collapse

**Name:** Time Collapse  
**Priority:** P1 — MVP (core differentiator — must ship at launch)  

**Description:**  
The emotionally unique feature that defines Legacy Architect. Time Collapse allows the creator to record a message explicitly framed as: "I am [age] today. This message is for you when you are [same age]." The app prompts the creator with age-specific questions (e.g., "What do you know at 42 that you wish you'd known at 20?"), records the message, and delivers it to the recipient when they reach that exact age.

**User Story:**  
> As a 42-year-old father, I want to record a message to my daughter to be opened when she turns 42 — so she can hear from me as a peer, not as a parent, at the exact same chapter of life.

**Spec Notes:**
- Creator enters their current age; system pre-calculates recipient delivery date based on recipient birthdate.
- If recipient birthdate is unknown (future child use case), creator sets "recipient age at delivery" and assigns recipient later.
- Prompt library tailored to creator's age: 20s prompts, 30s prompts, 40s prompts, 50s prompts, 60s+ prompts (managed by AI coach layer, Feature 6).
- Time Collapse messages are visually distinct in the vault (special UI treatment — brief for UX Architect).
- At delivery, recipient is shown: "This message was recorded when [Name] was exactly your age."
- Time Collapse also supports "record at 30 for future children" — placeholder recipient flow.

---

### Feature 4: Family Vault

**Name:** Family Vault  
**Priority:** P2 — Phase 2  

**Description:**  
A multi-generational shared archive that aggregates messages from multiple family members. A family can invite grandparents, parents, aunts, uncles, and siblings to contribute. The vault is browsable by living family members (with permission controls) and can be passed down indefinitely. The Vault becomes the family's institutional memory.

**User Story:**  
> As a family administrator, I want to create a shared vault where my mother, my siblings, and I can all contribute messages for the next generation — so our family's story is preserved together, not in isolated accounts.

**Spec Notes:**
- Vault creation by a designated Family Admin (one per vault).
- Invitations sent by email. Each invitee creates their own Legacy Architect account and is linked to the vault.
- Permission levels: Contributor (can add messages), Viewer (can view unlocked messages), Admin (manages vault, invites members).
- Message contributions within the vault maintain individual creator ownership and trigger rules.
- Family Vault has a "Living Archive" section: messages that are not time-locked and are immediately visible to all members (family photos, public-facing letters).
- Vault has a visual timeline view (design brief for UX Architect — critical feature).
- A vault can span generations: grandparents → parents → children → grandchildren.
- Vault can be accessed by heirs even after all original creators are gone, provided blockchain proof of access rights.
- B2B use: wealth manager can provision a Family Vault on behalf of a client family.

---

### Feature 5: AI Message Coach

**Name:** AI Message Coach  
**Priority:** P2 — Phase 2  

**Description:**  
Many users know they want to leave something meaningful but freeze when faced with a blank recording screen. The AI Message Coach is a guided pre-recording assistant that asks the user questions based on their chosen recipient, occasion, and message type — then helps them structure what they want to say before hitting record. It does NOT record for them or generate the message — it helps them find their own words.

**User Story:**  
> As someone who wants to record a message for my son's wedding day but doesn't know where to start, I want a guided prompt experience that asks me questions and helps me organize my thoughts — so my message feels genuine and complete, not rambling.

**Spec Notes:**
- Triggered optionally when user starts a new message: "Would you like help with this message?"
- Flow: select recipient type (child, parent, spouse, grandchild, friend) → select occasion (wedding, graduation, 18th birthday, "just because," Time Collapse) → AI asks 3-5 guided questions.
- Questions are open-ended: "What's a moment with [Name] you'll never forget?" / "What do you wish you could be there to see?" / "What's the most important thing you've learned that you want them to know?"
- User's answers are shown back as a loose outline before recording: "Here's what you told me — now record it in your own words."
- Outline is saved to the message draft for reference during recording.
- AI Coach never generates the actual message content — it is purely a structuring and prompting tool. This is an ethical and authenticity design choice.
- Prompt library: 50+ prompts at launch, expanding with usage data.
- Prompt library maintained and updated by the product team — not fully AI-generated in V1.
- Mobile: inline modal experience. Web: side panel.

---

### Feature 6: Guardian / Succession System

**Name:** Guardian / Succession System  
**Priority:** P1 — MVP  

**Description:**  
Every creator designates 1–3 trusted guardians at onboarding (and can update at any time). Guardians are the trusted humans who confirm life events, vote on emergency releases, and maintain the creator's vault if the creator is incapacitated. This is the trust architecture that makes the system legally and emotionally defensible.

**User Story:**  
> As a creator, I want to assign trusted people who can confirm that my son got married or that I have passed away — so the system can release the right messages at the right time, even if I'm not around to trigger it myself.

**Spec Notes:**
- Setup: during onboarding, user is required to add at least 1 guardian (2 strongly recommended; 3 is max).
- Guardian invitation: email invite with explanation of the role. Guardian must accept.
- Guardian role: confirm life events, vote on emergency release, receive annual check-in pings.
- Guardian dashboard: simple mobile-friendly view showing pending confirmations, vault status.
- Annual check-in: system pings creator once per year to confirm they are alive and want to maintain the vault. If creator misses check-in, guardians are notified. If creator misses 2 consecutive check-ins, emergency protocol begins (see Feature 7).
- Emergency release vote: requires 2-of-3 guardian approval (or 1-of-1 if only 1 guardian assigned). Each guardian votes independently via a confirmation link or in-app.
- 30-day challenge window: after vote is completed, a 30-day window begins before any emergency messages release. Creator can override during this window if they are alive.
- Succession: if a guardian dies or becomes unavailable, creator can replace them. If creator is incapacitated and a guardian needs replacing, the remaining guardians vote.
- All guardian actions are logged to blockchain (Polygon) for auditability.
- Legal note: guardian actions do not have legal standing. System should display a disclaimer that this is not a legal instrument.

---

### Feature 7: Emergency Release System

**Name:** Emergency Release System  
**Priority:** P1 — MVP  

**Description:**  
The mechanism by which messages are released in the event of the creator's death or incapacitation, outside of standard triggers. The emergency system is initiated by guardian consensus and follows a structured, auditable process with a built-in challenge window.

**User Story:**  
> As a guardian of my sister's Legacy Architect vault, I want to initiate an emergency release after her unexpected death — so her children receive the messages she prepared for them, without waiting for an arbitrary date trigger.

**Spec Notes:**
- Any guardian can initiate an emergency release request. Other guardians are immediately notified.
- All guardians cast votes independently (approve/deny). Quorum: 2-of-3 (or 1-of-1).
- System checks for creator activity: last login, check-in status. Shows this info to guardians.
- Once vote is approved, 30-day challenge window activates. System sends notification to creator's registered email and phone (in case of false positive).
- If creator does not respond in 30 days, emergency messages are released to recipients.
- Emergency-only messages: creator can tag specific messages as "emergency only" — these only release via the emergency system, not by date/age triggers.
- Partial release: creator can specify which messages are included in emergency release and which are not.
- Post-release audit: all released messages are logged with timestamp, guardian IDs, and vote record.
- Blockchain: vote and release events are written to Polygon for permanent auditability.

---

### Feature 8: Legacy Gifts

**Name:** Legacy Gifts  
**Priority:** P3 — Phase 3  

**Description:**  
A curated marketplace of physical gifts (jewelry, keepsakes, books, custom items) that can be attached to a message delivery. When a trigger fires and a message is unlocked, the recipient also receives a physical gift — shipped to their current address. Legacy Architect earns 15–20% commission on each gift order.

**User Story:**  
> As a grandmother, I want my granddaughter to receive a gold locket AND a personal video message on her 18th birthday — so the moment feels real, not just digital.

**Spec Notes:**
- Gift catalog: curated collection of 50–100 items at launch (jewelry, engraved keepsakes, books, handwritten letter printing services, custom photo prints).
- Creator selects a gift at message creation time. Gift is held in a "pending order" state.
- Address collection: system collects recipient address at time of delivery (not at purchase time, since addresses change). System sends recipient an address request form 30 days before scheduled delivery.
- If recipient address cannot be collected, gift is held for 90 days before order is cancelled (creator notified).
- Payment: creator pays for gift at time of selection (held until trigger fires). Refund policy: full refund if trigger never fires (e.g., recipient predeceases creator). Partial refund (minus processing) if cancelled within 30 days of trigger date.
- Fulfillment partners: 2–3 vetted fulfillment partners at launch. Gift catalog managed by Legacy Architect team.
- Engraving/personalization: creator can add a short engraving (30 chars) at purchase.
- Digital companion: gift arrives with a printed card directing recipient to open their Legacy Architect message.
- Revenue: Legacy Architect earns 15–20% commission on gift GMV. Fulfillment partner handles shipping and returns.
- Pricing: gifts range from $25 to $500. Average order value target: $85.
- International shipping: Phase 4 feature. Phase 3 is US-only.

---

### Feature 9: Wealth Manager Dashboard

**Name:** Wealth Manager Dashboard  
**Priority:** P1 — MVP (required for B2B pilot)  

**Description:**  
A dedicated portal for wealth managers (B2B users) to manage their clients' family vaults. The dashboard shows advisor's full client roster, vault status per client, pending actions, and a simplified onboarding flow to bring a new client into Legacy Architect without requiring the client to be tech-savvy.

**User Story:**  
> As a wealth manager, I want to see all my clients' vault statuses in one place, initiate vault creation on their behalf, and get notified when a client has an upcoming inheritance event — so I can use Legacy Architect as a proactive relationship tool, not a reactive one.

**Spec Notes:**
- Advisor login: separate credential from B2C user flow. Role: `advisor`.
- Client roster: list view with columns: Client Name, Vault Status (Not Started / Active / Messages Sealed / Pending Event), Guardian Status, Last Activity, Upcoming Triggers.
- Vault creation: advisor can initiate vault creation for a client, which sends the client a welcome email with onboarding link. Vault is "advisor-assisted" — advisor set it up on their behalf.
- Client view: advisor can view vault summary (message count, recipient count, sealed status) but CANNOT read message content. Content is private to creator. This is a hard privacy rule.
- Advisor notes: advisor can add internal notes per client vault (not visible to client).
- Event alerts: advisor is notified 60 days before any inheritance-linked trigger for their clients.
- Bulk import: upload CSV of client names and emails to initiate batch invitations.
- White-label option (P3): advisor dashboard can be white-labeled under firm branding.
- HFG pilot: Larry Harvey's dashboard is provisioned manually. Automated advisor provisioning in Phase 4.
- Reporting: monthly report of vault health (activation rate, message count, sealed rate) for advisor's book of business.

---

### Feature 10: Recipient Onboarding

**Name:** Recipient Onboarding  
**Priority:** P1 — MVP  

**Description:**  
When a trigger fires and a recipient is eligible to receive a message, the system initiates a recipient-specific onboarding flow. This is often the recipient's first interaction with Legacy Architect — they may not have known a vault existed. The experience must be handled with extreme emotional care.

**User Story:**  
> As someone who just received a notification that a message was left for me, I want a clear, emotionally sensitive experience that guides me to unlock and view the message — without confusion or friction — so the moment feels meaningful, not transactional.

**Spec Notes:**
- Delivery channel: email notification (primary) + SMS (if phone registered) + push (if app installed).
- Email subject line: "[Creator Name] left you a message" — simple, human. No product marketing in the delivery email.
- Landing page: recipient lands on a dedicated unlock page (not the main marketing site). Clean, quiet design. Only essential content.
- Identity verification: recipient must verify identity before unlocking. Options: email link (primary), phone OTP (secondary).
- If recipient is a minor: parent/guardian must unlock on their behalf. Minor-specific flow gated by creator's designation.
- Message playback: full-screen, immersive experience. Video autoplays (muted until user action). Letters are displayed cleanly. Voice plays with waveform visual.
- After viewing: recipient is offered the option to create their own vault ("Now leave something for someone you love") — soft CTA. Not aggressive.
- Saving/downloading: recipients can download their messages (video/voice/letter). This is their right.
- Recipient account: created automatically upon first unlock. Recipients can log back in to re-watch. They are shown only messages explicitly unlocked for them.
- Gift coordination: if a Legacy Gift is attached, recipient receives a separate shipping notification from the fulfillment partner with the Legacy Architect branding.

---

### Feature 11: Notification System

**Name:** Notification System  
**Priority:** P1 — MVP  

**Description:**  
The notification layer that connects creators, recipients, and guardians at every key moment in the vault lifecycle. Must be reliable, thoughtful, and never feel spammy. Email is the primary channel; push and SMS are secondary.

**User Story:**  
> As a creator, I want to receive relevant, timely reminders about my vault — upcoming triggers, check-in requests, guardian confirmations — without feeling like I'm being pestered.

**Spec Notes:**

**Creator Notifications:**
- Welcome / onboarding series (3 emails over 7 days — not product pitches, emotional storytelling)
- "You haven't recorded a message in 30 days" — gentle nudge (max 1/month)
- Upcoming trigger: 90 days, 30 days, 7 days before any date trigger fires
- Annual check-in ping: "Your vault is waiting. Let us know you're still here."
- Guardian confirmation: when a guardian confirms a life event
- Emergency release: if initiated

**Recipient Notifications:**
- Message unlock: primary delivery email (see Feature 10)
- Gift shipping notification (from fulfillment partner via Legacy Architect system)
- Reminder to view (if message unlocked but not viewed after 7 days)

**Guardian Notifications:**
- Invitation to become guardian (with role explanation)
- Annual check-in status for creator
- Emergency release vote request
- Vote confirmation from other guardians

**Technical:**
- Email: SendGrid (or equivalent). Transactional and lifecycle templates.
- Push: Firebase Cloud Messaging (FCM) for mobile.
- SMS: Twilio (for OTPs and critical alerts only — not marketing).
- All notifications are opt-configurable except transactional ones (unlock delivery, guardian alerts).
- Notification preferences screen in user settings.
- Rate limiting: max 2 non-transactional emails per week per user.

---

## 6. User Flows

---

### Flow 1: New User Onboarding and Recording First Message

1. User arrives at legacyarchitect.com (or via advisor-sent invitation link).
2. Lands on marketing/landing page. CTA: "Start Your Legacy — Free."
3. Account creation: email + password + name + date of birth. Or sign in with Google/Apple.
4. Email verification: user confirms email before proceeding.
5. Onboarding modal (3 screens):
   - Screen 1: "What is Legacy Architect?" — 30-second emotional explainer. Skip available.
   - Screen 2: "Who do you want to leave a message for?" — user adds first recipient (name, relationship, optional birthdate, optional email). Can add multiple or skip.
   - Screen 3: "Choose a trusted guardian" — add 1-3 guardians by email. Can skip but is prompted again 48 hours later.
6. User lands on their vault dashboard (empty state with clear CTA: "Record your first message").
7. User clicks "New Message."
8. Message creation form:
   - Select recipient (from list or add new)
   - Select message type (video / voice / letter / photo+doc)
   - Optionally: "Want help with this message?" — launches AI Coach (Feature 5, P2)
   - Set unlock trigger (date / age / life event / emergency-only)
9. Recording/upload interface loads (format-specific UI).
10. User records or uploads content.
11. Preview screen: user reviews the message before sealing.
12. Seal: message is encrypted, stored, and linked to trigger. Status: Sealed.
13. Confirmation screen: "Your message is safe. It will reach [Name] when [trigger description]."
14. User returned to vault dashboard, which now shows one sealed message.
15. Gentle prompt: "Would you like to record another message? You have 14 days free."

---

### Flow 2: Recipient Receiving and Unlocking a Message

1. Trigger condition is met (date arrives, guardian confirms life event, age calculated).
2. System queues message for delivery. Delivery job runs within 1 hour of trigger firing.
3. Recipient receives email: "[Creator Name] left you a message for this moment." Subject line is human — not branded.
4. Recipient clicks "Open My Message."
5. Lands on a dedicated unlock page: `/unlock/[token]` — clean, quiet, no navigation.
6. Page shows: creator name, their relationship to recipient, and a brief framing: "This message was prepared for you for this day."
7. Identity verification: recipient enters their email and receives a one-time link (or OTP to phone if registered). This confirms identity.
8. If recipient is new to the system: lightweight account creation (just name + email + password — minimal friction).
9. Message unlocks and plays/displays. Video is full-screen. Letter is cleanly typeset. Voice plays with visual.
10. After viewing: recipient sees message details (date recorded, trigger that fired).
11. Recipient can replay, download, or share (sharing is off by default — creator can enable).
12. If a Legacy Gift is attached: separate card appears: "A gift from [Creator Name] is on its way."
13. Post-unlock CTA (soft): "Want to leave something for someone you love?" — links to B2C signup. Not shown until after message is fully consumed.
14. Recipient can log in later at legacyarchitect.com to re-access their unlocked messages.

---

### Flow 3: Emergency Release Triggered by Guardian

1. Creator misses second annual check-in OR a guardian manually initiates emergency release.
2. If guardian-initiated: guardian logs into their guardian dashboard and selects "Initiate Emergency Release" for a specific creator's vault.
3. Guardian must provide a reason (dropdown: "Creator has passed away" / "Creator is incapacitated" / "Creator is unreachable"). Reason is logged.
4. All other guardians receive immediate email notification: "[Guardian Name] has requested emergency release of [Creator Name]'s vault. Your vote is required."
5. Each guardian accesses a secure voting link. They see: the reason provided, the creator's last login date, and the requester's statement.
6. Guardian casts vote: Approve or Deny. Optionally adds a note.
7. System requires quorum (2-of-3 or 1-of-1). Once quorum is reached:
   - System attempts to notify creator via email, SMS, and push: "An emergency release has been voted on for your vault. If you are alive and well, click here to halt the release." 
   - 30-day challenge window begins. Creator can halt at any time during this window.
8. If no response from creator in 30 days: emergency release executes.
9. Messages tagged "emergency release" are delivered to recipients using the standard recipient unlock flow (Flow 2), with a special framing note: "This message was prepared for an unexpected moment. It was released by [Creator Name]'s trusted guardians."
10. All events (vote, window start, release, recipient delivery) are written to Polygon blockchain.
11. Post-release: guardians receive a summary of what was released and to whom.

---

### Flow 4: Wealth Manager Setting Up a Client Vault

1. Larry Harvey (advisor) logs into the Wealth Manager Dashboard at `advisor.legacyarchitect.com`.
2. He selects "Add New Client Vault."
3. Enters client details: name, email, phone (optional), date of birth, relationship context ("long-term client, has 3 adult children").
4. System sends client (e.g., Margaret Weston, 72) a personalized invitation email: "Your wealth advisor Larry Harvey has set up a Legacy Vault for you at Legacy Architect. Click here to activate your vault."
5. Margaret clicks the link and completes her own lightweight onboarding (name confirmed, password set, guardian setup).
6. Larry sees Margaret's vault status update to "Active — Onboarding Complete" on his dashboard.
7. Larry adds an advisor note: "Margaret has 3 heirs. Oldest son (David) is executor. Discuss inheritance trigger for estate transfer event at next quarterly review."
8. Larry can optionally pre-suggest recipients for Margaret: he inputs the three children's names and emails. Margaret sees these as "suggested recipients" during her onboarding and confirms or edits them.
9. If Margaret has an upcoming inheritance-linked event (or Larry flags one), the system creates an event alert for Larry 60 days out.
10. Larry can pull a vault health report monthly: how many of his clients have active vaults, messages sealed, triggers set.
11. When Margaret's vault triggers an inheritance event, Larry is notified. He can reach out proactively to the heir (David), knowing the context has been set.

---

### Flow 5: Legacy Gift Purchase and Delivery Scheduling

1. Creator (Michael, 42) is recording a message for his daughter Maya's 18th birthday.
2. During message creation, after setting the trigger (Maya turns 18 = Dec 15, 2033), the system offers: "Would you like to send a gift with this message?"
3. Michael clicks "Browse Legacy Gifts." Gift catalog opens as a modal: categories (Jewelry, Books, Keepsakes, Custom). Filter by price range.
4. Michael selects a gold locket engraved with "Always with you." Price: $95. He adds "– Dad" in the personalization field.
5. System shows: "Your gift will be held and shipped in December 2033. You will be charged $95 today. Full refund if circumstances change."
6. Michael confirms payment. Gift order is created in "Pending — Trigger Unfired" state.
7. System sends Michael a confirmation: "Maya's locket is reserved and will ship when she turns 18."
8. 30 days before Maya's 18th birthday: system sends Maya (or her guardian, if she is still a minor at time of trigger — but she won't be at 18) an address collection form: "A special delivery is coming for you. Please confirm your shipping address."
9. Maya submits her address.
10. On Dec 1, 2033 (2 weeks before trigger date): gift order is passed to fulfillment partner with shipping details. Target arrival: Dec 14–15, 2033.
11. On Dec 15, 2033: message unlock email fires (Flow 2). Maya also receives a gift shipping notification from the fulfillment partner (co-branded with Legacy Architect).
12. Maya's unlock page shows: "A physical gift from your dad is also on its way." Includes tracking link once available.
13. Commission: Legacy Architect earns $14.25–19.00 on the $95 order (15–20%).

---

## 7. Technical Requirements

### 7.1 Platform

| Layer | Technology |
|---|---|
| Web Frontend | Next.js 14+ (App Router), TypeScript, TailwindCSS |
| Mobile App | React Native (Expo managed workflow), iOS + Android |
| Backend API | Node.js / NestJS, REST + WebSocket for real-time events |
| Authentication | Auth0 or Supabase Auth (JWT + refresh tokens) |
| Database | PostgreSQL (primary relational store) |
| Media Storage | AWS S3 or Cloudflare R2 (object storage — temp + processed media) |
| Permanent Archive | Arweave (all finalized/sealed media mirrored here post-processing) |
| Blockchain | Polygon (delivery instructions, guardian votes, unlock conditions, audit trail) |
| Email | SendGrid (transactional + lifecycle) |
| SMS / OTP | Twilio |
| Push Notifications | Firebase Cloud Messaging (FCM) |
| Background Jobs | BullMQ (Redis-backed job queue) |
| CDN | Cloudflare |
| Hosting | Vercel (web) + Railway or Render (backend API) |

---

### 7.2 Database Schema (High-Level)

Key entities:
- **User** (creator, recipient, guardian, advisor — roles are applied to users)
- **Vault** (belongs to User, contains messages, recipients, guardians)
- **Message** (belongs to Vault, has type, content refs, status, trigger_id)
- **Trigger** (type: date|age|life_event|inheritance|emergency, condition data, status)
- **Recipient** (belongs to Vault, may or may not have a User account yet)
- **Guardian** (belongs to Vault, linked to User, status: invited|active|retired)
- **GuardianVote** (emergency release votes, linked to guardian and vault)
- **LegacyGift** (linked to Message + Trigger, fulfillment status, order data)
- **AdvisorClient** (M2M: Advisor User ↔ Client User ↔ Vault)
- **AuditLog** (append-only log of all significant events — every state change)
- **BlockchainRecord** (references to Polygon tx hashes for auditability)
- **MediaFile** (processing status, S3 ref, Arweave CID, encryption metadata)

---

### 7.3 Security

- **E2E Encryption:** Message media is encrypted at rest (AES-256) and in transit (TLS 1.3). Encryption keys are per-vault, stored in a key management service (AWS KMS or HashiCorp Vault). Creator holds conceptual ownership of the key; platform cannot read content.
- **Identity Verification:** Account creation requires email verification. Recipient unlock requires OTP. Guardian actions require re-authentication.
- **Minor protection:** Creators designate recipients as minors. Minor-flagged messages require guardian/parent confirmation before unlock.
- **Data access:** Advisor can see vault metadata only — NEVER message content. Hard-coded ACL rule. Audited.
- **Breach response:** If a data breach occurs, content encryption means user content is not exposed. Metadata (names, emails, trigger dates) is the exposure risk. PII minimization strategy applies.
- **Password reset:** Time-limited tokens, no security questions. MFA optional for creators, recommended for advisors.
- **Audit logging:** All privileged actions (guardian vote, emergency release, advisor vault view, message unseal) are written to an immutable audit log.

---

### 7.4 Blockchain (Polygon)

Polygon is used for selective, auditable permanence — not for all data.

**What goes on-chain:**
- Guardian assignment transactions (guardian ID, vault ID, role, timestamp)
- Guardian vote events (vote cast, quorum reached)
- Emergency release authorization events
- Message seal transactions (hash of message metadata — not content — with creation timestamp)
- Trigger condition definitions (at time of sealing — proves the conditions were set before the creator died)
- Delivery execution events (message delivered to recipient, timestamp)

**What does NOT go on-chain:**
- Message content (ever)
- PII (names, emails, addresses)
- Full message metadata

**Why Polygon:**
- Low gas fees (essential for high-volume event logging)
- EVM-compatible, mature tooling
- Sufficient for audit/proof use case (no need for L1 Ethereum cost)

**Smart contracts needed:**
- `VaultRegistry.sol` — registers vault IDs on-chain
- `GuardianRegistry.sol` — records guardian assignments
- `TriggerProof.sol` — stores trigger condition hashes
- `DeliveryLog.sol` — records delivery events

---

### 7.5 Arweave (Permanent Media)

- All sealed messages are mirrored to Arweave after processing. The Arweave transaction ID (TxID) is stored in the MediaFile table.
- Arweave mirroring happens asynchronously post-seal (BullMQ job). It is not blocking.
- Creator is shown their Arweave TxID after sealing: "Your message is permanently archived. [View on Arweave Explorer]"
- Arweave cost is absorbed into platform operating costs and factored into subscription pricing.
- Cost estimate: ~$0.003/MB at current AR prices. A 100MB video ≈ $0.30. At 10,000 videos sealed/month = $3,000/month arweave cost. Factored into P1 and P2 tier pricing.

---

### 7.6 Scalability

- Backend: stateless NestJS services, horizontally scalable behind a load balancer.
- Media processing: video transcoding is the main compute cost. Use AWS Elastic Transcoder or FFmpeg workers (BullMQ). Async, non-blocking.
- Database: PostgreSQL with read replicas for heavy read queries (vault dashboard, advisor roster). Connection pooling via PgBouncer.
- CDN: all media delivery (to recipients) served from Cloudflare CDN with signed URLs (expiry: 24 hours per unlock session).
- Job queue: BullMQ with Redis. Trigger evaluation runs on a scheduled cron (every hour). High-priority jobs (message delivery) run immediately.
- Target scale at launch: 1,000 active vaults. Architecture should support 100,000 vaults without redesign.
- Multi-region: single-region at launch (US-East). Multi-region at Phase 4.

---

### 7.7 Key Technical Risks

| Risk | Description | Mitigation |
|---|---|---|
| Arweave cost spike | AR token price volatility could spike storage costs unexpectedly | Hedge with pre-purchased AR storage credits; monitor AR/USD monthly; build cost buffer into pricing |
| Polygon deprecation/migration | Polygon ecosystem changes (merger with AggLayer, etc.) could require contract migration | Use upgradeable proxy contracts; maintain migration playbook; abstract blockchain layer in codebase |
| Media transcoding bottleneck | Video upload volume spikes overwhelm transcoding queue | Autoscaling transcoding workers; queue depth monitoring; user-facing upload status transparency |
| Long-horizon data survival | Legacy Architect must outlive companies. What if Legacy Architect closes? | Arweave guarantees storage independent of LA; users can export all their content at any time; export-on-cancel feature is mandatory |
| Email deliverability at trigger time | Recipient hasn't checked that email in years; message delivery fails | Multiple delivery channels (email + SMS); retry logic; fallback guardian notification; allow recipient to register preferred future contact method |
| Key management at scale | Encryption keys must survive creator death without compromise | Use KMS with guardian-based key recovery process; document and test key recovery path in Phase 1 |

---

## 8. Monetization Model

### 8.1 B2C Subscription Tiers

| Tier | Name | Price | What's Included |
|---|---|---|---|
| **Free** | Seed | $0/month | 1 message, 1 recipient, 500MB storage, date trigger only, email delivery. No AI coach. No guardian system (basic only). Permanent — no expiry. Designed to convert. |
| **Tier 1** | Legacy | $9/month or $79/year | 25 messages, 5 recipients, 10GB storage, all trigger types (date, age, life event), guardian system (up to 3 guardians), Arweave archive, Polygon audit trail. AI Coach (Phase 2). |
| **Tier 2** | Heritage | $19/month or $159/year | 100 messages, 15 recipients, 50GB storage, everything in Legacy + Family Vault access (up to 10 family members), Time Collapse feature highlighted, priority support, Legacy Gifts access. |
| **Tier 3** | Dynasty | $39/month or $349/year | Unlimited messages, unlimited recipients, 250GB storage, everything in Heritage + Family Vault (up to 50 members), white-glove onboarding call, dedicated vault manager (async), API access (Phase 5). |

**Annual discount:** ~33% off monthly rate for annual commitment (standard SaaS practice).

**Storage overages:** $0.10/GB/month for usage above tier limit (auto-billing, user notified at 80% of limit).

---

### 8.2 B2B Licensing Model (Wealth Managers)

| Package | Price | What's Included |
|---|---|---|
| **Advisor Starter** | $299/month | Up to 20 client vaults, advisor dashboard, bulk invitation, vault health reports, HFG-style advisor notes per client. No white-label. |
| **Advisor Pro** | $599/month | Up to 100 client vaults, everything in Starter + priority onboarding support, quarterly business review call, co-branded invitation emails, inheritance event alerts. |
| **Firm License** | $1,499/month | Unlimited client vaults for up to 10 advisors in one firm, everything in Pro + white-label option (advisor firm branding on client-facing emails and vault pages), dedicated integration support, custom reporting. |
| **Enterprise / Family Office** | Custom pricing (~$3,000–8,000/month) | Full white-label, API integration with advisor CRM, custom trigger types, dedicated success manager, SLA guarantee. |

**Each advisor-provisioned client counts against the advisor's vault allocation.** Clients do NOT pay separately — their vault is covered by the advisor's license. This is the key B2B value prop: "We provide this as a service to your clients."

**Annual commitment discount:** 2 months free for annual B2B contracts.

---

### 8.3 Legacy Gifts Commission Model

- Legacy Architect earns **17.5% blended commission** on all Legacy Gift GMV (midpoint of 15–20% range).
- No subscription required to access Legacy Gifts — available on Heritage tier and above (B2C) and all B2B tiers.
- Fulfillment partner relationship: Legacy Architect takes commission off the top, remits remainder to partner monthly.
- Target gift AOV: $85. At 17.5% commission = $14.88 per gift.
- Target: 500 active gifts/month by end of Phase 3 = ~$7,400/month in gift revenue.
- Scaling to 5,000 gifts/month by end of Phase 4 = ~$74,400/month.

---

### 8.4 Freemium Entry Point

The **Seed tier (free)** is the freemium entry point. It is deliberately limited (1 message, 1 recipient) but not crippled — the experience is beautiful and the single message is permanent. The goal of Seed: let someone record one important message with zero friction. The emotional weight of having done it creates the conversion moment.

**Conversion trigger:** After recording their first message, users see a soft upgrade prompt: "You have 24 more things to say. Unlock them with Legacy plan." Conversion email sequence: 3 emails over 14 days focused on emotional stories, not features.

**Expected B2C free→paid conversion rate:** 8–12% within 90 days of first message.

---

### 8.5 LTV Estimates Per Tier

| Tier | Monthly Revenue | Annual Revenue | Churn Assumption | Avg. Tenure | LTV |
|---|---|---|---|---|---|
| Legacy (B2C) | $9 | $79 (annual) | 15%/year | 6.7 years | ~$530 |
| Heritage (B2C) | $19 | $159 (annual) | 10%/year | 10 years | ~$1,590 |
| Dynasty (B2C) | $39 | $349 (annual) | 8%/year | 12.5 years | ~$4,360 |
| Advisor Starter (B2B) | $299 | $3,588 | 20%/year | 5 years | ~$17,940 |
| Advisor Pro (B2B) | $599 | $7,188 | 15%/year | 6.7 years | ~$48,160 |
| Firm License (B2B) | $1,499 | $17,988 | 10%/year | 10 years | ~$179,880 |

*Note: B2C churn is expected to be unusually low vs. typical SaaS due to the nature of the product — users have irreplaceable content stored. This makes Legacy Architect structurally sticky in a way few products are.*

---

## 9. Competitive Analysis

### SafeBeyond

**What they do:** Video and voice messages stored for posthumous delivery. Date-based triggers and some life event triggers. Basic subscription model.  
**Pricing:** ~$9.99/month or $99/year.  
**Key weakness:** Limited trigger sophistication. No B2B model. No physical gift delivery. No family vault. No AI coaching. No blockchain permanence. Aesthetically dated. Declining growth signals.  
**How Legacy Architect beats them:** Superior trigger system, Time Collapse (unique), Family Vault, Legacy Gifts, wealth manager B2B, Arweave permanence, AI coach, modern UX. SafeBeyond is a feature; Legacy Architect is a platform.

---

### StoryWorth

**What they do:** Weekly prompts to help family members write their life stories. Compiled into a printed book at end of year. Subscription + book purchase.  
**Pricing:** $99/year per person. Book: $99–189.  
**Key weakness:** Backward-looking (capturing history, not delivering the future). No video. No time-locked delivery. No triggers. Linear product — you use it once and you're done. No B2B model.  
**How Legacy Architect beats them:** Legacy Architect is forward-looking (delivery at the right future moment). Video and voice are more emotionally powerful than text. Ongoing vault relationship vs. one-year project. StoryWorth is a journalism tool; Legacy Architect is a delivery infrastructure.

---

### Capsule.me

**What they do:** Time capsule app. Record a video capsule to be opened at a specific date. Primarily individual use. Free with limited premium features.  
**Pricing:** Free base, ~$5/month premium.  
**Key weakness:** Date-only triggers. No life event intelligence. No guardian system. No family network. No B2B. No permanence guarantee. Primarily a novelty product, not a serious legacy tool.  
**How Legacy Architect beats them:** Capsule.me is the toy version of what Legacy Architect does seriously. Richer trigger system, guardian trust architecture, Arweave permanence, B2B distribution, gift delivery. Not a direct competitor at the price and seriousness levels Legacy Architect targets.

---

### FutureMe

**What they do:** Write a letter to your future self, delivered by email on a date you choose. Public community of shared letters. Free.  
**Pricing:** Free (public letters). Small donation model.  
**Key weakness:** Only letters. Only to self. Only date trigger. No media. No recipients other than self. No family. No permanence. No B2B. Essentially a novelty email scheduler.  
**How Legacy Architect beats them:** Not a competitor. Different product entirely. FutureMe is a journaling tool for individuals. Legacy Architect is a multi-generational family delivery platform.

---

### HereAfter AI

**What they do:** AI that learns your voice and stories so loved ones can have conversations with an AI version of you after you die. Voice cloning + chatbot.  
**Pricing:** ~$9.99/month during life.  
**Key weakness:** Deeply ethically contested. AI-generated responses are not YOU — they're a simulation. No ability to control what the AI says. Grieving families interacting with an AI ghost is psychologically complex and potentially harmful. No life-event triggers. No physical gifts. No B2B. Significant ethical and legal exposure.  
**How Legacy Architect beats them:** Legacy Architect is the authentic alternative. Your real words. Your real voice. Your real face. No AI impersonation. Legacy Architect's AI helps you speak better — it doesn't speak for you. This is a core positioning advantage as the AI ethics conversation intensifies.

---

### Competitive White Space Summary

| Capability | SafeBeyond | StoryWorth | Capsule.me | FutureMe | HereAfter AI | **Legacy Architect** |
|---|---|---|---|---|---|---|
| Video/Voice/Letter | Partial | Letter only | Video only | Letter only | Voice (AI) | ✅ All formats |
| Life Event Triggers | Partial | ❌ | ❌ | ❌ | ❌ | ✅ |
| Time Collapse | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ Unique |
| Family Vault | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| AI Coach (authentic) | ❌ | ❌ | ❌ | ❌ | ❌ (impersonation) | ✅ |
| Guardian System | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| Blockchain Permanence | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| Physical Gifts | ❌ | Book only | ❌ | ❌ | ❌ | ✅ |
| Wealth Manager B2B | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |

**Legacy Architect owns the white space at the intersection of:** emotional delivery platform + institutional B2B distribution + authentic AI assistance + blockchain longevity + multi-generational family architecture + physical world gift delivery.

No competitor comes close to this combination. The closest threat is a well-funded startup entering this space. Speed to market and B2B pilot credibility (HFG) are the moats.

---

## 10. Go-to-Market Strategy

### Phase 1 — B2B Pilot: HFG Wealth Management (Now — Month 3)

**Objective:** Validate the core product with one real advisor and a handful of real clients. Generate a case study. Prove the B2B acquisition model before spending on B2C.

**Action steps:**
- Provision Larry Harvey with advisor dashboard (manual setup for pilot).
- Larry identifies 5–10 willing HFG clients as pilot participants.
- White-glove onboarding: Legacy Architect team assists each client via video call or written guide.
- Record qualitative feedback from both Larry and clients after 30 and 60 days.
- Goal: at least 3 clients with sealed messages by end of pilot.
- Output: written case study + 1-2 video testimonials (with permission). These become the anchor content for B2B sales.

**KPIs for Phase 1:** 1 advisor active, 10 clients provisioned, 5+ sealed messages, 1 case study published.

---

### Phase 2 — B2C Launch: Emotional Storytelling (Month 4–9)

**Objective:** Drive B2C signups through earned media and emotional content, not paid advertising.

**Channels:**
- **Long-form content:** Founding story blog post on the Legacy Architect site. "The message that never got sent" — a piece about why this exists.
- **Social:** Short-form video content (Instagram Reels, TikTok, YouTube Shorts) — real stories of messages left and received. No product demos — pure emotion. Target 3–5 pieces/week.
- **PR:** Pitch to parenting media (Parents.com, Fatherly, The Dad), personal finance media (The Balance, NerdWallet adjacent), and estate planning trade press.
- **Email waitlist:** Build pre-launch waitlist via a single landing page + lead magnet: "10 Questions to Ask Yourself Before It's Too Late" — a free PDF prompt guide. Target: 2,000 waitlist subscribers before B2C launch.
- **Reddit:** Organic participation in r/personalfinance, r/Parenting, r/widowers, r/grief — helpful, not promotional.
- **Partnership:** Parenting podcasts (Good Inside, Raising Good Humans, etc.) — pitch for interview/sponsorship.

**Key marketing angles:**
1. **Time Collapse** — The emotionally unique feature. "What would you say to your daughter at 42, when she's 42?"
2. **Don't be the person who didn't leave a message** — Fear of absence framing.
3. **Your words will outlive you. But only if you record them.** — Urgency + permanence.
4. **The Great Wealth Transfer needs a human layer.** — B2B angle.
5. **This is not AI writing for you. This is your real voice, forever.** — Differentiation from HereAfter AI.

---

### Phase 3 — B2B Scale (Month 10–18)

**Objective:** Turn the HFG case study into a repeatable B2B acquisition machine.

**Channels:**
- **Direct outreach:** Use HFG case study in cold outreach to 200 target wealth management firms (AUM $500M–$10B range). LinkedIn + email.
- **Referral program:** HFG and other pilot advisors refer peer advisors. Incentive: 1 month free per successful advisor referral.
- **Conference presence:** NAPFA (National Association of Personal Financial Advisors), FPA (Financial Planning Association), TD Ameritrade LINC — speaking slot or booth.
- **Estate attorney channel:** Estate attorneys are upstream of wealth managers. Partner with 10–20 attorneys to refer clients. Commission model: $50 referral fee per activated client vault.
- **Family office network:** Tiger 21, UHNW circles — white-glove outreach.
- **Content marketing for advisors:** "How Legacy Architect helped us retain the next generation" — advisor-focused case study library.

---

## 11. Success Metrics (KPIs)

### Activation

| Metric | Definition | Target (Month 6) | Target (Month 12) |
|---|---|---|---|
| Signup → First Message | % of signups who record at least 1 message | 40% | 55% |
| Time to First Message | Median time from account creation to first message sealed | < 7 days | < 5 days |
| Onboarding Completion | % who complete guardian setup | 50% | 65% |

---

### Engagement

| Metric | Definition | Target (Month 6) | Target (Month 12) |
|---|---|---|---|
| Messages per Active User | Avg number of sealed messages per paid user | 3 | 6 |
| Avg Vault Size | Total recipients per active vault | 2.5 | 4 |
| Monthly Active Users | Users who log in or add a message in last 30 days | 60% of paid base | 50% of paid base |
| Time Collapse Adoption | % of paid users who record a Time Collapse message | 15% | 25% |

---

### Retention

| Metric | Definition | Target |
|---|---|---|
| Annual Retention (B2C) | % of annual subscribers who renew | ≥ 80% |
| Monthly Churn (B2C) | Monthly subscriber churn rate | < 2% |
| B2B Contract Renewal | % of advisor licenses that renew annually | ≥ 85% |
| Net Revenue Retention (B2B) | Including upsells | ≥ 105% |

---

### B2B

| Metric | Definition | Target (Month 6) | Target (Month 12) |
|---|---|---|---|
| Advisors Onboarded | Active advisor accounts | 1 (HFG) | 10 |
| Clients per Advisor | Avg client vaults per active advisor | 8 | 15 |
| Advisor-Activated Vaults | Client vaults created via advisor channel | 8 | 150 |
| Advisor NPS | Net Promoter Score from advisors | — | ≥ 50 |

---

### Revenue

| Metric | Target (Month 6) | Target (Month 12) | Target (Month 18) |
|---|---|---|---|
| MRR | $5,000 | $25,000 | $75,000 |
| ARR | $60,000 | $300,000 | $900,000 |
| B2B % of Revenue | 60% | 45% | 40% |
| Legacy Gift GMV | $0 (not yet launched) | $0 (not yet launched) | $50,000/month |
| Paid B2C Users | 100 | 500 | 1,500 |

---

## 11b. Infrastructure Cost Model

### Overview
Legacy Architect has exceptional unit economics. The primary cost driver is video storage. All other infrastructure costs scale slowly relative to revenue.

### Storage Assumptions
- Average user: 15 messages over platform lifetime
- Average video message: 3 minutes at 720p compressed = ~150–200MB
- Average total storage per user: ~2.5GB

### Monthly Infrastructure Costs by Scale

| Users | Storage (Cloudflare R2) | Database (Supabase) | Backend (Railway) | Video Processing | Email (SendGrid) | **Total/month** |
|---|---|---|---|---|---|---|
| 500 | ~$15 | $25 | $50 | ~$75 | $20 | **~$185** |
| 5,000 | ~$150 | $100 | $200 | ~$300 | $75 | **~$825** |
| 50,000 | ~$1,500 | $500 | $1,500 | ~$2,000 | $300 | **~$5,800** |

*Storage: Cloudflare R2 at ~$0.015/GB/month. Video processing: AWS MediaConvert at ~$0.015/min.*

### Gross Margin by Tier

| Users | MRR (mid-tier $19/mo) | Infra Cost | **Gross Margin** |
|---|---|---|---|
| 500 | $9,500 | $185 | **98%** |
| 5,000 | $95,000 | $825 | **99.1%** |
| 50,000 | $950,000 | $5,800 | **99.4%** |

This is among the highest-margin SaaS product categories. Marginal cost per new user is near zero after fixed infrastructure is established.

### B2B (HFG Pilot) Specific Costs
- 500 HFG clients on platform: ~$185/month infrastructure
- HFG pays $1,500–5,000/month (depending on tier)
- **Gross margin on HFG account: 96–97%**

### Arweave / Blockchain Cost Strategy
Full Arweave storage for video (~$5–10/GB one-time) is cost-prohibitive at scale (~$12–25 per user upfront). Recommended phased approach:

| Phase | Storage Approach | Cost |
|---|---|---|
| Phase 1 (MVP) | Cloudflare R2 + SLA guarantee + longevity fund | ~$0.015/GB/month |
| Phase 2 | Arweave for metadata only (unlock conditions, guardian assignments — kilobytes, not GB) | ~$0.01/user one-time |
| Phase 3 | Hybrid: hot storage in R2, cold archive to Arweave for older messages | Negligible per user |

**Longevity Fund:** 5% of every subscription goes into a ring-fenced endowment. Marketing message: *"Your messages are guaranteed to outlive the company."* More compelling than "we use blockchain" — and honest.

### Build Cost (AI-Assisted)
Traditional development estimate: $40–60K
AI-assisted build (primary path): $7–15K
- Part-time developer for QA and integrations: $5–10K
- Infrastructure and third-party setup: $2–3K
- Design (largely done via Signal deliverables): minimal

**Timeline: 8 weeks to beta (AI-assisted) vs 16 weeks traditional**

### Year 1 Financial Model (HFG Pilot + 200 B2C users)

| Revenue Stream | Monthly | Annual |
|---|---|---|
| HFG pilot fee (Pilot tier) | $1,500 | $18,000 |
| 200 B2C users (avg $15/mo) | $3,000 | $36,000 |
| Legacy Gift commissions (est.) | $500 | $6,000 |
| **Total Revenue** | **$5,000** | **$60,000** |
| Infrastructure costs | $300 | $3,600 |
| **Gross Profit** | **$4,700** | **$56,400** |
| **Gross Margin** | **94%** | **94%** |

*Excludes founder time, marketing costs, and any developer fees.*

---

## 12. Risks & Mitigations

### Risk 1: Company Survival / Platform Longevity

**Risk:** Legacy Architect closes, and users lose irreplaceable content permanently.  
**Severity:** Critical. This is an existential trust risk — the whole product is built on the promise of permanence.  
**Mitigation:**
- Arweave mirroring ensures content survives platform shutdown independently.
- Users can export all content at any time (self-service export feature — mandatory, not optional).
- Legal commitment in Terms of Service: 12-month data preservation window if company closes.
- "Data Endowment" fund: ring-fence a portion of subscription revenue (2–5%) into a reserve fund specifically for data preservation operations. Transparently disclosed to users.
- Blockchain record ensures trigger conditions are publicly auditable even if platform closes.
- Explore partnership with a nonprofit digital preservation organization (Internet Archive) as a long-horizon failsafe.

---

### Risk 2: Legal / Regulatory

**Risk:** Legacy Architect is positioned as a "digital ethical will." In some jurisdictions, there may be legal ambiguity about the relationship between digital messages and probate law. Additionally, GDPR, CCPA, and data residency regulations create compliance complexity.  
**Severity:** Medium–High.  
**Mitigation:**
- Clear legal disclaimer in product: "Legacy Architect is not a legal will and does not have legal standing in probate proceedings. It is a personal communication platform."
- Legal review: contract an estate planning attorney to review all Terms of Service, particularly around guardian authority, inheritance triggers, and message ownership.
- GDPR compliance: data residency options (EU data stored in EU region) by Phase 2.
- CCPA compliance: data deletion request flow built into user settings at launch.
- Avoid language that implies legal authority. No "will," "estate," "legally binding" in marketing copy.
- Consider a legal advisory board (1–2 estate planning attorneys) to guide policy.

---

### Risk 3: Emotional Misuse

**Risk:** Messages are used to manipulate, guilt, or harm recipients. A creator records an abusive message to be delivered posthumously. A message intended as loving arrives at a traumatic moment and causes psychological harm.  
**Severity:** Medium. Not frequent, but high-impact when it occurs.  
**Mitigation:**
- Terms of Service: explicit prohibition on harassing, threatening, or abusive message content. Violations = account termination.
- Content moderation policy: automated CSAM scanning. Report mechanism for recipients post-delivery.
- Recipient controls: recipients can opt out of receiving future messages from a specific creator (pre-delivery, if known to recipient; post-delivery, for future messages).
- Crisis resource: if a recipient's unlock event is flagged as emotionally high-risk (e.g., death of creator), show a discreet mental health resource alongside the message.
- Guardian responsibility: guardians are instructed that part of their role is ensuring messages are appropriate. (This is a social/normative control, not a technical one.)

---

### Risk 4: Blockchain Dependency

**Risk:** Polygon network changes, high gas fees, or smart contract vulnerabilities could compromise the auditability layer.  
**Severity:** Medium.  
**Mitigation:**
- Blockchain is the audit/proof layer only — never the primary data store. Platform functions fully without blockchain. Blockchain is additive.
- Upgradeable proxy contracts allow migration without re-deploying core logic.
- Gas cost monitoring with automated alerts. Switch to batched transactions if gas spikes.
- Maintain an off-chain audit log (PostgreSQL) that mirrors all blockchain events. Users have two sources of truth.
- If Polygon becomes untenable: migration path to Base, Arbitrum, or another EVM-compatible L2 is straightforward given the abstraction layer.

---

### Risk 5: Gift Fulfilment Failure

**Risk:** A Legacy Gift fails to arrive on the trigger date (stockout, shipping failure, wrong address). This is not just a logistics failure — it's an emotional failure that can be devastating if the creator is deceased.  
**Severity:** High on emotional impact, medium on frequency.  
**Mitigation:**
- Address collection 30 days in advance with 2 reminder contacts.
- Fulfillment partner SLA: guaranteed processing 14 days before trigger date.
- Backup fulfillment: if primary partner cannot fulfill, Legacy Architect has a secondary partner.
- If gift cannot be delivered: creator (if living) is notified immediately. If creator is deceased, guardian is notified. Digital message still delivered on time regardless of gift status.
- Post-trigger quality check: email to recipient 7 days post-trigger: "Did your gift arrive?" Manual follow-up if no.
- Gift hold reserve: payment is held until trigger fires + 30 days. Refund if fulfillment fails.

---

### Risk 6: Technical Single Points of Failure

**Risk:** Core infrastructure failure (database outage, encryption key loss, CDN failure) at a trigger moment causes message delivery failure.  
**Severity:** High for individual affected users.  
**Mitigation:**
- Database: daily automated backups, point-in-time recovery, read replicas.
- Encryption keys: stored in KMS with automatic rotation and guardian-based recovery path.
- Delivery system: retry logic with exponential backoff. If primary email fails, fallback to SMS.
- Multi-channel delivery: email + SMS + in-app notification for trigger events.
- Status page: public uptime page. Users notified proactively of any service disruptions.
- Trigger queuing: messages due for delivery are queued 24 hours in advance, reducing point-of-failure risk.

---

### Risk 7: B2B Pilot Failure (HFG)

**Risk:** The HFG pilot does not generate the expected traction — Larry Harvey's clients don't adopt, or the workflow doesn't fit his practice.  
**Severity:** High for go-to-market timeline. Not existential.  
**Mitigation:**
- Set clear success criteria with Larry before pilot starts (written). Agree on what "success" looks like.
- Assign a dedicated pilot success owner at Legacy Architect (founder initially).
- Weekly check-in with Larry during pilot period.
- If adoption is low: diagnose the blocker (product friction? client hesitation? advisor workflow mismatch?) and iterate fast.
- Pilot is Phase 0 — there is no public launch yet. Failure is learnable, not catastrophic.
- Parallel: maintain 2–3 backup advisor relationships as plan B for B2B validation.

---

### Risk 8: Grief / Timing Sensitivity

**Risk:** A message is delivered at the wrong time — before the creator dies, due to a false guardian emergency, or to a recipient who is not emotionally prepared.  
**Severity:** Medium — emotionally significant.  
**Mitigation:**
- 30-day challenge window for emergency releases prevents accidental delivery.
- Creator can review and update trigger conditions annually (prompted).
- Recipient has a "not ready" option at unlock: "I'm not ready to open this yet. Remind me in [7 days / 30 days]."
- Guardian training: clear guidance on what constitutes a valid emergency release trigger.
- Crisis resources displayed at unlock (see Risk 3).

---

## 13. Roadmap

### Phase 0 — Now: B2B Pilot with HFG (Month 0–3)

**Goal:** Validate that wealth managers will use this, and that their clients will record messages.

| Deliverable | Description |
|---|---|
| Advisor dashboard (manual) | Provision Larry Harvey with a working advisor dashboard (can be partially manual/Airtable-backed in this phase) |
| Core vault creation | Creator can add message (video + letter, minimum), set a date trigger, seal message |
| Guardian system (basic) | Add 1-3 guardians, annual check-in ping |
| Recipient email delivery | Trigger fires → email to recipient with unlock link |
| Recipient unlock page | Clean unlock + identity verification + message playback |
| Arweave mirroring | Sealed media is mirrored to Arweave post-seal |
| HFG onboarding | White-glove onboarding of 5-10 HFG clients |

**Tech stack confirmed. No mobile app in Phase 0. Web-only.**

---

### Phase 1 — Month 0–6: MVP Public Launch

**Goal:** Public B2C launch with full core feature set. 100 paid users.

| Feature | Priority |
|---|---|
| All message types (video, voice, letter, photo/doc) | P1 |
| All trigger types (date, age, life event, inheritance) | P1 |
| Time Collapse feature | P1 |
| Guardian system (full — 3 guardians, 2/3 vote) | P1 |
| Emergency release system (30-day window) | P1 |
| Recipient onboarding (full flow) | P1 |
| Notification system (email) | P1 |
| B2C subscription billing (Stripe) | P1 |
| Seed (free) tier | P1 |
| Legacy and Heritage tiers | P1 |
| Polygon audit trail | P1 |
| Wealth Manager dashboard (full, automated provisioning) | P1 |
| Advisor Starter + Pro tiers | P1 |
| User settings (notifications, export, account) | P1 |
| Marketing site + SEO | P1 |

---

### Phase 2 — Month 6–12: AI Coach, Family Vault, Mobile App

**Goal:** Deepen engagement. Activate Family Vault for multi-generational use. Launch mobile.

| Feature | Priority |
|---|---|
| AI Message Coach | P2 |
| Family Vault (up to 10 members) | P2 |
| React Native mobile app (iOS + Android) | P2 |
| Dynasty B2C tier | P2 |
| Push notifications (mobile) | P2 |
| Time Collapse prompt library (expanded) | P2 |
| Unlimited letter length | P2 |
| Custom life event triggers (text) | P2 |
| Recipient "not ready" delay option | P2 |
| GDPR / CCPA compliance tooling | P2 |
| Referral program | P2 |

---

### Phase 3 — Month 12–18: Legacy Gifts, Blockchain Longevity Layer

**Goal:** Launch revenue-generating gift marketplace. Harden the longevity architecture.

| Feature | Priority |
|---|---|
| Legacy Gifts catalog + purchase flow | P3 |
| Address collection system (for gifts) | P3 |
| Fulfillment partner integration (API) | P3 |
| Arweave export (creator self-service) | P3 |
| Enhanced blockchain audit (DeliveryLog.sol) | P3 |
| Family Vault (up to 50 members) | P3 |
| Advisor co-branded emails | P3 |
| "Data Endowment" fund disclosure page | P3 |
| Minor recipient guardianship flow | P3 |

---

### Phase 4 — Month 18–24: B2B Scale, Wealth Manager Marketplace

**Goal:** Turn B2B into a scalable channel. Expand beyond HFG.

| Feature | Priority |
|---|---|
| Firm License tier + multi-advisor support | P3 |
| White-label advisor branding | P3 |
| Advisor referral program | P3 |
| Estate attorney channel (referral program) | P3 |
| Multi-region deployment (EU data residency) | P3 |
| Enhanced advisor reporting | P3 |
| Bulk client import (CSV + CRM API, beta) | P3 |
| Legacy Gifts international shipping (UK/AU/CA) | P3 |
| Conference sales playbook + materials | P3 |

---

### Phase 5 — Month 24+: Open API, White-Label, International

**Goal:** Become the infrastructure layer for legacy communication. Platform play.

| Feature | Description |
|---|---|
| Open API | Allow 3rd-party integrations (estate planning software, CRMs, insurance platforms) |
| White-label full platform | Full white-label for large enterprise clients |
| International localization | Spanish, Portuguese, German, French at minimum |
| Legacy Token / NFT proof (optional) | On-chain proof-of-legacy NFT for message recipients — a collectible artifact |
| Insurance channel | Partner with life insurance providers as B2B2C distribution |
| Family office product tier | Ultra-high-net-worth product with dedicated relationship manager |

---

## 14. Open Questions

The following decisions require founder input before development begins.

| # | Question | Why It Matters | Decision Needed By |
|---|---|---|---|
| OQ1 | **What is the primary legal entity structure?** Delaware C-Corp? LLC? This affects fundraising, advisor agreements, and the "Data Endowment" structure. | Legal setup is prerequisite for B2B contracts with HFG. | Before Phase 0 launch |
| OQ2 | **Who owns the guardian system liability?** If guardians vote incorrectly (false emergency release), what is Legacy Architect's legal exposure? Terms of Service must explicitly disclaim liability, but legal review is needed. | Significant legal and ethical risk if not clarified. | Before Phase 0 launch |
| OQ3 | **Content moderation policy: who reviews flagged messages?** If a recipient reports an abusive message, who reviews it? Internal team? Third-party moderator? What's the SLA? | Emotional misuse risk management requires a concrete policy, not just a rule in ToS. | Before Phase 1 public launch |
| OQ4 | **Pricing validation: is $9/month right for Legacy tier?** This was set based on competitive benchmarking. Suggest testing with a small waitlist group (pricing survey + stated willingness to pay) before hardcoding into billing. | Wrong pricing at launch is hard to walk back. | Before Phase 1 billing launch |
| OQ5 | **Key recovery design: what happens if Legacy Architect has zero knowledge of encryption keys?** If we go full zero-knowledge architecture, we cannot recover lost content. If we hold keys in KMS, we have access (legal exposure, breach risk). What's the tradeoff we accept? | Fundamental security architecture decision that affects everything else. | Before Phase 0 technical build |
| OQ6 | **HFG pilot terms: is this free, discounted, or full price?** Larry Harvey's pilot terms determine how we structure future B2B pilots. Free pilot sets a precedent. Paid pilot is harder to close but creates real revenue signal. | Commercial precedent and relationship structure. | Immediately |
| OQ7 | **Recipient address collection for gifts: do we hold PII long-term?** Address collection 30 days before trigger fires is clean. But for some triggers (child's 18th birthday in 2040), do we hold address collection open for years? GDPR/CCPA implications. | Privacy architecture and legal compliance for Legacy Gifts feature. | Before Phase 3 |
| OQ8 | **Brand and domain:** Is "Legacy Architect" the final brand name? Exact domain and social handle availability needs to be confirmed. legacyarchitect.com — is it available or acquired? | Affects all marketing materials, legal filings, and technical setup. | Before any public-facing content |
| OQ9 | **Founding team:** Who is building this? Does Aidan have a technical co-founder or CTO? Or is this being contracted/outsourced? This affects roadmap feasibility and hiring strategy. | Phase 0 timeline depends entirely on who is building. | Before Phase 0 begins |
| OQ10 | **Investor/fundraising intent:** Is Legacy Architect being built to bootstrap, raise a pre-seed, or something else? This affects how aggressively we push toward paid users vs. growth metrics vs. profitability. | Changes the entire resource allocation strategy. | Strategy session with Aidan |

---

*Document prepared by The Signal Product Studio.*  
*Next step: UX Architecture brief and wireframe sprint for Phase 0 MVP flows.*  
*Version history: v1.0 — March 16, 2026 — Initial draft.*
