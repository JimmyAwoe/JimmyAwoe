

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

* 🔭 &nbsp; **Currently Researching:** Efficient and Effective LLM Pretraining & Fine-Tuning Method.


## 🛠️ Tech Stack & Expertise

| Area | Technologies / Skills |
| :--- | :--- |
| **Deep Learning** | Efficient Pre-training and Fine-tuning of Large Language Models |
| **Programming** | Python |
| **Frameworks** | Megatron-LM, transformers |

---

## 🔬 Featured Research Projects

These are my key contributions to the field of efficient LLM training.
<!--
### GROUTER: Preemptive Routing for Stable and Efficient Mixture-of-Experts Training
* **Core Problem:** Systematically identified and provided a theoretical analysis of **Structure-Performance Interference (SPI)**—the inherent instability and optimization error accumulation caused by dynamic routing decisions in MoE training.
* **Innovation:** Proposed **GROUTER**, the first preemptive routing framework designed to *eliminate* SPI. We employ **Knowledge Distillation (KD)** to extract a high-quality, stable routing prior from a well-converged source model, injecting it as a fixed, near-optimal router into the target model.
* **Methodology:** Engineered two novel, complementary strategies for structural migration: **Expert Folding** and **Expert Tuning**.
* **Impact & Results:** Accelerated pre-training data utilization by **4.28x** and achieved up to **33.5% training throughput acceleration**.
-->
### An Efficient Subspace Algorithm for Federated Learning on Heterogeneous Data
* **Core Problem:** Addressed the dual challenge in Federated Learning: severe communication bottlenecks and detrimental client drift caused by Non-IID data.
* **Innovation:** Developed **FedSub**, an efficient subspace federated optimization algorithm that fundamentally enhances communication efficiency and convergence stability.
* **Technical Breakthroughs:** Utilized low-dimensional projection for model update compression (O(md) $\to$ O(rd)) and introduced a **dual variable correction mechanism** to mitigate client drift.
* **Validation:** Achieved comparable convergence accuracy to full-dimension methods at a **50% compression rate**, demonstrating superior convergence speed over established baselines.
* **Implementation** The algorithm has been adapted within my FedSub repository. This repository not only details how to reproduce the main experiments but also includes a packaged implementation of the algorithm. You can refer to the Readme.md to learn how to apply the FedSub algorithm to your own training tasks.

### PackTron: Efficient Sentence Packing for Large Language Model Training

* **Core Problem:** Addressed the dual challenge in LLM data loading: severe padding waste (up to 30-50% of tokens) in `datasets.load_dataset` and the complexity barrier of Megatron-LM's excellent but heavyweight data processing framework.
* **Innovation:** Developed **PackTron**, a lightweight, plug-and-play data loader that extracts Megatron-LM's proven sentence packing architecture into a simple, easy-to-use Python package.
* **Technical Breakthroughs:** Implemented intelligent sentence packing that eliminates padding entirely (100% token utilization), binary storage format with memory-mapped I/O for fast random access, and C++-accelerated indexing for efficient sample construction. Automatic multi-GPU data distribution and epoch management ensure seamless distributed training.
* **Validation:** Achieved **zero padding waste** with 100% token utilization, enabling accurate token counting and maximum training efficiency. The library provides a drop-in replacement for `datasets.load_dataset` while maintaining Megatron-LM's production-grade performance.
* **Implementation:** The library has been packaged as a standard Python package. This repository includes complete documentation, examples, and a simple API that makes Megatron-LM's efficient data processing accessible to the broader ML community. You can refer to the README.md to learn how to integrate PackTron into your training pipeline.



---

