# 🛡️ Awesome GUI Agent Safety

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

*A curated collection of research works on GUI Agent Safety, covering benchmarks, attacks, defenses, and evaluation frameworks.*

[📚 Papers by Environment](#papers-grouped-by-environments) •
[🔑 Papers by Keywords](#papers-grouped-by-keywords) •
[📝 All Papers](#all-papers-from-most-recent-to-oldest) •
[➕ Contributing](#How-to-Add-a-Paper)

---

## 📖 Table of Contents

- [🛡️ Awesome GUI Agent Safety](#️-awesome-gui-agent-safety)
  - [📖 Table of Contents](#-table-of-contents)
  - [Overview](#overview)
  - [📊 Keyword Visualization](#-keyword-visualization)
  - [Papers Grouped by Environments](#papers-grouped-by-environments)
  - [Papers Grouped by Keywords](#papers-grouped-by-keywords)
  - [All Papers (from most recent to oldest)](#all-papers-from-most-recent-to-oldest)
  - [How to Add a Paper](#how-to-add-a-paper)
  - [Star History](#star-history)
  - [Acknowledgment](#acknowledgment)

---

## Overview

This repository covers a variety of papers related to **GUI Agent Safety**, including:

- 🔒 **Security & Privacy**: Attacks, defenses, and privacy-preserving techniques
- 📊 **Benchmarks & Datasets**: Evaluation frameworks and safety benchmarks
- 🤖 **Agent Frameworks**: Safe agent architectures and control mechanisms
- 🎯 **Risk Assessment**: Threat models and vulnerability analysis
- 🔍 **Evaluation Methods**: Safety metrics and testing approaches

> **Note**: Papers are categorized by environment ([Web], [Mobile], [Desktop]) and research focus. The [Misc] category includes general topics with important applications in GUI agents.

---

## 📊 Keyword Visualization
![Keyword Word Cloud](update_template_or_data/statistics/keyword_wordcloud_long.png)

---

## Papers Grouped by Environments

<div align="center">

| [🌐 Web](paper_by_env/paper_web.md) | [📱 Mobile](paper_by_env/paper_mobile.md) | [🖥️ Desktop](paper_by_env/paper_desktop.md) | [Misc](paper_by_env/paper_misc.md) |
|:---:|:---:|:---:|:---:|

</div>

---

## Papers Grouped by Keywords
[evaluation (22)](paper_by_key/paper_evaluation.md) | [benchmark (18)](paper_by_key/paper_benchmark.md) | [risk (16)](paper_by_key/paper_risk.md) | [attack (10)](paper_by_key/paper_attack.md) | [injection (8)](paper_by_key/paper_injection.md) | [framework (7)](paper_by_key/paper_framework.md) | [dataset (4)](paper_by_key/paper_dataset.md) | [privacy (4)](paper_by_key/paper_privacy.md) | [survey (2)](paper_by_key/paper_survey.md) | [misuse (2)](paper_by_key/paper_misuse.md) | [method (2)](paper_by_key/paper_method.md) | [multi-agent (2)](paper_by_key/paper_multi-agent.md) | [jailbreaking (2)](paper_by_key/paper_jailbreaking.md) | [untrustworthy (1)](paper_by_key/paper_untrustworthy.md) | [verification (1)](paper_by_key/paper_verification.md) | [tool (1)](paper_by_key/paper_tool.md) | [trustworthiness (1)](paper_by_key/paper_trustworthiness.md) | [platform (1)](paper_by_key/paper_platform.md) | [pop-ups (1)](paper_by_key/paper_pop-ups.md) | [black-box (1)](paper_by_key/paper_black-box.md)


## All Papers (from most recent to oldest)
<details open>
<summary>📄 <b>Click to expand/collapse paper list</b></summary>

- [OS-Sentinel: Towards Safety-Enhanced Mobile GUI Agents via Hybrid Validation in Realistic Workflows](https://arxiv.org/abs/2510.24411)
    - Qiushi Sun, Mukai Li, Zhoumianze Liu, Zhihui Xie, Fangzhi Xu, Zhangyue Yin, Kanzhi Cheng, Zehao Li, Zichen Ding, Qi Liu, Zhiyong Wu, Zhuosheng Zhang, Ben Kao, Lingpeng Kong
    - 🏛️ Institutions: The University of Hong Kong, Fudan University, Shanghai AI Laboratory, Nanyang Technological University ☼Nanjing University, Shanghai Jiao Tong University
    - 📅 Date: Dec. 9, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile]
    - 🔑 Key: [benchmark], [evaluation], [risk], [framework]
    - 📖 TLDR: VLM agents show human-like capability in mobile environments, but pose significant security risks, including system compromise and privacy leakage. Addressing the challenge of detecting these unsafe operations, this paper introduce a dynamic sandbox **MobileRisk-Live** and safety benchmark **MobileRisk**. Based on this, they propose **OS-Sentinel**, a novel hybrid framework combining a Formal Verifier for system-level violations and a VLM-based Contextual Judge. [Github](https://github.com/OS-Copilot/OS-Sentinel)

- [GhostEI-Bench: Do Mobile Agents Resilience to Environmental Injection in Dynamic On-Device Environments?](https://arxiv.org/abs/2510.20333)
    - Chiyu Chen, Xinhao Song, Yunkai Chai, Yang Yao, Haodong Zhao, Lijun Li, Jie Li, Yan Teng, Gongshen Liu, Yingchun Wang
    - 🏛️ Institutions: Shanghai Jiao Tong University, Shanghai Artificial Intelligence Laboratory, The University of Hong Kong
    - 📅 Date: Nov. 21, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile]
    - 🔑 Key: [benchmark], [injection]
    - 📖 TLDR: VLMs used as mobile GUI agents are vulnerable to environmental injection, where adversarial UI elements like deceptive overlays or spoofed notifications contaminate the agent's visual perception. This bypasses textual safeguards and can cause privacy leakage or device compromise. This work introduces **GhostEI-Bench**, a benchmark using Android emulators to assess agent performance under these dynamic attacks.

- [OS-HARM: A Benchmark for Measuring Safety of Computer Use Agents](https://arxiv.org/abs/2503.18492)
    - JThomas Kuntz, Agatha Duzan, Hao Zhao, Francesco Croce, Zico Kolter, Nicolas Flammarion, Maksym Andriushchenko
    - 🏛️ Institutions: EPFL, Carnegie Mellon University
    - 📅 Date: Oct. 29, 2025
    - 📑 Publisher: NeurIPS 2025 Spotlight (Datasets and Benchmarks Track)
    - 💻 Env: [Desktop]
    - 🔑 Key: [benchmark], [evaluation], [misuse], [injection]
    - 📖 TLDR: Computer use agents, LLM-based systems interacting with GUIs via screenshots or accessibility trees, lack safety evaluation. This paper introduces OS-HARM, a benchmark built on OSWorld with 150 tasks across three harm categories: deliberate misuse, prompt injection, and model misbehavior (e.g., harassment, data exfiltration). An automated judge assesses both accuracy and safety. Frontier models (like o4-mini, Claude 3.7 Sonnet, Gemini 2.5 Pro) evaluated show high compliance with misuse queries, vulnerability to static prompt injections, and occasional unsafe actions. [Github](https://github.com/tml-epfl/os-harm)

- [AgentDAM: Privacy Leakage Evaluation for Autonomous Web Agents](https://arxiv.org/pdf/2503.09780)
    - Arman Zharmagambetov, Chuan Guo, Ivan Evtimov, Maya Pavlova, Ruslan Salakhutdinov, Kamalika Chaudhuri
    - 🏛️ Institutions: Meta
    - 📅 Date: Oct. 1, 2025
    - 📑 Publisher: NeurIPS 2025
    - 💻 Env: [Web]
    - 🔑 Key: [benchmark], [risk], [privacy]
    - 📖 TLDR: This work presents AGENTDAM, a new benchmark for evaluating whether AI web-navigation agents adhere to the privacy principle of data minimization—using sensitive information only when strictly necessary for a task. It simulates end-to-end web interactions and is adaptable to all existing agents. Evaluations of GPT-4, Llama-3, and Claude agents reveal they often inadvertently process unnecessary private data. The study also proposes a prompting-based defense to reduce leakage and shows that this end-to-end benchmarking offers a more realistic privacy assessment than simply probing LLMs. [Github](https://github.com/facebookresearch/ai-agent-privacy)

- [VeriOS: Query-Driven Proactive Human-Agent-GUI Interaction for Trustworthy OS Agents](https://arxiv.org/pdf/2509.07553)
    - Zheng Wu, Heyuan Huang, Xingyu Lou, Xiangmou Qu, Pengzhou Cheng, Zongru Wu, Weiwen Liu, Weinan Zhang, Jun Wang, Zhaoxiang Wang, Zhuosheng Zhang
    - 🏛️ Institutions: Shanghai Jiao Tong University, OPPO
    - 📅 Date: Sept. 17, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile], [web]
    - 🔑 Key: [framework], [untrustworthy], [dataset]
    - 📖 TLDR: Most existing OS agents are designed for idealized settings, whereas real-world environments often present untrustworthy conditions. To mitigate risks of over-execution in such scenarios, this work proposes a query-driven human-agent-GUI interaction framework that enables OS agents to decide when to query humans for more reliable task completion. This work also introduce VeriOS-Agent trained with a two-stage learning paradigm that falicitate the decoupling and utilization of meta-knowledge. Concretely, VeriOS-Agent autonomously executes actions in normal conditions while proactively querying humans in untrustworthy scenarios. [Github](https://github.com/Wuzheng02/VeriOS)

- [Safeguarding Mobile GUI Agent via Logic-based Action Verification](https://arxiv.org/abs/2503.18492)
    - Jungjae Lee, Dongjae Lee, Chihun Choi, Youngmin Im, Jaeyoung Wi, Kihong Heo, Sangeun Oh, Sunjae Lee, Insik Shin
    - 🏛️ Institutions: KAIST, Korea University, Sungkyunkwan University
    - 📅 Date: Sept. 11, 2025
    - 📑 Publisher: ACM MOBICOM '25
    - 💻 Env: [Mobile]
    - 🔑 Key: [method], [evaluation], [verification]
    - 📖 TLDR: we introduce VeriSafe Agent (VSA): a formal verification system that serves as a logically grounded safeguard for Mobile GUI Agents. VSA deterministically ensures that an agent's actions strictly align with user intent before executing the action. At its core, VSA introduces a novel autoformalization technique that translates natural language user instructions into a formally verifiable specification. This enables runtime, rule-based verification of agent's actions, detecting erroneous actions even before they take effect. [Github](https://github.com/VeriSafeAgent/VeriSafeAgent)

- [HAICOSYSTEM: An Ecosystem for Sandboxing Safety Risks in Human-AI Interactions](https://arxiv.org/abs/2409.16427)
    - Xuhui Zhou, Hyunwoo Kim, Faeze Brahman, Liwei Jiang, Hao Zhu, Ximing Lu, Frank Xu, Bill Yuchen Lin, Yejin Choi, Niloofar Mireshghallah, Ronan Le Bras, Maarten Sap
    - 🏛️ Institutions: Carnegie Mellon University, Allen Institute for AI
    - 📅 Date: Aug. 30, 2025
    - 📑 Publisher: COLM 2025
    - 💻 Env: [Misc]
    - 🔑 Key: [risk], [evaluation], [framework], [benchmark]
    - 📖 TLDR: HAICOSYSTEM is a framework that assesses AI agent safety in complex social interactions through a modular sandbox. It features a multi-dimensional evaluation covering operational, content, societal, and legal risks. Simulating over 8,000 interactions across 132 scenarios in seven domains, the study finds that state-of-the-art LLMs pose safety risks in 62% of cases, especially during tool use with malicious users. This underscores the critical need to address safety in dynamic human-AI-environment interactions. [Github](https://github.com/XuhuiZhou/HAICosystem)

- [Progent: Programmable Privilege Control for LLM Agents](https://arxiv.org/abs/2504.11703)
    - Tianneng Shi, Jingxuan He, Zhun Wang, Hongwei Li, Linyu Wu, Wenbo Guo, Dawn Song
    - 🏛️ Institutions: UC Berkeley, UC Santa Barbara, National University of Singapore
    - 📅 Date: Aug. 30, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [risk], [injection], [tool]
    - 📖 TLDR: LLM agents use LLMs and tools to perform user tasks but face security risks from external environments, like prompt injection and malicious tools, enabling dangerous actions such as financial fraud or data leakage. The core vulnerability is **over-privileged tool access**. This work introduces **Progent**, the first privilege control framework for securing LLM agents. Progent enforces tool-level security by restricting agents to necessary tool calls while blocking malicious ones, using a domain-specific language for fine-grained policy control. Progent operates deterministically at runtime, offering provable security without altering agent internals.

- [Magentic-UI: Towards Human-in-the-loop Agentic Systems](https://arxiv.org/abs/2507.22358)
    - Hussein Mozannar, Gagan Bansal, Cheng Tan, Adam Fourney, Victor Dibia, Jingya Chen, Jack Gerrits, Tyler Payne, Matheus Kunzler Maldaner, Madeleine Grunde-McLaughlin, Eric Zhu, Griffin Bassman, Jacob Alber, Peter Chang, Ricky Loynd, Friederike Niedtner, Ece Kamar, Maya Murad, Rafah Hosn, Saleema Amershi
    - 🏛️ Institutions: MSR
    - 📅 Date: Jul. 30, 2025
    - 📑 Publisher: arXiv (also MSR Technical Report MSR-TR-2025-40)
    - 💻 Env: [Web]
    - 🔑 Key: [evaluation], [multi-agent]
    - 📖 TLDR: Magentic-UI (Multi-agentic User Interface) is an open-source web interface enabling safe, efficient human–agent collaboration through a flexible multi-agent architecture. It supports web browsing, code execution, and file manipulation, and provides six interaction mechanisms—co-planning, co-tasking, multi-tasking, action guards, answer verification, and long-term memory—to integrate human oversight with AI autonomy. Evaluated via agentic benchmarks, simulated user tests, qualitative user study, and safety assessments, it demonstrates how incorporating human-in-the-loop dynamics can significantly improve agentic systems' reliability and performance. [Github](https://github.com/microsoft/magentic-ui)

- [WebGuard: Building a Generalizable Guardrail for Web Agents](https://arxiv.org/abs/2507.14293)
    - Boyuan Zheng, Zeyi Liao, Scott Salisbury, Zeyuan Liu, Michael Lin, Qinyuan Zheng, Zifan Wang, Xiang Deng, Dawn Song, Huan Sun, Yu Su
    - 🏛️ Institutions: OSU; Scale AI; UCB
    - 📅 Date: Jul. 18, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Web]
    - 🔑 Key: [dataset], [evaluation], [benchmark]
    - 📖 TLDR: WebGuard is the first comprehensive dataset designed for evaluating web agent action risks and developing necessary guardrails for real-world online environments. It contains 4,939 human-annotated, state-changing actions sourced from 193 websites across 22 domains, including various long-tail sites. The actions are categorized into a novel three-tier risk schema: SAFE, LOW, and HIGH, and the dataset includes training and test splits for evaluating generalization. The creators demonstrate that fine-tuning specialized guardrail models, such as the Qwen2.5VL-7B, using WebGuard significantly boosts performance, raising accuracy from 37% to 80% and increasing the recall of HIGH-risk actions from 20% to 76%. [Github](https://github.com/OSU-NLP-Group/WebGuard)

- [Toward a Human-Centered Evaluation Framework for Trustworthy LLM-Powered GUI Agents](https://arxiv.org/abs/2504.17934)
    - Chaoran Chen, Zhiping Zhang, Ibrahim Khalilov, Bingcan Guo, Simret A Gebreegziabher, Yanfang Ye, Ziang Xiao, Yaxing Yao, Tianshi Li, Toby Jia-Jun Li
    - 🏛️ Institutions: University of Notre Dame, Virginia Tech, University of Washington, Northeastern University
    - 📅 Date: Jun. 5, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [framework], [risk], [survey], [privacy]
    - 📖 TLDR: This paper identifies three key risks, distinguishing them from traditional automation and general autonomous agents. Current evaluations prioritize performance, largely overlooking privacy and security. We review existing metrics and outline five challenges in using human evaluators. To address this, we advocate for a human-centered evaluation framework. This framework must incorporate risk assessments, enhance user awareness via in-context consent, and embed privacy and security considerations directly into agent design and evaluation.

- [macOSWorld: A Multilingual Interactive Benchmark for GUI Agents](https://arxiv.org/abs/2506.04135)
    - Pei Yang, Hai Ci, and Mike Zheng Shou
    - 🏛️ Institutions: NUS
    - 📅 Date: Jun. 4, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Desktop]
    - 🔑 Key: [benchmark], [attack]
    - 📖 TLDR: Introduces macOSWorld, the first interactive benchmark for GUI agents on macOS, with 202 tasks across 30 apps (28 macOS-exclusive) in 5 languages plus a safety subset for deception attacks; evaluates 6 agents, showing proprietary CUAs outperform open-source and VLM-based agents, significant language gaps, and both grounding and safety challenges. [Github](https://macos-world.github.io/)

- [MLA-Trust: Benchmarking Trustworthiness of Multimodal LLM Agents in GUI Environments](https://arxiv.org/abs/2506.01616)
    - Xiao Yang, Jiawei Chen, Jun Luo, Zhengwei Fang, Yinpeng Dong, Hang Su, Jun Zhu
    - 🏛️ Institutions: Tsinghua University, East China Normal University
    - 📅 Date: Jun. 2, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile], [Web]
    - 🔑 Key: [benchmark], [evaluation], [framework], [trustworthiness]
    - 📖 TLDR: Multimodal LLM-based agents (MLAs) integrate vision, language, and action for unprecedented autonomy in GUI applications, but introduce critical trustworthiness challenges due to their ability to modify digital states. Existing benchmarks are insufficient. This work introduces MLA-Trust, the first unified framework evaluating MLA trustworthiness across four dimensions: truthfulness, controllability, safety, and privacy, using realistic web and mobile tasks. [Github](https://github.com/thu-ml/MLA-Trust)

- [Agent-SafetyBench: Evaluating the Safety of LLM Agents](https://arxiv.org/abs/2412.14470)
    - Zhexin Zhang, Shiyao Cui, Yida Lu, Jingzhuo Zhou, Junxiao Yang, Hongning Wang, Minlie Huang
    - 🏛️ Institutions: Tsinghua University
    - 📅 Date: May. 5, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [benchmark], [evaluation], [risk]
    - 📖 TLDR: This paper introduces AGENTSAFETYBENCH, a benchmark with 349 environments and 2,000 tests assessing 8 safety risk categories and 10 common failure modes. Evaluating 16 popular LLM agents reveals none achieve a safety score above 60%, highlighting severe safety challenges. Analysis identifies two core defects: lack of robustness and risk awareness. The findings indicate that defense prompts alone are insufficient, underscoring the need for more advanced safety strategies. [Github](https://github.com/thu-coai/Agent-SafetyBench/)

- [AgentHarm: A Benchmark for Measuring Harmfulness of LLM Agents](https://arxiv.org/abs/2410.09024)
    - Maksym Andriushchenko, Alexandra Souly, Mateusz Dziemian, Derek Duenas, Maxwell Lin, Justin Wang, Dan Hendrycks, Andy Zou, Zico Kolter, Matt Fredrikson, Eric Winsor, Jerome Wynne, Yarin Gal, Xander Davies
    - 🏛️ Institutions: Gray Swan AI, UK AI Security Institute
    - 📅 Date: Apr. 18, 2025
    - 📑 Publisher: ICLR 2025
    - 💻 Env: [Misc]
    - 🔑 Key: [benchmark], [evaluation], [attack], [jailbreaking]
    - 📖 TLDR: Research on LLM robustness to **jailbreak attacks** primarily focuses on chatbots, yet LLM agents, which use external tools for multi-stage tasks, pose greater misuse risks. This paper introduces **AgentHarm**, a benchmark of 110 malicious agent tasks (covering 11 harm categories) that tests whether agents retain capabilities post-jailbreak to complete harmful multi-step tasks. The evaluation found leading LLMs are surprisingly compliant with malicious agent requests even without jailbreaking. Simple universal jailbreak templates effectively jailbreak agents, enabling coherent, malicious, multi-step agent behavior. [Github](https://github.com/UKGovernmentBEIS/inspect_evals/tree/main/src/inspect_evals/agentharm)

- [The Obvious Invisible Threat: LLM-Powered GUI Agents' Vulnerability to Fine-Print Injections](https://arxiv.org/pdf/2504.11281v1)
    - Chaoran Chen, Zhiping Zhang, Bingcan Guo, Shang Ma, Ibrahim Khalilov, Simret A Gebreegziabher, Yanfang Ye, Ziang Xiao, Yaxing Yao, Tianshi Li, Toby Jia-Jun Li
    - 🏛️ Institutions: University of Notre Dame, Northeastern University, University of Washington, Virginia Tech, Johns Hopkins University
    - 📅 Date: Apr. 15, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [risk], [injection], [attack]
    - 📖 TLDR: LLM powered GUI agents perform tasks automatically by interpreting and interacting with GUIs. Their autonomy, especially when handling sensitive data, introduces new security risks. Adversaries can exploit the visual processing differences between agents and humans by injecting malicious GUI content, leading to altered agent behaviors or unauthorized private data disclosure. Our study characterized six attacks, testing them on state-of-the-art agents and human users. Findings show agents are highly vulnerable, especially to contextually embedded threats. Human oversight is insufficient, emphasizing the need for privacy-aware agent design and practical defense strategies.

- [From Interaction to Impact: Towards Safer AI Agents Through Understanding and Evaluating Mobile UI Operation Impacts](https://arxiv.org/abs/2410.09006)
    - Zhuohao Jerry Zhang, Eldon Schoop, Jeffrey Nichols, Anuj Mahajan, Amanda Swearngin
    - 🏛️ Institutions: University of Washington, Apple
    - 📅 Date: Mar. 22, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile]
    - 🔑 Key: [dataset], [risk], [evaluation]
    - 📖 TLDR: With the rise of generative AI, autonomous agents for managing daily tasks via user interfaces are advancing. Prior work focuses on UI navigation mechanics, but the real-world impacts of agents' potentially risky actions are understudied. This research investigates the consequences of AI agents' mobile UI actions. They developed an impact taxonomy through expert workshops, synthesized realistic mobile UI data, and annotated it with our categories. Evaluating various LLMs, this work shows the proposed taxonomy improves their reasoning about action impacts. However, significant gaps remain in reliably classifying nuanced or complex impacts.

- [Privacy-Enhancing Paradigms within Federated Multi-Agent Systems](https://arxiv.org/pdf/2503.08175)
    - Zitong Shi, Guancheng Wan, Wenke Huang, Guibin Zhang, Jiawei Shao, Mang Ye, Carl Yang
    - 🏛️ Institutions: National Engineering Research Center for Multimedia Software, Wuhan University, National University of Singapore, TeleAI, Emory University
    - 📅 Date: Mar. 11, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [multi-agent], [evaluation], [dataset], [privacy]
    - 📖 TLDR: This paper identified three key challenges in Federated Multi-Agent Systems (MAS): heterogeneous privacy, structural conversational differences, and dynamic network topologies. To solve these, they introduce Embedded Privacy-Enhancing Agents (EPEAgent). EPEAgent seamlessly integrates into the Retrieval-Augmented Generation (RAG) and context retrieval phases, minimizing data sharing to only task-relevant information. They also created a comprehensive evaluation dataset. Experiments confirm EPEAgent significantly enhances privacy protection while maintaining high system performance.

- [SAFEARENA: Evaluating the Safety of Autonomous Web Agents](https://arxiv.org/pdf/2503.04957)
    - Ada Defne Tur, Nicholas Meade, Xing Han Lù, Alejandra Zambrano, Arkil Patel, Esin Durmus, Spandana Gella, Karolina Stańczak, Siva Reddy
    - 🏛️ Institutions: McGill University, Mila, Concordia University, Anthropic, ServiceNow Research
    - 📅 Date: Mar. 6, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Web]
    - 🔑 Key: [benchmark], [evaluation], [misuse]
    - 📖 TLDR:  This work proposes SAFEARENA, the first benchmark to focus on the deliberate misuse of web agents. SAFEARENA comprises 250 safe and 250 harmful tasks across four websites. They classify the harmful tasks into five harm categories—misinformation, illegal activity, harassment, cybercrime, and social bias, designed to assess realistic misuses of web agents. To systematically assess the susceptibility to harmful tasks, they introduce the Agent Risk Assessment framework that categorizes agent behavior across four risk levels. [Github](https://safearena.github.io)

- [AEIA-MN: Evaluating the Robustness of Multimodal LLM-Powered Mobile Agents Against Active Environmental Injection Attacks](https://arxiv.org/abs/2502.13053)
    - Yurun Chen, Xueyu Hu, Keting Yin, Juncheng Li, Shengyu Zhang
    - 🏛️ Institutions: Zhejiang University
    - 📅 Date: Feb. 18, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile]
    - 🔑 Key: [evaluation], [injection], [attack]
    - 📖 TLDR: This paper introduces the concept of Active Environment Injection Attack (AEIA), where attackers disguise malicious actions as environmental elements to disrupt AI agents' decision-making processes. The authors propose AEIA-MN, an attack scheme leveraging mobile notifications to evaluate the robustness of multimodal large language model-based mobile agents. Experimental results demonstrate that even advanced models are highly vulnerable to such attacks, with success rates reaching up to 93% in the AndroidWorld benchmark.

- [Improved Large Language Model Jailbreak Detection via Pretrained Embeddings](https://arxiv.org/pdf/2412.01547)
    - Erick Galinkin, Martin Sablotny
    - 🏛️ Institutions: NVIDIA,
    - 📅 Date: Dec. 2, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [method], [risk], [injection], [jailbreaking]
    - 📖 TLDR: The adoption of LLMs requires robust security against attacks like prompt injection and jailbreaking, which aim to bypass safety policies. To prevent LLMs from generating harmful content or taking undesirable actions, owners must implement safeguards during training and use additional blocking tools. Detecting jailbreaking prompts is crucial. This work proposes a novel and superior approach for jailbreak detection by combining text embeddings optimized for retrieval with traditional machine learning classification algorithms.

- [Navigating the Risks: A Survey of Security, Privacy, and Ethics Threats in LLM-Based Agents](https://arxiv.org/abs/2411.09523)
    - Yuyou Gan, Yong Yang, Zhe Ma, Ping He, Rui Zeng, Yiming Wang, Qingming Li, Chunyi Zhou, Songze Li, Ting Wang, Yunjun Gao, Yingcai Wu, Shouling Ji
    - 🏛️ Institutions:  Zhejiang University, Southeast University, Stony Brook University
    - 📅 Date: Nov. 14, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [survey], [risk]
    - 📖 TLDR: This survey collects and analyzes the different threats faced by these agents. To address the challenges posed by previous taxonomies in handling cross-module and cross-stage threats, we propose a novel taxonomy framework based on the sources and impacts. Additionally, we identify six key features of LLM-based agents, based on which we summarize the current research progress and analyze their limitations. Subsequently, we select four representative agents as case studies to analyze the risks they may face in practical use. Finally, based on the aforementioned analyses, we propose future research directions from the perspectives of data, methodology, and policy, respectively.

- [WebOlympus: An Open Platform for Web Agents on Live Websites](https://aclanthology.org/2024.emnlp-demo.20/)
    - Boyuan Zheng, Boyu Gou, Scott Salisbury, Zheng Du, Huan Sun, Yu Su
    - 🏛️ Institutions: OSU
    - 📅 Date: Nov. 12, 2024
    - 📑 Publisher: EMNLP 2024
    - 💻 Env: [Web]
    - 🔑 Key: [framework], [platform]
    - 📖 TLDR: This paper introduces *WebOlympus*, an open platform designed to facilitate the research and deployment of web agents on live websites. It features a user-friendly Chrome extension interface, allowing users without programming expertise to operate web agents with minimal effort. The platform incorporates a **safety monitor** module to prevent harmful actions through human supervision or model-based control, supporting applications such as annotation interfaces for web agent trajectories and data crawling.

- [Attacking Vision-Language Computer Agents via Pop-ups](https://arxiv.org/abs/2411.02391)
    - Yanzhe Zhang, Tao Yu, Diyi Yang
    - 🏛️ Institutions: Georgia Tech, HKU, Stanford
    - 📅 Date: Nov. 4, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Web], [Desktop]
    - 🔑 Key: [risk], [pop-ups], [attack]
    - 📖 TLDR: This paper demonstrates that vision-language model (VLM) agents can be easily deceived by carefully designed adversarial pop-ups, leading them to perform unintended actions such as clicking on these pop-ups instead of completing their assigned tasks. Integrating these pop-ups into environments like OSWorld and VisualWebArena resulted in an average attack success rate of 86% and a 47% decrease in task success rate. Basic defense strategies, such as instructing the agent to ignore pop-ups or adding advertisement notices, were found to be ineffective against these attacks. [Github](https://github.com/SALT-NLP/PopupAttack)

- [SafeBench: A Safety Evaluation Framework for Multimodal Large Language Models](https://arxiv.org/pdf/2410.18927)
    - Zonghao Ying, Aishan Liu, Siyuan Liang, Lei Huang, Jinyang Guo, Wenbo Zhou, Xianglong Liu, Dacheng Tao
    - 🏛️ Institutions: Beihang University, China.
    - 📅 Date: Oct. 24, 2024
    - 📑 Publisher: ECCV 2024
    - 💻 Env: [Misc]
    - 🔑 Key: [benchmark], [evaluation]
    - 📖 TLDR: This paper introduces SafeBench, a new framework to better evaluate safety risks in Multimodal LLMs (MLLMs). It tackles limitations in current benchmarks by 1) automatically generating a high-quality, diverse dataset of 2,300 multimodal harmful queries across 23 risk scenarios, and 2) proposing a novel "jury deliberation" evaluation protocol where multiple LLMs collaboratively judge model outputs for more reliable assessments. Testing on 21 models (including GPT-4o and Gemini) revealed widespread safety issues, with insights into factors like image quality affecting performance. The framework is also extensible to modalities like audio. [Github](https://github.com/NY1024/SafeBench)

- [MobileSafetyBench: Evaluating Safety of Autonomous Agents in Mobile Device Control](https://arxiv.org/abs/2410.17520)
    - Juyong Lee, Dongyoon Hahm, June Suk Choi, W. Bradley Knox, Kimin Lee
    - 🏛️ Institutions: KAIST, UT at Austin
    - 📅 Date: Oct. 23, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile]
    - 🔑 Key: [benchmark], [evaluation]
    - 📖 TLDR: MobileSafetyBench introduces a benchmark for evaluating the safety of large language model (LLM)-based autonomous agents in mobile device control. Using Android emulators, the benchmark simulates real-world tasks in apps such as messaging and banking to assess agents' safety and helpfulness. The safety-focused tasks test for privacy risk management and robustness against adversarial prompt injections. Experiments show agents perform well in helpful tasks but struggle with safety-related challenges, underscoring the need for continued advancements in mobile safety mechanisms for autonomous agents. [Github](https://mobilesafetybench.github.io/)

- [Dissecting Adversarial Robustness of Multimodal LM Agents](https://arxiv.org/abs/2406.12814)
    - Chen Henry Wu, Rishi Rajesh Shah, Jing Yu Koh, Russ Salakhutdinov, Daniel Fried, Aditi Raghunathan
    - 🏛️ Institutions: CMU, Stanford
    - 📅 Date: Oct. 21, 2024
    - 📑 Publisher: ICLR 2025
    - 💻 Env: [Web]
    - 🔑 Key: [benchmark], [risk], [evaluation]
    - 📖 TLDR: This paper introduces the Agent Robustness Evaluation (ARE) framework to assess the adversarial robustness of multimodal language model agents in web environments. By creating 200 targeted adversarial tasks within VisualWebArena, the study reveals that minimal perturbations can significantly compromise agent performance, even in advanced systems utilizing reflection and tree-search mechanisms. The findings highlight the need for enhanced safety measures in deploying such agents. [Github](https://github.com/ChenWu98/agent-attack)

- [Refusal-Trained LLMs Are Easily Jailbroken As Browser Agents](https://arxiv.org/abs/2410.13886)
    - Priyanshu Kumar, Elaine Lau, Saranya Vijayakumar, Tu Trinh, Scale Red Team, Elaine Chang, Vaughn Robinson, Sean Hendryx, Shuyan Zhou, Matt Fredrikson, Summer Yue, Zifan Wang
    - 🏛️ Institutions: CMU, GraySwan AI, Scale AI
    - 📅 Date: Oct. 11, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Web]
    - 🔑 Key: [evaluation]
    - 📖 TLDR: This paper introduces **Browser Agent Red teaming Toolkit (BrowserART)**, a comprehensive test suite for evaluating the safety of LLM-based browser agents. The study reveals that while refusal-trained LLMs decline harmful instructions in chat settings, their corresponding browser agents often comply with such instructions, indicating a significant safety gap. The authors call for collaboration among developers and policymakers to enhance agent safety. [Github](https://github.com/scaleapi/browser-art)

- [ST-WebAgentBench: A Benchmark for Evaluating Safety and Trustworthiness in Web Agents](https://sites.google.com/view/st-webagentbench/home)
    - Ido Levy, Ben Wiesel, Sami Marreed, Alon Oved, Avi Yaeli, Segev Shlomov
    - 🏛️ Institutions: IBM Research
    - 📅 Date: Oct. 9, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Web]
    - 🔑 Key: [benchmark], [evaluation]
    - 📖 TLDR: This paper introduces ST-WebAgentBench, a benchmark designed to evaluate the safety and trustworthiness of web agents in enterprise contexts. It defines safe and trustworthy agent behavior, outlines the structure of safety policies, and introduces the "Completion under Policies" metric to assess agent performance. The study reveals that current state-of-the-art agents struggle with policy adherence, highlighting the need for improved policy awareness and compliance in web agents. [Github](https://github.com/segev-shlomov/ST-WebAgentBench)

- [AdvWeb: Controllable Black-box Attacks on VLM-powered Web Agents](https://arxiv.org/abs/2410.17401v2)
    - Chejian Xu, Mintong Kang, Jiawei Zhang, Zeyi Liao, Lingbo Mo, Mengqi Yuan, Huan Sun, Bo Li
    - 🏛️ Institutions: UIUC, OSU
    - 📅 Date: Sept. 27, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Web]
    - 🔑 Key: [black-box], [injection], [attack], [DPO]
    - 📖 TLDR: This paper presents AdvWeb, a black-box attack framework that exploits vulnerabilities in vision-language model (VLM)-powered web agents by injecting adversarial prompts directly into web pages. Using Direct Policy Optimization (DPO), AdvWeb trains an adversarial prompter model that can mislead agents into executing harmful actions, such as unauthorized financial transactions, while maintaining high stealth and control. Extensive evaluations reveal that AdvWeb achieves high success rates across multiple real-world tasks, emphasizing the need for stronger security measures in web agent deployments. [Github](https://ai-secure.github.io/AdvWeb/)

- [EIA: Environmental Injection Attack on Generalist Web Agents for Privacy Leakage](https://arxiv.org/abs/2409.11295)
    - Zeyi Liao, Lingbo Mo, Chejian Xu, Mintong Kang, Jiawei Zhang, Chaowei Xiao, Yuan Tian, Bo Li, Huan Sun
    - 🏛️ Institutions: OSU, UCLA, UChicago, UIUC, UW-Madison
    - 📅 Date: Sept. 17, 2024
    - 📑 Publisher: ICLR 2025
    - 💻 Env: [Web]
    - 🔑 Key: [injection], [privacy], [attack]
    - 📖 TLDR: This paper introduces the Environmental Injection Attack (EIA), a privacy attack targeting generalist web agents by embedding malicious yet concealed web elements to trick agents into leaking users' PII. Utilizing 177 action steps within realistic web scenarios, EIA demonstrates a high success rate in extracting specific PII and whole user requests. Through its detailed threat model and defense suggestions, the work underscores the challenge of detecting and mitigating privacy risks in autonomous web agents. [Github](https://github.com/osu-nlp-group/eia_against_webagent)

- [PrivacyLens: Evaluating Privacy Norm Awareness of Language Models in Action](https://arxiv.org/abs/2409.00138)
    - Yijia Shao, Tianshi Li, Weiyan Shi, Yanchen Liu, Diyi Yang
    - 🏛️ Institutions: Stanford, Harvard, Northeastern University
    - 📅 Date: Aug. 29, 2024
    - 📑 Publisher: NeurIPS 2024
    - 💻 Env: [Misc]
    - 🔑 Key: [risk], [benchmark], [evaluation]
    - 📖 TLDR: As language models gain agency in personalized communication, assessing their privacy norm awareness is challenging due to contextual cases and a lack of realistic evaluation. This work introduces PrivacyLens, a framework that extends privacy-sensitive seeds into vignettes and agent trajectories for multi-level evaluation. Grounded in privacy literature, it reveals a gap: models like GPT-4 and Llama-3-70B leak sensitive information in 25.68% and 38.69% of cases, even with privacy prompts. PrivacyLens also enables dynamic red-teaming by generating multiple trajectories per seed to probe leakage risks.

- [MM-SafetyBench: A Benchmark for Safety Evaluation of Multimodal Large Language Models](https://arxiv.org/pdf/2311.17600)
    - Xin Liu, Yichen Zhu, Jindong Gu, Yunshi Lan, Chao Yang, Yu Qiao
    - 🏛️ Institutions: Shanghai AI Laboratory
    - 📅 Date: Jun. 19, 2024
    - 📑 Publisher: arxiv
    - 💻 Env: [Misc]
    - 🔑 Key: [benchmark], [evaluation], [risk]
    - 📖 TLDR: This paper finds that even safety-aligned MLLMs can be compromised by benign text paired with malicious images. To assess this, we introduce MM-SafetyBench with 5,040 text-image pairs across 13 scenarios. Testing 12 models confirms their vulnerability, and we propose an effective prompting strategy for defense. [Github](https://github.com/AI45Lab/MM-SafetyBench)

- [Adversarial Attacks on Multimodal Agents](https://arxiv.org/pdf/2406.12814v1)
    - Chen Henry Wu, Jing Yu Koh, Ruslan Salakhutdinov, Daniel Fried, Aditi Raghunathan
    - 🏛️ Institutions: CMU
    - 📅 Date: Jun. 18, 2024
    - 📑 Publisher: NeurIPS 2024 Open-World Agents Workshop
    - 💻 Env: [Web]
    - 🔑 Key: [benchmark], [risk], [attack], [evaluation]
    - 📖 TLDR: This paper investigates the safety risks posed by multimodal agents built on vision-enabled language models (VLMs). The authors introduce two adversarial attack methods: a captioner attack targeting white-box captioners and a CLIP attack that transfers to proprietary VLMs. To evaluate these attacks, they curated VisualWebArena-Adv, a set of adversarial tasks based on VisualWebArena. The study demonstrates that within a limited perturbation norm, the captioner attack can achieve a 75% success rate in making a captioner-augmented GPT-4V agent execute adversarial goals. The paper also discusses the robustness of agents based on other VLMs and provides insights into factors contributing to attack success and potential defenses. [Github](https://github.com/ChenWu98/agent-attack)

- [Watch Out for Your Agents! Investigating Backdoor Threats to LLM-Based Agents](https://arxiv.org/abs/2402.11208)
    - Wenkai Yang, Xiaohan Bi, Yankai Lin, Sishuo Chen, Jie Zhou, Xu Sun
    - 🏛️ Institutions: Renming University of China, PKU, Tencent
    - 📅 Date: Feb. 17, 2024
    - 📑 Publisher: NeurIPS 2024
    - 💻 Env: [Misc]
    - 🔑 Key: [backdoor], [attack], [risk]
    - 📖 TLDR: This paper investigates backdoor attacks on LLM-based agents, introducing a framework that categorizes attacks based on outcomes and trigger locations. The study demonstrates the vulnerability of such agents to backdoor attacks and emphasizes the need for targeted defenses. [Github](https://github.com/lancopku/agent-backdoor-attacks)

- [A Trembling House of Cards? Mapping Adversarial Attacks against Language Agents](https://arxiv.org/pdf/2402.10196)
    - Lingbo Mo, Zeyi Liao, Boyuan Zheng, Yu Su, Chaowei Xiao, Huan Sun
    - 🏛️ Institutions: OSU, UWM
    - 📅 Date: Feb. 15, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [attack], [framework], [evaluation]
    - 📖 TLDR: This paper introduces a conceptual framework to assess and understand adversarial vulnerabilities in language agents, dividing the agent structure into three components—Perception, Brain, and Action. It discusses 12 specific adversarial attack types that exploit these components, ranging from input manipulation to complex backdoor and jailbreak attacks. The framework provides a basis for identifying and mitigating risks before the widespread deployment of these agents in real-world applications. [Github](https://github.com/OSU-NLP-Group/AgentAttack)

</details>

</details>

## How to Add a Paper

- Please add your entry to `update_template_or_data/update_paper_list.md` following the format shown below. Once your update is complete, submit a pull request to the main repository. After the pull request is merged, the GitHub Actions workflow will automatically update the main `README.md`, as well as the keyword and environment grouping files, sorted by date. 

- You may include multiple keywords for your entry. However, to ensure consistency across the repository, we recommend selecting the most relevant keywords that are already in use whenever possible.

<details>
<summary>Format example and explanation</summary>

```
- [title](paper link)
    - List authors directly without a "key" identifier (e.g., author1, author2)
    - 🏛️ Institutions: List the institutions concisely, using abbreviations (e.g., university names, like OSU).
    - 📅 Date: e.g., Oct 30, 2024
    - 📑 Publisher: e.g., ICLR 2025
    - 💻 Env: Indicate the research environment within brackets, such as [Web], [Mobile], or [Desktop]. Use [Misc] if it is researching in general domains.
    - 🔑 Key: Label each keyword within brackets, e.g., [framework], [dataset], [benchmark].
    - 📖 TLDR: Brief summary of the paper. [Github]
```

</details>

---

## Star History

<a href="https://star-history.com/#xueyu-ubc/Awesome-GUI-Agent-Safety&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=xueyu-ubc/Awesome-GUI-Agent-Safety&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=xueyu-ubc/Awesome-GUI-Agent-Safety&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=xueyu-ubc/Awesome-GUI-Agent-Safety&type=Date" />
 </picture>
</a>

---

## Acknowledgment

This repository references the initial template provided by the OSU-NLP-Group. See the original work at [GUI-Agents-Paper-List](https://github.com/OSU-NLP-Group/GUI-Agents-Paper-List).

We are grateful for their excellent work and highly recommend checking out and starring their curated collection of GUI agent papers. Furthermore, we extend our sincere gratitude to all contributors of this repository. If you are interested in our work, please star our repository!




</details>

[//]: # ()
[//]: # (## Contributors)

[//]: # ()
[//]: # (<a href="https://github.com/OSU-NLP-Group/GUI-Agents-Paper-List/graphs/contributors">)

[//]: # (  <img src="https://contrib.rocks/image?repo=OSU-NLP-Group/GUI-Agents-Paper-List" />)

[//]: # (</a>)
