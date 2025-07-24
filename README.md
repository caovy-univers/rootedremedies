# 🌿 TaxaTherapy: A Data-driven Lens on Medicinal Plants

**CodeOp DST19 Collaborative Project**  
**Date:** 24.07.2025  
**Contributors:** Eliana, Leila, Roza

---

## 🧭 Overview

**TaxaTherapy** explores how machine learning can be applied to predict the medicinal properties of plants based on their taxonomy, edibility, and native location. Despite the rich history of medicinal plants in traditional and modern pharmacology, only 5% of the 30% medicinal plants known are used in pharmaceuticals. This project aims to bridge this gap using data science and NLP.

---

## 🌱 What is a Medicinal Plant?

Medicinal plants are species whose harvested parts—leaves, roots, bark, seeds, or flowers—contain bioactive compounds used to:

- ✅ Prevent diseases  
- ✅ Alleviate symptoms  
- ✅ Cure illnesses in humans and animals

These plants are fundamental to many traditional healing systems and the source of numerous modern drugs.

---

## 🎯 Objective

**Can we classify medicinal properties of plants based on:**

- **Edibility** (context & variability of consumption)  
- **Taxonomic Family** (non-phylogenetic)  
- **Native Range** (region of origin)

---

## 🧪 Data & Methods

### 📊 Dataset

- Source: [Plants For A Future (PFAF)](https://pfaf.org)
- Dimensions: 17,950 rows × 27 columns
- Unique Plants: 4,131 species
- Categories of medicinal use: Digestive (26%), Neurological (19.2%), Systemic (11.4%), and more

### 🧠 Techniques

- **Natural Language Processing (spaCy):**
  - Tokenization
  - Lemmatization
  - Stop word removal
  - POS tagging
  - Named-entity recognition (NER)

- **Machine Learning:**
  - Classifiers tested: Logistic Regression, XGBoost, Neural Networks
  - Balanced class distributions with SMOTE (Synthetic Minority Over-sampling)
  - Model evaluation using accuracy, precision, recall, F1-score

---

## 🌍 Results

### 🌐 Global Patterns

- **Diuretic** properties dominate in Eurasia, South Africa, and Mexico (families: Asteraceae, Brassicaceae, Lamiaceae)
- **Tonic** and **Astringent** traits are common in Southern Eurasia and North America
- **Febrifuge** and **Skin** treatments emerge in Central Africa and Brazil

### 🧬 Key Findings

- **Family and Location** are the strongest predictors of medicinal properties
- **‘Hypotensive’** property was classified with up to **94% accuracy**
- **Neural Networks** outperformed XGBoost for capturing non-linear patterns in medicinal subgroup data
- Overfitting observed when combining all features in classical models

---

## 🚀 Conclusions

- Medicinal properties are **strongly correlated** with a plant’s taxonomy and native environment
- **XGBoost** showed high initial performance but poor generalization on full-feature sets
- **Neural Networks** provided better generalization and adaptability for real-world, complex data
- Future directions include:
  - 📈 Feature engineering for improved neural architectures
  - 📊 Expanding the dataset for balanced class representation

---

## 🙌 Acknowledgements

Huge thanks to:

- **Filipa Peleja**, **Oumaima**, and the **CodeOp DSPT19** team  
- [**Plants for a Future**](https://pfaf.org) for the dataset  
- Everyone who supported our project journey 🌱

---

📬 **Contact us on Slack** if you’d like to collaborate, contribute, or learn more!
