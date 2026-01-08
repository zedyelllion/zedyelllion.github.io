---
title: "Projects"
permalink: /projects/
author_profile: true
---


## 🧠 Research Projects
### 🔹 LLM Collaboration With Multi-Agent Reinforcement Learning
Keywords: Dec-POMDP · CTDE-inspired training · MAGRPO · Multi-turn LLM collaboration

Formalized multi-LLM collaboration as a cooperative Dec-POMDP: each agent observes partial, prompt-based information and outputs natural-language actions; the system/reward model provides joint rewards over multi-turn interactions 

Introduced MAGRPO, extending GRPO to multi-agent, multi-turn settings by sampling groups of joint rollouts and using group-relative Monte-Carlo advantages to coordinate agents without training a large centralized value model 

Evaluated on two collaboration domains:

Writing: 2 Qwen agents learn complementary roles (concise TLDR + detailed summary; background + method/experiments for arXiv-style expansion), improving structure/style coherence vs. prompt-level baselines 

Coding: 2 Qwen coder agents generate a helper + main function; rewards include structure/syntax/tests and an explicit cooperation bonus when main correctly uses helper; introduced CoopHumanEval to reduce non-cooperative noise in HumanEval 

Empirically, MAGRPO outperforms single-model and prompt-only multi-agent baselines in overall return and cooperation metrics, especially in multi-turn coding with external feedback signals

---

### 🔹 YUSE: Symbolic Testing for Floating-Point Programs
**Keywords:** Symbolic Execution · Floating-Point Errors · Software Testing  

- Developed techniques for detecting **floating-point inconsistencies and corner-case bugs**
- Focused on numerical instability, path explosion, and solver scalability
- Contributed to modeling, testing, and evaluation components of the framework
- This project strengthened my interest in **robust and reliable systems**

---

### 🔹 Parallel Computing on RTEMS (Paor Project)
**Keywords:** Parallelism · Embedded Systems · Performance Optimization  

- Worked on system-level parallel computation in real-time operating systems
- Designed and evaluated parallel strategies under strict timing constraints
- Gained experience bridging **systems research** with **algorithmic design**

---
