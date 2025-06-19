# Inclusive Jobs: Detecting Gender Biases in Job Advertisements

Language matters. In male-dominated fields like IT and finance, the language in job advertisements can unintentionally discourage women from applying. This prototype uses interpretable natural language processing (NLP) techniques to detect and explain the gendered appeal of job ads.

Built for the _Decoding Gender Bias in Hiring_ challenge at [Hack4Her 2025](https://hack4her.org/information), sponsored by [Randstad Digital](https://www.randstad.com/hr-services/digital/).

---

## Table of Contents
- [Features](#Features)
- [Datasets](#Datasets)
- [Results](#Results)
- [Reflections](#Reflections)
- [Tech Stack](#Tech-Stack)
- [The Team](#The-Team)

---

## Features

### TF-IDF
Explanation.

### Classification and regression models
Explanation.

### Word clouds
visualizing inclusive vs. exclusive language

### LIME-based local explanations for job advertisements
Explanation.

---

## Datasets
| Dataset | Description | Size | Language(s) |
|---------|-------------|------|-------------|
| `synthetic_vacancies` | Synthetic ads with known `women_proportion` labels | 366 ads | English |
| `labeled_vacancies` | Real-world job ads with `women_proportion` labels from application data | 2,375 ads | English, Dutch |
| `unlabeled_vacancies` | Real job ads with no applicant proportion data | 394 ads | English, Dutch, French, German |

---

## Results
Visualizations: word cloud, LIME screenshots

---

## Reflections
- note: turn all of this into a blogpost and link it here?
- extent that this tool can help improve job ads for male-dominated jobs
- understanding what language is considered "male-coded" and "female-coded" and why
- our tools and techniques chosen to maximise simplicity and out-of-the-box usage
- what we would do given more time: explore what positions/companies attract more men; sentence transformers for more robustness
- challenges of our data: monolingual synthetic
  - multilingual labelled and unlabelled
  - balanced, small synthetic dataset
  - unbalanced, large dataset

---

## Tech Stack

---

## About Hack4Her
[Hack4Her](https://hack4her.org/information) is the only female-focused student hackathon in the Netherlands. The fourth annual took place over the weekend of **June 13-15, 2025**.

We participated in the _Decoding Gender Bias in Hiring_ challenge sponsored by [Randstad Digital](https://www.randstad.com/hr-services/digital/).

---

## The Team
Emily Nadworna, Inge Martina, Ruhi Soni, Sharise Capriles

---
