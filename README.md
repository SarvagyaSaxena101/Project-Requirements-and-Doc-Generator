# 🚀 AutoSpec AI: Natural Language to Technical Specification Generator

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

## ✨ Overview

AutoSpec AI is a powerful tool that transforms your raw project ideas into well-structured technical specifications. Simply describe your concept in plain English, and watch as it generates detailed functional and non-functional requirements, API endpoints, database schemas, and more! 📝

**Live Demo:** [**Deployed Project Link**](http://your-deployed-link-here.com) 🌐

## 📋 Features

*   **🤖 AI-Powered Generation:** Leverages large language models to understand your ideas and generate detailed specs.
*   **🧩 Comprehensive Sections:** Creates all the essential sections of a technical document.
*   **✏️ Fully Editable:** All generated content is presented in editable text areas for you to refine.
*   **📄 Multiple Export Options:** Download your final specifications as a formatted PDF or DOCX file.
*   **🎨 Formatted & Professional:** Documents are generated with clean, professional formatting for immediate use.

## 🛠️ Tech Stack

*   **Frontend:** [Streamlit](https://streamlit.io/)
*   **AI/LLM:** [Groq](https://groq.com/) (using the Llama 3.1 model)
*   **PDF Generation:** [fpdf2](https://github.com/py-pdf/fpdf2)
*   **DOCX Generation:** [python-docx](https://python-docx.readthedocs.io/)
*   **Environment Variables:** [python-dotenv](https://github.com/theskumar/python-dotenv)

## ⚙️ Setup & Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    # For Windows
    python -m venv venv
    venv\Scripts\activate
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Set up your API key:**
    *   Create a file named `.env` in the root of the project.
    *   Add your Groq API key to the `.env` file like this:
        ```
        GROQ_API_KEY="your-groq-api-key"
        ```

5.  **Run the application:**
    ```bash
    streamlit run app.py
    ```

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
