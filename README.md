
# CrowdMoGen: Zero-Shot Text-Driven Collective Motion Generation

[Xinying Guo](https://gxyes.github.io/), [Mingyuan Zhang](https://mingyuan-zhang.github.io/), [Haozhe Xie](https://www.infinitescript.com/), [Chenyang Gu](https://www.linkedin.com/in/rheallyc/), [Ziwei Liu](https://liuziwei7.github.io/)

S-Lab, Nanyang Technological University

[![arXiv](https://img.shields.io/badge/arXiv-2407.06188-D8383A.svg)](https://arxiv.org/abs/2407.06188)
![visitors](https://visitor-badge.laobi.icu/badge?page_id=gxyes.CrowdMoGen)
[![page](https://img.shields.io/badge/homepage-A1A9D0.svg?logo=Google%20Home&logoColor=white&)](https://gxyes.github.io/projects/CrowdMoGen.html)
[![demo](https://img.shields.io/badge/demo-C497B2.svg?logo=YouTube&logoColor=white)](https://youtu.be/R7Q2Qw5eDVQ)

---

<div align="center"><img src="imgs/teaser.png" width="60%"/></div>

> **Abstract:** <i>Collective Motion Generation</i> is essential in entertainment industries such as animation and games as well as in strategic fields like urban simulation and planning.
> This new task requires an intricate integration of control and generation to realistically synthesize crowd dynamics under specific spatial and semantic constraints, whose challenges are yet to be fully explored.
> On the one hand, existing human motion generation models typically focus on individual behaviors, neglecting the complexities of collective behaviors.
> On the other hand, recent methods for multi-person motion generation depend heavily on pre-defined scenarios and are limited to a fixed, small number of inter-person interactions, thus hampering their practicality.
> To overcome these challenges, we introduce <strong>CrowdMoGen</strong>, a zero-shot text-driven framework that harnesses the power of Large Language Model (LLM) to incorporate the collective intelligence into the motion generation framework as guidance, thereby enabling generalizable planning and generation of crowd motions without paired training data.

<div align="center"><img src="imgs/method.png" width="80%"/></div>

> **Pipeline Overview:**
> <strong>CrowdMoGen</strong> is a novel two-stage, zero-shot framework for <i>Crowd Motion Generation</i>, which separates motion decision-making from motion generation into two distinct tasks:
> <br><strong>1) Crowd Scene Planner</strong> uses a Large Language Model (LLM) to interpret and decide on crowd movements based on user scenarios, giving our method zero-shot capabilities.
> It provides detailed semantic attributes (like action categories) and spatial attributes (like trajectories and interactions) for each individual, managing both overall crowd dynamics and individual interactions.
> <br><strong>2) Collective Motion Generator</strong> enhances the realism of generated motions and ensures strict adherence to control signals through joint-wise <strong>InputMixing</strong>, customized <strong>ControlAttention</strong> mechanisms, and carefully designed training objectives.

## Updates 🔥

- [2024/07/01] Code is coming soon.

## Citation 📝

```
```
