---
title: "Multitask Mayhem: Unveiling and Mitigating Safety Gaps in LLMs Fine-tuning"
collection: publications
category: conferences
permalink: /publication/multi-task-mayhem-llm-safety-gaps
excerpt: "Currently under review at COLING'25. This paper explores the task-wise safety degradation due to fine-tuning on downstream tasks such as summarization, code generation, translation, and classification across various calibration."
date:  # 2024-09-18
venue: # 'Journal 1'
slidesurl: # ''
paperurl: 'https://arxiv.org/pdf/2409.15361'
citation: # 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Recent breakthroughs in Large Language Models (LLMs) have led to their adoption across a wide range of tasks, ranging from code generation to machine translation and sentiment analysis, etc. Red teaming/Safety alignment efforts show that fine-tuning models on benign (non-harmful) data could compromise safety. However, it remains unclear to what extent this phenomenon is influenced by different variables, including fine-tuning task, model calibrations, etc. This paper explores the task-wise safety degradation due to fine-tuning on downstream tasks such as summarization, code generation, translation, and classification across various calibration. Our results reveal that: 1) Fine-tuning LLMs for code generation and translation leads to the highest degradation in safety guardrails. 2) LLMs generally have weaker guardrails for translation and classification, with 73-92% of harmful prompts answered, across baseline and other calibrations, falling into one of two concern categories. 3) Current solutions, including guards and safety tuning datasets, lack cross-task robustness. To address these issues, we developed a new multitask safety dataset effectively reducing attack success rates across a range of tasks without compromising the model’s overall helpfulness. Our work underscores the need for generalized alignment measures to ensure safer and more robust models.