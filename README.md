# Feedback-Tuning Language Models (Reading List)

**Topics: Reward Modeling (RM), Reinforcement Learning with Human Feedback (RLHF), Preference Modeling (PM)**

Learning from human feedback is about asking humans what they want and optimizing for that.

This document is for sharing papers relevant to “feedback-tuning” language models.



# Relevant Papers

### Reinforcement Learning with Human Feedback (**RLHF**)

These are methods/experiments on learning with human feedback, **<span style="text-decoration:underline;">with</span> reinforcement learning**.

* [Deep reinforcement learning from human preferences](https://arxiv.org/abs/1706.03741) (Christiano et al., 2017) (Preliminary Reading)
* [Fine-Tuning Language Models from Human Preferences](https://arxiv.org/abs/1909.08593) (Zeigler et al. 2019) 
    * Code: [https://github.com/openai/lm-human-preferences](https://github.com/openai/lm-human-preferences)
* [Learning to summarize from human feedback](https://arxiv.org/abs/2009.01325) (Steinnon et al., 2020)
    * Code:[ https://github.com/openai/summarize-from-feedback](https://github.com/openai/summarize-from-feedback)
* [**Feedback-Tree** Recursively Summarizing Books with Human Feedback](https://arxiv.org/abs/2109.10862) (Wu et al., 2021)
* [**WebGPT**: Browser-assisted question-answering with human feedback](https://arxiv.org/abs/2112.09332) (Nakano et al., 2021) 
* [**InstructGPT** Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155) (Ouyang et al., 2022) 
* [**HHH** A General Language Assistant as a Laboratory for Alignment](https://arxiv.org/abs/2112.00861) (Askell et al., 2021)
* [**HH** Training a Helpful and Harmless Assistant with Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2204.05862) \
(Bai et al., 2022)
    * Data: [https://github.com/anthropics/hh-rlhf](https://github.com/anthropics/hh-rlhf)
* [**GopherCite** Teaching language models to support answers with verified quotes](https://arxiv.org/abs/2203.11147) (Menick et al., 2022)
* [**Sparrow** Improving alignment of dialogue agents via targeted human judgements](https://storage.googleapis.com/deepmind-media/DeepMind.com/Authors-Notes/sparrow/sparrow-final.pdf) (Glaese et al, Sept 2022)
* [**ILQL** Offline RL for Natural Language Generation with Implicit Language Q Learning](https://arxiv.org/abs/2206.11871)** (Snell et al. 2022)
    * Presentation: [Charlie Snell ILQL, 29.July.2022](https://www.youtube.com/watch?v=fGq4np3brbs)


### Fine-tuning with Human Feedback (**FTHF**)

These are methods of learning with human feedback, **<span style="text-decoration:underline;">without</span> reinforcement learning**.

* [**REFINEMENT-WITH-FEEDBACK** Training Language Models with Natural Language Feedback](https://arxiv.org/abs/2204.14146) (Scheurer et al., 2022)
* [**FLAN** Fine-Tuned Language Models are Zero-Shot Learners](https://openreview.net/pdf?id=gEZrGCozdqR) (Wei et al., 2022)
    * Fine-tuning with instructions (Possibly relevant? Probably not)


### Transformers for Reinforcement Learning (**TRL**)

Miscellaneous papers on reinforcement learning techniques designed around Transformer based architectures.

* [**Decision Transformer**: Reinforcement Learning via Sequence Modeling](https://arxiv.org/abs/2106.01345) (Chen et al., 2021)
    * Code: [https://github.com/kzl/decision-transformer](https://github.com/kzl/decision-transformer)
    * See also: [**Trajectory Transformer** Offline Reinforcement Learning as One Big Sequence Modeling Problem](https://arxiv.org/abs/2106.02039) (Janner et al., 2021)
* [**Prompting Decision Transformer** for Few-Shot Policy Generalization](https://arxiv.org/abs/2206.13499) (Xu et al., 2022)
    * Code: [https://github.com/mxu34/prompt-dt](https://github.com/mxu34/prompt-dt)
* [**TransDreamer**: Reinforcement Learning with Transformer World Models](https://arxiv.org/abs/2202.09481) (Chen et al., 2022)


### Reinforcement Learning Algorithms

Common reinforcement learning algorithms used in “feedback-tuning” language models.  \

* [CMU 10-73 Deep Reinforcement Learning (Fall 2020)](https://cmudeeprl.github.io/703website_f20/)
* [**PPO** Proximal Policy Optimization](https://arxiv.org/abs/1707.06347) (Schulman et al., 2017)
    * Code: [baselines/ppo2.py at master](https://github.com/openai/baselines/blob/master/baselines/ppo2/ppo2.py)
    * General Policy Gradient Algorithms: [Policy Gradient Algorithms | Lil'Log](https://lilianweng.github.io/posts/2018-04-08-policy-gradient/)
* [Implementation Matters in Deep Policy Gradients: A Case Study on PPO and TRPO](https://arxiv.org/abs/2005.12729)
    * [The 37 Implementation Details of Proximal Policy Optimization · The ICLR Blog Track](https://iclr-blog-track.github.io/2022/03/25/ppo-implementation-details/)
* [**IQL** Offline Reinforcement Learning with Implicit Q-Learning](https://arxiv.org/abs/2110.06169) (Kostrikov et al., 2021)

---
