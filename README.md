# 3.-ai-linkedin-content-automation
# AI LinkedIn Content Automation

This project automates the generation and management of LinkedIn post ideas using AI agents, Google Sheets, and the Tavily Search API.  
The system is designed to fetch fresh content ideas, process them via AI, and store them in Google Sheets for easy review and publishing.

---

## 🔧 Features
- Automated scheduling with **Schedule Trigger**  
- Fetch existing rows from Google Sheets  
- Enrich data with **Tavily API** (real-time web results)  
- Generate LinkedIn post ideas using **OpenAI Chat Models**  
- Update rows in Google Sheets with processed content  
- Append final results for publishing or tracking  

---

## 🛠️ Workflow Overview
1. **Schedule Trigger** → Starts the process automatically.  
2. **Get row(s) in sheet** → Reads data from Google Sheets.  
3. **HTTP Request (Tavily API)** → Fetches fresh web context using Tavily Search.  
4. **AI Agent (OpenAI Chat Model)** → Generates content ideas based on retrieved context.  
5. **Update row in sheet** → Saves intermediate results.  
6. **Second AI Agent** → Refines or formats the content.  
7. **Code step** → Processes and prepares structured output.  
8. **Append row in sheet** → Saves final LinkedIn-ready posts.  

---


