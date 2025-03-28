This AI Research Assistant is a tool that automates research tasks by leveraging large language models (LLMs) and external search tools. It can summarize information, search Wikipedia and the web, and save research findings to a file. The assistant is built using **Python**, **LangChain**, and **Anthropic Claude 3.5 Sonnet**.

## Technologies Used
- Python
- LangChain(LangChain's tool-calling mechanism for structured output)
- Anthropic Claude 3.5 Sonnet(to generate research summaries)
- DuckDuckGo Search API and Wikipedia API(for fetching external data)
- Pydantic(for structured output parsing)
- Dotenv( for API key management)

## Prerequisites
- Python 3.8+
- An Anthropic API Key 
- Virtual environment (recommended)

## Steps to Install
1. Clone the repository:
   git clone https://github.com/yourusername/ai-research-assistant.git
   cd ai-research-assistant
   
2. Set up a virtual environment:
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   
3. Install dependencies:
   pip install -r requirements.txt
   
4. Configure API keys:
   - IN .env add your API keys:
     ANTHROPIC_API_KEY="your-anthropic-api-key"
  

## Troubleshooting
Error: `Your credit balance is too low to access the Anthropic API`**
- Ensure you have an active **Anthropic API** subscription.




