# llm-rag-app
 This is a quick tutorial on how to build a simple RAG (Retrieval Augmented Generation) using OpenAI's LLM and Pinecone Vector Database

 ## Pre-reqs
 1. Create an account with OpenAI and get a secret key
 2. Create an account with Pinecone and get a secret key
 3. Download the sample data file from `data` directory
 4. Install required libraries
 5. Fork the code and run in in local Jupyter notebook

 ## Libraries needed 
1. Pandas - - Library for reading and writing CSV files into data frames 
`pip install pandas` 
2. DotEnv - Library to load environment variables such as API Keys 
`pip install python-dotenv`
3. OpenAI Client - OpenAI Client library
`pip install openai`
4. AST - Library for converting string to list
`pip install ast`
5. TDQM - For keeping track of upload progress (depedency for Pinecone Client)
`pp install tdqm``
6. Pinecone Client - Pinecone library 
`pip install pinecone-client`

