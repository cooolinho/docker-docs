<h1 align="center">📚 Docker Docs</h1>

<p align="center">
  <em>Docker Compose-Konfiguration zum Hosten von Dokumentationsseiten</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Compose">
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx">
</p>

<p align="center">
  <a href="README.md">🇬🇧 English version</a>
</p>

---

## 📖 Über das Projekt

Ein Docker Compose-Setup zur Bereitstellung von Dokumentationswebseiten mit einem Webserver, konfiguriert für statisches Site-Hosting und einfache Updates.

## 🛠️ Tech-Stack

| Technologie | Version | Zweck |
|---|---|---|
| ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) Docker | Latest | Container-Laufzeit |
| ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) Nginx | Latest | Webserver |

## ✨ Funktionen

- **Statisches Site-Hosting** — Schnelle, zuverlässige Dokumentationsbereitstellung
- **Einfache Updates** — Dokumentationsverzeichnis als Volume mounten
- **Produktionsbereit** — Konfiguriert für öffentliche oder private Bereitstellung

## 🚀 Erste Schritte

### Voraussetzungen

- Docker
- Docker Compose

### Installation

```bash
git clone https://github.com/cooolinho/docker-docs.git
cd docker-docs
docker compose up -d
```

Greife auf die Dokumentation unter `http://localhost:80` zu.

## 📋 Verwendung

```bash
# Dienste starten
docker compose up -d

# Logs anzeigen
docker compose logs -f

# Dienste beenden
docker compose down
```

## 📄 Lizenz

Freigegeben unter der MIT-Lizenz.
