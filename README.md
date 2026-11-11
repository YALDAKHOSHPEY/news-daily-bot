# 📰 Daily News Bot - 48+ Commits Daily

**Last Update:** 2026-11-11 21:14:43

**Total News:** 12

**Sources:** NASA, Hacker News, BBC, Al Jazeera

---

## 📰 Latest News

### 1. Launch HN: Pomerado (YC F26) – Turn any website into an MCP for agents

**Source:** Hacker News

**Category:** technology

**Description:**
<p>Hi HN, we’re Alan and Akshay from Pomerado (<a href="https://pomerado.ai/">https://pomerado.ai/</a>). We connect your agents to any website by turning sites into deterministic, self-healing APIs in minutes, fully self-serve.<p>Agents are no longer limited by their intelligence, but rather by their ability to interact with systems. Airlines, banks, e-commerce, insurance portals, government sites, and legacy portals all lack APIs or MCPs and are common parts of personal assistant or business workflows. Agents instead rely on browser automation or computer use, which can be slow, expensive, and unreliable. And even if computer use were perfect, most companies have banned it out of security and compliance concerns.<p>We discovered this problem while tinkering with our own personal assistants. When OpenClaw came out, we wanted to “live our lives through our agents” and have them do everything for us. We soon found their usefulness was restricted by what tools they could connect to. For example, when trying to book flights, they fell back on computer use, which failed to checkout. These issues got magnified on repeated workflows, like searching many airlines at once.<p>Pomerado started off as a project to improve these personal assistant workflows. As we started building, we realized that just-in-time tool creation could have significant applications for AI builders in legacy verticals.<p>We’re ex-McKinsey and Scale AI, where we drove agent deployments in healthcare, professional services, and telecom. Each time, the biggest bottleneck was getting agents to interface well with legacy websites and apps.<p>Pomerado is what we built. It’s a self-serve platform where devs can create APIs for any website (even those they don’t own), in minutes. Users (or their coding agents) provide a short natural language description, answer a few questions about their workflow, and receive a MCP in less than an hour. Future tool calls use the deterministic MCP, which usually returns results in 5-30 seconds.<p>Here’s a walkthrough of our product: <a href="https://youtu.be/Bi4jci7rgHo" rel="nofollow">https://youtu.be/Bi4jci7rgHo</a><p>In practice:<p>- Our agent opens a browser, explores the website, and performs the requested task once by writing HTTP requests or a Playwright script. This example run establishes how to navigate the website, interact with the relevant controls, and obtain the desired result. If any additional user input is needed (e.g., login, clarification) the agent will ask the user over MCP.<p>- Afterwards, the agent uses the example run, along with all of the data it recorded, to create a generalizable and repeatable API. Throughout this process, a separate Guardian model reviews the coding agent’s calls against a set of guardrails. We also run a battery of tests with synthetic inputs to ensure that the API is generalized and not overfit to one input. A final publication agent ensures that the integration publishes a reasonable and generalized input/output schema<p>- We also handle sites that require authentication and 2FA. For authentication, we pass off to a deterministic sign-in process to ensure the model and our recorders never read customer credentials. Users can store 2FA TOTP seeds or link their account to a Pomerado phone number for us to autofill 2FA for them as well<p>- If future runs fail, a maintenance job is kicked off to repair and improve the tool. The maintenance job can fix broken steps (e.g., a renamed button), add additional functionality (e.g., searching for business class flights in addition to economy), or add new guardrails (e.g., reservation dates must be in the future). We’ve even seen people improve tools by just saying “please make this faster”<p>Unlike computer use, our MCPs are deterministic at runtime, which makes them much faster and cheaper. By taking slightly longer to do a task the first time, you reap the benefits much more in the future. It’s a great fit for repeated, high-volume tasks you want your agent to do.<p>We’d love to have you try it! We have both an open-source (MIT) (<a href="https://github.com/Pomerado/pomerado" rel="nofollow">https://github.com/Pomerado/pomerado</a>) and a free hosted version (<a href="https://app.pomerado.ai">https://app.pomerado.ai</a>).<p>So far, users of Pomerado include:<p>- A personal trainer using agents to prepare workouts and message clients. Before Pomerado, agents couldn’t login and use the site reliably, so this was all manual<p>- Car dealerships connecting their Grok Bots to legacy dealer systems, including marketplaces, CRMs, and ERPs. Dealers switched from computer use, which could take 1hr+<p>- Personal assistants using Pomerado to integrate with a broad range of consumer websites<p>Please ask any questions or share any feedback in the comments, thanks!</p>
<hr />
<p>Comments URL: <a href="https://news.ycombinator.com/item?id=50455811">https://news.ycombinator.com/item?id=50455811</a></p>
<p>Points: 5</p>
<p># Comments: 1</p>

🔗 **Read more:** [https://news.ycombinator.com/item?id=50455811](https://news.ycombinator.com/item?id=50455811)

---

### 2. Faster Retrieval for Better, More Efficient RAG

**Source:** Hacker News

**Category:** technology

**Description:**
<p>Article URL: <a href="https://machinelearning.apple.com/research/faster-retrieval">https://machinelearning.apple.com/research/faster-retrieval</a></p>
<p>Comments URL: <a href="https://news.ycombinator.com/item?id=50455633">https://news.ycombinator.com/item?id=50455633</a></p>
<p>Points: 9</p>
<p># Comments: 0</p>

🔗 **Read more:** [https://machinelearning.apple.com/research/faster-retrieval](https://machinelearning.apple.com/research/faster-retrieval)

---

### 3. A false smoke alarm almost drowned Jane Street's only NYC datacenter

**Source:** Hacker News

**Category:** technology

**Description:**
<p>Article URL: <a href="https://michael.bacarella.com/2026/11/10/false-smoke-alarm-jane-street-datacenter/">https://michael.bacarella.com/2026/11/10/false-smoke-alarm-jane-street-datacenter/</a></p>
<p>Comments URL: <a href="https://news.ycombinator.com/item?id=50455394">https://news.ycombinator.com/item?id=50455394</a></p>
<p>Points: 92</p>
<p># Comments: 40</p>

🔗 **Read more:** [https://michael.bacarella.com/2026/11/10/false-smoke-alarm-jane-street-datacenter/](https://michael.bacarella.com/2026/11/10/false-smoke-alarm-jane-street-datacenter/)

---

### 4. Jonathan Ross 'horrified' by Walliams allegations and Brand conviction

**Source:** BBC

**Category:** world

**Description:**
The TV presenter says he was once "friendly" with David Walliams and Russell Brand, but was "genuinely unaware" of their conduct.

🔗 **Read more:** [https://www.bbc.co.uk/news/articles/cmwy9jl18840o?at_medium=RSS&at_campaign=rss](https://www.bbc.co.uk/news/articles/cmwy9jl18840o?at_medium=RSS&at_campaign=rss)

---

### 5. 'I felt like I was being manipulated': Woman alleges Walliams groomed her as a teenager

**Source:** BBC

**Category:** world

**Description:**
Lilly Creightmore, who has alleged Walliams "groomed" her as a teenager, has told BBC Newsnight that she was "angry" at his behaviour.

🔗 **Read more:** [https://www.bbc.co.uk/news/videos/c8g46y14ye3zo?at_medium=RSS&at_campaign=rss](https://www.bbc.co.uk/news/videos/c8g46y14ye3zo?at_medium=RSS&at_campaign=rss)

---

### 6. Thousands of schools in Italy, Scotland and Northern Ireland hit by threats in suspected bomb hoax

**Source:** BBC

**Category:** world

**Description:**
More than 6,000 Italian schools received a threat. Authorities in all three countries say there appears to be no risk to the public. It is not known if the incidents are linked.

🔗 **Read more:** [https://www.bbc.co.uk/news/articles/cwz0k79pr8z2o?at_medium=RSS&at_campaign=rss](https://www.bbc.co.uk/news/articles/cwz0k79pr8z2o?at_medium=RSS&at_campaign=rss)

---

### 7. Thune re-elected as US Senate Republican leader after midterm losses

**Source:** Al Jazeera

**Category:** world

**Description:**
The Republican ran unopposed, despite some GOP lawmaker demands to evaluate the party&#039;s stinging midterm losses to Democ

🔗 **Read more:** [https://www.aljazeera.com/news/2026/11/11/thune-re-elected-as-us-senate-republican-leader-after-midterm-losses?traffic_source=rss](https://www.aljazeera.com/news/2026/11/11/thune-re-elected-as-us-senate-republican-leader-after-midterm-losses?traffic_source=rss)

---

### 8. Russia-Ukraine talks in UAE secure major prisoner exchange deal

**Source:** Al Jazeera

**Category:** world

**Description:**
Russia and Ukraine have agreed to a major prisoner exchange following two days of US-mediated talks in Abu Dhabi

🔗 **Read more:** [https://www.aljazeera.com/video/newsfeed/2026/11/11/russia-ukraine-talks-in-uae-secure-major-prisoner-exchange-deal?traffic_source=rss](https://www.aljazeera.com/video/newsfeed/2026/11/11/russia-ukraine-talks-in-uae-secure-major-prisoner-exchange-deal?traffic_source=rss)

---

### 9. Palestinian American activist refused UK entry for Gaza fundraiser

**Source:** Al Jazeera

**Category:** world

**Description:**
A Palestinian American activist has been refused entry to the UK to attend his charity’s annual Gaza fundraiser.

🔗 **Read more:** [https://www.aljazeera.com/video/newsfeed/2026/11/11/palestinian-american-activist-refused-uk-entry-for-gaza-fundraiser?traffic_source=rss](https://www.aljazeera.com/video/newsfeed/2026/11/11/palestinian-american-activist-refused-uk-entry-for-gaza-fundraiser?traffic_source=rss)

---

### 10. Tropical Cyclone 03S

**Source:** NASA

**Category:** nature

**Description:**
Natural event: Severe Storms

🔗 **Read more:** [https://eonet.gsfc.nasa.gov/api/v3/events/EONET_26159](https://eonet.gsfc.nasa.gov/api/v3/events/EONET_26159)

---

### 11. Typhoon Cempaka

**Source:** NASA

**Category:** nature

**Description:**
Natural event: Severe Storms

🔗 **Read more:** [https://eonet.gsfc.nasa.gov/api/v3/events/EONET_26157](https://eonet.gsfc.nasa.gov/api/v3/events/EONET_26157)

---

### 12. Tropical Storm Pena

**Source:** NASA

**Category:** nature

**Description:**
Natural event: Severe Storms

🔗 **Read more:** [https://eonet.gsfc.nasa.gov/api/v3/events/EONET_26158](https://eonet.gsfc.nasa.gov/api/v3/events/EONET_26158)

---


**Built with ❤️ by GitHub Actions**