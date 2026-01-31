# RamenDesu Project 🍜

Project focusing on the analysis and visualization of ramen ratings worldwide.

## Project Structure

- `data/`:
  - `raw/`: Immutable original dataset (`ramen-ratings.csv`).
  - `processed/`: Cleaned and standardized data ready for analysis (`ramen-cleaned.csv`).
- `notebooks/`:
  - `01_data_exploration.ipynb`: Initial data inspection and missing value analysis.
  - `02_cleaned_data_analysis.ipynb`: Final data cleaning and visual analysis (top brands, country distribution, packaging styles).

## Key Features
- **Data Cleaning**: Handling missing values, standardizing country names, and extracting ranking years/ranks.
- **Visualizations**: 
  - Top 20 Ramen Brands.
  - Countries with most Ramen varieties.
  - Distribution of Packaging Styles (grouped by percentage).
  - Highest Rated Brands (weighted by minimum product count).

## Requirements
- pandas
- matplotlib
- seaborn
- numpy
