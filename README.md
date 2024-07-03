## Setup

Create a new Python virtual environment

```
python3 -m venv .venv
```
```
source .venv/bin/activate
```


Next, install Ollama. This will allow you to run LLMs on your local machine
- https://ollama.com

Run the llama3 LLM locally in Ollama

```
ollama run llama3
```

Create a .env file in the project root directory
```
OPENAI_API_KEY="YOUR_OPENAPI_API_KEY"
```

# Architecture
![alt text](<architecture.png>)



## Reference

Tutorial video
- https://youtu.be/WL7V9JUy2sE