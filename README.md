# Data Science Intern Assignment - eCommerce Transactions Dataset

## Overview
This repository contains the deliverables for the Data Science Intern assignment focused on analyzing eCommerce transaction data. The tasks include exploratory data analysis (EDA), building a lookalike model, and performing customer segmentation.

---

## Repository Structure

```
data-science-assignment/
├── Mrigank_Raj_Dubey_EDA.ipynb         # EDA code
├── Mrigank_Raj_Dubey_EDA.pdf           # EDA insights report
├── Mrigank_Raj_Dubey_Lookalike.ipynb   # Lookalike model code
├── Mrigank_Raj_Dubey_Lookalike.csv     # Lookalike model recommendations
├── Mrigank_Raj_Dubey_Clustering.ipynb  # Clustering code
├── Mrigank_Raj_Dubey_Clustering.csv    # Clustering results
├── Mrigank_Raj_Dubey_Clustering.pdf    # Clustering report
├── README.md                           # Repository documentation
```

---

## Task Details

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- **Objective**: Analyze the dataset to uncover patterns and derive actionable insights.
- **Deliverables**:
  - `Mrigank_Raj_Dubey_EDA.ipynb`: Code for performing EDA.
  - `Mrigank_Raj_Dubey_EDA.pdf`: Report summarizing 5 business insights derived from the analysis.

### Task 2: Lookalike Model
- **Objective**: Recommend 3 similar customers for each of the first 20 customers based on their profiles and transaction histories.
- **Deliverables**:
  - `Mrigank_Raj_Dubey_Lookalike.ipynb`: Code for the lookalike model.
  - `Mrigank_Raj_Dubey_Lookalike.csv`: Recommendations with similarity scores.

### Task 3: Customer Segmentation / Clustering
- **Objective**: Segment customers into meaningful clusters using profile and transaction data.
- **Deliverables**:
  - `Mrigank_Raj_Dubey_Clustering.ipynb`: Code for clustering.
  - `Mrigank_Raj_Dubey_Clustering.csv`: Results of clustering with cluster assignments.
  - `Mrigank_Raj_Dubey_Clustering.pdf`: Report summarizing clustering methodology, results, and insights.

---

## Instructions to Reproduce

### Clone the Repository
```bash
git clone https://github.com/mrigankraj/data-science-assignment.git
cd data-science-assignment
```

### Set Up Environment
1. Ensure Python 3.8+ is installed.
2. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```

### Run Jupyter Notebooks
1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open and execute the following notebooks sequentially:
   - `Mrigank_Raj_Dubey_EDA.ipynb`
   - `Mrigank_Raj_Dubey_Lookalike.ipynb`
   - `Mrigank_Raj_Dubey_Clustering.ipynb`

### View Reports
- PDF reports (`EDA` and `Clustering`) summarize insights and results.

---

## GitHub Workflow
To upload all deliverables to GitHub:

1. **Initialize a Git Repository**
   ```bash
   git init
   ```

2. **Add Files to Repository**
   ```bash
   git add .
   ```

3. **Commit Changes**
   ```bash
   git commit -m "Initial commit for Data Science assignment"
   ```

4. **Create the Main Branch**
   ```bash
   git branch -M main
   ```

5. **Add Remote Repository**
   ```bash
   git remote add origin https://github.com/mrigankraj/data-science-assignment.git
   ```

6. **Push to GitHub**
   ```bash
   git push -u origin main
   ```

---

## License
MIT

---

## Contact
For questions or clarifications, please reach out to **Mrigank Raj Dubey (mrigankraj2003@gmail.com)**.
