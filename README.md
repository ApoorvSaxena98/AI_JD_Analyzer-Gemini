# 🧠 AI_JD_Analyzer-Gemini
A simple web app that uses `Gemini` to determine whether a resume and job description match the requirements of the position, and it offers recommendations for improvement. Ideal for job seekers and HR professionals.

---

**🛠️ Built With**
- Python
- Streamlit
- Gemini
 
---

## 📁 Project Structure
AI-JD-Analyzer_Gemini/

├── app.py # Main Streamlit application

├── prompts.py # Prompt builder for Gemini

├── requirements.txt # Project dependencies

├── streamlit/ # 🔁 Rename to ".streamlit" (see note below)

  └── secrets.toml # Google AI API key config (Enter your own api key)

├── assets/

│ └── sample_job_description.txt # Example job description

│ └── sample_resume.txt # Example resume for testing

└── README.md # Project documentation



**⚠️ IMPORTANT:**  
Rename the `streamlit` folder to `.streamlit` before running the app.  
**`.streamlit`** is a special hidden folder used to store configuration files for a Streamlit app. Located in your app/project directory. Commonly contains files like `secrets.toml` or `config.toml` for setting themes, ports, server options, etc.

---

## 🚀 Setup Instructions
**1. Install dependencies**
     `pip install -r requirements.txt`

**2. Inside the renamed .streamlit/ folder, create a file called secrets.toml and add:**
    `GEMINI_API_KEY = ""your-api-key"`
      
**3. Run the application**
     `streamlit run app.py`

---

**Sample Inputs**

Use the assets/ folder to test the app with example files:
- sample_resume.txt
- sample_job_description.txt


# Screenshot
![AI_Job_Description_Analyzer_Initial](https://github.com/user-attachments/assets/c9865277-7a36-4e85-8bb7-e09bf50465a3)

![AI_Job_Description_Analyzer](https://github.com/user-attachments/assets/b08e9447-d5c8-4773-b463-ef5fa81ed0f6)

![Gemini_(1)](https://github.com/user-attachments/assets/b185c088-281b-441a-8827-6c10770826e1)

![Gemini_(2)](https://github.com/user-attachments/assets/79db49d8-cf3f-426c-a72a-0f176a229100)

![Gemini_(3)](https://github.com/user-attachments/assets/82cc8a7a-fcd0-4f81-a18e-82a76af47c35)


# Final Note
This project demonstrates how Generative AI can enhance recruitment workflows by intelligently matching resumes to job descriptions. Designed for learning purposes, it’s lightweight, easy to run, and leverages modern tools like Streamlit and Google AI API Key, making it ideal for showcasing AI prototyping skills with practical business relevance.
