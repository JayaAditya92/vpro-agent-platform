# VPRO Agent Platform | Agentic AI & RAG Application

An Agentic AI application integrating React, FastAPI, LangGraph, Model Context Protocol (MCP), Retrieval-Augmented Generation (RAG), PostgreSQL with pgvector, and AWS Bedrock.

## Project Overview

VPRO Agent Platform is a hands-on Agentic AI project focused on developing an AI-powered conversational application.

The platform integrates frontend and backend components with AI services, knowledge retrieval, database connectivity, agent workflows, and evaluation capabilities.

## Architecture

The application follows this high-level architecture:

**React → FastAPI → LangGraph → AI Services**

Core components include:

- React frontend for user interaction.
- FastAPI backend for API integration.
- LangGraph for agent workflow orchestration.
- PostgreSQL with pgvector for database and vector operations.
- AWS Bedrock for foundation model integration.
- Amazon Titan for embedding integration.
- MCP Server for tool integration.
- RAG workflows for knowledge retrieval.
- Security Guardrails and Harness Engineering.

## Technology Stack

### Frontend
- React 19
- JavaScript
- Vite
- HTML
- CSS

### Backend
- Python
- FastAPI
- Uvicorn
- SQLAlchemy
- LangChain
- LangGraph

### Generative AI & Agentic AI
- AWS Bedrock
- Amazon Titan
- Retrieval-Augmented Generation (RAG)
- Corrective RAG (CRAG)
- SRAG
- Model Context Protocol (MCP)
- Security Guardrails
- Harness Engineering

### Database
- PostgreSQL
- pgvector

### Evaluation & Testing
- RAGAS
- Pytest
- HTTPX
- Dataset Evaluation
- RAG Evaluation

### Cloud & Deployment
- AWS
- Docker
- Docker Compose
- GitHub Actions

## MCP Tools

The project documentation identifies the following MCP tools:

1. Calculator
2. Search Knowledge Base

## Project Structure

```text
vpro-agent-platform/
│
├── .github/
│   └── workflows/
│
├── backend/
│   ├── app/
│   ├── data/
│   ├── tests/
│   ├── evaluate_dataset.py
│   ├── evaluate_live_rag.py
│   ├── generate_evaluation_report.py
│   ├── requirements.txt
│   └── README.md
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   ├── vite.config.js
│   └── README.md
│
├── images/
├── docker-compose.yml
└── README.md
```

## Evaluation Framework

The backend includes evaluation scripts for:

- Dataset evaluation.
- Live RAG evaluation.
- Evaluation report generation.
- Agent evaluation.
- RAG evaluation gates.
- Automated testing.

## Getting Started

### Clone Repository

```bash
git clone https://github.com/JayaAditya92/vpro-agent-platform.git

cd vpro-agent-platform
```

### Backend

Navigate to the backend directory:

```bash
cd backend
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Refer to the backend documentation for environment configuration and application startup instructions.

### Frontend

Navigate to the frontend directory:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Build the frontend:

```bash
npm run build
```

## Security

- Store sensitive credentials in environment variables.
- Never commit API keys or AWS credentials.
- Do not expose database connection strings.
- Keep sensitive configuration files outside version control.

## Author

**Jaya Aditya**

GitHub: https://github.com/JayaAditya92

## License

No license has been specified yet.
