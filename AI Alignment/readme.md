# AI Alignment and RLHF Notes
Modern language models are powerful, but capability alone is not enough. As these systems are deployed more widely, an important question arises: **how do we build models that behave in ways that are helpful, safe, and aligned with human intentions and values?** This broad challenge is often referred to as **AI alignment**. Researchers across machine learning, HCI, safety, and ethics are actively studying it, including in venues such as the BiAlign workshop, which focuses on human–AI alignment and value-centered AI design. Recent workshop descriptions explicitly highlight themes such as reinforcement learning, human feedback, value specification, human-in-the-loop methods, and scalable post-training alignment. 

One important direction in this space is **Reinforcement Learning from Human Feedback (RLHF)**. In RLHF, human preferences are used to train or guide models toward outputs that better match what people want. This usually involves learning from preference data, building reward models, and then optimising a policy with reinforcement learning. We discuss method like Gradient Policy algorithms like **[REINFORCE](https://cs229.stanford.edu/notes2020fall/notes2020fall/cs229-notes14.pdf)** and **Off-Policy Learning** and  **Proximal Policy Optimization ([Schulman et al., 2017](https://arxiv.org/abs/1707.06347))**  More recently, related methods such as **Direct Preference Optimisation (DPO) ([Rafailov et al., 2023](https://arxiv.org/abs/2305.18290))**  have become important alternatives that aim to align models with human preferences more directly. 

This repository is my personal collection of notes on the mathematical and conceptual foundations behind these ideas. I use it to organise what I learn about language models, reinforcement learning, alignment, and preference-based post-training. Whenever possible, I convert my handwritten notes into clean Overleaf writeups. Otherwise, I also upload the handwritten notes themselves so that the material is still available in full.

This repository contains my notes on language models, AI alignment, reinforcement learning, RLHF, PPO, TRPO, reward modelling, reward hacking, and DPO.

I use this space to collect and organise concepts I find interesting while studying modern language model training and alignment. Whenever possible, I convert my handwritten notes into clean Overleaf documents. Otherwise, I also upload the handwritten notes themselves.

## Contents

- Language Models
- AI Alignment: Core Motivation
- Reinforcement Learning Basics
- Bellman’s Value Function Derivation
- Big Picture: Alignment Pipeline
- Reward Model
- REINFORCE: RLHF with Policy Gradient Optimisation
- Variance Reduction Techniques
- Off-Policy Learning
- Trust Region Policy Optimisation (TRPO)
- Proximal Policy Optimisation (PPO)
- Reward Hacking in RLHF
- Direct Preference Optimisation (DPO)
- Summary: RLHF vs. DPO

## Included in this repository

- Cleaned and typed notes
- Overleaf/LaTeX versions where available
- Handwritten notes
- Mathematical derivations and conceptual summaries

These are personal learning notes meant to make advanced topics in alignment and reinforcement learning easier to follow.

## Related links

- BiAlign workshop: [https://bialign-workshop.github.io/2026](https://bialign-workshop.github.io/2026)
