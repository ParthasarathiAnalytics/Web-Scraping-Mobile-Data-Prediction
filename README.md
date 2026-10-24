Mobile Data Web Scraping & Price Prediction
An end-to-end data science capstone project focused on collecting
mobile-phone listing data through web scraping and applying machine
learning techniques to predict mobile phone prices.
Project status: This README is based on the files and notebook
listed in the repository. Exact dataset fields, scraping source
details, model choice, and evaluation scores should be confirmed from
the notebook before being reported as final results.

Project Overview
Mobile phones vary widely in price depending on their specifications,
brand, and other product attributes. This project explores how
web-scraped mobile phone data can be prepared for analysis and used to
build a machine learning model for price prediction.

The repository includes: - A Jupyter Notebook for the mobile price
prediction capstone. - A capstone project description PDF. - A project
documentation DOCX. - A capstone presentation.
Business Problem
Comparing mobile phones can be difficult when listings contain many
specifications and price points. A data-driven prediction workflow can
help explore the relationship between phone attributes and listed
prices.

This project investigates the use of collected mobile-phone data to: -
Organize product information for analysis. - Prepare data for machine
learning. - Explore patterns between phone specifications and price. -
Develop a model to estimate mobile phone prices from available features.
Objectives
1. Collect mobile phone listing information using web-scraping
   techniques.
2. Inspect and prepare the collected data for analysis.
3. Perform exploratory data analysis (EDA) to understand the dataset.
4. Select relevant input features for price prediction.
5. Train and evaluate a machine learning model.
6. Document the workflow and communicate the project through a notebook
   and presentation.
Tools & Technologies
  Tool / Technology                   Purpose
  Python                              Data processing and machine
                                      learning

  Jupyter Notebook                    Interactive analysis and
                                      experimentation

  Pandas                              Data manipulation and preparation

  NumPy                               Numerical operations

  Web-scraping libraries              Extracting information from web
                                      pages, depending on the notebook
                                      implementation

  Matplotlib / Seaborn                Visualization, if used in the
                                      notebook

  Scikit-learn                        Machine learning and evaluation, if
                                  used in the notebook
The table describes the typical roles of these tools in this workflow.
Verify the notebook imports to confirm the exact libraries used in this
project.
Repository Contents
  File                                                 Description
  MOBILE CAT PERDICT USING ML (CAPSTONE) (1).ipynb   Main notebook for the mobile price
                                                       prediction workflow

  CAPSTONE PROJECT bY SARATHI.docx                   Project documentation

  Cap Stone Project Description.pdf                  Capstone project brief /
                                                       description

  capstone ppt (wecompress.com).pptx                 Project presentation
  README.md                                          Project overview and usage guide
Workflow
1. Web Data Collection
Use web-scraping techniques to gather mobile phone listing information.
The specific website, fields collected, and scraping method should be
taken from the notebook and project documentation.
2. Data Preparation
Inspect the collected data for missing values, inconsistent formats,
duplicates, and data types. Apply only the cleaning steps appropriate to
the actual dataset.
3. Exploratory Data Analysis
Explore the distribution of mobile phone prices and investigate how
available specifications or product attributes relate to price. Use
charts and summary statistics where appropriate.
4. Feature Preparation
Choose suitable input variables and prepare them for model training.
Categorical fields may require encoding, and numeric fields may need
cleaning or transformation depending on the chosen algorithm.
5. Model Training
Train a regression model to estimate mobile phone prices from the
selected features. The specific algorithm and parameters should be
confirmed from the notebook.
6. Model Evaluation
Evaluate predictions using suitable regression metrics such as MAE, MSE
/ RMSE, and R², if these are calculated in the notebook. Report the
actual values from the notebook rather than assuming a score.
Getting Started
Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- The Python libraries imported by the notebook
1. Clone the repository
git clone https://github.com/ParthasarathiAnalytics/Web-Scraping-Mobile-Data-Prediction.git
cd Web-Scraping-Mobile-Data-Prediction
2. Create and activate a virtual environment (recommended)
Windows
python -m venv .venv
.venv\Scripts\activate
macOS / Linux
python3 -m venv .venv
source .venv/bin/activate
3. Install dependencies
Install the libraries required by the notebook. If a requirements.txt
file is added to the repository, use:
pip install -r requirements.txt
If there is no dependency file, install the packages listed in the
notebook's import cells.
4. Launch Jupyter
pip install notebook
jupyter notebook
Open MOBILE CAT PERDICT USING ML (CAPSTONE) (1).ipynb and run the
cells in order. Ensure any required dataset files and browser / scraping
dependencies are available before running the relevant cells.
Results
The notebook should be treated as the source of truth for: - The number
of records collected. - The final features used for prediction. - The
algorithm selected. - Train/test split and validation approach. -
Evaluation metrics and final model performance.

These values are intentionally not stated here because they could not be
independently confirmed from the repository preview.
Responsible Web Scraping
- Review the target website's terms of service and robots.txt before
  collecting data.
- Respect rate limits and avoid sending excessive requests.
- Do not collect personal or sensitive information.
- Use scraped information for permitted learning and research
  purposes.
Limitations
- Web pages and product listings can change over time.
- Scraped prices may be affected by promotions, availability, seller,
  and collection date.
- Model performance depends on data quality, feature selection, and
  validation methodology.
- Predictions are estimates and should not be treated as guaranteed
  market prices.
Future Improvements
- Add a reproducible scraper with clear configuration and error
  handling.
- Save raw and cleaned datasets separately and document the data
  dictionary.
- Add a requirements.txt file and step-by-step execution
  instructions.
- Compare multiple regression algorithms using the same validation
  strategy.
- Include actual-versus-predicted plots and residual analysis.
- Save the trained model and, if appropriate, build an interactive
  prediction interface.
- Add verified metrics and screenshots from the completed notebook.
Author
Parthasarathi A
- GitHub:
  ParthasarathiAnalytics
- Portfolio: Data Analytics
  Portfolio
Disclaimer
This repository is an educational capstone project. Scraping
availability, dataset coverage, and model predictions depend on the data
and implementation. Confirm all reported results against the notebook
before using them in a portfolio, presentation, or business decision.
