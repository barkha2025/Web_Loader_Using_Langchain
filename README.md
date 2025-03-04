# Langchain-Summarize-Text-from-Website
This Streamlit app summarizes content from a provided URL using a Groq-powered language model. Users input a Groq API key and URL . The app validates inputs, loads the content, and generates a 300-word summary with LangChain, displaying the result in the interface.
![image](https://github.com/user-attachments/assets/95208b3b-7e71-4525-a53c-b4f58b898cb4)



## Steps to execute the file:

1. Create a virtual environment (recommended):
```
conda create -p venv python=3.10
```
2. Activate the environment:
```
conda activate venv/
```
3. Install dependencies:
```
pip install -r requirements.txt
```
4. Execute the python file:
```
streamlit run app.py
```
5. Follow the link to streamlit webapp
6. Enter your groq_api_key
7. Use any web link or youtube link
8. It summerize with 300 word content from the provided link .
