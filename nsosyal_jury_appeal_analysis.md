Yes — and this changes how I’d rank some of our ideas.

I checked the current 2026 competition material and searched specifically for jury names. **As of now, I cannot find a publicly announced list of individual 2026 NSosyal İnovasyon Yarışması jurors.** The official page only says finalists will make a live presentation to the jury in September, while the rulebook defines the jury simply as an expert committee. ([teknofest.org](https://teknofest.org/tr/yarismalar/nsosyal-inovasyon-yarismasi/))

So I would **not** start inventing profiles of people who might be jurors. But we actually know enough to reverse-engineer the panel's likely evaluation mindset much more reliably from the rubric, last year's predecessor competition, and the organizer's stated product goals.

## The most important discovery: choose the track strategically

The 2026 rubric is unusually revealing.

For **Kullanıcı Katılımı ve Arayüz / UI/UX**, the weights are:

| Criterion | Weight |
|---|---:|
| Innovation & originality | **20%** |
| Technical competence & feasibility | **20%** |
| Problem-solving success | **15%** |
| **UI/UX** | **30%** |
| **Presentation & prototype quality** | **15%** |
| Business model | **0%** |

That means **65% of the score is directly Innovation + UX + Prototype**, before even counting technical implementation. ([cdn.teknofest.org](https://cdn.teknofest.org/media/upload/userFormUpload/2026_NSOSYAL_YARISMASI_SARTNAMESI_TR_2026_07_24_v9_1_G92Gv_UtwIa.pdf))

Compare Social AI:

| Criterion | Weight |
|---|---:|
| Innovation | 20% |
| **Technical competence** | **35%** |
| Problem solving | 20% |
| UI/UX | 10% |
| Prototype | 15% |

And Content Economy is the only one where business model explicitly gets 10%. ([cdn.teknofest.org](https://cdn.teknofest.org/media/upload/userFormUpload/2026_NSOSYAL_YARISMASI_SARTNAMESI_TR_2026_07_24_v9_1_G92Gv_UtwIa.pdf))

That has a major consequence:

> **Living Text / Canlı Metin should probably be entered as a User Engagement + UI/UX project, even if we put AI inside it.**

Don't make AI the identity of the project.

Make AI one enabling component.

---

# What kind of jury are we probably facing?

We know last year's different-but-related **NSosyal Super App Creathon** used a jury composed of **UI/UX specialists, software engineers, graphic designers and entrepreneurship representatives**. ([aa.com.tr](https://www.aa.com.tr/tr/teknofest/teknofestte-gencler-super-uygulama-icin-yarisacak/3680086?utm_source=chatgpt.com))

The 2026 competition is broader, and its rules explicitly encourage teams spanning software development, AI, data science, cybersecurity, product management, UI/UX, design and entrepreneurship. The mentorship phase similarly covers technical architecture, product development, AI integration, scalability, UX and product validation. ([cdn.teknofest.org](https://cdn.teknofest.org/media/upload/userFormUpload/2026_NSOSYAL_YARISMASI_SARTNAMESI_TR_2026_07_24_v9_1_G92Gv_UtwIa.pdf))

So I would mentally prepare for at least these **jury archetypes**:

### The product person

Their question is:

> “Why would NSosyal actually ship this?”

They don't care that the React animation is cool if there isn't a product reason for it.

You need:

> Current problem → behavioral insight → feature → measurable improvement.

---

### The UI/UX person

Their question is:

> “Is this actually easier/better, or merely more animated?”

They'll notice:

- interaction friction,
- hierarchy,
- thumb reach,
- motion,
- readability,
- accessibility,
- cognitive load,
- consistency,
- whether the interface explains itself.

For Living Text this person is potentially your **best friend**.

---

### The engineer

Their question becomes:

> “Okay. How does this actually work?”

For Living Text, don't show them just a fancy Figma card.

Show an actual content model:

```text id="76y4hi"
Post
 ├── TextBlock
 ├── RevealBlock
 ├── PollBlock
 ├── ExplainAction
 ├── SourceBlock
 ├── BranchBlock
 └── DiscussionAnchor
```

Then:

> ordinary NSosyal posts remain backwards-compatible; Living Text introduces a semantic block schema rendered by the client.

Now it sounds like a **new social-content primitive**, not an animation project.

---

### The AI/data person

If you mention AI, they'll reasonably ask:

> “Why does this require AI?”

That's where many competitors will probably screw themselves.

Don't say:

> AI generates posts!

Say:

> AI is optional and operates at specific friction points:
> - explain unfamiliar concepts,
> - produce source-bound context,
> - cluster 1,800 replies into navigable groups,
> - assist creators in producing optional depth layers.

And if they ask about hallucination:

> retrieved/source-bound information is separated from author-written content and labeled.

Much more mature.

---

### The ecosystem / strategic person

The official rules repeatedly emphasize products that can become real, scalable social-media technologies, create social value, improve digital life, support Turkish technology capability, and potentially compete globally. ([cdn.teknofest.org](https://cdn.teknofest.org/media/upload/userFormUpload/2026_NSOSYAL_YARISMASI_SARTNAMESI_TR_2026_07_24_v9_1_G92Gv_UtwIa.pdf))

Their question is essentially:

> “Why is this strategically useful for NSosyal rather than another random hackathon app?”

This is where our framing becomes important.

Don't pitch:

> “We added interactive posts.”

Pitch:

> **“Video platforms reinvented the consumption model for video. Text social networks never performed the equivalent redesign for text.”**

Then:

> **“NSosyal can differentiate by making text itself a modern interactive medium instead of competing with TikTok by becoming another video feed.”**

That is a much more interesting story.

---

# And something in the official language is almost tailor-made for Living Text

The rules explicitly list example UI/UX areas such as:

- adaptive interfaces,
- micro-animations,
- motion-based experiences,
- personalized interfaces,
- accessibility solutions,
- **new-generation social interaction experiences**. ([cdn.teknofest.org](https://cdn.teknofest.org/media/upload/userFormUpload/2026_NSOSYAL_YARISMASI_SARTNAMESI_TR_2026_07_24_v9_1_G92Gv_UtwIa.pdf))

And the general goal says users should spend their time on the platform **more efficiently, safely and with higher quality**, not merely "increase screen time." ([cdn.teknofest.org](https://cdn.teknofest.org/media/upload/userFormUpload/2026_NSOSYAL_YARISMASI_SARTNAMESI_TR_2026_07_24_v9_1_G92Gv_UtwIa.pdf))

So Living Text can be positioned as:

> **higher interaction without requiring lower information density.**

That distinction matters.

---

# There's also an interesting signal from the 2025 judging

I wouldn't overfit to last year's different competition, but two outcomes are revealing.

The third-place Pencipta team said their focus wasn't maximizing the number of Super App modules; it was **systems thinking and seamless integration**, and one team member specifically said that integration was what impressed the jury. ([trtindonesia.com](https://www.trtindonesia.com/article/f3fecbfb393a?utm_source=chatgpt.com))

There was also a jury special **Social Awareness Award** whose recipient describes the recognized project in terms of user needs, accessibility, clear interface logic and coherent design. ([tr.linkedin.com](https://tr.linkedin.com/in/elcinlinaakdag?utm_source=chatgpt.com))

Weak signal, but it suggests:

> **Don't feature-dump. Build one coherent idea extremely well.**

That is useful for us.

---

# How I would pitch Living Text to this jury

Not:

> “Text is boring, so we gamified it.”

That sounds shallow and possibly unhealthy.

Not:

> “TikTok is addictive so we made TikTok for text.”

Definitely not.

Instead:

> **“Social platforms optimized video consumption dramatically, but the basic unit of text social media has barely changed: it is still a static rectangle followed by like, reply and repost buttons.”**
>
> **“We redesigned the text post itself as an interactive medium.”**

Then show it immediately.

Normal post:

> Artificial intelligence uses significant amounts of water...

Static.

Then **Canlı Metin**:

> Yapay zekâ gerçekten su tüketiyor mu?
>
> **Ne kadar? ↓**

Tap.

Chart.

**Neden?**

Tap.

Explanation.

**Kaynak?**

Tap.

Citation.

**Karşı görüş?**

Tap.

Opposing argument.

Swipe.

Finished.

Then say:

> **“Instead of watch → wait → swipe, we optimize text for scan → notice → interact → understand → continue.”**

That's the thesis.

---

# The part I'd emphasize most to the UX jury

**The reader controls depth.**

That is more sophisticated than “more interaction.”

A 10-second reader gets:

> headline + key fact.

A curious reader taps:

> explanation.

A skeptical reader taps:

> source.

A technically interested reader taps:

> deeper detail.

Someone who disagrees taps:

> counterarguments.

So:

> **one post adapts to multiple attention budgets without forcing the author to publish a thread or forcing every reader through the same amount of content.**

That feels like actual UX research.

---

# The engineer needs one moment that makes them take it seriously

Show this:

### Existing model

```text id="kh9h2f"
Post {
    body: string
    media: []
}
```

### Canlı Metin

```text id="6ycg3m"
Post {
    blocks: [
        Text,
        Reveal,
        Source,
        Poll,
        Branch,
        Chart,
        DiscussionAnchor
    ]
}
```

Then say:

> **“We are not redesigning the card. We are redesigning the data model of a social-media text post.”**

That sentence is excellent for this project.

Because now the prototype has a technical contribution.

---

# Give the jury a before/after test

This is something I'd absolutely build.

Same information.

### A — conventional post

800 characters.

### B — Canlı Metin

Same information represented progressively.

Give test users both.

Measure:

- time to obtain the main point,
- full-completion rate,
- source-opening rate,
- comprehension questions,
- perceived effort,
- save/share likelihood,
- interaction rate.

The competition explicitly asks for user research summaries and usability-test results among expected deliverables, and its evaluation includes solving a real user problem and improving user experience. ([cdn.teknofest.org](https://cdn.teknofest.org/media/upload/userFormUpload/2026_NSOSYAL_YARISMASI_SARTNAMESI_TR_2026_07_24_v9_1_G92Gv_UtwIa.pdf))

Even **10–20 test users** with a clearly explained methodology gives you something competitors with beautiful mockups won't have:

> evidence.

Not “97% engagement increase!!!”

Just:

> “In our small usability study, participants reached the key information faster and reported lower perceived reading effort.”

That's enough.

---

# And protect yourselves against the obvious attack

A smart juror may say:

> **“Aren't you just making social media even more addictive?”**

Have the answer ready.

This could actually strengthen the project.

> “Our goal isn't maximizing endless consumption. Short video rewards passive continuation. Canlı Metin rewards deliberate interaction and information completion.”
>
> “The design measures completed information units, source exploration and comprehension rather than only dwell time.”

Then show:

> ✓ Read completely  
> Source viewed  
> 2 contextual layers explored

rather than:

> STREAK 🔥🔥🔥 KEEP SCROLLING!!!!

This directly aligns with the competition's stated concern with **digital wellbeing** and higher-quality time on the platform. ([teknofest.org](https://teknofest.org/tr/yarismalar/nsosyal-inovasyon-yarismasi/))

That's a very good defense.

---

# Likely jury questions we should design for now

**“Why isn't this just a poll/thread?”**

> Because those are separate post formats. Canlı Metin introduces composable semantic interactions *inside* a text document.

**“Does every author now need to spend 20 minutes constructing a post?”**

> No. Ordinary posting stays unchanged. Creators optionally insert simple blocks—Reveal, Explain, Poll, Source—and assistance can suggest structure.

**“Why would anybody use this instead of video?”**

> Because text is silent, searchable, extremely information-dense, accessible in low-bandwidth environments, fast to scan and much cheaper to create. We're preserving those advantages while adding interaction.

**“What happens to old NSosyal content?”**

> Backwards-compatible rendering. Plain posts remain plain posts.

**“Can this scale?”**

> Blocks are structured content; interaction telemetry is small event data. AI functions can be optional/on-demand rather than called for every feed impression.

**“Accessibility?”**

> Every interaction has semantic labels, keyboard/screen-reader paths, reduced-motion support and an expanded linear representation.

**“Can I share/export the text?”**

> Yes. There should always be a canonical linear representation of the content.

That last one is actually important.

---

# How our current ideas look through the jury lens

My current rough read — **not a final ranking**:

| Concept | Jury appeal |
|---|---|
| **Living Text / Canlı Metin** | 🔥🔥🔥🔥🔥 |
| **User-controlled feeds / Antennas** | 🔥🔥🔥🔥½ |
| **Trusted verified anonymity** | 🔥🔥🔥🔥½ |
| **Community OS** | 🔥🔥🔥🔥 |
| **Structured social actions** | 🔥🔥🔥🔥 |
| **Privacy-accountable security** | 🔥🔥🔥🔥 |
| **Semantic personal Library** | 🔥🔥🔥½ |
| **Local / incident layer** | 🔥🔥🔥½ |
| **Generic AI moderation** | 🔥🔥½ |
| **Generic creator monetization** | 🔥🔥½ |
| **Simple bot detector** | 🔥🔥 |

Living Text moves upward because it is almost perversely well matched to the **UI/UX weighting**: originality, UX, prototype quality and technical feasibility can all be demonstrated in the exact same 30-second interaction. ([cdn.teknofest.org](https://cdn.teknofest.org/media/upload/userFormUpload/2026_NSOSYAL_YARISMASI_SARTNAMESI_TR_2026_07_24_v9_1_G92Gv_UtwIa.pdf))

And that matters in a live jury setting.

The juror doesn't need to imagine:

> “At 5 million users our graph model would eventually detect coordinated behavior…”

They can **touch it and understand it immediately**.

---

## One more thing: don't “appeal to the jury” by sounding like TEKNOFEST marketing copy

They will presumably hear variations of:

> yerli ve milli yapay zekâ destekli yeni nesil sosyal medya ekosistemi...

all day.

Use their goals, but speak like product people.

Something like:

> **“NSosyal already gives text much more room than many competitors. But giving text more characters doesn't redesign the reading experience. We asked a different question: what would short-form text look like if it had received the same decade of interaction design that short-form video received?”**

Then demo.

**That**, I think, can get a room's attention.
