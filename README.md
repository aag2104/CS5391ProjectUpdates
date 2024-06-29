# CS5391ProjectUpdates
This repository holds my weekly reports regarding my progress on our CS5391 project. 

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
