# DEPTWEET
This repository contains the code, data, and models of the paper titled "DEPTWEET: A Typology for Social Media Texts to Detect Depression Severities" published in [Computers in Human Behavior](https://www.journals.elsevier.com/computers-in-human-behavior) (Q1, H-Index: 226, Impact Factor: ~9). 


[![arXiv](https://img.shields.io/badge/arXiv-2305.06595-b31b1b.svg)](https://arxiv.org/abs/2210.05372)
[![GoogleScholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=flat&logo=Google+Scholar&logoColor=white&color=gray&labelColor=4285F4)](https://tinyurl.com/3spp4bha)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=flat&logo=ResearchGate&logoColor=white&color=gray&labelColor=00CCBB)](https://www.researchgate.net/publication/363944652_DEPTWEET_A_typology_for_social_media_texts_to_detect_depression_severities)


# Data
Data folder contains tweet id's corresponding to severities of depression collected from Twitter. Owing to Twitter's policy on data sharing, we can not directly upload the dataset and are only restricted to sharing tweet-id's here. Users can rehydrate this dataset using <a href=https://github.com/DocNow/hydrator>hydrator</a> using the tweet-id's.  <br/>
In case of missing tweets or difficulties in extracting tweets, readers may fill up and sign the scanned copy of the Data Usage Agreement (DUA) available in this [link](https://drive.google.com/file/d/1hXmr680rKtftDNcdj26dkEnLNB8A0bWa/view?usp=sharing) and send to (mohsinulkabir@iut-dhaka.edu). Authors are committed to sharing the dataset in the shortest possible time once they receive the signed DUA. 
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
