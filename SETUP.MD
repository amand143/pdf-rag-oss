# Setup guide

## Prerequisites

- [ollama]
- [pinecone api key]

## Steps

1. Clone the repo
2. pip install requirements.txt
3. pull llama2 on ollama
3. Create a `.env` file with the following content:

```
PINECONE_API_KEY=<YOUR API KEY>
```

4. Setup the database:

Get your api key from pinecone, the code itself will generate the required indices for you.

5. Run all cells, you can customize your question in the last cell.
