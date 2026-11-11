# 🚕 Taxi Data Analysis Using Python

## 📌 Project Overview

This project focuses on cleaning, analyzing, and visualizing taxi trip data using Python. The Seaborn Taxis dataset is used to explore fare trends, trip distances, pickup borough activity, and customer payment behavior through data analysis and visualization techniques.

## 🎯 Project Objective

To clean, analyze, and visualize taxi trip data using Python, Pandas, Matplotlib, and Seaborn to identify fare trends, trip distance patterns, pickup borough activity, and customer payment behavior.

## 🛠️ Technologies & Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## 📂 Dataset

**Dataset Name:** Taxis Dataset

**Source:** Seaborn Built-in Dataset

```python
import seaborn as sns

df = sns.load_dataset("taxis")
```

The dataset contains information about taxi trips, including pickup and drop-off timestamps, distance, fare, tips, tolls, payment methods, and pickup/drop-off locations.

## 🔍 Project Workflow

### 1. Data Loading and Exploration
- Load the Seaborn Taxis dataset.
- Display the first and last five records.
- Check dataset shape, columns, and data types.
- Generate descriptive statistics.
- Inspect dataset information.

### 2. Data Cleaning
- Identify missing values.
- Convert pickup and drop-off columns into datetime format.
- Handle missing numerical values using median imputation.
- Handle missing categorical values using mode imputation.
- Remove rows with missing critical pickup timestamps.
- Verify the cleaned dataset.

### 3. Data Visualization

#### 📊 Matplotlib / Pandas Charts

| No. | Chart | Analysis |
|---|---|---|
| 1 | Line Chart | Taxi Fare Over Time |
| 2 | Bar Chart | Total Fare by Pickup Borough |
| 3 | Pie Chart | Payment Method Distribution |
| 4 | Histogram | Trip Distance Distribution |
| 5 | Box Plot | Tip Distribution by Pickup Borough |

#### 📈 Seaborn Charts

| No. | Chart | Analysis |
|---|---|---|
| 6 | Count Plot | Number of Trips by Pickup Borough |
| 7 | Scatter Plot | Distance vs Fare |
| 8 | Heatmap | Correlation Between Numerical Variables |
| 9 | Pair Plot | Relationships Between Distance, Fare, Tip, and Total |
| 10 | Violin Plot | Fare Distribution by Payment Method |

## 📌 Key Analysis

The project explores:

- Taxi fare variations over time.
- Total fare collected across pickup boroughs.
- Distribution of payment methods.
- Common taxi trip distance ranges.
- Tip amount variations across boroughs.
- Relationship between trip distance and fare.
- Correlations among numerical variables.
- Fare distribution across payment methods.

## 📁 Project Structure

```text
Taxi-Data-Analysis-Using-Python/
│
├── Taxi_Data_Analysis.py
│
├── README.md
│
└── requirements.txt
```

## ⚙️ Installation

Install the required Python libraries:

```bash
py -m pip install numpy pandas matplotlib seaborn
```

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Taxi-Data-Analysis-Using-Python.git
```

2. Navigate to the project folder:

```bash
cd Taxi-Data-Analysis-Using-Python
```

3. Run the Python file:

```bash
py Taxi_Data_Analysis.py
```
