### Setup for PDF-RAG-Q&A_assistant :

install Haggingface Hub: for Authenticale Pycode to HF-Model 
- pip install huggingface_hub


Set API key in Local Environment:
- setx <KEY_NAME> "haggingface Token Key"

Restart Terminal > reopen-terminal 
- echo %HF_TOKEN%


pip install numpy
pip install pymupdf
pip install faiss-cpu
pip install sentence-transformers
pip install scikit-learn
pip install tqdm
pip install python-dotenv
pip install tiktoken
pip install pandas

pip install numpy pymupdf faiss-cpu scikit-learn tqdm python-dotenv tiktoken pandas huggingface_hub


| Library               | Purpose in RAG        | Why Needed                           |
| --------------------- | --------------------- | ------------------------------------ |
| numpy                 | vector math           | embeddings stored as arrays          |
| pymupdf               | PDF reader            | extract text from uploaded PDFs      |
| faiss-cpu             | vector database       | store embeddings + similarity search |
| sentence-transformers | embedding model       | convert text → vectors               |
| scikit-learn          | similarity utilities  | cosine similarity, preprocessing     |
| tqdm                  | progress bars         | useful for indexing large PDFs       |
| python-dotenv         | environment variables | safely load API tokens               |
| tiktoken              | token counting        | manage prompt size                   |
| pandas                | data handling         | store chunks + metadata              |
