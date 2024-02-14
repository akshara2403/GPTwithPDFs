# GPTwithPDFs

This is a Langchain project that enables you to interact with any PDFs via the Gradio chat interface. It not only fetches relevant answers but also renders relevant pages of the PDFs.

# Technologies Used
1. Langchain
2. ChromaDB as vector store
3. OpenAI embeddings
4. OpenAI chat model (gpt-3.5-turbo)
5. Gradio 

# Steps performed

1. Build a chatbot interface using Gradio
2. Extract texts from pdfs and create embeddings
3. Store embeddings in the Chroma vector database
4. Send query to the backend (Langchain chain)
5. Perform a semantic search over texts to find relevant sources of data
6. Send data to LLM (ChatGPT) and receive answers on the chatbot


# How does the end product look like :
With Chat history :
<img width="1325" alt="Screenshot 2024-02-14 at 5 41 04 PM" src="https://github.com/akshara2403/GPTwithPDFs/assets/73586732/ac95e367-7f45-4407-b0b1-bafdf184b8a0">

<img width="1387" alt="Screenshot 2024-02-13 at 11 28 19 AM" src="https://github.com/akshara2403/GPTwithPDFs/assets/73586732/487ad6fd-182f-4fff-a809-43ac6fcd8c66">



