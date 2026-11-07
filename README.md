# Hi, I'm Max 👋

**Computer Engineering student (3rd year) at Wrocław University of Science and Technology · Java / backend developer**

I like building things that work outside the classroom: distributed systems in Java, a REST API backed by PostgreSQL, and a tractor navigation app that I test on my dad's farm with centimetre-accurate RTK GPS.

🔎 Looking for an internship or junior role in **Java / backend**  
📍 Wrocław, Poland · 📫 [maksymiliankula@wp.pl](mailto:maksymiliankula@wp.pl) · 💼 [LinkedIn](https://www.linkedin.com/in/maks-kula-5213633a9/)

---

## ⭐ Featured projects

### 🚜 [AgriNav](https://github.com/Maxoo005/agri_nav) – farm navigation with RTK GPS
`Flutter` `C++17` `Bluetooth` `u-blox ZED-F9P`

Shows a tractor driver how to keep parallel passes across a field, with on-screen arrows telling which way to correct the line. With RTK corrections from the ASG-EUPOS network the position is accurate to **1–3 cm** instead of the few metres of phone GPS. I bought the receiver with my scholarship, connected it over Bluetooth myself and test the app during real field work.

### 🍸 [Cocktails API](https://github.com/Maxoo005/cocktails-api) – REST backend
`Django REST Framework` `PostgreSQL` `Docker` `Swagger / OpenAPI`

A REST API for cocktails and ingredients: CRUD, pagination, combined filters and sorting. A cocktail and its ingredients are saved in one transaction, deleting an ingredient still in use returns `409`, invalid query parameters return `400`. No N+1 queries (`prefetch_related`, `EXISTS` subqueries), amounts stored as `Decimal`, key cases covered by API tests.

### ☕ [Java Advanced Labs](https://github.com/Maxoo005/Java-labs-pwr3sem) – 7 projects in Java 17/21
`Java` `Maven` `TCP/IP` `RMI` `multithreading`

- **Hair salons** – distributed CRUD system with my own handling of write conflicts between concurrent users
- **River network** – simulator of independent programs talking over TCP/IP, later rewritten in Java RMI
- **Statistics Poland data** – HTTP client for a public API, logic and UI split into separate Maven modules
- **Agent simulation** – each agent in its own thread on a shared board, guarded by `ReentrantLock`

---

## 📂 More projects

| Project | What it is | Stack |
| --- | --- | --- |
| [GymFLowAPP](https://github.com/Maxoo005/GymFLowAPP) | workout tracking app | Flutter |
| [WeeklyPlanner](https://github.com/Maxoo005/WeeklyPlanner) | weekly planner | React, Vite, Tailwind |
| [Apl-pogodowa](https://github.com/Maxoo005/Apl-pogodowa) | weather app | Flutter |
| [ML-FakeNews](https://github.com/Maxoo005/ML-FakeNews) | fake news detection (team project) | Python, Jupyter |
| [sorting_algorithms](https://github.com/Maxoo005/sorting_algorithms) · [graphs_algorithms](https://github.com/Maxoo005/graphs_algorithms) | algorithms with benchmarks | C++, CMake, Docker |

---

## 🛠 Tech stack

**Backend & data**  
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django_REST-092E20?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle SQL](https://img.shields.io/badge/Oracle_SQL-F80000?style=flat-square&logoColor=white)

**Mobile & web**  
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

**Other**  
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)

---

## 🌱 Right now

- 🚜 developing **AgriNav** further
- 🏋️ building **GymLoom**, a fitness PWA
- ☕ learning **Spring Boot**

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Maxoo005/Maxoo005/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Maxoo005/Maxoo005/output/github-contribution-grid-snake.svg">
  <img alt="contribution grid snake animation" src="https://raw.githubusercontent.com/Maxoo005/Maxoo005/output/github-contribution-grid-snake.svg">
</picture>
