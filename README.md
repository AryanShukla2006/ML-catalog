# ML-catalog
# 📘 PRML Study Notes – Christopher M. Bishop

This repository contains my personal learning notes and summaries as I study the book **"Pattern Recognition and Machine Learning"** by *Christopher M. Bishop*. The aim is to document key concepts, mathematical foundations, and reflections on each topic for future reference and sharing with fellow learners.

---

## 📅 Study Log

### ✅ Day 1: Introduction to Machine Learning & Polynomial Curve Fitting
- Applications of Machine Learning and Pattern Recognition
- Polynomial curve fitting as a way to demonstrate basic regression
- **Core Concepts Covered:**
  - Generalization
  - Overfitting
  - Polynomial functions as models
  - Cost function: Sum-of-squares error
  - Root Mean Square Error (Erms)
 
### ✅ Day 2: Probability Theory & Bayes' Theorem
- Derivation of **sum and product rules** using probability axioms
- **Bayes' Theorem** for conditional probability, including matrix-based understanding
- Introduction to **Probability Density Functions (PDFs)**
- **Key Takeaways:**
  - Importance of marginal, joint, and conditional probability
  - Visualizing dependencies with matrix representations
  - Understanding the shift from discrete to continuous probability using densities


### ✅ Day 3: Continuous Distributions & Bayesian View
- Change of variable and Jacobian in probability densities
- Expectation, variance, and covariance as statistical summaries
- Introduction to Bayesian probability: prior, likelihood, posterior
- Normal (Gaussian) distribution and its importance

### ✅ Day 4: Probabilistic Curve Fitting & MLE vs MAP
- Reformulated polynomial curve fitting as a probabilistic model using Gaussian noise
- Learned Maximum Likelihood Estimation (MLE) via log-likelihood derivation
- Identified MLE's limitations (overfitting, no regularization)
- Introduced Bayesian reasoning with priors → Maximum A Posteriori (MAP) estimation
- Hyperparameters like α (prior precision) and β (noise precision) introduced for better generalization


---

## 📚 Book Overview

- **Title:** Pattern Recognition and Machine Learning
- **Author:** Christopher M. Bishop
- **Publisher:** Springer
- **ISBN:** 978-0-387-31073-2

This is a foundational text in machine learning, known for its mathematical rigor and comprehensive coverage of probabilistic models.

---

## 🛠️ How to Use This Repository

- Browse daily learning notes in the `/notes` folder (to be added progressively).
- Use the content as a reference for understanding core ML concepts.
- Clone/fork the repository to maintain your own notes.

```bash
git clone https://github.com/yourusername/prml-study-notes.git
