<h1 align="center">📚 Docker Docs</h1>

<p align="center">
  <em>Docker Compose configuration for hosting documentation sites</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Compose">
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx">
</p>

<p align="center">
  <a href="README.de.md">🇩🇪 Deutsche Version</a>
</p>

---

## 📖 About

A Docker Compose setup for deploying documentation websites with a web server, configured for static site hosting and easy updates.

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|---|---|---|
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) Docker | Latest | Container runtime |
| ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) Nginx | Latest | Web server |

## ✨ Features

- **Static site hosting** — Fast, reliable documentation delivery
- **Easy updates** — Mount documentation directory as volume
- **Production-ready** — Configured for public or private deployment

## 🚀 Getting Started

### Prerequisites

- Docker
- Docker Compose

### Installation

```bash
git clone https://github.com/cooolinho/docker-docs.git
cd docker-docs
docker compose up -d
```

Access documentation at `http://localhost:80`.

## 📋 Usage

```bash
# Start services
docker compose up -d

# View logs
docker compose logs -f

# Stop services
docker compose down
```

## 📄 License

Released under the MIT License.
