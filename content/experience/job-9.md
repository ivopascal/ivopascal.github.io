---
date: 2026-03-04T00:00:00+01:00
draft: false
title: ""
jobTitle: "The Challenge of Out-Of-Distribution Detection in Motor Imagery BCIs"
location: "Merlijn Quincent Mulder, Matias Valdenegro-Toro, Andreea Ioana Sburlea, Ivo Pascal de Jong"
company: "arXiv preprint"
duration: "2026"
companyLogo: ""

---
*Abstract*: Machine Learning classifiers used in Brain-Computer Interfaces make classifications based on the distribution of data they were trained on. When they need to make inferences on samples that fall outside of this distribution, they can only make blind guesses. Instead of allowing random guesses, these Out-of-Distribution (OOD) samples should be detected and rejected. We study OOD detection in Motor Imagery BCIs by training a model on some classes and observing whether unfamiliar classes can be detected based on increased uncertainty. We test seven different OOD detection techniques and one more method that has been claimed to boost the quality of OOD detection. Our findings show that OOD detection for Brain-Computer Interfaces is more challenging than in other machine learning domains due to the high uncertainty inherent in classifying EEG signals. For many subjects, uncertainty for in-distribution classes can still be higher than for out-of-distribution classes. As a result, many OOD detection methods prove to be ineffective, though MC Dropout performed best. Additionally, we show that high in-distribution classification performance predicts high OOD detection performance, suggesting that improved accuracy can also lead to improved robustness. Our research demonstrates a setup for studying how models deal with unfamiliar EEG data and evaluates methods that are robust to these unfamiliar inputs. OOD detection can improve the overall safety and reliability of BCIs.

[Open Access Link](https://doi.org/10.48550/arXiv.2603.13324)