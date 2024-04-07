# LC_Pill_Checker 💊🔍

#### NOTE: This project is an ongoing experiment and certain features are not optimized for retrieval as of yet. Cleaning of data, validation datasets, and experimenting with different types of embeddings models, vector stores, and dimensionality reduction are needed to improve this project.

Problem:

There is currently no publicly available pill-identifying software in the UK which identifies tablets/capsules and their manufacturers based on their appearance. Furthermore, there are no publicly available and up-to-date images of medicines that may be used to train image models. 
This project is a Jupyter notebook which handles text descriptions of tablets and capsules as an alternative.

# Usage

Follow the steps in the notebook after preparing the dependencies and imports to obtain an api key from [OpenAI](https://openai.com/blog/openai-api).

This template is currently set to receive a text document with information on the tablet/capsule, drug description, and manufacturer with each entry separated by a new line. Adjust this as necessary based on your data.

# What I learned while making this ✍️
1. What [retrieval augmented generation (RAG)](https://research.ibm.com/blog/retrieval-augmented-generation-RAG) is and how it can be used to improve performance of large language models in responding to queries relating to specific information.
2. The various steps involved in the RAG architecture such as text embeddings (e.g. Tf-idf) and vector stores (e.g. FAISS, Chromadb, Lancedb).
3. The basics of the [LangChain framework](https://python.langchain.com/docs/get_started/introduction) 🦜️ and the various tools/databases that are available to carry out RAG.

# Things to work on 🛠️🔬
1. Explore different embeddings models and vectorstores
2. Explore the use of dimensionality reduction (UMAP) to improve model perfomance



DISCLAIMER: The information above is provided for private study and / or personal use purposes only, and is not intended to be a substitute for a health care provider’s consultation or advice. The information above does not constitute legal or technical advice.
