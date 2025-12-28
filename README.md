<!--
**Av1352/Av1352** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<div align="center">

# Anju Vilashni Nandhakumar  
### Applied Machine Learning Engineer · Computer Vision · NLP · Reinforcement Learning

**MS in Artificial Intelligence, Northeastern University**  
Boston, MA · Open to Full-Time ML/AI Roles

I design and deploy ML systems where **correctness, interpretability, and real-world constraints**
matter more than leaderboard scores.

[![Portfolio](https://img.shields.io/badge/Portfolio-vxanju.com-73BA9B?style=for-the-badge&logo=google-chrome&logoColor=white)](https://vxanju.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-anju--vilashni-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/anju-vilashni)
[![Email](https://img.shields.io/badge/Email-nandhakumar.anju@gmail.com-DAB49D?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nandhakumar.anju@gmail.com)

</div>

---

## 🧠 What I Build

- End-to-end ML systems from data → model → deployment  
- Explainable computer vision models for high-stakes domains  
- Transformer-based NLP systems on large-scale datasets  
- Reinforcement learning agents under safety and efficiency constraints  

My work focuses on **engineering tradeoffs**, not just model accuracy.

---

## 🎯 Senior Highlights

- Reduced inference latency by **~20%** through GPU-aware optimization  
- Built **clinical-style ML pipelines** with explainability and reporting  
- Designed **multi-agent RL systems** with reward shaping and safety constraints  
- Deployed multiple models as **production-ready web systems**  

---

## 🏗 Flagship Systems

### VisAIble — Explainable Deepfake Detection System  
**PyTorch · EfficientNet · Grad-CAM · LIME**

**Problem**  
Deepfake detection systems fail in real environments when predictions lack interpretability.

**Key Decisions**
- Chose EfficientNet-B0 over ViTs to meet latency constraints  
- Combined Grad-CAM and LIME for complementary explanations  
- Focused on false-positive reduction over raw accuracy

**Outcome**
- +8% accuracy over baseline CNN  
- ~22% reduction in false positives on unseen data  

🔗 [Live Demo](https://visaible.streamlit.app/) · [Code](https://github.com/Av1352/VisAIble)

---

### Explainable Tumor Classification  
**TensorFlow · CNNs · SHAP · Medical Imaging**

**Problem**  
Black-box cancer classifiers are unsuitable for clinical decision support.

**Approach**
- CNN-based histopathology classification  
- SHAP + Grad-CAM overlays for clinician-interpretable outputs  

**Outcome**
- High-confidence predictions with visual explanation overlays  
- Designed for clinical review rather than benchmark optimization  

🔗 [Live Demo](https://tumor-classification-xai.streamlit.app/) · [Code](https://github.com/Av1352/Tumor-Classification)

---

### Logical Fallacy Detection  
**ELECTRA · Transformers · NLP**

**Problem**  
Detecting nuanced logical fallacies requires reasoning beyond keyword matching.

**Approach**
- Fine-tuned ELECTRA on multi-class fallacy datasets  
- Combined contextual embeddings with case-based reasoning

**Outcome**
- Robust performance across subtle fallacy classes  
- Generalized better than classical classifiers on out-of-distribution samples  

🔗 [Live Demo](https://logical-fallacy-detection.streamlit.app/) · [Code](https://github.com/Av1352/Logical-Fallacy-Detection)

---

### Autonomous Highway Reinforcement Learning  
**Rainbow DQN · A3C · Decision Transformers**

**Problem**  
RL agents trained in simulation often fail under safety-critical constraints.

**Key Learnings**
- Reward shaping mattered more than algorithm choice  
- Stable policies required conservative exploration strategies  

**Outcome**
- Achieved max reward of 48.2 in highway-env  
- Improved policy stability across random seeds  

🔗 [Live Demo](https://highway-reinforecement-problem.streamlit.app/) · [Code](https://github.com/Av1352/Highway-RL)

---

## ⚙️ Engineering Notes (Things That Actually Mattered)

- Dataset leakage caused larger performance drops than architecture choice  
- Explainability methods were unstable across seeds → fixed via normalization  
- Inference optimization had more real-world impact than marginal accuracy gains  
- RL agent behavior was dominated by reward design, not model complexity  

---

## 🧰 Tools I Reach For

**Modeling:** PyTorch, TensorFlow, Hugging Face  
**Explainability:** Grad-CAM, SHAP, LIME  
**Deployment:** Docker, AWS, Streamlit, Flask  
**Experimentation:** Scikit-learn, NumPy, Pandas  

---

## 📊 GitHub Activity

<div align="center">

<img
  src="https://github-readme-stats.vercel.app/api?username=Av1352&show_icons=true&count_private=true"
  alt="GitHub Stats"
  height="165"
/>

<img
  src="https://github-readme-streak-stats.herokuapp.com?user=Av1352"
  alt="GitHub Streak"
  height="165"
/>

</div>

---

## 🎓 Education

**Northeastern University** — MS in Artificial Intelligence  
**SRM Institute of Science and Technology** — BE Computer Science (AI/ML)

---

## 📝 Publication

**Music Recommendation via Facial Emotion Recognition**  
*International Journal of Research and Analytical Reviews (IJRAR), 2022*  
📄 https://ijrar.org/viewfull.php?&p_id=IJRAR22D2280

---

## 🔍 Currently Exploring

- Explainability under distribution shift  
- Human-AI collaboration in safety-critical ML  
- Bridging academic ML and production constraints  

---

<div align="center">

*I build ML systems meant to survive outside notebooks.*  
⭐ If something here helps you, feel free to star the repo.

</div>
