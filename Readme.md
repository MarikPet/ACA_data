# Excel Statistical Analysis & Hypothesis Testing Portfolio

[![Excel](https://shields.io)](https://microsoft.com)
[![License: MIT](https://shields.io)](https://opensource.org)
[![Analytics](https://shields.io)](https://github.com)

Welcome to the **Excel Statistical Analysis Portfolio**. This repository showcases advanced statistical modeling, data validation, and hypothesis testing pipelines engineered entirely within Microsoft Excel. It demonstrates how to leverage native spreadsheet architectures to run rigorous statistical validations for business decision-making.

---

## 📂 Repository Structure

The project artifacts are structured as follows to ensure clean navigation and file integrity:

```text
├── models/                     # Production spreadsheet workbooks (.xlsx)
├── docs/                       # Academic papers and reference material
│   └── Hypothesis_testing.pdf  # Comprehensive theoretical breakdown of statistical tests
└── README.md                   # Project documentation and dashboard
```

---

## 🎯 Core Analytics & Excel Features

### 1. Hypothesis Testing Frameworks
* **Parametric Testing**: Built-in evaluation models tracking T-Tests (Independent/Paired), Z-Tests, and ANOVA (Analysis of Variance) structures.
* **Non-Parametric Analysis**: Implementation tracking for Chi-Square Test of Independence for categorical distributions.
* **Statistical Integrity Protection**: Data validation logic checking for distribution variances, sample sizes, and outlier metrics before running test mechanisms.

### 2. Analytical Presentation
* **Hypothesis_testing.pdf**: A structured companion guide breaking down the underlying mathematical theories, test selections, and p-value interpretations behind the spreadsheet models.

---

## 🚀 How to Use the Models

### Prerequisites
To interact with the models with full formula integrity, you will need:
* Microsoft Excel 2021 or Microsoft 365 (Recommended for Dynamic Arrays)
* **Analysis Toolpak Add-in** enabled (Go to `File` > `Options` > `Add-ins` > `Excel Add-ins` > Check `Analysis Toolpak`)

### Getting Started
1. **Download the Workbook**: Navigate to the `models/` directory, select the `.xlsx` file, and click **Download raw file**.
2. **Review the Theory**: Open `docs/Hypothesis_testing.pdf` to review the statistical frameworks and criteria used to construct the models.
3. **Analyze**: Input your custom data arrays into the designated input cells to watch the automated p-value calculators dynamically update.

---

## 🛠️ Excel Technical Stack

* **Toolpak Engines**: Descriptive Statistics, Anova: Single Factor, t-Test: Two-Sample Assuming Unequal Variances.
* **Core Functions**: `T.TEST()`, `CHISQ.TEST()`, `Z.TEST()`, `AVERAGE()`, `STDEV.S()`, `NORM.DIST()`.
* **Logic Architecture**: Dynamic array formulas, conditional formatting for significance thresholds ($\alpha = 0.05$), and automated statistical inference text blocks.

---

## 📄 License

This portfolio project is open-source and licensed under the terms of the [MIT License](https://opensource.org).
