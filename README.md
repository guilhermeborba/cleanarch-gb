# CleanArch-GB

Backend project built with Node.js and TypeScript using Clean Architecture, SOLID principles, DDD, and TDD.  
Developed as a hands-on learning project based on Rodrigo Manguinho's course.

## ✨ Technologies

- [Node.js](https://nodejs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/)
- [Jest](https://jestjs.io/) – Unit testing
- [MongoDB](https://www.mongodb.com/) – Database
- [Husky](https://typicode.github.io/husky/#/) – Git hooks
- [Lint-Staged](https://github.com/okonet/lint-staged) – Pre-commit linting
- [ESLint + Prettier](https://eslint.org/) – Code style
- [Docker](https://www.docker.com/) (optional)

## 🧱 Architecture

This project follows a modular structure with layered separation, based on:

- **Domain** – Entities and business rules (Enterprise Business Rules)
- **Data** – Business rule implementations and adapters (Application Business Rules)
- **Infra** – External implementations (Drivers/Frameworks)
- **Presentation** – HTTP controllers and routes
- **Main** – Application setup (dependency injection, startup)

### Applied patterns

- Clean Architecture
- SOLID principles
- Domain-Driven Design (DDD)
- Test-Driven Development (TDD)

## 📁 Project Structure

```
src/
├── domain/
├── data/
├── infra/
├── presentation/
├── main/
└── validations/
```

## 🚀 Getting Started

### Prerequisites

- Node.js LTS
- MongoDB (local or Docker)
- Yarn or NPM

### Installation

```bash
# Install dependencies
yarn install

# Copy the example env file and configure your variables
cp .env.example .env
```

### Run in development mode

```bash
yarn dev
```

The API will be available at: `http://localhost:5050`

### Run tests

```bash
yarn test
```

### View test coverage

```bash
yarn test:cov
```

### Lint and format

```bash
yarn lint
yarn format
```

## 🐳 Docker (optional)

```bash
docker-compose up -d
```

## 🧪 Testing

- 100% test coverage with Jest
- Unit tests for all use cases
- Integration tests for HTTP routes

## 🧠 Key Concepts

- Clean Architecture with well-defined layers
- Test-Driven Development (TDD)
- Dependency Inversion (via dependency injection)
- Domain-Driven Design (DDD)
- SOLID principles

## 📌 Project Status

🚧 In development – initial version based on the Udemy course.  
New features are being added in each lesson with full test coverage and best practices.

## 👨‍💻 Author

**Guilherme Borba**  
[LinkedIn](https://www.linkedin.com/in/guilhermeborba) • [GitHub](https://github.com/guilhermeborba)


