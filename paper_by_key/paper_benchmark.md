# Papers with Keyword: benchmark

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

- [HAICOSYSTEM: An Ecosystem for Sandboxing Safety Risks in Human-AI Interactions](https://arxiv.org/abs/2409.16427)
    - Xuhui Zhou, Hyunwoo Kim, Faeze Brahman, Liwei Jiang, Hao Zhu, Ximing Lu, Frank Xu, Bill Yuchen Lin, Yejin Choi, Niloofar Mireshghallah, Ronan Le Bras, Maarten Sap
    - 🏛️ Institutions: Carnegie Mellon University, Allen Institute for AI
    - 📅 Date: Aug. 30, 2025
    - 📑 Publisher: COLM 2025
    - 💻 Env: [Misc]
    - 🔑 Key: [risk], [evaluation], [framework], [benchmark]
    - 📖 TLDR: HAICOSYSTEM is a framework that assesses AI agent safety in complex social interactions through a modular sandbox. It features a multi-dimensional evaluation covering operational, content, societal, and legal risks. Simulating over 8,000 interactions across 132 scenarios in seven domains, the study finds that state-of-the-art LLMs pose safety risks in 62% of cases, especially during tool use with malicious users. This underscores the critical need to address safety in dynamic human-AI-environment interactions. [Github](https://github.com/XuhuiZhou/HAICosystem)

- [WebGuard: Building a Generalizable Guardrail for Web Agents](https://arxiv.org/abs/2507.14293)
    - Boyuan Zheng, Zeyi Liao, Scott Salisbury, Zeyuan Liu, Michael Lin, Qinyuan Zheng, Zifan Wang, Xiang Deng, Dawn Song, Huan Sun, Yu Su
    - 🏛️ Institutions: OSU; Scale AI; UCB
    - 📅 Date: Jul. 18, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Web]
    - 🔑 Key: [dataset], [evaluation], [benchmark]
    - 📖 TLDR: WebGuard is the first comprehensive dataset designed for evaluating web agent action risks and developing necessary guardrails for real-world online environments. It contains 4,939 human-annotated, state-changing actions sourced from 193 websites across 22 domains, including various long-tail sites. The actions are categorized into a novel three-tier risk schema: SAFE, LOW, and HIGH, and the dataset includes training and test splits for evaluating generalization. The creators demonstrate that fine-tuning specialized guardrail models, such as the Qwen2.5VL-7B, using WebGuard significantly boosts performance, raising accuracy from 37% to 80% and increasing the recall of HIGH-risk actions from 20% to 76%. [Github](https://github.com/OSU-NLP-Group/WebGuard)

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

- [SAFEARENA: Evaluating the Safety of Autonomous Web Agents](https://arxiv.org/pdf/2503.04957)
    - Ada Defne Tur, Nicholas Meade, Xing Han Lù, Alejandra Zambrano, Arkil Patel, Esin Durmus, Spandana Gella, Karolina Stańczak, Siva Reddy
    - 🏛️ Institutions: McGill University, Mila, Concordia University, Anthropic, ServiceNow Research
    - 📅 Date: Mar. 6, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Web]
    - 🔑 Key: [benchmark], [evaluation], [misuse]
    - 📖 TLDR:  This work proposes SAFEARENA, the first benchmark to focus on the deliberate misuse of web agents. SAFEARENA comprises 250 safe and 250 harmful tasks across four websites. They classify the harmful tasks into five harm categories—misinformation, illegal activity, harassment, cybercrime, and social bias, designed to assess realistic misuses of web agents. To systematically assess the susceptibility to harmful tasks, they introduce the Agent Risk Assessment framework that categorizes agent behavior across four risk levels. [Github](https://safearena.github.io)

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

- [ST-WebAgentBench: A Benchmark for Evaluating Safety and Trustworthiness in Web Agents](https://sites.google.com/view/st-webagentbench/home)
    - Ido Levy, Ben Wiesel, Sami Marreed, Alon Oved, Avi Yaeli, Segev Shlomov
    - 🏛️ Institutions: IBM Research
    - 📅 Date: Oct. 9, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Web]
    - 🔑 Key: [benchmark], [evaluation]
    - 📖 TLDR: This paper introduces ST-WebAgentBench, a benchmark designed to evaluate the safety and trustworthiness of web agents in enterprise contexts. It defines safe and trustworthy agent behavior, outlines the structure of safety policies, and introduces the "Completion under Policies" metric to assess agent performance. The study reveals that current state-of-the-art agents struggle with policy adherence, highlighting the need for improved policy awareness and compliance in web agents. [Github](https://github.com/segev-shlomov/ST-WebAgentBench)

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

- [Introducing v0.5 of the AI Safety Benchmark from MLCommons](https://arxiv.org/abs/2404.12241)
    -  MLCommons AI Safety Working Group (WG)
    - 🏛️ Institutions:  MLCommons AI Safety Working Group (WG), et al.
    - 📅 Date: May. 13 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile]
    - 🔑 Key: [benchmark], [evaluation], [AI-Safety], [AI-systems]
    - 📖 TLDR: This paper introduces v0.5 of the AI Safety Benchmark, which has been created by the MLCommons AI Safety Working Group. The AI Safety Benchmark has been designed to assess the safety risks of AI systems that use chat-tuned language models. We introduce a principled approach to specifying and constructing the benchmark, which for v0.5 covers only a single use case (an adult chatting to a general-purpose assistant in English), and a limited set of personas (i.e., typical users, malicious users, and vulnerable users). We created a new taxonomy of 13 hazard categories, of which 7 have tests in the v0.5 benchmark. This release of v0.5 of the AI Safety Benchmark includes (1) a principled approach to specifying and constructing the benchmark, which comprises use cases, types of systems under test (SUTs), language and context, personas, tests, and test items; (2) a taxonomy of 13 hazard categories with definitions and subcategories; (3) tests for seven of the hazard categories, each comprising a unique set of test items, i.e., prompts. There are 43,090 test items in total, which we created with templates; (4) a grading system for AI systems against the benchmark; (5) an openly available platform, and downloadable tool, called ModelBench that can be used to evaluate the safety of AI systems on the benchmark; (6) an example evaluation report which benchmarks the performance of over a dozen openly available chat-tuned language models; (7) a test specification for the benchmark.
