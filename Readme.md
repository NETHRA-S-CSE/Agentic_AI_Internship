# Agentic AI Internship


## Task 01 - AI vs Human Text Analysis

In this task, I worked with an AI vs Human Text dataset to explore the differences between machine-generated and human-written content. The dataset was loaded and analyzed using Python data science libraries. I performed data preprocessing by cleaning the text, removing unwanted characters, converting text to lowercase, and preparing the data for further Natural Language Processing (NLP) tasks.

I also conducted Exploratory Data Analysis (EDA) to understand the distribution of AI-generated and human-written samples. Various visualizations were created to identify patterns and gain insights from the dataset. Additionally, NLP techniques such as tokenization, stopword removal, and word frequency analysis were applied to better understand the textual content.

### Tools and Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Plotly
* NLTK
* Regular Expressions (Regex)
* WordCloud

### Concepts Learned

* Data preprocessing
* Text cleaning
* Tokenization
* Stopword removal
* Exploratory Data Analysis (EDA)
* Data visualization
* Natural Language Processing fundamentals



## Task 02 - Building a Basic RAG Retrieval Pipeline

In this task, I implemented the core components of a Retrieval-Augmented Generation (RAG) pipeline using LangChain. First, I loaded a PDF document using PyPDFLoader and extracted its textual content. To make the document easier to process, I split the text into smaller chunks using CharacterTextSplitter and RecursiveCharacterTextSplitter, while experimenting with chunk size and chunk overlap.

After chunking the document, I generated vector embeddings for each chunk using Hugging Face embedding models. These embeddings convert text into numerical vectors that capture semantic meaning. The generated vectors were then stored in a FAISS vector database, which enables efficient similarity search.

Finally, I performed retrieval by converting user queries into embeddings and searching the FAISS index for the most relevant document chunks. This demonstrated how semantic search works and provided a foundation for building document-based question-answering systems.

### Tools and Technologies Used

Python
LangChain
PyPDFLoader
CharacterTextSplitter
RecursiveCharacterTextSplitter
Hugging Face Embeddings
FAISS Vector Database

### Concepts Learned

PDF loading and text extraction
Text chunking strategies
Chunk overlap and context preservation
Embedding generation
Vector databases
Semantic similarity search
Fundamentals of Retrieval-Augmented Generation (RAG)
