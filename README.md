# TarımPlus+

A full-stack web marketplace that connects **farmers**, **workers**, and **customers** on a single platform — allowing farmers to sell their produce, workers to find agricultural jobs, and customers to buy fresh, local, organic products directly from the source.

Built as a university project at Galatasaray University.

---

## Features

- Three user roles: **Farmer**, **Worker**, and **Customer**
- User registration and login
- Farmers can post product listings; workers can post and browse job listings; customers can browse and search products
- All users and listings are stored in a database

---

## Tech Stack

**Frontend:** React, JavaScript
**Backend:** Node.js, Express (REST API), JWT authentication
**Database:** PostgreSQL

---

## Architecture

A React frontend communicates with a Node.js / Express REST API, which connects to a PostgreSQL database.

```
Frontend (React)
        │  REST API
        ▼
Backend (Node.js + Express)
        │
        ▼
Database (PostgreSQL)
```

Authentication is handled with JWT: protected requests are verified before they reach the API, using a secret key stored in an environment variable rather than in the code.

---

## Getting Started

### Prerequisites
- Node.js and npm
- A PostgreSQL database

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/cisem00/TarimPlus+.git
   cd TarimPlus+
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file with your own values (database connection, JWT secret, port).

4. Start the backend and the frontend.

---

## Screenshots

- Landing page
  
<img width="456" height="249" alt="Ekran Resmi 2026-07-04 13 11 29" src="https://github.com/user-attachments/assets/4ba84ca7-38fe-4280-9df4-68441efb000c" />


- Sign up / Login
  
<img width="455" height="246" alt="Ekran Resmi 2026-07-04 13 11 59" src="https://github.com/user-attachments/assets/c6bdd4b9-27f7-454b-8149-f396871d83b0" />


- Product listings (customer view)
  
  <img width="453" height="242" alt="Ekran Resmi 2026-07-04 13 12 23" src="https://github.com/user-attachments/assets/0ce92052-96c6-4f78-b5f4-812c769bf741" />
  

- Job listings (worker view)
  
  <img width="450" height="245" alt="Ekran Resmi 2026-07-04 13 13 02" src="https://github.com/user-attachments/assets/cad43c22-ba3c-4087-b6c4-d61a291ed177" />
  

- Create listing page
  
  <img width="456" height="242" alt="Ekran Resmi 2026-07-04 13 13 27" src="https://github.com/user-attachments/assets/a9fc51bd-b201-42ce-a2d9-c34b74f426ef" />
  


---

## Author

**Çisem Kaplan** — [GitHub](https://github.com/cisem00)

*Developed as a university group project; this repository contains the full implementation.*
