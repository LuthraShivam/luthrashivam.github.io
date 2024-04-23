---
title: Langchain Tutorial for fun and profit - Part 1
#date: 2024-14-21 17:30:00
categories: [Generative AI]
tags: [AI, Python, Langchain, OpenAI]
---

### Disclaimer

I don't advertise myself as an expert in Generative AI or MLOps (yet). While I'm trying to keep the content of this blog post accurate and adhering to AI best practices, there may be events where I make my share of mistakes. 

In the meantime, please sit back and enjoy as I toil away at learning Langchain and the wonderful world of AI :)

## What is Langchain?

AI - some love it, some hate it, some wanna figure out how we can churn out the next billion(s) dollar startup using it, and some want to generate cat pictures on demand (a cat wearing a mage hat casting a lightning bolt on a hippo riding a unicycle - yep, it give you this).

Any pivotal technology such as Generative AI needs tools that either help it integrate with existing systems, or build entirely new systems using it. Langchain could be one of them.

## Chains in Langchain

Gen AI has a pattern that will be familiar to anyone that has used a ChatGPT(or any other AI Model) prompt, namely being the following:

```
Input ---> AI model ---> Output
```

There are several other moving parts going on behind the curtains, but if we simplify an interaction with an AI model, it gets decomposed to something listed above.

