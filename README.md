# Privacy-First Local Agentic Knowledge Base and Code Synthesizer

## Group 4

**Team Members and Contact Information**

| Student Name | GitHub ID | Student Email |
| -------- | -------- | -------- |
| Tarangkumar Janakkumar Patel | https://github.com/TarangkumarPatel | tjpatel5@myseneca.ca |
| Jaishnav Prasad | https://github.com/CyberJalagam | jprasad3@myseneca.ca |
| Festus Sabu | https://github.com/festussabu | fsabu@myseneca.ca |
| Faith Sam | https://github.com/faithsam32004 | fsam3@myseneca.ca |

## Problem

Developers, students, researchers, and professionals increasingly rely on AI assistants to search, summarize, and reason over their documents, notes, and codebases. However, most of these tools send data to cloud providers, which creates serious privacy, security, and compliance risks for anyone working with confidential, proprietary, or regulated information. Many organizations ban cloud AI tools outright for this reason, and individuals often hesitate to upload personal files or private source code. They also depend on a constant internet connection and recurring subscription fees. As a result, the people who would benefit most from AI-powered knowledge tools are often the ones who cannot safely use them, leaving them to search and cross-reference large collections of files manually.

## Proposed Solution

We propose a privacy-first desktop application that lets users ingest their local files, including documents, codebases, and notes, and use fully offline AI models to search, reason, summarize, and answer complex multi-step questions without sending any data to a cloud provider. The application will process files into vector embeddings stored in a local database, then use a retrieval-augmented generation (RAG) engine to ground every answer in the user's own content. Autonomous multi-agent workflows with tool calling will handle tasks that require several steps, such as comparing documents, tracing logic across a codebase, or generating new code based on existing files. All of this will run behind a clean, intuitive desktop interface packaged as a standalone executable, demonstrating that powerful AI applications can operate entirely offline with zero cloud dependency.


## Technologies

- *Backend and AI pipeline:* Python for data ingestion, embedding generation, and vector processing
- *Local API and process management:* FastAPI with asynchronous request handling
- *Agent orchestration:* LangChain or LlamaIndex for RAG and multi-agent tool-calling workflows
- *Local LLMs:* Ollama to run open-source language and embedding models on the user's machine
- *Vector database:* ChromaDB or LanceDB as an embedded, file-based vector store
- *Frontend:* React with TypeScript
- *Desktop packaging:* Tauri to bundle the app as a standalone desktop executable
- *Collaboration and DevOps:* Git and GitHub (issues, branches, pull requests), GitHub Projects for Agile planning, and GitHub Actions for automated CI/CD
