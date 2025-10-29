# STOR 664 Project Folder Template

This template is designed to provide an overview of the different steps of the project, how to structure your repository, and expectations for each component.

---

## What to Do

1) **Set up your repository**  
    - Clone or copy this template repository. 
    - Use the same folder structure and naming conventions.
    - Make sure Dr. Kessler (@dankessler) and Shaleni Kovach (@Shalenik) are invited to the repository.
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

### 2. Install dependencies (optional but highly recommended)
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

---

## Contributing

1) Create a feature branch for each component of the project. For example, for the methods deliverable:
```bash
git checkout -b methods
```

2) Every team member should be working on this branch for the methods component of the project.
   - Use concise, meaningful messages:
     ```
     git commit -m "Add OLS model fitting script"
     ```
4) Before the submission deadline, open a PR and set Dr. Kessler and Shaleni as reviewers. If this is a peer reviwed component, make sure your reviewer(s) have access to the repository and are also assigned as reviewers on the PR. A link to your PR will need to be included as part of your Gradescope submission.
5) Incorporate feedback as necessary, update the feature branch, and close the PR before moving to the next component.
   - Your next feature branch should be created from your newly updated `main` branch.
   - `main` should only be updated from one of the feature branches after a PR.

## Peer Reviewing

For one component of the project you will be asked to peer-review another team's pull request. When doing so, make sure to leave **at least two** constructive comments. You will be asked to provide links to your two comments in Gradescope.

Your peer reviewers should be able to clone and run your repository to reproduce your results.

## Reports

It is highly recommended to render your reports from rmarkdown or quarto. Github will display markdown, PDF, or Jupyter notebooks natively so any of these options can be used in the reports page - however, a PDF will need to be uploaded to Gradescope to recieve a grade for that section.

