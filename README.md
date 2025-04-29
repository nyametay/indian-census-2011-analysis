# 🇮🇳 Indian Census 2011 Data Analysis

This repository contains a Jupyter Notebook that performs data analysis on the 2011 Census of India. It uses Python and pandas to explore demographics, religion, workforce, and other metrics at the state and district levels.

---

## 📓 Notebook Overview

**`Indian 2011 Census Data Analysis.ipynb`** includes:
- Loading and inspecting census data
- Cleaning and understanding missing data
- State-wise aggregation of population and religion statistics
- Filtering and indexing DataFrames
- Manipulating column names with suffixes and prefixes

---

## 🧾 Dataset Description

The dataset includes:
- District-level population counts
- Religious demographics (Hindus, Muslims, Christians, Sikhs, Buddhists, Jains)
- Worker statistics (including gender)
- Education and literacy indicators

> **Dataset used:** `Census+2011.csv`  
> Please place the CSV file inside a `../Datasets/` directory or update the path in the notebook accordingly.

---

## 📊 Analysis Highlights

1. **Visual Tweaks**  
   - Hiding DataFrame index  
   - Setting captions using `.style.set_caption()`

2. **Filtering Data**  
   - Show data for specific districts: New Delhi, Lucknow, Jaipur

3. **Aggregated Statistics**  
   - State-wise total population  
   - Religion-wise population summary per state  
   - Total male workers in Maharashtra

4. **DataFrame Indexing & Naming**  
   - Setting `District_code` as index  
   - Adding suffixes or prefixes to all column names

---

## 🛠️ Requirements

Install the required dependencies with:

```bash
pip install pandas
```
## Running the Notebook
1. Clone the repository:

```bash
git clone https://github.com/your-username/indian-census-2011-analysis.git
cd indian-census-2011-analysis
```
2. Launch Jupyter Notebook:

```bash
jupyter notebook
```
Open Indian 2011 Census Data Analysis.ipynb and run the cells to explore the data.

