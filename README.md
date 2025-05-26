# rag-sytems

### Setup
1. Setup
conda create -n rags
conda activate rags

2. Install llama
pip install llama-index

3. Install qdrant
install docker

`docker run -p 6333:6333 -p 6334:6334 \
    -v $(pwd)/qdrant_storage:/qdrant/storage:z \
    qdrant/qdrant`

4. install Ollama
Download OLLAMA: https://ollama.com/download

Run: ollama run llama3.2

5. Install additional packages

pip install qdrant_client torch transformers

pip install llama-index-embeddings-huggingface

pip install llama-index-llms-ollama

pip install llama-index-vector-stores-qdrant