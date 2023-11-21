---
layout: archive
title: "Research Project"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

## BioLlama: Biomedical Inference Via Tool-Augmented Large Language Model

Despite the large amount of publicly available information such as document and examples, most biomedical APIs require a wealth of expertise and a lot of time to master. To relieve biomedical researchers from this trouble, we train large language models to automatically solve user-assigned biomedical inference task. 

To be more specific, user only need to give a task description and an API document, our model will take over and directly give an executable script to solve the task.

In fact, there are already efficient retrievers that can automatically find the related API documents based on task description. Therefore, the only thing the user need to provide is the task description. Then a pipeline based on our model can take over and automatically solve the user's needs.

Sep. 2023 - Now



## Enhance Biomedical Task with GPT4
Use GPT-4-generated biomedical information to enhance biomedical task. Our motivation is that gpt4 can be introduced into biomedical tasks by generating extra information that is orthogonal to the original task features. Intuitively, broad tasks can benefit in this way.

This project failed to overperform the baseline. A major reason could be the quality of embedding. At that time, we only had access to models such as BioBERT to encode the generated content, and we did not have access to GPT3.5 embedding. Recently, a similar work [GenePT](https://www.biorxiv.org/content/10.1101/2023.10.16.562533v1.full.pdf) using GPT3.5 embedding achieved success.

Mar. 2023- Aug. 2023

## Deep Graph Mutual Learning for Cross-domain Recommendation

The cold-start problem has always attracted much attention in the field of recommendation systems. By leveraging information from mutil-domains, cold-start problem can be alleviated. Our motivation is that mutual learning strategy can be an efficient method to model the information flow between different domains.

We employed graph neural network to obtain extensive features for the cold-start users and employed mutual learning method to enhance the users' representation in the target domains.

Our project consistently outperformed the baselines. We presented our paper at the 27th International Conference on Database Systems for Advanced Applications
(DASFAA). And extended the work to the journal Expert Systems with Applications.