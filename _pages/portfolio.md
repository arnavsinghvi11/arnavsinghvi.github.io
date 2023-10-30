---
layout: archive
title: "Research Projects"
permalink: /research-projects/
author_profile: true
---

## <a href="https://github.com/stanfordnlp/dspy"> DSPy </a>
*Submitted to **ICLR 2024** and currently under review.*  
*Accepted to the **NeurIPS 2023 Workshop R0-FoMo: Robustness of Few-shot and Zero-shot Learning in Large Foundation Models***

<a href="https://github.com/stanfordnlp/dspy">
  ![DSPy Logo](/images/DSPy8.png){:width="200px" height="150px"}
</a>

DSPy is a groundbreaking framework designed to address advanced tasks using language models (LMs) and retrieval models (RMs). With DSPy, programming is emphasized over traditional prompting techniques as you can express any pipeline using clean, Pythonic control flow and incorporate models like GPT-3.5, Llama2, and T5. DSPy introduces a revolutionary perspective that unifies the realms of prompting, finetuning, reasoning, and retrieval augmentation, providing an efficient and effective solution to LM-based task solving. Drawing inspiration from PyTorch, DSPy allows users to declare needed modules alongside their functionality, rather than focusing on implementation details. The DSPy compiler then automatically traces the modularized format, training LMs to execute declarative steps and crafting meticulously designed prompts and finetunes for the LMs. Signatures introduce a declarative specification of input/output behavior for DSPy modules, allowing for intuitive and efficient communication of clear instructions to LMs, while Teleprompters guide the fine-tuning of LMs, learning from demonstrations to generate effective prompts for desired tasks. In essence, DSPy provides an ecosystem that streamlines LM-based task solving from concept to completion, representing a paradigm shift in the landscape of ML and AI.

I've had the great pleasure of working under the mentorship of [Omar Khattab](https://omarkhattab.com/) and the DSPy team at Stanford in bringing the fabulous creation of DSPy to life.

Want to learn more? Check out these resources:

- [arXiv](https://arxiv.org/abs/2310.03714): Explore our paper on arXiv.
- [GitHub](https://github.com/stanfordnlp/dspy): Explore the code and project details on GitHub.
- [Twitter/X Thread](https://twitter.com/lateinteraction/status/1694748401374490946): Follow the discussion and updates on the release thread.


## PORT (in-progress)

<img src="{{ site.baseurl }}/images/port.png" width="600px" height="450px">

PORT (Private Optimal Runtime Training) is a heuristic that accelerates network runtime and optimizes RAM usage for training LLMs on memory-constrained devices by leveraging their unified memory. Stemming from [POET (Private Optimal Energy Training)](https://shishirpatil.github.io/poet/), PORT refines specific layers and frames training as an ILP, enabling dynamic selection of the best accelerator for each network node and leading to substantial runtime enhancements across diverse devices.

I've had the great pleasure of working under the mentorship of [Shishir Patil](https://shishirpatil.github.io/) and the research team at the Sky Lab in UC Berkeley.


## Quadrotor Drone Stability (in-progress)

<img src="{{ site.baseurl }}/images/drone.png" width="400px" height="250px">

This project involves training quadrotor drones to stabilize and reach target positions while simulating under environments where one, two or three propellors experience failure. 

I've had the great pleasure of working under the mentorship of [Zhongyu Li](https://zyliatzju.github.io/) and the research team at the Hybrid Robotics group in UC Berkeley.