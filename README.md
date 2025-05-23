# Privacy Awareness: A Demo-cum Tutorial for Privacy Aware Learning

This project is a web-based interactive tutorial designed to educate the general public and policymakers about data privacy, particularly focusing on **Differential Privacy in Linear Regression**. The demo emphasizes how adding noise to data during training can protect sensitive information while maintaining a balance with model accuracy.

## Problem Statement

Create a web application to educate users about data piracy and promote:
- Informed decision-making
- Awareness of privacy risks in machine learning
- Advocacy for stronger data privacy laws

## Motivation

With increasing concerns over data security and privacy, it's essential to:
- Protect sensitive information during data analysis
- Ensure compliance with privacy regulations
- Maintain the accuracy of predictive models

## Approach

The tutorial demonstrates the application of **Differential Privacy** by:
- Adding **Gaussian** and **Laplace noise** to:
  - Input features (X)
  - Output labels (y)
  - Model predictions
  - Regression coefficients
- Applying **clipping** to bound the data before noise addition
- Varying the **epsilon (ε)** parameter to control privacy levels
- Visualizing:
  - Regression results with and without noise
  - Effects of different privacy budgets (ε values)

## Web Application Functionality

- A clean and interactive **User Interface**
- Embedded **Google Colab notebook** for experimentation
- Visualization of noise effects on linear regression using the **Diabetes dataset**
- Options to toggle:
  - Type of noise (Laplace/Gaussian)
  - Use of clipping
  - Epsilon values

##  Example Scenarios

- **Adding Laplace noise** to predictions, coefficients, input features (X), and output values (y) – with and without clipping
- **Visual comparison** of noisy vs. baseline regression models

## Key Concepts & Formulas

- **Ordinary Least Squares Regression (OLSR)**
- **Laplace noise formula**
- **Gaussian noise formula**

## Resources

- [Efficient differentially private learning improves drug sensitivity prediction – Biology Direct](https://biologydirect.biomedcentral.com/articles/10.1186/s13062-017-0203-4)
- [The Algorithmic Foundations of Differential Privacy – Aaron Roth & Cynthia Dwork](https://www.cis.upenn.edu/~aaroth/privacybook.html)


---

Feel free to fork, contribute, or suggest improvements via pull requests!
