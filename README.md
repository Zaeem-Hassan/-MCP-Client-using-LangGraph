# -MCP-Client-using-LangGraph
<img src="Thumbnail.png"  width="1536" height="1024">

<img src="Technical architecture.png"  width="1536" height="1024">

### LangGraph MCP Client + FastMCP Cloud Expense Tracker Server + Stock Price Tool

This project is a full-stack **AI Agent System** built using **LangGraph**, **MCP (Model Context Protocol)**, and **FastMCP Cloud**.  
It shows how an AI agent can call tools — both **local** and **cloud-hosted** — to perform real-world tasks like:

- ✔️ Fetching **live stock prices**  
- ✔️ Reading/writing from your **FastMCP cloud Expense Tracker server**  
- ✔️ Running **web search**  
- ✔️ Maintaining **persistent conversation memory**

---
## Watch demo here https://youtu.be/MvDsPgjbRu8

## Project Highlights

### LangGraph MCP Client
A fully asynchronous agent capable of connecting to multiple MCP servers via:

- **MCP over SSE** (FastMCP cloud)
- **MCP over stdio** (local tools)
- Automatic tool loading with `client.get_tools()`

Integrated tools include:

- GPT-OSS-120B (via Groq)  
- DuckDuckGo Search  
- Stock Price Tool  
- Expense Tracker (FastMCP)

---

### FastMCP Cloud-Hosted Server  
Your Expense Tracker server is live at:
https://Expense-tracker.fastmcp.app/mcp
Exposes tools like:

- `add_expense`
- `get_expenses`
- `delete_expense`
- `get_total`
- etc.

---
