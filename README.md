<h1 align="center">Vivaan Gupta</h1>
<p align="center">
  <strong>Biomedical Engineering & Computer Science @ Johns Hopkins University</strong><br>
  Building AI/ML systems for clinical decision support, medical imaging, surgical intelligence, and drug discovery
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vivaangupta">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:vgupta18@jh.edu">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" />
  </a>
</p>

---

### About Me

Biomedical engineering and computer science student at Johns Hopkins building deep learning systems for regulated clinical environments. My work spans medical image segmentation, surgical video analysis, cardiac signal processing, drug discovery, and clinical NLP — with a consistent focus on FDA-ready evaluation methodology, demographic bias analysis, and production deployment.

Every project includes detailed `RESULTS.md` documentation with methodology, benchmarks against published baselines, ablation studies, and clinical context.

---

### Featured Projects

#### Medical Imaging & Surgical AI

| Project | Description | Key Results | Stack |
|---------|-------------|-------------|-------|
| [**MedSeg Pipeline**](https://github.com/VivaanGupta17/medseg-pipeline) | U-Net & Attention U-Net for brain tumor segmentation on BraTS with DICOM preprocessing and Grad-CAM explainability | WT Dice 0.901, TC 0.834, ET 0.798 | PyTorch · pydicom · NIfTI |
| [**SurgPhase**](https://github.com/VivaanGupta17/surgical-phase-recognition) | Real-time surgical phase recognition & instrument detection on Cholec80 using MS-TCN++ and Transformers | 92.1% accuracy, 42 FPS, mAP 0.847 | PyTorch · ONNX · TensorRT |
| [**VSP-3D**](https://github.com/VivaanGupta17/vsp-3d-reconstruction) | AI-powered virtual surgical planning — DICOM → 3D segmentation → mesh → osteotomy planning → 3D-printable guides | Mandible Dice 0.952, 12 min vs 3 weeks | PyTorch · VTK · SimpleITK |

#### Cardiac & Wearable AI

| Project | Description | Key Results | Stack |
|---------|-------------|-------------|-------|
| [**CardioAI**](https://github.com/VivaanGupta17/cardio-ai) | 12-lead ECG arrhythmia detection with multi-sensor fusion and 6-mechanism alert fatigue reduction | AUROC 0.953, 70.6% false alarm reduction | PyTorch · SciPy · PhysioNet |
| [**GlucoCast**](https://github.com/VivaanGupta17/glucocast) | CGM glucose forecasting with Temporal Fusion Transformers — hypoglycemia prevention with Clarke Error Grid validation | 11.6 RMSE (30-min), 97.3% Zone A+B | PyTorch · OhioT1DM |

#### Drug Discovery & Pharma AI

| Project | Description | Key Results | Stack |
|---------|-------------|-------------|-------|
| [**MolProp-GNN**](https://github.com/VivaanGupta17/molprop-gnn) | Graph neural networks for ADMET property prediction with scaffold-split evaluation and atom-level interpretability | HIV AUROC 0.793, scaffold split analysis | PyG · RDKit · Optuna |
| [**TrialPredictor**](https://github.com/VivaanGupta17/trial-predictor) | Clinical trial outcome prediction with portfolio NPV simulation — predicting Phase II/III success from compound + trial features | AUROC 0.714, +$1.4B eNPV lift | XGBoost · DeepSurv · SHAP |

#### Clinical NLP & MLOps

| Project | Description | Key Results | Stack |
|---------|-------------|-------------|-------|
| [**ClinicalRAG**](https://github.com/VivaanGupta17/clinical-nlp-rag) | RAG pipeline for biomedical literature with hallucination detection, biomedical NER, and HIPAA-compliant clinical text processing | 8.3% hallucination rate (vs 24.1% no-RAG) | PubMedBERT · FAISS · ScispaCy |
| [**MedML-Ops**](https://github.com/VivaanGupta17/medml-ops) | FDA-compliant MLOps with GMLP checklist automation, PCCP model versioning, bias monitoring, and drift detection | 10/10 GMLP principles automated | MLflow · FastAPI · Docker |

#### Other Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [**Aurexon**](https://github.com/VivaanGupta17/aurexon) | Medtech asset intelligence platform — ML-powered due diligence with 9-stage analysis pipeline | React · TypeScript · Express |
| [**HRV-TBI**](https://github.com/Rapuris/HRV_TBI) | TBI subphenotype identification through heart rate variability clustering on MIMIC-III | Python · R · scikit-learn |

---

### Technical Focus Areas

```
Medical Imaging          ██████████████████░░  Segmentation, 3D reconstruction, DICOM/NIfTI, Grad-CAM
Surgical AI              ████████████████░░░░  Phase recognition, instrument detection, VSP, real-time inference
Cardiac & Wearable AI    ████████████████░░░░  ECG classification, CGM prediction, HRV, alert fatigue reduction
Drug Discovery ML        ██████████████░░░░░░  GNNs, ADMET prediction, clinical trial outcomes, portfolio NPV
Clinical NLP             ██████████████░░░░░░  RAG, biomedical NER, hallucination detection, HIPAA compliance
MLOps & Regulatory       ██████████████████░░  FDA GMLP, PCCP, bias monitoring, drift detection, model lifecycle
```

---

### Tools & Frameworks

**ML/DL:** PyTorch · PyTorch Geometric · scikit-learn · XGBoost · ONNX · TensorRT · MONAI  
**Medical:** pydicom · SimpleITK · VTK · NIfTI · RDKit · PhysioNet · OpenSlide · ScispaCy  
**NLP/LLM:** PubMedBERT · FAISS · ChromaDB · Hugging Face Transformers  
**MLOps:** MLflow · Docker · FastAPI · Evidently AI · Great Expectations  
**Languages:** Python · C · JavaScript/TypeScript · SQL · R  
**Platforms:** AWS · NVIDIA CUDA · JHU Rockfish HPC · GitHub Actions

---

<p align="center">
  <em>Building AI systems that are not just accurate, but deployable in regulated clinical environments.</em><br>
  <em>Every project includes a detailed RESULTS.md — start there.</em>
</p>
