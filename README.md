# 🎪 Maven Toys — Power BI Report

**Maven Toys** is a Power BI report that visualizes sales, customer behaviour, and product performance for a toy retailer.  
This repo contains the Power BI Desktop file (`Maven Toys.pbix`) and supporting notes so collaborators can open, inspect, and reuse the report.

---

## 🔎 What's inside
- `Maven Toys.pbix` — main Power BI Desktop file (report + data model + visuals)  
- `README.md` — this file  
- `Data/` *(optional)* — source CSV / Excel files (if included)   
---

## 🎯 Purpose
- Visualize sales & revenue trends  
- Explore top products, categories, and customer segments  
- Surface geographic performance & seasonality  
- Provide interactive dashboards for quick business decisions

---

## 🧰 Tools & Requirements
- **Power BI Desktop** — install the latest stable release from Microsoft.  
- If the report uses external live sources (SQL, cloud, API) you may need credentials to refresh data.  
- **Optional:** Git LFS for versioning `.pbix` files if the file is large (>100 MB).

---

## 🚀 How to open the report
1. Download `Maven Toys.pbix` from this repo (https://github.com/Nishchalaa/Maven-Toys-Analysis.git).  
2. Install & open **Power BI Desktop**.  
3. File → Open → pick `Maven Toys.pbix`.  
4. If prompted to update data source credentials, provide them (or skip refresh to explore visuals offline).

---

## ⚠️ Notes & Caveats
- `.pbix` files are binary. Git diffs are not human-readable — snapshots only.  
- GitHub web UI blocks single files >100 MB. Use Git LFS, Releases, or cloud storage for big PBIX files.  
- Remove or anonymize any sensitive data before sharing publicly.

---

## 📁 Suggested repo structure
