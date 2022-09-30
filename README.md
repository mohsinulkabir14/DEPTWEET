# DEPTWEET
GitHub repository for the DEPTWEET: A Typology for Social Media Texts to Detect Depression Severities. Published in [Computers in Human Behavior](https://www.journals.elsevier.com/computers-in-human-behavior).
# Data
Data folder contains tweet id's corresponding to severities of depression collected from Twitter. Owing to Twitter's policy we are restricted to sharing tweet-id's and users can rehydrate this dataset using <a href=https://github.com/DocNow/hydrator>hydrator</a>. In case of missing tweets or difficulties in extracting tweets, readers may send an email to the corresponding author (mohsinulkabir@iut-dhaka.edu).
# Code
Code for obtaining the baseline result is available in this <a href= https://github.com/tasnim7ahmed/Depression-In-Tweets>repo</a>.
# Citation
If you find our work and dataset useful, please cite our [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0747563222003235).
```bash
@article{KABIR2022107503,
title = {DEPTWEET: A typology for social media texts to detect depression severities},
journal = {Computers in Human Behavior},
pages = {107503},
year = {2022},
issn = {0747-5632},
doi = {https://doi.org/10.1016/j.chb.2022.107503},
url = {https://www.sciencedirect.com/science/article/pii/S0747563222003235},
author = {Mohsinul Kabir and Tasnim Ahmed and Md. Bakhtiar Hasan and Md Tahmid Rahman Laskar and Tarun Kumar Joarder and Hasan Mahmud and Kamrul Hasan},
keywords = {Social media, Mental health, Depression severity, Dataset},
abstract = {Mental health research through data-driven methods has been hindered by a lack of standard typology and scarcity of adequate data. In this study, we leverage the clinical articulation of depression to build a typology for social media texts for detecting the severity of depression. It emulates the standard clinical assessment procedure Diagnostic and Statistical Manual of Mental Disorders (DSM-5) and Patient Health Questionnaire (PHQ-9) to encompass subtle indications of depressive disorders from tweets. Along with the typology, we present a new dataset of 40191 tweets labeled by expert annotators. Each tweet is labeled as ‘non-depressed’ or ‘depressed’. Moreover, three severity levels are considered for ‘depressed’ tweets: (1) mild, (2) moderate, and (3) severe. An associated confidence score is provided with each label to validate the quality of annotation. We examine the quality of the dataset via representing summary statistics while setting strong baseline results using attention-based models like BERT and DistilBERT. Finally, we extensively address the limitations of the study to provide directions for further research.}
}
```
