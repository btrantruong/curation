# Algorithmic Curation and Its Societal Impacts

| | |
|---|---|
| **Instructor** | Dr. Bao T. Truong |
| **Time** | Thursdays, 13:00–14:30 |
| **Language** | English |
| **Assessment** | Oral exam |

## Latest Announcement

<!-- LATEST_ANNOUNCEMENT_START -->
> **Week 13 - Designing a "For You" Feed (09/07)**
>
>
> Hi class,
>
> Following our discussion on embedding values into social media, I'd like you to design your own recommendation system for a "For You" feed.
>
> ### Mandatory exercise
> I want you to think critically about what values a recommendation system should promote and how those values can actually be implemented and evaluated. Write up your answer to share in class next time. In your answer, justify your design choices. You can do this through your own reasoning, by referencing industry practices, or by citing peer-reviewed research. Use the steps outlined below.
>
> #### 1. Conceptualization
>
> Think about what we've learned so far, as well as the values you would want a recommendation system to reflect.
>
> The platform can be:
> - a centralized social media platform (e.g., TikTok, X, Instagram),
> - a decentralized platform (e.g., Bluesky or Mastodon),
> - or even a completely new platform that doesn't exist yet.
>
> It also doesn't have to be a general-purpose social network. Maybe it's meme-only, video-only, designed for local communities, or something entirely different.
>
> As you design it, think about questions like:
> - What do you want the platform to encourage or discourage?
> - What kinds of content should be promoted?
> - What signals should the recommendation algorithm use?
> - What additional platform features (moderation, community governance, user controls, etc.) would support those goals?
> - How does the underlying infrastructure (centralized vs. decentralized) enable or limit your design?
>
> One possible approach is to first define the values or goals of your platform, then design the recommendation algorithm, and finally think about what platform features are needed to make those goals achievable.
>
> #### 2. Operationalization
>
> Operationalization is the process of turning abstract ideas into something that can actually be measured or implemented. Here, the goal is to bridge your high-level design ideas with a concrete implementation.
> For example, if your goal is to promote "meaningful conversations," how would the system recognize that? What data or behaviors would it use? What features would the algorithm rely on?
>
> Think about how your recommendation system would bring your values to life:
> - What inputs or signals does it use?
> - What models or rules does it rely on?
> - What information would it need to collect?
> - How does it balance competing objectives?
>
> #### 3. Evaluation
>
> Finally, think about how you would evaluate your system.
>
> Consider questions such as:
> - Is your proposed system actually viable? What parts would be difficult to implement?
> - How would you know whether your recommendation system is achieving its intended goals? What metrics or data would you collect to evaluate success?
> - What unintended or downstream consequences might arise? How could you detect, measure, and mitigate those consequences?
>
> ### Inspiration
>
> Below are some examples for your inspiration. Choose one to read would suffice. They are from platform engineering blog posts, research papers, or released code.
>
> - [X (Twitter) Open-source recommendation algorithm](https://github.com/xai-org/x-algorithm)
> - [Facebook News Feed ranking, powered by machine learning](https://engineering.fb.com/2021/01/26/core-infra/news-feed-ranking/) 
> - [Meta transparency documentation](https://transparency.meta.com/)
> - [Scaling Instagram's recommendation system](https://engineering.fb.com/2025/05/21/production-engineering/journey-to-1000-models-scaling-instagrams-recommendation-system/) 
> - [How TikTok recommends videos "For You"](https://newsroom.tiktok.com/how-tiktok-recommends-videos-for-you?lang=en)
> - [Why a video is recommended](https://newsroom.tiktok.com/learn-why-a-video-is-recommended-for-you?lang=en)
> - [Deep Neural Networks for YouTube Recommendations](https://research.google/pubs/deep-neural-networks-for-youtube-recommendations/)
> - [An Industrial-Scale Sequential Recommender for LinkedIn Feed Ranking](https://arxiv.org/abs/2602.12354) 
> - [Blogpost - The AI researcher's guide to a non-boring Bluesky Feed](https://nsaphra.net/post/bsky/)
>
> ### Optional exercise
>
> Bring your feed to life.
> Decentralized platforms like Bluesky make it possible for people to build their own custom feeds that others can subscribe to. If motivated, you can try building your own custom feed that others can use. It might blow up - you never know! 
>
> ### Bluesky & Mastodon resources to build custom feeds 
> - [Custom Feed documentation](https://docs.bsky.app/docs/starter-templates/custom-feeds)
> - [Bluesky Feed generator repository](https://github.com/bluesky-social/feed-generator)
> - [AT Protocol custom feed tutorial](https://atproto.com/guides/custom-feed-tutorial)
> - [Mastodon Timeline API documentation](https://docs.joinmastodon.org/methods/timelines/)
<!-- LATEST_ANNOUNCEMENT_END -->

→ [All announcements & reading lists](announcements.md)

---

## Course Description

Digital platforms increasingly rely on algorithms to organize and curate information. Recommendation systems and ranking algorithms determine which posts appear in social media feeds, which products are suggested in online stores, and which videos or articles gain visibility. These systems play an important role in shaping culture and economy, both online and offline.

This seminar introduces students to the basic computational ideas behind algorithmic curation and explores their broader social consequences. We will study several foundational methods used in modern recommendation systems, including content similarity, clustering, collaborative filtering, and ranking techniques. Through small computational exercises in Python, students will learn how these methods work and how they influence which content becomes visible or popular.

The course also examines how algorithmic curation interacts with social networks and the spread of information. We discuss how recommendation and ranking systems can create feedback loops that amplify certain content, shape patterns of attention, and influence the diffusion of information online. Throughout the semester, we connect algorithmic choices and biases to broader societal impacts, such as misinformation, filter bubbles, and polarization.

The seminar combines discussion of research papers with short computational exercises and student-led presentations of recent studies. Students should have basic familiarity with programming in Python or another scripting language. Prior experience with machine learning or recommendation systems is not required. By the end of the course, students will have a practical understanding of how algorithmic curation systems operate, introductory experience with core recommendation techniques, and the ability to critically analyze how these systems shape social dynamics online.

## Schedule

| Week | Date | Topic | Key Concepts |
|------|------|-------|--------------|
| 1 | 16/04 | Introduction: What is Algorithmic Curation? | Algorithmic gatekeeping, ranking systems, examples across domains |
| 2 | 23/04 | Algorithms as Cultural and Economic Gatekeepers | Platform power, attention economy, visibility |
| 3 | 30/04 | Content Representation, Similarity, and Clustering | Vector spaces, similarity metrics, k-nearest neighbors, k-means |
| 4 | 07/05 | Collaborative Filtering | User–item matrices, user-based and item-based CF |
| 5 | 14/05 | *(No class)* | |
| 6 | 21/05 | Ranking and Popularity Bias | Ranking objectives, popularity signals, exposure |
| 7 | 28/05 | *(No class)* | |
| 8 | 04/06 | Evaluating Recommendation Systems | Precision, recall, diversity, coverage |
| 9 | 11/06 | Networks and Information Diffusion | Network structure, information diffusion, virality |
| 10 | 18/06 | Algorithmic Bias I | Algorithmic fairness and bias |
| 11 | 25/06 | Algorithmic Bias II | Networked impacts: misinformation, filter bubbles, polarization |
| 12 | 02/07 | Algorithmic Bias III | Feedback loops and ways to address them |
| 13 | 09/07 | Governance, Accountability, and Alternative Designs | Policy responses, economic incentives, research efforts |
| 14 | 16/07 | Final Session: Discussion and Feedback | Course synthesis and open discussion |

## Class Structure

- **Before class:** Read 2–3 papers — one mandatory and one or two from the suggested reading list. ~~Prepare a short summary slide with key insights to present in class. Slides due at least 2 hours before class.~~ Update: Starting June 4, the deliverable for each class will change from a presentation to a written summary. Please prepare a summary for each mandatory academic paper reading (excluding textbook readings) in the format described in section 4) “Takeaways.” As usual, please send your summary to me at least 2 hours before class.

- Please follow this naming convention for the submission: "<date>_<your-last-name>_<optional-title>",
For example, "2026-04-23_Bauer_critique of Baeza-yates".

- **In class:** Students present their findings, followed by open discussion.

## Evaluation

- Participation in discussion
- Final oral exam
