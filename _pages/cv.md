---
layout: cv
title: "CV"
permalink: /cv/
author: "jocelynnwj"
---

{% include base_path %}

**Data Scientist | MS in Applied Data Science @ USC Viterbi**  
Data science enthusiast with a product mindset and a focus on real-world impact. Experienced in LLM evaluation, data labeling, machine learning, and building AI-driven tools that are both intelligent and user-friendly.

Education
======
**University of Southern California**  
Master of Science in Applied Data Science, Viterbi School of Engineering  
*Jan. 2024 to Dec. 2025 (Expected)*  
  - **Relevant Coursework:** Deep Learning and Its Applications, Machine Learning for Data Science, Foundations and Applications of Data Mining, User Experience Design & Strategy

**University of California, Riverside**  
Bachelor of Science in Business Administration, Concentration in Business Analytics  
*Jul. 2019 to Dec. 2022*  
  - **GPA:** 3.76/4.0  
  - **Academic Highlights:** Cum Laude | Dean's Honor List for 5 Quarters

Work Experience
======
**Fusion AI – Data Scientist Intern, AI Innovation Team**  
*Glen Allen, VA (Remote) | Jun. 2025 to Aug. 2025*
  - Developed and deployed ML/DL models to address real-world business problems, leveraging both structured and unstructured data (text, images, user logs).
  - Conducted A/B testing and statistical validation to evaluate model performance, identifying optimization opportunities and improving business KPIs.
  - Fine-tuned LLMs and foundation models for specific downstream tasks, collaborating cross-functionally with PMs, engineers, and designers to translate business needs into data-driven solutions.
  - Performed LLM fine-tuning for downstream tasks; collaborated with PMs, engineers, and designers for business-driven solutions.

**M-Joys Tech – Data Analyst / AI Intern**  
*Hangzhou, Zhejiang, China | Jun. 2024 to Aug. 2024*
  - Improved model evaluation by generating 30,000+ labeled AI voice interaction records for LLM evaluation and response validity.
  - Conducted data cleaning with SQL and Python (Pandas, Regex) to achieve 97%+ data consistency; validated data via schema checks and audits.
  - Analyzed response failures and improved classification accuracy by 20% through prompt engineering and LLM fine-tuning using PyCharm.

Academic Projects and Research
======
**Yelp Recommendation System Optimization – DSCI 553**  
*Mar. 2025 to May. 2025*
  - Built a hybrid recommender system using Spark RDD, Python, and XGBoost to process 100,000+ user-business review records.
  - Improved prediction accuracy (RMSE=0.978) by applying cross features and feature engineering on user activity, popularity, and time-based interactions.
  - Designed a scalable batch pipeline for regression modeling, optimizing runtime under limited memory constraints.

**Plant Leaf Image Classification Using SAM and Vision Transformers – CSCI 566**  
*Oct. 2024 to Dec. 2024*
  - Fine-tuned ViT and ResNet50 models on 20,000+ segmented images using Segment Anything Model (SAM) to improve plant disease classification.
  - Applied data augmentation (Gaussian blur, rotation) to enhance robustness across 15 categories; achieved 99.95% (ViT) and 99.81% (ResNet50) top-1 accuracy.
  - Validated model generalization with ROC-AUC, precision, recall, F1-score, maintaining ≥0.99 under 10% noise levels.

**Job Management Blog Database Management System – DSCI 551**  
*Feb. 2024 to May. 2024*
  - Built an end-to-end data pipeline to scrape 800+ LinkedIn job listings using Python, Selenium, and store into MySQL with optimized schema design.
  - Improved query speed (~0.2s/query) and automated ingestion for downstream analysis.
  - Developed a full-stack job board system with Django MVC, boosting server response efficiency by 40% and maintaining >95% UI stability.

**Cryptocurrency Project – UCR School of Business, Research Assistant**  
*Mar. 2021 to Dec. 2021*
  - Summarized 40+ peer-reviewed papers on blockchain and digital asset markets to build cross-asset financial models.
  - Processed and cleaned 20,000+ Yahoo Finance entries using Python (Pandas, Matplotlib), achieving 95%+ data integrity.
  - Delivered insights into crypto-ETF relationships via regression and correlation analysis, identifying 0.72 Pearson correlation between BTC and ARK Innovation ETF.

Skills
======
- **Computer / Data Skills:** Python, SQL (Certified: Coursera SQL for Data Science), Pandas, NumPy, scikit-learn, Matplotlib, TensorFlow, PyTorch
- **Other Tools & Skills:** Git, Jupyter Notebook, Tableau, Google Colab
- **Strengths:** Data preprocessing, machine learning model development, statistical analysis, experiment design, dashboarding, cross-functional communication

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
  
Talks
======
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html  %}
{% endfor %}</ul>
  
Teaching
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
  
Service and Leadership
======
- Open to leadership, volunteering, and collaboration opportunities in data science and AI communities.
