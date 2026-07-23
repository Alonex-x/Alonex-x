<div align="center">
  <h1 style="font-family: monospace; color: #c9d1d9;">Hi, I am <span style="color: #58a6ff;">Alone</span></h1>
</div>

<img src="img/Wallpaper%20PC.jpg" alt="Alone" width="300" align="right">

### Alone | Solucionador Técnico
Desarrollador especializado en automatización de procesos, extracción de datos y configuración de servidores.

**Stack principal:**
- Python (Scripting, Scraping, Automatización)
- WordPress (Optimización, Migración, Seguridad)
- Linux (Bash, Administración de Servidores)
- conocimiento en ciberseguridad | hacking ético 

<br clear="right">

---

## Skills

### Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Tools & Platforms
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## Proyectos
- Scripts de automatización para tareas repetitivas
- Configuraciones de seguridad para sitios con alto tráfico
- Herramientas de análisis de datos desde fuentes públicas

---

## Connect with me

[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/user/alonex_x1)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Alonex-x)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alonex_x.com@proton.me)

## GitHub Stats

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Alonex-x&theme=dark" alt="GitHub Streak" />
  <br>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Alonex-x&theme=dark" alt="Top Languages" />
</div>

---

```markdown
# Nexus Ecosystem

Sistema modular de agentes de software autónomos. Cada componente se comunica a través de una API REST central, permitiendo registro, asignación de misiones, reporte de eventos y supervisión en tiempo real.

## Cómo empezar

1. **Clonar los repositorios:**
   - [nexus-agent-api](https://github.com/Alonex-x/nexus-agent-api)
   - [nexus-scraper](https://github.com/Alonex-x/nexus-scraper)
   - [nexus-terminal](https://github.com/Alonex-x/nexus-terminal)

2. **Orden de arranque:**
   - **Primero:** levantar la API (puerto `8080`).
   - **Segundo:** ejecutar el scraper (se registra contra la API y consulta misiones cada 30s).
   - **Tercero:** abrir el panel de control (consulta el estado de los agentes en tiempo real).

3. **Registro y comunicación:**
   - Cada agente se registra con `POST /api/v1/agents/register` y obtiene una API Key.
   - Los agentes envían heartbeats periódicos (`POST /api/v1/agents/heartbeat`).
   - Las misiones se crean en la API y son recogidas por los agentes correspondientes.

## Arquitectura

```mermaid
graph TD
    NEXUS[Nexus Terminal] -->|consulta estado, lanza misiones| API[Nexus Agent Management API]
    SCRAPER[Scraper v1] -->|registra, heartbeat, recibe misiones| API
    SNIFFER[Sniffer v1] -->|registra, heartbeat, envía eventos| API
    MONITOR[Monitor v1] -->|registra, heartbeat, reporta cambios| API
    KIS[KIS v1] -->|registra, heartbeat, envía patrones| API
```

## Componentes

| Proyecto | Lenguaje | Descripción |
|----------|----------|-------------|
| [Nexus Terminal](https://github.com/Alonex-x/nexus-terminal) | HTML/CSS/JS | Panel de control visual con estética CRT |
| [Nexus Agent Management API](https://github.com/Alonex-x/nexus-agent-api) | Java/Spring Boot | API REST central del ecosistema |
| [Nexus Scraper](https://github.com/Alonex-x/nexus-scraper) | Python/Playwright | Agente de web scraping sigiloso |
| [Desktop Automation Toolkit](https://github.com/Alonex-x/desktop-automation-toolkit) | Python | Automatización de tareas de escritorio |
| [Network Traffic Analyzer](https://github.com/Alonex-x/network-traffic-analyzer) | Java | Análisis de tráfico de red |
| [File Integrity Monitor](https://github.com/Alonex-x/file-integrity-monitor) | C++ | Monitor de integridad de archivos |
| [KIS](https://github.com/Alonex-x/nexus-kis) | C++ | Estadísticas de entrada de teclado |

## Demos

- **Nexus Terminal (demo en vivo):** [alonex-x.github.io/nexus-terminal](https://alonex-x.github.io/nexus-terminal)
- **Video del scraper en acción:** [Ver demo](https://raw.githubusercontent.com/Alonex-x/nexus-scraper/main/demos/demo-scraper.mp4)
```

---
