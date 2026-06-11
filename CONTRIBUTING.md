# Contributing to AI Agent Approval Triage System

## Getting Started

1. Fork the repository
2. Clone your fork: `git clone <your-fork>`
3. Create a feature branch: `git checkout -b feature/your-feature`
4. Set up development environment: `docker-compose up`

## Development Workflow

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

## Code Standards

- Use TypeScript for type safety
- Follow ESLint configuration
- Write tests for new features
- Keep functions small and focused

## Pull Request Process

1. Update documentation
2. Add/update tests
3. Run linter: `npm run lint`
4. Submit PR with clear description
5. Wait for code review and CI to pass

## Commit Message Format

```
<type>(<scope>): <subject>

<body>

<footer>
```

Types: feat, fix, docs, style, refactor, test, chore

## Questions?

Open an issue or reach out to the maintainers.