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

**What I'm building right now**

- At DeepMechanix, document AI for engineering: pipelines and agents that read drawings and datasheets into structured specs, with a citation behind every value, and a research engine that never states a number without its source.
- At UFS, a phone agent that takes contractor and client calls, and a daily pipeline that finds and verifies leads across all 50 states.
- On the side, a medical assistant with a safety gate in front of the model, and a paper on why the usual safety check stops working after fine-tuning.

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
