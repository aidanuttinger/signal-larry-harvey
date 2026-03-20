# Legacy Architect — Product Specifications

**Client:** Larry Harvey (HFG Wealth Management)  
**Project:** Proprietary messaging platform for high-net-worth families  
**Engagement Value:** $40,000 (4 months @ $10K/month)  
**Status:** In Development  

---

## Quick Reference

| Document | Purpose | Format |
|----------|---------|--------|
| **PRD.md** | Full product requirements document — vision, features, roadmap, financials | Markdown |
| **BRIEF-presentation.html** | Executive brief in beautiful format (navy/gold design) | HTML |
| **PRD-presentation.html** | PRD converted to presentation format | HTML |
| **ARCHITECTURE.md** | Technical architecture, tech stack, security model | Markdown |
| **DESIGN-SYSTEM.md** | UI/UX guidelines and design specifications | Markdown |
| **LAUNCH.md** | Launch strategy, go-to-market, customer acquisition | Markdown |
| **STATUS.md** | Current project status, blockers, milestones | Markdown |
| **SPRINT.md** | Development sprint details and timeline | Markdown |
| **QA.md** | Quality assurance criteria and testing strategy | Markdown |
| **DECISIONS.md** | Key decisions made and rationale | Markdown |

---

## What This Product Does

**Legacy Architect** is a time-locked messaging platform that allows high-net-worth families to:

1. **Record messages** in video, voice, letter, or document format
2. **Set release triggers** based on specific life events (inheritance, wedding, graduation, age milestones)
3. **Use Time Collapse** (unique feature) to record themselves at their current age for recipients to receive when the recipient reaches that same age
4. **Build a Family Vault** — multi-generational archive that persists across decades
5. **Manage guardians** — trusted people who confirm life events and vote on emergency message releases
6. **Attach physical gifts** — send both messages and curated physical gifts together

**Key Insight:** 70% of heirs change advisors after inheriting wealth. Legacy Architect anchors heirs emotionally to the family's values and their relationship with the advisor (HFG), long before the inheritance event.

---

## Nine Core Features

1. **Message Recording** — Video (up to 10 min), voice, letters (rich text), photo/document uploads
2. **Smart Unlock Triggers** — Date-based, age-based, life event-based, or custom triggers
3. **Time Collapse™** — Record at age X for recipient to receive when they turn age X (unique differentiator)
4. **Family Vault** — Multi-generational shared archive
5. **Guardian/Succession System** — 1–3 guardians manage life events and vote on emergency releases
6. **Emergency Release System** — 30-day challenge window protects against accidental releases
7. **AI Message Coach** (Phase 2) — Guided prompts to help users articulate their thoughts
8. **Legacy Gifts** (Phase 3) — Curated physical gifts attached to messages
9. **Wealth Manager Dashboard** (B2B) — Advisor provisioning, client vault management, event alerts

---

## Financial Model (Conservative Case)

### Revenue Streams
- **B2C Subscriptions:** $9–39/month per user (4 tiers)
- **B2B Licensing:** $299–1,499/month per advisor firm
- **Legacy Gift Commission:** 17.5% on gift GMV

### Year 1 Projection (HFG pilot + 200 B2C users)
- Total ARR: **$60,000**
- Gross margin: **94%** (after infrastructure)

### Founding Partner Benefits (HFG)
- 25% of all licensing revenue from other advisory firms (in perpetuity)
- Co-branding ("HFG Legacy Architect")
- 3-year market exclusivity
- Advisory board seat
- Founding rate locked (never increases)

---

## Development Roadmap

### Phase 0 — B2B Pilot (Now – Month 3)
HFG onboarding, basic vault, guardian system, email delivery

### Phase 1 — MVP Public Launch (Month 0–6)
All message types, all trigger types, Time Collapse, emergency release, B2C billing, advisor dashboard

### Phase 2 — AI + Mobile (Month 6–12)
AI Message Coach, Family Vault, iOS/Android app, premium tiers

### Phase 3 — Gifts & Scale (Month 12–18)
Legacy Gifts fulfillment, multi-advisor licensing, white-label support

### Phase 4 — Platform Play (Month 18+)
Open API, international localization, insurance partnerships

---

## Technology Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Next.js 14+, React Native, TailwindCSS |
| Backend | Node.js / NestJS |
| Database | PostgreSQL |
| Storage | AWS S3 / Cloudflare R2 (hot), Arweave (permanent) |
| Blockchain | Polygon (audit trail, not primary store) |
| Email | SendGrid |
| SMS | Twilio |
| Push | Firebase Cloud Messaging |
| Job Queue | BullMQ (Redis) |
| CDN | Cloudflare |

---

## Why This Wins

### Competitive White Space
- **SafeBeyond:** Weak triggers, no B2B, no permanence guarantee
- **StoryWorth:** Backward-looking (captures history), one-year project
- **Capsule.me:** Date-only triggers, novelty positioning
- **HereAfter AI:** AI impersonation (ethical problem), no control over messaging

### Legacy Architect's Advantages
✅ Time Collapse (unique, no competitor has this)  
✅ Institutional B2B distribution (wealth managers)  
✅ Authentic messaging (your actual voice, not AI)  
✅ Blockchain permanence (Arweave + Polygon)  
✅ Multi-generational architecture  
✅ Physical gift delivery integration  

---

## Risk Mitigation

| Risk | Mitigation |
|------|-----------|
| Platform longevity | Arweave mirroring, user data export, legal longevity commitment |
| Technical failure | Daily backups, read replicas, failover systems, multi-channel delivery |
| Emotional misuse | Content moderation, recipient controls, crisis resources |
| Gift fulfillment | Backup partners, SLA guarantees, quality checks |
| Blockchain dependency | Off-chain audit log mirrors blockchain, upgradeable contracts, migration playbook |

---

## Open Questions (For Larry)

1. **Legal entity structure** — Delaware C-Corp? LLC? (affects B2B contracts)
2. **Guardian system liability** — Who's responsible if guardians vote incorrectly?
3. **Content moderation** — Who reviews flagged messages and what's the SLA?
4. **Pricing validation** — Is $9/month right for Legacy tier? (suggest price testing)
5. **Key recovery design** — Zero-knowledge encryption vs. KMS access tradeoff?
6. **HFG pilot terms** — Free? Discounted? Full price?
7. **Recipient address collection** — When/how to collect PII for gift shipping?
8. **Founding team** — Who's building this? Technical co-founder needed?

---

## Next Steps

### If Larry Closes
1. Kickoff call → Phase 1 brand brief
2. Website research & competitor analysis
3. Create project timeline & milestones
4. Announce partnership publicly (with permission)

### If Larry is Pending
1. Schedule second presentation (technical deep dive)
2. Offer pilot/proof-of-concept at smaller scope
3. Identify remaining objections
4. Set hard decision date (by end of March)

---

## File History

| Date | Change | By |
|------|--------|-----|
| 2026-03-19 | Created initial PRD and project files | Signal Studio |
| 2026-03-19 | Integrated PRD into larry-legacy-architect-pitch.html | Claude Code |
| 2026-03-19 | Organized project under client folder structure | Claude Code |

---

**Last Updated:** March 19, 2026 — 22:55 GMT-3  
**Repository:** `/the-signal/clients/larry-harvey/legacy-architect/`  
**Status:** ✅ Ready for presentation
