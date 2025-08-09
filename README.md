# Credit Risk EDA (Lending Club)

Quick, recruiter-friendly look at default rates across **FICO bands**, **grade**, and **term** using accepted-loans data.

## Results (quick hits)
- Defaults drop from **25.3%** at **FICO 660–679** to **7.1%** at **780+**.
- Lower grades (**E–G**) run about **3.8×** the default rate of **A/B** (**40.9%** vs **10.6%**).
- **60-month** loans default more than **36-month** (**32.5%** vs **16.0%**).

## How to run
- Open the notebook (`LC_Credit_Risk_EDA_clean.ipynb`) in Colab or locally.
- Set `DATA_PATH` to your file path (e.g., `/content/drive/MyDrive/loans.csv` or a small `loans_sample.csv`).
- Run all cells top → bottom. Requirements: `pandas`, `matplotlib`, `jupyter`.

## Notes
- FICO bands are rebucketed to **660+** to reflect LendingClub’s funded population.
- Charts and tables are embedded in the notebook outputs.

