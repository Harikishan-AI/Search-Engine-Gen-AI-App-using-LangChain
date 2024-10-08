# 🔎 Search Engine Gen AI App Using LangChain Tools and Agents

This project demonstrates a search-powered chatbot application built using Streamlit and LangChain, enabling dynamic interactions with multiple information sources such as Wikipedia, Arxiv, and DuckDuckGo. The app leverages **LangChain's Agent** functionality, integrating powerful tools to enhance user queries by combining information retrieval and language model capabilities.

## Features:
- **LangChain Integration**: Uses LangChain to connect tools for retrieving information from multiple sources.
- **Wikipedia API**: Queries Wikipedia for concise and informative responses.
- **Arxiv API**: Extracts relevant academic papers from Arxiv, providing quick and insightful information on research topics.
- **DuckDuckGo Search**: Executes web searches to provide more general information from the internet.
- **Interactive Chat Interface**: Implemented using Streamlit, allowing users to input queries and interact with the chatbot directly.
- **Groq API**: Utilizes the Groq API for large-scale language models, offering powerful, real-time text generation.

## How It Works:
1. **Input**: The user enters a query in the chat interface.
2. **Agent Initialization**: The app initializes a LangChain Agent with access to various tools like Arxiv, Wikipedia, and DuckDuckGo search.
3. **Information Retrieval**: Based on the user's input, the agent dynamically selects the appropriate tools to fetch relevant data.
4. **Real-Time Response**: The response, generated in real-time, is displayed within the chat, along with the agent's thought process and actions using `StreamlitCallbackHandler`.

## Usage:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/search-engine-gen-ai.git
   cd search-engine-gen-ai
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Set your environment variables by adding your API keys to a .env file:
   ```bash
   GROQ_API_KEY=your_groq_api_key
4. Run the Streamlit app:
   ```bash
   streamlit run app.py
5. Enter your query in the chat input and watch the chatbot retrieve answers from Wikipedia, Arxiv, or DuckDuckGo.

## Future Enhancements:
- Expand the set of tools and agents for more comprehensive query handling.
- Add more robust error handling for parsing or retrieval issues.
- Improve the UI/UX for a better interactive experience.
