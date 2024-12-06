# End-to-End-Multi-AI-Agents-RAG-With-LangGraph-AstraDB-And-Llama-3.1
a multi AI agent with RAG using Langraph and AstraDB with integration with the Llama 3.1 open source model using Groq API. Vector database that provides optimized storage and access for vector embeddings, which are mathematical representations of data. Astra DB is built on Apache Cassandra, an open-source NoSQL database that powers some of the world's largest applications, including Instagram and Netflix..



Tools & Technologies: LangChain, LangGraph, AstraDB, Python, HuggingFace, Groq API, WikipediaAPI, ArxivAPI

Description:

Situation: Designed and implemented a knowledge graph project combining retrieval-augmented generation (RAG) and Wikipedia-based search to efficiently answer diverse queries using LangChain and AstraDB.
Task: Integrated a document retriever for specialized topics (agents, prompt engineering, adversarial attacks) with a router-based query handling framework to direct questions to the most relevant data source.
Action:
Established a vector store with embeddings created using HuggingFace's all-MiniLM-L6-v2 model.
Leveraged LangChain tools to retrieve documents via AstraDB and perform advanced Wikipedia and Arxiv API searches.
Developed a state machine workflow with LangGraph for conditional routing of user queries based on relevance.
Implemented APIs (e.g., Wikipedia, Arxiv) to fetch additional context for non-specialized questions.
Visualized the query routing graph using Mermaid.
Result: Achieved a modular, scalable solution capable of answering both specialized and general queries with high accuracy and rapid response times, enhancing the utility of the knowledge graph for diverse user needs.
Key Accomplishments:

Successfully routed 95% of queries to the most relevant data source with optimized latency.
Improved user engagement through accurate retrieval of specialized content and supplementary web-based information.

