# London Bike Rides

This project uses bike ride data in London to clean and analyze the data, followed by visualizing the results using Tableau. The project workflow includes data manipulation in Python, data cleaning, and then visualization in Tableau to extract valuable insights.

## Project Structure

The project folder contains the following files:

### 1. **Data**:
- `london_bike_final.xlsx`: The Excel file containing the raw bike ride data from London. This file serves as the primary data source for the project.

### 2. **Data Manipulation**:
- `london.ipynb`: A Jupyter Notebook containing the Python code used to clean and preprocess the raw bike ride data. The code performs data cleaning tasks such as handling missing values, removing outliers, and transforming the data into a format suitable for analysis.

### 3. **Visualizations**:
- `London Bike Rides - Moving Average and Heatmap.twbx`: A Tableau workbook file that contains the visualizations based on the cleaned data. This workbook includes interactive charts and dashboards designed to provide insights into bike ride patterns across London.

## Requirements

Before running the project, ensure you have the following tools installed:

### 1. **Python 3.x**:
You’ll need Python 3.x to run the `data_cleaning.ipynb` file.

### 2. **Jupyter Notebook**:
To interact with and execute the `data_cleaning.ipynb` notebook.

### 3. **Tableau**:
To view and explore the visualizations in the `london_bike_rides.twb` file.

### Python Libraries:
The `data_cleaning.ipynb` file requires the following Python libraries:
- **pandas** for data manipulation.
- **zipfile** for extracting zip archives.
- **kaggle** for downloading datasets directly from Kaggle.
```bash
pip install pandas numpy matplotlib seaborn
