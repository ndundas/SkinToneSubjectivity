# The Subjectivity of Skin Tone: Evaluating Patient and Annotator Agreement Across Scales

This repository contains code used for analyzing the reliability of skin tone annotations using various scales (e.g., Fitzpatrick and Monk) in our paper. The project assesses patient and annotator agreement to explore the subjectivity of skin tone classification in healthcare and research contexts.

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Dataset Information](#dataset-information)
3. [Methods and Analysis](#methods-and-analysis)
4. [Results and Visualizations](#results-and-visualizations)
5. [How to Use](#how-to-use)

---

## Project Overview

This study focuses on:
- Evaluating inter-rater reliability and agreement across three annotators.
- Comparing patient self-assessments with annotator judgments for skin tone.
- Utilizing statistical measures such as Fleiss' Kappa, Kendall's W, and Cronbach's Alpha to assess reliability.
- Exploring the role of skin tone scales (e.g., Fitzpatrick and Monk) in capturing diversity.

---

## Dataset Information

The dataset includes:
- **Annotator Data**: Scores and confidence ratings provided by three annotators across multiple images per patient.
- **Patient Data**: Self-reported skin tone classifications and demographic information.
- **Skin Tone Scales**: Includes Fitzpatrick and Monk scores, linked to metadata for comprehensive analysis.

---

## Methods and Analysis

The notebook follows these key steps:
1. **Data Loading**: Import annotator and patient data.
2. **Preprocessing**: Clean, normalize, and structure data for analysis.
3. **Statistical Tests**:
    - Inter-rater reliability (e.g., Fleiss' Kappa, Kendall's W).
    - Internal consistency (e.g., Cronbach's Alpha).
    - Agreement and bias using Bland-Altman plots.
4. **Visualization**:
    - Box plots, violin plots, and scatter plots to explore data trends and variability.

---

## Results and Visualizations

The project generates:
- Visualizations of agreement and discrepancies in skin tone classification.
- Statistical summaries showcasing the reliability of each scale.
- Insights into annotator biases and the subjectivity of skin tone assessment.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/username/skin-tone-study.git
   ```

2. Navigate to the directory: 
  ```bash
  cd skin-tone-study
  ```

3. Install the dependencies: 
  ```bash
  pip install -r requirements.txt
  ```

4. Run the Notebook: 
  ```bash
  jupyter notebook FINAL_SkineToneData.ipynb
  ```