# AI_Agent_coordination
An AI-powered multi-agent coordination platform that uses specialised agents, workflow orchestration, tool integrations, and human-in-the-loop approval to automate complex tasks and support intelligent decision-making.
AI Agent Coordination & Decision Engine

An AI-powered multi-agent platform designed to coordinate specialised AI agents, execute complex workflows, integrate external tools, and support intelligent decision-making with human-in-the-loop approval.

Overview

The AI Agent Coordination & Decision Engine divides complex user tasks into smaller responsibilities and coordinates multiple specialised agents to process them.

Each agent performs a specific role, such as planning, research, analysis, or decision-making. The platform also provides tool integration, workflow execution, conversation history, memory, and human approval capabilities.

Key Features

- Multi-Agent Architecture: Specialised Planning, Research, Analysis, and Decision agents.
- Agent Orchestration: Coordinates multiple agents through structured workflows.
- Workflow Execution: Processes user tasks through multiple execution stages.
- Tool Integration: Includes Calculator, Weather, Web Research, Database Query, and Enterprise Task tools.
- Human-in-the-Loop: Allows users to approve or reject actions.
- Conversation Management: Maintains conversation history.
- Memory Support: Provides persistence for relevant interaction context.
- Execution History: Tracks tool and workflow execution.
- REST API: Backend APIs developed using FastAPI.
- Dashboard: Provides an interface for monitoring platform activities.

Technology Stack

Frontend

- React
- TypeScript
- Vite
- Tailwind CSS

Backend

- Python
- FastAPI
- LangChain
- LangGraph
- Pydantic
- SQLAlchemy

Database

- SQLite for local development and demonstration
- PostgreSQL and pgvector as production-oriented database options

Testing

- Pytest
- Vitest
- ESLint

Project Architecture

The application follows a frontend-backend architecture.

1. The user submits a task through the frontend.
2. The backend receives and processes the request.
3. The agent orchestration layer coordinates specialised agents.
4. Agents use registered tools when required.
5. Workflow results are processed and presented to the user.
6. Human approval is supported for actions requiring review.

Local Development

The project can be run locally using Python and Node.js.

- Backend: FastAPI
- Frontend: React development server
- Local database: SQLite

The current local demonstration uses a mock LLM provider.

Current Project Status

The local application is implemented and the backend automated test suite has passed 105 tests.

Web Research requires a configured Tavily-compatible API key. Production authentication, production database infrastructure, cloud deployment, and production performance validation remain future work.

Objective

The objective of this project is to demonstrate how multiple specialised AI agents can coordinate, use tools, execute workflows, and support human decision-making through a unified platform.
