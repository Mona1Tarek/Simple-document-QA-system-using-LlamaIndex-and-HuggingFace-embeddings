#  LlamaIndex + HuggingFace 

This project demonstrates how to use **[LlamaIndex](https://github.com/run-llama/llama_index)** with HuggingFace embeddings and language models for building a simple document Question-Answering (QA) system.

---

##  Features
- Load and process documents from a local folder (`data/`).
- Generate embeddings using **BAAI/bge-small-en-v1.5**.
- Use **TinyLlama-1.1B-Chat-v1.0** as the language model.
- Query the index with natural language questions.


---

##  Installation

1. Clone this repository or download the notebook.
2. Install the required dependencies:

```bash
pip install llama-index
pip install llama-index-embeddings-huggingface
pip install llama-index-llms-huggingface
pip install transformers
