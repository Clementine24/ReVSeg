# ReVSeg: Incentivizing the Reasoning Chain for Video Segmentation with Reinforcement Learning

<div align="center">

![Teaser Image](./asset/teaser.png)

[**Project Page**](https://clementine24.github.io/ReVSeg/) | [**arXiv Paper**](#) | [**Code**](https://github.com/Clementine24/ReVSeg)

**📢 #**

</div>

## Abstract

Reasoning-centric video object segmentation is an inherently complex task: the query often refers to dynamics, causality, and temporal interactions, rather than static appearances. Yet existing solutions generally collapse these factors into simplified reasoning with latent embeddings, rendering the reasoning chain opaque and essentially intractable. 
We therefore adopt an explicit decomposition perspective and introduce **ReVSeg**, which executes reasoning as sequential decisions in the native interface of pretrained vision language models (VLMs). Rather than folding all reasoning into a single-step prediction, **ReVSeg** executes three explicit operations -- semantics interpretation, temporal evidence selection, and spatial grounding -- aligning pretrained capabilities.
We further employ reinforcement learning to optimize the multi-step reasoning chain, enabling the model to self-refine its decision quality from outcome-driven signals. Experimental results demonstrate that **ReVSeg** attains state-of-the-art performances on standard video object segmentation benchmarks and yields interpretable reasoning trajectories.

## Method Overview

![Framework](./asset/framework.png)

**ReVSeg** runs a two-turn reasoning chain over the input video and query.

### Key Features

- 🧠 **Explicit Reasoning Chain**: Decomposes complex reasoning into interpretable sequential decisions
- 🎯 **Reinforcement Learning**: Optimizes reasoning quality through outcome-driven signals
- 📊 **State-of-the-Art Performance**: Achieves top results on video object segmentation benchmarks
- 🔍 **Interpretable Trajectories**: Provides transparent reasoning process visualization

### Example Cases
![qualitative cases](./asset/case_study_2samples.png)



## Citation

If you find our work useful, please consider citing:

```bibtex
@article{#,
  title={ReVSeg: Incentivizing the Reasoning Chain for Video Segmentation with Reinforcement Learning},
  author={Li, Yifan and Yin, Yingda and Zhu, Lingting and Chen, Weikai and Qian, Shengju and Wang, Xin and Fu, Yanwei},
  journal={#},
  year={2025}
}
```

<div align="center">

**✨ Code will be released soon. Stay tuned for updates!**

</div>