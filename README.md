# AIT582-Project-Fall25-DREAM

Metadata analytics for Disaster Recovery — Fall 2025


DREAM : Disaster Recovery and Emergency Allocation using Metadata
*using State-of-the-Art Technology for Resource Transparency*

**Website:** https://mason.gmu.edu/~knirmalk/ait582.html

**Abstract:**
This project examines how large-scale metadata analytics can improve transparency and efficiency within FEMA’s Public Assistance (PA) program, which funds disaster recovery across the United States. Using over 700,000 nationwide PA project records, we engineered key metadata—such as project size, applicant type, incident type, workflow stage, and a derived lag days metric—to uncover geographic funding disparities, processing delays, and predictors of project complexity. Our analysis shows that PA funding is highly concentrated by state and disaster type, with substantial inequities even after normalization. We also found that large projects experience significantly longer processing times, with median delays exceeding 600 days. Machine learning models, including Logistic Regression, Decision Tree, and tuned Random Forests, demonstrated that metadata alone can reliably distinguish large from small projects, revealing strong predictive signals such as lag days, mitigation amounts, and workflow indicators. These findings highlight the potential of metadata-driven analytics to support more equitable, transparent, and timely disaster recovery operations.

TEAM #4 : 

*Contributed by :* 

* Md Hasan Ullad Sadi

* Keerthanyaa Nirmalkumar



Directory Structure:
```
AIT582-DL1/
├─ data/
│  ├─ raw/          # your JSON drops here (read-only)
│  └─ cleaned/      # cleaned CSV/Parquet outputs
├─ notebooks/
│  ├─ 00_Prelim-Analysis.ipynb    # load + schema + missingness +  EDA
│  ├─ 01_ingestion_&_RQ_analysis.ipynb      # RQ1 + RQ2 + RQ3 
│  ├─ 03_fine-tune-confidence.ipynb          # H2 stats + H3 
│  ├─ distribution-of-project-sizes.png
│  ├─ distribution-of-top10-states.png
│  ├─ incident-types-by-total-obligated-funding.png
│  ├─ total-funding-by-project-size.png
│  └─ fema_choropleth_by_disaster_type.html
├─ .gitignore
└─ README.md

```


**Research Questions**

**RQ1:** Do obligated funding allocations under FEMA’s PA
program vary systematically across states and disaster types?

**RQ2:** Are smaller PA projects processed more quickly than
larger projects, as measured by the time between disaster
declaration and first obligation (lag days)?

**RQ3:** Can project-level metadata be used to accurately
predict FEMA project size categories (small vs. large) using
machine-learning models?

**References**

[1] K. Nirmalkumar and M. Ullad Sadi, "AIT 582 Project Website," George Mason University, 2025. [Online]. Available: https://mason.gmu.edu/~knirmalk/ait582.html. Accessed: Nov. 30, 2025.

[2] "Preprocessing data," *scikit-learn Documentation*, [Online]. Available: https://scikit-learn.org/stable/modules/preprocessing.html. Accessed: Nov. 30, 2025.

[3] "Logistic regression," *scikit-learn Documentation*, [Online]. Available: https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression. Accessed: Nov. 30, 2025.

[4] "Issue #21755: Hidden attribute is not working in HTML repr of estimators," *scikit-learn/scikit-learn* GitHub repository, [Online]. Available: https://github.com/scikit-learn/scikit-learn/issues/21755. Accessed: Nov. 29, 2025.

[5] "Troubleshooting Jupyter kernel crashes in VS Code," Microsoft, [Online]. Available: https://aka.ms/vscodeJupyterKernelCrash. Accessed: Nov. 29, 2025.

[6] "pandas documentation," The pandas development team, [Online]. Available: https://pandas.pydata.org/docs/. Accessed: Dec. 1, 2025.

[7] "Installation," *pandas*, [Online]. Available: https://pandas.pydata.org/docs/getting_started/install.html. Accessed: Dec. 1, 2025.

[8] "NumPy documentation," NumPy Developers, [Online]. Available: https://numpy.org/doc/stable/. Accessed: Dec. 1, 2025.

[9] "Installing scikit-learn," *scikit-learn Documentation*, [Online]. Available: https://scikit-learn.org/stable/install.html. Accessed: Nov. 28, 2025.

[10] "Matplotlib documentation," Matplotlib Developers, [Online]. Available: https://matplotlib.org/stable/index.html. Accessed: Dec. 2, 2025.

[11] "Installing Matplotlib," *Matplotlib*, [Online]. Available: https://matplotlib.org/stable/install/index.html. Accessed: Dec. 2, 2025.

[12] "Seaborn documentation," M. Waskom et al., [Online]. Available: https://seaborn.pydata.org/. Accessed: Nov. 27, 2025.

[13] "Installation," *seaborn*, [Online]. Available: https://seaborn.pydata.org/installing.html. Accessed: Nov. 27, 2025.

