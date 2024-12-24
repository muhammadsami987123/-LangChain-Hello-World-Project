# 🚀 LangChain + Google Gemini 2.0 Integration 🌟

This project demonstrates a simple **"Hello, World!"** implementation using **LangChain** and the **Google Gemini 2.0 Flash API**. It showcases the integration of advanced AI models into Python workflows for dynamic prompt execution.

## **Features**
- Integration of **LangChain** and **Google Gemini 2.0 Flash API**.
- Uses `langchain-google-genai` for seamless interaction with Google’s LLM.
- Demonstrates a basic "Hello, World!" response generation using AI.

## **Getting Started**

### **Prerequisites**
1. Install necessary libraries:
   ```bash
   pip install -U langchain langchain-google-genai
   ```
2. Set your Google API Key in Colab or your environment:
   ```python
   from google.colab import userdata
   userdata.set('GOOGLE_API_KEY', 'your_actual_api_key_here')
   ```

### **Run the Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name/langchain-google-gemini-hello-world.git
   cd langchain-google-gemini-hello-world
   ```
2. Run the script:
   ```bash
   python hello_world.py
   ```

### **Expected Output**
```
Generated Response:
Hello, World!
