<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0f0f,100:1a1a2e&height=160&section=header&text=Omar%20Khaled&fontSize=52&fontColor=e2e8f0&animation=fadeIn&fontAlignY=38&desc=Backend%20Engineer%20%E2%80%94%20Node.js%20%7C%20TypeScript%20%7C%20PostgreSQL&descSize=16&descAlignY=60&descColor=94a3b8" width="100%"/>
</div>

<br/>

I build backend systems and occasionally go deeper than I need to - like writing a database engine from scratch to understand what sits under the ORMs I use every day.

Currently finishing a B.Sc. in Electrical Engineering at Alexandria University and looking for backend engineering roles.

<br/>

---

## Projects

<br/>

**[FetchDB](https://github.com/OmarKHDR/FetchDB)** &nbsp;·&nbsp; *Relational database engine, from scratch*

> `NestJS` `TypeScript` `Binary I/O` `Parser`

A working SQL-over-HTTP engine built without any database libraries. The goal was to understand storage and query execution at the level most engineers never touch.

- Character-level lexer → Pratt parser → typed AST → execution
- Append-only binary storage with O(1) primary key lookup
- MVCC-inspired row versioning - full history preserved, no data loss
- Promise-chaining mutex for FIFO write ordering
- Schema versioning with rollback to any prior table state
- **Supports:** `SELECT` `INSERT` `UPDATE` `DELETE` `CREATE TABLE` - full `WHERE` expression evaluation (no subqueries), `ORDER BY`, `LIMIT`

<br/>

**[LinkGate](https://github.com/OmarKHDR/linkgate)** &nbsp;·&nbsp; *Multi-role URL shortener*

> `NestJS` `TypeScript` `Prisma` `PostgreSQL`

- Three access tiers (public, private, group) with authorization enforced at the query level via Prisma - not in application logic
- Group membership modeled as a junction table with role and status enums
- Uniqueness handled with a hex generator and length-scaling retry loop - no pre-insertion check needed

<br/>

**[Job Finder](https://github.com/OmarKHDR/job-finder)** &nbsp;·&nbsp; *REST API with multi-role auth*

> `Node.js` `TypeScript` `Express` `PostgreSQL` `Sequelize` `JWT`

- JWT auth with refresh token rotation across three user roles
- Normalized PostgreSQL schema (3NF) with indexes on high-frequency query columns

<br/>

**SANAD** &nbsp;·&nbsp; *Autonomous wheelchair + smart home backend - graduation project, in progress*

> `Node.js` `Express` `WebSockets` `UDP` `ROS` `Jest` `Supertest` `Swagger`

- REST API and WebSocket gateway bridging a remote client with onboard wheelchair hardware over a real-time network boundary
- Smart home module using UDP broadcast for zero-config device discovery - each device runs a minimal HTTP server exposing `GET /state` and `POST /control`
- Full device and wheelchair state published to ROS so other system modules can interact through standard ROS interfaces
- Feature-based module structure (Singleton + Builder patterns) replacing a layered monolith
- Jest/Supertest integration tests for all completed endpoints; Swagger/OpenAPI docs for hardware team integration

<br/>

---

## Stack

```
Node.js · TypeScript · NestJS · Express.js
PostgreSQL · MongoDB · Redis · Prisma · Sequelize
REST · WebSockets · Socket.io · Swagger/OpenAPI
JWT · OAuth2 · RBAC · Refresh Token Rotation
Jest · Supertest · Docker · CI/CD · GitHub Actions · Linux
```

<br/>

---

## Background

| | |
|---|---|
| **Backend Intern** | NWeave Development |
| **Full Stack Developer** | OPST Research Lab, Alexandria University &nbsp;·&nbsp; *2024* |
| **Vice Head, SWE Team** | IEEE SSCS Alexandria University &nbsp;·&nbsp; *2024* |
| **Software Engineering** | Holberton School / ALX Africa &nbsp;·&nbsp; *2023–2024* |
| **B.Sc. Electrical Engineering** | Alexandria University &nbsp;·&nbsp; *2021–2026, GPA 3.33* |

<br/>

---

<div align="center">

<a href="mailto:omarsliman37@gmail.com"><img src="https://img.shields.io/badge/Email-omarsliman37@gmail.com-0f172a?style=flat-square&logo=gmail&logoColor=94a3b8&labelColor=1e293b&color=1e293b"/></a>
&nbsp;
<a href="https://linkedin.com/in/omar-khdr"><img src="https://img.shields.io/badge/LinkedIn-omar--khdr-0f172a?style=flat-square&logo=linkedin&logoColor=94a3b8&labelColor=1e293b&color=1e293b"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:0f0f0f&height=80&section=footer" width="100%"/>

</div>
