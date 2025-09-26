# ReAct-Agent-Hub �

An intelligent AI Agent powered by **LangChain** and **HuggingFace LLMs**, enhanced with real-time tools for **web search** and **weather information**.  
This project demonstrates how to combine multiple tools into a single conversational AI using the **ReAct Agent architecture**.

---

## ✨ Features
- 🔗 **LangChain Integration** – Build and manage AI workflows with ease.  
- 🧠 **HuggingFace LLM** – Harness the power of state-of-the-art language models.  
- 🌐 **Web Search Tool** – Uses DuckDuckGo for fetching the latest information.  
- ☁️ **Weather Tool** – Fetches real-time weather updates using APIs.  
- ⚡ **ReAct Agent** – Reasoning + Acting loop for dynamic query handling.  

---

## 🛠️ Installation

Clone this repository and install dependencies:
go through the requirement.txt file first 

```bash
git clone https://github.com/hendrix0731/My_AIAgent.git
cd My_AIAgent
pip install -r requirements.txt
```

or install directly for colab:
```bash
! pip install langchain-huggingface langchain-core langchain_community requests duckduckgo-search ddgs
```

---

## 🔑 Setup

Add your **HuggingFace API Key**:

```python
import os
os.environ["HUGGINGFACEHUB_API_TOKEN"] = "your_api_key_here"
```

⚠️ **Note:** Keep your API key private. Do not commit it to GitHub.

---

## 🚀 Usage

Open the notebook and run cells step by step:

```bash
jupyter notebook My_AIAgent.ipynb
```

Example workflow:
1. Import dependencies  
2. Initialize tools (Search + Weather)  
3. Build the ReAct Agent  
4. Ask queries like:
   - *“What’s the weather in india?”*  
   - *“Search the latest AI research trends.”*  

---

## 📂 Project Structure
```
My_AIAgent.ipynb   # Jupyter notebook with code and explanations
README.md          # Project documentation
```

---

## 📈 Future Improvements
- Add more tools (e.g., Wikipedia, Calculator, News API).  
- Enhance weather tool with more detailed data (humidity, wind speed, etc.).  
- Deploy as a web app (Streamlit/Gradio) for interactive usage.  

---

## 🙌 Acknowledgements
- [LangChain](https://www.langchain.com/)  
- [HuggingFace](https://huggingface.co/)  
- [DuckDuckGo Search](https://duckduckgo.com/)  
