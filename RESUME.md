# Kevin Kirui

**Biomedical AI Developer**

Nairobi, Kenya

arapkirui513@gmail.com | [linkedin.com/in/kevin-kirui-ba9593275](https://linkedin.com/in/kevin-kirui-ba9593275) | [github.com/arapkirui513-hub](https://github.com/arapkirui513-hub)

---

## Profile

Biomedical AI developer with a foundation in Biomedical Engineering from KMTC. Hands-on experience maintaining critical care equipment at Kenya's largest referral hospitals (KNH & KTRH). Building AI solutions for healthcare—from arrhythmia detection to clinical NLP. Bridging the gap between clinical engineering and intelligent systems.

---

## Projects

### [ECG Arrhythmia Detector](https://github.com/arapkirui513-hub/ecg-arrhythmia-detector)

End-to-end arrhythmia classification comparing Random Forest vs 1D CNN on MIT-BIH Arrhythmia Database.

- Achieved **99.9% F1-score** with zero false negatives on minority class (Atrial Premature Beats)
- Solved "Equilibrium Trap" with **141:1 class weighting** for rare arrhythmia detection
- Implemented bandpass filtering (0.5–40 Hz) to improve R-peak detection from 88% to **97.3%**
- CNN outperformed classical ML by capturing P-wave morphology in raw waveforms

**Tech:** Python, PyTorch, Scikit-learn, WFDB, NumPy, Matplotlib

---

### [Chest X-Ray Pneumonia Classifier](https://github.com/arapkirui513-hub/chest-xray-classifier)

Binary classification using DenseNet-121 with Grad-CAM interpretability on Kaggle Chest X-Ray dataset.

- Test AUC: **0.89**, exceeding technical threshold of 0.85
- Grad-CAM analysis revealed spurious boundary activation in false negatives
- Two-phase transfer learning: frozen backbone → end-to-end fine-tuning
- Full evaluation: ROC curve, sensitivity, specificity, confusion matrix

**Tech:** Python, PyTorch, MONAI, Grad-CAM

---

### [Clinical Note Assistant](https://github.com/arapkirui513-hub/clinical-note-assistant)

NLP-powered clinical note summarisation with Streamlit interface and GPT-4o-mini.

- Extracts chief complaint, diagnosis, and plan from free-text clinical notes
- Manual validation identified 4 failure patterns (pre-op diagnosis copying, data omission)
- Implemented safety disclaimer and per-output caveat for regulatory compliance
- Operative-report few-shot example improved diagnosis synthesis

**Tech:** Python, Streamlit, OpenAI API

---

## Clinical Experience

### Biomedical Equipment Technician

**Kenyatta National Hospital (KNH) & KTRH** | 2023–Present

- Maintained critical care equipment including ECG monitors, ventilators, and diagnostic imaging systems
- Supported clinical engineering workflows in East Africa's largest referral hospital
- Gained firsthand understanding of clinical data flows and equipment constraints

---

## Skills

| Category | Skills |
|----------|--------|
| **Clinical Engineering** | ECG equipment, medical imaging systems, ventilators, hospital workflows |
| **Deep Learning** | PyTorch, MONAI, CNNs, transfer learning, Grad-CAM |
| **Classical ML** | Scikit-learn, Random Forest, feature engineering, class imbalance handling |
| **Healthcare AI** | WFDB, DICOM, PhysioNet, clinical NLP, MIT-BIH, signal processing |
| **Tools** | Git, Docker, Jupyter, Streamlit, Conda, Kaggle |
| **Languages** | Python, SQL |

---

## Education

### Kenya Medical Training College (KMTC)

**Diploma in Biomedical Engineering**

**Certificate in Biomedical Engineering**

---

### Pre-Stanmore AI for Biomedical Engineering

**Self-directed study programme** | 2026

- Built 3 end-to-end healthcare AI projects
- Covered: neural networks, medical imaging, clinical NLP, regulatory compliance

---

## Regulatory Awareness

All projects are educational prototypes. Clinical AI deployment requires: MHRA/FDA conformity assessment, prospective clinical validation, clinician-in-the-loop oversight, comprehensive audit trails, and patient consent.

---

## References

Available upon request
