# Welcome to Ecosistema de Información Académica Dinara 

We are building the future of scalable, modular, and efficient software solutions. Our technology stack is carefully chosen to ensure robust, maintainable, and high-performance applications.

## 🛠 Technology Stack

### Backend (REST API)
Our backend infrastructure is built on modern, scalable technologies:
- **Runtime Environment**: Node.js v22.12.0
- **Framework**: NestJS v10.0.0
- **Database**: PostgreSQL v16
- **ORM**: Prisma v6.2.1
- **Language**: TypeScript v5.7.2

### Frontend
Our frontend architecture leverages micro-frontends for scalability and maintainability:
- **Runtime Environment**: Node.js v22.12.0
- **Core Library**: React v18.3.1
- **DOM Rendering**: React DOM v18.3.1
- **UI Framework**: Material MUI v6.3.0
- **Micro-Frontend Architecture**:
  - Single-spa v6.0.3
  - Single-spa React v6.0.2
  - Module Federation Enhanced v0.8.5
- **Development Tools**:
  - TypeScript v5.7.2
  - Webpack v5.97.1
  - Babel v7.26.0
- **Type Definitions & Testing**:
  - @types/react v18.3.18
  - @types/react-dom v18.3.5
  - @testing-library/react v16.1.0

## 📋 Development Conventions

### Language Standards
We maintain English as our primary development language for:
- Variable naming
- Code comments
- Repository names

### Git Workflow Guidelines

#### Branch Management
- `main`: Production-only branch
  - Contains only production-ready code
  - Direct commits/pushes are not allowed
  - Changes only through approved pull requests
- `dev`: Main development branch
  - All feature development starts from here
  - Base branch for all feature branches
  - Intermediate testing and integration

#### Development Workflow
1. Create a new feature branch from `dev`
   - Use descriptive names reflecting the feature
   - Format: `feature/descriptive-name` or `fix/issue-description`
2. Work on your feature branch
3. Create a pull request to merge into `dev`
4. After testing and approval, merge into `dev`
5. Production releases are managed through `dev` → `main` merges

#### Commit Guidelines
We follow a structured commit message format:
```
<type>: [<ticket>] <description>
```

#### Commit Types
- `feat`: New features
- `fix`: Bug fixes
- `hot-fix`: Critical fixes requiring immediate deployment

## 🤝 Contributing
We welcome contributions that align with our technical standards and coding conventions. Please ensure you follow our commit message format and coding standards when submitting pull requests.

---
© 2025 Universidad Nacional de Colombia

Developed by Dirección Nacional de Información Académica Registro y Matrícula - DINARA
