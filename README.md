# 📰 Daily News Bot - 48+ Commits Daily

**Last Update:** 2026-09-24 21:32:59

**Total News:** 12

**Sources:** BBC, Hacker News, Al Jazeera, NASA

---

## 📰 Latest News

### 1. Show HN: Whiteboard (YC W26) – An open-source IDE for thoughtful software design

**Source:** Hacker News

**Category:** technology

**Description:**
<p>Hello! We’re Sid, Alex, Ketan, and Milan. We’re building Whiteboard, an open-source desktop app where humans and agents can architect software together in a common workspace. Here’s our repo: <a href="https://github.com/devdotfast/whiteboard" rel="nofollow">https://github.com/devdotfast/whiteboard</a> and our homepage: <a href="https://whiteboard.dev.fast/">https://whiteboard.dev.fast/</a><p>We were missing the feeling of a “whiteboard session” with another dev where you leave with a deep understanding of a system, so we built this app for ourselves. Whiteboard plugs into the tools you already use - e.g. Claude Code, Codex, etc. – and gives your agent an SDK to draw on an in-app canvas to describe its work. We began with an MVP based on HTML artifacts and started rethinking the app as we ran into limitations:<p>1. Built on top of CodeOSS: We found that in pure HTML tools it was hard to connect a spec or diagram to code. In Whiteboard, when you click on visualizations like a sequence diagram, an entity relationship diagram, or a quote from the agent’s trace, you can jump to the underlying code directly. When navigating code, you get keybindings and LSP support from VSCode out of the box. We’ve found this is especially valuable because tradeoffs are often only discovered after a first pass at implementation (re: slop)<p>2. Semantic diff viewer: we wrote a semantic, AST-aware diff viewer in Rust so you can only view the code changes which are relevant to you [1]. We’ve set up some sane defaults: large added functions are summarized as pseudocode, and things like unit tests and large documentation changes are collapsed / hidden. This is all customizable with a WASM-based plugin system.<p>3. Decision Log: We found it difficult to reason about what set of decisions our agents made autonomously. So we built tools for agents to query and link their own traces to the Whiteboard, so you can understand how the requirements that you set were implemented, and understand what decisions your agent made autonomously.<p>Here’s a quick demo video explaining more: <a href="https://youtu.be/ChPn3ftULWE" rel="nofollow">https://youtu.be/ChPn3ftULWE</a><p>Folks at companies like Salesforce and Modal are using Whiteboard today as a review tool for architecture or spec-level changes – really any change where they want to be involved:<p>1. Reviewing your own coding agent’s work: because Whiteboard makes it easier to review large amounts of code, folks will typically have their AI agents create a prototype and a corresponding Whiteboard session so they can iterate on the design.<p>2. Reviewing other people’s changes: We’ve found that Whiteboard is particularly helpful when composed with tools like Greptile. For example, you can run an automated code reviewer on small changes and escalate to a Whiteboard session for the changes that require human judgement.<p>Why we built this: we’re four buddies from college who quit our jobs as tech leads right before agentic coding became industry standard. As we iterated towards an MVP for a previous idea, we struggled to maintain a comprehensible codebase while reaping all the velocity benefits of agentic coding. As more PRs were merged without our understanding, we felt a ‘cognitive debt’ begin to seep in, until it became difficult for us to even contribute to the system [2].<p>We’re releasing our desktop app under an MIT license. Please poke through and feel free to contribute! Eventually we’ll charge companies for a hosted web version that manages whiteboard session creation alongside features like trajectory storage and multiplayer reviews. Everything will always remain self-hostable.<p>Thanks for reading, and we hope you try it out! We would love to hear any feedback and to learn from your expertise.<p>Here’s are the project links again: <a href="https://github.com/devdotfast/whiteboard" rel="nofollow">https://github.com/devdotfast/whiteboard</a>, and you can install (for MacOS + Linux) at <a href="https://install.dev.fast">https://install.dev.fast</a><p>[1] diffs library: <a href="https://github.com/devdotfast/diffr" rel="nofollow">https://github.com/devdotfast/diffr</a>
[2] Credit for the term ‘cognitive debt’ goes to  <a href="https://www.geoffreylitt.com/2026/07/02/understanding-is-the-new-bottleneck" rel="nofollow">https://www.geoffreylitt.com/2026/07/02/understanding-is-the...</a></p>
<hr />
<p>Comments URL: <a href="https://news.ycombinator.com/item?id=49833867">https://news.ycombinator.com/item?id=49833867</a></p>
<p>Points: 30</p>
<p># Comments: 0</p>

🔗 **Read more:** [https://github.com/devdotfast/whiteboard](https://github.com/devdotfast/whiteboard)

---

### 2. LinkedIn wins court order blocking mass scraping of user data

**Source:** Hacker News

**Category:** technology

**Description:**
<p>Article URL: <a href="https://therecord.media/linkedin-wins-court-order-blocking-mass-scraping">https://therecord.media/linkedin-wins-court-order-blocking-mass-scraping</a></p>
<p>Comments URL: <a href="https://news.ycombinator.com/item?id=49832646">https://news.ycombinator.com/item?id=49832646</a></p>
<p>Points: 40</p>
<p># Comments: 27</p>

🔗 **Read more:** [https://therecord.media/linkedin-wins-court-order-blocking-mass-scraping](https://therecord.media/linkedin-wins-court-order-blocking-mass-scraping)

---

### 3. Oracle invokes force majeure on New Mexico AI data center

**Source:** Hacker News

**Category:** technology

**Description:**
<p>Article URL: <a href="https://qz.com/oracle-force-majeure-new-mexico-ai-data-center-092426">https://qz.com/oracle-force-majeure-new-mexico-ai-data-center-092426</a></p>
<p>Comments URL: <a href="https://news.ycombinator.com/item?id=49832564">https://news.ycombinator.com/item?id=49832564</a></p>
<p>Points: 25</p>
<p># Comments: 1</p>

🔗 **Read more:** [https://qz.com/oracle-force-majeure-new-mexico-ai-data-center-092426](https://qz.com/oracle-force-majeure-new-mexico-ai-data-center-092426)

---

### 4. Watch: Why has Trump been so eager to welcome Xi?

**Source:** BBC

**Category:** world

**Description:**
President Donald Trump has been talking about Chinese President Xi Jinping's visit for months, the BBC's Sarah Smith looks at why.

🔗 **Read more:** [https://www.bbc.co.uk/news/videos/c914d17zn6kxo?at_medium=RSS&at_campaign=rss](https://www.bbc.co.uk/news/videos/c914d17zn6kxo?at_medium=RSS&at_campaign=rss)

---

### 5. White House restores access to media outlets banned by Trump after judge's order

**Source:** BBC

**Category:** world

**Description:**
Lawyers for CNN, Politico and MS Now are seeking an emergency court hearing, saying the White House "repeatedly violated" the order.

🔗 **Read more:** [https://www.bbc.co.uk/news/articles/cqe8ek7608mlo?at_medium=RSS&at_campaign=rss](https://www.bbc.co.uk/news/articles/cqe8ek7608mlo?at_medium=RSS&at_campaign=rss)

---

### 6. Poland says fire at Starlink station is sabotage as Denmark warns of rising Russian threat

**Source:** BBC

**Category:** world

**Description:**
The satellite station is used in part to provide internet coverage to neighbouring Ukraine, the government says.

🔗 **Read more:** [https://www.bbc.co.uk/news/articles/cmp30r1klk37o?at_medium=RSS&at_campaign=rss](https://www.bbc.co.uk/news/articles/cmp30r1klk37o?at_medium=RSS&at_campaign=rss)

---

### 7. Ukrainian knifeman kills one, wounds four at abbey in Poland

**Source:** Al Jazeera

**Category:** world

**Description:**
Ukraine&#039;s President Zelenskyy denounces &#039;horrific crime&#039; after 31-year-old attacks clergy, worshippers in border town.

🔗 **Read more:** [https://www.aljazeera.com/news/2026/9/24/ukrainian-knifeman-kills-one-wounds-four-at-abbey-in-poland?traffic_source=rss](https://www.aljazeera.com/news/2026/9/24/ukrainian-knifeman-kills-one-wounds-four-at-abbey-in-poland?traffic_source=rss)

---

### 8. Jerusalem Daily: Ben-Gvir sets out bid to become defence minister

**Source:** Al Jazeera

**Category:** world

**Description:**
In October elections, Israel’s national security minister Itamar Ben-Gvir is hoping to become defence minister.

🔗 **Read more:** [https://www.aljazeera.com/video/newsfeed/2026/9/24/jerusalem-daily-ben-gvir-sets-out-bid-to-become-defence-minister?traffic_source=rss](https://www.aljazeera.com/video/newsfeed/2026/9/24/jerusalem-daily-ben-gvir-sets-out-bid-to-become-defence-minister?traffic_source=rss)

---

### 9. Collapsing currency and inflation leave families struggling in Sudan

**Source:** Al Jazeera

**Category:** world

**Description:**
Rising bread, sugar and meat prices strain Sudanese households already grappling with war and economic instability.

🔗 **Read more:** [https://www.aljazeera.com/features/2026/9/24/collapsing-currency-and-inflation-leave-families-struggling-in-sudan?traffic_source=rss](https://www.aljazeera.com/features/2026/9/24/collapsing-currency-and-inflation-leave-families-struggling-in-sudan?traffic_source=rss)

---

### 10. Tropical Storm Nolo

**Source:** NASA

**Category:** nature

**Description:**
Natural event: Severe Storms

🔗 **Read more:** [https://eonet.gsfc.nasa.gov/api/v3/events/EONET_24786](https://eonet.gsfc.nasa.gov/api/v3/events/EONET_24786)

---

### 11. Tropical Storm Surigae

**Source:** NASA

**Category:** nature

**Description:**
Natural event: Severe Storms

🔗 **Read more:** [https://eonet.gsfc.nasa.gov/api/v3/events/EONET_24787](https://eonet.gsfc.nasa.gov/api/v3/events/EONET_24787)

---

### 12. Tropical Cyclone 01B

**Source:** NASA

**Category:** nature

**Description:**
Natural event: Severe Storms

🔗 **Read more:** [https://eonet.gsfc.nasa.gov/api/v3/events/EONET_24785](https://eonet.gsfc.nasa.gov/api/v3/events/EONET_24785)

---


**Built with ❤️ by GitHub Actions**