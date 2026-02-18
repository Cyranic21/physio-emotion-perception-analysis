
1. Objectivation of User Perception via Physiological Signals

Correlation between subjective emotional ratings and heart rate data (DEAP-inspired study)

2. Project Overview

This project explores the relationship between subjective emotional perception and objective physiological signals, inspired by the DEAP dataset framework.
The objective is to assess whether emotional self-reports can be partially explained or predicted using heart rate data, following a rigorous data-driven sensory science approach.

This work is positioned at the intersection of:

Affective computing

Sensory science

Human-centered data analysis

VR / XR user experience research

3. Research Question

Can subjective emotional intensity be explained or predicted from physiological signals such as heart rate?

4. Dataset

Open physiological-emotion dataset (heart rate + emotion ratings)

Inspired by the DEAP experimental paradigm

Variables:

HeartRate (objective physiological signal)

EmotionScore (subjective self-reported emotional intensity)

EmotionLabel (categorical emotional state)

6. Methodology

Exploratory Data Analysis

Distribution of heart rate values

Distribution of subjective emotion scores

Emotion category comparison

Statistical Analysis

Pearson and Spearman correlations

Interpretation of weak-to-moderate correlations

Visualization

Boxplots by emotion category

Scatter plots (Heart Rate vs Emotion Score)

Correlation heatmap

Predictive Modeling

Linear regression

Ridge regression

Model evaluation (RMSE, R²)

7. Key Results

Heart rate shows a statistically meaningful but partial relationship with emotional self-reports

Predictive performance remains moderate, reflecting the complexity of emotional perception

Results highlight the importance of multimodal physiological signals for improved prediction

8. Scientific Interpretation

This project demonstrates that physiological data alone cannot fully capture subjective perception, but they provide valuable explanatory insight when analyzed rigorously.
The approach emphasizes interpretability, scientific validity, and reproducibility rather than raw predictive performance.

9. Tools & Technologies

Python

pandas, numpy, scipy

scikit-learn

matplotlib, seaborn

Jupyter Notebook

10. Perspectives

Integration of additional physiological signals (EDA, HRV, EEG)

Extension to immersive VR/XR environments

Multimodal affective modeling

📂 Repository Structure
├── notebook.ipynb
├── data/
├── figures/
└── README.md