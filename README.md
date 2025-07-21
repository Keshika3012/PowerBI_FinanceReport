# Power BI Executive Finance Dashboard
## 🎯 What It Does

- Highlights the month and year with the highest profit  
- Compares revenue and profitability across regions  
- Shows top-performing products and segments with bar charts  

## 📂 Included Files

- `sample_data/Financial Sample.xlsx` – raw Excel dataset  
- `Finance Dashboard.pbix` – the finished Power BI report  
- `documentation/` – notes, transformation steps, and screenshots  
- `DAX-measures.md` – sample DAX: `Total Units Sold`, calendar table example

## 🛠 Key Workflow

1. **Import Data**  
   Load the Excel file via Power BI Desktop sample or file import.

2. **Prepare Data in Power Query**  
   - Convert units to whole numbers  
   - Format segment names (e.g. uppercase)  
   - Rename month column  
   - Filter out discontinued products  
   - Apply changes

3. **Model with DAX**  
   - Create measures (e.g. Total Units Sold)  
   - Generate a Calendar table covering Jan 1, 2013–Dec 31, 2014  
   - Link date relationships between tables

4. **Design the Report**  
   - Title box ("Executive Summary – Finance Report")  
   - Line chart for monthly profit (peaks in Dec 2014)  
   - Map showing profit by country/region  
   - Clustered bar chart of sales by product & segment  
   - Slicers for filtering dates by year/month

5. **Polish Formatting**  
   - Apply a clean theme (e.g. “Executive”)  
   - Add background shapes, shadows, and styled titles

6. **Publish** *(optional)*  
   Share via Power BI Service for live stakeholder viewing
