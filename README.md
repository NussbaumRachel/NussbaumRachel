# Hi, I'm Rachel Nussbaum 

**Verification & Software Engineer** — SystemVerilog/UVM · C++ · Full-Stack · DevOps

I work on both sides of the hardware/software line: I build **UVM verification environments** that prove a design does exactly what the spec says, and I build software end to end, from real-time multiplayer servers in modern C++ to production-style web apps and the CI/Docker pipelines around them. In both, I care about layered architecture, reusable components, and checks that catch bugs automatically.

<!-- Add your links here, e.g.:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR-HANDLE)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:YOUR-EMAIL)
-->

---

## 🚀 Featured Projects

### 🔬 [UVM Verification Environment — YAPP Router](https://github.com/NussbaumRachel/uvm-yapp-router-verification) (SystemVerilog / UVM)
A complete, layered UVM 1.1d testbench for a 3-channel packet router, run on Cadence Xcelium.
- **100% functional coverage** · 64 packets checked by the scoreboard · **0 mismatches / 0 UVM_ERROR**
- YAPP interface UVC built from scratch: constrained-random packets, driver, monitor with **TLM analysis port** and covergroup
- **Reference model + scoreboard** that mirrors the router's registers and predicts dropped packets (illegal address, oversized, router disabled)
- Two checker styles: push model (`uvm_analysis_imp_decl`) and pull model (`uvm_tlm_analysis_fifo`)
- **Virtual sequencer** coordinating the YAPP and HBUS interfaces; coverage closure with directed boundary values and cross coverage
- `SystemVerilog` `UVM 1.1d` `Cadence Xcelium` `SimVision` `Functional Coverage` `Constrained Random`

### ♟️ [Kung Fu Chess](https://github.com/NussbaumRachel/Kung-Fu-Chess) — Real-time multiplayer game server (C++17)
Chess without turns: every player moves in real time, with per-piece cooldowns.
- **Authoritative server** with isolated game rooms and asynchronous **WebSocket** networking
- Layered design: Model → Movement → Rule Engine → Arbiter → Game Engine → Controller
- **PostgreSQL** persistence, **Redis** sessions, **Docker Compose** deployment, OpenCV graphical client
- `C++17` `CMake` `WebSockets` `PostgreSQL` `Redis` `Docker` `OpenCV`

### 🚪 Metzada Doors — Factory Management System (Full-Stack)
A management system for a door manufacturing plant: orders, customers, employees, inventory and production tasks.
**[Frontend (React)](https://github.com/metzada-doors/MetzadaReact) · [Backend (ASP.NET Core)](https://github.com/metzada-doors/DoorsProjectInServer)**
- **Automatic CNC program generation** — a Rule Engine turns each door's specification into a ready-to-run `.mpf` machine program
- Layered .NET 8 API (API → Business Logic → Data Access) with **EF Core**, **SQL Server** and **JWT** authentication
- Role-based dashboards (manager, measurer) with protected routes
- Order builder with door configuration, Excel export and charts
- Hebrew-calendar scheduling, form validation with **Zod** + **React Hook Form**
- `React 19` `Redux Toolkit` `C#` `.NET 8` `EF Core` `SQL Server` `JWT`

### 🎁 [Chinese Auction Manager](https://github.com/NussbaumRachel/blank-app) (Angular)
A web app for running a charity Chinese auction — managing gifts, donors, customers, and ticket purchasing.
- Component-based architecture with typed models and routing
- UI built with **PrimeNG** and **Bootstrap**
- `Angular 20` `TypeScript` `RxJS` `PrimeNG` `SCSS`

---

## 🛠️ Tech Stack

**Hardware Verification:**
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-1F6FEB?style=flat)
![UVM](https://img.shields.io/badge/UVM_1.1d-0E7C86?style=flat)
![Cadence Xcelium](https://img.shields.io/badge/Cadence_Xcelium-B31B1B?style=flat)
![Functional Coverage](https://img.shields.io/badge/Functional_Coverage-555555?style=flat)

**Languages:**
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat&logo=dotnet&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Frontend:**
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat&logo=redux&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)

**Backend & Data:**
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**DevOps & Tools:**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white)
