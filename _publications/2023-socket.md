---
title: "Do LLMs Understand Social Knowledge? Evaluating the Sociability of Large Language Models with SocKET Benchmark"
collection: publications
permalink: /publications/2023-socket
excerpt: 'We curate a benchmark for NLP tasks on their ability to understand tasks requiring social knowledge and contextual appropriateness, which we name SocKET. We perform analyses on popular open-source LLMs and show that these tasks remain a challenge at its current state.'
date: 2023-05-23
venue: 'Empirical Methods in Natural Language Processing (EMNLP)'
paperurl: 'https://aclanthology.org/2023.emnlp-main.699/'
---

Abstract: Large language models (LLMs) have been shown to perform well at a variety of syntactic, discourse, and reasoning tasks. While LLMs are increasingly deployed in many forms including conversational agents that interact with humans, we lack a grounded benchmark to measure how well LLMs understand \textit{social} language. Here, we introduce a new theory-driven benchmark, SocKET, that contains 58 NLP tasks testing social knowledge which we group into five categories: humor & sarcasm, offensiveness, sentiment & emotion, and trustworthiness. In tests on the benchmark, we demonstrate that current models attain only moderate performance but reveal significant potential for task transfer among different types and categories of tasks, which were predicted from theory. Through zero-shot evaluations, we show that pretrained models already possess some innate but limited capabilities of social language understanding and training on one category of tasks can improve zero-shot testing on others. Our benchmark provides a systematic way to analyze model performance on an important dimension of language and points to clear room for improvement to build more socially-aware LLMs. The associated resources are released at [this https URL](https://github.com/minjechoi/SOCKET)

[Download paper here](https://aclanthology.org/2023.emnlp-main.699.pdf)

## Code
- [Code and models used for the paper](https://github.com/minjechoi/SOCKET)

- [Hugging Face Datasets](https://huggingface.co/datasets/Blablablab/SOCKET)

## Recorded Talks and Slides
- [Talk - 6 minute version](https://drive.google.com/file/d/1pSZemHDGEQ_WbclEuCw0m9fqmFOzU3l4/view?usp=drive_link)
- [Slides](https://docs.google.com/presentation/d/1DDAEpCkOSpJIP6WfBJTDSM197uTCA68K/edit?usp=sharing&ouid=110455722560441196999&rtpof=true&sd=true)