# Complex-Odor
The goal of this study is to prevent  the occurrence of complex odor using odor substances.
- https://doi.org/10.3390/app12062826
- https://doi.org/10.3390/app122412943

### The data information is as follows:
  - Response variable: Complex odor
  - Explanatory variables:
    - Ammonia
    - Sulfur compounds: Hydrogen Sulfide, Methyl mercaptan, Dimethyl sulfide, Dimethyl disulfide
    - Volatile Organic compounds: Acetic acid , Propionic acid, Butyric acid, Iso-Butyric acid, Valeric acid, Iso-Valeric aic, Phenol, para-Cresol, Indole, Skatole
    - Categorical variables(only study2): season, spot


### This study consists of two parts.

- The study1 compares 126 pipelines for an optimal prediction model pipeline. In addition, Correlation analysis, PCA and Feature importance are performed.\
  (**Data special note: High missing rate, Small amount of data)

![(Figure 2) The overall workflow of the conducted study](https://user-images.githubusercontent.com/79679194/229401591-ac6cf608-bb72-4d5a-8a2d-2d621f7b2d1b.jpg)


- The study2 creates the optimal predictive classification model(emission or non emission) and interprets the relationship between the variables using PDP of XAI. In addition, ANOVA, Correlation analysis and Feature importance are performed.\
  (**Data special note: Convert complex odor(numerical) to categorical)

![pipelines](https://user-images.githubusercontent.com/79679194/229402641-fc6952fe-82b0-4c2b-bac3-99b54a16678d.png)

