# AI Agent Approval Triage System

A comprehensive application for managing the approval workflow of new AI agents in your organization.

## Features

- **Agent Submission**: Submit new AI agents with capabilities, use cases, and documentation
- **Automated Assessment**: Preliminary checks on agent specifications
- **Review Dashboard**: Centralized interface for approvers to review submissions
- **Risk Scoring**: Automated risk assessment based on agent capabilities and permissions
- **Audit Trail**: Complete history of all approvals and rejections
- **Compliance Tracking**: Ensure agents meet organizational standards and policies
- **Integration Ready**: Connect with your existing tools and workflows

## Tech Stack

- **Frontend**: React + TypeScript + Tailwind CSS
- **Backend**: Node.js + Express + PostgreSQL
- **Authentication**: OAuth2 / OIDC
- **Containerization**: Docker
- **CI/CD**: GitHub Actions

## Quick Start

```bash
# Clone the repository
git clone https://github.com/eddycwb/ai-agent-approval.git
cd ai-agent-approval

# Start with Docker
docker-compose up

# Frontend will be available at http://localhost:3000
# API will be available at http://localhost:3001
```

## Project Structure

```
.
├── frontend/              # React application
├── backend/               # Express API server
├── database/              # Schema and migrations
├── docs/                  # Documentation
└── docker-compose.yml     # Local development setup
```

## Development

### Backend Development
```bash
cd backend
npm install
npm run dev
```

### Frontend Development
```bash
cd frontend
npm install
npm run dev
```

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

## License

MIT