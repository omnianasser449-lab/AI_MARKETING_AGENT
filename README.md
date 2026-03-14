# 🤖 AI Marketing Agent
### Python + Gemini AI Portfolio Project | Google Colab

---

## 📌 Project Overview

An end-to-end AI-powered marketing agent that automatically analyzes campaign performance data and generates a professional executive report using Google Gemini AI.

Feed it campaign data → it analyzes KPIs → AI writes a full CEO-ready report.

---

## 🔧 Tools & Libraries Used
- **Python** — core language
- **Pandas** — data manipulation and KPI calculations
- **Google Gemini AI** — AI report generation
- **Google Colab** — development environment

---

## 🤖 How The Agent Works
```
Raw Campaign Data (200 campaigns)
        ↓
Python calculates KPIs (ROI, Conversion Rate, Cost Per Conversion)
        ↓
Results sent to Gemini AI with analyst prompt
        ↓
AI generates professional executive report
        ↓
Report saved as file
```

---

## 📊 Dataset

- **200 marketing campaigns** across 12 months
- **5 campaign types** — Email, Search, Social Media, Display, Influencer
- **12 columns** — budget, spend, impressions, clicks, leads, conversions, revenue

---

## 🔍 Project Structure
```
Cell 1 → Install and import libraries
Cell 2 → Connect to Gemini AI API
Cell 3 → Load campaign data
Cell 4 → Calculate KPIs (ROI, Conversion Rate, Cost Per Conversion)
Cell 5 → Send data to AI and generate report
Cell 6 → Save report as text file
```

---

## 📈 KPIs Calculated

| Metric | Formula |
|--------|---------|
| ROI % | (Revenue - Spend) / Spend × 100 |
| Conversion Rate | Conversions / Clicks × 100 |
| Cost Per Conversion | Spend / Conversions |

---

## 💡 Sample AI Report Output

The agent automatically produces a report including:
- Executive Summary with portfolio-wide ROI
- Best performing campaign analysis
- Worst performing campaign analysis
- 3 actionable recommendations
- Budget reallocation suggestion

See `marketing_ai_report.txt` for full sample output.

---

## 🧠 Python Skills Demonstrated

| Skill | Where Used |
|-------|-----------|
| `Pandas` | Load and manipulate campaign data |
| `groupby().agg()` | Calculate KPIs per campaign type |
| `reset_index()` | Clean grouped data |
| `f-strings` | Build dynamic AI prompts |
| `Gemini API` | Connect and query AI model |
| `file handling` | Save AI report as .txt file |

---

## 👤 Author
Built as part of a data analyst portfolio to demonstrate Python, AI integration, and marketing analytics proficiency.
