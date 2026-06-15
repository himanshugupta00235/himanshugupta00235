<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=1600&color=58A6FF&center=true&vCenter=true&width=700&lines=Himanshu+Gupta+%E2%80%94+AI+%26+ML+Engineer;2+Published+Papers+%C2%B7+94.3%25+CV+Accuracy+%C2%B7+AIR+57+NMTSE;From+First+Principles+to+Production+AI)](https://git.io/typing-svg)

<br>

B.Tech Computer Science · AI/ML Specialization · Bennett University · **Graduating July 2026**

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/himanshu-gupta-383a6b220/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:himanshugupta00235@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/himanshugupta00235)

</div>

---

<div align="center">

| 📄 2 Published Papers | 💻 300+ DSA Problems | 🎯 94.3% CV Accuracy | 🏆 AIR 57 · NMTSE | 📦 6 Projects Shipped | 🎓 CGPA 8.15 / 10 |
|:---:|:---:|:---:|:---:|:---:|:---:|

</div>

---

## Who I Am

Three years. Built from first principles. Published peer-reviewed research on explainable AI and sustainability before my final year. Shipped a computer vision safety system that runs on a Raspberry Pi at 15 FPS. Wrote gradient descent from scratch before ever calling `model.fit()`.

Now learning to build with LLMs, RAG pipelines, and agentic systems — with the same discipline I brought to every layer before this one.

**I implement before I import. I publish before I claim. I optimize for real constraints, not benchmark scores.**

---

## Currently Building

> **Document Intelligence Pipeline** · `Active Build · 2025`

A production-minded RAG system for cross-document question answering over domain-specific corpora.

**Architecture under construction:**
- FastAPI async backend → LangChain retrieval chain → ChromaDB vector store → streaming response with source attribution
- Comparing chunking strategies: fixed-size vs recursive text splitting vs semantic chunking — measuring precision and recall at each approach
- Implementing BM25 + dense retrieval hybrid with Maximum Marginal Relevance (MMR) reranking for result diversity
- Target: sub-500ms query latency with grounded, citation-level answers

**Technical questions I'm working through:** Whether retrieval quality or generation quality is the dominant bottleneck in domain-specific RAG; how chunk overlap affects precision vs recall at different context window sizes; when hybrid retrieval actually outperforms dense-only.

[Repository (in progress) →](https://github.com/himanshugupta00235)

---

## Research Publications

Two peer-reviewed papers before graduation. Both focused on real-world deployment — not benchmark chasing.

<table>
<tr>
<td>

**Enhancing Crop Prediction with Explainable AI: SHAP-Based Approach**
*Peer-Reviewed · Published · 2024*

The problem with ML in agriculture isn't accuracy — it's that farmers won't act on a black-box prediction. Built a LightGBM pipeline (**98.64% accuracy** on SF24 dataset, 4,800 records, 28 features with SMOTE balancing), then applied SHAP for both global feature importance and per-prediction explanations. The goal wasn't just performance: it was a model a non-technical domain expert could interrogate, challenge, and trust. Accuracy and interpretability, not accuracy or interpretability.

[Read Paper →](https://ieeexplore.ieee.org/abstract/document/11398280)) &nbsp;·&nbsp; [Repository →](https://github.com/himanshugupta00235/Enhancing-Crop-Prediction-with-Explainable-AI-ASHAP-Based-Approach-)

</td>
</tr>
<tr>
<td>

**Revolutionizing Waste Management: An AI-driven Approach Towards Sustainability**
*Peer-Reviewed · Published · 2024*

Smart city infrastructure needs waste classification at camera speed. Applied Random Forest and Decision Tree ensemble classifiers on a 22,500+ image Kaggle dataset, using PCA and LASSO for dimensionality reduction before training — a deliberate choice to reduce variance before ensembling, not after. Validated via K-Fold cross-validation for generalization robustness. Built for operational scalability, not lab conditions.

[Read Paper →](https://www.taylorfrancis.com/chapters/edit/10.1201/9781003593089-140/revolutionizing-waste-management-ai-driven-approach-towards-sustainability-sankalp-bijalwan-aniket-saroj-himanshu-gupta-shashwat-sharma-saurabh-kumar-srivastava-ambrish-kumar)) &nbsp;·&nbsp; [Repository →](https://github.com/himanshugupta00235/Revolutionizing-Waste-Management-An-AI-driven-Approach-Towards-Sustainability-)

</td>
</tr>
</table>

---

## Engineering Journey

```
2022  ─── CS Foundations
      │   └── C++, Python · OOP · OS · Computer Networks · DBMS · SDLC
      │   └── 300+ DSA problems — LeetCode · TUF · GeeksforGeeks
      │   └── Cert: C++ Deep Dive (Udemy, Abdul Bari)
      │   └── Cert: Algorithmic Toolbox (Coursera, UC San Diego)
      │   └── Built: ChatNest (C++ CLI chat app with auth + messaging)
      │   └── Built: Huffman File Compressor (60% size reduction, files up to 10MB)
      │
2023  ─── Machine Learning & Applied Research
      │   └── Scikit-Learn · NumPy · Pandas · Matplotlib
      │   └── Batch gradient descent from scratch → R² > 98% on 10,000-record dataset
      │   └── TF-IDF + Logistic Regression spam classifier → 92.8%+ on 5,600 emails, Streamlit-deployed
      │   └── Cert: Supervised ML Classification (IBM, Coursera)
      │   └── Published: Crop Prediction with XAI (98.64% · SHAP)
      │   └── Published: Waste Management AI (22,500+ images · K-Fold validated)
      │
2024  ─── Deep Learning · Computer Vision · Accessibility AI
      │   └── TensorFlow · Keras · OpenCV · Dlib
      │   └── Driver Drowsiness Detection — 94.3% accuracy, 15 FPS, Raspberry Pi deployable
      │   └── Multi-indicator fusion (EAR + MAR + Head Pose) → 5.7% false positive rate
      │   └── Sign Language Converter — Audio/Text ↔ Indian Sign Language (web app)
      │   └── Flask + Streamlit deployment experience
      │
2025  ─── Generative AI & Agentic Systems  ◄─── Active
            └── FastAPI · LangChain · ChromaDB · FAISS
            └── RAG Architecture · Hybrid Retrieval · Embedding Models
            └── LangGraph · AI Agents (next)
            └── Building: Document Intelligence Pipeline
```

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### Real-Time Driver Drowsiness Detection
`Computer Vision` `Safety-Critical AI` `Edge Deployment`

**The problem:** Single-metric systems (PERCLOS alone) generate false positives that drivers begin ignoring — eliminating the safety benefit entirely.

**The approach:** Multi-indicator AND logic: Eye Aspect Ratio (EAR) + Mouth Aspect Ratio (MAR) + Head Pose Estimation via Dlib's 68-point facial landmark model. Alert triggers only when multiple thresholds breach simultaneously, drastically cutting spurious alerts.

**Stack:** `Python` `OpenCV` `Dlib` `NumPy` `Flask`

**Results:** 94.3% detection accuracy · 5.7% false positive rate · 15 FPS real-time · Raspberry Pi deployable

**Decision that mattered:** AND logic over OR logic for multi-signal fusion. OR catches everything but cries wolf constantly. AND preserves trust in the alert system.

[![Code →](https://img.shields.io/badge/View%20Code-%23181717?style=flat-square&logo=github&logoColor=white)](https://github.com/himanshugupta00235/Real-Time-Driver-Drowsiness-Detection-System-By-Himanshu)

</td>
<td width="50%" valign="top">

### Crop Prediction with Explainable AI *(Published)*
`XAI` `LightGBM` `SHAP` `Agricultural ML`

**The problem:** Accurate crop prediction models fail in the field because domain experts — farmers — won't act on predictions they can't interrogate or challenge.

**The approach:** LightGBM classification on SMOTE-balanced SF24 dataset (4,800 records, 28 features) → SHAP post-hoc explainability for both global feature importance and per-prediction attribution. Each prediction ships with a reason a non-technical user can evaluate.

**Stack:** `Python` `LightGBM` `SHAP` `SMOTE` `Scikit-Learn`

**Results:** 98.64% accuracy · Peer-reviewed and published · Actionable explanations for non-ML users

**Decision that mattered:** SHAP post-hoc over an inherently interpretable model preserved accuracy while adding trust. The explainability-accuracy tradeoff was a choice, not a constraint.

[![Code →](https://img.shields.io/badge/View%20Code-%23181717?style=flat-square&logo=github&logoColor=white)](https://github.com/himanshugupta00235/Enhancing-Crop-Prediction-with-Explainable-AI-ASHAP-Based-Approach-)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Gradient Descent from Scratch
`ML Fundamentals` `Optimization` `NumPy`

**The problem:** Most engineers know how to call `model.fit()`. Fewer understand what happens at each iteration — which means they can't debug it when it fails.

**The approach:** Full pipeline without sklearn optimization: feature normalization → custom batch gradient descent (10,000 iterations, manually tracked) → loss curve visualization → residual analysis for model validation.

**Stack:** `Python` `NumPy` `Matplotlib` `Pandas`

**Results:** R² > 98% on 10,000-record dataset · Internalized understanding of optimization mechanics

**Decision that mattered:** Implementing feature normalization manually revealed why gradient descent diverges when features are on different scales — a step sklearn silently handles but that breaks without it.

[![Code →](https://img.shields.io/badge/View%20Code-%23181717?style=flat-square&logo=github&logoColor=white)](https://github.com/himanshugupta00235/Predictive-Regression-Modeling-with-Gradient-Descent-)

</td>
<td width="50%" valign="top">

### Sign Language Converter (Audio/Text ↔ ISL)
`Accessibility AI` `Computer Vision` `NLP`

**The problem:** Communication tools for deaf and hard-of-hearing communities are severely under-resourced in Indian Sign Language compared to ASL or English-language systems.

**The approach:** Web application converting audio and text input to ISL gesture sequences with bidirectional support — both hearing-to-signing and signing-to-text pathways.

**Stack:** `Python` `Computer Vision` `NLP` `Web App`

**Results:** Functional bidirectional ISL converter · Addresses a high-impact accessibility gap where prior art in Indian language sign systems is minimal

**Why this project:** AI's highest-leverage use cases are often in domains where the market is small but the need is acute and systematically underserved.

[![Code →](https://img.shields.io/badge/View%20Code-%23181717?style=flat-square&logo=github&logoColor=white)](https://github.com/himanshugupta00235/Real-time-audio-text-to-Indian-sign-language-and-vice-versa-converter)

</td>
</tr>
</table>

<details>
<summary><b>+ 2 more projects (ChatNest · Spam Classifier)</b></summary>

<br>

**ChatNest — C++ CLI Chat Application** · `C++` `STL` `Data Structures`
Real-time command-line chat system built entirely in C++ with STL containers. User registration, authentication, friend management, and messaging without external networking libraries. Forced every architectural decision into the open.
→ [Repository](https://github.com/himanshugupta00235/Chatting-Based-Application-using-Cpp-Data-Structure)

<br>

**Spam Message / Email Classifier** · `NLP` `Scikit-Learn` `Streamlit`
TF-IDF → StandardScaler → Logistic Regression → Streamlit web app with pickle-based model serving. 92.8%+ accuracy on 5,600 emails. A clean, production-ready sklearn pipeline from preprocessing to live inference.
→ [Repository](https://github.com/himanshugupta00235/Spam-Message-Email-Identifier-By-Himanshu)

</details>

---

## Technical Arsenal

<table>
<tr>
<th align="center">Foundation · Used in Projects</th>
<th align="center">Active · Current Builds</th>
<th align="center">Next · Mastering Now</th>
</tr>
<tr>
<td align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</td>
<td align="center">

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</td>
<td align="center">

![LangGraph](https://img.shields.io/badge/LangGraph-58A6FF?style=flat-square&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-00D4FF?style=flat-square&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-00C4B4?style=flat-square&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-FF4B4B?style=flat-square&logoColor=white)

</td>
</tr>
</table>

---

## What Makes Me Different

Three things that distinguish how I work — not just what I've learned:

**1. I implement before I import.**
Wrote batch gradient descent from scratch before using sklearn optimizers. Built Huffman compression from scratch before ever importing zlib. This isn't academic masochism — it's how I ensure I understand exactly what I'm asking a library to do, so I can reason about it when it fails or behaves unexpectedly.

**2. I publish, not just prototype.**
Two peer-reviewed papers before my final year. Research discipline changes how you engineer: define your evaluation methodology before running experiments, not after seeing results you like. That habit carries directly into how I build and validate ML systems.

**3. I design for the constraints that actually matter.**
94.3% accuracy on a server is meaningless if it runs at 2 FPS on the hardware your user has. Built the drowsiness detector specifically to run on Raspberry Pi at 15 FPS. Used SHAP specifically because farmers — not data scientists — are the end users. Real-world constraints are design inputs, not obstacles to work around.

---

## AI Engineer Roadmap

| Stage | Status | Proof |
|---|:---:|---|
| CS Foundations + DSA | ✅ | 300+ problems · C++ & algorithms certifications · AIR 57 NMTSE |
| Classical Machine Learning | ✅ | 3 ML projects · custom gradient descent · sklearn pipelines in production |
| Deep Learning + Computer Vision | ✅ | Drowsiness detection at 94.3% · Sign language converter · TF + OpenCV |
| Applied Research | ✅ | 2 peer-reviewed papers published · SHAP / XAI · ensemble methods |
| Generative AI / RAG Systems | 🔄 | Document Intelligence Pipeline in progress · LangChain + ChromaDB |
| Agentic AI Engineering | ⏳ | LangGraph · multi-agent coordination · tool use · memory systems |
| Production AI Systems | 🎯 | MLOps · inference optimization · monitoring · scalable pipelines |

---

## Learning in Public

I don't just list technologies I'm exploring. Here's exactly what I'm doing and where I am:

| Topic | Current Activity | Depth |
|---|---|---|
| RAG Architecture | Building doc Q&A pipeline; benchmarking fixed vs semantic chunking | Implementing — past tutorial stage |
| LangChain / LCEL | Working through LangChain Expression Language + building custom chains | Active — first retrieval chains working |
| FastAPI | Building async ML inference endpoints with Pydantic validation | First endpoints deployed locally |
| Foundational Papers | Reading originals, not blog summaries: *Attention Is All You Need* · *RAG paper (Lewis et al.)* · *Constitutional AI* | Ongoing — taking structured notes |
| ML Theory | Re-derive key results before trusting library implementations | Done: gradient descent, backprop, attention weights |
| Problem Solving | Consistent practice — 300+ over 3 years, not pre-interview sprints | Ongoing |

---

## GitHub Analytics

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=himanshugupta00235&show_icons=true&theme=github_dark&hide_border=true&count_private=true&include_all_commits=true" />
<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=himanshugupta00235&layout=compact&theme=github_dark&hide_border=true&langs_count=8" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=himanshugupta00235&theme=github-dark-blue&hide_border=true)](https://git.io/streak-stats)

</div>

---

## Open To

<div align="center">

Graduating **July 2026** · Actively seeking full-time roles in:

**ML Engineering &nbsp;·&nbsp; AI Engineering &nbsp;·&nbsp; Generative AI Engineering &nbsp;·&nbsp; Research Engineering**

Also open to: pre-placement offers, research internships (2025–2026), and AI product collaborations.

<br>

[![Email](https://img.shields.io/badge/himanshugupta00235%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:himanshugupta00235@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Let's%20Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/himanshu-gupta-383a6b220/)
[![Resume](https://img.shields.io/badge/Download%20Resume-181717?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://drive.google.com/file/d/1RAXEdIfAIvesxwoDafYlOe6vK4p-me_7/view?usp=sharing)

<br>

*Greater Noida, India · Open to remote and relocation*

</div>

---

<div align="center">
<sub>Every claim on this profile has a repository or published paper behind it.</sub>
</div>
