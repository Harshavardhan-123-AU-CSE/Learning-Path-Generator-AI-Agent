# Learning-Path-Generator-AI-Agent 
# AI Search Agent using n8n

This project is an AI-powered automation workflow built using **n8n**.  
It acts as an intelligent agent that understands user queries, searches the web using SerpAPI, processes the results using an AI model, and produces structured, meaningful outputs.
---

## What This Project Does

The AI Search Agent automates research and content generation by combining reasoning, live web search, and AI summarization.

In simple terms, the agent:
- Understands what the user is asking
- Searches the internet in real time
- Analyzes the results
- Produces a clean, useful response
- Optionally stores the output in Google Docs
- ---

## End-to-End Process Flow

### 1. User Input
The workflow starts when a user sends a message through chat.

Example:
create a 3 days plan to learn python
cretae a 6 days learning plan for java 
create me a learning plan for Artificial Intelligence
---

### 2. AI Agent Reasoning
The AI Agent:
- Interprets the user’s intent
- Decides whether a web search is required
- Forms a suitable search query
- Orchestrates the overall flow
---

### 3. Web Search via SerpAPI
If external information is required:
- The agent calls **SerpAPI**
- Uses Google Search (`engine=google`)
- Fetches real-time, relevant results
---

### 4. AI Processing & Summarization
The AI model (Google Gemini):
- Reads the raw search results
- Filters irrelevant information
- Extracts key insights
- Structures the content logically

---

### 5. Output Generation
The final output is:
- Clear
- Structured
- User-friendly

The response can be:
- Displayed directly in chat
- Stored in Google Docs
- Passed to other automation steps
---

## Workflow Architecture

User Chat Input
↓
AI Agent (Reasoning & Decisions)
↓
SerpAPI (Live Web Search)
↓
AI Model (Understanding & Summarization)
↓
Final Output (Chat / Google Docs)
---

## Tech Stack

- **n8n** – Workflow automation platform
- **AI Agent (n8n)** – Reasoning and tool orchestration
- **Google Gemini** – AI model for understanding and summarization
- **SerpAPI** – Real-time Google search
- **Google Docs API** – Optional document storage
- **Git & GitHub** – Version control
---

##  Project Structure

ai-search-agent-n8n/
│
├── workflows/
│ └── ai-search-agent.json
│
└── README.md
---

## How to Run the Project

1. Clone this repository
2. Open **n8n**
3. Import the workflow JSON file
4. Configure credentials:
   - SerpAPI API Key
   - Google (Gemini & Docs)
5. Execute the workflow
6. Send chat messages to interact with the AI Agent
---

## Environment & Security

Required credentials:
- SerpAPI API Key
- Google API credentials

## Use Cases

- Learning plan generation
- Research assistants
- AI-powered search bots
- Content research and summarization
- Knowledge automation workflows
- Portfolio AI agent demonstration

---

## Why This Project Is Valuable

- Demonstrates **AI agent reasoning**, not just API usage
- Uses **real-time web data**
- Shows practical automation design
- Clean separation of reasoning, tools, and output
- Industry-relevant AI workflow architecture

---

## Author

**Majji Harsha Vardhan**  
Computer Science Student | Full-Stack Developer | AI Automation Enthusiast
---

## Future Enhancements

- Memory-enabled AI Agent
- Multi-source search integration
- Result ranking and filtering
- PDF / report generation
- Slack or WhatsApp integration
- Cloud deployment (Docker / EC2 / Railway).
