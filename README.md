# 📂 FGSSR Academic Study Platform - Documentation Portal

Welcome to the official artifact and engineering documentation repository for the **FGSSR Academic Study Platform**. This portal contains the exhaustive software engineering blueprints, system analysis models, and architectural designs constructed for the graduation project.

---

## 📌 Table of Contents
- [📄 Project Books](#-project-books)
- [🏗️ Architectural Diagrams (C4 Model)](#️-architectural-diagrams-c4-model)
- [🗄️ Database Modeling & Schema Design](#️-database-modeling--schema-design)
- [🔄 Data Flow Diagrams (DFD)](#-data-flow-diagrams-dfd)
- [🎭 Unified Modeling Language (UML) Specs](#-unified-modeling-language-uml-specs)
  - [Use Case Diagrams](#use-case-diagrams)
  - [Activity Diagrams](#activity-diagrams)
  - [Sequence Diagrams](#sequence-diagrams)
  - [State Diagrams](#state-diagrams)
- [🧩 High-Level Components](#-high-level-components)

---

## 📄 Project Books

Complete textual reports detailing requirements elicitation, literature review, and system specifications:
* [Project Documentation PDF](book/Web%20Application%20FGSSR%20%20Academic%20Study%20Platform%20_%202026.pdf) - Comprehensive Engineering Report (June 2026).
* [Project Book PDF](book/Web%20Application%20FGSSR%20%20Academic%20Study%20Platform.pdf) - Core Thesis Specification Document.

---

## 🏗️ Architectural Diagrams (C4 Model)

Abstracted mapping of the ecosystem structure across multiple layers of granularity:
* [C4 - Context Layer](C4/C4%20-%20CONTEXT.drawio.html) - System boundaries and external user/actor flows.
* [C4 - Container Layer](C4/C4%20-%20CONTINER%20.drawio.html) - Tech stack distributions, server layers, and data stores.
* [C4 - Component Layer](C4/C4-COMPONANT.drawio.html) - Internal application structural components within the Laravel containers.

---

## 🗄️ Database Modeling & Schema Design

Relational modeling blueprints optimized for high data integrity and normalization constraints:
* [Entity-Relationship Diagram (ERD)](ERD/FGSSR%20ERD.drawio.html) - General conceptual schema mapping.
* [Extended Entity-Relationship (EERD)](EERD/FGSSR%20EERD.drawio.html) - Enhanced schema featuring specialization, inheritance, and strict constraints.
* [Relational Mapping](MAPPING/mapping%20(3).html) - Formal mapping structure translating EERD components directly into physical MySQL database tables.

---

## 🔄 Data Flow Diagrams (DFD)

Functional decomposition illustrating data tracking pipelines across the application layers:
* [Context Diagram (Level 0 DFD)](DFD/FGSSR%20DFD%20L0.drawio.html) - Global system boundary data exchange.
* [Level 1 DFD](DFD/FGSSR%20DFD%20L1.drawio.html) - Detailed breakdown of main functional processes.
* [Level 2 DFD](DFD/FGSSR%20DFD%20L2.drawio.html) - Precise processing and sub-process data tracking points.

---

## 🎭 Unified Modeling Language (UML) Specs

### Use Case Diagrams
Functional system boundaries mapped against multi-tier actors:
* [Authentication Management](USE%20CASE/FGSSR%20Use%20Case%20Auth.drawio.html)
* [User Dashboard & Profile Management](USE%20CASE/FGSSR%20Use%20Case%20User%20Dashboard%20and%20Profile%20Management.drawio.html)
* [Administrative User Management](USE%20CASE/FGSSR%20UseCase%20Manage%20Users.drawio.html)
* [Academic Program Management](USE%20CASE/FGSSR%20Use%20Cse%20Academic%20Program%20Management.drawio.html)
* [Real-Time Chat Subsystem](USE%20CASE/Use%20case%20chat%20Diagram.drawio.html)
* [Exam Scheduling Architecture](USE%20CASE/use%20case%20exam%20schedule%20Diagram.drawio.html)
* [Study Table Subsystem](USE%20CASE/use%20case%20study%20table%20Diagram.drawio.html)
* [File & Asset Management System](USE%20CASE/fileUseCase.png)
* [Place & Campus Venue Management](USE%20CASE/placeUseCase.png)
* [Smart Notification System](USE%20CASE/notificationUseCase.png)
* [Dynamic Query Search System](USE%20CASE/searchUseCase.png)
* [Materials Schedule Subsystem](USE%20CASE/Use%20case%20mater%20Diagram.drawio.html)

### Activity Diagrams
Operational step-by-step logic and procedural control workflows:
* [Login & Identity Verification Loop](ACTIVITY/FGSSR%20ACTIVITY%20ATH%20.drawio.html)
* [Manage System Users Workflow](ACTIVITY/FGSSR%20activity%20%20Manage%20Users.drawio.html)
* [Dashboard & Profile Updates Processing](ACTIVITY/FGSSR%20activityUser%20Dashboard%20and%20Profile%20Management.drawio.html)
* [Courses Architecture Control](ACTIVITY/Courses.png)
* [Diploma Setup & Course Mapping](ACTIVITY/Courses_Diplomas.png)
* [Diplomas Lifecycle Control](ACTIVITY/Diplomas.png)
* [File System & File Operations Processing](ACTIVITY/fileActivityDiagram.png)
* [Smart Notification Dispatch Cycle](ACTIVITY/notificationActivityDiagram.drawio.png)
* [Campus Venue/Place Management Loop](ACTIVITY/placeActivityDiagram.png)
* [Dynamic Engine Data Search](ACTIVITY/searchActivityDiagram.drawio.png)
* [Real-Time Messaging Exchange Pipeline](ACTIVITY/activity%20chat%20Diagram.drawio.html)
* [Exam Timetable Scheduling Cycle](ACTIVITY/activity%20exam%20Diagram.drawio.html)
* [Materials Academic Timetable Flow](ACTIVITY/activity%20material%20Diagram.drawio.html)
* [Study Table Matrix Control](ACTIVITY/activity%20study%20table%20Diagram.drawio.html)

### Sequence Diagrams
Object-oriented chronological interactions across the MVC layer:
* [User Registration Operations](SQU/fgssr%20register%20.drawio.html)
* [Admin Actions: Manage Users Hierarchy](SQU/fgssr%20register%20.drawio.html)
* [Secure Session Authentication & Profile Pulling](SQU/FGSSR%20SQU%20%20mang%20profile%20and%20auth%20login.drawio.html)
* [Dashboard/Profile Mutex State Updates](SQU/FGSSR%20SQU%20User%20Dashboard%20and%20Profile%20Management.drawio.html)
* [Assigning Course Elements to Diplomas](SQU/FSSR%20Sequence%20Diagram%20Add%20course%20to%20diploma.png)
* [New Course Element Initialization](SQU/FSSR%20Sequence%20Diagram%20
