# Supporting R Code for the Manuscript

***“Environmental heterogeneity shapes higher soil fungal diversity in forests of eastern Asia compared to eastern North America”***

This repository contains three R scripts that support the analyses presented in **Yang et al.** The scripts cover data processing, plant phylogenetic tree construction, and hypothesis testing related to soil fungal diversity across Eastern Asia (EA) and Eastern North America (ENA).

---

## 📁 Repository Contents

---

### **1. `H1 code.r`**

#### **1.1 Purpose**

Test Hypothesis 1 (H1)-the pattern hypothesis:
**Soil fungal taxonomic and phylogenetic diversity are greater in EA than in ENA.**

#### **1.2 Key Functions**

* Create boxplots showing significantly higher fungal diversity in EA than in ENA based on five datasets.
* Generate merged figures comparing fungal diversity between EA and ENA across the disjunct plant phylogenetic tree.
* Create boxplots showing significant differences in fungal diversity among plant genera.
* All figures are accompanied by statistical test outputs.

---

### **2. `H2 code.r`**

#### **2.1 Purpose**

Test Hypotheses 2 (H2)-the mechanism hypothesis:
**The intercontinental difference is explained primarily by environmental factors rather than by plant-related factors or continent per se, with greater climatic, topographic, and soil heterogeneity in EA promoting greater fungal diversity.**

#### **2.2 Key Functions**

* Perform OLS multiple regression models to disentangle the drivers of soil fungal alpha diversity across EA and ENA forests.
* Summarize multiple OLS regression models using donut diagrams.
* Create partial regression plots illustrating the independent effects of key environmental predictors on soil fungal diversity.

---

### **3. `Plant phylogenetic tree construction.r`**

#### **3.1 Purpose**

Construct plant phylogenetic trees to visualize the study design.

#### **3.2 Key Functions**

* Draw phylogenetic trees for the **Expanded datasets**.
* Draw phylogenetic trees for the **Disjunct datasets**.

---
