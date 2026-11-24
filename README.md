# 📰 Daily News Bot - 48+ Commits Daily

**Last Update:** 2026-11-25 01:12:00

**Total News:** 12

**Sources:** Al Jazeera, Hacker News, NASA, BBC

---

## 📰 Latest News

### 1. Launch HN: Versine (YC F26) – MCP to send and receive money

**Source:** Hacker News

**Category:** technology

**Description:**
<p>Hey HN, we’re Harshith, Param, and Vishnu and we're building Versine (<a href="https://versine.com">https://versine.com</a>). Versine lets you send and request money just by talking or texting with your AI (think Venmo with an MCP). We’re software engineers who have worked on distributed systems at Stripe, Databricks, and Amazon.<p>Versine is an MCP that sits in front of a wallet with a balance. With it, your agent can do things like:<p>- Send money to someone with your approval (via passkey in our app)<p>- Send and request money to/from up to 100 people at once<p>- Send money to people without a Versine account (they cash out to their bank in 2 mins)<p>- Pay people without your explicit approval to trusted contacts (you can set this)<p>Here’s a demo: <a href="https://youtube.com/shorts/Q9X7zioEqi0" rel="nofollow">https://youtube.com/shorts/Q9X7zioEqi0</a><p>We started working on this because assistants are frustratingly hands-off when it comes to finance and money movement. You can have your assistant go through a receipt and map out all the amounts owed taking care of splitting the subtotal, taxes, tips, but at the end of it the assistant hands back work to you when you have to go out and make the Venmo transfer.<p>Our current solution is oriented towards power users: those who want to automate everything through their agent use us to split dinners, group trips, or settle poker ledgers. We see ourselves unlocking more value for the general consumer as<p>1. More people turn into power users of agents, and
2. We expand to a more complete banking solution: deposits, transfers, wires, everything you can (and more) do with your bank offered as an MCP.<p>Behind the scenes, each user has a self-custodial stablecoin wallet storing USDC on Base. With self-custodial wallets, users own their keys, meaning money can’t be sent without their approval.<p>Interestingly, we were almost forced into this solution because we had around 4 weeks to build this product (after a pivot), and traditional fiat with a partner bank would have caused far too many regulatory and compliance slowdowns.<p>Because of that, the only fast option that remained was using stablecoin wallets. It also ensures we aren't a Money Services Business (MSB) since we don’t hold control or access to the user’s funds.<p>Each call to the wallet creates what we call one-time or recurring standing permissions. For a one-time payment, your agent makes an MCP call, and you receive a notification in our mobile app. Once you swipe up in the app and approve with a passkey (or your device’s biometric method), we create a one-time permission that instructs your wallet to send $X to your recipient’s address.<p>Trusted contacts let your agent send money to people that you’ve previously authorized without explicit passkey approval. Generally, these are people that you’d trust to send your money back even if your agent made a mistake.<p>We’re also able to support sending money to someone off Versine using claim forwarding, where the user authorizes us to forward a specific amount to a future address (which we create once we verify a recipient's OTP).<p>Param worked on scaling vector search at Databricks and harness evals at Glean. Harshith worked on core Stripe Connect fee-processing infrastructure and built an AWS Fargate autoscaler at Amazon. Vishnu worked on intent-based agent testing infrastructure at Amazon. None of us were experienced in stablecoin or crypto infra before working on Versine but our distributed systems experience has helped us a lot.<p>We'd love for you guys to try it! It's available on iOS and Android and as an MCP on ChatGPT and Claude. We also support a public MCP and REST API for other agents.<p>Please let us know how you find it and if it works as you'd hoped!<p><a href="https://versine.com">https://versine.com</a></p>
<hr />
<p>Comments URL: <a href="https://news.ycombinator.com/item?id=50634426">https://news.ycombinator.com/item?id=50634426</a></p>
<p>Points: 15</p>
<p># Comments: 7</p>

🔗 **Read more:** [https://news.ycombinator.com/item?id=50634426](https://news.ycombinator.com/item?id=50634426)

---

### 2. Ternary Bonsai 2.5 27B

**Source:** Hacker News

**Category:** technology

**Description:**
<p>Article URL: <a href="https://prismml.com/news/bonsai-2-5-27b">https://prismml.com/news/bonsai-2-5-27b</a></p>
<p>Comments URL: <a href="https://news.ycombinator.com/item?id=50633922">https://news.ycombinator.com/item?id=50633922</a></p>
<p>Points: 120</p>
<p># Comments: 34</p>

🔗 **Read more:** [https://prismml.com/news/bonsai-2-5-27b](https://prismml.com/news/bonsai-2-5-27b)

---

### 3. From CUDA and Jax to TorchTPU: Lessons from a Cayley Graph Solver

**Source:** Hacker News

**Category:** technology

**Description:**
<p>Article URL: <a href="https://andlukyane.com/blog/cayley-graphs-and-torchtpu">https://andlukyane.com/blog/cayley-graphs-and-torchtpu</a></p>
<p>Comments URL: <a href="https://news.ycombinator.com/item?id=50633424">https://news.ycombinator.com/item?id=50633424</a></p>
<p>Points: 25</p>
<p># Comments: 0</p>

🔗 **Read more:** [https://andlukyane.com/blog/cayley-graphs-and-torchtpu](https://andlukyane.com/blog/cayley-graphs-and-torchtpu)

---

### 4. Disability benefit review calls for closer link with claimant costs

**Source:** BBC

**Category:** world

**Description:**
A government-commissioned report calls for a "rebalancing" of the amount paid to different claimants.

🔗 **Read more:** [https://www.bbc.co.uk/news/articles/cm4gn6gn9057o?at_medium=RSS&at_campaign=rss](https://www.bbc.co.uk/news/articles/cm4gn6gn9057o?at_medium=RSS&at_campaign=rss)

---

### 5. Two arrested on suspicion of burglary at Prince and Princess of Wales's Norfolk home

**Source:** BBC

**Category:** world

**Description:**
The break-in took place at the family's country retreat in Norfolk, on the Sandringham Estate.

🔗 **Read more:** [https://www.bbc.co.uk/news/articles/cr9d7qdg24vno?at_medium=RSS&at_campaign=rss](https://www.bbc.co.uk/news/articles/cr9d7qdg24vno?at_medium=RSS&at_campaign=rss)

---

### 6. Substance released at Manchester concert could be linked to robberies, police say

**Source:** BBC

**Category:** world

**Description:**
Police are investigating a possible link between the Co-op Live evacuation and reported robberies.

🔗 **Read more:** [https://www.bbc.co.uk/news/articles/cqrmgvnzwrm3o?at_medium=RSS&at_campaign=rss](https://www.bbc.co.uk/news/articles/cqrmgvnzwrm3o?at_medium=RSS&at_campaign=rss)

---

### 7. Hostage situation reported in Colombia as armed men flee into supermarket

**Source:** Al Jazeera

**Category:** world

**Description:**
President Abelardo de la Espriella says police and military have been deployed as situation unfolds in Cartagena.

🔗 **Read more:** [https://www.aljazeera.com/news/2026/11/24/hostage-situation-reported-in-colombia-as-armed-men-flee-into-supermarket?traffic_source=rss](https://www.aljazeera.com/news/2026/11/24/hostage-situation-reported-in-colombia-as-armed-men-flee-into-supermarket?traffic_source=rss)

---

### 8. Brazil doctor uses surfboard and sledgehammer in flood rescue

**Source:** Al Jazeera

**Category:** world

**Description:**
A Brazilian doctor is being hailed a hero after rescuing an old man from severe flooding using a surfboard

🔗 **Read more:** [https://www.aljazeera.com/video/newsfeed/2026/11/24/brazil-doctor-uses-surfboard-and-sledgehammer-in-flood-rescue?traffic_source=rss](https://www.aljazeera.com/video/newsfeed/2026/11/24/brazil-doctor-uses-surfboard-and-sledgehammer-in-flood-rescue?traffic_source=rss)

---

### 9. Libya’s Haftar visits Turkiye days after Ukraine hits Russian warship

**Source:** Al Jazeera

**Category:** world

**Description:**
Ahead of Erdogan’s Libya trip, Haftar’s visit suggests Turkiye seeks another way to bring the country&#039;s rivals together.

🔗 **Read more:** [https://www.aljazeera.com/news/2026/11/24/libyas-haftar-visits-turkiye-days-after-ukraine-hits-russian-warship?traffic_source=rss](https://www.aljazeera.com/news/2026/11/24/libyas-haftar-visits-turkiye-days-after-ukraine-hits-russian-warship?traffic_source=rss)

---

### 10. Wildfire Little Ridge, Highland, Virginia

**Source:** NASA

**Category:** nature

**Description:**
Natural event: Wildfires

🔗 **Read more:** [https://eonet.gsfc.nasa.gov/api/v3/events/EONET_26661](https://eonet.gsfc.nasa.gov/api/v3/events/EONET_26661)

---

### 11. Wildfire White Oak Flat, Alleghany, Virginia

**Source:** NASA

**Category:** nature

**Description:**
Natural event: Wildfires

🔗 **Read more:** [https://eonet.gsfc.nasa.gov/api/v3/events/EONET_26662](https://eonet.gsfc.nasa.gov/api/v3/events/EONET_26662)

---

### 12. Wildfire Greene - Caney Creek Lane, Greene, Tennessee

**Source:** NASA

**Category:** nature

**Description:**
Natural event: Wildfires

🔗 **Read more:** [https://eonet.gsfc.nasa.gov/api/v3/events/EONET_26568](https://eonet.gsfc.nasa.gov/api/v3/events/EONET_26568)

---


**Built with ❤️ by GitHub Actions**