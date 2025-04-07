## 📊 Crop Yield Analysis Using Climate and Agricultural Factors

### 🌱 Overview
This project investigates the relationship between agricultural inputs (like rainfall, pesticides, and temperature) and crop yield across different countries from 1990 to 2013. The analysis uses data visualization and statistical techniques to uncover patterns that can inform sustainable farming practices.

---

### 📂 Dataset Description
The dataset used in this project contains agricultural and climate information with the following variables:

| Variable | Description |
|----------|-------------|
| `Area` | Country name |
| `Item` | Crop type |
| `Year` | Year (1990–2013) |
| `average_rain_fall_mm_per_year` | Average yearly rainfall (mm) |
| `pesticides_tonnes` | Pesticide usage in tonnes |
| `avg_temp` | Average temperature |
| `hg/ha_yield` | Crop yield (hectogram/hectare) |

---

### 📌 Project Workflow

The notebook follows a structured, step-by-step approach:

1. 🔧 **Import Libraries**  
   Essential Python packages for data manipulation and visualization.

2. 📥 **Read Dataset**  
   Load the dataset and review basic information (shape, types, missing values).

3. 🔍 **Dataset Overview**  
   Statistical summary and basic EDA to understand data distribution and outliers.

4. 📈 **Data Visualization**  
   - Trend of crop yield over time  
   - Temperature and rainfall analysis  
   - Correlation heatmap  
   - Country-wise comparisons  

5. 🧪 **Insights & Conclusions**  
   Final thoughts derived from visualizations and observations.

---

### 🚀 How to Run

Clone this repository and install required packages:

Open the Jupyter Notebook:

```bash
jupyter notebook ADS_Internal_Assessment.ipynb
```

---

### 🧰 Requirements

The following Python libraries are used in this project:

- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `plotly` *(optional)*  
- `sklearn` *(if any ML modeling added later)*

You can install them with:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn
```

---



---

### 🙌 Acknowledgments

- Dataset sourced from [FAOSTAT](http://www.fao.org/faostat/)
- Color styling inspired by custom notebook themes.

---

### 📌 Author

**Aditya Shirke**  


---
