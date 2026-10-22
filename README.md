# Can Zhang · 张灿

**Multimodal Learning · Video Understanding · Video Agents**

> **Seeking PhD opportunities for Fall 2027.** I am interested in multimodal learning, efficient video understanding, and evidence-grounded agents. I also welcome research collaborations and related research internship opportunities.

I am a master's student in Computer Technology at **Beijing University of Chemical Technology**, with expected graduation in 2027. My research spans robust vision-language adaptation, efficient temporal representations, and retrieval-based video agents.

A question connecting my work is: **How can multimodal systems select, retain, and verify the right temporal evidence under limited computation?**

📬 [alexlessend@gmail.com](mailto:alexlessend@gmail.com) · [GitHub](https://github.com/aub123)

## Recent Video Research

### RESUME: Recurrent State Updates from Motion and Residual Signals for Efficient Video Language Modeling
**Can Zhang**, Xiaotian Han, Junyuan Shang, Yuchen Ding, Zhenyu Zhang, Shuohuan Wang, Dianhai Yu, Ruirui Li<br>
**arXiv preprint, 2026** · [Paper](https://arxiv.org/abs/2609.39563)

RESUME models video as an evolving compact state: an anchor I-frame initializes the state, while motion and residual signals update it over time. A shared readout connects the state trajectory to video-language modeling.

### From Intent to Evidence: Policy-Steered Multi-Strategy Retrieval for Long-Video Agents
**Can Zhang**, Baofeng Zhang, Xiaotian Han, Junyuan Shang, Yuchen Ding, Shuohuan Wang, Dianhai Yu, Ruirui Li<br>
**arXiv preprint, 2026** · [Paper](https://arxiv.org/abs/2608.31005)

VESTA is a training-free long-video agent that routes questions to focused, recall, or contrastive retrieval. Its acquire–verify–consolidate loop maintains a temporal evidence ledger to track provenance, coverage, and conflicting evidence.

## Selected Peer-Reviewed Publications

- **AIM: Augmentation-Invariant Memory for Robust Open-set Test-Time Adaptation**<br>
  **Can Zhang**, Yunfeng Liu, Ye Wang, Ruirui Li. **IJCNN 2026**. [Paper](https://doi.org/10.1109/IJCNN69854.2026.11729088)
- **Multi-Cache Enhanced Prototype Learning for Test-Time Generalization of Vision-Language Models**<br>
  Xinyu Chen, Haotian Zhai, **Can Zhang**, Xiupeng Shi, Ruirui Li. **ICCV 2025**. [Paper](https://openaccess.thecvf.com/content/ICCV2025/html/Chen_Multi-Cache_Enhanced_Prototype_Learning_for_Test-Time_Generalization_of_Vision-Language_Models_ICCV_2025_paper.html)
- **Mitigating Cache Noise in Test-Time Adaptation for Large Vision-Language Models**<br>
  Haotian Zhai, Xinyu Chen, **Can Zhang**, Tianming Sha, Ruirui Li. **ICME 2025**. [Paper](https://doi.org/10.1109/ICME59968.2025.11209257)
- **Double-Shrink: Enhancing Model Robustness under SDN Noise by Reducing Uncertain Confidence**<br>
  Naihao Wang, **Can Zhang**, Yunfeng Liu, Wentao Chen, Ruirui Li. **ICME 2025**. [Paper](https://doi.org/10.1109/ICME59968.2025.11209463)

## Research Questions I Want to Explore

- **Memory that knows what is missing.** How can a video agent represent uncertainty, detect gaps in temporal coverage, and decide when to retrieve more evidence?
- **Video representations under a compute budget.** Can motion, residual signals, and event structure guide when to update a compact state and when to revisit visual tokens?
- **Evidence-sensitive reasoning.** How should an agent revise an answer when retrieved clips conflict, and how can evaluations measure whether its answer is supported by the video?

These are directions I hope to investigate during my PhD and through future collaborations.

## Research and Engineering Experience

My research internships at **Baidu** and the **China Telecom Artificial Intelligence Research Institute** have involved video agents, multimodal training, data pipelines, and distributed training systems.

**Tools I have worked with:** Python, PyTorch, verl, Megatron, MS-Swift, and distributed training workflows.

If your group works on video-language models, multimodal memory, efficient inference, or reliable agents, I would be happy to discuss potential research fit for **Fall 2027**.
