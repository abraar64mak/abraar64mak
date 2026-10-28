<h1 align="center">Hey, I'm Abraar Khan 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&center=true&vCenter=true&width=700&lines=AI+Engineer+building+agents+that+survive+production;LangGraph+%7C+RAG+%7C+MCP+%7C+Clinical+ML;If+it+isn't+evaluated%2C+it+isn't+done;Open+to+relocate+%E2%80%94+let's+talk" alt="Typing intro" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/abraar-khan-ali/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/abraar64mak?tab=repositories"><img src="https://img.shields.io/badge/All%20Repos-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <img src="https://img.shields.io/badge/Location-Reno%2C%20NV%20(open%20to%20relocate)-2ea44f?style=for-the-badge" />
</p>

---

## 🔭 Right now

I'm an **AI Engineer at CDF** (since Jun 2026), where I built an agreement-screening engine that takes vendor contracts from intake to counsel. Before that I shipped clinical ML at **Aventusoft** and finished my **M.S. in AI Systems at the University of Florida**.

My rule for every project: **if I can't measure it, I don't trust it.** Every project below ships with real numbers, not vibes.

<table align="center">
  <tr>
    <td align="center"><h3>65%</h3>less manual contract triage</td>
    <td align="center"><h3>1,200+</h3>contracts a year automated</td>
    <td align="center"><h3>94%</h3>match with legal review on liability &amp; indemnity flags</td>
    <td align="center"><h3>68% → 1.6%</h3>prompt-injection attack success</td>
  </tr>
</table>

---

## 💼 Experience <sub>(click to expand)</sub>

<details open>
<summary><b>🤖 AI Engineer — CDF</b> · <i>Jun 2026 – Present · Remote</i></summary>
<br>

- Architected a **LangGraph multi-agent pipeline** on FastAPI + PostgreSQL that routes vendor contracts to reviewers
- Automated clause extraction and risk scoring across **1,200+ contracts/year**, cutting manual triage **65%**
- Matched legal review on **94%** of liability and indemnity flags by pairing LLM extraction with rule-based checks
- Designed an **approval gate** that fast-tracks routine agreements and escalates high-risk cases to counsel
- Traced every routing decision with **Arize**, logged for audit, with checkpoints that resume interrupted runs

</details>

<details>
<summary><b>🫀 ML &amp; Data Engineer — Aventusoft</b> · <i>Aug 2025 – May 2026 · Boca Raton, FL</i></summary>
<br>

- Developed **BeatNet**, a clinical ECG tool pairing a **1D U-Net** for PQRST detection with a fine-tuned **ECG-FM** classifier
- Deployed a streaming **PyTorch** inference service for live cardiac diagnosis on wearables
- Improved arrhythmia **F1 +14%** and **AUC +11%** by synthesizing rare-class waveforms to balance training sets
- Enforced **IEC 62304**-compliant CI/CD release gates so every model update stayed audit-ready

</details>

<details>
<summary><b>🔎 AI &amp; Analytics Engineer Intern — Plumb5</b> · <i>Jan 2023 – Apr 2023 · Bengaluru, India</i></summary>
<br>

- Shipped search and retrieval services for a customer-acquisition product serving multi-region enterprise clients
- Cut manual prospect qualification time **30%** with engagement-scoring pipelines
- Raised result precision **12%** with **FAISS** multi-vector reranking
- Validated 10+ ingestion streams with scripted outlier detection

</details>

---

## 🛠️ Things I've built <sub>(click a project for the details)</sub>

<details open>
<summary><b>🗄️ <a href="https://github.com/abraar64mak/MCP-DATA-ASSISTANT">Multi-Agent Data Assistant (MCP)</a></b> — plain English in, safe SQL out</summary>
<br>

Ask your database a question, get an answer plus the exact statement that produced it. The fun part was making it hard to break.

- **75%** execution accuracy
- `sqlglot` **AST firewall** passed **65 adversarial cases**
- Tenant isolation via role-based table access, cost budgets, and row policies
- Every answer shows the executed SQL, per-step timing, and a trace ID

`Python` `MCP` `sqlglot` `PostgreSQL` `RLS`

</details>

<details>
<summary><b>🛡️ <a href="https://github.com/abraar64mak/SecureAI-RAG">SecureAI-RAG</a></b> — prompt-injection red-teaming</summary>
<br>

- **250 poisoned-document attacks** in four families, mapped to the **OWASP LLM Top 10 (2025)**
- Attack success cut from **68.0% → 1.6%** with a four-stage, independently switchable defense stack
- **96.5%** benign utility preserved; rule-based stages add only ~**0.6 ms**
- 16 canary secrets to measure leaks, and an honest **25.7%** residual success against defense-aware adversaries

`Python` `RAG` `Red teaming` `OWASP`

</details>

<details>
<summary><b>📄 <a href="https://github.com/abraar64mak/document-intelligence-platform">Document Intelligence Platform</a></b> — transformer NER at scale</summary>
<br>

- Tuned **RoBERTa** to **0.916 strict entity F1** on 3,453 CoNLL-2003 test samples, with a regression check on every merge
- **PySpark** executors load model weights once; crashed batches are bisected and corrupt files quarantined so runs keep going
- One **FastAPI** endpoint serves up to 32 files per request, returning labels, confidence scores, and character offsets

`RoBERTa` `PySpark` `FastAPI` `Hugging Face`

</details>

<details>
<summary><b>🫀 <a href="https://github.com/abraar64mak/Beatnet">BeatNet</a></b> — ECG wave delineation</summary>
<br>

Finds the start, peak, and end of every P, QRS, and T wave in a heartbeat — the landmarks cardiologists measure by hand. 1D U-Net with a TCN bottleneck, trained on LUDB and PTB-XL, exported to ONNX for faster inference.

`PyTorch` `1D U-Net` `TCN` `ONNX`

</details>

<details>
<summary><b>⚖️ <a href="https://github.com/abraar64mak/Distributed-Code-Judge">Distributed Code Judge</a></b> — LeetCode-style judge</summary>
<br>

Runs untrusted code in isolated containers, with Kafka queuing submissions behind the scenes.

`Docker` `Kafka` `PostgreSQL` `GitHub Actions`

</details>

<details>
<summary><b>🧩 More repos</b></summary>
<br>

| Repo | What it is |
|---|---|
| [Langraph-MCP](https://github.com/abraar64mak/Langraph-MCP) | LangGraph and MCP project |
| [ECG-FUDICIAL-POINT-DETECTION](https://github.com/abraar64mak/ECG-FUDICIAL-POINT-DETECTION) | ECG fiducial point detection |
| [gene-prediction-comparison](https://github.com/abraar64mak/gene-prediction-comparison) | Comparative survey of eukaryotic gene prediction tools |
| [financial-risk-assessment](https://github.com/abraar64mak/financial-risk-assessment) | VaR, stress testing, and portfolio optimization |
| [customer-churn-prediction](https://github.com/abraar64mak/customer-churn-prediction) | Churn ML pipeline and behavioral analysis |

</details>

---

## 🧰 Toolbox <sub>(hover for the tool name)</sub>

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=dotnet&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

**GenAI &amp; Modeling**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat&logo=anthropic&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat&logo=meta&logoColor=white)
![Ragas](https://img.shields.io/badge/Ragas-6E40C9?style=flat)

**Backend &amp; Data**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)

**Cloud, DevOps &amp; Observability**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat&logo=opentelemetry&logoColor=white)
![Arize](https://img.shields.io/badge/Arize-7B3FE4?style=flat)

**Dev tools**
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat&logo=anthropic&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=flat&logo=cursor&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-412991?style=flat&logo=openai&logoColor=white)

---

## 📝 Published work

Two papers, both **Best Paper Award** winners:

- 🏆 **Predicting Fetus Health using CNN** — IConIC 2K23, AIP Conference Proceedings
- 🏆 **Quantifying Exercise Form for Optimal Performance and Injury Prevention** — ICCCNet 2023, Springer LNNS

---

## 🎓 Education

- **University of Florida** — M.S., Artificial Intelligence Systems (Aug 2024 – May 2026)
- **Anna University, India** — Bachelors in Artificial Intelligence &amp; Machine Learning (Jun 2020 – May 2024)

---

## ⚽ Off the clock

Football analytics nerd (pressing stats are my weakness), strength training regular, and occasional tech writer. My exercise-form paper came from that gym habit, so the hobbies do leak into the work.

<p align="center"><i>Open to AI, ML, and data engineering roles. Happy to relocate.</i></p>

<p align="center">
  <a href="https://www.linkedin.com/in/abraar-khan-ali/"><img src="https://img.shields.io/badge/Let's%20connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>
