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

Output:
![{B0F0CAD9-586E-47B6-A8C7-9CA9F9D367B3}](https://github.com/user-attachments/assets/768b0c45-3cfb-4fb4-be3f-9e70f7cda425)

![{FF0932CE-C499-4AC7-9499-03973DC5E3FD}](https://github.com/user-attachments/assets/82552529-7a89-4151-a1e5-9dbddba74004)

![{04418A7A-7713-40AC-B34D-2DDE6A0639B2}](https://github.com/user-attachments/assets/56cac9bd-c88e-4188-ae67-f702f4ed3864)

![{E6BC8629-B467-43F2-9E68-35AB9467957C}](https://github.com/user-attachments/assets/2521d2d7-9bde-489a-8d2a-d0b79c41a524)

![{BEE7C624-13FC-408F-908B-441088133726}](https://github.com/user-attachments/assets/ac3e013b-bdf6-4c4f-9870-9fd9b75f8904)







