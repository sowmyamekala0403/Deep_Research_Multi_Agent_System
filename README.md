# Multi_Agent_Research_System

This project is an AI-powered research workflow built using a **multi-agent architecture**. Each agent has a specialized role — searching, reading, writing, and critiquing — and they collaborate to generate structured, professional research reports.

## 🔹 Features
- **Search Agent** → Finds relevant information using web search tools.
- **Reader Agent** → Scrapes and extracts content from URLs.
- **Writer Agent** → Produces detailed, structured research reports.
- **Critic Agent** → Reviews reports, scores them, and suggests improvements.

## 🔹 Tech Stack
- Python 3.10+
- LangChain for agent orchestration
- OpenAI / Gemini models for natural language generation
- dotenv for environment variable management

## 🔹 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Multi_Agent_Research_System.git
   cd Multi_Agent_Research_System
## 🔹 Create a virtual environment:
bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

## 🔹 Install dependencies:
bash
pip install -r requirements.txt
Add your API keys in a .env file:
env
OPENAI_API_KEY=your_openai_key_here
GOOGLE_API_KEY=your_gemini_key_here

## 🔹 Run the pipeline:
python pipeline.py

## 🔹 Workflow:
- Search Agent gathers information on the topic.
- Reader Agent scrapes additional details from URLs.
- Writer Agent compiles findings into a structured research report.
- Critic Agent evaluates the report and provides feedback.

## 🔹 Areas to Improve:
- Add more depth to conclusion
- Include more diverse references

## 🔹 One line verdict:
Solid report with room for deeper analysis.
