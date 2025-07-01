# Financial_Agent

Financial_Agent is an AI-powered assistant that leverages large language models and real-time data tools to provide financial insights and web search capabilities. It uses the [phidata](https://github.com/phidatahq/phidata) framework to orchestrate multiple agents for tasks such as retrieving stock prices, analyst recommendations, company fundamentals, and the latest news.

## Features

- **Finance AI Agent**: Fetches stock prices, analyst recommendations, company fundamentals, and company news using Yahoo Finance.
- **Web Search Agent**: Searches the web for up-to-date information and always includes sources.
- **Multi-Agent Collaboration**: Combines the strengths of both agents to deliver comprehensive financial summaries and news.
- **Customizable Instructions**: Agents can be tailored with specific instructions for data presentation and sourcing.

## Setup

1. Clone the repository.
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Create a `.env` file with your API keys (see `.env.example` for required variables):
   - `OPENAI_API_KEY` (required for OpenAI integration)
   - Any other keys required by your tools
4. Run the main script:
   ```sh
   python financial_agent.py
   ```

## Requirements

- Python 3.8+
- See [requirements.txt](requirements.txt) for Python dependencies.

## Usage

The script will summarize analyst recommendations and share the latest news for a given stock (e.g., NVDA) by combining financial data and web search results. You can modify the query in `financial_agent.py` to analyze other stocks or financial topics.

## License

This project is for educational and research purposes.
