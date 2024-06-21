# AI-Content-Generator

A multi-lingual AI PDF search app built with Python, Cohere, LangChain, and Bubble.

## How it works

The document is uploaded as a PDF Docx, URL, txt file, or PPT. The text is then extracted and split into chunks which is converted into numbers using Cohere's multilingual API. Cohere's embedding model is then used to save the chunks into a vector database.

Once the text is saved, we can then search, which uses similar logic. The search query is converted into numbers and compared to the existing numbers in the vector database to find the cosine similarity of multilingual text, which is how results are generated.
