### Command for Graph RAG
- python -m graphrag.index --init --root ./ragtest -> initiate the index

- python -m graphrag.index --root ./ragtest

- python -m graphrag.query --root ./ragtest --method global "QUERY" -> Looking for global/top level information/community

- python -m graphrag.query --root ./ragtest --method local "QUERY" -> Looking for local/chunk level information


### Using Ollama local model
- ollama pull mistral
- ollama pull nomic-embed-text
- /opt/anaconda3/envs/graphrag/lib/python3.12/site-packages/graphrag/llm/openai [Converted the openai_embeddings_llm.py file to work with ollama]