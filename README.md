::: {align="center"}
# 📱 Mobile Data Web Scraping & Price Prediction

### Turning mobile phone listing data into data-driven price insights with Python and Machine Learning

```{=html}
<p>
```
`<img src="https://img.shields.io/badge/Project-Data%20Science-6C63FF?style=for-the-badge" alt="Data Science Project" />`{=html}
`<img src="https://img.shields.io/badge/Python-Analysis-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />`{=html}
`<img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter Notebook" />`{=html}
`<img src="https://img.shields.io/badge/Machine%20Learning-Price%20Prediction-0A7B65?style=for-the-badge" alt="Machine Learning" />`{=html}
```{=html}
</p>
```
**[📂 View
Repository](https://github.com/ParthasarathiAnalytics/Web-Scraping-Mobile-Data-Prediction)**
  •   **[👨‍💻 View
Portfolio](https://parthasarathi-analytics.vercel.app/)**
:::✨ Project at a Glance
This capstone project explores a complete data science workflow for
mobile phone listings: collecting data through web scraping, preparing
it for analysis, exploring patterns in product attributes, and applying
machine learning techniques to estimate mobile phone prices.
Core idea: Use product listing data to investigate how mobile
phone attributes relate to price and build a data-driven prediction
workflow.

<table>
<tr>
<td width="50%">
<h3>
🎯 Goal
</h3>
Explore mobile phone listing data and develop a price-prediction model.
</td>
<td width="50%">
<h3>
🧰 Approach
</h3>
Web scraping → data preparation → EDA → model training → evaluation.
</td>
</tr>
<tr>
<td width="50%">
<h3>
📓 Main Deliverable
</h3>
Jupyter Notebook containing the capstone workflow.
</td>
<td width="50%">
<h3>
📈 Expected Output
</h3>
An evaluated regression model and insights grounded in the collected
data.
</td>
</tr>
</table>
📑 Table of Contents
- Business Problem
- Project Objectives
- Technology Stack
- Project Files
- Project Workflow
- Getting Started
- Model Evaluation
- Responsible Web Scraping
- Limitations
- Future Enhancements
- Author
💡 Business Problem
Mobile phone prices vary based on product specifications, brand,
availability, and seller offers. Comparing listings can be difficult
when product information is spread across multiple pages or presented in
inconsistent formats.

This project investigates whether collected mobile phone listing data
can be prepared and used to model the relationship between available
product attributes and listed prices.
Questions this project explores
- What mobile phone listing information can be collected from web
  pages?
- What data-quality issues need to be addressed before analysis?
- Which available product attributes appear related to price?
- How can a machine learning regression model estimate price from
  selected features?
- How should model performance be evaluated?
🎯 Project Objectives
- 🌐 Collect mobile phone listing data using web-scraping techniques.
- 🧹 Inspect and prepare the collected data for analysis.
- 🔎 Perform exploratory data analysis (EDA).
- 🧩 Select relevant features for price prediction.
- 🤖 Train a machine learning regression model.
- 📏 Evaluate model performance using appropriate metrics.
- 📝 Document the process and communicate the project through
  supporting materials.
🛠️ Technology Stack
  Technology                          Role in the project
  Python                          Data processing and model
                                      development

  Jupyter Notebook                Interactive coding, analysis, and
                                      experimentation

  Pandas                          Tabular data preparation and
                                      analysis

  NumPy                           Numerical operations

  Web-scraping libraries          Collecting listing data, depending
                                      on the notebook implementation

  Matplotlib / Seaborn            Data visualization, if used

  Scikit-learn                    Model training and evaluation, if
                                  used
Confirm the exact libraries and versions from the notebook's import
cells before documenting them as final dependencies.
🗂️ Project Files
  File                                                 Purpose
  MOBILE CAT PERDICT USING ML (CAPSTONE) (1).ipynb   Main notebook for the mobile price
                                                       prediction workflow

  CAPSTONE PROJECT bY SARATHI.docx                   Project documentation

  Cap Stone Project Description.pdf                  Capstone project description

  capstone ppt (wecompress.com).pptx                 Project presentation
  README.md                                          Project overview and instructions
🔄 Project Workflow
┌──────────────────────┐
│  1. Web Data Scraping │
│  Collect listings     │
└──────────┬───────────┘
           ▼
┌──────────────────────┐
│  2. Data Preparation  │
│  Inspect and clean    │
└──────────┬───────────┘
           ▼
┌──────────────────────┐
│  3. Exploratory Data  │
│  Analysis (EDA)       │
└──────────┬───────────┘
           ▼
┌──────────────────────┐
│  4. Feature Selection │
│  Prepare model inputs │
└──────────┬───────────┘
           ▼
┌──────────────────────┐
│  5. Model Training    │
│  Fit a regression     │
│  model                │
└──────────┬───────────┘
           ▼
┌──────────────────────┐
│  6. Model Evaluation  │
│  Measure performance │
└──────────────────────┘
Workflow details
1. Web scraping
Collect mobile phone listing information from the target website.
Document the source, fields, and scraping approach used in the notebook.

2. Data preparation
Inspect missing values, duplicates, inconsistent formats, and data
types. Apply cleaning steps based on the actual dataset.

3. Exploratory data analysis
Review price distributions and investigate relationships between price
and the product attributes available in the data.

4. Feature preparation
Choose input features and prepare categorical or numeric variables as
required by the selected model.

5. Model training
Train a regression algorithm using an appropriate training and testing
strategy.

6. Evaluation
Compare predicted and actual prices and assess performance with suitable
regression metrics.
🚀 Getting Started
Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- Required packages used by the notebook
- Any dataset files or scraping dependencies required by the project
1. Clone the repository
git clone https://github.com/ParthasarathiAnalytics/Web-Scraping-Mobile-Data-Prediction.git
cd Web-Scraping-Mobile-Data-Prediction
2. Create a virtual environment (recommended)
Windows
python -m venv .venv
.venv\Scripts\activate
macOS / Linux
python3 -m venv .venv
source .venv/bin/activate
3. Install dependencies
If the repository contains a requirements.txt file:
pip install -r requirements.txt
If it does not, install the packages listed in the notebook's import
cells. You can install Jupyter with:
pip install notebook
4. Launch Jupyter Notebook
jupyter notebook
Open MOBILE CAT PERDICT USING ML (CAPSTONE) (1).ipynb and run the
cells in order. Make sure the expected data files and scraping
prerequisites are available.
📊 Model Evaluation
Use the notebook as the source of truth for the final model and results.
For a regression task, commonly used evaluation metrics include:

  Metric     What it indicates
  MAE    Average absolute prediction error
  MSE    Average squared prediction error
  RMSE   Prediction error expressed in the target's units
  R²     Proportion of target variance explained by the model

Only report metrics that were actually calculated by the project. The
dataset size, chosen algorithm, train/test split, and final scores
should be added after checking the completed notebook.
Results note: Verified model scores and dataset statistics are not
stated here because they have not been confirmed from the notebook
contents.

🛡️ Responsible Web Scraping
- Check the target website's terms of service and robots.txt.
- Respect rate limits and avoid excessive requests.
- Do not collect personal or sensitive information.
- Keep source attribution and data-collection dates where appropriate.
- Use collected information only for permitted learning and research
  purposes.
⚠️ Limitations
- Web page layouts and product listings can change over time.
- Listed prices may depend on seller, promotion, stock, and collection
  date.
- Missing or inconsistent product attributes can affect model quality.
- Results depend on data quality, feature selection, and validation
  design.
- Predictions are estimates, not guaranteed selling prices.
🔭 Future Enhancements
- [ ] Add a reproducible scraping script with clear configuration and
  error handling.
- [ ] Document the source website and create a data dictionary.
- [ ] Add a requirements.txt file for reproducible setup.
- [ ] Compare multiple regression algorithms with the same validation
  strategy.
- [ ] Include actual-versus-predicted plots and residual analysis.
- [ ] Save the trained model and document how to load it.
- [ ] Build a small interactive interface for estimating prices.
- [ ] Add verified dataset statistics, model metrics, and project
  screenshots.
👨‍💻 Author
::: {align="center"}
### Parthasarathi A

**Data Analytics \| Data Science \| Machine Learning**

[![GitHub](https://img.shields.io/badge/GitHub-ParthasarathiAnalytics-181717?style=for-the-badge&logo=github)](https://github.com/ParthasarathiAnalytics)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit%20Website-6C63FF?style=for-the-badge&logo=vercel&logoColor=white)](https://parthasarathi-analytics.vercel.app/)
:::::: {align="center"}
**⭐ If you find this project useful, consider starring the
repository.**

*Built as a data science capstone project for learning and
experimentation.*
:::Disclaimer
This is an educational project. Data availability, scraping behavior,
and model predictions depend on the implementation and the source data.
Validate the notebook's results before using them in a portfolio
presentation or business decision.
