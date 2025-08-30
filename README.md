# 🧹 Automated EDA Workflow (n8n + AI)

This project contains an **n8n workflow** for automated **Exploratory Data Analysis (EDA)** with integrated AI reporting.

---

## ⚙️ Features
- ✅ Null value detection & cleaning  
- ✅ Duplicate row handling  
- ✅ Data type fixing (e.g., numeric strings → floats)  
- ✅ Outlier detection using **Z-score method**  
- ✅ AI-generated **Business Insight Report** (via OpenRouter LLM)  
- ✅ Automatic chart generation using [QuickChart.io](https://quickchart.io)  
- ✅ Exports to Google Sheets + Email delivery  

---

## 📊 Workflow Overview
1. **Google Sheets → n8n**: Import raw dataset  
2. **Data Cleaning**: Handle nulls, duplicates, type mismatches, outliers  
3. **AI Agent**: Generate executive summary & insights  
4. **Chart Generator**: Create visualizations (bar/line/pie/heatmap)  
5. **Output**: Save cleaned dataset to Google Sheets + email structured report  

---

## 🚀 Usage
1. Import `workflows/eda_automatic.json` into your **n8n instance**.  
2. Configure credentials for:  
   - Google Sheets  
   - Gmail (for report delivery)  
   - OpenRouter API (LLM agent)  
3. Run workflow manually or set a schedule trigger.  

---

## 📸 Example Output
- **📊 Report:** Automated Executive Summary with metrics & action items  
- **📈 Chart:** QuickChart URL embedded in email  
- **📥 Delivery:** Report sent directly via Gmail  

---

## 🔮 Future Improvements
- Add anomaly detection for categorical features  
- Integrate visualization dashboards (e.g., Metabase / Power BI)  
- Enable Slack/Teams notifications  
