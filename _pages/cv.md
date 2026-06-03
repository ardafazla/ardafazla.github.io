---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

CV
======
[PDF Version](http://ardafazla.github.io/files/arda_fazla_cv.pdf)

Education
======
* **Doctor of Philosophy** - Electrical and Computer Engineering **(4.00/4.00)**, 2024-Present  
Purdue University - The Elmore Family School of Electrical and Computer Engineering - Indiana, US.  
**Advisor**: [Prof. Abolfazl Hashemi](https://abolfazlh.github.io)

* **Master of Science** - Electrical and Electronics Engineering **(3.91/4.00)**, 2021-2024  
Bilkent University - Faculty of Engineering - Ankara, Turkey.  
**Advisor**: [Prof. Süleyman Serdar Kozat](http://kilyos.ee.bilkent.edu.tr/~kozat/)

* **Bachelor of Science** - Electrical and Electronics Engineering **(3.61/4.00)**, 2017-2021  
Middle East Technical University - Faculty of Engineering - Ankara, Turkey.

Research Background & Interests
======
* Optimization: constrained/unconstrained optimization theory, multi-objective optimization
* Trustworthy Deep Learning: robustness, privacy, memorization
* Distributionally Robust Optimization: invariant learning, subpopulation shift, domain generalization

Publications
======

### Preprints
1. **A. Fazla**, E. Kaya, A. Upadhyay, A. Hashemi, _"Lower Bounds and Proximally Anchored SGD for Non-Convex Minimization Under Unbounded Variance"_, Under Review at NeurIPS 2026.  
   Available: [https://arxiv.org/abs/2604.16620](https://arxiv.org/abs/2604.16620)

2. A. Upadhyay, **A. Fazla**, A. Hashemi, _"Beyond Bounded Variance: Variance-Reduced Normalized Methods for Nonconvex Optimization under Blum-Gladyshev Noise"_, Under Review at NeurIPS 2026.  
   Available: [https://arxiv.org/abs/2605.15314](https://arxiv.org/abs/2605.15314)

### Conference Papers
1. **A. Fazla**, A. Hashemi, _"Mitigating Spurious Correlations with Memorization-Guided Dataset De-Biasing Selection"_, Uncertainty in Artificial Intelligence, 2026.  
   Available: [https://arxiv.org/abs/2606.02830](https://arxiv.org/abs/2606.02830)

2. K. G. Ince, A. Köksal, **A. Fazla**, A. A. Alatan, _"Semi-Automatic Annotation for Object Detection"_, Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV) Workshops, 2021, pp. 1233-1239.  
   Available: [https://doi.org/10.1109/ICCVW54120.2021.00143](https://doi.org/10.1109/ICCVW54120.2021.00143)

### Journal Papers
1. S. F. Tekin, **A. Fazla**, S. S. Kozat, _"Numerical Weather Forecasting using Convolutional-LSTM with Attention and Context Matcher Mechanisms"_, IEEE Transactions on Geoscience and Remote Sensing, 2024.  
   Available: [https://arxiv.org/abs/2102.00696](https://arxiv.org/abs/2102.00696)  
   Code: [https://github.com/sftekin/spatio-temporal-weather-forecasting](https://github.com/sftekin/spatio-temporal-weather-forecasting)

2. **A. Fazla**, M. E. Aydin, S. S. Kozat, _"Time-Aware and Context-Sensitive Ensemble Learning for Sequential Data"_, IEEE Transactions on Artificial Intelligence, 2023.  
   Available: [https://doi.org/10.1109/TAI.2023.3319308](https://doi.org/10.1109/TAI.2023.3319308)  
   Code: [https://github.com/ardafazla/context-time-aware-ensemble](https://github.com/ardafazla/context-time-aware-ensemble)

3. M. E. Aydin, **A. Fazla**, S. S. Kozat, _"Hybrid State Space-based Learning for Sequential Data Prediction with Joint Optimization"_, arXiv preprint arXiv:2309.10553, 2023.  
   Available: [https://arxiv.org/abs/2309.10553](https://arxiv.org/abs/2309.10553)  
   Code: [https://github.com/mustafaaydn/lstm-sx](https://github.com/mustafaaydn/lstm-sx)

4. **A. Fazla**, M. E. Aydin, S. S. Kozat, _"Joint Optimization of Linear and Nonlinear Models for Sequential Regression"_, Digital Signal Processing, Elsevier, 2022.  
   Available: [https://doi.org/10.1016/j.dsp.2022.103802](https://doi.org/10.1016/j.dsp.2022.103802)  
   Code: [https://github.com/ardafazla/jointoptimization](https://github.com/ardafazla/jointoptimization)

Professional Experiences
======

### Purdue University, Research Assistant  
_Advisor: Prof. Abolfazl Hashemi_  
_West Lafayette, IN_

**Stochastic Optimization**, _Aug 2025-Present_  
* Developed **PASTA** and **SAUCE**, two stochastic optimization frameworks for nonconvex learning under realistic noise assumptions, covering unbounded variance and Blum-Gladyshev noise. Established theoretical convergence guarantees and demonstrated their relevance to modern deep learning settings where classical bounded-variance assumptions fail.
* Currently investigating the optimization and generalization behavior of deep neural networks, with a focus on sharpness-aware training dynamics and adaptive scheduling.

**Trustworthy Deep Learning**, _Aug 2024-Present_  
* Proposed a two-stage coreset selection algorithm with the dual purpose of eliminating spurious correlations and reducing dataset size. The deployed product achieved up to **27%** improvement over standard ERM while utilizing only **10%** of the training data on benchmark datasets such as Waterbirds, CMNIST, MetaShift, and UrbanCars, while also outperforming state-of-the-art invariant learning methods.
* Currently studying the training dynamics of deep learning models, with a focus on how loss landscape sharpness interacts with common training interventions and influences memorization and generalization, particularly in out-of-distribution settings.

### Databoss Security & Analytics Inc., Data Scientist  
_Ankara, Turkey_

**Hourly Wind Energy Prediction**, _Jun 2023-May 2024_  
* Predicted the hourly energy data of multiple wind turbines in Turkey and Europe, showing chaotic and nonstationary behavior in multiple regions.
* Developed a large-scale ML framework consisting of various adaptive feature construction and selection methods with models such as deep learning models, machine learning models, statistical models, and state-of-the-art ensembling techniques. The deployed product increased short-term forecasting accuracy by an average of **21%** and long-term forecasting accuracy by an average of **8%**.

**Natural Gas Demand Prediction**, _Aug 2021-May 2023_  
* Predicted daily international natural gas demand in Turkey, consisting of nonstationary multivariate time series from multiple sources.
* Developed a large-scale ML framework tailored toward a specific customer profile, where predictions are obtained based on key indicators automatically extracted from the data itself and/or user-given side information. The constructed framework was deployed to various natural gas production companies.

### METU Center for Image Analysis (OGAM), Machine Learning Engineer  
_Ankara, Turkey_

**UAV Small Object Detection and Tracking**, _Jun 2020-Jul 2021_  
* Developed a Python application for real-time small target tracking by leveraging temporal data derived from object detector outputs, achieving **6%** superior performance over the widely known YOLOv3 algorithm.
* Constructed a novel multi-hypothesis tracking algorithm with an annotation tool for semi-automatic correction of mislabeled UAV data. The deployed product decreased the total mislabeled data in various datasets by an average of **13%**.

Academic Awards
======

### Elmore Family School of Electrical and Computer Engineering, Purdue University  
_2024-2029_  
* Awarded the highly competitive and prestigious Elmore Fellowship Award for my graduate studies, given only to the most outstanding applicants.

### Turk Telekom & Information and Communication Technologies Authority  
_2023-2024_  
* Awarded 5G and Beyond Joint Graduate Support Programme, a merit-based fellowship of monthly stipend during M.Sc.

### Scientific and Technological Research Council of Turkey  
_2021-2023_  
* Awarded Directorate of Science Fellowships and Grant Programme, a merit-based monthly stipend and accommodation support during M.Sc.

* Received the **373rd** rank among 2M high school graduates in the University Entrance Examination.

* Received the **11th** rank among 0.2M university graduates in ALES, the National GRE.

Academic Duties
======

### Reviewer Duties
**Conferences:** ICLR '25-'26, NeurIPS '26, AISTATS '26, AAAI '25  
**Journals:** IEEE TAI '25, IEEE IOT '24-'25

### Teaching Assistantship
**Electrical and Electronics Engineering, Bilkent University**, _2021-2024_  
* EEE321 Signals and Systems
* EEE202 Circuit Theory
* MATH255 Probability and Statistics

Software Skills
======
* **Python:** Professional research and industrial experience based on machine learning. High knowledge and experience in libraries such as _PyTorch_, _TensorFlow_, _Pandas_, _NumPy_, and _Scikit-Learn_. I have experience with Docker and Git via industrial projects.
* **MATLAB:** Professional research experience in signal processing and computer vision. Used for projects during courses, research, and internships.
* **R:** Intermediate-level experience, employed during research based on time-series forecasting using statistical models.
* **C/C++:** Intermediate experience in various course projects.

Languages
======
_Turkish:_ Native  
_English:_ Conversationally Fluent [TOEFL IBT 108/120 (October 19, 2022)]