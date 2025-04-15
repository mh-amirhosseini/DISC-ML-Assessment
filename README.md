📊 Dataset Overview: DISC-Inspired Personality Questionnaire (ML Study)
This repository contains the anonymised dataset for a machine learning–driven exploration of the DISC personality framework. The data was collected as part of a research project examining whether computational methods can enhance the classification accuracy, efficiency, and interpretability of traditional DISC-based assessments.

📌 About the Dataset
The dataset consists of responses to 40 personality items adapted from validated psychological inventories available via the International Personality Item Pool (IPIP). Items were drawn from four behavioural dimensions that loosely map onto the DISC model:

Assertiveness (CPI/IPIP)

Social Confidence (JPI-R/IPIP)

Adventurousness (NEO/IPIP)

Dominance (CPI/IPIP)

Each participant rated 40 statements on a 5-point Likert scale:

1 = Strongly disagree

2 = Disagree

3 = Neither agree nor disagree

4 = Agree

5 = Strongly agree

All statements were phrased in the first person (e.g., "I express myself easily", "I like to visit new places").

🧩 Item Structure
The questionnaire includes 10 items per DISC-related dimension:

AS (Assertiveness): AS1–AS10

SC (Social Confidence): SC1–SC10

AD (Adventurousness): AD1–AD10

DO (Dominance): DO1–DO10

Items cover behaviours such as leadership, sociability, novelty-seeking, and assertiveness.

👥 Demographic Information
Participants were asked to provide:

Gender (selected from: Male, Female, Other, or Prefer not to say)

Age (free-text entry; values below age 18 were excluded from the dataset)

To preserve anonymity, no personally identifiable information (PII) was collected. Only participants who confirmed the accuracy and research suitability of their responses were retained.

🔍 Purpose of the Dataset
This dataset supports analyses related to:

Supervised classification (e.g., Logistic Regression, XGBoost)

Feature selection using RFE

Unsupervised clustering (e.g., K-Means, PCA, Silhouette analysis)

Personality trait profiling and questionnaire reduction

It serves as the foundation for a research manuscript submitted to Nature Humanities and Social Sciences Communications.

📂 File Included
DISC.csv – cleaned and anonymised dataset (1001 rows × 47 columns)

📜 Citation
If using this dataset, please cite the corresponding research paper (link forthcoming upon publication).
