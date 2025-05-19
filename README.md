# The Lottery Lot
*Natsuura Fukuda* | *Math 37700: Applied Statistics and Probability* | *Spring 2025*

---

## Table of Contents  
1. [Project Overview](#project-overview)  
2. [Data Description](#data-description)   
3. [Project Structure](#project-structure)  
4. [Project Flow](#project-flow)  
5. [Notebooks & Modules](#notebooks--modules)  
6. [Results & Deliverables](#results--deliverables)  
7. [Slide Deck](#slide-deck)  
8. [License](#license)  

---

## Project Overview  
**Problem Statement**  
> The lottery is innately unpredictable and uncertain but the variables at play during the purchase of the lottery ticket could affect the possibility of being a winner. The goal is to identify if there are variables that can skew the lottery in one’s favor or if it is purely random. 
> Some challenges are that lotteries are regional, so demographic may skew towards that region (in this case Texas), lack of results if the lottery really is just chance, outliers skewing the data.

**Proposed Solution**  
> By compiling and finding trends in data of Texas Lottery winners, we aim to pinpoint certain aspects such as:
> - Demographic of buyer
> - Ticket information
> - Location of retailer

> By comparing and contrasting these variables we can find most likely traits that make up a lottery winner, providing clues to if distribution of lottery tickets, types of people who buy them make a difference in who wins the lottery.

**Impact**  
> The impact that this project has includes:
> - Having more people win the lottery, more evenly distributing wealth between lottery players
> - Making the lottery more “equal” by identifying skewing variables
> - Identify demographics prone to gambling

---

## Data Description  
- **Source:** data.texas.gov  
- **Raw Files:** Located under `data/raw/Winners_List_of_Texas_Lottery__Prizes_20250418`   
- **Processed Files:** `data/processed/`  

| File name | Description |
|-----------|-------------|
| `data/raw/Winners_List_of_Texas_Lottery__Prizes_20250418` | Original full dataset |
| `data/processed/Draw_Ticket.csv` | Cleaned & split dataset |
| `data/processed/ScratchTicket.csv` | Cleaned & split dataset |
| `data/processed/Draw_Ticket_Encoded.csv` | Encoded & split training set |
| `data/processed/Scratch_Ticket_Encoded.csv` | Encoded & split training set |
| `data/processed/freq_mappings_X_d.json`  | Mapping of encoding |
| `data/processed/freq_mappings_X_s.json`  | Mapping of encoding |

---

## Project Structure  
    CapstoneProject/
    ├── README.md
    ├── .gitignore
    ├── requirements.txt
    ├── .gitattributes
    │
    ├── data/
    │   ├── raw/                # Immutable source data
    │   └── processed/          # Cleaned, feature‑engineered data
    │
    ├── notebooks/              # Jupyter notebooks
    │   ├── 01-data-loading-cleaning.ipynb
    │   ├── 02-eda.ipynb
    │   ├── 03-baseline-models.ipynb
    │   └── 04-final-modeling.ipynb
    │
    ├── outputs/                # Figures
    |   └── figures/
    |
    ├── slides/                 # Slide deck PDF & source
    |   ├── Capstone Sprint 1 Presentation NF.pdf
    └── └── Capstone Final Presentation.pdf

---

## Project Flow  

    Raw Data Ingestion  →  Data Cleaning  
    Data Cleaning       →  Feature Engineering  
    Feature Engineering →  Exploratory Data Analysis  
    EDA                 →  Baseline Modeling  
    Baseline Modeling   →  Advanced Modeling & Optimization  
    Advanced Modeling   →  Model Evaluation & Interpretation
    Evaluation          →  Deployment & Reporting  

1. **Raw Data Ingestion** – load source files and validate schema.  
2. **Data Cleaning** – handle missing values, remove duplicates, standardize formats.  
3. **Feature Engineering** – create new variables, encode categoricals, scale numerics.  
4. **Exploratory Data Analysis** – generate summary statistics and key visualizations (bar plots)
5. **Baseline Modeling** – decision tree to get simple understanding and set benchmark
6. **Advanced Modeling & Optimization** – simple neural network
7. **Model Evaluation & Interpretation** – compare metrics (MSE, R Squared) and interpret data
8. **Deployment & Reporting** – create figures in `outputs/figures/`, assemble slide deck.

---

## Notebooks & Modules  
| Path | Purpose |
|------|---------|
| `notebooks/01-data-loading-cleaning.ipynb` | Data ingestion, cleaning, and saving processed files |
| `notebooks/02-eda.ipynb` | Visual and statistical exploration of cleaned data |
| `notebooks/03-baseline-models.ipynb` | Fit and evaluate initial benchmark models |
| `notebooks/04-final-modeling.ipynb` | Advanced modeling, optimization, and final evaluation |

---

## Results & Deliverables  
- **Key Figures** – located in `outputs/figures/` (e.g., feature importance, ROC curve)  
- **Metrics Summary** – documented in notebooks and slide deck  

---

## Slide Deck  
*Location:* `/slides/Capstone Final Presentation.pdf`  
Slides covering: overview, data & preprocessing, key insights, model results, demo/design & next steps.

---

## License  
This project is licensed under the **MIT License** – see `LICENSE` for details.
