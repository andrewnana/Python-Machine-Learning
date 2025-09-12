# Python-Machine-Learning-Thyroid-Cancer





\#### Background



Thyroid cancer is one of the most common endocrine malignancies and is on the rise in both the US and globally \[^1] This cancer generally has a favorable prognosis but still carries a significant risk of recurrence. Traditional statistical methods are commonly used to assess the relationships between clinical, pathological, and demographic predictors and thyroid cancer recurrence, but usually rely on predefined assumptions about variable relationships (independence of observations, homoscedasticity, etc.). Machine learning (ML) techniques can provide more flexible approaches by adaptively learning patterns directly from the data. This can enable more accurate predictions, especially in complex, high-dimensional clinical datasets, and more importantly, allow prediction on new data.



\#### Purpose

&nbsp; 

This project investigates recurrence in thyroid cancer patients using both statistical logistic regression and machine learning methods. With the logistic regression, we explore the relationship between several “causes” and the likelihood of recurrence. We then shift to machine learning techniques for risk stratification and evaluate the predictive accuracy of the following algorithms: 



\- logistic regression,

\- K-Nearest Neighbors (KNN),

\- Support Vector Machines (SVM),

\- Decision Tree,

\- Random Forest, and,

\- Artificial Neural Networks (ANN)



These algorithms are evaluated based on the following performance metrics:



\-	Sensitivity (ability to correctly identify patients who experience recurrence), 

\-	Specificity (ability to correctly identify those who do not), 

\-	Positive Predictive Value (PPV) (the probability that predicted recurrences are true), 

\-	Negative Predictive Value (NPV) (the probability that predicted non-recurrences are true),

\-	Area Under the ROC curve (AUC) (overall discriminatory ability),

\-	Accuracy (the proportion of correct classifications across all cases).



\#### Data Source and initial study



The dataset in this study is publicly accessible and was generously provided by Borzooei et al., who published their original findings in 2024 \[^2]. Thyroid cancer patients were followed prospectively for at least 10 years, to assess whether their cancer recurred, and  several demographic, clinical and pathological measures were collected. In total 383 patients were included, which is a relatively small sample size. A full description of the study design can be consulted in the published paper. While the study is longitudinal in design, it does not provide  time-to-event information which prevents the use of appropriate ML techniques tailored for longitudinal data \[^3]. The lack of this crucial piece of information coerces us to focus instead on models that apply to binary outcomes, such as those cited above. 



\#### Disclaimer

&nbsp; 

This project does not aim to replicate the original study by Borzooei et al. Rather, it demonstrates alternative analytic strategies for examining the same problem. Given these differences in methodological choices and assumptions, results were not expected to mirror those of the original study. 

This analysis is intended for educational and research purposes only and has not been peer-reviewed. While efforts have been made to ensure the accuracy of the methods and results, the author does not guarantee the correctness or completeness of the analysis. The author bears no responsibility or liability for any errors, omissions, or outcomes resulting from the use of this material. Use at your own discretion.







\[^1]: Kitahara CM, Schneider AB. Epidemiology of Thyroid Cancer. Cancer Epidemiol Biomarkers Prev. 2022 Jul 1;31(7):1284-1297. doi: 10.1158/1055-9965.EPI-21-1440. PMID: 35775227; PMCID: PMC9473679.



\[^2]: Borzooei S, Briganti G, Golparian M, Lechien JR, Tarokhian A. Machine learning for risk stratification of thyroid cancer patients: a 15-year cohort study. Eur Arch Otorhinolaryngol. 2024 Apr;281(4):2095-2104. doi: 10.1007/s00405-023-08299-w. Epub 2023 Oct 30. PMID: 37902840.



\[^3]: Cascarano, A., Mur-Petit, J., Hernández-González, J. et al. Machine and deep learning for longitudinal biomedical data: a review of methods and applications. Artif Intell Rev 56 (Suppl 2), 1711–1771 (2023). https://doi.org/10.1007/s10462-023-10561-w

