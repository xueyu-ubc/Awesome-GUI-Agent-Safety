# Papers with Keyword: risk

- [OS-Sentinel: Towards Safety-Enhanced Mobile GUI Agents via Hybrid Validation in Realistic Workflows](https://arxiv.org/abs/2510.24411)
    - Qiushi Sun, Mukai Li, Zhoumianze Liu, Zhihui Xie, Fangzhi Xu, Zhangyue Yin, Kanzhi Cheng, Zehao Li, Zichen Ding, Qi Liu, Zhiyong Wu, Zhuosheng Zhang, Ben Kao, Lingpeng Kong
    - 🏛️ Institutions: The University of Hong Kong, Fudan University, Shanghai AI Laboratory, Nanyang Technological University ☼Nanjing University, Shanghai Jiao Tong University
    - 📅 Date: Dec. 9, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile]
    - 🔑 Key: [benchmark], [evaluation], [risk], [framework]
    - 📖 TLDR: VLM agents show human-like capability in mobile environments, but pose significant security risks, including system compromise and privacy leakage. Addressing the challenge of detecting these unsafe operations, this paper introduce a dynamic sandbox **MobileRisk-Live** and safety benchmark **MobileRisk**. Based on this, they propose **OS-Sentinel**, a novel hybrid framework combining a Formal Verifier for system-level violations and a VLM-based Contextual Judge. [Github](https://github.com/OS-Copilot/OS-Sentinel)

- [AgentDAM: Privacy Leakage Evaluation for Autonomous Web Agents](https://arxiv.org/pdf/2503.09780)
    - Arman Zharmagambetov, Chuan Guo, Ivan Evtimov, Maya Pavlova, Ruslan Salakhutdinov, Kamalika Chaudhuri
    - 🏛️ Institutions: Meta
    - 📅 Date: Oct. 1, 2025
    - 📑 Publisher: NeurIPS 2025
    - 💻 Env: [Web]
    - 🔑 Key: [benchmark], [risk], [privacy]
    - 📖 TLDR: This work presents AGENTDAM, a new benchmark for evaluating whether AI web-navigation agents adhere to the privacy principle of data minimization—using sensitive information only when strictly necessary for a task. It simulates end-to-end web interactions and is adaptable to all existing agents. Evaluations of GPT-4, Llama-3, and Claude agents reveal they often inadvertently process unnecessary private data. The study also proposes a prompting-based defense to reduce leakage and shows that this end-to-end benchmarking offers a more realistic privacy assessment than simply probing LLMs. [Github](https://github.com/facebookresearch/ai-agent-privacy)

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

- [Attacking Vision-Language Computer Agents via Pop-ups](https://arxiv.org/abs/2411.02391)
    - Yanzhe Zhang, Tao Yu, Diyi Yang
    - 🏛️ Institutions: Georgia Tech, HKU, Stanford
    - 📅 Date: Nov. 4, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Web], [Desktop]
    - 🔑 Key: [risk], [pop-ups], [attack]
    - 📖 TLDR: This paper demonstrates that vision-language model (VLM) agents can be easily deceived by carefully designed adversarial pop-ups, leading them to perform unintended actions such as clicking on these pop-ups instead of completing their assigned tasks. Integrating these pop-ups into environments like OSWorld and VisualWebArena resulted in an average attack success rate of 86% and a 47% decrease in task success rate. Basic defense strategies, such as instructing the agent to ignore pop-ups or adding advertisement notices, were found to be ineffective against these attacks. [Github](https://github.com/SALT-NLP/PopupAttack)

- [Dissecting Adversarial Robustness of Multimodal LM Agents](https://arxiv.org/abs/2406.12814)
    - Chen Henry Wu, Rishi Rajesh Shah, Jing Yu Koh, Russ Salakhutdinov, Daniel Fried, Aditi Raghunathan
    - 🏛️ Institutions: CMU, Stanford
    - 📅 Date: Oct. 21, 2024
    - 📑 Publisher: ICLR 2025
    - 💻 Env: [Web]
    - 🔑 Key: [benchmark], [risk], [evaluation]
    - 📖 TLDR: This paper introduces the Agent Robustness Evaluation (ARE) framework to assess the adversarial robustness of multimodal language model agents in web environments. By creating 200 targeted adversarial tasks within VisualWebArena, the study reveals that minimal perturbations can significantly compromise agent performance, even in advanced systems utilizing reflection and tree-search mechanisms. The findings highlight the need for enhanced safety measures in deploying such agents. [Github](https://github.com/ChenWu98/agent-attack)

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
