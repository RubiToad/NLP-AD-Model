# NLP-AD-Model
This project will use filtered and unfiltered clinical notes to classify AD and explain reasoning. 

Collaborators: Sumaya Hossain, Bismack Tokoli, Tyler Mondalto

Problem Description:

Alzheimer’s is a progressive neurodegenerative disorder with highly individualized trajectories. While predictive models can capture broad disease patterns, they often fail to provide patient-level explanations that clinicians and researchers can readily interpret. In our project, we work with structured CSV files that integrate information from imaging biomarkers, cognitive assessments, genetic profiles, and clinical notes. The goal is to transform these multimodal features (e.g., MMSE, CDR, hippocampal volume, Precuneus, Cingulate, APOE status) into clear, factual, and concise patient-level explanations that highlight progression and risk in an interpretable way.
Motivation & Importance:
- Patient-level explainability is crucial in Alzheimer’s disease, where small changes in cognition or imaging biomarkers can indicate progression.
- Clinicians and researchers need concise, consistent snapshots for each patient.
- Grounded summaries reduce manual chart review time, help track progression, and improve communication in multidisciplinary teams.
- This demonstrates responsible LLM use on clinical data with measurable factuality.


Dataset Information:

We will use the OASIS-3 (Open Access Series of Imaging Studies) dataset, a large longitudinal resource for Alzheimer’s disease and normal aging research. It includes data from over 1,000 participants aged 42–95, followed for more than 15 years.
Key Features & Data Integration:
-	Clinical Assessments: Clinical Dementia Rating (CDR), Mini-Mental State Examination (MMSE)
-	Neuroimaging Biomarkers: FreeSurfer derived MRI measures including hippocampal volumes, whole-brain volumes, and cortical thickness. PET-derived amyloid burden measures (SUVR)
-	Genetic Information: APOE genotype status, a critical Alzheimer's risk factor.
-	Demographics: Age, sex, education, and relevant medical history.
