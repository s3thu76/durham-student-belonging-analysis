# Belonging or Burnout?  
## Social Integration Among Graduate Students in Durham

This project examines how graduate students in Durham experience social integration and belonging, and which factors are most strongly associated with feeling connected to the community.

The repository demonstrates a complete, end-to-end data science workflow using survey data: from survey design and feature engineering to exploratory analysis, modeling, and statistical inference. The project is framed around **social good**, with a focus on identifying actionable levers to improve student well-being and community integration.

---

## Research Question

How are graduate students’ feelings of belonging related to:
- time spent living in Durham,
- living situation,
- and frequency of in-person social interactions?

---

## Methods

### Survey Design
- Likert-scale questions measuring belonging, social connection, and comfort initiating interactions
- Contextual variables including time in Durham, living situation, transportation, and international status

### Feature Engineering
- Construction of a composite **Belonging Index** (average of four Likert-scale items)
- Reverse-coding of workload-related barriers for interpretability
- Numeric encoding of ordinal survey responses

### Analysis
- Exploratory data analysis (distributions and group comparisons)
- Multivariate linear regression with categorical controls (one-hot encoding)
- Bootstrap confidence intervals to quantify uncertainty in group-level differences
- Visualization using matplotlib

---

## Key Findings

- Belonging is moderate on average, clustering around the midpoint of the scale
- Students newer to Durham report lower belonging than more established residents
- Living with roommates or a partner is associated with higher belonging than living alone
- Frequency of in-person social interactions shows the strongest relationship with belonging
- After controlling for other factors, workload flexibility shows a weaker association than social interaction frequency

---

## Social Good Implications

The results suggest that community-building interventions may be most effective when they:
- Target students in their **first semester** in Durham
- Increase **recurring, low-friction in-person interactions**
- Provide structured on-ramps for students living alone
