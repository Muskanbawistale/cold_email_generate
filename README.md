# cold_email_generate
Cold Email Generator built with Streamlit, ChromaDB, and LangChain-Groq. Generates context-aware personalized cold emails with an interactive UI.
## 🚀 Setup

1. **Get a Groq API Key**  
   - Go to [Groq Console](https://console.groq.com/keys) and generate a new API key.  
   - Inside `app/.env`, add your key like this:  
     ```env
     GROQ_API_KEY=your_api_key_here
     ```

2. **Install dependencies**  
   Run the following command in your project root:  
   ```bash
   pip install -r requirements.txt
