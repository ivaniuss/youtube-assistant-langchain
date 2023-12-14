# Youtube Assistant

Ask questions about any YouTube video to this LLM powered assistant.

1. Paste the url of your youtube video.
2. Ask a question about the video.
3. Press submit.

You'll get an answer based on the video transcript.

## Installation
First of all clone the repository 

```bash
git clone https://github.com/ivaniuss/youtube-assistant-langchain.git
cd pets-name-langchain
```

### Basic installation

```bash
pip install -r requirements
```

### Using Virtual Enviroment

```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
### Using Docker

```bash
docker build -t pets-name-langchain .
docker-compose up -d
```

## Running the Application

Remember to store your `.env` variable `OPENAI_API_KEY` before. You can get your apikey [here](https://platform.openai.com/api-keys).

### Using Basic or Virtual Environment

```bash
streamlit run app.py
```

### Using Docker

Visit http://localhost:4000 in your browser.

## Technologies Used

- [LangChain](https://python.langchain.com/docs/get_started/introduction.html)
- [Streamlit](https://streamlit.io/)
- [OpenAI](https://platform.openai.com)
