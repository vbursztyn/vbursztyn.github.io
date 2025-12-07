---
title: "Learning to Perform Complex Tasks through Compositional Fine-Tuning of Language Models."
collection: publications
permalink: /publication/2022-emnlp
excerpt: 'Accepted at EMNLP 2022 Findings.'
date: 2022-10-23
venue: 'Findings of the Association for Computational Linguistics: EMNLP 2022'
paperurl: 'https://aclanthology.org/2022.findings-emnlp.121/'
citation: '<strong>Victor S. Bursztyn</strong>, David Demeter, Doug Downey, and Larry Birnbaum. 2022. Learning to Perform Complex Tasks through Compositional Fine-Tuning of Language Models. In Findings of the Association for Computational Linguistics: EMNLP 2022, pages 1676–1686, Abu Dhabi, United Arab Emirates. Association for Computational Linguistics.'
---

How to usefully encode compositional task structure has long been a core challenge in AI. Recent work in chain of thought prompting has shown that for very large neural language models (LMs), explicitly demonstrating the inferential steps involved in a target task may improve performance over end-to-end learning that focuses on the target task alone. However, chain of thought prompting has significant limitations due to its dependency on huge pretrained LMs. In this work, we present compositional fine-tuning (CFT): an approach based on explicitly decomposing a target task into component tasks, and then fine-tuning smaller LMs on a curriculum of such component tasks. We apply CFT to recommendation tasks in two domains, world travel and local dining, as well as a previously studied inferential task (sports understanding). We show that CFT outperforms end-to-end learning even with equal amounts of data, and gets consistently better as more component tasks are modeled via fine-tuning. Compared with chain of thought prompting, CFT performs at least as well using LMs only 7.4% of the size, and is moreover applicable to task domains for which data are not available during pretraining.