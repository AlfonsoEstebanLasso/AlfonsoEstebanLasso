# Alfonso Esteban Lasso

Biomedical data scientist: biostatistics, machine learning and synthetic patient data for clinical trials. PhD researcher in Information and Communication Technologies (Artificial Intelligence) at Universidad Rey Juan Carlos. Biologist (UCM, 2016), MSc in Bioinformatics and Biostatistics (UOC-UB, 2019), BSc in Applied Data Science (UOC, 2026).

## Focus

- **Synthetic patient data for clinical trials.** Whether synthetic data preserves the inferential validity of survival analysis (hazard ratios, event rates, statistical significance, type I error), using deep generative models (variational autoencoders) and public, de-identified, patient-level phase 3 oncology trials from Project Data Sphere. Previously developed within a public-private R&D project on AI for clinical trials funded by the Spanish State Research Agency and co-funded by ERDF (CPP2023-010929).
- **Survival analysis and biostatistics.** Cox proportional hazards, random survival forests and gradient boosting; calibration, bootstrap and leakage-controlled cross-validation; subgroup robustness.
- **Privacy-preserving data sharing.** Re-identification risk (membership inference, k-anonymity, distance to closest record), anonymization, pseudonymization and GDPR-aware pipelines.
- **Bioinformatics and omics data analysis.** RNA-seq (fastp, HISAT2, featureCounts, DESeq2, GSEA), Oxford Nanopore bacterial genomics (Prokka, Roary, Integron Finder) and proteomics statistics in R.

## Selected repositories

| Repository | What it shows |
| --- | --- |
| [survival-prediction-nesp-nct00119613](https://github.com/AlfonsoEstebanLasso/survival-prediction-nesp-nct00119613) | Reproducible pipeline predicting overall and progression-free survival under chemotherapy from anonymized phase 3 trial data (NCT00119613): Cox PH vs RSF vs XGBoost with anti-leakage CV, bootstrap, calibration, SHAP; CTGAN synthetic data with TSTR, membership-inference, k-anonymity and DCR checks; pytest smoke tests and a model card. BSc thesis, UOC (9.6/10). |
| [gdsc-depmap-drug-response-r](https://github.com/AlfonsoEstebanLasso/gdsc-depmap-drug-response-r) | Drug response prediction in cancer cell lines from gene expression (GDSC v17.3 AUC, DepMap 19Q1): random forest (h2o, caret), ridge, lasso and elastic net (glmnet) and linear SVM, as regression and classification, with a reproducible data download, a renv environment and a documented errata of the 2019 code. MSc thesis code, UOC-UB, published as deposited. |
| [platelet-aggregation-flow-cytometry-r](https://github.com/AlfonsoEstebanLasso/platelet-aggregation-flow-cytometry-r) | R code of a 2021 commissioned analysis of platelet aggregation, surface markers and hemogram by flow cytometry in essential thrombocythemia (two-way ANOVA with Tukey HSD by genotype and treatment), published as delivered and cleaned, with its limitations documented and no patient data; related to a 2026 Molecular & Cellular Proteomics article (third author). |
| [data-privacy-lab](https://github.com/AlfonsoEstebanLasso/data-privacy-lab) | Linkage attacks on a de-identified HR dataset, then k-anonymity generalization, MDAV microaggregation, salted double-hash pseudonymization and RSA/ElGamal/A5-1 encryption. |
| [spark-ml-streaming](https://github.com/AlfonsoEstebanLasso/spark-ml-streaming) | PySpark on a Cloudera CDH cluster: spark.ml pipeline predicting ICU admission from ~460k COVID-19 records (class-imbalance handling) plus Structured Streaming jobs on live ADS-B aircraft positions. |
| [restaurant-reviews-sentiment](https://github.com/AlfonsoEstebanLasso/restaurant-reviews-sentiment) | Sentiment-analysis data product for 2.36M reviews: TextBlob weak labeling, TF-IDF, logistic regression vs random forest, SHAP explainability and a per-restaurant KPI widget. |
| [text-mining-ner-spacy](https://github.com/AlfonsoEstebanLasso/text-mining-ner-spacy) | NLTK preprocessing of 1.6M tweets, a Keras LSTM seq2seq German-English translator with GloVe embeddings, and a custom spaCy NER model with entity linking to Wikidata. |
| [machine-learning-labs](https://github.com/AlfonsoEstebanLasso/machine-learning-labs) | SVM vs decision trees, ensemble regression, CNNs and ResNet50 transfer learning, and tabular Q-learning on Gymnasium CliffWalking. |

Also public: [social-network-analysis](https://github.com/AlfonsoEstebanLasso/social-network-analysis) (NetworkX retweet network from 1.42M tweets, community detection, epidemic-spreading simulations), [covid-vaccination-dataviz](https://github.com/AlfonsoEstebanLasso/covid-vaccination-dataviz) (interactive Plotly charts), [musicbrainz-collab-graphs](https://github.com/AlfonsoEstebanLasso/musicbrainz-collab-graphs) (API data collection and collaboration graphs), [shell-data-pipelines](https://github.com/AlfonsoEstebanLasso/shell-data-pipelines) (bash, awk and gnuplot) and [java-oop-exercises](https://github.com/AlfonsoEstebanLasso/java-oop-exercises) (Java 17). All repositories are MIT-licensed.

## Stack

Python (pandas, NumPy, scikit-learn, scikit-survival, lifelines, XGBoost, SHAP, SDV, TensorFlow/Keras, spaCy, NLTK, PySpark, NetworkX, Plotly, pytest), R (survival, DESeq2, tidyverse), SQL/PostgreSQL, Bash, HPC with SLURM, Docker, Git.

## Publications

- Guerrero-Carreño X, Smits S, **Esteban Lasso A**, et al. Platelet Proteome Links Metabolism to Reactivity in Essential Thrombocythemia. *Mol Cell Proteomics*. 2026;25:101617. [doi:10.1016/j.mcpro.2026.101617](https://doi.org/10.1016/j.mcpro.2026.101617)
- Bargiela-Cuevas S, et al. (incl. **Esteban-Lasso A**). Histone Acetyl Transferase 1 Is Overexpressed in Poor Prognosis, High-grade Meningeal and Glial Brain Cancers. *J Histochem Cytochem*. 2024;72(8-9):585-599. [doi:10.1369/00221554241272341](https://doi.org/10.1369/00221554241272341)
- **Esteban Lasso A**, Martínez Toledo C, Perosanz Amarillo S. Diseño de un modelo para generar datos sintéticos en investigación médica. *Dianas*. 2023;12(1):e202303fp01. [dianas.web.uah.es](https://dianas.web.uah.es/journal/e202303fp01)

Full list, funding and affiliations on ORCID: [0009-0006-4029-6178](https://orcid.org/0009-0006-4029-6178).

## Recognition

Work on synthetic patient data for oncology trials selected as one of 50 projects from over 800 applications to Anthropic's inaugural Claude Science Cohort (AI for Science program), 2026.

## Contact

[LinkedIn](https://www.linkedin.com/in/alfonsoestebanlasso) | [ORCID](https://orcid.org/0009-0006-4029-6178)
