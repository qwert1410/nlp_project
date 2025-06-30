# Repository Overview

This repository contains two main modules: one for **Attribution Methods** and another for **Chain of Thought**.

## Attribution Folder

In the `attribution` folder, the main script for processing the data is **`LLM_attribution.ipynb`**. It was developed for use in Google Colab, so the file paths are tailored for that environment but can be modified as needed. This script performs attribution analysis using GPT, BERT, and LLaMA models on the ERASER dataset, as well as BERT and GPT analysis on the COSE dataset. The results are saved as Parquet files in batches to prevent data loss due to potential disconnections.

The second script, **`metrics.ipynb`**, processes the results and calculates key metrics: **recall**, **F1-score**, and **span-hit recall**. This script also saves the computed metrics as Parquet files.

The final script, **`plot.ipynb`**, generates the plots used in our paper.
