# GT-6740-MachineLearning-FinalProject
Final Project files for ISYE 6740

These files pertain to the final project for ISYE 6740. Please read the problem statement below for an understanding of what I did for this proejct.

Problem Statement: A physician diagnoses breast tumors as benign or malignant before beginning treatment. Malignant tumors require immediate aggressive treatment since they have cancerous cells that can spread to other tissues in the body. Benign tumors require little if any treatment because they typically remain in the tissue that they originated from (breast in this study). Due to the vastly different treatment requirements between malignant and benign tumors, it is critical that physicians properly diagnose these tumor types before beginning treatment. 

Surgical biopsy is the gold standard in classifying breast tumors as benign or malignant because it has an accuracy that is close to 100%. The drawbacks of surgical biopsies however are invasiveness (requires large needle inserted into the breast), long procedure times, and costliness. A fine needle aspirate (FNA) biopsy is a less invasive and less costly procedure to diagnose tumors that involves extraction of fluid from the tumor and subsequent analysis of the nuclei within this fluid by a physician. The downside of an FNA biopsy however is poor accuracy relative to surgical biopsies, with reported accuracy metrics ranging from 65% to 98%.3
The dataset used for this study consisted of 569 breast tumor samples collected at University of Wisconsin hospitals.1,2 

The main goal of this analysis was to determine if machine-learning algorithms examined in ISyE 6740 could use FNA biopsy metrics to distinguish malignant vs. benign breast tumors with high accuracy. Fortunately, FNA biopsy metrics and surgical biopsy classification were available in this dataset, where the surgical biopsy results were assumed the true classification. The second goal of this study was to identify the feature variables that were most helpful in distinguishing malignant vs. benign tumors
