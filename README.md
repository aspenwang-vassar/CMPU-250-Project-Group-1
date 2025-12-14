# CMPU-250 Group 1 Project: Healthcare Data Analysis

This repository contains the code, data, and reports used for a CMPU-250 course project. The goal of this project is to analyze healthcare data, perform exploratory data analysis (EDA), and generate predictive models or insights as documented in the final reports.

-----------------------------

This repository includes:

* `data/`
  This directory contains the datasets used throughout the project lifecycle:
  * `healthcare_dataset.csv`: The raw source dataset.
  * `cleaned_data.csv`: The preprocessed dataset used for analysis.
  * `full_data.csv`: The complete dataset with correlation injected.
  * `README.md`: Documentation specific to the data files.

* `eda/`
  Contains the exploratory analysis work:
  * `Group1_EDA.ipynb`: The Jupyter Notebook containing visualization, summary statistics, and initial data exploration logic.
  * `README.md`: Details on the EDA process.

* `preliminary_report/`
  Artifacts relating to the mid-project checkpoint:
  * `Group_1_Preliminary_Analysis.ipynb`: The code script for initial modeling and testing.
  * `Group 1 Preliminary Analysis Report.pdf`: The submitted PDF report summarizing preliminary findings.
  * `README.md`: Context for the preliminary submission.

* `final_report/`
  The final deliverables for the project:
  * `Group_1_Final_Analysis.ipynb`: The comprehensive analysis notebook containing the final models and evaluation metrics.
  * `Group 1 Final Report.pdf`: The comprehensive final paper.
  * `README.md`: Overview of the final submission.

* `presentation/`
  Materials used for the project presentation:
  * `Group 1 CMPU-250 Project Slides.pdf`: The slide deck presented to the class.
  * `README.md`: Presentation notes or context.

* `proposal/`
  * `Group 1 Project Proposal.pdf`: The initial project proposal outlining our research questions and methodology.
  * `README.md`: Proposal specific documentation.

* `figures/`
  * Directory for storing generated plots and figures used in the reports.

* `peer_review/`
  * Documentation regarding peer reviews conducted during the course.

* `scripts/`
  * Utility scripts and project configuration files (e.g., `.gitignore`).

-----------------------------

## Setup & Installation

### 0. Clone the Repository
Start by cloning this repository to your local machine:

```bash
git clone [https://github.com/your-username/CMPU-250-Group-1.git](https://github.com/your-username/CMPU-250-Group-1.git)
cd CMPU-250-Group-1

```

### 1. Requirements
Ensure you have Python installed along with Jupyter Notebook to run the `.ipynb` files. You can install necessary libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

```

### 2. Directory Structure
The project is organized into modular folders to separate data, analysis code, and written reports.

* Data is located in `./data/`
* Analysis Notebooks are in `./eda/`, `./preliminary_report/`, and `./final_report/`

---

## Usage
### Exploratory Data Analysis
To view the initial data exploration, launch the notebook in the `eda` folder:

```bash
jupyter notebook eda/Group1_EDA.ipynb

```

### Final Analysis Pipeline
To reproduce the final results reported in the PDF, execute the final analysis notebook:

```bash
jupyter notebook final_report/Group_1_Final_Analysis.ipynb

```

---

## Data Format Details
You can load the main datasets using pandas as follows:

```python
import pandas as pd

# Load the raw data
df_raw = pd.read_csv("data/healthcare_dataset.csv")

# Load the cleaned data used for modeling
df_clean = pd.read_csv("data/cleaned_data.csv")

```

