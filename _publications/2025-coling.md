---
title: "A Flash in the Pan: Better Prompting Strategies to Deploy Out-of-the-Box LLMs as Conversational Recommendation Systems."
collection: publications
permalink: /publication/2025-coling
excerpt: 'Accepted at COLING 2025.'
date: 2025-01-01
venue: 'Proceedings of the 31st International Conference on Computational Linguistics'
paperurl: 'https://aclanthology.org/2025.coling-main.561/'
citation: 'Gustavo Adolpho Lucas de Carvalho, Simon Benigeri, Jennifer Healey, <strong>Victor S. Bursztyn</strong>, David Demeter, and Lawrence Birnbaum. 2025. A Flash in the Pan: Better Prompting Strategies to Deploy Out-of-the-Box LLMs as Conversational Recommendation Systems. In Proceedings of the 31st International Conference on Computational Linguistics, pages 8385–8398, Abu Dhabi, UAE. Association for Computational Linguistics.'
---

Conversational Recommendation Systems (CRSs) are a particularly interesting application for out-of-the-box LLMs due to their potential for eliciting user preferences and making recommendations in natural language across a wide set of domains. Somewhat surprisingly, we find however that in such a conversational application, the more questions a user answers about their preferences, the worse the model’s recommendations become. We demonstrate this phenomenon on a previously published dataset as well as two novel datasets which we contribute. We also explain why earlier benchmarks failed to detect this round-over-round performance loss, highlighting the importance of the evaluation strategy we use and expanding upon Li et al. (2023a). We also present preference elicitation and recommendation strategies that mitigate this degradation in performance, beating state-of-the-art results, and show how three underlying models, GPT-3.5, GPT-4, and Claude 3.5 Sonnet, differently impact these strategies. Our datasets and code are available at https://github.com/CtrlVGustavo/A-Flash-in-the-Pan-CRS.