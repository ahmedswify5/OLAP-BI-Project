# Enterprise OLAP Data Warehouse & Business Intelligence Solution

An end-to-end Data Warehousing, OLAP, and Business Intelligence project built using the Microsoft BI (MSBI) stack. This project processes, models, and analyzes IMDB movie data to deliver multi-dimensional insights and reporting.

## 🚀 Project Architecture & Workflow

1. **Extraction, Transformation, Loading (ETL) - SSIS:**
   - Source data preprocessing (`preproscing_imdb.csv`)[cite: 1, 6].
   - Cleaning, transforming, and loading raw data into a structured relational database.

2. **Dimensional Modeling & Data Warehouse:**
   - Implemented a **Star Schema** architecture, separating fact tables from dimension tables to optimize query performance and data integrity.

3. **Multidimensional OLAP Cubes - SSAS:**
   - Designed and processed OLAP cubes (`SSAS LAP`) to enable fast aggregation, slicing, and dicing of metrics like movie ratings, runtimes, and genres.

4. **Reporting & Visualization - SSRS & Power BI:**
   - Built interactive paginated reports (`BI_proj1`) and dashboards to visualize key performance indicators (KPIs) and analytical trends.

## 🛠️ Tech Stack
- **Database / ETL:** SQL Server, SSIS (SQL Server Integration Services)[cite: 2]
- **OLAP & Modeling:** SSAS (SQL Server Analysis Services)[cite: 3]
- **Reporting:** SSRS (SQL Server Reporting Services)[cite: 1] & Power BI
- **Languages / Data:** Python, SQL, CSV datasets[cite: 6]

## 📂 Project Structure
- `BI_proj1.slnx` - SQL Server Reporting Services (SSRS) project solution[cite: 1].
- `SSAS LAP.slnx` - SQL Server Analysis Services (SSAS) multidimensional cube solution[cite: 3].
- `SSIS2.slnx` - SQL Server Integration Services (SSIS) ETL pipelines solution[cite: 2].
- `preproscing_imdb.csv` - Cleaned IMDB raw dataset[cite: 6].
