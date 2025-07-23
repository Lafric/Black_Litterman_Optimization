# Black-Litterman model for Portfolio Optimization & Diversification Analysis

This repository contains two Jupyter notebooks that explore advanced techniques in **portfolio management and risk analysis**. The focus is on improving portfolio construction using modern financial models like **Black-Litterman** and quantifying the **benefits of diversification**.

---

## Contents

### `black_litterman.ipynb`

**Purpose:**  
Implements the Black-Litterman model for portfolio optimization by combining market equilibrium with investor views.

**Highlights:**

- Computes implied equilibrium returns using the reverse optimization approach.
- Allows incorporation of investor confidence and subjective views.
- Outputs updated expected returns and optimal asset weights.
- Useful for institutional portfolio strategy and stress-testing scenarios.

---

### `diversification_benefit.ipynb`

**Purpose:**  
Analyzes the impact of diversification on portfolio risk using historical asset data.

**Highlights:**

- Computes individual asset volatility and total portfolio risk.
- Measures how diversification reduces overall risk.
- Compares naive equal-weight portfolios to optimized ones.
- Visualizes correlation matrices and risk reduction.

---

Inspired from the following articles:

https://theaiquant.medium.com/achieving-financial-excellence-portfolio-optimization-in-python-with-mean-variance-and-5525175800b4
http://www.quantandfinancial.com/2013/07/mean-variance-portfolio-optimization.html
http://www.quantandfinancial.com/2013/08/black-litterman.html
