<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=1600&color=58A6FF&center=true&vCenter=true&width=950&lines=Himanshu+Gupta+%E2%80%94+AI%2FML+Engineer+%26+Flutter+Developer;2+Published+Papers+%C2%B7+94.3%25+CV+Accuracy+%C2%B7+Production+Flutter+Apps;From+First+Principles+to+Production+AI+%26+Apps)](https://git.io/typing-svg)

<br>

B.Tech Computer Science · AI/ML Specialization · Bennett University · **Graduating July 2026**

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/himanshu-gupta-383a6b220/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:himanshugupta00235@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/himanshugupta00235)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-v2-one-zeta.vercel.app/)

</div>

---

<div align="center">

| 📄 2 Published Papers | 💻 350+ DSA Problems | 🎯 94.3% CV Accuracy | 📱 Flutter + Firebase Shipped | 🏆 AIR 57 · NMTSE | 🎓 CGPA 8.15 / 10 |
|:---:|:---:|:---:|:---:|:---:|:---:|

</div>

---

## Who I Am

Three years. Built from first principles. Published peer-reviewed research on explainable AI and sustainability before my final year. Shipped a computer vision safety system that runs on a Raspberry Pi at 15 FPS. Wrote gradient descent from scratch before ever calling `model.fit()`.

Most recently, took that same discipline into mobile: shipped **PrepAI**, a Flutter interview-prep app built on Firebase, MVVM, and the Repository Pattern — because a well-validated model means nothing if it never reaches a product someone actually opens. Now learning to build with LLMs, RAG pipelines, and agentic systems too — with the same rigor I brought to every layer before this one.

**I implement before I import. I publish before I claim. I design for the product someone opens, not just the metric on a slide.**

---

## Featured Build

### PrepAI — Flutter Interview-Prep App
`Mobile Development` `Firebase` `Clean Architecture`

**The problem:** Interview-prep tools are either flat, unfiltered question dumps or web-only experiences — neither fits into the small, frequent gaps of a real day where most prep actually happens.

**The approach:** Built mobile-first in Flutter on **MVVM** with a **Repository Pattern** and a dedicated **Service Layer**, so Firebase never touches the UI directly — ViewModels talk only to repository interfaces, never to Firestore. Firebase Authentication and Cloud Firestore sync a categorized, difficulty-filtered question bank, bookmarks, dashboard analytics, and progress tracking in real time, with AI-generated answer suggestions layered in as the direct bridge between the ML work below and a product someone opens daily.

**Stack:** `Flutter` `Dart` `Firebase Auth` `Cloud Firestore` `Provider` `MVVM` `Repository Pattern` `Material Design`

**Results:** Full authentication + real-time data sync across categories, difficulty levels, bookmarks, and progress · Clean separation across Views, ViewModels, Repositories, and Services · Built using Cursor and GitHub Copilot without sacrificing architectural discipline

**Decision that mattered:** Repository Pattern over direct Firestore calls inside ViewModels — the backend could be swapped (Supabase, a mock source, anything) without touching a single screen. Same instinct as choosing SHAP over a black-box model: optimize for what you can defend, not just what happens to work once.

[![Code →](https://img.shields.io/badge/View%20Code-%23181717?style=flat-square&logo=github&logoColor=white)](https://github.com/himanshugupta00235/prep-ai)
[![Live Demo →](https://img.shields.io/badge/Live%20Demo-FFCA28?style=flat-square&logo=firebase&logoColor=black)](https://prepai-5819e.web.app/#/home)

---

## Currently Building

> **KhetSaathi** · `Active Build`

An offline-first Flutter + Firebase app that turns my published crop-prediction research into something an actual farmer with patchy or no internet can use in the field.

**Architecture under construction:**
- Flutter (offline-first) → local Hive cache → background sync queue → Cloud Firestore → Cloud Function → LightGBM crop-advisory model endpoint
- Comparing offline conflict-resolution strategies for farm-log entries: last-write-wins vs merge-on-sync vs manual conflict flagging, since rural connectivity drops mid-write often
- On-device crop/leaf photo capture with client-side compression before upload, to keep data usage low on 2G
- FCM push notifications for advisory alerts (pest risk, irrigation timing) triggered from Cloud Functions once the model scores new data
- Target: fully usable offline for data entry, auto-syncs within a short window once connectivity returns, advisory shown in the farmer's regional language

[Repository (in progress) →](https://github.com/himanshugupta00235)

---

## Research Publications

Two peer-reviewed papers before graduation. Both focused on real-world deployment — not benchmark chasing.

<table>
<tr>
<td>

**Enhancing Crop Prediction with Explainable AI: SHAP-Based Approach**
*Peer-Reviewed · Published · 2026*

The problem with ML in agriculture isn't accuracy — it's that farmers won't act on a black-box prediction. Built a LightGBM pipeline (**98.64% accuracy** on SF24 dataset, 4,800 records, 28 features with SMOTE balancing), then applied SHAP for both global feature importance and per-prediction explanations. The goal wasn't just performance: it was a model a non-technical domain expert could interrogate, challenge, and trust.

[Read Paper →](https://ieeexplore.ieee.org/abstract/document/11398280) &nbsp;·&nbsp; [Repository →](https://github.com/himanshugupta00235/Enhancing-Crop-Prediction-with-Explainable-AI-ASHAP-Based-Approach-)

</td>
</tr>
<tr>
<td>

**Revolutionizing Waste Management: An AI-driven Approach Towards Sustainability**
*Peer-Reviewed · Published · 2025*

Smart city infrastructure needs waste classification at camera speed. Applied Random Forest and Decision Tree ensemble classifiers on a 22,500+ image Kaggle dataset, using PCA and LASSO for dimensionality reduction before training, validated via K-Fold cross-validation for generalization robustness.

[Read Paper →](https://www.taylorfrancis.com/chapters/edit/10.1201/9781003593089-140/revolutionizing-waste-management-ai-driven-approach-towards-sustainability-sankalp-bijalwan-aniket-saroj-himanshu-gupta-shashwat-sharma-saurabh-kumar-srivastava-ambrish-kumar) &nbsp;·&nbsp; [Repository →](https://github.com/himanshugupta00235/Revolutionizing-Waste-Management-An-AI-driven-Approach-Towards-Sustainability-)

</td>
</tr>
</table>

---

## Engineering Journey

```
2022  ─── CS Foundations
      │   └── C++, Python · OOP · OS · Computer Networks · DBMS · SDLC
      │   └── 300+ DSA problems — LeetCode · TUF · GeeksforGeeks
      │   └── Built: ChatNest (C++ CLI chat app with auth + messaging)
      │   └── Built: Huffman File Compressor (60% size reduction, files up to 10MB)
      │
2023  ─── Machine Learning & Applied Research
      │   └── Scikit-Learn · NumPy · Pandas · Matplotlib
      │   └── Batch gradient descent from scratch → R² > 98% on 10,000-record dataset
      │   └── TF-IDF + Logistic Regression spam classifier → 92.8%+ on 5,600 emails, Streamlit-deployed
      │   └── Published: Crop Prediction with XAI (98.64% · SHAP) (2026)
      │   └── Published: Waste Management AI (22,500+ images · K-Fold validated) (2025)
      │
2024  ─── Deep Learning · Computer Vision · Accessibility AI
      │   └── TensorFlow · Keras · OpenCV · Dlib
      │   └── Driver Drowsiness Detection — 94.3% accuracy, 15 FPS, Raspberry Pi deployable
      │   └── Multi-indicator fusion (EAR + MAR + Head Pose) → 5.7% false positive rate
      │   └── Sign Language Converter — Audio/Text ↔ Indian Sign Language (web app)
      │
2025  ─── Generative AI & Agentic Systems
      │   └── FastAPI · LangChain · ChromaDB · FAISS
      │   └── RAG Architecture · Hybrid Retrieval · Embedding Models
      │   └── Building: Document Intelligence Pipeline
      │
2026  ─── Mobile Development & Production Architecture  ◄─── Active
            └── Flutter · Dart · Firebase (Auth, Firestore) · Provider
            └── MVVM · Repository Pattern · Service Layer architecture
            └── Built: PrepAI — Flutter interview-prep app, developed with Cursor + GitHub Copilot
            └── Applying research-grade rigor to mobile product architecture
```

---

## Other Projects

<table>
<tr>
<td width="50%" valign="top">

### Real-Time Driver Drowsiness Detection
`Computer Vision` `Safety-Critical AI` `Edge Deployment`

**The problem:** Single-metric systems (PERCLOS alone) generate false positives that drivers begin ignoring — eliminating the safety benefit entirely.

**The approach:** Multi-indicator AND logic: Eye Aspect Ratio (EAR) + Mouth Aspect Ratio (MAR) + Head Pose Estimation via Dlib's 68-point facial landmark model.

**Stack:** `Python` `OpenCV` `Dlib` `NumPy` `Flask`

**Results:** 94.3% detection accuracy · 5.7% false positive rate · 15 FPS real-time · Raspberry Pi deployable

[![Code →](https://img.shields.io/badge/View%20Code-%23181717?style=flat-square&logo=github&logoColor=white)](https://github.com/himanshugupta00235/Real-Time-Driver-Drowsiness-Detection-System-By-Himanshu)

</td>
<td width="50%" valign="top">

### Crop Prediction with Explainable AI *(Published)*
`XAI` `LightGBM` `SHAP` `Agricultural ML`

**The problem:** Accurate crop prediction models fail in the field because domain experts — farmers — won't act on predictions they can't interrogate.

**The approach:** LightGBM classification on SMOTE-balanced SF24 dataset → SHAP post-hoc explainability for global and per-prediction attribution.

**Stack:** `Python` `LightGBM` `SHAP` `SMOTE` `Scikit-Learn`

**Results:** 98.64% accuracy · Peer-reviewed and published · Actionable explanations for non-ML users

[![Code →](https://img.shields.io/badge/View%20Code-%23181717?style=flat-square&logo=github&logoColor=white)](https://github.com/himanshugupta00235/Enhancing-Crop-Prediction-with-Explainable-AI-ASHAP-Based-Approach-)

</td>
</tr>
</table>

<details>
<summary><b>+ 4 more projects (Gradient Descent · Sign Language Converter · ChatNest · Spam Classifier)</b></summary>

<br>

**Gradient Descent from Scratch** · `Python` `NumPy` `Matplotlib`
Full pipeline without sklearn optimization: manual feature normalization → custom batch gradient descent → loss curve visualization. R² > 98% on a 10,000-record dataset.
→ [Repository](https://github.com/himanshugupta00235/Predictive-Regression-Modeling-with-Gradient-Descent-)

**Sign Language Converter (Audio/Text ↔ ISL)** · `Computer Vision` `NLP`
Web application converting audio and text input to Indian Sign Language gesture sequences with bidirectional support.
→ [Repository](https://github.com/himanshugupta00235/Real-time-audio-text-to-Indian-sign-language-and-vice-versa-converter)

**ChatNest — C++ CLI Chat Application** · `C++` `STL` `Data Structures`
Real-time command-line chat system built entirely in C++ with STL containers — no external networking libraries.
→ [Repository](https://github.com/himanshugupta00235/Chatting-Based-Application-using-Cpp-Data-Structure)

**Spam Message / Email Classifier** · `NLP` `Scikit-Learn` `Streamlit`
TF-IDF → StandardScaler → Logistic Regression → Streamlit web app. 92.8%+ accuracy on 5,600 emails.
→ [Repository](https://github.com/himanshugupta00235/Spam-Message-Email-Identifier-By-Himanshu)

</details>

---

## Technical Arsenal

<table>
<tr>
<th align="center">Foundation · Shipped in Production</th>
<th align="center">Active · Current Builds</th>
<th align="center">Next · Mastering Now</th>
</tr>
<tr>
<td align="center">

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</td>
<td align="center">

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

</td>
<td align="center">

![Riverpod](https://img.shields.io/badge/Riverpod-58A6FF?style=flat-square&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-58A6FF?style=flat-square&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-00D4FF?style=flat-square&logoColor=white)

</td>
</tr>
</table>

---

## What Makes Me Different

**1. I implement before I import.**
Wrote batch gradient descent from scratch before using sklearn optimizers. This is how I ensure I understand exactly what I'm asking a library to do, so I can reason about it when it fails.

**2. I publish, not just prototype.**
Two peer-reviewed papers before my final year. Research discipline changes how you engineer: define your evaluation methodology before running experiments, not after seeing results you like.

**3. I design for the constraints that actually matter.**
94.3% accuracy on a server is meaningless if it runs at 2 FPS on the hardware your user has. Built the drowsiness detector specifically to run on Raspberry Pi at 15 FPS. Used SHAP specifically because farmers — not data scientists — are the end users.

**4. I build the model and the product around it.**
A SHAP explanation or a 94.3%-accurate detector is only as useful as the surface it ships in. Built PrepAI specifically to prove the same rigor extends past the notebook — into Firebase-backed, MVVM-architected, production mobile code.

---

## Engineer Roadmap

| Stage | Status | Proof |
|---|:---:|---|
| CS Foundations + DSA | ✅ | 350+ problems · AIR 57 NMTSE |
| Classical Machine Learning | ✅ | 3 ML projects · custom gradient descent · sklearn pipelines in production |
| Deep Learning + Computer Vision | ✅ | Drowsiness detection at 94.3% · Sign language converter · TF + OpenCV |
| Applied Research | ✅ | 2 peer-reviewed papers published · SHAP / XAI · ensemble methods |
| **Mobile / Production App Development** | ✅ | **PrepAI — Flutter, Firebase, MVVM, Repository Pattern** |
| Generative AI / RAG Systems | 🔄 | Document Intelligence Pipeline in progress · LangChain + ChromaDB |
| Agentic AI Engineering | ⏳ | LangGraph · multi-agent coordination · tool use · memory systems |

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

Graduating **July 2026** · Actively seeking roles in:

**Flutter / Mobile App Development &nbsp;·&nbsp; ML Engineering &nbsp;·&nbsp; AI Engineering &nbsp;·&nbsp; Generative AI Engineering**

Also open to: pre-placement offers, mobile development internships, research internships (2025–2026), and AI product collaborations.

<br>

[![Email](https://img.shields.io/badge/himanshugupta00235%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:himanshugupta00235@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Let's%20Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/himanshu-gupta-383a6b220/)
[![Resume](https://img.shields.io/badge/Download%20Resume-181717?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://drive.google.com/file/d/1RAXEdIfAIvesxwoDafYlOe6vK4p-me_7/view?usp=sharing)

<!-- ⚠️ Update the Resume badge link above once you upload the new Flutter-focused resume version -->

<br>

*Greater Noida, India · Open to remote and relocation*

</div>

---

<div align="center">
<sub>Every claim on this profile has a repository or published paper behind it.</sub>
</div>
