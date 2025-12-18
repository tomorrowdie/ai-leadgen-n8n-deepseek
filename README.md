# 🤖 AI B2B Lead Generator (n8n + DeepSeek)
### Powered by [Angry Factory](https://github.com/AngryFactory) | [安能學院 Anergy Academy](https://www.anergyacademy.com)

[![DeepSeek LeadGen Interface](http://www.anergyacademy.com/wp-content/uploads/2025/12/Fill-Up-Form.png)](https://www.anergyacademy.com/zh-cn/ai-leadgen-n8n-deepseek/)

> 🚀 **[View Full Tutorial & Live Demo on AnergyAcademy.com](https://www.anergyacademy.com/zh-cn/ai-leadgen-n8n-deepseek/)**

---

## 🎯 Who is this for? (適用對象)

**This tool is built for high-value B2B sales and call-based service businesses.**
If you need a constant stream of fresh leads but hate manual searching, this automation is for you.

✅ **High-Ticket Sales:** Find decision-makers for expensive products.
✅ **Professional Services:** Insurance Agents, Mortgage Brokers, Real Estate.
✅ **Cold Calling Teams:** Generate phone numbers for your sales team instantly.
✅ **B2B Agencies:** Marketing agencies, SEO firms, and Consultants.

**Stop buying old, dead leads. Generate fresh ones on demand.**

---

## 📖 Introduction (簡介)

**[English]**
A fully automated, no-code Lead Generation agent that finds, verifies, and extracts contact info for any business niche using **n8n** and **DeepSeek API**.

**[中文]**
一個基於 **n8n** 和 **DeepSeek** 的全自動 B2B 潛在客戶開發工具。無需寫代碼，自動搜索、驗證並提取任何行業的客戶聯繫方式（郵箱、電話、網站）。

---

## ✨ Features (功能特點)
* **💰 Ultra Low Cost:** Uses DeepSeek V3 API (<$0.01 per run).
* **⚡ Automated Research:** Finds website, email, phone, and social media links.
* **✅ Data Verification:** AI visits the website to verify it is a legitimate business.
* **📊 Auto-Save:** Automatically saves verified leads to Google Sheets or n8n Tables.

---

## 🚀 Quick Start (快速開始)

### 1. Prerequisites (前置需求)
* **n8n:** [Install n8n](https://n8n.io) (Desktop or Cloud).
* **DeepSeek API Key:** [Get Key Here](https://platform.deepseek.com).

### 2. Installation (安裝步驟)
1.  **Download:** Get the `.json` workflow file from this repository.
2.  **Import:** Open n8n > Click **"Import from File"** > Select the JSON.
3.  **Setup:** Add your DeepSeek API Key (see guide below).
4.  **Run:** Click "Execute" and fill in the form (Niche + Country).

---

## 🛠️ Configuration Guide (配置指南)

### Step 1: Get Your API Key
Login to the **DeepSeek Developer Platform**:
![DeepSeek Login](http://www.anergyacademy.com/wp-content/uploads/2025/12/Add-Deepseek-API-02.png)

Create a new API Key (Label it "n8n"):
![Generate Key](http://www.anergyacademy.com/wp-content/uploads/2025/12/Add-Deepseek-API-04.png)

### Step 2: Connect to n8n
In n8n, create a new **DeepSeek Credential**:
![Create Credential](http://www.anergyacademy.com/wp-content/uploads/2025/12/Add-Deepseek-API-01.png)

Paste your API Key and check the connection:
![Connection Success](http://www.anergyacademy.com/wp-content/uploads/2025/12/Add-Deepseek-API-05.png)

### Step 3: Configure the Node
Ensure your HTTP Request node is set up like this:
![HTTP Settings](http://www.anergyacademy.com/wp-content/uploads/2025/12/Add-Deepseek-API-06.png)

---

## 💰 Cost & Pricing (成本與價格)
DeepSeek is extremely affordable compared to GPT-4. Running 100 leads typically costs less than $0.10.
* **Reference:** [DeepSeek Pricing Docs](https://api-docs.deepseek.com/quick_start/pricing)

![DeepSeek Cost](http://www.anergyacademy.com/wp-content/uploads/2025/12/deepseek-api-keys-dashboard-management.png)

---

## 📄 License
This project is open-source under the MIT License.
Built by **John Chin** @ [Anergy Academy](https://www.anergyacademy.com).
