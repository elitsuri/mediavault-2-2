# mediavault-2

> MediaVault 2: Local media library manager with transcoding and metadata support

## ✨ Features
- JWT authentication with access + refresh tokens
- Role-based access control (admin/user)
- Full CRUD with pagination, search, and filtering
- Premium responsive UI with dark/light mode
- Real-time validation and error handling
- Docker Compose for one-command startup
- Comprehensive README with API documentation
- Database migrations with Alembic/Flyway

## 🧰 Tech Stack
Spring Boot, Java, PostgreSQL, Docker

## 🏗️ Architecture
Three-tier architecture: Spring Boot, Java backend, native frontend, PostgreSQL database. Containerized with Docker.

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/mediavault-2
cd mediavault-2

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
