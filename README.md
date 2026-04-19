# 🤖 AI-Powered Data Insights
### Automated Business Intelligence Reports using Google Gemini API + Python

---

## 📌 Project Overview
This project demonstrates how to combine **traditional data analytics** 
with **Generative AI** to automatically generate professional business 
insight reports from raw datasets.

A Python script reads a CSV dataset, generates a structured statistical 
summary, and sends it to the **Google Gemini API**, which returns a 
boardroom-ready business intelligence report — in seconds.

---

## 🛠️ Tech Stack
- **Python** (Pandas, Google Generative AI SDK)
- **Google Gemini API** (gemini-1.5-flash)
- **Google Colab** (development environment)
- **Dataset:** Walmart Weekly Sales Dataset (6,435 records, 45 stores)

---

## ⚙️ How It Works

```
CSV Dataset → Data Summary Generation → Gemini API Prompt → 
AI Business Report → Saved as .txt file
```

1. Loads the Walmart sales CSV using Pandas
2. Generates a structured summary (shape, statistics, missing values, 
   sample rows, holiday breakdown)
3. Builds a role-based prompt assigning Gemini as a Senior Data Analyst
4. Sends the summary to Gemini API and receives a 7-section report
5. Saves the full report as a downloadable text file

---

## 📊 Report Sections Generated
1. Executive Summary
2. Key Findings (5 data-backed insights)
3. Sales Performance Analysis
4. Economic Impact Analysis (CPI, Unemployment, Fuel Price)
5. Holiday Impact Analysis
6. Actionable Recommendations (3 strategies)
7. Risk Flags (2 quantified risks)

---

## 📈 Sample Output
![Sample Output]<img width="1219" height="406" alt="sample output screenshot" src="https://github.com/user-attachments/assets/33282311-6532-4f3d-ae3f-9adce9004015" />


> Full report available here: [walmart_insights_report.txt](walmart_insights_report.txt)

---

## 🚀 How to Run This Yourself

### Step 1 — Get a Free Gemini API Key
Visit [aistudio.google.com](https://aistudio.google.com) and generate 
a free API key.

### Step 2 — Open in Google Colab
[![Open In Colab](API_Powered_Data_Insights.ipynb)](https://colab.research.google.com/)

Upload this notebook and your dataset CSV to Colab.

### Step 3 — Install Dependencies
```python
!pip install google-generativeai -q
```

### Step 4 — Add Your API Key
Replace `paste_your_api_key_here` in Cell 4 with your actual Gemini 
API key.

### Step 5 — Run All Cells
Run cells in order (1 → 5). The report generates in ~15 seconds.

---

## 💡 Key Learnings
- Generative AI can transform raw statistical summaries into 
  professional business narratives in seconds
- Role-based prompting (assigning AI a specific expert persona) 
  dramatically improves output quality and tone
- Combining traditional data analytics (Pandas) with LLM APIs 
  creates a powerful end-to-end insight generation pipeline
- This approach can reduce report-writing time by an estimated 
  60–70% in real analytics workflows

---

## 🔗 Related Projects
- [Walmart Sales Prediction ML](https://github.com/mohitramtekkar5-oss/Walmart-Sales-Prediction-ML)
- [Prompt Engineering Experiments](https://github.com/mohitramtekkar5-oss/Prompt-Engineering-Experiments)

---

## 👤 Author
**Mohit Priya Ramtekkar**  
Data Analyst | ML & Generative AI Enthusiast  
[LinkedIn](https://linkedin.com/in/mohit-priya-ramtekkar) • 
[GitHub](https://github.com/mohitramtekkar5-oss)

---
*This project was built as part of a hands-on Generative AI learning 
journey following the Generative AI for Everyone course by 
DeepLearning.AI on Coursera.*
