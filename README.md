<p align="center">
  <img src="./assets/system-flow.png" width="85%" alt="Real Estate System Flow" />
</p>

# 🏠 Enterprise Real Estate API

A high-performance, stateless backend service designed for real estate market orchestration. Built with **Clean Architecture** and **Domain-Driven Design (DDD)** principles.

---

## 🚀 Core Capabilities

* **⚡ Geo-Spatial Search:** Advanced filtering for property locations and proximity.
* **🔐 Identity Management:** RBAC (Role-Based Access Control) with JWT integration.
* **📦 Asset Management:** Dynamic SVG rendering and automated property metadata handling.
* **🛡 Data Integrity:** Strict schema validation via **Zod** or **Joi**.
* **📉 Rate Limiting:** Built-in protection against DDoS and brute-force attacks.

---

## 🛠 Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Runtime** | Node.js (LTS) |
| **Framework** | Express.js (Strict Routing) |
| **Persistence** | MongoDB (Mongoose) / PostgreSQL |
| **Security** | Helmet, Argon2, JWT |
| **DevOps** | Docker, Morgan (Logging), Dotenv |

---

## 📂 Project Blueprint

```text
src/
├── api/             # Transport layer (Controllers & Routes)
├── core/            # Business logic (Services & Use-cases)
├── data/            # Persistence layer (Models & Migrations)
├── middleware/      # Auth, Error handling & Interceptors
└── shared/          # Utility functions & Constants
