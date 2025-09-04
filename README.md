# Multi_Agent_Data_Analyst

## Research-to-Visualization Agent using LangGraph, Tavily, and Matplotlib  

This project implements an **AI Research & Visualization Agent** that:  
1. Takes a **natural language query** from the user.  
2. Uses the **Tavily Search API** to gather information from the internet.  
3. Evaluates the search results for **relevance and completeness**.  
4. Optimizes the query if the search results are insufficient.  
5. Extracts **structured, numerical/plot-friendly data**.  
6. Generates **Matplotlib code automatically** to visualize the extracted data.  
7. Executes the code and displays the **final visualization**.  

The workflow is powered by **LangGraph**, **LangChain**, and **Groq LLMs**.

---

##  Features
- **Automated Internet Research** using [Tavily](https://tavily.com).  
- **Dynamic Evaluation** of search results (`yes/no`) before moving forward.  
- **Query Optimization** if results are not sufficient.  
- **Data Extraction** that filters theoretical text and keeps only plot-ready values.  
- **Matplotlib Code Generation** — the agent decides the best chart type (line, bar, pie, scatter, etc.) based on data.  
- **Automated Plot Execution** using Python REPL to render the visualization.  
- **Graph-based Workflow** designed using LangGraph with conditional routing.  

---

## 🛠️ Tech Stack
- **Python 3.10+**  
- [LangGraph](https://github.com/langchain-ai/langgraph)  
- [LangChain](https://www.langchain.com/)  
- [Tavily Search API](https://tavily.com/)  
- [Groq LLMs](https://groq.com/)  
- **Matplotlib** for visualization  
- **dotenv** for API key management  

---
