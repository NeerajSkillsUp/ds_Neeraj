# Data Science Assignment: Trader Sentiment Analysis

This repository contains the submission for the Web3 Trading Team data science assignment.

**Candidate:** ds_Neeraj

### Google Colab Notebook Link

As required by the instructions, here is the link to the live Google Colab notebook used for this analysis.

**[https://colab.research.google.com/drive/1bzTIvVniTZuPpDuy4Ked8pzZWI1vjnSi?usp=sharing]**

*(Access is set to "Anyone with the link can view" as per the instructions).*

---

### Project Structure

This repository follows the exact structure specified in the assignment instructions:

ds_<your_name>/ ├── notebook_1.ipynb ├── csv_files/ │ └── (Empty - Original data sourced from links) ├── outputs/ │ ├── pnl_by_sentiment.png │ ├── volume_by_sentiment.png │ ├── side_by_sentiment.png │ └── (leverage_by_sentiment.png was skipped) ├── ds_report.pdf └── README.md

---

### Key Finding: Data Incompatibility

A critical part of this analysis was data validation. The provided datasets were found to be incompatible, which prevents the core analysis from being completed.

1.  **Date Mismatch:** The trader data (`historical_data.csv`) is from **2024-2025**, while the sentiment data (`fear_greed_index.csv`) is from **2018**. There are no overlapping dates, making a merge impossible.

2.  **Missing Data:** The 'leverage' column, required for risk analysis, is missing from the trader dataset.

The `ds_report.pdf` contains a full explanation of these findings. The `Notebook_1.ipynb` script includes a diagnostic check that programmatically confirms this issue. The charts in the `outputs/` folder are blank as a result.