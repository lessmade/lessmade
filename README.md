
# lessmade

> Building distributed backend systems.

### Tech Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

---

## Featured Project

### WorkTime Sync *(Hackathon • RTU MIREA "Spring Code")*

Distributed microservice system for employee workload analysis and calendar synchronization.

**My microservices**

- **Conflict Service** — Detects schedule conflicts using employee profiles and calendar events. Consumes Kafka events and recalculates conflicts automatically.
- **Profile Service** — Stores employee profiles and publishes domain events for other microservices.
- **Task Service** — Imports and normalizes Google Calendar events into a unified internal model.

**Built with**

`Spring Boot` • `Apache Kafka` • `PostgreSQL` • `Docker`


