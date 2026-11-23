<div align="center">

# Marc Schaar

### Full-Stack Developer · Python / Django REST Framework · TypeScript / Angular

Ich baue produktive Webanwendungen von der Datenbank bis zur Oberfläche –<br/>
mit klarer Architektur, testgetrieben und automatisiert ausgeliefert.

<a href="https://marc-schaar.com"><img src="https://img.shields.io/badge/Portfolio-marc--schaar.com-0e75b6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
<a href="mailto:kontakt@marc-schaar.com"><img src="https://img.shields.io/badge/E--Mail-kontakt%40marc--schaar.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="E-Mail" /></a>

</div>

---

## Kurzprofil

Full-Stack-Entwickler mit Schwerpunkt auf **Django REST Framework** im Backend und **Angular** im Frontend. Beruflich entwickle und betreibe ich eine produktive Dokumentationsplattform für Prüfungen und Wartungen – von Datenmodell und API-Design über PDF-Erzeugung und Schnittstellen zu Drittsystemen bis zum Deployment auf eigenem Linux-Server.

Mein Anspruch: fachlich komplexe Abläufe in Software übersetzen, die verständlich, testbar und wartbar bleibt.

> 🇬🇧 **English:** Full-stack developer (Python/Django REST Framework, TypeScript/Angular). I build and run production web apps end to end – data modelling, API design, CI/CD and Linux deployment – with a test-driven, service-layer architecture and pragmatic LLM integrations.

## Was ich mitbringe

- **Backend-Architektur:** Service-/Selector-Layer statt Fachlogik in Views und Serializern, explizite Serializer, rollenbasierte Rechte (RBAC), OpenAPI-Verträge (drf-spectacular) zwischen Backend und Frontend
- **Qualität als Standard:** TDD mit pytest, Postman-Collections als Abnahmetests, ruff, mypy, import-linter und automatisch geprüfte Größenlimits je Funktion und Datei
- **Modernes Angular:** Standalone Components, Signals, strict TypeScript, Tailwind CSS, Vitest (Angular 19 – 22)
- **Asynchrone Verarbeitung & Daten:** PostgreSQL/PostGIS, Celery, Redis, RQ, pg-boss für Hintergrundjobs, Synchronisation und Transcoding
- **Betrieb:** GitHub Actions, Docker, Gunicorn, Nginx, Supervisor, Deploy-Skripte mit CI-Gate auf Ubuntu-Servern
- **KI-Integration:** Multi-Provider-Anbindungen (Gemini mit Groq-Fallback, Claude) mit strukturierten JSON-Ausgaben – die KI erklärt berechnete Ergebnisse, die Berechnung selbst bleibt deterministisch und testbar

## Tech-Stack

**Backend** &nbsp;
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white" alt="Django" />
<img src="https://img.shields.io/badge/Django_REST_Framework-A30000?style=flat-square&logo=django&logoColor=white" alt="DRF" />
<img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS" />
<img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" alt="Celery" />

**Frontend** &nbsp;
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white" alt="Angular" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />

**Daten** &nbsp;
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white" alt="PostGIS" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black" alt="Firebase" />

**Qualität & Betrieb** &nbsp;
<img src="https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest" />
<img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest" />
<img src="https://img.shields.io/badge/Ruff-D7FF64?style=flat-square&logo=ruff&logoColor=black" alt="Ruff" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />

**KI** &nbsp;
<img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini" />
<img src="https://img.shields.io/badge/Groq-F55036?style=flat-square" alt="Groq" />
<img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude" />

---

## Ausgewählte Projekte

### 🚴 Kudos Care – Wartungs-Tracking mit Strava-Integration
[Backend](https://github.com/Marc-Schaar/kudos_care_backend) · [Frontend](https://github.com/Marc-Schaar/kudos-care) · *produktiv auf eigenem Server*

Synchronisiert Fahrten und Räder per Strava-OAuth, ergänzt jede Fahrt um historische Wetter- und Winddaten und berechnet den Verschleiß von Kette, Reifen, Bremsbelägen & Co. – gewichtet nach Regen, Hitze, Kälte und Wind – mit Status `ok` / `warn` / `critical`. Eine optionale KI-Schicht erklärt die Ergebnisse in Klartext.

`Django 6` `DRF` `PostGIS` `Celery/Redis` `Angular 21 (Signals)` `Tailwind v4` `MapLibre` `Gemini/Groq`

### 🎬 Videoflix – Video-Streaming-API
[Repository](https://github.com/Marc-Schaar/videoflix_backend) · [Live](https://videoflix.marc-schaar.com)

Streaming-Backend mit automatischem HLS-Transcoding in mehreren Auflösungen über eine Job-Queue sowie JWT-Authentifizierung über HttpOnly-Cookies.

`Django` `DRF` `ffmpeg` `Redis/RQ` `Docker` `CI/CD`

### 📋 KanMind – Kanban-API mit Rollenrechten
[Repository](https://github.com/Marc-Schaar/kan_mind_backend) · [Live](https://kanmind.marc-schaar.com)

Mehrbenutzer-Kanban-Backend mit Token-Authentifizierung, strikter rollenbasierter Zugriffskontrolle und Integrationstests.

`Django` `DRF` `RBAC` `pytest`

### 💼 Coderr – Freelancer-Plattform
[Repository](https://github.com/Marc-Schaar/coderr_backend) · [Live](https://coderr.marc-schaar.com)

REST-API für einen Freelancer-Marktplatz: Angebote, Bestellungen und Bewertungen mit feingranularen Berechtigungen, containerisiert und per CI/CD ausgeliefert.

`Django` `DRF` `Docker` `GitHub Actions`

### 💬 DA-Bubble – Team-Chat in Echtzeit
[Repository](https://github.com/Marc-Schaar/da-bubble) · [Live](https://da-bubble.marc-schaar.com)

Slack-inspirierter Messenger mit Channels, Threads, Direktnachrichten und Mentions.

`Angular 19 (Standalone, Signals)` `Firebase`

<details>
<summary><b>Weitere Projekte</b></summary>
<br/>

| Projekt | Beschreibung | Stack |
| :--- | :--- | :--- |
| [Quizly](https://github.com/Marc-Schaar/quizly_backend) | REST-API für eine KI-gestützte Quiz-Anwendung | Django, DRF |
| [Join](https://github.com/Marc-Schaar/Join) · [Live](https://join.marc-schaar.com) | Kanban-Task-Manager mit Drag & Drop und Kontaktverwaltung | JavaScript (OOP), Firebase |
| [El Pollo Loco](https://github.com/Marc-Schaar/El-Pollo-Loco) · [Live](https://el-pollo-loco.marc-schaar.com) | 2D-Jump-'n'-Run im Browser | JavaScript, HTML5 Canvas |

</details>

**Beruflich & nicht öffentlich:** Dokumentationsplattform für Prüfungen und Wartungen (Django 5.2 LTS, DRF, Angular 22, PDF-Erzeugung, digitale Signatur, IP-gesicherte Integrations-API) sowie ein Backend für Instandhaltung und Lufttüchtigkeit von Segelflugzeugen nach Part-ML/Part-CAO (Django 6, PostgreSQL 18, Python 3.14). Details gern im Gespräch.

---

## GitHub-Aktivität

<!--
Die Karten werden einmal täglich per GitHub Actions (.github/workflows/metrics.yml, lowlighter/metrics)
generiert und direkt in dieses Repo committet – kein Live-Rendering durch Drittanbieter.
-->
<p align="left">
  <img src="https://raw.githubusercontent.com/Marc-Schaar/Marc-Schaar/main/metrics.base.svg" alt="GitHub-Metriken" width="58%" />
  <img src="https://raw.githubusercontent.com/Marc-Schaar/Marc-Schaar/main/metrics.languages.svg" alt="Meistgenutzte Sprachen" width="38%" />
</p>

---

## Kontakt

Ich freue mich über Nachrichten zu Projekten, Zusammenarbeit oder spannenden Positionen.

📧 [kontakt@marc-schaar.com](mailto:kontakt@marc-schaar.com) &nbsp;·&nbsp; 🌍 [marc-schaar.com](https://marc-schaar.com)
