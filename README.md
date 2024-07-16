# CS5391ProjectUpdates
This repository holds my weekly reports regarding my progress on our CS5391 project. 

# Week 5

This week, I've been focusing on different chunking methods for large language models (LLMs) such as GPT-3 and GPT-4. Chunking involves breaking down long texts into smaller, manageable pieces or "chunks" to fit within the token limits of these models, which enhances performance and maintains context more effectively.
To put these methods into practice, I used Beautiful Soup to scrape a webpage and experimented with applying different chunking techniques to the extracted data.

I also considered several factors to determine the best chunk size for tasks like text summarization. These factors included token limits of LLMs, memory and performance requirements, coherence and context maintenance, complexity of the text, task specificity, and the balance between performance and accuracy.

To further explore chunk sizes, I implemented a script to experiment with different chunk sizes (256, 512, 1024, 2048 tokens) and evaluated the number of chunks produced. This helped in understanding how different sizes affect the chunk count and, implicitly, the potential impact on processing and performance.

Overall, this week’s work has deepened my understanding of how to effectively manage large texts with LLMs and will inform future projects involving text processing and summarization.

# Week 4

To build a Retrieval-Augmented Generation (RAG) system that accesses files on my local machine, I began by setting up a virtual environment and installing necessary libraries such as sentence-transformers, faiss-cpu, torch, transformers, PyMuPDF, python-docx, jupyter, and ipywidgets. I then created and saved sample text files on various topics like the history of computing and climate change. Using a Jupyter Notebook, I imported the required libraries, loaded pre-trained models for sentence embedding and language generation, and implemented functions to read content from different file types. I generated embeddings for the documents using sentence-transformers and indexed them with FAISS for efficient similarity search. For querying, I encoded user queries to search for the most similar documents using the FAISS index. Initially, I used a local model (distilgpt2) for answer generation but switched to GPT-3.5-turbo via the OpenAI API for better results. I then created a UI with ipywidgets for query input and results display, resolving issues with widget display by enabling necessary Jupyter extensions. The system successfully generated relevant responses, such as explaining the negative impacts of climate change and mitigation efforts.

7/5/2024: Ria, Zareenah, Grant, and I met for coffee and discussed the first steps of the project. I plan to do some research on knowledge graphs and practice using beautifulsoup before Tuesday’s meeting. I will update my GitHub page accordingly.

# Week 3

This week, I focused on understanding AI agents by following David Ondrej's YouTube video titled "Build Anything with AI Agents, Here's How." AI agents are poised to revolutionize technology by autonomously making decisions and taking actions towards specific goals without needing detailed human instructions. According to Andrej Karpathy, AI agents are the path to achieving Artificial General Intelligence (AGI), though it will require better large language models (LLMs), affordable API costs, and user-friendly interfaces.

AI agents excel at automating clear, simple tasks and are already being utilized in various fields, such as 24/7 research, software engineering, and customer service. While LLMs currently perform quick, predictive tasks (System 1 thinking), the goal is to develop agents capable of strategic reasoning (System 2 thinking). To experiment with AI agents, I chose CrewAI for its ease of setup and robust documentation. I set up a Google Colab notebook, installed CrewAI, and defined two agents: a researcher to analyze AI advancements and a writer to summarize these findings into an engaging article. This setup aims to streamline the process of leveraging AI agents for complex tasks and prepare for the future advancements in AI technology.

# Week 2

This week, I initially started working on creating a generative search engine on my local machine, following an article on Medium. Despite facing some difficulties, I plan to revisit this project later. Instead, I shifted focus to building my own vector database. With the help of ChatGPT, I successfully generated embeddings, created a vector database, and queried it.

The original task involved designing a system to index local files, retrieve relevant documents, and generate answers using a language model like Llama 3. Although I had to abandon this project temporarily due to access issues with Llama 3, I progressed with my vector database project. Using tools like Qdrant, Streamlit, and Faiss, I managed to create a semantic index and query it effectively. This week’s experience has provided valuable insights into embedding models and vector databases, laying the groundwork for future projects in AI and information retrieval.

# Week 1

This week, I tackled three main tasks. First, I experimented with embeddings using a Python program. I set up a virtual environment, installed the "Transformers" package from Huggingface, and used Jupyter Notebook to execute code that computed the cosine similarity between sentence embeddings. This task provided hands-on experience with embedding models and their applications.

Next, I worked on running Ollama on Genuse servers. After downloading Cisco VPN for remote login, I connected to the Genuse server and successfully ran Ollama, loading the Llama2 model to interact with it. This task was essential for understanding how to deploy and utilize large language models on remote servers.

Lastly, I began building my own Retrieval-Augmented Generation (RAG) system using Langchain, Ollama, and Streamlit. This involved setting up a virtual environment, creating and configuring the necessary Python files, and drafting a user interface for the RAG system. Although I encountered some roadblocks, such as issues with recognizing Streamlit installations and accessing files from the virtual environment, I made significant progress. Despite not fully resolving the final problem of viewing Streamlit in the browser, the groundwork laid this week has been invaluable for future development.
