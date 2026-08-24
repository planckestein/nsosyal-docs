Yes — and this pass turned up a bunch of mechanics that are **much less obvious than “add Communities / add AI / add payments.”**

I deliberately looked at platforms whose *structure* differs from X/Instagram: campus networks, verified-anonymous professional networks, hyperlocal communities, Japanese niche services, Southeast Asian forums, and community utilities. Against NSosyal's current publicly documented feature set, many of these still appear absent. ([play.google.com](https://play.google.com/store/apps/details?hl=tr&id=com.ntech.app&utm_source=chatgpt.com))

# 1. Korea — Everytime: social network + actual university operating system

**Everytime** is particularly relevant to NSosyal because it doesn't simply create “a university community.”

It combines:

- school verification,
- school-exclusive discussion boards,
- department/cohort chats,
- course timetables,
- course reviews written by verified students,
- exam information,
- GPA/credit management,
- cafeteria menus,
- shuttle information,
- study-room information,
- campus marketplace. ([apps.apple.com](https://apps.apple.com/kr/app/everytime/id642416310?l=en-GB&platform=vision&utm_source=chatgpt.com))

That's a major product lesson.

Don't build:

> “İTÜ Community”

Build:

# **İTÜ inside NSosyal**

**Bugün**
- Next class: Calculus II — 13:30
- Cafeteria: …
- Shuttle: 8 min
- Library occupancy: 73%

**Dersler**
- MAT201
- reviews
- previous exam experiences
- people currently taking it

**Campus**
- secondhand marketplace
- lost & found
- events
- club activity

**Community**
- department discussion
- class discussion
- anonymous board

This turns NSosyal from a place students *post on* into something students **need open all day**.

### Competition potential: ⭐⭐⭐⭐⭐

---

# 2. Korea — Blind: verified identity without public identity

Blind has a very clever social primitive:

> **prove what you are without revealing who you are.**

Employees verify their workplace, but conversations remain anonymous. It supports:

- private company channels,
- industry channels,
- public topic channels,
- salary comparisons,
- employer reviews,
- career discussions. ([help.teamblind.com](https://help.teamblind.com/article/71-features?utm_source=chatgpt.com))

Blind says its verification infrastructure deliberately separates work-email verification from activity data. ([us.teamblind.com](https://us.teamblind.com/faq?utm_source=chatgpt.com))

That's much more interesting than NSosyal's current:

> ✓ verified person.

Imagine:

## **Verified Anonymous Mode**

A post could display:

> 🎓 **Verified Boğaziçi student**  
> Anonymous

or:

> 🩺 **Verified physician**  
> Anonymous

or:

> 💼 **Verified employee of Company X**  
> Anonymous

without revealing the account.

That enables conversations people otherwise avoid:

> “Our department has a serious harassment problem.”

> “This professor's exam policy changed.”

> “My company's internship process works like this.”

> “I'm a physician; this viral medical claim is misleading.”

The credential provides **context and credibility**, while anonymity reduces personal risk.

### Competition potential: ⭐⭐⭐⭐⭐

This might combine extremely well with the **anti-dystopian privacy architecture** we discussed earlier.

---

# 3. Blind has an even smaller clever feature: lifecycle-aware credentials

Blind now distinguishes current employees from verified former employees. Former employees can receive an **Ex-Employee** tag but cannot participate as current employees inside the old company's private channel. ([help.teamblind.com](https://help.teamblind.com/article/128-linkedin-verification?utm_source=chatgpt.com))

That's excellent credential design.

Credentials aren't just:

> verified / not verified.

They're **stateful**.

NSosyal could represent:

> ✓ Current İTÜ student  
> ◷ İTÜ alumnus

> ✓ Current ASELSAN employee  
> ◷ Former ASELSAN employee

> ✓ Active club board member  
> ◷ Former president

That dramatically improves the credential idea.

---

# 4. Taiwan — Dcard: anonymous but socially contextual

Dcard allows posting under different identity presentations including:

- fully anonymous,
- university identity,
- university + department,
- nickname. ([support.dcard.in](https://support.dcard.in/hc/en-us/articles/7434533266319-How-to-be-anonymous-Will-others-know-who-I-am?utm_source=chatgpt.com))

That produces an idea more sophisticated than simply giving NSosyal an anonymous switch.

## **Contextual Identity**

For each post:

**Post as:**

○ Ahmet Yılmaz  
○ @ahmet  
○ Verified ITÜ student  
○ Verified engineering student  
○ Anonymous

Your identity presentation depends on **why you're speaking**.

That could fit NSosyal remarkably well.

---

# 5. Dcard's original discovery mechanic was wonderfully weird

Dcard originally became popular with a **once-per-day student matching system**.

At midnight, a verified university student got matched with one student from another university. Both had a limited period to mutually accept before they could communicate. ([taiwan.md](https://taiwan.md/en/culture/dcard-taiwan-social-platform/?utm_source=chatgpt.com))

Forget dating specifically.

The product idea is:

> **scarcity-based discovery instead of infinite swipe/discovery.**

Imagine:

# **Bugünün Bağlantısı**

Once per day NSosyal introduces you to:

> another first-year electrical engineering student,

or:

> another Formula Student member,

or:

> someone learning Japanese,

or:

> a Turkish indie-game developer.

No infinite doom-scroll of profiles.

**One high-quality introduction per day.**

That's surprisingly elegant.

---

# 6. Japan — Misskey Antennas: the feed becomes a query

This one goes directly into our **algorithm-control** research.

Misskey has **Antennas**. Users define conditions; matching posts are automatically collected into a separate real-time timeline. ([misskey-hub.net](https://misskey-hub.net/en/docs/for-users/features/antenna/?utm_source=chatgpt.com))

That's conceptually different from Lists.

Imagine NSosyal:

# **Akıllı Akış / Anten**

Create:

### “AI Research Turkey”

Include:

- contains “LLM”, “yapay zekâ”, “transformer”
- from Turkish-language accounts
- exclude job ads
- exclude reposts
- include accounts I don't follow
- minimum account age 30 days.

Or:

### “F1 Race Weekend”

- Formula 1 topics
- exclude spoilers before 22:00
- media allowed
- Turkish + English
- prioritize followed accounts.

This is basically:

> **saved search + custom algorithm + live timeline.**

And unlike opaque recommendation systems, **the user's rule is the algorithm**.

### Competition potential: ⭐⭐⭐⭐⭐

---

# 7. Misskey Clips: bookmarks that become publications

Misskey's **Clips** let users collect posts into named collections, add descriptions, and choose whether those collections are private or public. ([misskey-hub.net](https://misskey-hub.net/en/docs/for-users/features/clip//?utm_source=chatgpt.com))

That improves our previous **NSosyal Library** concept.

Instead of:

> Bookmark.

You could create:

### Deprem Mühendisliği Kaynakları

32 posts  
Public collection  
Curated by @Ayse

or:

### Read Later

Private.

or:

### Best NSosyal explanations of LLMs

Public.

This converts saving into **curation**.

Combine that with semantic search and it becomes quite powerful.

---

# 8. Misskey even gives users a real file library

Misskey has a user-facing **Drive** containing previously uploaded media/files. Users can organize files into folders and reuse them in future posts rather than uploading everything again. ([misskey-hub.net](https://misskey-hub.net/en/docs/for-users/features/drive/?utm_source=chatgpt.com))

That sounds boring until you think about creators.

## NSosyal Media Library

- logos
- intro clips
- common images
- PDFs
- diagrams
- event posters
- previous videos

Then:

> Attach from Library

For organizations and creators, that's genuinely useful.

---

# 9. Japan — Marshmallow: recipient-controlled AI moderation

This might be one of the strangest and most useful safety designs I've found.

**Marshmallow** is an anonymous-message service where AI filters negative/abusive messages *before the recipient sees them*. ([marshmallow-qa.com](https://marshmallow-qa.com/about?hl=en&utm_source=chatgpt.com))

But the clever part is that the **recipient controls the moderation strictness**.

Available modes range roughly from:

- no AI interference,
- tolerate negativity,
- standard filtering,
- positive-only. ([help.marshmallow-qa.com](https://help.marshmallow-qa.com/AI%E3%83%A2%E3%83%BC%E3%83%89-6a100991db316651dd563222?utm_source=chatgpt.com))

That's extremely relevant to our earlier observation:

> users want a **mixer board**, not an ON/OFF switch.

Imagine NSosyal DMs/replies:

### Interaction tolerance

**Open**
> Show almost everything.

**Balanced**
> Hide severe abuse/threats.

**Comfortable**
> Filter insults and hostility.

**Positive only**
> Only constructive/positive anonymous messages.

And individual categories:

- criticism ✅
- profanity ✅
- sexual content ❌
- insults ❌
- political disagreement ✅
- repetitive messages ❌.

### Competition potential: ⭐⭐⭐⭐⭐

Not:

> “AI decides what everybody may say.”

But:

> **“I decide what I personally want AI to shield me from.”**

Very different philosophy.

---

# 10. Thailand — Pantip has an embarrassingly useful tiny feature

Pantip has a feature meaning essentially:

# **“I read up to here.”**

Inside a giant discussion thread, you can mark the exact comment where you stopped. When you return, Pantip jumps you back to that position. ([apps.apple.com](https://apps.apple.com/th/app/pantip/id1223282907?utm_source=chatgpt.com))

Why the hell don't more platforms do this?

For NSosyal:

> **Continue from 183 replies ago**

or Küre:

> **Resume reading — 63%**

or live/event discussions:

> **247 new replies since you left**

Tiny feature.

Very high actual usefulness.

---

# 11. Pantip structures posts by *intent*

Pantip doesn't make every contribution just “a post.”

It distinguishes things such as:

- Q&A,
- discussion,
- review,
- poll,
- news,
- buy/sell. ([pantip.com](https://pantip.com/forum/all?utm_source=chatgpt.com))

Germany's nebenan.de independently does something similar:

- Announcement,
- Search,
- Offer,
- Recommendation,
- Event. ([hilfe.nebenan.de](https://hilfe.nebenan.de/hc/en-001/articles/205509772-What-Are-Posts?utm_source=chatgpt.com))

This is a very important design pattern.

Instead of NSosyal composer:

> What do you want to say?

ask:

### What are you trying to do?

**💬 Discuss**

**❓ Ask**

**📣 Announce**

**⭐ Review**

**🆘 Request help**

**🤝 Offer help**

**📅 Organize event**

**🛒 Sell**

**🙋 Volunteer**

Now the platform understands the **intent** of the post.

And that means UI can change appropriately.

A question gets:

> ✓ Mark accepted answer

An event gets:

> Going / Maybe

A request gets:

> Fulfilled ✓

A review gets:

> rating

An offer gets:

> Claim

This might be one of the most universally applicable ideas we've found.

---

# 12. Germany — nebenan.de: geographic reach is deliberately bounded

nebenan.de verifies residents and automatically assigns them to their real neighborhood. Users can interact with their immediate and adjacent neighborhoods, but the service deliberately does **not** turn everything into nationwide viral reach. ([hilfe.nebenan.de](https://hilfe.nebenan.de/hc/en-001/articles/115002741745-What-is-nebenan-de-and-what-can-I-do-on-the-platform?utm_source=chatgpt.com))

That's a powerful product constraint.

For NSosyal Yerel:

### Reach

○ My building  
○ My campus  
○ My neighborhood  
○ Adjacent neighborhoods  
○ District  
○ İstanbul  
○ Türkiye

Rather than:

> PUBLIC TO THE WHOLE INTERNET.

A post saying:

> “Has anyone lost a cat near Abbasağa?”

shouldn't be fighting Turkish presidential news for global engagement.

Local information needs **local distribution**.

---

# 13. nebenan.de: “help” is an actual social object

The network explicitly supports people **offering and requesting assistance**, alongside a local marketplace, events, groups, local businesses and neighborhood information. ([hilfe.nebenan.de](https://hilfe.nebenan.de/hc/en-001/articles/115002741745-What-is-nebenan-de-and-what-can-I-do-on-the-platform?utm_source=chatgpt.com))

This suggests:

# **NSosyal Dayanışma**

Structured requests:

> 🆘 Need blood donor — A+  
> İstanbul / Şişli  
> Expires in 6 hours

> 🔧 Need drill for one afternoon  
> 700 m away

> 📚 Looking for Calculus tutor  
> ITÜ Ayazağa

> 🚗 Need transport for elderly neighbor  
> Tomorrow 09:00

Then:

**Can help**

And the request closes when fulfilled.

Much better than hoping a plain-text tweet gets noticed.

---

# 14. India — Public: citizen reporting as a dedicated layer

India's **Public** app focuses explicitly on **hyperlocal updates**: short videos about local incidents, traffic, water shortages, infrastructure, jobs, events and other city-level information. Users can also report local issues themselves. ([apps.apple.com](https://apps.apple.com/in/app/public/id1451495152?utm_source=chatgpt.com))

That gives **NSosyal Yerel** another direction:

## Local issue reports

> 🚰 Water outage  
> 17 reports nearby

> 🚧 Road blocked  
> Confirmed by 8 users

> ⚡ Power outage  
> Started 14:22

> 🐕 Lost dog  
> Last seen 400 m away

The network could aggregate duplicate reports into **one evolving local object**.

Now you get:

> 47 people posted separately about this road closure

→ NSosyal merges them into:

### Road closure — Büyükdere Cd.

- first reported 14:08
- 47 reports
- 13 images
- municipality update
- affected area
- latest status.

That is significantly better than hashtags.

---

# 15. Jodel — hyperlocal interaction without profile performance

Jodel's core model is unusually radical:

- location-based nearby feed,
- anonymous users,
- local voting,
- channels,
- karma,
- nearby chats. ([play.google.com](https://play.google.com/store/apps/details?id=com.tellm.android.app&utm_source=chatgpt.com))

Its newer **VibeCheck** lets nearby active users publicly expose a mood/activity while keeping their identity private; users can request a chat without exact location being shown. ([support.jodel.com](https://support.jodel.com/de/articles/377866?utm_source=chatgpt.com))

The interesting principle isn't necessarily anonymity.

It's:

> **sometimes I want to interact with whoever is here, not with people I follow.**

Imagine NSosyal:

### Şu anda kampüste

🟢 183 people active

- ☕ Coffee break — 14
- 📚 Studying — 83
- 🎮 Free — 11
- 🏃 Running — 7
- 💬 Want to chat — 18

Potentially very useful for campus/event modes.

Obviously you'd need serious privacy controls.

---

# 16. India — Kutumb treats Communities like formal organizations

Kutumb has:

- official membership,
- member lists,
- donation collection,
- committees,
- titles/positions,
- posts,
- social discussions. ([kutumbapp.com](https://kutumbapp.com/?utm_source=chatgpt.com))

This makes our **Community OS** idea stronger again.

A community isn't necessarily:

> bunch of people talking.

It can have an actual organization chart:

### YTÜ Racing

**President**
Ayşe

**Technical Lead**
Emre

**Software**
12 members

**Sponsors**
4 members

**Alumni**
38 members

And permissions follow roles.

That's useful for:

- NGOs,
- clubs,
- teams,
- professional associations,
- neighborhood organizations.

---

# 17. Vietnam — Zalo turns an organization account into a service desk

Zalo Official Accounts can support:

- messaging,
- voice calls,
- menus,
- chatbots,
- group management,
- analytics,
- multiple administrator roles,
- conversation assignment,
- APIs,
- Mini Apps,
- MiniCRM-like customer information. ([oa.zalo.me](https://oa.zalo.me/home/function/management?trk=public_post_reshare-text&utm_source=chatgpt.com))

This yields another good NSosyal distinction:

> **People accounts and Organization accounts shouldn't merely be cosmetically different.**

Imagine:

### Türk Kızılay ✓

Profile buttons:

**Ask**

**Volunteer**

**Donate**

**Find center**

**Upcoming events**

Messages enter a managed inbox:

> Assigned to: Mehmet  
> Status: Waiting  
> Category: Volunteer inquiry

An organization has staff roles:

- owner
- communications
- support agent
- moderator
- events manager.

That's serious institutional infrastructure.

---

# 18. Indonesia — KASKUS: marketplaces can belong *inside* communities

KASKUS combines communities/forum discussion with buying and selling, real-time live chat and community-specific mechanics. ([apps.apple.com](https://apps.apple.com/id/app/kaskus-forum-hobi-komunitas/id571569180?utm_source=chatgpt.com))

That's more interesting than having one universal NSosyal Marketplace.

## Community marketplace

### Mechanical Keyboards Türkiye

**Sell**
- switches
- keycaps
- boards

### ITÜ

- textbooks
- calculators
- dorm equipment
- bicycles

### Photography

- lenses
- bodies
- tripods.

The **community supplies trust and relevance**.

That's much better than dumping everything into an OLX clone.

---

# 19. KASKUS also uses explicit community status

Its recent app changes expose badges for roles such as:

- thread starter,
- moderator,
- community owner,

and let users pin badges to their profile. ([apps.apple.com](https://apps.apple.com/id/app/kaskus-forum-hobi-komunitas/id571569180?utm_source=chatgpt.com))

That suggests NSosyal badges shouldn't primarily be:

> ✨ you posted 100 times!

They should answer:

> **Why should I care about this person's role here?**

Examples:

> Community Founder  
> Moderator  
> Event Organizer  
> Accepted Expert  
> Top Answerer  
> Verified Alum  
> Volunteer Coordinator.

Functional badges > vanity badges.

---

# 20. Japan — mixi2 deliberately refuses the “everything is media” model

mixi2 is interesting because its creators explicitly describe the problem with giant algorithmic networks becoming **news/media systems instead of relationships between people**.

Its default feed is chronological and centered on accounts/communities the user deliberately chose. ([support.mixi.social](https://support.mixi.social/support/solutions/articles/154000212308-mixi2%E3%81%AE%E7%89%B9%E5%BE%B4?utm_source=chatgpt.com))

Its discovery emphasizes what is becoming popular **among people near your social network**, not merely globally viral content. ([mixi.co.jp](https://mixi.co.jp/news/2024/1223/37672/?utm_source=chatgpt.com))

That suggests a lovely NSosyal feed:

# **Çevremde**

Not:

> National Trends.

But:

> **What people I actually know are talking about.**

Example:

**Türkiye**
> #Election

**My network**
> Erasmus applications  
> Formula Student  
> Linear Algebra exam  
> İstanbul rain

That second one may be vastly more socially useful.

---

# 21. mixi2's “Memories” turns posting into a personal archive

mixi2 now has a **calendar-based Memories system**:

- see your posts by date,
- maintain posting streaks,
- backfill previous dates,
- generate a daily summary card. ([support.mixi.social](https://support.mixi.social/support/solutions/articles/154000248604-%E8%87%AA%E5%88%86%E3%81%AE%E3%83%9D%E3%82%B9%E3%83%88%E3%82%92%E6%8C%AF%E3%82%8A%E8%BF%94%E3%82%8B%EF%BC%88%E6%80%9D%E3%81%84%E5%87%BA%E6%A9%9F%E8%83%BD%EF%BC%89?utm_source=chatgpt.com))

That's different from:

> timeline from newest to oldest forever.

NSosyal could have:

# **Hayatım / Arşiv**

Calendar:

**August 2026**

Tap August 12:

- 3 posts
- event attended
- 18 photos
- saved article
- community milestone.

Social media becomes a **personal memory substrate**, not just disposable attention.

---

# 22. mixi2 has a delightfully constrained profile concept

Its **9/me portfolio** lets users choose only **nine** things—images, links, communities—to visually represent themselves. ([support.mixi.social](https://support.mixi.social/support/solutions/articles/154000246162-%E3%83%9D%E3%83%BC%E3%83%88%E3%83%95%E3%82%A9%E3%83%AA%E3%82%AA%E3%82%92%E4%BD%9C%E6%88%90%E3%81%99%E3%82%8B?utm_source=chatgpt.com))

That could improve NSosyal's CV-heavy profile.

Rather than endless fields:

# **Beni anlatan 9 şey**

🛰 CubeSat  
🎸 Guitar  
🏫 İTÜ  
🔗 GitHub  
🏎 Formula Student  
📷 Photography  
📚 Dune  
🇯🇵 Japanese  
🧑‍💻 Rust

It's social identity through **curation**, not form-filling.

---

# 23. Japan — Pixiv's creator economy starts with requests, not advertising

Pixiv lets fans send **paid creation requests** directly to creators, who decide which ones they want to accept. The whole lifecycle—from request through creation and publication—can happen on the platform. Pixiv reported more than 320,000 requests sent by 2025. ([pixiv.co.jp](https://www.pixiv.co.jp/2025/09/10/120000?utm_source=chatgpt.com))

That's a considerably healthier creator mechanic than:

> maximize impressions → advertisements.

For NSosyal:

# **İstek / Commission**

> “Could you produce an infographic explaining earthquake retrofit classes?”

Budget:

> ₺1,500

Creator:

> Accept / decline

Or:

> “Please make a Turkish tutorial explaining this open-source library.”

Then the resulting work becomes an NSosyal publication.

Could fit the **Content Economy** category very well.

---

# 24. Pixiv demonstrates a complete creation loop

Pixiv's wider ecosystem connects:

> discover creator  
> → follow  
> → support monthly  
> → commission work  
> → buy digital/physical work  
> → creator can manufacture merchandise on demand. ([pixiv.co.jp](https://www.pixiv.co.jp/service/?utm_source=chatgpt.com))

The important NSosyal lesson:

> **Creator economy doesn't have to mean advertising revenue share.**

It could mean actual **patronage and work**.

---

# 25. Japan — Niconico added content lineage to Shorts

Niconico's 2026 short-video system allows creators to pin a link from a short clip directly to another source video—for example, directing viewers from a clipped short to the full original. It retains Niconico's synchronized flowing-comment experience as well. ([prtimes.jp](https://prtimes.jp/main/html/rd/p/000000903.000096446.html?utm_source=chatgpt.com))

That inspires:

# **Derivative content lineage**

When someone clips/remixes:

> **Source:** Original 28-minute video  
> `03:17–03:49`

Click:

> Watch original at 03:17

Fantastic for:

- interviews,
- political clips,
- lectures,
- podcasts,
- sports.

It also helps fight **context stripping**.

That's actually pretty good for NSosyal.

---

# 26. Germany — a neighborhood post can have intentionally limited propagation

One detail from nebenan.de I particularly like:

A post can explicitly target:

- immediate neighborhood,
- adjacent neighborhoods,
- a group,
- or, separately, become public. ([hilfe.nebenan.de](https://hilfe.nebenan.de/hc/en-001/articles/205509772-What-Are-Posts?utm_source=chatgpt.com))

This suggests a broader NSosyal primitive:

# **Audience by relevance, not merely privacy**

When posting:

**Who is this useful to?**

○ Followers  
○ My university  
○ My neighborhood  
○ İstanbul  
○ Turkey  
○ Specific community.

Different from:

> public/private.

That's potentially very powerful.

---

# 27. Southeast Asia taught another interesting lesson: forum threads aren't dead

Pantip and KASKUS remain built heavily around **persistent threads and categorized communities**, not just ephemeral person-centric feeds. Pantip exposes rooms, tags, clubs and explicit post types; KASKUS combines long-running community threads with live interaction and commerce. ([apps.apple.com](https://apps.apple.com/id/app/kaskus-forum-hobi-komunitas/id571569180?utm_source=chatgpt.com))

The feed model says:

> Follow **people**.

The forum model says:

> Follow **conversations**.

NSosyal should perhaps let you explicitly follow:

> a thread  
> a question  
> an event  
> an object  
> a topic  
> an investigation

without following the author.

That's an important distinction.

---

# What this pass adds to our master idea pool

These are the **new things I would actually keep**:

| Idea | Inspiration | My current interest |
|---|---|---:|
| **Verified-but-anonymous posting** | Blind, Dcard | ⭐⭐⭐⭐⭐ |
| **University OS inside NSosyal** | Everytime | ⭐⭐⭐⭐⭐ |
| **User-programmed “Antennas” / smart feeds** | Misskey | ⭐⭐⭐⭐⭐ |
| **Intent-based post types** | Pantip, nebenan.de | ⭐⭐⭐⭐⭐ |
| **Recipient-controlled AI moderation** | Marshmallow | ⭐⭐⭐⭐⭐ |
| **Structured hyperlocal incident objects** | Public, nebenan.de | ⭐⭐⭐⭐⭐ |
| **Community membership + committees + real roles** | Kutumb | ⭐⭐⭐⭐⭐ |
| **Institutional service-desk accounts** | Zalo | ⭐⭐⭐⭐⭐ |
| **Creator commissions / requests** | Pixiv | ⭐⭐⭐⭐⭐ |
| **Context-preserving clip → source lineage** | Niconico | ⭐⭐⭐⭐⭐ |
| **Dynamic credentials: student → alumnus, current → former employee** | Blind | ⭐⭐⭐⭐⭐ |
| **Community-specific marketplaces** | KASKUS | ⭐⭐⭐⭐ |
| **Public/private curated post collections** | Misskey Clips | ⭐⭐⭐⭐ |
| **Calendar-based personal social archive** | mixi2 | ⭐⭐⭐⭐ |
| **Social-neighborhood rather than global trends** | mixi2 | ⭐⭐⭐⭐ |
| **One high-quality introduction per day** | old Dcard | ⭐⭐⭐⭐ |
| **“Read up to here” thread state** | Pantip | ⭐⭐⭐⭐ |
| **Role/status badges with actual meaning** | KASKUS | ⭐⭐⭐⭐ |
| **Reusable personal media/file library** | Misskey | ⭐⭐⭐ |
| **Anonymous nearby “current vibe” discovery** | Jodel | ⭐⭐⭐, privacy-sensitive |

## And I think two completely new project families have now emerged

### **A. Trusted Anonymity**

This wasn't nearly as clear before.

Combine:

**Blind + Dcard + Everytime + our privacy/security work.**

The user proves an attribute cryptographically or through verification:

> university student  
> employee  
> doctor  
> engineer  
> resident

but can speak **without exposing their personal identity**.

The platform could support:

> **verified claims without public identification.**

That has massive applications for whistleblowing, workplace/campus discussions, sensitive Q&A, professional advice and community participation.

And if implemented with strong separation between credentials and posting identity, there's a serious technical/privacy story there—not merely UI.

### **B. Structured Social Actions**

This has now appeared independently in **Pantip + nebenan.de + Public + Everytime + BAND + Douyin + Russian platforms**.

The major insight is:

> **Not every post is the same kind of object.**

A social network should understand:

**Question**

**Event**

**Request**

**Offer**

**Report**

**Review**

**Task**

**Petition**

**Application**

**Sale**

**Volunteer opportunity**

**Incident**

Then each post gets behavior appropriate to what it *is*.

That's beginning to look like a very deep NSosyal architecture idea rather than one feature.

And I think we should continue doing these country/niche passes. There are still potentially useful ecosystems I haven't properly mined yet—**Brazil/Latin America, Central/Eastern Europe, Africa, Iran, and niche professional/scientific/fandom networks**—and at this point each region is producing at least one genuinely non-obvious idea.
