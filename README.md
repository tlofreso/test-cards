# An application for managing contacts, households, and mailings.
This application will let users create households. Households will include a mailing address, and household members. When users add mailing addresses, the app will leverage the google places api for auto-completion. The tech stack will follow the Full Stack FastAPI Template:

Technology Stack and Features

⚡ FastAPI for the Python backend API.
🧰 SQLModel for the Python SQL database interactions (ORM).
🔍 Pydantic, used by FastAPI, for the data validation and settings management.
💾 PostgreSQL as the SQL database.
🚀 React for the frontend.
💃 Using TypeScript, hooks, Vite, and other parts of a modern frontend stack.
🎨 Chakra UI for the frontend components.
🤖 An automatically generated frontend client.
🧪 Playwright for End-to-End testing.
🦇 Dark mode support.
🐋 Docker Compose for development and production.
🔒 Secure password hashing by default.
🔑 JWT (JSON Web Token) authentication.
📫 Email based password recovery.
✅ Tests with Pytest.
📞 Traefik as a reverse proxy / load balancer.
🚢 Deployment instructions using Docker Compose, including how to set up a frontend Traefik proxy to handle automatic HTTPS certificates.
🏭 CI (continuous integration) and CD (continuous deployment) based on GitHub Actions.
