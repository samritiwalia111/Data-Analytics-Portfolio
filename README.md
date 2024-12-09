# London Bike Rides - Data Analytics Portfolio Project

This project demonstrates an end-to-end data analytics process for analyzing **London Bike Rides** using **Tableau** and **Python**. The analysis focuses on creating insights through moving averages and heatmaps of bike ride data, leveraging both Python for data cleaning and Tableau for data visualization.

## Project Structure

The project folder contains the following files:

### 1. **Data**:
- `london-bike-sharing-dataset.zip`: A zip file containing the raw dataset of London bike-sharing information.
  
### 2. **Data Processing (Python)**:
- `london_bikes.ipynb`: A Jupyter Notebook that contains the Python code for data cleaning, preprocessing, and exploratory analysis. This notebook handles tasks like missing data treatment, feature engineering, and merging different data sources.
- `london_bikes_final.xlsx`: The final cleaned and processed dataset saved in Excel format, ready for use in Tableau for visualization.
- `london_merged.csv`: A CSV file containing the merged dataset, which combines various features and datasets for deeper analysis.

### 3. **Visualizations (Tableau)**:
- `London Bike Rides - Moving Average and Heatmap.twbx`: A Tableau workbook that includes interactive visualizations of bike ride patterns. The workbook includes:
  - **Moving Average**: A time series analysis of bike rides to identify trends and seasonality.
  - **Heatmap**: A heatmap visualization of bike rides across different locations and times.

## Requirements

### 1. **Python 3.x**:
Ensure you are using Python 3.x to run the `london_bikes.ipynb` notebook.

### 2. **Required Libraries**:
The Python notebook requires the following libraries to process and clean the data:
- **pandas** for data manipulation.
- **zipfile** for extracting zip archives.
- **kaggle** for downloading datasets directly from Kaggle.
```bash
