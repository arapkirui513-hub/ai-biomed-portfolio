# Kevin Kirui — Biomedical AI Portfolio

> **Bridging clinical engineering and intelligent systems.**

Biomedical AI developer with a foundation in Biomedical Engineering from KMTC. Hands-on experience at Kenya's largest referral hospitals (KNH & KTRH), building AI solutions for healthcare—from arrhythmia detection to clinical NLP. Currently focused on data engineering and the Nairobi tech ecosystem, preparing for Stanmore AI for Biomedical Engineering.

[![GitHub](https://img.shields.io/badge/GitHub-arapkirui513--hub-blue?logo=github)](https://github.com/arapkirui513-hub)
[![Email](https://img.shields.io/badge/Email-arapkirui513%40gmail.com-red?logo=gmail)](mailto:arapkirui513@gmail.com)

---

## 📊 GitHub Stats

![Kevin's GitHub Stats](https://github-readme-stats.vercel.app/api?username=arapkirui513-hub&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=arapkirui513-hub&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9)

---

## Projects

### 1. [🫀 ECG Arrhythmia Detector](https://github.com/arapkirui513-hub/ecg-arrhythmia-detector)

**End-to-end arrhythmia classification using deep learning and classical ML.**

- Processed 9,561 beats from MIT-BIH Arrhythmia Database (4 records)
- Implemented bandpass filtering, R-peak detection (97.3% accuracy), beat segmentation
- Compared Random Forest (F1: 0.996) vs 1D CNN (F1: 0.999)
- CNN outperformed RF on minority class (Atrial Premature Beats: 0.933 vs 0.923)
- High sensitivity on atrial premature beats—critical for AFib screening

**Tech:** Python, PyTorch, Scikit-learn, WFDB, NumPy, Matplotlib

---

### 2. [🫁 Chest X-Ray Pneumonia Classifier](https://github.com/arapkirui513-hub/chest-xray-classifier)

**Binary classification using transfer learning with DenseNet-121 and Grad-CAM interpretability.**

- Two-phase transfer learning on Kaggle Chest X-Ray dataset
- Test AUC: 0.8887 (exceeds 0.85 threshold)
- Grad-CAM analysis revealed spurious boundary activation in false negatives
- Full evaluation: ROC curve, sensitivity, specificity, confusion matrix

**Tech:** Python, PyTorch, MONAI, Grad-CAM

---

### 3. [📋 Clinical Note Assistant](https://github.com/arapkirui513-hub/clinical-note-assistant)

**NLP-powered clinical note summarisation with Streamlit interface.**

- Extracts chief complaint, diagnosis, and plan from free-text clinical notes
- GPT-4o-mini with prompt engineering for structured extraction
- Manual validation identified 4 failure patterns (pre-op diagnosis copying, data omission)
- Implemented safety disclaimer and per-output caveat for regulatory compliance

**Tech:** Python, Streamlit, OpenAI API

**Status:** ⚠️ Educational prototype only — NOT FOR CLINICAL USE

---

## Skills

| Category | Technologies |
|----------|--------------|
| **Languages** | Python, SQL |
| **Deep Learning** | PyTorch, TensorFlow, MONAI |
| **Classical ML** | Scikit-learn, XGBoost |
| **Healthcare AI** | WFDB, DICOM, Clinical NLP, PhysioNet |
| **Web/App** | Streamlit, Flask |
| **Tools** | Git, Docker, Jupyter, Conda, Kaggle |
| **Data** | Pandas, NumPy, Matplotlib, Seaborn |

---

## What's Next

- **Stanmore AI for Biomedical Engineering** — Formal training in medical AI development
- **Expanding into** medical imaging, clinical decision support, and healthcare data engineering
- **Contributing to** open-source healthcare AI (WFDB, PyHealth, MONAI tutorials)

---

## Regulatory & Ethical Statement

All projects in this portfolio are **educational prototypes**. They have not been validated for clinical use and must not be used to inform patient care decisions.

Clinical AI deployment requires:

- Prospective clinical validation
- MHRA/FDA conformity assessment
- Clinician-in-the-loop oversight
- Comprehensive audit trails
- Patient consent and data governance

---

## Contact

- **GitHub:** [github.com/arapkirui513-hub](https://github.com/arapkirui513-hub)
- **Email:** arapkirui513@gmail.com

---

*Built as part of Pre-Stanmore AI for Biomedical Engineering self-study programme.*
