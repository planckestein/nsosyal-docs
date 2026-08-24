Yes — this is already producing much stronger evidence than the previous “what features exist?” pass.

One limitation first: there is no universal public leaderboard of feature requests across social networks, so I’m distinguishing **features the companies themselves have called “most requested/top requested”** from features that merely recur heavily in public forums. That keeps us from pretending ten Reddit posts equal a proper survey.

## The strongest documented requests I found

| Demand | Platform evidence | Status by Aug. 2026 | Why it matters for NSosyal |
|---|---|---|---|
| **Native private messaging** | Threads explicitly called messaging **one of its top-requested features**; its product head described it as the No. 1 request since launch. Bluesky similarly described DMs as its **most requested product feature**. ([about.fb.com](https://about.fb.com/news/2025/07/introducing-messaging-highlighted-perspectives-threads/amp/?utm_source=chatgpt.com)) | Shipped on both | Users expect public conversations to transition naturally into private ones. NSosyal already has DMs, so the innovation opportunity is *better* DM mechanics rather than DMs themselves. |
| **Edit posts** | X's own documentation calls Edit Post a **“highly requested feature.”** ([help.x.com](https://help.x.com/en/using-x/x-premium-how-to?utm_source=chatgpt.com)) | Exists, but tied to X Premium | Very simple concept, but **transparent editing + edit history + correction notices** could be useful for trustworthy social discourse. |
| **Organize/save posts privately** | Bluesky's Saved Posts/bookmarks were described as one of its **most in-demand features**. Discord users repeatedly requested personal message bookmarks for years before Discord began experimenting with bookmarks/reminders. ([techcrunch.com](https://techcrunch.com/2025/09/08/bluesky-adds-private-bookmarks/?utm_source=chatgpt.com)) | Partly solved | “Save” clearly wants to evolve into a **personal knowledge system**: folders, tags, reminders, search, notes, collections. |
| **Control profile layout** | Instagram said rearranging profile grids was among its **most frequently requested features**, eventually rolling it out broadly in June 2026. ([techcrunch.com](https://techcrunch.com/2025/06/12/instagram-will-finally-let-you-rearrange-your-grid/?utm_source=chatgpt.com)) | Shipped | Particularly relevant because NSosyal already has unusually detailed/CV-like profiles. Users clearly value control over how their identity is presented. |
| **Playback controls for short-form media** | YouTube says playback-speed controls were among the Shorts community's **top-requested features**. ([blog.youtube](https://blog.youtube/news-and-events/youtube-shorts-experience-updates-features/?utm_source=chatgpt.com)) | Shipped June 2026 | Small feature, huge demand: users dislike media players deciding how they must consume something. |
| **Search comments/discussions properly** | Reddit surveyed users about search; **comment search was one of the top requested search improvements**. ([redditinc.com](https://redditinc.com/news/new-on-reddit-comment-search-improved-search-results-relevance-updated-search-design?utm_source=chatgpt.com)) | Shipped and subsequently expanded | Social search is still bad almost everywhere. NSosyal could go much further than literal keyword matching. |
| **Multiple accounts / identity switching** | A Discord account-switching request accumulated about **1,230 votes and 197 comments**; Discord subsequently built desktop account switching. Mobile switching remained separately requested. ([support.discord.com](https://support.discord.com/hc/en-us/community/posts/360057832011-Multiple-Discord-Accounts?utm_source=chatgpt.com)) | Partly solved | Strong evidence that people don't actually have one monolithic online identity. |
| **Scheduled messages/posts** | Discord has years of repeated requests. One 2018 request has **163 votes/32 comments**, with many duplicate requests afterward. Threads ultimately added post scheduling in 2025. ([support.discord.com](https://support.discord.com/hc/en-us/community/posts/360032382432-Send-a-scheduled-message-Suggestion?sort_by=votes&utm_source=chatgpt.com)) | Solved inconsistently | Useful for creators, organizations, communities, students, clubs and event management. |
| **Choose what someone's reposts do to your feed** | Bluesky has an open feature request specifically to **hide reposts/quote-posts per followed account**; Threads users independently ask for essentially the same thing. ([github.com](https://github.com/bluesky-social/social-app/issues/1116?utm_source=chatgpt.com)) | Still uneven across platforms | Interesting because it distinguishes **“I like this person's posts”** from **“I want everything they amplify.”** |
| **Control or disable whole content formats** | YouTube finally added a **zero-minute Shorts limit** after longstanding demand to get Shorts out of users' experience. Threads users similarly still ask for things like disabling video autoplay. ([theverge.com](https://www.theverge.com/streaming/912898/youtube-shorts-feed-limit-zero-minutes?utm_source=chatgpt.com)) | Increasingly being added | This points toward user-selectable **modes**, rather than every social product becoming one giant mixed feed. |

And then there is the category that, in my view, dwarfs almost everything else:

# Users want control over the algorithm

This shows up independently on basically every major platform.

Threads first let users choose/default custom feeds, then created **Dear Algo**, and by June 2026 expanded that into **Your Algo**, where users privately tell Threads which subjects they want more or less of and for how long. The original Dear Algo was actually inspired by users already posting attempts to “talk” to the recommendation algorithm themselves. ([techcrunch.com](https://techcrunch.com/2025/03/20/threads-adds-new-features-to-highlight-topics-and-limit-replies/?utm_source=chatgpt.com))

TikTok built **Manage Topics** plus AI-powered **Smart Keyword Filters**, after hundreds of millions of keyword-filter uses demonstrated that people actively try to sculpt what the recommendation system shows them. ([newsroom.tiktok.com](https://newsroom.tiktok.com/tiktok-trending-summer-2025-plus-new-ways-to-shape-your-feed?lang=en-150&utm_source=chatgpt.com)) A 2026 empirical study of TikTok also found that users can have difficulty making the recommendation system permanently stop showing unwanted subjects—even after explicitly using “Not Interested.” ([arxiv.org](https://arxiv.org/abs/2605.10690?utm_source=chatgpt.com))

YouTube's decision to let users effectively shut off Shorts altogether is another version of the same demand: **“stop deciding that I must consume this.”** ([theverge.com](https://www.theverge.com/streaming/912898/youtube-shorts-feed-limit-zero-minutes?utm_source=chatgpt.com))

X continues to expose Following versus For You, but users were still complaining in 2026 when chronological behavior appeared to change or become less accessible on some clients. X has since gone further and introduced Grok-powered custom topic timelines. ([help.x.com](https://help.x.com/en/using-x/x-timeline?utm_source=chatgpt.com))

Instagram/Facebook feed control became significant enough that a Dutch court ordered Meta to make opting out of personalized recommendation feeds direct and persistent under the EU Digital Services Act. ([reuters.com](https://www.reuters.com/technology/dutch-court-gives-meta-more-time-change-timeline-settings-2025-10-28/?utm_source=chatgpt.com))

Bluesky, meanwhile, essentially built **algorithmic choice into the product's philosophy**, but even there users ask for finer controls—for instance muting one person's reposts without muting their original posts, or dividing a person's output into separately followable “channels.” ([github.com](https://github.com/bluesky-social/social-app/issues/1116?utm_source=chatgpt.com))

So I'd mark **FEED / ALGORITHM CONTROL** in enormous red letters in our research notes.

---

## Something else important emerged: users want **granularity**

A lot of requests aren't really demands for completely novel technologies.

They're variants of:

**“You gave me an ON/OFF switch when I actually want a mixer board.”**

Don't:

> Mute this person.

Give me:

> Keep their original posts, hide their reposts.

Don't:

> Do you want recommendations?

Give me:

> More motorsports, normal amount of technology, less politics this week, zero celebrity gossip, and don't recommend posts I've already seen.

Don't:

> Private/public profile.

Give me:

> Professional posts public, hobby community visible to followers, personal posts mutuals-only.

Don't:

> Enable DMs.

Give me:

> Mutuals can DM directly, verified organizations go into requests, strangers cannot send media, nobody under account-age X can DM me, and completely disable DMs whenever I want.

Threads' DM rollout is an excellent cautionary example. Meta called DMs its most-requested feature, **then immediately faced users complaining that they wanted the ability to disable them**, particularly because of harassment/spam concerns. ([techcrunch.com](https://techcrunch.com/2025/07/03/not-everyone-is-thrilled-with-threads-dms/?utm_source=chatgpt.com))

So “most requested” does **not necessarily mean universally wanted**.

That distinction could produce a very good competition project.

---

## There is also a fascinating **identity/persona** cluster

Discord users spent years asking for multiple-account switching largely because they wanted to separate **work / school / gaming / personal identities**. ([support.discord.com](https://support.discord.com/hc/en-us/community/posts/360057832011-Multiple-Discord-Accounts?utm_source=chatgpt.com))

Bluesky has an unusually ambitious open feature proposal called **Channels**, motivated by almost exactly the same problem: instead of creating five accounts, let one person divide their output into different separately followable streams—art, work, NSFW, politics, personal life, etc. Followers could subscribe only to the parts they care about. ([github.com](https://github.com/bluesky-social/social-app/issues/1078?utm_source=chatgpt.com))

That one caught my attention **specifically for NSosyal**.

Imagine:

**Ahmet Yılmaz**
- 👨‍💻 Yazılım
- 🎮 Oyun
- 📷 Fotoğraf
- 🎓 Akademik
- 💬 Kişisel

I could follow Ahmet but subscribe only to **Yazılım + Akademik**.

That's materially different from Communities, hashtags, Lists or multiple accounts.

And NSosyal's richer profile/CV orientation may make that concept fit better there than it does on X.

---

## Another recurring demand: **“I saw something. Help me find it again.”**

This sounds mundane, but several platforms keep rediscovering it.

Bluesky users demanded bookmarks. ([techcrunch.com](https://techcrunch.com/2025/09/08/bluesky-adds-private-bookmarks/?utm_source=chatgpt.com))

Discord users demanded personal message bookmarks, eventually leading to an experimental bookmark/reminder system. ([support.discord.com](https://support.discord.com/hc/en-us/articles/26442819646999-Message-Bookmarks-and-Reminders?utm_source=chatgpt.com))

X now has bookmark folders for Premium and, in 2026, introduced a broader **History** area for bookmarks, likes, articles and long videos. ([help.x.com](https://help.x.com/en/using-x/x-premium-how-to?utm_source=chatgpt.com))

Reddit users demanded better searching of comments because finding a remembered discussion by opening giant threads manually was painful. ([redditinc.com](https://redditinc.com/news/new-on-reddit-comment-search-improved-search-results-relevance-updated-search-design?utm_source=chatgpt.com))

Bluesky currently has an open request even for **searching specifically within posts you've liked**. ([github.com](https://github.com/bluesky-social/social-app/issues/7971?utm_source=chatgpt.com))

That's a coherent problem:

> **Social networks are extremely good at showing you new information and bizarrely bad at helping you retrieve information you've already encountered.**

There might be something competition-worthy hiding in that.

Think less “Bookmarks.”

Think:

**My NSosyal Library**

Search:

> “That post I saw two weeks ago explaining İstanbul earthquake building regulations; I think an engineer posted it.”

And it searches your:

- seen history,
- likes,
- saves,
- replies,
- followed accounts,
- downloaded/read Küre articles,

semantically rather than requiring exact keywords.

Now *that* starts becoming a Social AI project rather than a bookmark button.

---

## Current research ranking

Based on the strength and recurrence of the demand signals so far, I'd currently rank the underlying user needs approximately:

| Rank | Underlying user demand | Signal strength |
|---|---|---|
| **1** | **Control what the algorithm/feed shows me** | 🔥🔥🔥🔥🔥 |
| **2** | **Let me selectively filter people/topics/content types without unfollowing everything** | 🔥🔥🔥🔥🔥 |
| **3** | **Let me find things I've previously seen/saved/liked** | 🔥🔥🔥🔥 |
| **4** | **Better control over private communication and who may contact me** | 🔥🔥🔥🔥 |
| **5** | **Organize my identity/profile/content instead of one giant chronological dump** | 🔥🔥🔥🔥 |
| **6** | **Edit/correct content safely after publication** | 🔥🔥🔥 |
| **7** | **Multiple personas/accounts with painless switching** | 🔥🔥🔥 |
| **8** | **Schedule content/messages** | 🔥🔥🔥 |
| **9** | **Control the media experience—autoplay, Shorts/Reels, speed, etc.** | 🔥🔥🔥 |
| **10** | **Better search/discovery within conversations** | 🔥🔥🔥 |

This is already changing how I'd evaluate the previous feature-landscape list.

For example, **“AI post generator” is looking even worse**. Users aren't screaming for another machine to write posts for them. The strongest demands are for **agency over the giant information machine they're already trapped inside**.

And that gives us a potentially much stronger direction for NSosyal:

> **Don't use AI to generate more content. Use AI to give the user control over existing content.**

I think we should keep mining before locking onto that, though. The next useful pass is specifically **Reddit/X/Bluesky/Threads feature-request threads with actual vote/like/comment counts**, so we can start putting numbers behind these instead of relying on qualitative recurrence.
