---
title: "Leveraging GPT-4 for Identifying Cancer Phenotypes in Electronic Health Records: A Performance Comparison between GPT-4, GPT-3.5-turbo, Flan-T5 and spaCy’s Rule-based & Machine Learning-based methods. Submitted to JAMIA Open. Bhattarai, K., Oh, I.Y, Sierra J.M., Tang, J., Payne, P.R.O, Abrams, Z.B, Lai, A.M.
(2024)."
collection: publications
permalink: /publication/bibliography-1
date: 2024-5-1
venue: 'JAMIA Open'

paperurl: 'https://www.biorxiv.org/content/10.1101/2023.09.27.559788v2'
---

Accurately identifying clinical phenotypes from Electronic Health Records (EHRs) provides additional insights into patients’ health, especially when such information is unavailable in structured data. This study evaluates the application of OpenAI’s Generative Pre-trained Transformer (GPT)-4 model to identify clinical phenotypes from EHR text in non-small cell lung cancer (NSCLC) patients. The goal was to identify disease stages, treatments and progression utilizing GPT-4, and compare its performance against GPT-3.5-turbo, Flan-T5-xl, Flan-T5-xxl, and two rule-based and machine learning-based methods, namely, scispaCy and medspaCy.Phenotypes such as initial cancer stage, initial treatment, evidence of cancer recurrence, and affected organs during recurrence were identified from 13,646 records for 63 NSCLC patients from Washington University in St. Louis, Missouri. The performance of the GPT-4 model is evaluated against GPT-3.5-turbo, Flan-T5-xxl, Flan-T5-xl, medspaCy and scispaCy by comparing precision, recall, and micro-F1 scores.GPT-4 achieved higher F1 score, precision, and recall compared to Flan-T5-xl, Flan-T5-xxl, medspaCy and scispaCy’s models. GPT-3.5-turbo performed similarly to that of GPT-4. GPT and Flan-T5 models were not constrained by explicit rule requirements for contextual pattern recognition. SpaCy models relied on predefined patterns, leading to their suboptimal performance.GPT-4 improves clinical phenotype identification due to its robust pre-training and remarkable pattern recognition capability on the embedded tokens. It demonstrates data-driven effectiveness even with limited context in the input. While rule-based models remain useful for some tasks, GPT models offer improved contextual understanding of the text, and robust clinical phenotype extraction.
