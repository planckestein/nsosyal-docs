---
title: "NSosyal Innovation Research Playbook & Gap Matrix Specification"
version: "2.0 — Discovery First"
date: "2026-08-19"
purpose: "Standalone continuation document for broad feature discovery, gap exploration, and later-stage validation for the NSosyal İnovasyon Yarışması"
---

# NSosyal Innovation Research Playbook & Gap Matrix Specification

## 0. Why this document exists

This document is the **standalone operating manual** for continuing the NSosyal İnovasyon Yarışması research in a future chat/session without needing the original conversation.

The research has already moved through several stages:

1. Reverse-engineering the current NSosyal web/product surface.
2. Looking at established global platforms such as X, Threads, Bluesky, Reddit, Instagram, TikTok, YouTube, Discord, LinkedIn, and Mastodon.
3. Looking for **most-requested / repeatedly complained-about features** on major platforms.
4. Mining Chinese domestic platforms for product ideas.
5. Mining Chinese platforms for both:
   - user-protective security features, and
   - monitoring / operator-control capabilities.
6. Mining Russian domestic platforms.
7. Mining regional and niche platforms in Korea, Japan, Taiwan, India, Thailand, Germany, Vietnam, Indonesia, and elsewhere.
8. Identifying recurring product families rather than merely collecting isolated features.

The research should now continue in a way that is **broad, opportunistic, and creative first**, then become rigorous only when an idea begins to look promising.

The aim is not to prove every idea before writing it down.

The aim is to:

> **collect aggressively → notice patterns → combine ideas → identify promising directions → then verify the strongest ones carefully.**

---

# 1. Core research question

The central question is:

> **What can NSosyal add that could solve a real user problem, exploit a meaningful product gap, fit NSosyal unusually well, and become a convincing competition prototype?**

At the discovery stage, a candidate is worth recording if it satisfies even one of these:

- a platform somewhere implements something unusual,
- users repeatedly complain about a related problem,
- NSosyal appears weak in the area,
- a feature suggests an interesting synthesis,
- a local/domestic platform solved a problem differently from Western platforms,
- a niche community has a mechanic that could transfer surprisingly well,
- a security/privacy mechanism reveals a useful design principle,
- the idea simply produces a strong "why doesn't social media already do this?" reaction.

The **final project**, however, should eventually sit near the intersection of:

> **NSosyal gap**
>
> × **real or plausible user need**
>
> × **strong product idea**
>
> × **meaningful differentiation**
>
> × **technical feasibility**
>
> × **strong demo value**
>
> × **competition fit**
>
> × **acceptable privacy / abuse risk**

The first phase is exploration.

The second phase is validation.

Do not confuse them.

---

# 2. The two-mode research system

## MODE A — Discovery

This is the default mode while exploring regions, platforms, communities, or feature families.

The rule is:

> **Interesting is enough to enter the notebook.**

A discovery does **not** need:

- proof that NSosyal lacks it,
- proof that users are demanding it,
- multiple source platforms,
- official documentation,
- a polished prototype plan,
- a numerical score.

At this stage, weak signals are useful.

Examples:

- one obscure Japanese platform has a strange but clever feature,
- three Reddit users complain about the same thing,
- a Chinese app solves identity differently,
- an old forum had a feature modern social media abandoned,
- a regional app bundles community functions in an unusual way,
- a speculative combination suddenly seems powerful.

These should be captured immediately.

The cost of recording a weak idea is low.

The cost of prematurely discarding a potentially great idea is high.

---

## MODE B — Validation

Only switch to this mode when an idea becomes:

- repeatedly interesting,
- part of a larger pattern,
- clearly relevant to NSosyal,
- likely to enter a shortlist,
- or important enough to make factual claims about.

Then verify:

- whether NSosyal actually has it,
- whether users actually want it,
- whether the source platform really supports it,
- whether it is technically feasible,
- whether it fits competition rules,
- whether privacy/security risks are manageable,
- whether a prototype can demonstrate it.

The rule is:

> **Explore loosely. Validate ruthlessly.**

---

# 3. Idea maturity states

Instead of forcing every idea through hard evidence gates, give each idea a maturity state.

| State | Meaning |
|---|---|
| **SPARK** | Interesting idea or observation. Barely researched. |
| **SIGNAL** | Some evidence, precedent, or user-interest signal exists. |
| **PATTERN** | Similar need or mechanic appears across multiple sources/platforms. |
| **CONCEPT** | NSosyal-specific adaptation has been articulated. |
| **VALIDATING** | Being checked for demand, gap, feasibility, and risks. |
| **VALIDATED** | Strong enough evidence exists to support major claims. |
| **SHORTLIST** | Serious competition candidate. |
| **REJECTED** | Not worth pursuing further. |
| **PARKED** | Interesting but impractical or not timely. |

This is intentionally permissive.

A **SPARK** can still be extremely valuable.

---

# 4. Research principles

## 4.1 Collect before judging

When researching a platform, first ask:

> **What is unusual here?**

Do not immediately ask:

> Can we prove NSosyal users want it?

That comes later.

Record strange mechanics, even if they initially seem niche.

Some of the strongest discoveries so far came from platforms that were not obvious NSosyal analogues.

Examples:

- Pantip's "read up to here"
- Misskey Antennas
- Blind's verified anonymity
- Pixiv commissions
- BAND's organization tooling
- Douban's social objects
- Marshmallow's recipient-controlled moderation

None needed a demand study before becoming useful ideas.

---

## 4.2 Separate four different questions

Eventually, every serious concept should answer:

### A. Does anyone already implement it?

Product precedent.

### B. Do users appear to want the underlying outcome?

Demand.

### C. Does NSosyal already have something equivalent?

Gap.

### D. Can we adapt or combine it into something better for NSosyal?

Innovation.

But during discovery, **A alone may be enough to record an idea**.

Likewise, a strong user complaint may be worth recording even before any solution is known.

---

## 4.3 Distinguish current facts from design inference

Use three labels mentally or explicitly:

### Observed

> BAND supports shared calendars and RSVP.

### Inferred

> This suggests NSosyal Communities could become organization infrastructure.

### Speculative

> Turkish university clubs would probably adopt this heavily.

All three are useful.

Only the first is a factual source claim.

Do not suppress inference or speculation; just avoid presenting them as proven.

---

## 4.4 "Not found" is useful enough during exploration

Use simple NSosyal status labels:

| State | Meaning |
|---|---|
| **YES** | Clearly present in NSosyal. |
| **PARTIAL** | Some version exists. |
| **NOT FOUND** | We did not find it during current research. |
| **LIKELY GAP** | Multiple checks suggest it is absent or materially weaker. |
| **VERIFIED GAP** | Strong current evidence supports absence. |
| **UNKNOWN** | Not checked. |

During discovery, **NOT FOUND** is enough.

Do not waste time proving absence for every weak candidate.

Only upgrade to VERIFIED GAP if the idea becomes important.

---

# 5. Evidence philosophy

Evidence matters, but it should support exploration rather than block it.

## Evidence labels

### A — Primary

- official product docs
- official help center
- official release notes
- official API docs
- official competition rules

### B — Strong independent

- academic research
- credible security research
- reputable investigative reporting
- public feature-request systems with meaningful metrics

### C — Good secondary

- Reuters
- The Verge
- TechCrunch
- reputable regional tech press
- interviews

### D — Community / anecdotal

- Reddit
- X
- Ekşi Sözlük
- GitHub issue discussions
- forums
- app-review comments

### E — Researcher inference

- product hypothesis
- synthesis
- design extrapolation
- "this could work well for NSosyal"

### F — Wild idea

- little or no evidence
- recorded because the mechanism is interesting

**F is allowed.**

The matrix is an idea laboratory, not a courtroom.

---

# 6. Demand should not be a gate

Users do not always ask for the best innovations before they exist.

Some needs are:

- explicit,
- latent,
- indirectly expressed,
- or only visible through workarounds.

Therefore demand should be recorded in several forms.

## Demand types

### Explicit demand

Users directly ask for the feature.

> "Please add bookmarks."

### Problem demand

Users complain about a problem without naming the right solution.

> "I can never find posts I saw last week."

Possible solution:

> semantic personal library.

### Workaround demand

Users invent hacks.

> Users create private accounts just to save posts.

Possible solution:

> first-class collections.

### Behavioral demand

Usage patterns suggest need.

> Users repeatedly switch accounts to separate audiences.

Possible solution:

> contextual identities.

### Analog demand

A feature is heavily used elsewhere even if NSosyal users have not requested it.

### Speculative demand

We believe the need could exist but have not yet researched it.

All are worth recording.

---

# 7. Demand strength — lightweight version

Do not over-score early ideas.

Use rough labels first:

| Label | Meaning |
|---|---|
| **UNKNOWN** | Not researched |
| **WEAK** | Small or scattered signal |
| **MODERATE** | Repeated signal or strong analogous use |
| **STRONG** | Repeated across communities/platforms |
| **VERY STRONG** | Platform itself acknowledges major demand / huge measurable request history |

Only convert to numeric scores during shortlist validation.

---

# 8. The discovery matrix

During exploration, use a lightweight row.

Recommended fields:

| Field | Description |
|---|---|
| **ID** | Stable identifier |
| **Idea / Feature** | Short name |
| **Family** | Feed, identity, local, etc. |
| **Source Platform** | Where found |
| **Region** | Country/region |
| **What it does** | Plain explanation |
| **Why interesting** | The actual insight |
| **Possible NSosyal adaptation** | Rough idea |
| **NSosyal status** | YES / PARTIAL / NOT FOUND / LIKELY GAP / UNKNOWN |
| **Demand signal** | Unknown / weak / moderate / strong / very strong |
| **Evidence** | A–F |
| **Risk flag** | None / privacy / abuse / monitoring / legal / technical |
| **Maturity** | SPARK / SIGNAL / PATTERN / etc. |
| **Notes** | Anything useful |

That is enough for **90% of early research**.

Do not force a 40-column spreadsheet on every weird idea.

---

# 9. The validation matrix

Only serious concepts need the full version.

Recommended fields:

| Field | Description |
|---|---|
| **ID** | Stable identifier |
| **Feature / Concept** | Short name |
| **Project Family** | Feed, Communities, Trust, Local, Security, etc. |
| **Problem Solved** | User problem, not implementation |
| **Source Platform(s)** | Where the pattern was found |
| **Region** | Geographic/product ecosystem |
| **Source Feature** | Actual implementation |
| **Evidence Grade** | A–F |
| **Source URL(s)** | Best links |
| **Demand Type** | Explicit / problem / workaround / behavioral / analog / speculative |
| **Demand Strength** | Weak → Very Strong |
| **NSosyal Status** | YES / PARTIAL / NOT FOUND / LIKELY GAP / VERIFIED GAP / UNKNOWN |
| **Gap Confidence** | Low / Medium / High |
| **Existing NSosyal Adjacent Feature** | Closest current feature |
| **NSosyal Adaptation** | How it would work here |
| **Differentiation** | Why it is not merely a clone |
| **Competition Category** | Content Economy / Social AI / User Engagement-UI/UX / cross-cutting |
| **Competition Fit** | Low / Medium / High |
| **Innovation** | Low / Medium / High |
| **User Impact** | Low / Medium / High |
| **Demo Value** | Low / Medium / High |
| **Technical Feasibility** | Low / Medium / High |
| **Prototype Time Fit** | Low / Medium / High |
| **Integration Burden** | Low / Medium / High |
| **Data Dependency** | Low / Medium / High |
| **Privacy Risk** | Low / Medium / High |
| **Abuse Risk** | Low / Medium / High |
| **Monitoring/Control Risk** | Low / Medium / High |
| **Legal/Policy Risk** | Low / Medium / High |
| **Success Metric** | What would prove it works |
| **Killer Demo** | 20–60 second judge demo |
| **Prototype Scope** | Minimal credible implementation |
| **Full Product Vision** | Where it could eventually go |
| **Known Competitors** | Similar products |
| **Open Questions** | What still needs research |
| **Maturity** | VALIDATING / VALIDATED / SHORTLIST / etc. |

---

# 10. Scoring philosophy

Do **not** score everything.

Scoring too early creates false precision and punishes imaginative ideas.

Use scoring only when comparing serious shortlist candidates.

Before that, prefer:

- notes,
- tags,
- confidence,
- maturity states,
- rough strengths and weaknesses.

---

# 11. Late-stage shortlist scoring

When comparing 5–15 serious concepts, use a flexible weighted score.

## Positive dimensions — 100 points

| Dimension | Weight |
|---|---:|
| User/problem relevance | 15 |
| NSosyal fit | 12 |
| Innovation / synthesis | 15 |
| Competition fit | 12 |
| User impact | 12 |
| Demo quality | 12 |
| Technical feasibility | 10 |
| Prototype time fit | 6 |
| Extensibility / future value | 4 |
| User agency / trust | 2 |
| **Total** | **100** |

Do not require hard evidence for every point.

A concept can score strongly because of a convincing product argument.

---

# 12. Risk is a discussion, not an automatic kill switch

Track:

- privacy risk
- abuse risk
- surveillance/monitoring risk
- legal risk
- technical dependency
- moderation burden
- data requirements

But do not immediately discard an idea because risk exists.

Instead ask:

> Can the design be changed to preserve the value while reducing the risk?

Example:

**Verified anonymity**

Risk:
- operator could deanonymize users.

Possible mitigation:
- credential service separated from posting identity,
- short-lived proofs,
- minimal logs,
- pseudonymous tokens,
- no public legal identity.

Risk becomes a **design constraint**, not necessarily a rejection.

---

# 13. When to reject an idea

Reject only when one of these becomes reasonably clear:

- it already exists in NSosyal in nearly the same form,
- the benefit is trivial,
- it cannot be credibly prototyped,
- it depends on unavailable production infrastructure with no meaningful simulation,
- it is basically an AI wrapper with no product insight,
- it has severe unavoidable harms,
- a stronger idea covers the same need,
- it has no interesting NSosyal-specific adaptation.

Otherwise:

> park it.

Do not over-delete the idea pool.

---

# 14. Discovery heuristics

When researching a platform, ask questions like:

### What does this platform do that X does not?

### What does it assume about users that Western platforms do not?

### What local constraint shaped it?

### What feature looks boring but is probably used constantly?

### What workflow does it replace?

### What happens before and after a post?

### How does it handle identity?

### How does it handle groups?

### How does it handle real-world institutions?

### What does it do with old content?

### How does it preserve context?

### How does it monetize creators?

### How does it handle moderation?

### How does it let users control algorithms?

### What does it expose to the user that other platforms hide?

### What does it hide from the user that should worry us?

### What feature would be surprisingly useful in Turkey?

### What would become much better if combined with another platform's feature?

These questions are often more productive than:

> "What features does Platform X have?"

---

# 15. Combination hunting

Some of the best ideas will come from combining features across unrelated platforms.

Examples already discovered:

## Blind + MAX + Dcard

> privacy-preserving verified identity.

## BAND + LINE + Kutumb + Zalo

> Community OS.

## Misskey + Threads + TikTok

> user-controlled recommendation studio.

## Douban + Wikipedia + semantic search

> persistent social knowledge graph.

## Public + nebenan.de + Xiaohongshu

> structured hyperlocal social layer.

## Marshmallow + Bluesky moderation

> user-controlled moderation mixer.

## Pixiv + NSosyal Küre

> commissions and useful creator work.

## Niconico + provenance

> context-preserving remixes.

Treat cross-platform synthesis as a first-class research activity.

---

# 16. Current master project families

These are **idea clusters**, not commitments.

---

## FEED — Feed / algorithm agency

Sources:

- Bluesky
- Threads
- TikTok
- Misskey
- YouTube
- X complaints
- Dzen

Ideas:

- custom feeds
- natural-language feed control
- explicit include/exclude rules
- temporary topic preferences
- format preferences
- per-account repost controls
- custom "Antennas"
- user-visible recommendation reasoning

Core thesis:

> **Users should operate the algorithm rather than merely be operated on by it.**

---

## LIBRARY — Personal knowledge / retrieval

Sources:

- Bluesky bookmarks
- Misskey Clips
- Reddit search
- Discord bookmarks/reminders
- X history
- liked-post search requests

Ideas:

- semantic memory
- public/private collections
- saved-post folders
- "find the post I saw last month"
- remembered-reading state
- personal archive

---

## IDENTITY — Contextual identity

Sources:

- Kakao
- Dcard
- Discord
- LINE
- Blind

Ideas:

- different profile presentations
- posting personas
- community-specific identity
- verified role without full identity
- current/former credential states

---

## TRUSTED-ANON — Verified anonymity

Sources:

- Blind
- Dcard
- Everytime

Core concept:

> **Prove what you are without revealing who you are.**

Potential use:

- campus complaints
- workplace discussion
- sensitive Q&A
- professional advice
- whistleblowing
- community participation

---

## COMMUNITY-OS — Communities that actually run organizations

Sources:

- BAND
- LINE
- Everytime
- Kutumb
- Zalo
- VK
- MAX
- Odnoklassniki

Possible capabilities:

- calendar
- RSVP
- attendance
- roles
- committees
- forms
- tasks
- files
- subrooms
- calls
- event archive
- service desk
- marketplace
- treasury

Core thesis:

> Replace the pile of WhatsApp + Discord + Calendar + Forms + Drive.

---

## SOCIAL-OBJECTS — Persistent entities / knowledge graph

Sources:

- Douban
- forum systems
- local platforms

Entities:

- university
- book
- movie
- game
- club
- paper
- institution
- event
- city
- product
- sports team

Each can accumulate:

- posts
- reviews
- experts
- communities
- events
- sources
- history

---

## LOCAL — Hyperlocal / physical-world social layer

Sources:

- Xiaohongshu
- Douyin
- Public
- nebenan.de
- Jodel
- Everytime
- MAX

Ideas:

- campus spaces
- neighborhood feeds
- verified local communities
- issue reports
- local events
- nearby needs/offers
- place-specific discussion
- bounded distribution

---

## ACTIONS — Structured social actions

Sources:

- Pantip
- nebenan.de
- BAND
- Douyin
- VK
- MAX
- Public

Types:

- Question
- Event
- Request
- Offer
- Review
- Incident
- Volunteer opportunity
- Application
- Petition
- Sale
- Booking
- Task

Core thesis:

> **Not every contribution should be represented as the same generic post object.**

---

## EVENTS — Event lifecycle

Sources:

- Threads
- X
- Reddit
- BAND
- OK
- local platforms

Lifecycle:

### Before
- RSVP
- questions
- reminders
- agenda

### During
- live posts
- chat
- Q&A
- polls
- audio/video
- information cards

### After
- recording
- transcript
- AI summary
- archive
- resolved questions

---

## TRUST — Credentials / expertise

Sources:

- Bluesky Trusted Verifiers
- MAX Digital ID
- Blind
- Zhihu

Ideas:

- student credential
- university affiliation
- employee
- former employee
- doctor
- engineer
- organization representative
- community role
- topic expertise

Principle:

> Verify meaningful attributes, not merely status.

---

## SECURITY — User-protective social security

Sources:

- WeChat
- Weibo
- Douyin
- Tencent security practices

Ideas:

- anti-fraud prompts
- scam-link warnings
- account takeover detection
- security center
- emergency lockdown
- sensitive-information guard
- provenance
- user-visible security telemetry
- impersonation detection
- coordinated spam/bot detection

Possible umbrella:

### NShield

---

## ANTI-DYSTOPIA — Privacy-accountable security

Derived from threat-model research.

Ideas:

- local/on-device filtering
- minimal telemetry
- transparent intervention logs
- admin-access audit trails
- short retention
- purpose limitation
- privacy-preserving credentials
- user appeals
- no invisible behavioral score

Core thesis:

> **Security should increase the user's control over risk without unnecessarily increasing operator control over the user.**

---

## MODERATION — User-controlled moderation

Sources:

- Marshmallow
- Bluesky
- Mastodon
- Reddit

Possible:

### Interaction Mixer

Per-category control over:

- insults
- profanity
- sexual content
- political disagreement
- spam
- criticism
- spoilers
- repetitive content

Actions:

- show
- blur
- collapse
- hide
- notify

---

## CREATOR — Creator economy beyond ads

Sources:

- Pixiv
- Weibo
- Dzen
- VK
- ShareChat
- Odnoklassniki

Ideas:

- commissions
- creator requests
- paid series
- community treasury
- subscriptions
- donations
- paid expertise
- outcome-based compensation

---

## COLLAB — Collaborative creation

Sources:

- Yappy
- Instagram
- community tools

Ideas:

- shared draft
- contributor roles
- attachments
- tasks
- review
- approval
- co-authorship
- revision history

---

## PROVENANCE — Content lineage

Sources:

- Niconico
- AI labeling systems
- provenance standards

Ideas:

- clip links to original timestamp
- source lineage
- remix relationship
- editing history
- AI-assisted vs synthetic
- signed capture

---

## ORGANIZATIONS — Organization accounts as tools

Sources:

- Zalo
- MAX
- VK
- Odnoklassniki

Ideas:

- staff roles
- service desk
- managed inbox
- ticket assignment
- appointments
- forms
- bots
- mini-apps
- event management

---

## MINI-APPS — Social platform extensibility

Sources:

- WeChat
- VK
- MAX
- Zalo

Examples:

- event registration
- club membership
- tournament bracket
- municipality issue report
- booking
- volunteer signup
- campus utility
- job board

Potential competition scope:

> prototype a small Community Mini App framework rather than an entire super-app.

---

# 17. Checked geographic/platform research

Legend:

- ✅ **Meaningful pass completed**
- 🟨 **Partial / touched**
- ⬜ **Not systematically researched**

---

## Global / US-centered mainstream — ✅

Platforms:

- X
- Threads
- Bluesky
- Reddit
- Instagram
- TikTok
- YouTube
- Discord
- LinkedIn
- Mastodon partially

Covered:

- feature landscapes
- most-requested features
- feed control
- messaging
- bookmarks
- search
- profile customization
- editing
- scheduling
- communities
- live events
- AMAs
- Community Notes
- broadcast channels
- creator features

Still useful:

- deeper quantitative demand mining
- App Store complaints
- feature-request vote counts
- long-running Reddit/X requests

---

## China — ✅ deep

Platforms:

- WeChat / Weixin
- Weibo
- Xiaohongshu
- Douyin
- Douban
- Zhihu
- Bilibili

Product ideas:

- Mini Programs
- Local Life
- Super Topics
- creator series
- social objects
- reputation/expertise
- synchronized comments
- anti-fraud
- account security
- behavioral anomaly detection
- manipulation detection
- content provenance
- youth modes

Monitoring/control analysis:

- real-name identity
- IP-region display
- account reputation
- distribution control
- search filtering
- private-message censorship research
- behavioral monitoring
- social graph analysis
- regulatory logging
- super-app correlation risk

Still possible:

- smaller Chinese communities
- gaming communities
- enterprise/social tools
- livestream ecosystems

---

## Russia — ✅ deep

Platforms:

- VK
- MAX
- Odnoklassniki
- Dzen
- RUTUBE
- Yappy

Ideas:

- selective credentials
- trusted actions
- verified real-world communities
- mini apps
- bookings
- community calls
- live → recording lifecycle
- community monetization
- collaborative creation
- format-aware feeds
- creator metrics
- child mode
- domestic digital-service integration

Still possible:

- Russian Telegram bot ecosystems
- smaller regional forums
- deeper monitoring/control pass

---

## Korea — ✅ meaningful

Platforms:

- Everytime
- Blind
- KakaoTalk
- BAND

Ideas:

- University OS
- verified anonymity
- lifecycle credentials
- multi-profile identity
- Community OS

Still possible:

- Naver Cafe
- SOOP/AfreecaTV
- gaming/social platforms
- deeper Kakao ecosystem

---

## Japan — ✅ meaningful

Platforms:

- LINE OpenChat
- Misskey
- Marshmallow
- mixi2
- Pixiv
- Niconico

Ideas:

- per-community identity
- subrooms
- live audio
- Antennas
- Clips
- personal Drive
- recipient-controlled moderation
- network-local trends
- memories
- constrained profile curation
- commissions
- content lineage

Still possible:

- note
- broader LINE ecosystem
- BBS/imageboard systems
- VTuber communities
- Japanese gaming communities

---

## Taiwan — ✅ focused

Platform:

- Dcard

Ideas:

- contextual identity
- verified anonymity
- scarcity-based discovery

Still possible:

- PTT
- Bahamut
- civic-tech communities

---

## India — ✅ partial-to-meaningful

Platforms:

- ShareChat
- Public
- Kutumb

Ideas:

- audio communities
- gifting
- hyperlocal reporting
- formal community organization
- committees
- donations

Still possible:

- Moj
- Koo historical lessons
- Josh
- Lokal
- low-bandwidth systems
- multilingual systems

---

## Thailand — ✅ focused

Platform:

- Pantip

Ideas:

- read-position marker
- typed/intention-based posts
- persistent categorized discussion

Still possible:

- local creator/community apps
- LINE Thailand

---

## Vietnam — ✅ focused

Platform:

- Zalo

Ideas:

- institutional service desks
- admin roles
- managed conversations
- bots
- Mini Apps
- CRM-like organization features

---

## Indonesia — ✅ focused

Platform:

- KASKUS

Ideas:

- community marketplaces
- functional badges
- persistent forums + live interaction

---

## Germany — ✅ focused

Platforms:

- nebenan.de
- Jodel

Ideas:

- neighborhood verification
- bounded geographic reach
- structured help/offer posts
- hyperlocal interaction

---

# 18. Regions not yet systematically checked

These are opportunities, not obligations.

Do not treat the list as a rigid queue.

Research whichever area seems likely to generate useful novelty.

---

## Latin America / Brazil — ⬜

Potential platforms/themes:

- Brazilian local social products
- Kwai regional adaptations
- neighborhood/community apps
- creator/live ecosystems
- social commerce
- WhatsApp-adjacent workflows
- fintech/social overlap

Countries:

- Brazil
- Mexico
- Argentina
- Colombia
- Chile
- Peru

Interesting questions:

- How do products adapt around WhatsApp dominance?
- What social-commerce mechanics emerged?
- What creator formats are unusually strong?
- What mobile/low-bandwidth constraints shaped product design?

---

## Iran — ⬜

Platforms:

- Rubika
- Bale
- Eitaa
- Soroush Plus
- Aparat
- Gap

Do both:

### Product pass
- messaging
- channels
- payments
- communities
- creator tools
- local services

### Monitoring/control pass
- identity requirements
- inspection/moderation
- metadata
- search/ranking
- state integration
- privacy

Priority: high because it may reveal another domestic-platform model distinct from China/Russia.

---

## Wider MENA — ⬜

Potential:

- Saudi Arabia
- UAE
- Egypt
- Jordan
- Gulf
- North Africa

Themes:

- Arabic-first UX
- social audio
- creator economy
- family/community structure
- local identity
- payments
- institutional integration

---

## Africa — ⬜

Potential platforms/ecosystems:

- Ayoba
- M-Pesa-adjacent services
- local messaging/community apps
- low-data products
- creator platforms

Themes:

- offline-first
- low bandwidth
- SMS fallback
- multilingual UX
- community payments
- phone-number identity
- trusted local groups
- public-service communication

---

## Central/Eastern Europe — ⬜

Countries:

- Poland
- Czechia
- Slovakia
- Hungary
- Romania
- Bulgaria
- Serbia
- Croatia
- Baltics
- Ukraine

Themes:

- domestic forums
- local marketplaces
- civic/community platforms
- emergency/resilience systems
- wartime communication in Ukraine

---

## Balkans — ⬜

Potential relevance to Turkey:

- local forums
- sports communities
- diaspora networks
- civic systems
- neighborhood/community tools

---

## Caucasus / Central Asia — ⬜

Countries:

- Azerbaijan
- Georgia
- Kazakhstan
- Uzbekistan
- Kyrgyzstan

Themes:

- domestic language ecosystems
- super-apps
- Telegram-heavy communities
- payments
- government service integration
- local identity systems

---

## Southern / Western Europe beyond Germany — ⬜

Potential:

- Spain
- Italy
- France
- Portugal
- Greece

Themes:

- local/community apps
- civic platforms
- event systems
- marketplaces
- neighborhood networks

---

# 19. Community/product archetypes checked and unchecked

---

## Mainstream microblogging / public feed — ✅

Covered:

- X
- Threads
- Bluesky
- NSosyal

Still useful:

- demand mining
- timeline control
- moderation transparency

---

## General community/forum networks — ✅

Covered:

- Reddit
- Pantip
- KASKUS

Still possible:

- classic forums
- modern specialist forums
- long-term moderation tools

---

## Campus/student networks — ✅ meaningful

Covered:

- Everytime
- Dcard

Still possible:

- campus safety apps
- university planning systems
- local student marketplaces
- academic timetable/social systems

---

## Verified-anonymous professional communities — ✅ focused

Covered:

- Blind
- Dcard-related patterns

Still possible:

- Fishbowl
- industry communities
- whistleblowing systems
- expert anonymous networks

---

## Professional networks — 🟨 partial

Touched:

- LinkedIn
- Blind

Not systematically explored:

- Fishbowl
- Polywork-style systems
- profession-specific networks
- hiring/referral products
- project portfolio networks

Particularly relevant because NSosyal already has CV-like profile elements.

---

## Academic/scientific communities — ⬜

Potential:

- ResearchGate
- Academia.edu
- ORCID
- OpenReview
- Zotero
- PubPeer
- ResearchHub
- Semantic Scholar author features

Themes:

- citations
- author identity
- peer review
- reputation
- corrections
- versioning
- claim/source graphs

---

## Q&A / knowledge communities — 🟨

Touched:

- Reddit
- Zhihu

Not yet deep:

- Stack Overflow
- Stack Exchange
- Quora
- MathOverflow
- Brainly

Themes:

- accepted answers
- duplicates
- canonical questions
- privileges
- reputation
- review queues
- expertise

---

## Wikipedia / collaborative knowledge — ⬜

Potentially extremely fertile.

Study:

- revision history
- diffs
- talk pages
- citations
- watchlists
- protection
- revert
- editor roles
- consensus
- dispute resolution
- transparent moderation

Potential synthesis:

> social posts/objects that evolve collaboratively while preserving public history.

---

## Creator/art communities — 🟨 meaningful but incomplete

Covered:

- Pixiv
- Weibo
- Dzen
- VK
- ShareChat

Still possible:

- DeviantArt
- ArtStation
- Patreon
- Ko-fi
- Tumblr
- Cara
- Behance
- Substack

Themes:

- commissions
- attribution
- licensing
- fan support
- creator requests
- source lineage
- collaborative work

---

## Fandom communities — ⬜

Potential:

- Tumblr
- AO3
- FanFiction.net
- MyAnimeList
- AniList
- Letterboxd
- RateYourMusic
- fandom wikis

Themes:

- tagging
- spoiler control
- content warnings
- collections
- relationship tags
- fan curation
- canonical/source linking

---

## Gaming social systems — ⬜

Potential:

- Steam
- Discord gaming
- Xbox
- PlayStation
- Guilded
- FACEIT
- Battle.net

Themes:

- rich presence
- looking-for-group
- party formation
- achievements
- reputation
- matchmaking
- event scheduling
- guild roles

---

## Dating / social discovery — 🟨 very partial

Touched:

- Dcard historical matching

Possible sources:

- Tinder
- Bumble
- Hinge
- Coffee Meets Bagel
- Slowly
- Meetup

Only transfer:

- intent signaling
- constrained discovery
- introductions
- safety
- compatibility
- anti-harassment

---

## Civic / emergency / disaster systems — 🟨 partial

Touched:

- Public
- nebenan.de
- local/civic ideas

Not deep:

- Ushahidi
- Citizen
- Nextdoor
- earthquake-response apps
- emergency networks
- volunteer coordination

Very relevant for Turkey.

Themes:

- incident verification
- duplicate reports
- trusted authorities
- volunteer coordination
- needs/supply matching
- offline operation
- crisis prioritization

---

## Marketplace / trust systems — 🟨

Touched:

- KASKUS
- social commerce examples
- local marketplaces

Still possible:

- Carousell
- Vinted
- Wallapop
- eBay
- Sahibinden
- Facebook Marketplace

Themes:

- reputation
- escrow
- dispute resolution
- anti-scam
- identity
- community-specific commerce

---

## Privacy-first networks — ⬜

Potential:

- Signal
- Session
- SimpleX
- Matrix
- Briar
- Secure Scuttlebutt

Themes:

- metadata minimization
- key verification
- disappearing data
- local processing
- sealed sender
- unlinkability
- decentralized identity
- transparency

Very relevant to anti-dystopian security.

---

## Federated/decentralized social — 🟨

Touched:

- Bluesky
- Mastodon
- Misskey

Still possible:

- Lemmy
- PeerTube
- Nostr
- Farcaster
- Matrix social layers

Themes:

- portable identity
- migration
- moderation markets
- user-owned feeds
- interoperability
- distributed communities

---

## Moderation/governance systems — 🟨

Touched:

- Reddit
- Bluesky
- Marshmallow
- Mastodon
- China
- Community Notes

Still possible:

- Wikipedia
- Stack Exchange
- Twitch AutoMod
- Discord AutoMod
- community juries
- appeals systems
- review queues
- transparency logs

Potential unexplored opportunity:

> **Moderation due process and appeals.**

---

## Accessibility-first social design — ⬜

Potential themes:

- blind/low-vision UX
- deaf/hard-of-hearing UX
- dyslexia
- cognitive accessibility
- alt-text assistance
- captions
- sign language
- reduced motion
- sensory filtering
- simplified interfaces
- screen-reader navigation

Could be unusually competition-friendly.

---

## Old internet/forum mechanics — 🟨

Touched:

- Pantip
- KASKUS

Still deliberately inspect:

- phpBB
- vBulletin
- LiveJournal
- IRC
- Usenet
- Slashdot
- Digg
- old Reddit
- old Facebook Groups

Look for:

- unread markers
- thread subscriptions
- topic bumping
- moderator sections
- slow mode
- nested replies
- persistent archives
- reputation
- custom filters
- chronological reading state

Rule:

> Newer is not automatically better.

---

## Institutional/service communities — ✅ partial

Covered:

- Zalo
- MAX
- VK
- Odnoklassniki

Still possible:

- government service platforms
- universities
- healthcare
- customer-service communities
- public institution channels

---

## Security / anti-fraud — ✅ meaningful

Covered:

- WeChat
- Weibo
- Douyin
- Tencent practices

Ideas:

- anti-phishing
- account takeover
- graph spam detection
- security centers
- information leak prevention
- provenance
- insider access

Still possible:

- finance anti-fraud systems
- gaming anti-cheat
- Discord/Twitch abuse prevention
- privacy-preserving detection

---

## Monitoring / operator-control systems — ✅ China deep, 🟨 elsewhere

China threat-model pass completed.

Possible future:

- Russia
- Iran
- Western commercial ranking/surveillance systems

Purpose:

> understand dual-use risks, not blindly copy them.

---

# 20. Search procedure for a new platform

Do not force every step for every platform.

Use this as a flexible guide.

---

## Step 1 — Understand why the platform exists

Ask:

- Who uses it?
- What problem does it solve?
- Why does it exist alongside global platforms?
- What local constraint shaped it?
- Is it a feed, community, utility, messenger, creator network, forum, etc.?

---

## Step 2 — Hunt signature mechanics

Search official product pages, help centers, app listings, release notes, developer docs, newsrooms.

Ask:

> **What would disappear if this became a generic Twitter clone?**

Record those things.

---

## Step 3 — Capture sparks immediately

Do not wait for validation.

Record:

- mechanic
- source
- why interesting
- rough NSosyal adaptation
- any obvious risk

Then continue researching.

---

## Step 4 — Look for adjacent patterns

Search whether:

- another country built something similar,
- a niche product solved the same problem differently,
- users elsewhere ask for the same outcome.

This is how a SPARK becomes a PATTERN.

---

## Step 5 — Mine user pain

Search:

- Reddit
- platform forums
- X
- Ekşi
- app reviews
- GitHub issues
- support communities

But do not require user complaints for every idea.

Look for:

- direct requests
- workarounds
- recurring frustration
- behavior that suggests a latent need

---

## Step 6 — Check NSosyal lightly

During discovery:

- search current product/release notes,
- mark YES / PARTIAL / NOT FOUND / UNKNOWN.

Do not spend an hour proving absence unless the idea becomes serious.

---

## Step 7 — Write the NSosyal version

This matters more than copying the source feature.

Ask:

> **What would this become if designed specifically for NSosyal, Turkey, its communities, and the competition?**

A good adaptation often combines multiple sources.

---

## Step 8 — Threat-model lightly

Add obvious concerns.

Examples:

- location → stalking
- anonymity → abuse
- verification → deanonymization
- graph analysis → surveillance
- marketplace → fraud
- AI moderation → censorship
- reputation → hidden social scoring

Do not kill the concept yet.

Record mitigation ideas.

---

## Step 9 — Promote only the interesting ones

When an idea keeps surviving discussion:

> move it to VALIDATING.

Then do serious verification.

---

# 21. Validation procedure for serious concepts

Only for concepts likely to reach the shortlist.

Verify:

1. Current NSosyal feature status
2. Official competition category/rules
3. Strongest comparable products
4. User pain/demand
5. Technical dependencies
6. Data availability
7. Privacy/security risks
8. Abuse scenarios
9. Prototype feasibility
10. 60-second demo
11. success metrics
12. differentiation

At this point, evidence should become strict.

---

# 22. Demand-mining search templates

## Generic English

```text
"[platform]" "most requested feature"
"[platform]" "top requested feature"
"[platform]" feature request
"[platform]" users have been asking for
"[platform]" missing feature
"[platform]" wish it had
"[platform]" workaround
site:reddit.com "[platform]" "feature request"
site:reddit.com "[platform]" "why doesn't"
site:github.com "[platform]" feature request
"[platform]" new feature official
"[platform]" help feature
"[platform]" release notes
```

---

## NSosyal

```text
site:nsosyal.com [feature]
NSosyal [feature]
NSosyal yeni özellik
NSosyal özellikleri
NSosyal güncelleme
NSosyal sürüm notları
```

Pain / demand:

```text
NSosyal keşke
NSosyal neden yok
NSosyal özellik önerisi
NSosyal eksik
NSosyal sorun
NSosyal öneri
NSosyal eklenmeli
site:eksisozluk.com NSosyal
site:reddit.com NSosyal
```

---

## Chinese

```text
功能          feature
新功能        new feature
功能建议      feature suggestion
用户反馈      user feedback
安全          security
社区          community
小程序        mini program
反诈          anti-fraud
青少年模式    youth mode
内容审核      content moderation
```

---

## Russian

```text
новая функция         new feature
функции               features
пользователи просили  users requested
предложения           suggestions
жалобы                complaints
безопасность          security
сообщества            communities
мини-приложения       mini-apps
```

---

## Korean

```text
기능 요청       feature request
사용자 의견     user feedback
새 기능         new feature
커뮤니티        community
보안            security
익명            anonymous
대학생          university student
```

---

## Japanese

```text
機能要望        feature request
新機能          new feature
ユーザーの声    user feedback
コミュニティ    community
匿名            anonymous
セキュリティ    security
お気に入り      favorites/bookmarks
```

---

# 23. Research anti-patterns

Avoid these mistakes.

## "It only has one weak source, so ignore it."

Wrong during discovery.

One weak source can still reveal a great mechanic.

---

## "Users never requested it."

That does not mean they do not need it.

Look for latent or workaround demand.

---

## "Nobody else does it."

Could be a warning.

Could also be an innovation opportunity.

Investigate why.

---

## "Platform X has it, therefore NSosyal needs it."

Still wrong.

The feature must eventually have a credible NSosyal-specific reason.

---

## "AI can do it."

AI is an implementation method.

The product benefit must exist independently.

---

## "We didn't find it, therefore NSosyal lacks it."

Mark NOT FOUND.

Verify later if needed.

---

## "More engagement is good."

Do not use time-on-platform as the only product value.

Prefer:

- useful outcomes
- agency
- knowledge
- trust
- coordination
- successful retrieval
- community health

---

## "Security means privacy."

Often false.

Always ask:

> Who gains power from this security feature?

---

# 24. Current strongest cross-platform lessons

These are broad recurring insights.

---

## Lesson 1 — Users want more control

Across:

- Threads
- TikTok
- YouTube
- Bluesky
- Misskey
- X

Possible direction:

> recommendation controls as a mixer board.

---

## Lesson 2 — Generic posts are too primitive

Across:

- Pantip
- nebenan.de
- BAND
- Douyin
- Public
- VK

Possible direction:

> structured social objects with lifecycle and actions.

---

## Lesson 3 — Communities become powerful when they perform work

Across:

- BAND
- Everytime
- LINE
- Kutumb
- Zalo
- VK/MAX

Possible direction:

> Community OS.

---

## Lesson 4 — One person can need multiple identities

Across:

- Blind
- Dcard
- Kakao
- LINE
- Discord

Possible direction:

> contextual identity.

---

## Lesson 5 — Verification can prove useful attributes

Across:

- Blind
- MAX
- Bluesky

Possible direction:

> verified student / doctor / employee / organization role rather than generic blue check.

---

## Lesson 6 — Feeds are bad memory systems

Across:

- Douban
- Reddit
- Misskey
- bookmarks
- old forums

Possible direction:

> persistent social knowledge and semantic retrieval.

---

## Lesson 7 — Domestic platforms often become infrastructure

Across:

- WeChat
- VK
- MAX
- Zalo

Possible direction:

> communities + identity + services + mini-apps.

Risk:

> centralization and surveillance.

---

## Lesson 8 — Safety tools can become surveillance tools

Across:

- identity
- graph analysis
- behavior analysis
- semantic classifiers
- device tracking
- provenance

Possible direction:

> privacy-accountable security.

---

## Lesson 9 — Creator economy does not need to mean ads

Across:

- Pixiv
- Weibo
- Dzen
- VK
- ShareChat

Possible direction:

> commissions, patronage, useful outcomes, expert work.

---

## Lesson 10 — Local relevance is not global popularity

Across:

- nebenan.de
- Public
- Jodel
- Xiaohongshu
- MAX
- Everytime

Possible direction:

> bounded, place-aware social systems.

---

# 25. Existing research files

Previously created research documents:

1. `nsosyal_competitive_feature_landscape.md`
2. `nsosyal_most_requested_features_research.md`
3. `nsosyal_regional_platform_feature_research.md`
4. `nsosyal_security_monitoring_features.md`
5. `nsosyal_dystopian_monitoring_threat_model.md`
6. `nsosyal_russian_platform_feature_research.md`
7. `nsosyal_niche_local_platform_research.md`

This file supersedes the original stricter gap-matrix playbook.

---

# 26. Recommended future data files

When the idea pool becomes large, create:

## `nsosyal_discovery_matrix.csv`

Lightweight, many rows.

Suggested columns:

```text
ID
Idea
Family
Source Platform
Region
What It Does
Why Interesting
NSosyal Adaptation
NSosyal Status
Demand Signal
Evidence
Risk Flags
Maturity
Notes
```

---

## `nsosyal_validation_matrix.csv`

Only shortlist candidates.

Use the larger validation schema.

---

## `platform_research_log.csv`

Suggested:

```text
Platform
Country
Region
Platform Type
Research Date
Official Homepage
Official Help Center
Release Notes
App Store
Play Store
Distinctive Mechanics
Security Notes
Privacy Notes
Research Depth
Needs Follow-up
```

---

# 27. Stable feature IDs

Suggested families:

```text
FEED-###
LIB-###
ID-###
ANON-###
COMM-###
OBJECT-###
LOCAL-###
ACTION-###
EVENT-###
TRUST-###
SEC-###
PRIV-###
MOD-###
CREATOR-###
COLLAB-###
PROV-###
ORG-###
MINIAPP-###
ACCESS-###
CIVIC-###
KNOW-###
```

Example:

```text
ANON-001
Verified anonymous posting
Sources: Blind, Dcard
Maturity: PATTERN
```

---

# 28. Shortlisting rule

There is **no fixed numerical threshold**.

A concept becomes shortlist-worthy when the research team can make a convincing argument that:

- the problem matters,
- the NSosyal adaptation is clear,
- the feature is not basically already there,
- the prototype is buildable,
- the demo is compelling,
- the idea fits at least one competition category,
- the risks are understood,
- and there is some evidence or reasoning supporting user value.

An unusual 60/100 idea with a brilliant product insight can be stronger than a generic 90/100 idea.

Numbers should assist judgment, not replace it.

---

# 29. How to restart in a future session

Give this file to the assistant and say:

> **Continue the NSosyal innovation research using discovery-first mode from this playbook. Do not repeat already checked areas unless there is a reason. Collect unusual features freely even with weak evidence. Mark confidence and maturity instead of rejecting early. Only switch to strict validation for concepts that begin to look shortlist-worthy.**

For a regional pass:

> **Research Latin America in discovery-first mode. Focus on distinctive mechanics, local constraints, weird features, and transferable ideas. Do not demand strong proof before recording ideas.**

For a community archetype:

> **Research scientific and academic social systems using discovery-first mode.**

For demand:

> **Take the current promising concepts and investigate actual user demand. Promote only the strongest into validation.**

For NSosyal pain:

> **Mine current NSosyal user complaints and connect them to existing project families or create new ones.**

---

# 30. Suggested next research directions

Not a rigid queue.

Choose based on curiosity and likely novelty.

### NSosyal complaints
High value because it grounds the research in actual platform pain.

### Academic / Wikipedia / knowledge systems
Likely to produce new ideas around expertise, revision, citations, and collective knowledge.

### Privacy-first systems
Useful for anti-dystopian security.

### Iran / MENA
Likely to reveal another domestically constrained social ecosystem.

### Africa
Potentially strong for low-bandwidth, offline, community-payments, and public-service design.

### Latin America
Likely useful for mobile-first creator/social-commerce systems.

### Gaming communities
Strong identity, group, matchmaking, reputation, and coordination mechanics.

### Accessibility-first design
Underexplored and potentially highly distinctive.

### Old internet
Useful features may have been lost during the shift to engagement feeds.

---

# 31. Final research philosophy

The previous playbook was too close to due diligence.

This version deliberately changes the order of operations.

Do **not** begin with:

> "Can we prove this is a good idea?"

Begin with:

> **"Is there something interesting here?"**

Then:

> **"What problem might it solve?"**

Then:

> **"What happens if we combine it with another idea?"**

Then:

> **"Would this fit NSosyal unusually well?"**

Only after an idea survives those questions should the research become strict.

The operating philosophy is:

> **Discover broadly.**
>
> **Keep weak signals.**
>
> **Look for recurring patterns.**
>
> **Combine aggressively.**
>
> **Shortlist intelligently.**
>
> **Validate the finalists ruthlessly.**

The goal is not to build the most defensible spreadsheet.

The goal is to find the **best competition idea**.

The spreadsheet exists to help us do that, not to prevent us from thinking.
