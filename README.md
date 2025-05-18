# Credit Risk Assessment Using 99% CreditVaR

Using a **99% CreditVaR**, the objective is to assess the credit risk of a portfolio composed of two debt instruments from the **banking sector**, each with a **notional value of EUR 1,000** and a **maturity of 4 years**.

- The first is a **BNP Paribas senior bond** with a **recovery rate** averaging **60%** and a **volatility of 15%**.
- The second is a **Société Générale junior (or subordinated) bond** with a **recovery rate** averaging **30%** and a **volatility of 25%**.

We assume that **recovery rates are independent**.

Throughout the study, you must rigorously present the **tools used** and **justify** your modeling choices. Writing clear and well-reasoned **conclusions** is essential for ensuring the document is understandable to **non-specialists**.

---

## 1. Extracting Implied Default Probabilities

We consider that the **4-year CDS spreads** for BNP and SG are respectively **100bps** and **120bps**, and the **5-year CDS spreads** are **120bps** and **150bps**.  
The CDS were priced assuming a **recovery rate of 40%**.

From the CDS spreads for different maturities for both companies, **extract the implied default probabilities**.

---

## 2. Recovery Rate Distributions

Characterize the **distribution of recovery rates** for each of the two bonds.

---

## 3. Historical Equity Data

### a. Univariate Exploratory Analysis

Perform a **univariate exploratory analysis** of the **equity data** for both companies.

### b. Risk Factor Distribution Modeling

Appropriately model the **univariate distributions** of the **risk factors**.

---

## 4. Dependence Structure – Non-parametric Analysis

Study the **dependence structure** between the risk factors using **non-parametric criteria**.

---

## 5. Dependence Structure – Parametric Copula Models

Model the dependence structure using the following **parametric copulas**:

### a. Elliptical Copulas

- Gaussian  
- Student-t

### b. Archimedean Copulas

- Clayton  
- Gumbel  
- Frank

## 6. Portfolio CreditVaR at 99%

Finally, compute the **99% CreditVaR** of the portfolio using the **Monte Carlo simulation method**.
