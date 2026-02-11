# Mapping the American Literary Canon (1850–2006)
### An Exploratory Data Analysis within the Digital Humanities Framework

## Overview

This repository presents an **Exploratory Data Analysis (EDA)** of a curated dataset consisting of 50 canonical works of American literature, spanning the period **1850–2006**.  

The project is situated within a **Digital Humanities (DH)** framework and integrates numerical, categorical, and textual data in order to explore literary production, reception, and thematic patterns.

This study constitutes the **final project for the Data Analytics course** of the **MSc Digital Humanities programme**, jointly offered by the National and Kapodistrian University of Athens, the University of Cyprus, and the ATHENA Research Centre.

---

## Research Objectives

The project addresses the following research questions:

- Genre composition and diversity within the American literary canon
- Temporal distribution and publication trends
- Reader evaluation and reception patterns
- The relationship between textual length and reader ratings
- The influence of publication date on reader evaluation
- Dominant lexical and thematic patterns in textual descriptions

---

## Dataset Description

The dataset consists of **50 representative works** of American literature and spans more than one and a half centuries (1850–2006). Each observation corresponds to a single literary work and is described by **eight variables**, encompassing categorical, numerical, and textual data.

### Dataset Variables

| Variable Name       | Data Type     | Description |
|--------------------|--------------|-------------|
| title              | Categorical  | Full title of the literary work |
| author             | Categorical  | Full name of the author |
| year               | Numerical    | Year of original publication |
| pages              | Numerical    | Length of the work measured in number of pages |
| category            | Categorical  | Specific literary genre or form |
| literary_period     | Categorical  | Broader literary movement or historical period |
| average_rating      | Numerical    | Average reader rating (scale 1.0–5.0) |
| description         | Textual      | Extended textual summary of plot and themes |

### Data Quality

- No missing values were detected across any variables  
- No duplicate records were found  
- All observations were retained, including outliers, due to their canonical and historical significance  

These characteristics ensure **data completeness, consistency, and analytical reliability**.

---

## Methodology

### Exploratory Data Analysis (EDA)
- Descriptive statistics and distribution analysis
- Outlier detection using the Interquartile Range (IQR) method
- Visualisations including:
  - Horizontal bar plots
  - Box plots
  - Histograms
  - Pareto charts
  - Treemaps

### Statistical Modelling
- **Simple Linear Regression**  
  Examining the relationship between textual length (pages) and average reader rating
- **Multiple Linear Regression**  
  Incorporating both textual length and publication year as predictors of reader rating

All models are applied **exploratorily**, with emphasis on interpretive insight rather than predictive accuracy.

### Text Analysis
- Text preprocessing pipeline:
  - Lowercasing
  - Removal of punctuation and non-alphabetic tokens
  - Stopword elimination
  - Lemmatisation
- Frequency-based NLP analysis
- Extraction and visualisation of the **40 most frequent lemmas** in work descriptions

---

## Key Findings

- The dataset exhibits **high genre diversity** with no single dominant literary category
- Publication dates are strongly concentrated in the **twentieth century**
- Textual length alone has **minimal explanatory power** for reader ratings
- Publication year contributes moderately to reader evaluation
- Lexical analysis highlights dominant themes related to narrative structure, social relations, identity, and historical context

Overall, the project demonstrates the value of computational methods as **exploratory and reflexive tools** within Digital Humanities research.

---

## Repository Structure

├── CODE_Mapping_the_American_Literary_Canon_1850_2006.ipynb

├── README_Mapping_the_American_Literary_Canon_1850_2006.md

├── REPORT_Mapping_the_American_Literary_Canon_1850_2006.pdf

---

## License

**Academic Use – Coursework License**

This repository contains the final project for the **Data Analytics course** of the **MSc Digital Humanities programme**.  
The material is intended **exclusively for academic, educational, and research purposes**.  
Reuse, modification, or redistribution for commercial purposes is not permitted without explicit permission from the author.

---

## Author

**Constantinos Panayi**  
MSc Digital Humanities  
National and Kapodistrian University of Athens · University of Cyprus · ATHENA Research Centre
