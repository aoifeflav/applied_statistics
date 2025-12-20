# Applied Statistics

**Author:** Aoife Flavin

**Student ID:** G00239331

## Overview

This repository contains my coursework for Applied Statistics, a module completed in the final semester of the Higher Diploma in Data Analytics at ATU.  
The module lecturer was Ian McLoughlin.

As part of this module, I completed four applied statistics problems, which are available in the accompanying Jupyter notebook:
- [problems.md](https://github.com/ianmcloughlin/applied-statistics/blob/main/assessment/problems.md)

### Summary of Problems

#### Problem 1 – Simulation of a Classical Hypothesis Test
Extended the *Lady Tasting Tea* experiment by simulating a modified experimental design using randomisation in NumPy, estimating the probability of perfect classification by chance, and reflecting on implications for p-value thresholds.

#### Problem 2 – Sampling Distributions of the Standard Deviation
Used large-scale simulation to compare sample and population standard deviation estimators for small samples drawn from a normal distribution, visualising their distributions and analysing how bias changes with sample size.

#### Problem 3 – Type II Error in t-Tests
Simulated independent-samples t-tests across a range of mean differences to estimate type II error rates, demonstrating how statistical power increases as the true effect size grows.

#### Problem 4 – ANOVA vs Multiple t-Tests
Compared one-way ANOVA with multiple pairwise t-tests using simulated normal data, illustrating why ANOVA is preferred when testing equality of multiple group means.


---

## Repository Contents

- `problems.ipynb` — the main notebook containing the analysis and solutions  
- `requirements.txt` — Python dependencies required to run the notebook  
- `README.md` — setup and usage instructions (this file)

---

## Setup

### Prerequisites
- Python **3.9+** recommended
- `pip` available on your system

### Clone the Repository
```bash
git clone <https://github.com/aoifeflav/applied_statistics.git>
cd <applied_statistics>
```


### Install Dependencies
```bash
pip install -r requirements.txt
```

---

## Running the Notebook

Start Jupyter:
```bash
jupyter notebook
```

Then open:
- `problems.ipynb`

Run cells from top to bottom to reproduce the results.

---

## Data and Assets


This repository contains only the notebook. The computations do not rely on external datasets stored in the repository.

---

## Technologies Used

- **Jupyter Notebook** – interactive analysis environment  
- **NumPy** – numerical computing  
- **Pandas** – data manipulation  
- **Matplotlib** and **Seaborn** – visualisation  
- **SciPy** – statistical functions  

---

## Reproducibility Notes

- All dependencies are listed in `requirements.txt`
- For fully pinned versions, you can generate a locked file with:
  ```bash
  pip freeze > requirements.txt
  ```
- This ensures consistent results across different systems

---