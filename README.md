<div align="center">

# Moneeb Ur Rahman

### ML for Digital Twins · Reinforcement Learning · LLM Agents

Computer Science @ NUST (SEECS) · Researcher on **S2Cool**, a £2.8M UKRI project on low-energy cooling

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/moneeb-ur-rahman)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:moneeburrahman07@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=moneeb07&style=for-the-badge&color=2ea44f&label=Profile+Views)](https://github.com/moneeb07)

</div>

---

```
moneeb07@github
------------------------
OS: Linux, Windows
Shell: bash
Host: National University of Sciences & Technology (NUST), SEECS
Location: Islamabad, Pakistan
Focus: ML for Digital Twins, Reinforcement Learning, LLM Agents

Languages:
  - Python, TypeScript, JavaScript
  - Java (Android), C / C++, SQL

ML / DL / RL:
  - PyTorch, TensorFlow, scikit-learn, XGBoost
  - DQN, Gymnasium, A*, Dijkstra
  - Pandas, NumPy

LLMs:
  - OpenAI, Gemini, LangChain, LangGraph
  - RAG, tool calling, multi-agent systems
  - FAISS, Pinecone, Whisper

Evaluation:
  - Precision@K, Recall@K, NDCG, MRR
  - Cross-validation, ablation studies

Backend:
  - FastAPI, Django, Node.js, Express
  - PostgreSQL, MongoDB, Redis

Frontend:
  - React, Next.js, React Native, Tailwind CSS

DevOps / Cloud:
  - Docker, AWS (EC2, Fargate), Vercel
  - GitHub Actions, Git, Linux

Simulation:
  - NVIDIA Omniverse USD Composer

Currently:
  - ML digital twin of a NIEC air conditioner @ S2Cool
```

---

## Selected work

### ML Digital Twin — S2Cool
*£2.8M UKRI project · Northumbria University · 30+ partners across the UK and Pakistan*

Trained ML models for three NIEC air-conditioner components (humidifier, wet channel, dry channel) on ~6,000 data points from each of **11 physical experiments in London**. Models reach **R² > 0.93, RMSE < 0.5**, and drive performance modelling and failure prediction. Connected to **NVIDIA Omniverse USD Composer** via Python so the 3D model runs as a real-time simulation.

`PyTorch` `scikit-learn` `NVIDIA Omniverse` `Python`

### [Deep RL Escape Room Agents](https://github.com/moneeb07/Escape-game-rl)

DQN trained in a custom Gymnasium environment (22 state features, 5 actions) with prioritized experience replay and a target network. The agent collects a clue and escapes while dodging a predictive bullet, a chasing ghost and two moving saws — **90% bullet, 87% saw, 80% ghost avoidance over 1,000 episodes**.

`PyTorch` `Gymnasium` `Pygame` `DQN`

### [NLP Job Recommender](https://github.com/moneeb07/nlp_job_recommender)

Two-stage retrieve-and-rank across 5,000 job postings: FAISS retrieves the top 100 via Sentence-BERT embeddings, then a weighted re-ranker scores meaning, skill overlap and experience. IR metrics implemented from scratch — **NDCG@10 rose 0.329 → 0.464 (+41%)** over a TF-IDF baseline.

`Sentence-BERT` `FAISS` `spaCy` `scikit-learn`

### [Kissan Dost](https://github.com/moneeb07/Kissan-Dost)

Crop-yield prediction over 9 crops across 12 countries using rainfall, temperature, pesticide and soil data. Six regression models compared — **Random Forest best at R² = 0.9679** — plus ARIMA and LSTM forecasts behind a Streamlit app.

`scikit-learn` `XGBoost` `TensorFlow` `Streamlit`

### StackShadow — 2nd place, national Google AI Hackathon

Three Gemini agents audit any GitHub repository for vulnerabilities and outdated dependencies against OSV and GitHub Advisories, with a cost-analysis agent, row-level security and a 6-model fallback chain.

`Gemini` `Multi-agent` `Next.js` `PostgreSQL`

### InterviewAI

Full hiring platform with five AI-graded interview rounds across three services. Code runs against test cases in a **Judge0 sandbox via Redis/BullMQ**, system-design diagrams are scored 0–100 by GPT-4o, and the voice round uses a Vapi agent. CI/CD ships the Docker service to AWS EC2.

`React` `Node.js` `FastAPI` `MongoDB` `Docker` `AWS`

---

## Achievements

- Selected to contribute to **S2Cool**, a £2.8M UKRI-funded international research project
- **133rd of 75,000 applicants** — NUST Entrance Test 2023
- **2nd place** — national Google AI Hackathon
- **172nd of 3,000** — AI Hackathon Pakistan 2026 (first Alibaba Cloud hackathon in Pakistan)

---

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=moneeb07&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=moneeb07&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />

<img src="https://github-profile-trophy.vercel.app/?username=moneeb07&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=6" alt="Trophies" />

</div>
