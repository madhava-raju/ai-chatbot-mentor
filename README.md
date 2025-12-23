🤖 AI Chatbot Mentor

Domain-Specific Intelligent Learning Assistant

AI Chatbot Mentor is a module-based, domain-restricted AI mentoring system designed to provide focused, accurate, and distraction-free learning support. Unlike generic chatbots, this application strictly answers questions only within the selected learning domain.

Built using Streamlit, LangChain, and Hugging Face LLMs, it ensures controlled responses, session memory, and downloadable conversation history.

🚀 Key Features

🎯 Domain-Restricted Mentoring
Answers only within the selected module (Python, SQL, ML, etc.)

🚫 Out-of-Scope Question Rejection
Prevents hallucinated or irrelevant responses

💬 Interactive Chat Interface
Clean and intuitive Streamlit-based UI

🧠 Context-Aware Conversations
Maintains session-level conversation memory

📥 Download Chat History
Export complete conversation as a .txt file

🔐 Secure API Handling
Environment variables protected using .env (not pushed to GitHub)

📚 Supported Learning Modules

Python

SQL

Power BI

Exploratory Data Analysis (EDA)

Machine Learning

Deep Learning

Generative AI

Agentic AI

🧩 System Architecture
```bash
User
 │
 ▼
Streamlit UI
 │
 ▼
Module Selection
 │
 ▼
LangChain Prompt Template
 │  (Domain Restriction Rules)
 ▼
Hugging Face LLM
 │
 ▼
AI Mentor Response
 │
 ▼
Chat History + Download Option
``` 
🛠️ Tech Stack
```bash
Component	        Technology
Frontend	        Streamlit
LLM Orchestration	LangChain
Language Model	  Hugging Face 
Language	        Python
Export            Format.txt
```
## 📁 Project Structure

```bash
ai-chatbot-mentor/
│
├── chat/
│   ├── files/
│   │   ├── main.py
│   │   ├── req.txt
│   │   └── .env (ignored)
│   │
│   └── etc/
│
├── .gitignore
└── README.md
```
⚙️ Installation & Setup
1️⃣ Clone the Repository
```bash
git clone https://github.com/madhava-raju/ai-chatbot-mentor.git 
cd ai-chatbot-mentor
```
2️⃣ Create Virtual Environment 
```bash
python -m venv Mentor
venv\Scripts\activate
```

3️⃣ Install Dependencies
```bash
pip install -r chat/files/req.txt
```
4️⃣ Configure Environment Variables

Create a .env file inside chat/files/:
```bash
HUGGINGFACEHUB_API_TOKEN=your_api_key_here
```


5️⃣ Run the Application
```bash
streamlit run chat/files/main.py
```

🎓 Learning Outcomes

Building domain-restricted AI systems

Prompt engineering for controlled outputs

Using LangChain with Streamlit

Secure API key management

Designing real-world AI mentor applications

🏁 Conclusion

AI Chatbot Mentor bridges the gap between generic chatbots and real-world educational AI assistants by enforcing strict domain control, improving reliability, and enhancing the learning experience.
