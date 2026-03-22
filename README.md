# SHEIN-Data-Pipeline
# 👗 Fashion Catalog ETL Pipeline
This project demonstrates a full Data Engineering workflow: Extracting nested data from a raw CSV, transforming it using Python/Pandas, and loading it into a clean format for business analysis.

## 📊 Project Workflow
1. **Extraction:** Handled semicolon-separated raw CSV data.
2. **Parsing:** Used `ast.literal_eval` to dynamically extract attributes from JSON-like strings in the `description` column.
3. **Cleaning:** Standardized prices, handled missing brand data, and removed duplicates.
4. **Analysis:** Visualized price distributions, brand market share, and product color trends.

## 📈 Key Findings
- **Catalog Size:** Over 100k unique products processed.
- **Brand Presence:** 99.5% brand attribution across the catalog.
- **Market Segment:** Heavily focused on budget-friendly fashion under $15.

## 🛠️ Tools Used
- **Language:** Python 3.10
- **Libraries:** Pandas, NumPy, Matplotlib
- **Environment:** VS Code / Jupyter
