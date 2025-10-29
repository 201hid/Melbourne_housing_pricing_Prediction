# 🏡 Melbourne Housing Dashboard

### 📊 Overview
This project presents an **interactive data analysis dashboard** of the Melbourne Housing Market, built entirely in **Python (Pyodide/Jupyter Notebook)** using `pandas` and `matplotlib`.  
It explores real-world property data — visualizing price trends, suburb comparisons, and correlations to help identify key housing insights for investors and analysts.

---

### 💾 Dataset
**Source:** [Melbourne Housing Market – Kaggle](https://www.kaggle.com/datasets/anthonypino/melbourne-housing-market)  
**Files Used:** `Melbourne_housing_FULL.csv`

This dataset includes:
- 🏠 **Property Features:** Rooms, Bathrooms, Land Size, Building Area  
- 📍 **Location Details:** Suburb, Region, Distance from CBD  
- 💰 **Sale Info:** Price, Type, Method, Date of Sale  
- 🗺️ **Additional Metadata:** Council Area, Coordinates, and Year Built  

---

### ⚙️ Tech Stack
| Tool | Purpose |
|------|----------|
| **Python (Pyodide)** | Browser-based runtime for JupyterLite |
| **Pandas** | Data cleaning and aggregation |
| **Matplotlib** | Visualization (bar charts, scatter plots, trend lines) |
| **NumPy** | Numerical computations |

---

### 🧠 Key Insights
1. **Top Suburbs:** Visualizes the 10 most expensive suburbs in Melbourne based on median property prices.  
2. **Price Trends:** Tracks median housing prices over time to identify growth or cooling phases.  
3. **Distance Correlation:** Reveals that properties **closer to the Melbourne CBD** have significantly higher prices.  
4. **Feature Correlations:** Displays a heatmap showing the strongest factors affecting price (e.g., rooms, land size, distance).  

---

### 🧾 Notebook Sections
| Section | Description |
|----------|--------------|
| 1️⃣ Import & Load Data | Loads CSV and displays initial overview |
| 2️⃣ Clean Data | Handles missing values, converts date, extracts year |
| 3️⃣ Top Suburbs | Median price comparison by suburb |
| 4️⃣ Price Trend | Price changes over time |
| 5️⃣ Price vs Distance | Scatterplot of price vs proximity to CBD |
| 6️⃣ Correlation Heatmap | Visualizes feature correlations |
| 7️⃣ Summary Insights | Prints analytical summary and findings |

---

### 📈 Example Visuals
- **Top 10 Suburbs Bar Chart**
- **Median Price Trend Line**
- **Price vs Distance Scatter Plot**
- **Correlation Heatmap**

---

### 🚀 How to Run
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/anthonypino/melbourne-housing-market).  
2. Upload the file `Melbourne_housing_FULL.csv` to your Jupyter environment (or JupyterLite/Pyodide).  
3. Open and run the notebook cells **sequentially**.  
4. All visuals will be rendered directly in the browser — no installation or internet access required.

---

### 🧩 Compatibility
✅ Works fully offline in:
- **JupyterLite (Pyodide)**  
- **VS Code Jupyter extension**  
- **Kaggle Notebooks**  
- **Google Colab**  

If using a local environment, you can optionally install `plotly` for interactive charts.

---

### 🔍 Author
**Towhidul Hassan**  
Computer Science Graduate | Telstra Consultant | Data & AI Enthusiast  
📧 [LinkedIn](https://linkedin.com/in/towhidul-hassan) | 🌐 [Portfolio](https://github.com/towhidulhassan)
