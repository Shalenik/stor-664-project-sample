# STOR 664 Project Folder Template

This template is designed to provide an overview of the different steps of the project, how to structure your repository, and expectations for each component.

---

## What to Do

1) **Set up your repository**  
    - Clone or copy this template repository. 
    - Use the same folder structure and naming conventions.
2) **Document your work**  
    - Update your `README.md` following the directions below.
    - Keep all code, data, and reports within the appropriate folders (outlined below). 
3. **Submit your reports**  
    - Upload your completed reports to **GradeScope**.  
    - Ensure the same reports are available in your `/report` folder on GitHub.

---

## README Setup
In your README.md there should be five sections:

1) Project Name
2) Team Members and their github ids
3) Overview or description of project
4) Overview or description of repository
5) Basic usage explanation

For example:


# stor-664-project-sample

## Team Members
- Member 1 (@user1)
- Member 2 (@user2)
- Member 3 (@user3)
- Member 4 (@user4)

## Overview
This repository contains the group project for [STOR 664, Fall 2025].  
Our goal is to ... using data ... and methods ....
Results show ...

## Repository Structure
| Folder | Purpose | Key Files |
|---------|----------|-----------|
| `/data/raw` | Original unmodified datasets | `data1.csv`, `data2.csv` |
| `/data/processed` | Cleaned datasets ready for analysis | `merged_data.rds` |
| `/src` | Analysis and visualization code | `02_fit_models.R`, `03_generate_figures.R` |
| `/results/tables` | Numeric summaries | `model_performance.csv` |
| `/results/figures` | Visual outputs | `figure1.png` |
| `/report` | All written deliverables | `01_introduction.md`, `final_report.qmd` |

## Getting Started
### 1. Clone the repository

```bash
git clone <your .git url>
cd stor-664-project-sample
```

### 2. Install dependencies
Example in R:
```r
renv::restore()
```

Example in Python:
```python
pip install -r requirements.txt
```

### 3. Running Analysis Scripts
```r
Rscript scripts/03_generate_figures.R
```

