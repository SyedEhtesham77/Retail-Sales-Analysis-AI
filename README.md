# Retail Sales Analysis and AI-Based Sales Prediction

**Internship:** AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026 — BharatCares  
**Project level:** Beginner  
**Code file:** `YourName_RetailSalesAnalysisAI.ipynb`

## Overview
This project demonstrates a beginner-friendly data analytics workflow using Python. It summarizes retail-style sales data, creates charts, and trains a Linear Regression model to estimate sales from units sold, unit price, and advertising spend.

## Project objectives
- Inspect and clean tabular data.
- Calculate summary statistics and sales by category/region.
- Visualize sales patterns and relationships.
- Train and evaluate a baseline machine-learning model.
- Explain limitations and responsible use.

## Dataset
The notebook generates a reproducible **synthetic sample dataset** so the project can run without a separate download. It is for learning and demonstration only; it is not real company data and must not be described as real-world evidence. The notebook includes a commented example for loading a CSV file if you have an approved dataset.

## Technologies
- Python
- pandas and NumPy
- Matplotlib and Seaborn
- scikit-learn
- Jupyter Notebook

## Files
- `YourName_RetailSalesAnalysisAI.ipynb` — complete project code and explanations.
- `requirements.txt` — Python libraries needed to run the notebook.
- `YourName_ProjectReport.docx` — project documentation.
- `README.md` — project overview and setup instructions.

## Setup instructions

### Option A: Run locally
1. Install Python 3.10 or later.
2. Extract all project files into one folder.
3. Open a terminal/Command Prompt in that folder.
4. Create and activate a virtual environment (recommended).

   **Windows**
   ```bash
   py -m venv .venv
   .venv\\Scripts\\activate
   ```

   **macOS/Linux**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```

5. Install dependencies:
   ```bash
   python -m pip install --upgrade pip
   pip install -r requirements.txt
   ```
6. Start Jupyter:
   ```bash
   jupyter notebook
   ```
7. Open `YourName_RetailSalesAnalysisAI.ipynb` and choose **Kernel → Restart & Run All**.

### Option B: Use Google Colab
1. Open Google Colab.
2. Upload `YourName_RetailSalesAnalysisAI.ipynb`.
3. If a library is missing, run `!pip install -r requirements.txt` after uploading the requirements file, or install the missing package directly.
4. Run all notebook cells from top to bottom.

## Expected outputs
- Dataset preview and data-quality checks.
- Summary statistics.
- Tables for total sales by category and region.
- Bar charts, a scatter plot, and a correlation heatmap.
- Linear Regression test metrics (MAE and R²).
- Actual-versus-predicted comparison and an example estimate.

Exact metric values are printed when the notebook runs. Do not invent or manually claim values that have not been observed from an actual run.

## How to use a real CSV
If your internship requires an external dataset, use a dataset you are permitted to use. In the notebook, replace the sample-data creation cell with code similar to:
```python
df = pd.read_csv("your_sales_data.csv", parse_dates=["Date"])
```
Ensure the CSV contains the columns used by the notebook: `Date`, `Category`, `Region`, `Units_Sold`, `Unit_Price`, `Advertising_Spend`, and `Sales`. If your dataset uses different column names, update the code consistently.

## Limitations and responsible use
- The default data is synthetic and only demonstrates a workflow.
- Model quality depends on data quality and representativeness.
- A random split is not a rigorous time-series forecasting evaluation.
- Association does not prove causation.
- Do not upload confidential or personally identifiable data to public services.

## Author details
Replace `YourName` in the required filenames with your full name before submission. Add your name, college, branch, roll number (if requested by the form), and submission date to the report only if required. Verify the internship's exact submission instructions before uploading.
