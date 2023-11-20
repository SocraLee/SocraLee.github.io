---
title: 'PaperReading: ToolDec-Using Finite-State-Machine to Decode'
date: 2023-10-14
permalink: /posts/20231014ToolDec/
tags:
  - LLM
  - NLP
---
# [ToolDec](https://arxiv.org/abs/2310.07075)
Using FSM to enhance augmented LLM.
## Key intuition and motivation: 
the generation of api calls can be explicitly represented using states. By eliminating tokens outside the predefined states vocabulary, we can greatly reduce hallucinations.
Core contribution: beyond a extensible method in augmented LLM, it provides a general method of incorporating domain-knowledge to eliminate hallucinations.

## Future direction: 
In LLM applications (in augmented LLM or biomedical), a core problem is how to incorporate prior knowledge with LLM to avoid mistakes and hallucinations. FSM is good for tool usage, but not transferable for other domains such as biomedical.
Following this research line, the next step could be developing a general method that use prior knowledge to find a high-quality reliable subset of tokens which eliminate hallucinations as much as possible.

For example, use "phrase" (in tool usage, api name is a phrase, in API decode, type and according parameter is somehow a "phrase") to eliminate hallucinations.
