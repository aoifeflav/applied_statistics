# Applied Statistics

**Author:** Aoife Flavin

**Student ID:** G00439331

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

You can run the notebook locally using Visual Studio Code or directly in the browser using GitHub Codespaces.

### Option 1: Run Locally with Visual Studio Code

1. Install:
   - **Python 3.9+**
   - **Visual Studio Code**
   - The VS Code **Python** and **Jupyter** extensions

2. Clone the Repository
```bash
git clone <https://github.com/aoifeflav/applied_statistics.git>
cd <applied_statistics>
```


3. Install Dependencies
```bash
pip install -r requirements.txt
```

4. Open the repository in Visual Studio Code:
   ```bash
   code .
   ```

5. Open the notebook (`.ipynb`) file and run cells interactively inside VS Code.

---

### Option 2: Run in GitHub Codespaces (No Local Setup)

1. Navigate to the repository on GitHub.
2. Click **Code → Codespaces → Create codespace on main**.
3. Once the Codespace loads, open a terminal and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the notebook file and run it directly in the browser.

> **Note:** GitHub Codespaces provides a preconfigured Linux environment with Python installed, allowing the notebook to be run without any local setup.

---

## Data and Assets


This repository contains only the notebook and a requirements.txt file. The computations do not rely on external datasets stored in the repository.

---

## Technologies Used

- [**Jupyter Notebook**](https://jupyter.org/) – interactive analysis environment  
- [**NumPy**](https://numpy.org/) – numerical computing  
- [**Pandas**](https://pandas.pydata.org/) – data manipulation  
- [**Matplotlib**](https://matplotlib.org/) and [**Seaborn**](https://seaborn.pydata.org/) – visualisation  
- [**SciPy**](https://scipy.org/) – statistical functions  

---

## Reproducibility Notes

- All dependencies are listed in `requirements.txt`
- For fully pinned versions, you can generate a locked file with:
  ```bash
  pip freeze > requirements.txt
  ```
- This ensures consistent results across different systems

---

## Sources

A variety of resources were used in completing this coursework. I relied primarily on the module lecture videos and lecture notes when developing solutions to the problems. In addition, I made extensive use of the official documentation for the [Python](https://docs.python.org/3/) libraries used throughout the notebook.

Several online resources were also helpful for reference and clarification, including [GeeksforGeeks](https://www.geeksforgeeks.org/), [W3Schools](https://www.w3schools.com/), [DataCamp](https://www.datacamp.com/), [Wikipedia](https://www.datacamp.com/), and similar educational websites. I also used [YouTube](https://www.youtube.com/) videos to help build intuition around more challenging statistical concepts.

[ChatGPT](https://chatgpt.com/) was used throughout the project as a support tool, primarily for debugging code, clarifying concepts, and assisting with formatting and presentation of the Jupyter notebook and this README.

---