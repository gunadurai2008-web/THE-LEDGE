# THE LEDGE MVP

## Product goal

A shared workspace where teammates can assign work to a real AI agent, follow its activity and code changes, and keep project knowledge in one place.

## MVP areas

1. Projects and team access
2. Agent task submission, execution history, and activity updates
3. Project workspace and code change visibility
4. Document Workspace with manual and AI-assisted document creation
5. Shared project documents that teammates can access

## Initial architecture

- React + Vite frontend
- Python + FastAPI backend
- PostgreSQL for persistent shared data
- A controlled Python agent runner
- Real-time activity updates through WebSockets

## Build sequence

1. Prepare the local development tools and start the frontend and API.
2. Add project and document data models and persistence.
3. Add team access and project document creation/editing.
4. Connect the agent runner and record its activity.
5. Add live updates, review flows, and deployment.
