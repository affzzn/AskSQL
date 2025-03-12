# Ask My SQL

This project enables interaction with a MySQL database using natural language. It uses LangChain, Google Gemini API, and Streamlit to create a chat interface that converts user questions into SQL queries and returns answers based on the database content.

## Requirements

- Python 3.x
- Streamlit
- LangChain
- Gemini API Key
- MySQL
- `mysql-connector-python`
- `langchain`
- `langchain-core`
- `langchain-community`
- `langchain-google-genai`

## Setup Instructions

```bash

Install the required Python packages:

pip install -r requirements.txt

Create a .env file and add your Gemini API key:

GOOGLE_API_KEY=<your-google-api-key>

Start the Streamlit application:

streamlit run app.py
```

Once connected, type your questions in the chat input box, and the assistant will generate the appropriate SQL query, execute it on the database, and provide a natural language response based on the SQL results.
