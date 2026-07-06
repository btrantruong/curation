# Announcements

---

All readings are available on the course portal or in the `readings` folder of this repo.

## Week 13 - Designing a "For You" Feed (09/07)

Hi class,

Following our discussion on embedding values into social media, I'd like you to design your own recommendation system for a "For You" feed.

### Mandatory exercise
I want you to think critically about what values a recommendation system should promote and how those values can actually be implemented and evaluated. Write up your answer to share in class next time. In your answer, justify your design choices. You can do this through your own reasoning, by referencing industry practices, or by citing peer-reviewed research. Use the steps outlined below.

#### 1. Conceptualization

Think about what we've learned so far, as well as the values you would want a recommendation system to reflect.

The platform can be:
- a centralized social media platform (e.g., TikTok, X, Instagram),
- a decentralized platform (e.g., Bluesky or Mastodon),
- or even a completely new platform that doesn't exist yet.

It also doesn't have to be a general-purpose social network. Maybe it's meme-only, video-only, designed for local communities, or something entirely different.

As you design it, think about questions like:
- What do you want the platform to encourage or discourage?
- What kinds of content should be promoted?
- What signals should the recommendation algorithm use?
- What additional platform features (moderation, community governance, user controls, etc.) would support those goals?
- How does the underlying infrastructure (centralized vs. decentralized) enable or limit your design?

One possible approach is to first define the values or goals of your platform, then design the recommendation algorithm, and finally think about what platform features are needed to make those goals achievable.

#### 2. Operationalization

Operationalization is the process of turning abstract ideas into something that can actually be measured or implemented. Here, the goal is to bridge your high-level design ideas with a concrete implementation.
For example, if your goal is to promote "meaningful conversations," how would the system recognize that? What data or behaviors would it use? What features would the algorithm rely on?

Think about how your recommendation system would bring your values to life:
- What inputs or signals does it use?
- What models or rules does it rely on?
- What information would it need to collect?
- How does it balance competing objectives?

#### 3. Evaluation

Finally, think about how you would evaluate your system.

Consider questions such as:
- Is your proposed system actually viable? What parts would be difficult to implement?
- How would you know whether your recommendation system is achieving its intended goals? What metrics or data would you collect to evaluate success?
- What unintended or downstream consequences might arise? How could you detect, measure, and mitigate those consequences?

### Inspiration

Below are some examples for your inspiration. Choose one to read would suffice. They are from platform engineering blog posts, research papers, or released code.

- [X (Twitter) Open-source recommendation algorithm](https://github.com/xai-org/x-algorithm)
- [Facebook News Feed ranking, powered by machine learning](https://engineering.fb.com/2021/01/26/core-infra/news-feed-ranking/) 
- [Meta transparency documentation](https://transparency.meta.com/)
- [Scaling Instagram's recommendation system](https://engineering.fb.com/2025/05/21/production-engineering/journey-to-1000-models-scaling-instagrams-recommendation-system/) 
- [How TikTok recommends videos "For You"](https://newsroom.tiktok.com/how-tiktok-recommends-videos-for-you?lang=en)
- [Why a video is recommended](https://newsroom.tiktok.com/learn-why-a-video-is-recommended-for-you?lang=en)
- [Deep Neural Networks for YouTube Recommendations](https://research.google/pubs/deep-neural-networks-for-youtube-recommendations/)
- [An Industrial-Scale Sequential Recommender for LinkedIn Feed Ranking](https://arxiv.org/abs/2602.12354) 
- [Blogpost - The AI researcher's guide to a non-boring Bluesky Feed](https://nsaphra.net/post/bsky/)

### Optional exercise

Bring your feed to life.
Decentralized platforms like Bluesky make it possible for people to build their own custom feeds that others can subscribe to. If motivated, you can try building your own custom feed that others can use. It might blow up - you never know! 

### Bluesky & Mastodon resources to build custom feeds 
- [Custom Feed documentation](https://docs.bsky.app/docs/starter-templates/custom-feeds)
- [Bluesky Feed generator repository](https://github.com/bluesky-social/feed-generator)
- [AT Protocol custom feed tutorial](https://atproto.com/guides/custom-feed-tutorial)
- [Mastodon Timeline API documentation](https://docs.joinmastodon.org/methods/timelines/)

## Week 12 - Efforts to improve social media recommendations (02/07)

- **We're meeting again on Zoom (link can be found in my announcement email)** 
- Feel free to choose any 2 papers out of the list below for your reading this week. All of them should be publicly available through the links provided here, but let me know if you cannot access any of them. 

### The effects of Facebook algorithm
- [Does social media polarize voters? Unprecedented experiments on Facebook users reveal surprises](https://www.science.org/content/article/does-social-media-polarize-voters-unprecedented-experiments-facebook-users-reveal)
- [How do social media feed algorithms affect attitudes and behavior in an election campaign?](https://www.science.org/doi/10.1126/science.abp9364)
- [Like-minded sources on Facebook are prevalent but not polarizing](https://www.nature.com/articles/s41586-023-06297-w)
- [Reshares on social media amplify political news but do not detectably affect beliefs or opinions](https://www.science.org/doi/10.1126/science.add8424)

### The effects of Twitter/X algorithm
- [The political effects of X’s feed algorithm](https://www.nature.com/articles/s41586-026-10098-2)
- [Algorithmic amplification of politics on Twitter](https://www.pnas.org/doi/full/10.1073/pnas.2025334119)

### Algorithmic popularity bias 
- [How algorithmic popularity bias hinders or promotes quality](https://www.nature.com/articles/s41598-018-34203-2)
- [Navigation services amplify concentration of traffic and emissions in our cities](https://arxiv.org/pdf/2407.20004)

### Designing alternative social media feeds 
- [Embedding Democratic Values into Social Media AIs via Societal Objective Functions](https://dl.acm.org/doi/10.1145/3641002)
- [Reranking partisan animosity in algorithmic social mediafeeds alters affective polarization](https://www.science.org/doi/10.1126/science.adu5584)
- [The Prosocial Ranking Challenge: Reducing Polarization on Social Media without Sacrificing Engagement](https://arxiv.org/pdf/2603.19626)
- [Bonsai: Intentional and Personalized Social Media Feeds](https://dl.acm.org/doi/pdf/10.1145/3772318.3791855)
- [Identifying Constructive Conflict in Online Discussions through Controversial yet Toxicity Resilient Posts](https://ojs.aaai.org/index.php/ICWSM/article/view/42738)
- [Political audience diversity and news reliability in algorithmic ranking](https://www.nature.com/articles/s41562-021-01276-5)

## Week 10--11 — Understanding Social Media — Algorithmic & network impacts (25/06)

- **Note that we won't meet on June 18**
- The next meeting is June 25, on Zoom (link can be found in my announcement email)

**Mandatory:**
- Understanding Social Media Recommendation Algorithms by Arvind Narayanan
- The Attention Economy by Filippo Menzer and Thomas Hills
Available in `readings/week10_11_recsys_society.zip`

**Optional readings:**
- [YY Ahn 2026 NetSci Keynote](https://yyahn.com/talks/netsci2026-keynote/)
- [Experimental evidence of massive-scale emotional contagion through social networks](https://www.pnas.org/doi/abs/10.1073/pnas.1320040111)

### Network science topics

For those interested in complexity and network science, here are some resources.

**Online course**

- [Complexity Explorer courses](https://www.complexityexplorer.org/#gsc.tab=0) by [the Santa Fe Institute](https://www.santafe.edu/) — a great way to understand the foundational theories of complex systems science.

**Books**

- *Network Science* by Albert-László Barabási — freely available online at [networksciencebook.com](https://networksciencebook.com).
- *A First Course in Network Science* by Filippo Menczer, Santo Fortunato & Clayton A. Davis.
- *Introduction to the Theory of Complex Systems* by Stefan Thurner, Rudolf Hanel & Peter Klimek.
- *The Computational Beauty of Nature: Computer Explorations of Fractals, Chaos, Complex Systems, and Adaptation* by Gary William Flake.
- *Networks, Crowds, and Markets* by David Easley & Jon Kleinberg.
- *Think Complexity: Complexity Science and Computational Modeling* by Allen Downey.

**Reading collections in this repo**
- A folder of readings on individual network science topics (collective motion, community detection, mobility, network robustness, science of science, and more) — see `readings/topics in network science/`, where each topic is also available as its own zip.

## Week 9 — Intro to Network Science (11/06)

**Mandatory:**
- Watch [Veritasium - Can you really reach anyone in 6 steps?](https://www.youtube.com/watch?v=CYlon2tvywA)
- [Barabási Chapter 2 (Graph Theory)](https://networksciencebook.com/chapter/2)
- Play around with the simulations in the video:
    - [Disease spreading](https://www.veritasium.com/simulation2)
    - [Preferential attachment](https://ve42.co/barabasiAlbertSim)  


**Optional readings:**
Available in `readings/week07_virality.zip`
- Salganik et al., 2006 
- Weng et al., 2013 

## Week 8 — Collaborative Filtering (04/06)

**Mandatory readings:**

- MMDS ch. 9.3 — Collaborative Filtering (pp. 321–326)
- Koren et al. (2009) — *Matrix Factorization Techniques for Recommender Systems* (`readings/week08_...`)

**Optional readings:**

- MMDS ch. 9.4 — Dimensionality Reduction
- [How to read academic papers](readings/How%20to%20read%20academic%20papers.docx)


---

## Week 7 - No class (28/05)

---

## Week 6 — Evaluating Recommender Systems (21/05)

**Mandatory:**

- Kaminskas & Bridge — *Diversity, Serendipity, Novelty, and Coverage*

The additional readings cover many of the same concepts from slightly different perspectives and levels of technical detail — choose whichever feels most intuitive as a substitute for the mandatory reading.

For further exploration, see Mena-Maldonado et al. (2021) on false-positive metrics in recommender system evaluation.

---

## Week 4 — Content-Based Recommendations (07/05)

This week we continue with the Spotify dataset as a running example for content-based recommendation.

**Mandatory readings:**

- MMDS ch. 9.1 — A Model for Recommendation Systems (pp. 307–311)
- MMDS ch. 9.2 — Content-Based Recommendations (pp. 311–320)

**Optional readings:**

- Jain (2010) — *Data Clustering: 50 Years Beyond K-Means* (`readings/week04_...`)
- [How Hacker News ranking works](https://medium.com/hacking-and-gonzo/how-hacker-news-ranking-algorithm-works-1d9b0cf2c08d)
- [How Reddit ranking works](https://medium.com/hacking-and-gonzo/how-reddit-ranking-algorithms-work-ef111e33d0d9)

---

## Week 3 — Content Representation & Similarity (30/04)

Apologies for the late notice — to make up for it, the readings are short. This week we walk through the representation of content in vector space.

We draw from *Mining of Massive Datasets* (Leskovec, Rajaraman & Ullman, 2020), a wonderful resource on data mining and the Web. The full book is freely available at [infolab.stanford.edu/~ullman/mmds/book.pdf](http://infolab.stanford.edu/~ullman/mmds/book.pdf) — let me know if you have trouble accessing it.

**Mandatory readings:**

- MMDS ch. 1.3.1 — Importance of Words in Documents (pp. 8–9)
- MMDS ch. 3.1 — Finding Similar Items: Near-Neighbor Search (pp. 73–77)
- MMDS ch. 7.3 — K-Means Algorithms (pp. 254–257)

These give us the necessary ingredients to build up to the in-class example.

**Optional readings** (treat as mandatory if you already know TF-IDF, vector distances, and k-NN):

- MMDS ch. 7.3 (continued) — K-Means (pp. 257–262)
- MMDS ch. 9.1 — A Model for Recommendation Systems (pp. 307–311)
- MMDS ch. 9.2 — Content-Based Recommendations (pp. 311–320)
- Mikolov et al. (2013) — *Distributed Representations of Words and Phrases* (word2vec)
- [Accessible blog post on word2vec](https://jalammar.github.io/illustrated-word2vec/)
