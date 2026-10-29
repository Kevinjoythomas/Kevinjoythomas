<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img alt="Kevin Joy Thomas, AI engineer" src="assets/header-light.svg" width="100%">
</picture>

[Resume](https://drive.google.com/file/d/1lCiF9b8M5p-fDf6Ri24wTQ1jVWCUmWJn/view) · [LinkedIn](https://www.linkedin.com/in/kevin-joy-thomas/) · [LeetCode](https://leetcode.com/u/kevinjoythomas7/) · [Hugging Face](https://huggingface.co/kevinjoythomas) · kevinjoythomas2004@gmail.com

I build LLM systems that have to be right, not just fluent: extraction pipelines that read engineering documents into structured specs, agents that research with citations, a medical assistant with a safety gate in front of the model. I spend as much time on the evaluation as on the system, because that is how you find out it was wrong before a user does.

## Experience

| | Role | Where | When |
|---|---|---|---|
| **DeepMechanix** | Founding AI Engineer | San Jose, remote | May 2026 to present |
| **United Field Services** | AI Specialist, contract | Los Angeles, remote | Oct 2025 to present |
| **Google** | Software Engineering Intern, Workspace Search | Bangalore | Jun to Aug 2025 |
| **Moksa.AI** | Machine Learning Intern | Hyderabad | Feb to May 2025 |
| **Envideo Technologies** | Founding AI Engineer (Intern) | Remote | Feb 2024 to Mar 2025 |

At DeepMechanix: a document-intelligence pipeline that turns engineering packages into cited design specs (93.1% of checked fields correct vs 74.7% for GPT-5.5 alone on held-out vessels), the agentic extraction layer behind it, and a multi-agent research engine that stores every claim with a quote, source URL and confidence band. At UFS: an inbound voice agent on Claude Haiku 4.5 and Deepgram, a vendor-matching ranker measured on 800 held-out jobs (Hit@10 20.1% to 34.1%), and a daily lead pipeline across all 50 US states. At Google: a third-party client search server migrated from Java to an internal C++ framework.

## Research

| | | |
|---|---|---|
| **Saying "See a Doctor" Is Not Triage** | Sole author, under review | A keyword safety rubric rated a QLoRA-fine-tuned Llama 3 8B 6.7x safer on emergencies while blinded judges found no change; rubric-judge agreement fell from Cohen's kappa 0.61 to 0.03, replicated on 273 physician-labeled HealthBench conversations. |
| **OpenHealth triage gate** | First author, in preparation | A pre-generation gate (40 red-flag rules plus a zero-shot Gemma 3 4B check) that catches 92% of emergencies at 92% specificity, 2.9 s per message on a 4 GB laptop GPU. |

## Selected work

| Repository | What it is |
|---|---|
| [OpenHealth](https://github.com/Kevinjoythomas/OpenHealth) | Private medical assistant: QLoRA-fine-tuned Llama 3 8B, hybrid keyword and semantic retrieval over clinical guidelines with citations, five services on Docker Compose. Measured: retrieval about 0.1 s warm, 4.2 s per answer on a T4. |
| [asme-rag-harness](https://github.com/Kevinjoythomas/asme-rag-harness) | Clause-level retrieval evaluation over an engineering code, with abstention and a citation graph. |
| [Kubernetes-Store-Provisioning-Platform](https://github.com/Kevinjoythomas/Kubernetes-Store-Provisioning-Platform) | A Kubernetes operator that provisions isolated store environments: Helm, network policies, resource quotas. |
| [Network-Security-Pipeline](https://github.com/Kevinjoythomas/Network-Security-Pipeline) | MLOps pipeline for phishing-site detection: schema and drift checks, MLflow tracking, a FastAPI service, Docker image shipped to AWS by CI. |
| [Person-Reidentification-System](https://github.com/Kevinjoythomas/Person-Reidentification-System) | Cross-camera person re-identification API on torchreid embeddings, served with Flask. |
| [Unattended-Baggage-Detection](https://github.com/Kevinjoythomas/Unattended-Baggage-Detection) | Flags unattended bags in video by tracking people and bags with YOLOv8 and Deep SORT. |

## Recognition

- 89th of 74,829 participants, Amazon ML Challenge 2024
- 8th place, HackXcelerate 2024, a national hackathon held with Microsoft, Hyderabad
- LeetCode: 759 problems solved, contest rating 1,758, top 10.4%

## Toolkit

Python, C++, C · PyTorch, QLoRA, LangChain, Ollama, sentence-transformers, OpenVINO, YOLO · FastAPI, Flask, PostgreSQL, Redis, RabbitMQ, React · Docker, GitHub Actions, AWS

<sub>B.E. in Information Technology, Maturi Venkata Subba Rao (MVSR) Engineering College, Hyderabad, 2022 to 2026.</sub>
