<img width="711" height="303" alt="image" src="https://github.com/user-attachments/assets/8fd5ac12-08c6-445d-8381-40813dc998f2" />
# 🧠 Automated Account Research Workflow (AI + Web)

This workflow automates account research by using AI to search the web and extract structured information — eliminating the manual research normally done by sales reps during prospecting.

It accepts unstructured inputs such as a **domain** or **company name** and converts them into clean, actionable insights.

---

## 🚀 What This Workflow Does

The workflow uses an **Advanced AI Module** with two main capabilities:

### 🔎 1. Google Research (SerpAPI)
Performs automated Google searches to gather publicly available details about the company.

### 🌐 2. Website Content Extraction
Uses a sub-workflow to visit and collect content from the company’s website to support deeper analysis.

---

## 🧩 Output

From the input, the workflow returns a structured set of properties:

- `domain`  
- `company Linkedin Url`  
- `cheapest plan`  
- `has free trial`  
- `has enterprise plan`  
- `has API`  
- `market` (B2B or B2C)

---

## 🔧 Customizable with n8n

The real strength of n8n is that you can modify this workflow to gather any type of information you want.

- Update the **AI prompt** to specify which details you want the workflow to research.
- Define your preferred output format inside the **Structured Output Parser** module.
- Extend the workflow with additional API calls, scrapers, or sub-workflows as needed.

---

## 📌 Summary

This automation serves as an AI-powered research assistant by combining:
- Google results  
- Website content extraction  
- Structured AI output  

It significantly reduces manual investigation time and helps sales teams prepare their prospecting activities more efficiently.
