# MLOPS-with-DVC

This repository demonstrates a Machine Learning Operations (ML Ops) workflow using **Data Version Control (DVC)** for data & model versioning and experiment tracking, applied to an **email spam classification** project. The sample dataset and artifacts are versioned via DVC, and large assets are stored on **AWS S3**.

---

## 🔍 Project Overview

Deep learning and ML projects evolve through repeated experiments, parameter changes, and dataset updates. To make this process **reproducible**, **collaborative**, and **trackable**, this project uses:

- **Git** for source code versioning  
- **DVC** to version datasets, models, metrics, and experiments  
- **AWS S3** as remote storage for large data artifacts  
- (Optional) Logging and experiment visualization with DVCLive / Studio  

This setup ensures you can reproduce all steps, compare runs, and maintain clear lineage between data, code, and models. :contentReference[oaicite:0]{index=0}

---

## 🧠 Features

- 📦 **Data Versioning** — Track dataset changes without bloating git history  
- 🧪 **Experiment Tracking** — Record results, metrics, and parameters for every run  
- ⚙️ **Pipeline Automation** — Define workflows with `dvc.yaml`  
- ☁️ **Remote Storage** — Push data and models to AWS S3  
- 📊 **Experiment Comparison** — Compare outcomes over multiple runs easily  
