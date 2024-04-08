# RAG-TranSum a RAG based text summarizer and translator for Audios from vid clips
## Working

The application processes audio and video files to extract transcribed text, saving it locally. Text data is not converted to vector embeddings or stored in a vector database. Users have the option to summarize or translate the extracted text, which is processed by the model to generate the output.

## Tasks

The project involved the following subtasks:

- **Task 1:** Extracting text from audio and video files.
- **Task 2:** Creating a vector DB for storing embeddings(chromaDB).
- **Task 3:** Developing a summarizer and translator using open-source Large Language Models (LLMs).
- The entire project was coded in Python.

## Overview of Large Language Models (LLMs)

Large Language Models (LLMs) leverage transformer architectures to efficiently process sequential data. Trained on extensive text corpora, LLMs learn language patterns, while fine-tuning on specific tasks further enhances their performance. Their text generation capability relies on predicting the next word based on context, employing self-attention mechanisms to weigh word importance. LLMs excel in tasks such as language translation, summarization, and question answering, owing to their versatility and ability to understand and generate human-like text. These attributes make LLMs powerful tools with wide-ranging applications in natural language processing tasks.
