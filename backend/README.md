# VPRO Agent Platform - Backend

## Project Overview

The backend of VPRO Agent Platform is developed using Python and FastAPI.

It provides the API and AI integration layer for the Agentic AI conversational application.

## Technology Stack

- Python
- FastAPI
- Uvicorn
- SQLAlchemy
- PostgreSQL
- pgvector
- LangChain
- LangGraph
- AWS Bedrock
- Amazon Titan
- MCP
- RAGAS
- Docker

## Architecture

The documented application flow is:

React → FastAPI → LangGraph

The backend architecture includes:

1. Application installation.
2. Service initialization.
3. Database connections and tables.
4. Document indexing.
5. MCP integration.
6. Knowledge base queries.

## AI and RAG Components

### Retrieval-Augmented Generation

The project documentation identifies:

- RAG
- CRAG
- SRAG

### Agent Orchestration

LangGraph is used in the documented architecture for agent workflow orchestration.

### Model Integration

- AWS Bedrock
- Amazon Titan
- LangChain AWS integration

### Database and Vector Search

- PostgreSQL
- pgvector

### Model Context Protocol

The documented MCP tools include:

1. Calculator
2. Search Knowledge Base

### Security and Engineering

- Security Guardrails
- Harness Engineering

## Evaluation Framework

The backend contains evaluation scripts for:

- Dataset evaluation.
- Live RAG evaluation.
- Evaluation report generation.
- Agent evaluation.
- RAG evaluation gates.

## Installation

Install the backend dependencies:

```bash
pip install -r requirements.txt
```

## Environment Configuration

Configure the required environment variables before running the application.

Never commit credentials, API keys, AWS secrets, or database passwords.

Refer to the local development configuration instructions.

## Testing

Run the automated tests using:

```bash
pytest
```

## Deployment

The project documentation identifies Docker and AWS as deployment technologies.

Refer to the deployment configuration for the actual deployment procedure.

## Author

Jaya Aditya

GitHub: https://github.com/JayaAditya92
