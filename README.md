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

Biomedical engineering and computer science student at Johns Hopkins building deep learning systems for regulated clinical environments. My work spans medical image segmentation, self-supervised pretraining, radiology report generation, surgical video analysis, imitation learning for surgical robots, cardiac signal processing, wearable health, digital pathology, drug discovery, clinical NLP, ICU monitoring, and FDA-compliant MLOps.

Every project includes a detailed **RESULTS.md** with methodology, benchmarks against published baselines, ablation studies, and clinical context. Start there.

---

### Medical Imaging & Reconstruction

| Project | Description | Key Results | Stack |
|---------|-------------|-------------|-------|
| [**MedSeg Pipeline**](https://github.com/VivaanGupta17/medseg-pipeline) | U-Net & Attention U-Net for brain tumor segmentation on BraTS | WT Dice 0.901, TC 0.834, ET 0.798 | PyTorch · pydicom · NIfTI |
| [**MedFM**](https://github.com/VivaanGupta17/medfm) | Self-supervised foundation models (SimCLR, MoCo v3, MAE) pretrained on chest X-rays | MAE 1%-label AUROC 0.742 vs 0.572 random | PyTorch · ViT · timm |
| [**RadReport-VL**](https://github.com/VivaanGupta17/radreport-vl) | Vision-language model for automated radiology report generation | BLEU-4 0.142, 12.4% hallucination rate | PyTorch · BioGPT · MIMIC-CXR |
| [**MRI-DiffRecon**](https://github.com/VivaanGupta17/mri-diffusion-recon) | Score-based diffusion models for accelerated MRI reconstruction | SSIM 0.942 at 4x, 98.2% pathology preserved | PyTorch · fastMRI · SDE |
| [**PathAI**](https://github.com/VivaanGupta17/pathai) | MIL for whole slide image analysis — cancer detection on Camelyon16 | TransMIL AUROC 0.961, FROC 0.846 | PyTorch · OpenSlide · CLAM |

### Surgical AI & Robotics

| Project | Description | Key Results | Stack |
|---------|-------------|-------------|-------|
| [**SurgPhase**](https://github.com/VivaanGupta17/surgical-phase-recognition) | Real-time surgical phase recognition & instrument detection on Cholec80 | 92.1% accuracy, 42 FPS, mAP 0.847 | PyTorch · ONNX · TensorRT |
| [**VSP-3D**](https://github.com/VivaanGupta17/vsp-3d-reconstruction) | AI-powered virtual surgical planning — CT → 3D segmentation → osteotomy → 3D-printable guides | Mandible Dice 0.952, 12 min vs 3 weeks | PyTorch · VTK · SimpleITK |
| [**SurgBot-IL**](https://github.com/VivaanGupta17/surgbot-il) | Imitation learning for surgical robots — BC, DAgger, Diffusion Policy, VLA models | Diffusion Policy 84.7% suturing success | PyTorch · JIGSAWS · Gym |

### Cardiac, Wearable & ICU AI

| Project | Description | Key Results | Stack |
|---------|-------------|-------------|-------|
| [**CardioAI**](https://github.com/VivaanGupta17/cardio-ai) | 12-lead ECG arrhythmia detection with multi-sensor fusion and alert fatigue reduction | AUROC 0.953, 70.6% false alarm reduction | PyTorch · SciPy · PTB-XL |
| [**GlucoCast**](https://github.com/VivaanGupta17/glucocast) | CGM glucose forecasting with Temporal Fusion Transformers | 11.6 RMSE (30-min), 97.3% Clarke A+B | PyTorch · OhioT1DM |
| [**ICU-Anomaly**](https://github.com/VivaanGupta17/icu-anomaly) | ICU time-series anomaly detection — sepsis prediction, mortality, early warning | Sepsis AUROC 0.847, 1.8 alarms/day | PyTorch · MIMIC-III |

### Drug Discovery & Pharma AI

| Project | Description | Key Results | Stack |
|---------|-------------|-------------|-------|
| [**MolProp-GNN**](https://github.com/VivaanGupta17/molprop-gnn) | Graph neural networks for ADMET molecular property prediction | HIV AUROC 0.793, scaffold split analysis | PyG · RDKit · Optuna |
| [**TrialPredictor**](https://github.com/VivaanGupta17/trial-predictor) | Clinical trial outcome prediction with portfolio NPV simulation | AUROC 0.714, +$1.4B eNPV lift | XGBoost · DeepSurv · SHAP |

### Clinical NLP & MLOps

| Project | Description | Key Results | Stack |
|---------|-------------|-------------|-------|
| [**ClinicalRAG**](https://github.com/VivaanGupta17/clinical-nlp-rag) | RAG for biomedical literature with hallucination detection and biomedical NER | 8.3% hallucination (vs 24.1% no-RAG) | PubMedBERT · FAISS · ScispaCy |
| [**MedML-Ops**](https://github.com/VivaanGupta17/medml-ops) | FDA-compliant MLOps — GMLP automation, PCCP versioning, bias monitoring, drift detection | 10/10 GMLP principles automated | MLflow · FastAPI · Docker |

### Other Projects

| Project | Description | Stack |
|---------|-------------|-------|
| [**Aurexon**](https://github.com/VivaanGupta17/aurexon) | Medtech asset intelligence platform with 9-stage ML analysis pipeline | React · TypeScript · Express |
| [**HRV-TBI**](https://github.com/Rapuris/HRV_TBI) | TBI subphenotype identification through HRV clustering on MIMIC-III | Python · R · scikit-learn |

---

### Technical Focus Areas

```
Medical Imaging          ██████████████████████  Segmentation, foundation models, report generation, diffusion recon
Digital Pathology        ████████████████░░░░░░  Whole slide images, MIL, cancer detection, stain normalization
Surgical AI & Robotics   ████████████████████░░  Phase recognition, VSP, imitation learning, VLA, diffusion policy
Cardiac & Wearable AI    ██████████████████░░░░  ECG, CGM prediction, HRV, multi-sensor fusion, alert fatigue
ICU & Clinical Monitoring████████████████░░░░░░  Sepsis prediction, early warning, anomaly detection, MIMIC
Drug Discovery ML        ██████████████░░░░░░░░  GNNs, ADMET, clinical trials, portfolio NPV simulation
Clinical NLP             ██████████████░░░░░░░░  RAG, biomedical NER, hallucination detection, HIPAA
MLOps & Regulatory       ██████████████████░░░░  FDA GMLP, PCCP, bias monitoring, drift detection, lifecycle
```

---

### Tools & Frameworks

**ML/DL:** PyTorch · PyTorch Geometric · scikit-learn · XGBoost · ONNX · TensorRT · MONAI · timm  
**Medical:** pydicom · SimpleITK · VTK · NIfTI · RDKit · PhysioNet · OpenSlide · ScispaCy  
**NLP/LLM:** PubMedBERT · BioGPT · FAISS · ChromaDB · Hugging Face Transformers  
**Vision:** ViT · SimCLR · MoCo · MAE · CLAM · TransMIL · Diffusion Models  
**MLOps:** MLflow · Docker · FastAPI · Evidently AI · Great Expectations  
**Languages:** Python · C · JavaScript/TypeScript · SQL · R  
**Platforms:** AWS · NVIDIA CUDA · JHU Rockfish HPC · GitHub Actions

---

<p align="center">
  <em>Building AI systems that are not just accurate, but deployable in regulated clinical environments.</em><br>
  <em>Every project includes a detailed RESULTS.md — start there.</em>
</p>
