# 💰 Josh - Your Personal Finance AI Agent

Josh is an AI-powered personal finance assistant built with [Groq SDK](https://groq.com) and Node.js.  
It helps you **track expenses, incomes, balances, and plan your finances** directly from the terminal.  

---

## 🚀 Features
- Add expenses and incomes  
- Track total expenses within a given period  
- Get current balance (income - expenses)  
- Interactive CLI chat powered by `llama-3.3-70b-versatile`  
- Extendable with new financial tools  

---

##  Tech Stack
- **Node.js** (with ES modules)  
- **Groq SDK** for LLM-powered conversations  
- **Readline** for interactive CLI input  

---

## 🔧 Setup & Installation

1. Clone this repo:
   ```bash
   git clone https://github.com/AmitKun07/ai_agent.git
   cd ai-agent
2. Install dependencies:
   ```bash
   npm install
3. Set your Groq API key in .env file:
   ```bash
   GROQ_API_KEY=your_api_key_here
4. Run the agent:
   ```bash
   bun run agent.js
   node agent.js
---
## 💬 Usage
   Once running, type your queries in the terminal.
   Examples:
   ```bash
   User: Add an expense of 500 for groceries
   Assistant: Added to the database.

   User: Add income of 2000 as salary
   Assistant: Added to the income database.

   User: What’s my current balance?
   Assistant: 1500 INR

   User: bye


---  

## ⚠️ Notes
   - Currently, data is stored in-memory only (resets when you restart the program).  
   - getTotalExpense does not yet filter by date range — only sums all expenses.  
   - For persistence, consider integrating a database.

 ## 🛠️ Future Improvements
   - ✅ Date-based expense tracking  
   - ✅ Persistent database (SQLite/MongoDB)  
   - ✅ Web/desktop interface.

## 📄 License
    MIT License. Free to use and modify.



    
    

