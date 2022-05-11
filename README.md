# Medical Cost Personal Dataset
A simple data analysis of medical cost for people of different age, gender, with children and smoking habits. 

## Content
---

**Columns**
* age: age of primary beneficiary
* sex: insurance contractor gender, female, male
* bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height,
* objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
* children: Number of children covered by health insurance / Number of dependents
* smoker: Smoking
* region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.
* charges: Individual medical costs billed by health insurance
---

## Data sources
The data is available for download at kaggle.com at Miri Choi's profile: [data link](https://www.kaggle.com/datasets/mirichoi0218/insurance)

This data is outdated and there is no way to validate its quality. Although, the data is clean and has no empty values. 

---

## Manipulation of data
The data was relatively clean, just a few ajustments were made. 

One duplicated row was removed and couple of outliers. The outliers were couple of people who had a very high Body Mass Index (BMI), very out of context. 

For futher information, please access the jupyter notebook file: [click here](https://github.com/rogercarelli/Medical_Cost_Personal_Dataset/blob/main/Analyses_v2.ipynb)

---

## Data visualization
As GitHub does not show the plots made in jupyter notebook, you can find a final dashboard version at Tableau. 
[Click here to see the dashboard](https://public.tableau.com/app/profile/roger5654/viz/MedicalCost_16522935532250/Dashboard1?publish=yes)
