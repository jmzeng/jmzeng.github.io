---
title: Natural Language Processing to Identify Cancer Treatments With Electronic Medical
  Records
authors:
- Jiaming Zeng
- Imon Banerjee
- A. Solomon Henry
- Douglas J. Wood
- Ross D. Shachter
- Michael F. Gensheimer
- Daniel L. Rubin
date: '2021-12-01'
publishDate: '2023-12-16T17:13:24.193043Z'
publication_types:
- article-journal
publication: '*JCO Clinical Cancer Informatics*'
doi: 10.1200/CCI.20.00173
abstract: PURPOSE Knowing the treatments administered to patients with cancer is important
  for treatment planning and correlating treatment patterns with outcomes for personalized
  medicine study. However, existing methods to identify treatments are often lacking.
  We develop a natural language processing approach with structured electronic medical
  records and unstructured clinical notes to identify the initial treatment administered
  to patients with cancer.   METHODS We used a total number of 4,412 patients with
  483,782 clinical notes from the Stanford Cancer Institute Research Database containing
  patients with nonmetastatic prostate, oropharynx, and esophagus cancer. We trained
  treatment identification models for each cancer type separately and compared performance
  of using only structured, only unstructured ( bag-of-words, doc2vec, fasttext),
  and combinations of both ( structured + bow, structured + doc2vec, structured +
  fasttext). We optimized the identification model among five machine learning methods
  (logistic regression, multilayer perceptrons, random forest, support vector machines,
  and stochastic gradient boosting). The treatment information recorded in the cancer
  registry is the gold standard and compares our methods to an identification baseline
  with billing codes.   RESULTS For prostate cancer, we achieved an f1-score of 0.99
  (95% CI, 0.97 to 1.00) for radiation and 1.00 (95% CI, 0.99 to 1.00) for surgery
  using structured + doc2vec. For oropharynx cancer, we achieved an f1-score of 0.78
  (95% CI, 0.58 to 0.93) for chemoradiation and 0.83 (95% CI, 0.69 to 0.95) for surgery
  using doc2vec. For esophagus cancer, we achieved an f1-score of 1.0 (95% CI, 1.0
  to 1.0) for both chemoradiation and surgery using all combinations of structured
  and unstructured data. We found that employing the free-text clinical notes outperforms
  using the billing codes or only structured data for all three cancer types.   CONCLUSION
  Our results show that treatment identification using free-text clinical notes greatly
  improves upon the performance using billing codes and simple structured data. The
  approach can be used for treatment cohort identification and adapted for longitudinal
  cancer treatment identification.
featured: true
links:
- name: URL
  url: https://ascopubs.org/doi/10.1200/CCI.20.00173
- name: Github
  url: https://github.com/jmzeng/cancer_treatment_identification
---
