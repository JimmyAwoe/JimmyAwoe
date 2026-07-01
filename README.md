

<!--
## Hi there 👋
**JimmyAwoe/JimmyAwoe** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
<img src="https://{{Your-Image-Link-Here-Optional-e.g.-GitHub-Avatar}}" width="150" alt="Profile Picture"/>

## 🔥 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username={{Your-GitHub-Username}}&show_icons=true&theme=vue-dark&hide_border=true&count_private=true" alt="Your GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username={{Your-GitHub-Username}}&layout=compact&theme=vue-dark&hide_border=true" alt="Your Top Languages" />
</p>

---
-->
<div align="center">
  
  <h1>👋 Hello there! I'm JimmyAwoe </h1>
  <p>
 Enthusiast in AI
  </p>  
  
  [![GitHub total stars](https://img.shields.io/github/stars/JimmyAwoe?style=social)](https://github.com/JimmyAwoe)
  [![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:xuyq@stu.pku.edu.cn)

  ---
</div>

## 💡 About Me

I am a second-year Master's student at Peking University.

* 🔭 &nbsp; **Currently Researching:** Efficient LLM Training & MLLM Reasoning


## 🛠️ Tech Stack & Expertise

| Area | Technologies / Skills |
| :--- | :--- |
| **Deep Learning** | Efficient Pre-training and Fine-tuning of Large Language Models |
| **Programming** | Python |
| **Frameworks** | Megatron-LM, transformers |

---

## 🔬 Featured Research Projects

These are my key contributions to the field of efficient LLM training.

### GROUTER: Preemptive Routing for Stable and Efficient Mixture-of-Experts Training
* **Core Problem:** Addressed the core bottleneck of MoE training: the entanglement of routing structure learning and representation optimization, which leads to slow convergence, training instability and high runtime overhead.
* **Innovation:** Developed Grouter, a preemptive routing framework that distills stable routing priors from fully trained MoE models, decoupling routing from representation to fundamentally accelerate MoE pre-training.
* **Technical Breakthroughs:** Lightweight distillation architecture, Expert Folding & Tuning for cross-configuration transfer, and offline pre-routing optimization to eliminate dynamic routing overhead.
* **Validation:** Delivered 4.28× pre-training data efficiency improvement and up to 33.5% training throughput acceleration, with consistent superiority over SOTA baselines across diverse MoE setups.
* **Implementation:** Full open-source implementation with pre-trained weights, Megatron-LM integration, and one-click reproduction scripts are provided in this repository.

### PackTron: Efficient Data Loader for Large Language Model Training

* **Core Problem:** Addressed the dual challenge in LLM data loading: severe padding waste (up to 30-50% of tokens) in `datasets.load_dataset` and the complexity barrier of Megatron-LM's excellent but heavyweight data processing framework.
* **Innovation:** Developed **PackTron**, a lightweight, plug-and-play data loader that extracts Megatron-LM's proven sentence packing architecture into a simple, easy-to-use Python package.
* **Technical Breakthroughs:** Implemented intelligent sentence packing that eliminates padding entirely (100% token utilization), binary storage format with memory-mapped I/O for fast random access, and C++-accelerated indexing for efficient sample construction. Automatic multi-GPU data distribution and epoch management ensure seamless distributed training.
* **Validation:** Achieved **zero padding waste** with 100% token utilization, enabling accurate token counting and maximum training efficiency. The library provides a drop-in replacement for `datasets.load_dataset` while maintaining Megatron-LM's production-grade performance.
* **Implementation:** The library has been packaged as a standard Python package. This repository includes complete documentation, examples, and a simple API that makes Megatron-LM's efficient data processing accessible to the broader ML community. You can refer to the README.md to learn how to integrate PackTron into your training pipeline.



---

