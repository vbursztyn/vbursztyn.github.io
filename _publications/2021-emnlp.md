---
title: "\"It doesn't look good for a date\": Transforming Critiques into Preferences for Conversational Recommendation Systems."
collection: publications
permalink: /publication/2021-emnlp
excerpt: 'Acceptance rate of 17.9%. Paper also invited for oral presentation.'
date: 2021-11-01
venue: 'Proceedings of the Conference on Empirical Methods in Natural Language Processing'
paperurl: 'https://aclanthology.org/2021.emnlp-main.145/'
citation: '<strong>Victor S. Bursztyn</strong>, Jennifer Healey, Nedim Lipka, Eunyee Koh, Doug Downey, and Larry Birnbaum. 2021. “It doesn’t look good for a date”: Transforming Critiques into Preferences for Conversational Recommendation Systems. In Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing, pages 1913–1918, Online and Punta Cana, Dominican Republic. Association for Computational Linguistics.'
---

Conversations aimed at determining good recommendations are iterative in nature. People often express their preferences in terms of a critique of the current recommendation (e.g., “It doesn’t look good for a date”), requiring some degree of common sense for a preference to be inferred. In this work, we present a method for transforming a user critique into a positive preference (e.g., “I prefer more romantic”) in order to retrieve reviews pertaining to potentially better recommendations (e.g., “Perfect for a romantic dinner”). We leverage a large neural language model (LM) in a few-shot setting to perform critique-to-preference transformation, and we test two methods for retrieving recommendations: one that matches embeddings, and another that fine-tunes an LM for the task. We instantiate this approach in the restaurant domain and evaluate it using a new dataset of restaurant critiques. In an ablation study, we show that utilizing critique-to-preference transformation improves recommendations, and that there are at least three general cases that explain this improved performance.