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

- [MLA-Trust: Benchmarking Trustworthiness of Multimodal LLM Agents in GUI Environments](https://arxiv.org/abs/2506.01616)
    - Xiao Yang, Jiawei Chen, Jun Luo, Zhengwei Fang, Yinpeng Dong, Hang Su, Jun Zhu
    - 🏛️ Institutions: Tsinghua University, East China Normal University
    - 📅 Date: Jun. 2, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile], [Web]
    - 🔑 Key: [benchmark], [evaluation], [framework], [trustworthiness]
    - 📖 TLDR: Multimodal LLM-based agents (MLAs) integrate vision, language, and action for unprecedented autonomy in GUI applications, but introduce critical trustworthiness challenges due to their ability to modify digital states. Existing benchmarks are insufficient. This work introduces MLA-Trust, the first unified framework evaluating MLA trustworthiness across four dimensions: truthfulness, controllability, safety, and privacy, using realistic web and mobile tasks. [Github](https://github.com/thu-ml/MLA-Trust)

- [From Interaction to Impact: Towards Safer AI Agents Through Understanding and Evaluating Mobile UI Operation Impacts](https://arxiv.org/abs/2410.09006)
    - Zhuohao Jerry Zhang, Eldon Schoop, Jeffrey Nichols, Anuj Mahajan, Amanda Swearngin
    - 🏛️ Institutions: University of Washington, Apple
    - 📅 Date: Mar. 22, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile]
    - 🔑 Key: [dataset], [risk], [evaluation]
    - 📖 TLDR: With the rise of generative AI, autonomous agents for managing daily tasks via user interfaces are advancing. Prior work focuses on UI navigation mechanics, but the real-world impacts of agents' potentially risky actions are understudied. This research investigates the consequences of AI agents' mobile UI actions. They developed an impact taxonomy through expert workshops, synthesized realistic mobile UI data, and annotated it with our categories. Evaluating various LLMs, this work shows the proposed taxonomy improves their reasoning about action impacts. However, significant gaps remain in reliably classifying nuanced or complex impacts.

- [AEIA-MN: Evaluating the Robustness of Multimodal LLM-Powered Mobile Agents Against Active Environmental Injection Attacks](https://arxiv.org/abs/2502.13053)
    - Yurun Chen, Xueyu Hu, Keting Yin, Juncheng Li, Shengyu Zhang
    - 🏛️ Institutions: Zhejiang University
    - 📅 Date: Feb. 18, 2025
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile]
    - 🔑 Key: [evaluation], [injection], [attack]
    - 📖 TLDR: This paper introduces the concept of Active Environment Injection Attack (AEIA), where attackers disguise malicious actions as environmental elements to disrupt AI agents' decision-making processes. The authors propose AEIA-MN, an attack scheme leveraging mobile notifications to evaluate the robustness of multimodal large language model-based mobile agents. Experimental results demonstrate that even advanced models are highly vulnerable to such attacks, with success rates reaching up to 93% in the AndroidWorld benchmark.

- [MobileSafetyBench: Evaluating Safety of Autonomous Agents in Mobile Device Control](https://arxiv.org/abs/2410.17520)
    - Juyong Lee, Dongyoon Hahm, June Suk Choi, W. Bradley Knox, Kimin Lee
    - 🏛️ Institutions: KAIST, UT at Austin
    - 📅 Date: Oct. 23, 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile]
    - 🔑 Key: [benchmark], [evaluation]
    - 📖 TLDR: MobileSafetyBench introduces a benchmark for evaluating the safety of large language model (LLM)-based autonomous agents in mobile device control. Using Android emulators, the benchmark simulates real-world tasks in apps such as messaging and banking to assess agents' safety and helpfulness. The safety-focused tasks test for privacy risk management and robustness against adversarial prompt injections. Experiments show agents perform well in helpful tasks but struggle with safety-related challenges, underscoring the need for continued advancements in mobile safety mechanisms for autonomous agents. [Github](https://mobilesafetybench.github.io/)

- [Introducing v0.5 of the AI Safety Benchmark from MLCommons](https://arxiv.org/abs/2404.12241)
    -  MLCommons AI Safety Working Group (WG)
    - 🏛️ Institutions:  MLCommons AI Safety Working Group (WG), et al.
    - 📅 Date: May. 13 2024
    - 📑 Publisher: arXiv
    - 💻 Env: [Mobile]
    - 🔑 Key: [benchmark], [evaluation], [AI-Safety], [AI-systems]
    - 📖 TLDR: This paper introduces v0.5 of the AI Safety Benchmark, which has been created by the MLCommons AI Safety Working Group. The AI Safety Benchmark has been designed to assess the safety risks of AI systems that use chat-tuned language models. We introduce a principled approach to specifying and constructing the benchmark, which for v0.5 covers only a single use case (an adult chatting to a general-purpose assistant in English), and a limited set of personas (i.e., typical users, malicious users, and vulnerable users). We created a new taxonomy of 13 hazard categories, of which 7 have tests in the v0.5 benchmark. This release of v0.5 of the AI Safety Benchmark includes (1) a principled approach to specifying and constructing the benchmark, which comprises use cases, types of systems under test (SUTs), language and context, personas, tests, and test items; (2) a taxonomy of 13 hazard categories with definitions and subcategories; (3) tests for seven of the hazard categories, each comprising a unique set of test items, i.e., prompts. There are 43,090 test items in total, which we created with templates; (4) a grading system for AI systems against the benchmark; (5) an openly available platform, and downloadable tool, called ModelBench that can be used to evaluate the safety of AI systems on the benchmark; (6) an example evaluation report which benchmarks the performance of over a dozen openly available chat-tuned language models; (7) a test specification for the benchmark.
