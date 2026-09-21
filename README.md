<div align="center">

# Carlos Andrés Durán Paredes

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1400&color=6929C4&center=true&vCenter=true&width=620&lines=Quantum+Machine+Learning+%C2%B7+Qiskit+2.x;M.Eng.+student+%40+Universidad+de+Antioquia+(UdeA);Physics+Engineer+%C2%B7+Universidad+del+Cauca" alt="Quantum Machine Learning · M.Eng. student at UdeA · Physics Engineer" />

<a href="https://www.linkedin.com/in/carlos-andres-duran-paredes-3a7878163/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://scholar.google.com/citations?user=wxrUAkUAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
<a href="https://www.researchgate.net/profile/Carlos-Duran-Paredes"><img src="https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white" alt="ResearchGate"></a>
<a href="mailto:caduranpd@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>

</div>

---

## About me

I'm a Master of Engineering student at **Universidad de Antioquia (UdeA)** working on **quantum machine learning**: variational classifiers, hybrid quantum-classical models, and experiments on real NISQ hardware through IBM Quantum. I graduated in Physics Engineering from Universidad del Cauca.

My work sits between papers and packages. When I publish a result, I try to ship the code as something other people can install, rerun, and check, with honest baselines and leakage-free evaluation instead of headline "quantum advantage" claims.

Before quantum, I worked on deep learning for urban acoustics (the *Sound Maps* project), led the IEEE AESS student chapter at Unicauca, and took part in the university's aerospace research seedbed.

---

## ⚛️ Featured project

<div align="center">

### [qiskit-data-reuploading](https://github.com/Carlosandp/qiskit-data-reuploading)

<a href="https://qiskit.github.io/ecosystem/p/d5572b9d/"><img src="https://qisk.it/e-d5572b9d" alt="Qiskit Ecosystem"></a>
<a href="https://pypi.org/project/qiskit-data-reuploading/"><img src="https://img.shields.io/pypi/v/qiskit-data-reuploading?color=6929C4&label=PyPI" alt="PyPI"></a>
<a href="https://pypi.org/project/qiskit-data-reuploading/"><img src="https://img.shields.io/pypi/dm/qiskit-data-reuploading?color=6929C4&label=downloads" alt="Downloads"></a>
<a href="https://arxiv.org/abs/2605.19233"><img src="https://img.shields.io/badge/arXiv-2605.19233-b31b1b" alt="arXiv"></a>

<img src="https://raw.githubusercontent.com/Carlosandp/qiskit-data-reuploading/main/data_reuploading_classifier.gif" width="480" alt="Data re-uploading classifier learning a decision boundary">

</div>

A scikit-learn-compatible data re-uploading quantum classifier (Pérez-Salinas et al., 2020) built on **Qiskit 2.x V2 primitives**. It is listed in the official **Qiskit Ecosystem** as a paper artifact and runs on simulators or IBM Quantum hardware with the same `fit` / `predict` API.

```bash
pip install qiskit-data-reuploading
```

---

## 🔬 Research code

**[TLM-UAV Quantum Anomaly Detection](https://github.com/Carlosandp/TLM-UAV-Quantum-Anomaly-Detection)** &nbsp;
<img src="https://img.shields.io/badge/Qiskit-2.x-6929C4?style=flat-square&logo=qiskit&logoColor=white" alt="Qiskit"> <img src="https://img.shields.io/badge/XGBoost-hybrid-189FDD?style=flat-square" alt="XGBoost"> <a href="https://arxiv.org/abs/2605.19233"><img src="https://img.shields.io/badge/arXiv-2605.19233-b31b1b?style=flat-square" alt="arXiv"></a><br>
Hybrid XGBoost + data re-uploading detector for cyber-physical attacks on drones, evaluated with a group-aware temporal split and a three-level proxy-feature audit. The hybrid is the only model whose F1 improves once contextual proxies are removed, and it records the lowest false-alarm rate under proxy-free evaluation. Fully reproducible.

**[GCM Strategy: Quantum Battle of the Sexes on NISQ hardware](https://github.com/Carlosandp/GCMStrategy)** &nbsp;
<img src="https://img.shields.io/badge/IBM_Quantum-QPU-052FAD?style=flat-square&logo=ibm&logoColor=white" alt="IBM Quantum"> <img src="https://img.shields.io/badge/IEEE_CHILECON-2025-00629B?style=flat-square&logo=ieee&logoColor=white" alt="IEEE CHILECON 2025"><br>
Classical vs. quantum (EWL scheme) Battle of the Sexes across 31 entanglement values, run on ideal simulation, noisy simulation, and real IBM QPUs. A guided circuit-mapping strategy picks qubit pairs to reduce error on hardware.

**[UrbanSonic-CNNs](https://github.com/Carlosandp/UrbanSonic-CNNs)** &nbsp;
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow"> <img src="https://img.shields.io/badge/librosa-audio-4B8BBE?style=flat-square" alt="librosa"><br>
CNN classifier for the *Urbanphony* urban soundscape taxonomy on spectrograms from historic cities. Published in *Ingeniería e Investigación* and at IntelliSys 2025.

---

## 🤖 Applied AI

**[Operational insights chatbot](https://github.com/Carlosandp/rappi-operational-insights-chatbot)**: natural-language KPI queries over logistics data. The LLM only parses intent and writes the narrative; every number comes from pandas, so answers can't hallucinate figures.

**[Competitive intelligence pipeline](https://github.com/Carlosandp/rappi-competitive-intelligence-mx)**: price, fee, ETA, and promotion monitoring across three delivery platforms in Mexico, with a Streamlit dashboard and an HTML executive report.

---

## 📄 Selected publications

- **Durán Paredes, C. A.** et al. *Quantum Machine Learning for Cyber-Physical Anomaly Detection in Unmanned Aerial Vehicles.* arXiv:[2605.19233](https://arxiv.org/abs/2605.19233), 2026.
- Díaz Agreda, G. D., … **Durán Paredes, C. A.** et al. *Experimental Implementation of the Quantum Volunteer's Dilemma on NISQ Hardware.* arXiv:[2605.30676](https://arxiv.org/abs/2605.30676), 2026.
- Cajas Ordóñez, S. A., … **Durán, C. A.** et al. *Uncertainty Makes It Stable: Curiosity-Driven Quantized Mixture-of-Experts.* arXiv:[2511.11743](https://arxiv.org/abs/2511.11743), 2025.
- Cajas Ordóñez, S. A., … **Durán, C. A.** et al. *Embedding-Aware Quantum-Classical SVMs for Scalable Quantum Machine Learning.* arXiv:[2508.00024](https://arxiv.org/abs/2508.00024), 2025.
- Díaz Agreda, G. D., **Durán Paredes, C. A.** et al. *Quantum Battle of the Sexes with Error Mitigation on NISQ Hardware.* IEEE CHILECON, 2025.
- **Durán Paredes, C. A.** et al. *Urbanphony-3-CNN.* Ingeniería e Investigación 45(2), 2025.
- **Durán, C.** et al. *A CNN-Based Approach for Classifying Urban Soundscape Taxonomy in Historic Cities.* IntelliSys, 2025.

Full list on [Google Scholar](https://scholar.google.com/citations?user=wxrUAkUAAAAJ&hl=en).

---

## 🧰 Tools

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Qiskit-6929C4?style=flat-square&logo=qiskit&logoColor=white" alt="Qiskit">
<img src="https://img.shields.io/badge/IBM_Quantum-052FAD?style=flat-square&logo=ibm&logoColor=white" alt="IBM Quantum">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
<img src="https://img.shields.io/badge/XGBoost-189FDD?style=flat-square" alt="XGBoost">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow">
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas">
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit">
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter">
<img src="https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white" alt="LaTeX">
</p>

---

<div align="center">

Open to research collaborations in quantum machine learning · 📫 <a href="mailto:caduranpd@gmail.com">caduranpd@gmail.com</a>

</div>
