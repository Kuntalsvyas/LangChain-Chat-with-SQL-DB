# 💬 LangChain Chat with SQL Database
An AI-powered chatbot that connects to a MySQL database and allows users to ask questions in natural language. Built using LangChain, Streamlit, and SQLAlchemy, it leverages the power of LLMs to interpret user queries, convert them into SQL, and return results in real time.

---

# 🔧 Features
- 💡 Ask questions about your MySQL database in plain English
- 🔄 Converts natural language to SQL queries using LangChain LLM
- 📊 Real-time SQL execution with MySQL
- 🖥️ Simple and elegant UI built using Streamlit
- 🧠 Context-aware responses
- 🔐 Secure MySQL connectivity via SQLAlchemy

---

# 🧰 Tech Stack
- LangChain – for natural language understanding and SQL query generation
- OpenAI/Groq API – LLM backend
- MySQL – database used for storing and querying user data
- SQLAlchemy – ORM and connector for MySQL
- Streamlit – interactive web UI
- Python 3.10+

---

# 🚀 Installation 

**1. Clone the Repository**
- git clone https://github.com/Kuntalsvyas/LangChain-Chat-with-SQL-DB.git
- cd LangChain-Chat-with-SQL-DB

**2. Create and Activate Virtual Environment**
- python -m venv venv
- venv\Scripts\activate  # On Windows
- source venv/bin/activate  # On Mac/Linux

**3. Install Dependencies**
-pip install -r requirements.txt

**4. Set Environment Variables**
- Create a .env file in the root folder and add:

**5.Run the App**
- streamlit run app.py

---

# 📊 Results & Evaluation
- Real-time, accurate SQL-generated responses
- Safety ensured via SELECT-only execution
- Schema-aware mapping of fields for reliable conversion

---

# 🛠️ Future Enhancements
- Add conversational memory and context
- Deploy as a REST API backend
- Build a Streamlit dashboard with visualizations
- Include model interpretability tools like SHAP or LIME
- Integrate with CRM platforms or automate queries

---

# 🙌 Author
Made with 💬 by Kuntal Vyas
If you liked this repo, give it a ⭐ and share it!
