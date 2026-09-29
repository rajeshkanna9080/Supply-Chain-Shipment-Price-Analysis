# Supply Chain Shipment Price Analysis

## Project Overview
Exploratory data analysis of supply-chain shipment and pricing data using Python. The project focuses on shipment patterns, country distribution, logistics modes, pricing/value fields, product/vendor activity, and delivery performance.

## Dataset
**Source:** Kaggle — Supply Chain Shipment Price Data  
Dataset page: https://www.kaggle.com/datasets/apoorvwatsky/supply-chain-shipment-pricing-data  
Reference notebook supplied by the project owner:  
https://www.kaggle.com/code/divyeshardeshana/supply-chain-shipment-price-data-analysis

Expected dataset file:
`data/SCMS_Delivery_History_Dataset.csv`

## Repository Structure
```text
Supply-Chain-Shipment-Price-Analysis/
├── 01_Supply_Chain_EDA.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── data/
    └── README.md
```

## Analysis Covered
- Data quality and missing values
- Shipment distribution by country
- Shipment-mode and fulfilment analysis
- Pricing / value / freight exploration
- Product, vendor and brand analysis
- Delivery-delay analysis
- Numeric correlation review
- Business insight prompts

## Tools
Python, Pandas, NumPy, Matplotlib, Jupyter Notebook

## How to Run
1. Download `SCMS_Delivery_History_Dataset.csv` from the Kaggle dataset.
2. Place it inside the `data/` folder.
3. Install the packages in `requirements.txt`.
4. Run `01_Supply_Chain_EDA.ipynb`.

## Attribution
The dataset is sourced from Kaggle. This repository contains an original analysis workflow and does not claim ownership of the dataset.
