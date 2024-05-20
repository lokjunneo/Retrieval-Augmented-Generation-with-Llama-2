# Retrieval-Augmented-Generation-with-Llama-2-and-LangChain
Retrieval-Augmented Generation (RAG) is a technique that combines a retriever and a generative language model to deliver accurate response. It involves retrieving relevant information from a large corpus and then generating contextually appropriate responses to queries. Here we use the quantized version of the Llama 2 13B LLM with LangChain to perform generative QA with RAG. The notebook file has been tested in Google Colab with T4 GPU. 

![image](https://github.com/muntasirhsn/Retrieval-Augmented-Generation-with-Llama-2/assets/29087240/0be4ab98-43f3-47f2-8520-5833630671fc)

Figure: A schematic representation of RAG with a retriever and an LLM

Notes:

## Alternative retrievals:
Vectorstore might not be suitable if the context is incredibly huge. Can try an alternative below
[https://python.langchain.com/v0.1/docs/modules/data_connection/retrievers/](https://python.langchain.com/v0.1/docs/modules/data_connection/retrievers/)

## Prompt templates:
[https://gpus.llm-utils.org/llama-2-prompt-template/](https://gpus.llm-utils.org/llama-2-prompt-template/)

## Using ChromaDB for Vectorstore
[RAG_with_Lama_2_and_LangChain.ipynb](RAG_with_Lama_2_and_LangChain.ipynb) contains an example where ChromaDb was used to create a Vector Store.


RetrievalQA is deprecated by still describes some useful concepts:

![image](https://github.com/lokjunneo/Retrieval-Augmented-Generation-with-Llama-2/assets/44422169/69593687-efb8-4323-b3b0-0e84b9cdc8d8)

(From [https://stackoverflow.com/questions/77352474/langchain-how-to-get-complete-prompt-retrievalqa-from-chain-type](https://stackoverflow.com/questions/77352474/langchain-how-to-get-complete-prompt-retrievalqa-from-chain-type))
