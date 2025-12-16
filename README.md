#  Personal Finance Chatbot 

A smart, privacy-focused financial advisor powered by the **IBM Granite 3.2 2B** model. This application uses local LLM inference to provide personalized advice on savings, investing, budgeting, and debt management without sending your data to external servers.

## Features
- **Local Intelligence**: Powered by IBM Granite 3.2 (2B) for privacy-first assistance.
- **Interactive UI**: Built with Streamlit for a clean, responsive chat experience.
- **Financial Topics**: Specialized knowledge in savings, taxes, investing, and more.

## 🛠️ Installation

1.  **Clone the repository**:
    ```bash
    git clone <your-repo-url>
    cd ibmgranite
    ```

2.  **Install dependencies**:
    ```bash
    pip install streamlit transformers torch
    ```

## ▶️ Usage

Run the chatbot application:
```bash
streamlit run demo.py
```

The application will launch in your default web browser at `http://localhost:8501`.

the local model will be downloaded automatically when run the project for first time.
To run it using gpu install cuda and run the project.
