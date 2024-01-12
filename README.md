# HMS - Harmful Brain Activity Classification
![title card](assets/title-card.png)

[Challenge Link](https://www.kaggle.com/competitions/hms-harmful-brain-activity-classification)

[Variable Description Link](https://docs.google.com/spreadsheets/d/1YQVs89pAXDtdoIE6Exb0LL8spjBac2ubjy1KlcUxBQs/edit?usp=sharing)

## Description of Challenge
The goal of this competition is to detect and classify seizures and other types of harmful brain activity. You will develop a model trained on electroencephalography (EEG) signals recorded from critically ill hospital patients.

Your work may help rapidly improve electroencephalography pattern classification accuracy, unlocking transformative benefits for neurocritical care, epilepsy, and drug development. Advancement in this area may allow doctors and brain researchers to detect seizures or other brain damage to provide faster and more accurate treatments. 

From stethoscopes to tongue depressors, doctors rely on many tools to treat their patients. Physicians use electroencephalography with critically ill patients to detect seizures and other types of brain activity that can cause brain damage. You can learn about how doctors interpret these EEG signals in these videos:
EEG Talk - ACNS Critical Care EEG Terminology 2021 (Part 1) (Part 2) (Part 3) (Part 4) (Part 5)

Currently, EEG monitoring relies solely on manual analysis by specialized neurologists. While invaluable, this labor-intensive process is a major bottleneck. Not only can it be time-consuming, but manual review of EEG recordings is also expensive, prone to fatigue-related errors, and suffers from reliability issues between different reviewers, even when those reviewers are experts.

Competition host Sunstella Foundation was created in 2021 during the COVID pandemic to help minority graduate students in technology overcome challenges and celebrate their achievements. These students are vital to America's technology leadership and diversity. Through workshops, forums, and competitions, the Sunstella Foundation provides mentorship and career advice to support their success.

Sunstella Foundation is joined by Persyst, Jazz Pharmaceuticals, and the Clinical Data Animation Center (CDAC), whose research aims to help people preserve and enhance brain health.

Your work in automating EEG analysis will help doctors and brain researchers detect seizures and other types of brain activity that can cause brain damage, so that they can give treatments more quickly and accurately. The algorithms developed in this contest may also help researchers who are working to develop drugs to treat and prevent seizures.

There are six patterns of interest for this competition: seizure (SZ), generalized periodic discharges (GPD), lateralized periodic discharges (LPD), lateralized rhythmic delta activity (LRDA), generalized rhythmic delta activity (GRDA), or “other”. Detailed explanations of these patterns are available here.

The EEG segments used in this competition have been annotated, or classified, by a group of experts. In some cases experts completely agree about the correct label. On other cases the experts disagree. We call segments where there are high levels of agreement “idealized” patterns. Cases where ~1/2 of experts give a label as “other” and ~1/2 give one of the remaining five labels, we call “proto patterns”. Cases where experts are approximately split between 2 of the 5 named patterns, we call “edge cases”.

## Organisations
<img src="assets/hms_logo.png" width="400">

- [Harvard Medical School](https://hms.harvard.edu/) A preeminent institution of medical education and research, renowned globally for its advanced academic rigor, groundbreaking discoveries in healthcare, and commitment to shaping the future of medicine through its distinguished faculty, diverse student body, and extensive network of hospitals and research centers.

<img src="assets/CCEMRC-logo.png" width="400">

- [Critical Care EEG Monitoring Research Consortium (CCEMRC)](https://www.acns.org/research/critical-care-eeg-monitoring-research-consortium-ccemrc) Provided the labels for model training and evaluation, and to others who contributed to the scientific work that enabled this competition.


## Team
- Shaw Chifamba - (Lead, Machine Learning/Stats Analysis) [![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/shawbc/)
- Kacper Buksa - (Data Analytics) [![Linkedin](https://i.stack.imgur.com/gVE0j.png) LinkedIn](https://www.linkedin.com/in/kacper-buksa/)
