- [Qwen3Guard Technical Report](https://arxiv.org/pdf/2510.14276)
    -  Qwen Team
    - 🏛️ Institutions:  Qwen Team
    - 📅 Date: Oct. 16, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [benchmark], [evaluation], [AI-Safety], [Model]
    - 📖 TLDR: Existing LLM safety classifiers are limited by binary labels and delayed detection. We introduce Qwen3Guard, a multilingual safety model series featuring: (1) Generative Qwen3Guard for fine‑grained tri‑class classification (safe/controversial/unsafe). (2) Stream Qwen3Guard for real‑time, token‑level monitoring during streaming generation.

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

- [Toward a Human-Centered Evaluation Framework for Trustworthy LLM-Powered GUI Agents](https://arxiv.org/abs/2504.17934)
    - Chaoran Chen, Zhiping Zhang, Ibrahim Khalilov, Bingcan Guo, Simret A Gebreegziabher, Yanfang Ye, Ziang Xiao, Yaxing Yao, Tianshi Li, Toby Jia-Jun Li
    - 🏛️ Institutions: University of Notre Dame, Virginia Tech, University of Washington, Northeastern University
    - 📅 Date: Jun. 5, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [framework], [risk], [survey], [privacy]
    - 📖 TLDR: This paper identifies three key risks, distinguishing them from traditional automation and general autonomous agents. Current evaluations prioritize performance, largely overlooking privacy and security. We review existing metrics and outline five challenges in using human evaluators. To address this, we advocate for a human-centered evaluation framework. This framework must incorporate risk assessments, enhance user awareness via in-context consent, and embed privacy and security considerations directly into agent design and evaluation.

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

- [Privacy-Enhancing Paradigms within Federated Multi-Agent Systems](https://arxiv.org/pdf/2503.08175)
    - Zitong Shi, Guancheng Wan, Wenke Huang, Guibin Zhang, Jiawei Shao, Mang Ye, Carl Yang
    - 🏛️ Institutions: National Engineering Research Center for Multimedia Software, Wuhan University, National University of Singapore, TeleAI, Emory University
    - 📅 Date: Mar. 11, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [multi-agent], [evaluation], [dataset], [privacy]
    - 📖 TLDR: This paper identified three key challenges in Federated Multi-Agent Systems (MAS): heterogeneous privacy, structural conversational differences, and dynamic network topologies. To solve these, they introduce Embedded Privacy-Enhancing Agents (EPEAgent). EPEAgent seamlessly integrates into the Retrieval-Augmented Generation (RAG) and context retrieval phases, minimizing data sharing to only task-relevant information. They also created a comprehensive evaluation dataset. Experiments confirm EPEAgent significantly enhances privacy protection while maintaining high system performance.

- [AEGIS2.0: A Diverse AI Safety Dataset and Risks Taxonomy for Alignment of LLM Guardrails](https://arxiv.org/pdf/2501.09004)
    -  Shaona Ghosh, Prasoon Varshney, Makesh Narsimhan Sreedhar, Aishwarya Padmakumar, Traian Rebedea, Jibin Rajan Varghese, Christopher Parisien
    - 🏛️ Institutions:  Nvidia
    - 📅 Date: Jan. 15, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [dataset], [evaluation], [AI-Safety]
    - 📖 TLDR: To address the lack of high-quality, commercially usable safety datasets for LLMs, we created Aegis 2.0. This dataset features a novel, fine-grained taxonomy (12 main hazard categories, 9 subcategories) for classifying risks. It contains over 34,000 human-LLM interactions, annotated via a hybrid human+LLM jury pipeline. Crucially, lightweight models fine-tuned on Aegis 2.0 match the performance of models trained on much larger, non-commercial datasets. We also introduce a safety+topic training blend that improves model adaptability to new risks. All data and models will be open-sourced to advance LLM safety research.

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

- [SafeBench: A Safety Evaluation Framework for Multimodal Large Language Models](https://arxiv.org/pdf/2410.18927)
    - Zonghao Ying, Aishan Liu, Siyuan Liang, Lei Huang, Jinyang Guo, Wenbo Zhou, Xianglong Liu, Dacheng Tao
    - 🏛️ Institutions: Beihang University, China.
    - 📅 Date: Oct. 24, 2024
    - 📑 Publisher: ECCV 2024
    - 💻 Env: [Misc]
    - 🔑 Key: [benchmark], [evaluation]
    - 📖 TLDR: This paper introduces SafeBench, a new framework to better evaluate safety risks in Multimodal LLMs (MLLMs). It tackles limitations in current benchmarks by 1) automatically generating a high-quality, diverse dataset of 2,300 multimodal harmful queries across 23 risk scenarios, and 2) proposing a novel "jury deliberation" evaluation protocol where multiple LLMs collaboratively judge model outputs for more reliable assessments. Testing on 21 models (including GPT-4o and Gemini) revealed widespread safety issues, with insights into factors like image quality affecting performance. The framework is also extensible to modalities like audio. [Github](https://github.com/NY1024/SafeBench)

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

- [Introducing v0.5 of the AI Safety Benchmark from MLCommons](https://arxiv.org/abs/2404.12241)
    -  MLCommons AI Safety Working Group (WG)
    - 🏛️ Institutions:  MLCommons AI Safety Working Group (WG), et al.
    - 📅 Date: May. 13, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Misc]
    - 🔑 Key: [benchmark], [evaluation], [AI-Safety], [AI-systems]
    - 📖 TLDR: This paper presents v0.5 of the AI Safety Benchmark by the MLCommons AI Safety Working Group, designed to evaluate safety risks of chat-tuned AI systems. Version 0.5 covers a single English chat use case with typical, malicious, and vulnerable personas. It introduces 13 hazard categories, with tests for seven, totaling 43,090 prompts. The release includes benchmark specifications, a grading system, the ModelBench evaluation platform, an example report, and documentation of limitations. Version 1.0, planned for late 2024, will offer broader safety insights.

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
