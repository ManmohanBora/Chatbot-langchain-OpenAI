# 🚀 LangChain Demo with OpenAI API
This project is a simple, clean, and powerful demo showcasing how to build an interactive chatbot using **LangChain**, **OpenAI GPT-4**, and **Streamlit**. It takes user input, sends it through a LangChain prompt template to the GPT-4.1 model, and displays the response in a user-friendly web interface.

## 📌 Features
- 🔗 **LangChain** for structured prompts and chaining logic  
- 🤖 **OpenAI's GPT-4.1** for advanced natural language understanding  
- 🌐 **Streamlit** for quick web app deployment  
- 🔐 Environment variable support via **dotenv**


## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
https://github.com/ManmohanBora/Chatbot-langchain-OpenAI.git
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
streamlit
langchain
langchain-openai
python-dotenv
```
### 3. Add API Keys
Create a .env file in the root directory and add your keys:
```bash
OPENAI_API_KEY=your_openai_api_key
LANGCHAIN_API_KEY=your_langchain_api_key
```
### 4. Run the App
```bash
streamlit run app.py
```
## 💡 How It Works
- User enters a question in the Streamlit UI.
- The question is formatted using a LangChain ChatPromptTemplate.
- The formatted input is passed to OpenAI's GPT-4.1 model.
- The response is parsed and displayed back in the app.

## 📸 Demo Screenshot
![Screenshot 2025-04-18 114832](https://github.com/user-attachments/assets/c8c6db13-88b2-4fe1-8776-f832a0b15059)
