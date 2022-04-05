---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Victor S. Bursztyn. I am a final-year PhD Candidate in Artificial Intelligence at Northwestern University, advised by Prof. Larry Birnbaum. In two years of work in the R&D industry, before and during my PhD, I have co-invented [eight patent applications to the USPTO](https://patents.google.com/?inventor=Victor+Bursztyn) (four as first inventor). Since May 2020, I have had the pleasure to collaborate with Adobe Research and publish at [EMNLP 2021](https://research.adobe.com/news/adobe-research-at-emnlp-2021/), [NeurIPS 2021](https://research.adobe.com/news/adobe-research-at-neurips-2021/), and [CHI 2021](https://research.adobe.com/news/adobe-research-at-chi-2021/).

What I Expect for the Future
------
My research is broadly focused on the computational modeling of human conversations, lying mainly in the subfield of Natural Language Processing but also interfacing with Human-Computer Interaction, Recommender Systems, Information Retrieval, and Machine Learning. I am passionate about the roles that conversation modeling will play in the next generation of intelligent systems, which I identify as at least two:

1. Conversations will likely improve human-computer interactions for individual users. For example, a user who can give conversational feedback on their search results will be able to avoid multiple rounds of searching from scratch, trying to guess which combination of keywords will lead to the desired results;
2. Conversations will eventually facilitate collaborations involving multiple parties. For example, when an editing software can understand a sequence of comments made by co-workers on a particular work, it will be able to suggest changes that will assist in the development of such work. Once we reach this stage, users will have an additional incentive to exchange feedback on digital spaces, consolidating the importance of conversation modeling in AI-powered software.

This vision has guided me to investigate the first role through multiple angles in the past few years, and it motivates me to seek employment in companies that are likely to view conversation modeling as strategic in the years to come.

How I Have Worked Towards It
------
My core work during the PhD has been done in partnership with Jennifer Healey, Eunyee Koh, and Nedim Lipka (Adobe Research), Prof. Doug Downey (Allen Institute for AI), and David Demeter (Northwestern University).

First, we developed a functional conversational system focused on helping users navigate a limited set of options, a search scenario that exists in inherently-constrained environments (e.g., when searching for products in a physical store with limited inventory, or when searching for restaurants nearby). We presented this system in a [CHI 2021 paper](https://www.youtube.com/watch?v=97NOZQPrQr4), where we also identified a key user need when searching for restaurants: the ability to critique one of the options (e.g., “It doesn’t look good for a date”) and have the system understand the preference that is implied (e.g., “I prefer a more romantic place”).

Following this finding, we developed a lower-level study focused on the NLP task of critique interpretation. In a [paper published at EMNLP 2021](https://aclanthology.org/2021.emnlp-main.145/), we investigated whether large language models (LLMs) such as BERT and GPT-3 can perform critique-to-preference transformations, and to what extent does this step help recommendation retrieval. In two ablation studies, we found that using GPT-3 to perform critique-to-preference transformation consistently improves our ability to retrieve recommendations from restaurant reviews: 110-124% when retrieval is based on pre-trained embeddings, and 19-59% when it relies on fine-tuning BERT. The paper also includes three potential explanations for this improved performance.

Finally, these results encouraged us to go yet one level deeper. Our current work focuses on teaching GPT-3 to perform the entire recommendation task (e.g., “You don’t like cold weather. Between London and Lisbon, you should visit…”), with all the implied sub-steps, instead of performing only the critique-to-preference transformation. In this example, an LLM is expected to perform at least three sub-steps: (i) interpret a negatively phrased preference; (ii) retrieve temperature facts for two entities, London and Lisbon; and (iii) compare such entities in light of the preference and facts. We have developed a novel method for teaching LLMs to perform any complex task involving a series of sub-steps, which we call Compositional Language Model Fine-Tuning (CLMFT). In a forthcoming paper, we will show how CLMFT consistently outperforms standard methods based on end-to-end learning.

Beyond Work
------
As a Brazilian graduate student in the United States, I am always happy to participate in initiatives to improve access of underrepresented communities to the Computer Science field. At Northwestern, I was among the students who co-founded [Latin@CS](https://sites.northwestern.edu/hispanicsincs/), an organization for this very purpose focused on the LatinX community.

I am married to Vanessa, a graphic designer also from Rio de Janeiro, Brazil. As low-budget foodies, we love to spread the word about the wholesomeness of tropical fruits in the hope of increasing [Cashew](https://en.wikipedia.org/wiki/Cashew) import --- the fruit, not the nut! --- in the US :)
