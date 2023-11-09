# Embedder

## this repo ingests PDF's from the 'documents' directory and converts them into Vector Embeddings into Pinecone.

## I'm experiencing issues with dependencies so have not included a requirements.txt, however the commands below will run setup.py

``
python3.8 -m venv myenv
source myenv/bin/activate 
pip install openai
pip install langchain
pip install pinecone-client
pip install python-dotenv
pip install 'unstructured[pdf]'
pip install tiktoken
cd embedder
python3 setup.py
``