# chat-with-multiple-pdfs
In this repo, i am able to chat with multiple pdfs. I have used streamlit at frontend. Used FAISS (Facebook AI Similarity Search), a library which is used for similarity search of vectors.

# Stack

1. Python = 3.10
2. streamlit = 1.32.2
3. google-generativeai = 0.4.1
4. langchain = 0.1.13
5. faiss-cpu = 1.8.0

# How to use

1. First of all, needs to have conda (Anaconda) -package and env management tool.
2. Once conda is installed create new virtual env using command conda create -p {env_name} python={python_version} e.g. conda create -p venv python=3.10
3. Activate conda env using command conda activate {env}
4. Create .env file as per sample env .For this you will need to create google gemini api key.
5. Install packges using command pip install -r requirements.txt
6. Run application using command streamlit run app.py
