---
layout: archive
title: "Research Projects"
permalink: /research-projects/
author_profile: true
---

## <a href="https://github.com/stanfordnlp/dspy"> DSPy </a>
*Accepted to the **NeurIPS 2023 Workshop R0-FoMo: Robustness of Few-shot and Zero-shot Learning in Large Foundation Models***
*Submitted to **ICLR 2024** and currently under review.*  

<a href="https://github.com/stanfordnlp/dspy">
  ![DSPy Logo](/images/DSPy8.png){:width="200px" height="150px"}
</a>

DSPy is a groundbreaking framework designed to address advanced tasks using language models (LMs) and retrieval models (RMs). With DSPy, programming is emphasized over traditional prompting techniques as you can express any pipeline using clean, Pythonic control flow and incorporate models like GPT-3.5, Llama2, and T5. DSPy introduces a revolutionary perspective that unifies prompting, finetuning, reasoning, and retrieval augmentation, providing a comprehensive solution to LM-based task solving. Drawing inspiration from PyTorch, DSPy allows users to declare needed modules alongside their functionality, rather than focusing on implementation details. The DSPy compiler then automatically traces the modularized format, training LMs to execute declarative steps with optimized prompts for the LMs. Signatures allow for this declarative specification of input/output behavior in  DSPy modules, allowing for intuitive communication of clear instructions to LMs, while Teleprompters optimize the performance of LMs, learning from demonstrations to generate effective prompts for desired tasks. In essence, DSPy provides a novel framework that streamlines LM-based task solving from concept to completion, representing a paradigm shift in language model prompting.

I've had the great pleasure of working under the mentorship of [Omar Khattab](https://omarkhattab.com/) and the DSPy team at Stanford in bringing DSPy to life.

Want to learn more? Check out these resources:

- [arXiv](https://arxiv.org/abs/2310.03714): Explore our paper on arXiv.
- [GitHub](https://github.com/stanfordnlp/dspy): Explore the code and project details on GitHub.
- [Twitter/X Thread](https://twitter.com/lateinteraction/status/1694748401374490946): Follow the discussion and updates on the release thread.


## PORT (in-progress)

<img src="{{ site.baseurl }}/images/PORT_unified_memory.PNG" width="600px" height="450px">

PORT (Private Optimal Runtime Training) is a solver framework that optimizes network runtime and optimizes RAM usage for training models on memory-constrained devices. By leveraging unified memory of device accelerators, PORT refines network layers and frames training as an ILP, enabling dynamic selection of the best accelerator for each network node and leading to substantial runtime enhancements across diverse devices.

I've had the great pleasure of working under the mentorship of [Shishir Patil](https://shishirpatil.github.io/) and the research team at the Sky Lab in UC Berkeley.


## Quadrotor Drone Stability (in-progress)

<img src="{{ site.baseurl }}/images/drone.png" width="400px" height="250px">

This project involves training quadrotor drones to stabilize and reach target positions while simulating under environments where one, two or three propellors experience failure. 

I've had the great pleasure of working under the mentorship of [Zhongyu Li](https://zyliatzju.github.io/) and the research team at the Hybrid Robotics group in UC Berkeley.