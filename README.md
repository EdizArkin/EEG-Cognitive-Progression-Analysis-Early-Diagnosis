# EEG-Cognitive-Progression-Analysis-Early-Diagnosis

**AI-driven analysis of multimodal EEG/ERP signals for the early detection and prognosis tracking of Mild Cognitive Impairment (MCI) and related neurological disorders.**

## 📋 Project Overview  
This repository hosts the notebooks, analysis workflows, and documentation for a research project focusing on the use of electroencephalography (EEG) and event-related potentials (ERP) to detect and monitor cognitive decline (specifically MCI) at an early stage.

## 🧠 Key Features  
- Multimodal signal processing (resting-state EEG + ERP tasks)  
- Machine learning / AI models for classification of MCI vs Healthy Controls (HC)  
- Longitudinal and prognostic tracking of cognitive progression  
- Notebook-driven, fully reproducible research pipeline  

## 📂 Folder Structure  
/README.md
/LICENSE
/.gitignore
/DATA_CREDIT.md
/data/ ← dataset files (included in repository; small and anonymized)
/notebooks/ ← main Jupyter notebooks for preprocessing, analysis, and model training
/src/ ← helper scripts and functions used in notebooks
/results/ ← output figures, metrics, and intermediate results


## 🗂️ Dataset  
The primary dataset used in this project is sourced from the Harvard Dataverse repository.

- **DOI:** doi:10.7910/DVN/GDGIVG  
- **Persistent URL:** https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/GDGIVG  
- Detailed dataset acknowledgement and citation are provided in `DATA_CREDIT.md`.

## 📌 Licensing & Credit  
- The **code** in this repository is released under the MIT License (see `LICENSE`).  
- The **dataset** is shared under the licence conditions specified by the original Harvard Dataverse record.  
- Users must include proper acknowledgment of the dataset in any derived publication or reuse of this repository.  

## 🧮 Reproducibility & Versioning  
- All analyses are conducted in Jupyter Notebooks to ensure clarity and transparency.  
- The environment and dependencies can be recreated via a `requirements.txt` or `environment.yml` file.  
- Random seeds and configuration parameters are explicitly set in each notebook for consistent results.  
- Data integrity is maintained by versioning through Git, with large raw files tracked and structured for efficient reuse.  

## 📝 Citation  
If you use this repository or its results in your research, please cite:  

Ediz Arkın Kobak (2025). EEG-Cognitive-Progression-Analysis-Early-Diagnosis:
AI-driven multimodal EEG/ERP pipeline for early detection and prognosis tracking of MCI and related neurological disorders.
GitHub repository, https://github.com/EdizArkin/EEG-Cognitive-Progression-Analysis-Early-Diagnosis


Also include the dataset citation provided in `DATA_CREDIT.md`.

---
