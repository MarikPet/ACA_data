# Web Marketing Campaign: A/B Hypothesis Testing & Operational Performance Metrics

## 📊 Project Overview
This project delivers a rigorous, data-driven statistical evaluation of a Web Marketing Campaign's performance impact on user engagement. Utilizing a dataset tracking web visitor telemetry logs from June 2025, the objective was to determine whether a strategic spring marketing push successfully generated a statistically meaningful increase in average user session durations against historical operational baselines. 

The entire data cleaning, exploratory analysis, and parametric statistical modeling lifecycle was executed natively using **Advanced Microsoft Excel**.

## 🎯 Business Question & Hypothesis Staging
The core corporate analytical question addressed was: *“Did the spring web marketing initiative cause a statistically significant increase in the time users spend engaged on our platform, or is the observed variance merely a result of random noise?”*

To evaluate the operational impact velocity with absolute mathematical confidence, a right-tailed one-sample hypothesis test was framed:
*   **Null Hypothesis ($H_0$):** $\mu \le 120$ seconds (The marketing campaign had no positive effect; average session duration remains equal to or less than the historical baseline).
*   **Alternative Hypothesis ($H_1$):** $\mu > 120$ seconds (The marketing campaign successfully drove a statistically significant increase in user engagement duration).

## 🛠️ Data Cleansing & Analytical Methodology
Prior to statistical testing, the raw telemetry data was scrubbed and profiled to ensure complete ledger data quality:
1.  **Data Standardizing:** Standardized messy session logs, handled timestamp parameters, and eliminated null record attributes to preserve sample variance.
2.  **Dataset Profiling:** Extracted descriptive statistics to evaluate the underlying distribution rules:
    *   **Sample Size ($n$):** 81 active users
    *   **Sample Mean ($\bar{x}$):** 342 seconds
    *   **Sample Standard Deviation ($s$):** 154 seconds
    *   **Degrees of Freedom ($df$):** 80 ($n - 1$)
    *   **Significance Alpha ($\alpha$):** 0.05 (95% Confidence Interval)

## 📈 Statistical Modeling & Result
Because the true population variance was unknown, an **Independent One-Sample Right-Tailed T-Test** was engineered directly inside Excel. 

Using the structural T-statistic formula:
$$t = \frac{\bar{x} - \mu_0}{s / \sqrt{n}}$$

*   **Calculated Test Statistic ($t_{calc}$):** **13.0**
*   **Critical Threshold Value ($t_{crit}$):** **1.664** (Sourced from the standard t-distribution table at $df = 80, \alpha = 0.05$)

### 📌 Conclusion
The calculated test statistic ($13.0$) falls significantly deeper into the right-tailed critical region than the required critical threshold boundary ($1.664$). Consequently, we **reject the Null Hypothesis ($H_0$)** with over 95% mathematical confidence. 

This provides definitive statistical proof that the Web Marketing Campaign effectively shifted consumer behavior, driving a highly significant increase in user platform session duration and providing data-backed justification for long-term product funding allocations.

## 📂 Repository Contents
*   `📊 Web_Marketing_Campaign_Analysis.xlsx` - Master spreadsheet containing raw telemetry logs, data-cleaning steps, and active T-test formula architectures.
*   `📁 Hypothesis_testing.pdf` / `.pptx` - Executive data storytelling deck translating statistical outputs into operational product strategy metrics.
