Financial Data Extraction Tool Using OpenAI API
This tool is a streamlit based app that uses openai api to extract key financial measures such as company name, stock symbol, revenue, net income etc. from a news article. The news article is typically an article about company's finance reporting.



<img width="693" height="301" alt="image" src="https://github.com/user-attachments/assets/35ce65d6-fa7b-43cd-86b9-80e9a868a8b0" />

Installation
pip install -r requirements.txt
You need to create an account on openai website. You will get inital 5$ free credits which is more than enough for this project. Once you get an api key from your account add it to secret_key.py



-------------------------------------------OpenApi Functions ---------------------------------------------------

OpenAI Function Calling Tutorial For Beginners
College management Q&A system using openai function calls

<img width="1090" height="533" alt="image" src="https://github.com/user-attachments/assets/c1cc79da-b133-4bb9-bba7-97d487b4eac5" />

# AtliQ Commerce College Q&A System

Build a system that can take input questions related to a database of an imaginary college called **AtliQ Commerce College**. This system uses **OpenAI Function Calling** to answer both college-specific and general questions.

---

## ✅ Sample Questions
- **How much Peter Pandey has to pay in the first semester?**  
  → Returns **pending fees**  
- **How much did Peter Pandey pay in the first semester?**  
  → Returns **paid fees**  
- **What is the purpose of a balance sheet?**  
  → General question answered by OpenAI LLM (similar to ChatGPT)  
- **Average GPA in third semester?**  
  → Returns average GPA of all students in the third semester  

---

## 🛠 Tech Stack
- **Database:** MySQL  
- **Backend:** Python + OpenAI Function Calling  
- **Frontend:** Streamlit  

---

## ⚙️ Setup Instructions

### 1. **Database Setup**
- Navigate to the `db` directory.
- Run the SQL script in your **MySQL Workbench** to create the schema and populate data.

### 2. **Install Python Dependencies**
```bash
pip install openai
pip install streamlit
pip install mysql-connector-python


## OpenAI setup: You need to obtain a secret key from your openai account and put it in secret_key.py file
Running streamlit app
From your command line run this command,

streamlit run main.py
