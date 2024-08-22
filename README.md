# RAG-system-using-Langchain+ChromaDB+OpenAI

Generates embeddings from text, storing these embeddings in a vector database(Chroma) and then querying this database to answer questions based on the text data.

Splits text into three chunks for processing (based on a word similarity search) and uses three chunks of text divided by ----- lines to answer query

How to Use:
type in terminal: python query_data.py "Your message"
Uses data in resume folder, can be found in main.py and changed (DATA_PATH = "resume")
