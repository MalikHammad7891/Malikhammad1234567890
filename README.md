📌 Project Overview
Laplytics is a data analysis and machine learning preprocessing project designed to explore and prepare a laptop specifications dataset for predictive modeling.  
It covers **Exploratory Data Analysis (EDA)**, **Feature Engineering**, **Dimensionality Reduction**, and **Feature Selection** to identify the most influential factors affecting laptop prices.


🚀 Features
- **Data Cleaning**: Removing duplicates, unnecessary columns, and converting data types.
- **Exploratory Data Analysis**:
  - Histograms & boxplots for price distribution
  - Correlation heatmaps
  - Company-wise price comparisons
- **Feature Engineering**:
  - Extracting screen resolution
  - Creating `PPI` (Pixels Per Inch)
- **Dimensionality Reduction**:
  - Applying **Principal Component Analysis (PCA)**
- **Feature Selection**:
  - Using **SelectKBest (f_regression)** to identify top features
- **Visualizations**:
  - Price trends and comparisons
  - PCA scatter plots
  - Heatmaps


 📊 Dataset
- **Source**: Laptop specifications dataset (CSV format)
- **Columns**:
  - Company, TypeName, Inches, ScreenResolution, Cpu, Ram, Memory, Gpu, OpSys, Weight, Price
- **Target Variable**: `Price`

🛠️ Technologies Used
- **Python 3.x**
- **Pandas** – Data manipulation & analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical data visualization
- **scikit-learn** – PCA, feature selection, preprocessing
