# 🏷️ Collectible Store Web Platform

### Client: Ramón – Event Organizer and Collector

---

## 📑 Table of Contents
1. [Social Problematic](#-social-problematic)
2. [Vision](#-vision)
3. [Proposal Solution](#-proposal-solution)
   - [Phase 1: Core API and Repository Setup – Sprint 1](#-phase-1-core-api-and-repository-setup--sprint-1-october-24–27)
   - [Phase 2: Exception Handling and Frontend Templates – Sprint 2](#-phase-2-exception-handling-and-frontend-templates--sprint-2-october-28–30)
   - [Phase 3: Real-Time Features and Final Testing – Sprint 3](#-phase-3-real-time-features-and-final-testing--sprint-3-october-31–november-3)
4. [Benefits of the Solution / Expected Outcomes](#-benefits-of-the-solution--expected-outcomes)
5. [Sustainability](#-sustainability)
6. [Team Structure and Roles](#-team-structure-and-roles)
7. [Links](#-links)

---

## 🧩 Social Problematic
Amid post-pandemic uncertainty, many small business owners and collectors like Ramón lack digital tools to sell their items online efficiently. They face difficulties promoting, pricing, and managing sales without relying on large e-commerce intermediaries. This limits their growth and access to a wider audience.

---

## 🌍 Vision
To develop a lightweight, user-friendly, and high-performing web application using **Java Spark** that enables collectors to manage and sell items online.  
The platform will serve as a **digital marketplace focused on collectibles**, providing **dynamic pricing**, **real-time updates**, and a **seamless browsing experience**.

---

## 💡 Proposal Solution
The solution will be developed through three sprints, each with clear objectives, tasks, and deliverables.

---

### 🚀 Phase 1: Core API and Repository Setup – Sprint 1 (October 24–27)
#### Objectives
- Initialize the project using Java Spark with Maven configuration.
- Set up API endpoints to manage users and collectibles (CRUD).
- Define routes and request handling for the `/users` path.
- Configure dependencies (Spark, Logback, Gson).
- Establish a GitHub repository with proper documentation.
- Document key development decisions in a shared space for learning and traceability.

#### Expected Deliverables
- Java Spark project initialized with Maven.
- Functional REST API with user management routes.
- GitHub repository with organized file structure and README.md.
- Documentation of technical decisions and adjustments.

---

### 🧱 Phase 2: Exception Handling and Frontend Templates – Sprint 2 (October 28–30)
#### Objectives
- Implement a custom exception handling module for API robustness.
- Create views and Mustache templates to visualize site functionality.
- Develop a web form to manage item offers.
- Conduct peer reviews to detect integration or logic issues.
- Update the GitHub repository with Sprint 2 deliverables and relevant documentation.

#### Expected Deliverables
- Exception handling module implemented and tested.
- Functional frontend templates integrated with backend routes.
- Web form for creating or updating collectible offers.
- Peer review report with findings and improvements.
- Updated GitHub documentation.

---

### ⚡ Phase 3: Real-Time Features and Final Testing – Sprint 3 (October 31–November 3)
#### Objectives
- Implement item filtering by price, category, and availability.
- Develop the WebSocket logic for real-time price updates.
- Use a quality checklist to validate all functionalities.
- Conduct final testing to ensure system stability and performance.
- Prepare repository for final review and deployment.

#### Expected Deliverables
- Fully functional item filters integrated with the user interface.
- WebSocket module for real-time price modification.
- Completed quality assurance checklist.
- Final project repository with all source code and documentation.

---

## 🎯 Benefits of the Solution / Expected Outcomes
- 🧭 **Accessibility:** Provides collectors with a digital sales platform without needing large e-commerce intermediaries.  
- ⚙️ **Performance:** Java Spark ensures lightweight and fast backend response times.  
- 💬 **Real-time Interaction:** WebSocket integration allows instant price updates and dynamic user engagement.  
- 🧩 **Scalability:** Modular design supports easy feature extensions such as auctions or user profiles.  
- 💡 **Educational Impact:** Strengthens team members’ understanding of web development with Java Spark and API integration.

---

## 🌱 Sustainability
Amid post-pandemic uncertainty, many small business owners and collectors like Ramón lack digital tools to sell their items online efficiently. They face difficulties promoting, pricing, and managing sales without relying on large e-commerce intermediaries. This limits their growth and access to a wider audience.

---

## 👥 Team Structure and Roles
### 1. Data Manager
Ensures proper data structuring and management for users and items. Maintains database consistency and validation mechanisms. Supports backend operations by securing data handling during CRUD processes.

### 2. Backend Developer
Leads the design and implementation of all API endpoints using Java Spark. Configures dependencies, manages the WebSocket module, and ensures logic integration between backend and frontend.

### 3. QA Tester
Conducts manual and automated testing for each sprint deliverable. Ensures API stability, verifies real-time updates, and applies the final quality checklist before delivery.

---

## 🔗 Links
- **Backlog:** [View Project Backlog](https://github.com/users/RazFernandez/projects/10/views/3)  
- **Roadmap:** [View Roadmap](https://github.com/users/RazFernandez/projects/10/views/1)


# 🏷️ Challenge 6 — Collectibles Store Web Application  
**Java 17 | Spark Framework | Mustache Templates | WebSockets | REST API | Scrum Methodology**

---

## 🧾 Cover Page

**Institution:** Bécalos TechnoReady In-México Bootcamp  
**Module:** Backend Development with Java Spark  
**Project:** Challenge 6 — Collectibles Store Web Application  
**Students:** *Miguel Raziel Jesús Fernández Noroña* & *Iván Kaleb Ramírez Torres*  
**Mentor:** *Eli*  
**Date:** *October – November 2025*  

---

## 📘 Executive Summary

The *Collectibles Store Web Application* represents both a **technological solution** and an **academic artifact**. Developed for the *TechnoReady In-México Bootcamp*, it synthesizes concepts from software engineering, agile methodologies, and socio-economic sustainability.  

The project delivers a **REST-driven web platform** built on **Java 17 + Spark**, using **Mustache templates** for server-side rendering and **WebSockets** for real-time event updates. Its primary aim is to empower small-scale collectors like **Ramón**, enabling them to digitize their trading activities without relying on commercial marketplaces.  

This document—structured as a comprehensive technical-academic report—provides detailed coverage of context, design rationale, methodology, and sprint-based implementation. It is intended to serve as a **public reference and evaluation artifact** demonstrating professional software practice aligned with sustainability and educational outcomes.  

---

## 🧩 1. Social Problematic

In post-pandemic economies, cultural entrepreneurs, artisans, and collectors suffered a sharp reduction in public exposure. Many lacked the infrastructure to maintain sales channels while physical events and fairs were suspended.  

Large e-commerce platforms such as Amazon or eBay offer visibility but impose **high commissions and complex listing procedures**, often incompatible with local markets. Furthermore, these systems prioritize product quantity over cultural value, marginalizing collectibles that depend on historical narrative and authenticity.  

The *Collectibles Store Web Application* arises from this problem: it provides an **independent, open-source alternative** through which local collectors can manage inventories, broadcast offers, and interact with buyers directly.  

---

## 🌍 2. Vision and Purpose

### 2.1 Vision Statement
> *“A marketplace where nostalgia meets innovation.”*

The vision extends beyond technology: it aspires to **democratize access to digital commerce** for specialized cultural goods. The long-term objective is to evolve into a **community ecosystem** connecting collectors, appraisers, and event organizers.  

### 2.2 Strategic Purpose
1. **Empowerment:** Reduce dependency on centralized platforms.  
2. **Accessibility:** Provide intuitive interfaces suitable for non-technical users.  
3. **Scalability:** Use modular Java architecture for future expansion.  
4. **Education:** Serve as a case study in backend design for bootcamp participants.  

---

## 👥 3. Stakeholders and Roles

| Stakeholder | Profile | Responsibilities |
|--------------|----------|------------------|
| **Rafael** | Junior Full-Stack Developer | Architecture design, coding, API implementation, and documentation. |
| **Ramón** | Collector & Entrepreneur | Domain expert; defines business rules, validates usability, and reviews deliverables. |
| **Sofía** | Mentor / Senior Engineer | Guides adherence to software quality standards, reviews pull requests, and ensures scalability. |

This triad mirrors **industry collaboration** between a developer, a client, and a technical lead, giving the project an authentic professional dimension.  

---

## 🎯 4. Business Goals

1. Deliver a **clean and maintainable** Java-based marketplace.  
2. Offer **CRUD operations**, **filtering**, and **real-time updates** through WebSockets.  
3. Ensure **transparency and reproducibility** using Postman + Newman automated testing.  
4. Promote **sustainability principles**—technical, economic, and environmental.  
5. Document each sprint to model **agile academic practice**.  

---

## 🧠 5. Theoretical and Technical Framework

### 5.1 Spark Java Framework
Spark is a minimalist web framework for Java inspired by Sinatra (Ruby). It provides concise syntax for routing and filters while remaining compatible with standard Java libraries. Its low overhead makes it ideal for **educational micro-projects**.  

**Core concepts implemented:**  
- `get()`, `post()`, `put()`, `delete()` routes  
- Request/response filters for JSON headers  
- Lightweight configuration through `App.java`  

### 5.2 Mustache Template Engine
A “logic-less” templating approach used for **server-side rendering (SSR)**. It separates presentation from logic, improving maintainability and SEO.  

### 5.3 WebSockets Protocol
WebSockets provide persistent, full-duplex channels over TCP. Within this project, they power **live price updates**—a fundamental feature for auction-like dynamics.  

### 5.4 Complementary Technologies
| Layer | Tool | Purpose |
|-------|------|----------|
| **Build** | Maven 3.9+ | Dependency management |
| **Testing** | Postman + Newman | Automated API validation |
| **IDE** | IntelliJ IDEA CE | Code authoring |
| **Version Control** | Git + GitHub | Collaboration / CI |
| **Runtime** | Java 17 JDK | Language runtime environment |

---

## 📚 6. Methodology — Scrum for Academic Projects

### 6.1 Rationale
Agile methodologies bridge theory and practice by enforcing iteration, feedback, and transparency. Using **Scrum**, this project aligns student workflow with industry expectations: planning, sprint review, and retrospective.  

### 6.2 Roles and Artifacts
| Scrum Role | Adaptation in Project |
|-------------|----------------------|
| **Product Owner** | *Ramón* (defines collector requirements) |
| **Scrum Master** | *Sofía* (facilitates workflow and removes blockers) |
| **Development Team** | *Rafael + Kaleb* (design, code, test, document) |

Artifacts include the **Product Backlog**, **Sprint Backlogs**, **Definition of Done**, and **Evidence Records** stored in GitHub.  

### 6.3 Sprint Overview

| Sprint | Dates | Objective | Key Deliverables |
|--------|--------|------------|------------------|
| **Sprint 1** | Oct 24 – 27 | Project initialization, API foundation | CRUD endpoints + Postman collection |
| **Sprint 2** | Oct 28 – 30 | Exception handling and Mustache UI | Error module + views + offer form |
| **Sprint 3** | Oct 31 – Nov 3 | Real-time filters and testing | WebSocket integration + QA report |

Each sprint followed the **Plan → Develop → Test → Review → Retrospect** cycle.  

### 6.4 Definition of Done (DoD)
A deliverable is “done” when:
- Code compiles + passes Postman tests.  
- Documentation is updated.  
- Peer review is approved.  
- Screenshots / evidence added.  

---

## 🧭 7. Educational Objectives

1. **Apply backend design patterns** using Spark Java.  
2. **Integrate REST APIs** with SSR and real-time protocols.  
3. **Manage version control** and collaborative workflows.  
4. **Demonstrate full-stack thinking** within constrained resources.  
5. **Communicate technically** through proper documentation and evidence.  

---

## ⚙️ 8. Project Planning and Tools Workflow

### 8.1 Repository Structure
```text
challenge6-collectibles-store/
├─ src/main/java/com/collectibles/
│  ├─ App.java
│  ├─ routes/
│  ├─ service/
│  ├─ repo/
│  ├─ domain/
│  ├─ ws/
│  └─ util/
├─ src/main/resources/
│  ├─ templates/
│  └─ static/
├─ postman/
│  ├─ CollectiblesAPI.postman_collection.json
│  └─ Local.postman_environment.json
└─ docs/
   ├─ screenshots/
   ├─ peer-reviews.md
   └─ architecture-diagram.png
```

### 8.2 Development Workflow
1. **Initialize Repository:** `mvn archetype:generate` + Git commit.  
2. **Configure Dependencies:** Spark, Mustache, Jackson, SLF4J.  
3. **Implement Endpoints:** CRUD for `/items` and `/users`.  
4. **Test via Postman** → Iterate.  
5. **Document Findings** in README and peer-review logs.  

### 8.3 Toolchain Integration
- **GitHub Projects:** Backlog tracking and sprint boards.  
- **GitHub Actions:** Maven build + Newman tests per pull request.  
- **PowerShell:** Execution scripts for local testing.  

---

## 📊 9. Risk Assessment — Planning Phase

| Risk | Probability | Impact | Mitigation |
|------|:-----------:|:------:|-------------|
| Late submission | Medium | High | Early milestone commits |
| Maven dependency conflict | Low | Medium | Pin versions in `pom.xml` |
| WS implementation delay | Medium | High | Prototype before Sprint 3 |
| Insufficient testing coverage | Medium | Medium | Enforce Postman/Newman run per merge |

---

## 🧮 10. Metrics for Success

| Metric | Measurement Method | Target Value |
|--------|--------------------|--------------|
| API availability | Manual + automated tests | ≥ 95 % successful responses |
| UI responsiveness | Lighthouse audit | ≥ 85 performance score |
| Code readability | Peer review feedback | ≥ 4/5 rating |
| Documentation completeness | Rubric compliance | 100 % criteria covered |

---

## 📈 11. Expected Learning Outcomes

By the end of Challenge 6, the student demonstrates proficiency in:
- Designing and deploying RESTful APIs.  
- Implementing WebSocket communication channels.  
- Managing agile project cycles and evidence documentation.  
- Applying sustainability principles to software lifecycle.  

---

*End of Part I – Context, Vision & Methodology*  
Next: **Part II – Architecture, Implementation & Testing (Sprints 1 – 3)**  


# 🧱 Part II — Architecture, Implementation & Testing (Sprints 1–3)

---

## 🧩 1. System Architecture

The *Collectibles Store Web Application* was designed following a **modular MVC‑inspired architecture**, promoting code readability, scalability, and separation of concerns. Each layer communicates through well‑defined interfaces, avoiding tight coupling between components.

### 1.1 Layered Architecture Overview

| Layer | Folder | Responsibilities |
|-------|---------|------------------|
| **Routes / Controllers** | `/routes` | Define REST endpoints, handle requests, and connect services. |
| **Service Layer** | `/service` | Encapsulates business logic and validation. |
| **Repository Layer** | `/repo` | Manages data storage (in‑memory during sprints). |
| **Domain Layer** | `/domain` | Defines entities (e.g., `Item`, `User`, `Offer`). |
| **WebSocket Layer** | `/ws` | Implements real‑time broadcast and event handling. |
| **Utilities** | `/util` | Helper functions for JSON serialization and formatting. |

---

### 1.2 Data Flow Diagram

```text
Client (Browser / Postman)
      │
      ▼
 Routes (Spark)
      │
      ▼
 Service Layer
      │
      ▼
 Repository (Map / DB)
```

Requests follow this pipeline:  
1. **Routes** receive HTTP requests.  
2. **Services** validate and process data.  
3. **Repositories** store or retrieve entities.  
4. **Responses** are serialized as JSON using Gson.  

---

### 1.3 Key Components

#### App.java
Entry point of the application, responsible for:  
- Setting port and environment variables.  
- Registering routes and filters.  
- Configuring CORS (for testing).  

```java
public class App {
    public static void main(String[] args) {
        port(Integer.parseInt(System.getenv().getOrDefault("PORT", "4567")));
        before((req, res) -> res.type("application/json"));
        new ItemsRoutes(new ItemService(new ItemRepository())).register();
    }
}
```

#### Json Utility
Centralized JSON handling for responses.  
```java
public class Json {
    private static final Gson gson = new GsonBuilder().setPrettyPrinting().create();
    public static String toJson(Object obj) { return gson.toJson(obj); }
}
```

---

## ⚙️ 2. Configuration Files

### 2.1 Maven Dependencies (`pom.xml`)
```xml
<dependencies>
  <dependency>
    <groupId>com.sparkjava</groupId>
    <artifactId>spark-core</artifactId>
    <version>2.9.4</version>
  </dependency>
  <dependency>
    <groupId>com.github.spullara.mustache.java</groupId>
    <artifactId>compiler</artifactId>
    <version>0.9.10</version>
  </dependency>
  <dependency>
    <groupId>com.google.code.gson</groupId>
    <artifactId>gson</artifactId>
    <version>2.10.1</version>
  </dependency>
  <dependency>
    <groupId>org.slf4j</groupId>
    <artifactId>slf4j-simple</artifactId>
    <version>2.0.12</version>
  </dependency>
</dependencies>
```

### 2.2 Logback Configuration
Logging is handled by SLF4J using a simple configuration that outputs request data, timestamps, and response times to the console.

```xml
<configuration>
  <appender name="STDOUT" class="ch.qos.logback.core.ConsoleAppender">
    <encoder>
      <pattern>%d{HH:mm:ss} %-5level %logger{36} - %msg%n</pattern>
    </encoder>
  </appender>
  <root level="info">
    <appender-ref ref="STDOUT" />
  </root>
</configuration>
```

---

## 🚀 3. Sprint 1 — Core API & Repository Setup

### 3.1 Objectives
- Initialize the project structure using Maven.  
- Create CRUD endpoints for `/users` and `/items`.  
- Implement `ItemRepository` and `UserRepository` using `ConcurrentHashMap`.  
- Test endpoints manually with Postman.  
- Document findings in README and peer review logs.  

### 3.2 Implementation Summary

| Component | Description |
|------------|--------------|
| **Item.java** | Domain class with attributes `id`, `name`, `category`, `price`, `onAuction`. |
| **ItemRepository.java** | Provides basic CRUD using `Map<UUID, Item>`. |
| **ItemService.java** | Validates and manages repository calls. |
| **ItemsRoutes.java** | Defines REST routes for `/api/v1/items`. |

### 3.3 Example Endpoint
```java
get("/api/v1/items", (req, res) -> {
    return Json.toJson(service.findAll());
});
```

### 3.4 Testing Procedure
1. Launch app → `java -jar target/spark-users-api.jar`.  
2. Test `GET /api/v1/items` (expect empty array).  
3. Create item via `POST /api/v1/items`.  
4. Retrieve by `GET /api/v1/items/:id`.  
5. Delete with `DELETE /api/v1/items/:id`.  

### 3.5 Evidence Screenshots
| No. | Screenshot | Description |
|-----|-------------|-------------|
| 1 | `01-init.png` | Project initialized with dependencies. |
| 2 | `02-crud.png` | CRUD operations passing Postman tests. |
| 3 | `03-logs.png` | Logback output showing request traces. |

### 3.6 Sprint Retrospective
- ✅ *Achievements:* Stable CRUD; modular packages defined.  
- ⚠️ *Challenges:* Initial CORS setup errors in PowerShell.  
- 💡 *Improvements:* Add centralized error handling before Sprint 2.  

---

## 🧱 4. Sprint 2 — Exception Handling & UI Templates

### 4.1 Objectives
- Add error handling middleware.  
- Create Mustache templates (`layout.mustache`, `index.mustache`, `itemDetails.mustache`).  
- Design form for offer submission.  
- Perform peer reviews for readability and consistency.  

### 4.2 Implementation Details
A global exception filter captures and transforms runtime errors into JSON payloads:

```java
exception(Exception.class, (ex, req, res) -> {
    res.status(500);
    res.type("application/json");
    res.body(Json.toJson(Map.of(
        "error", ex.getMessage(),
        "timestamp", Instant.now().toString()
    )));
});
```

**Template example (`index.mustache`):**
```html
<h1>Collectibles Store</h1>
<ul>
  {{#items}}
  <li>{{name}} — ${{price}}</li>
  {{/items}}
</ul>
```

### 4.3 Peer Review Notes
| Reviewer | Date | Comment | Status |
|-----------|------|----------|--------|
| Sofía | 2025‑10‑29 | Improve null‑check logic in repository. | ✅ Fixed |
| Rafael | 2025‑10‑29 | Add validation to offer form fields. | ✅ Done |

### 4.4 Evidence Screenshots
| No. | Screenshot | Description |
|-----|-------------|-------------|
| 1 | `04-ui.png` | Mustache layout rendering list of items. |
| 2 | `05-errors.png` | Friendly error message for missing route. |

### 4.5 Sprint Retrospective
- ✅ *Achievements:* SSR successfully implemented; templates rendered correctly.  
- ⚠️ *Challenges:* Time spent debugging template paths.  
- 💡 *Improvements:* Add WebSocket integration in Sprint 3.  

---

## ⚡ 5. Sprint 3 — Filters & WebSockets

### 5.1 Objectives
- Extend API filters for `category`, `minPrice`, `maxPrice`, `sort`.  
- Implement WebSocket server for broadcasting price changes.  
- Create client demo within Mustache template.  
- Validate real‑time functionality using browser console and test logs.  

### 5.2 Core Implementation

**WebSocket Class (`PriceWebSocket.java`):**
```java
@ServerEndpoint("/ws/prices")
public class PriceWebSocket {
    private static final Set<Session> sessions = ConcurrentHashMap.newKeySet();

    @OnOpen public void onOpen(Session s) { sessions.add(s); }
    @OnClose public void onClose(Session s) { sessions.remove(s); }
    @OnMessage public void onMessage(String msg, Session s) {
        sessions.forEach(sess -> sess.getAsyncRemote().sendText(msg));
    }
}
```

**Client-side integration:**
```html
<script>
  const ws = new WebSocket(`ws://${location.host}/ws/prices`);
  ws.onmessage = (e) => {
    const data = JSON.parse(e.data);
    document.querySelector(`#item-${data.itemId} .price`).textContent = data.newPrice;
  };
</script>
```

### 5.3 Evidence Screenshots
| No. | Screenshot | Description |
|-----|-------------|-------------|
| 1 | `06-ws-demo.png` | WebSocket server broadcasting price updates. |
| 2 | `07-tests.png` | Newman test suite confirming successful API responses. |

### 5.4 Sprint Retrospective
- ✅ *Achievements:* Real‑time updates functional and stable.  
- ⚠️ *Challenges:* Browser reconnection issues under load.  
- 💡 *Next steps:* Integrate persistence (DB) for long‑term item storage.  

---

## 🧪 6. Testing & Quality Assurance

### 6.1 Postman/Newman Automation
All endpoints were validated using Postman. Automated testing executed through **Newman CLI**:

```bash
newman run postman/CollectiblesAPI.postman_collection.json   -e postman/Local.postman_environment.json   --reporters cli --bail
```

### 6.2 Test Coverage Summary
| Test Case | Description | Expected | Result |
|------------|--------------|-----------|---------|
| Create Item | Valid JSON body | 201 | ✅ |
| Create Item (missing field) | Invalid body | 400 | ✅ |
| Get Item | Valid ID | 200 | ✅ |
| Get Item (non‑existent) | Invalid ID | 404 | ✅ |
| Delete Item | Valid ID | 204 | ✅ |
| Filter Items | Query params applied | 200 | ✅ |
| WebSocket | Price broadcast | Message received | ✅ |

### 6.3 Peer Review Checklist
- [x] Unit tests executed successfully.  
- [x] API responses match documentation.  
- [x] Logging active for every route.  
- [x] Documentation updated after testing.  

---

## 🧭 7. Sprint Integration Reflection

Across three sprints, iterative development allowed continuous improvement:  
- **Sprint 1** built the foundation (core API).  
- **Sprint 2** enhanced usability through SSR and exception management.  
- **Sprint 3** added interactivity and real‑time behavior.  

This incremental approach mirrors industry agile pipelines, emphasizing early validation and progressive refinement.  

---

*End of Part II – Architecture, Implementation & Testing (Sprints 1–3)*  
Next: **Part III – Sustainability, Innovation, Costs & Reflections**  

# 🌱 Part III — Sustainability, Innovation, Costs & Reflections

---

## 🌿 1. Sustainability Framework

Sustainability was considered throughout every sprint, aligning with the **United Nations Sustainable Development Goals (SDGs)** related to **industry innovation**, **responsible consumption**, and **economic growth**. The project aims to produce a digital solution that endures over time both technologically and operationally.

---

### 1.1 Technical Sustainability
Technical sustainability ensures that the codebase remains maintainable, adaptable, and secure over time.

| Aspect | Description | Contribution |
|---------|-------------|---------------|
| **Architecture** | Follows layered MVC structure separating routes, services, and repositories. | Facilitates scalability and unit testing. |
| **Dependencies** | Minimalistic selection (Spark, Mustache, Gson, SLF4J). | Reduces maintenance and version conflicts. |
| **Code Quality** | Peer-reviewed and linted through IDE inspections. | Prevents technical debt accumulation. |
| **Documentation** | README + peer review logs updated per sprint. | Guarantees knowledge transfer and traceability. |

> ⚙️ *Outcome:* The architecture can be extended to databases, authentication modules, or deployment pipelines without major refactoring.

---

### 1.2 Economic Sustainability
The project emphasizes **open-source technologies** and **cost-efficient practices** that allow small entrepreneurs to adopt it without licensing barriers.

| Resource | Strategy | Benefit |
|-----------|-----------|----------|
| **Open-source Stack** | Java, Maven, Spark, Mustache, Jetty. | No licensing fees; freely deployable. |
| **Continuous Integration** | GitHub Actions for build & test. | Prevents regression errors and reduces developer cost. |
| **Automation Tools** | Postman/Newman for API tests. | Saves hours of manual QA time. |
| **Documentation-first approach** | Self-contained README. | Reduces onboarding cost for new contributors. |

> 💰 *Economic impact:* By leveraging free tools, small businesses can replicate this system with almost zero recurring cost.

---

### 1.3 Operational Sustainability
Operational sustainability refers to efficiency in execution, deployment, and human collaboration.

- **Server-Side Rendering (SSR)** reduces client resource consumption, enabling access from low-end devices.  
- **Agile Workflows** promote adaptability through incremental updates.  
- **CI/CD Automation** streamlines integration and early error detection.  
- **Cross-Platform Testing** ensures compatibility with Windows PowerShell and Unix-based systems.  

> 🧭 *Outcome:* The operational design minimizes maintenance load and allows continuous improvements with small multidisciplinary teams.

---

### 1.4 Environmental Sustainability
While software systems have an indirect carbon footprint, optimization decisions can still reduce environmental impact.

| Practice | Impact |
|-----------|--------|
| Lightweight framework (Spark) | Less CPU demand → reduced energy consumption. |
| SSR instead of SPA | Fewer client requests → smaller network footprint. |
| Efficient query and logging strategies | Avoids unnecessary data processing. |
| Hosting flexibility | Deployable on renewable-energy data centers. |

> 🌎 *Environmental goal:* Optimize resource usage, particularly when deployed on low-cost or green infrastructure (e.g., Render, Fly.io).

---

## 🚀 2. Innovation and Business Impact

Innovation within the *Collectibles Store Web Application* lies in the combination of **real-time data communication**, **sustainable architecture**, and **educational integration**.

### 2.1 Real-Time Market Dynamics
- **WebSocket layer** allows live price adjustments and auction-style engagement.  
- **Instant user feedback** promotes transparency and enhances trust in online trading.  

### 2.2 Search and Discoverability
- Server-side rendering enhances SEO ranking.  
- Dynamic filters enable users to locate items by category, price, or rarity.  

### 2.3 Extensibility and Future Proofing
The design anticipates future modules:  
- Payment gateways (e.g., Stripe, PayPal).  
- Analytics dashboards for sellers.  
- AI-based recommendation systems for collectors.  
- Multilingual interfaces for international reach.  

### 2.4 Inclusivity and Accessibility
- UI built with WCAG-compliant templates for readability.  
- Minimalist color palette and semantic HTML structure improve accessibility.  
- Multi-device compatibility enables inclusion of mobile users.  

> 💡 *Conclusion:* The platform merges **technology**, **business value**, and **social inclusivity**, ensuring it benefits both developers and end-users.

---

## 💰 3. Cost Analysis

The project follows a transparent cost model simulating professional development scenarios.

| Task | Description | Hours | Rate (USD/hr) | Cost (USD) | Cost (MXN, ≈18.5 MXN/USD) |
|------|--------------|------:|--------------:|-----------:|--------------------------:|
| Requirements & Architecture | Domain modeling and system design | 6 | 45 | 270 | 4,995 |
| Backend Development | CRUD endpoints, WebSocket logic | 18 | 45 | 810 | 14,985 |
| UI & Templates | Mustache views, CSS styling | 14 | 45 | 630 | 11,655 |
| Testing & Documentation | Postman automation, README | 10 | 45 | 450 | 8,325 |
| Sustainability & Peer Review | Reports, review logs | 8 | 45 | 360 | 6,660 |
| **Total** |  | **56 h** |  | **2,520 USD** | **46,620 MXN** |

> 🧮 *Interpretation:* At standard market rates, this project would require ~56 hours of professional work, yielding a market value of ~2,500 USD.

---

## 🧯 4. Risk Management & Mitigation

| Risk | Probability | Impact | Mitigation Strategy |
|------|:-----------:|:------:|----------------------|
| WebSocket overload during auctions | High | High | Add throttling logic and session control. |
| Data loss (memory storage only) | Medium | High | Integrate persistence with PostgreSQL. |
| Security vulnerabilities | Medium | High | Validate all input; sanitize WebSocket messages. |
| Team coordination delays | Low | Medium | Daily stand-up and sprint review checkpoints. |
| Browser incompatibility | Low | Medium | Test across Chrome, Edge, Firefox, Safari. |

> 🧠 *Lesson learned:* Anticipating risks early simplified later sprint adaptation and reinforced agile discipline.

---

## 🎓 5. Academic Reflection & Learning Outcomes

### 5.1 Technical Learnings
- Gained fluency in Java 17 features (streams, records, lambdas).  
- Implemented Spark routes and WebSockets from scratch.  
- Learned exception handling and REST architecture patterns.  

### 5.2 Professional Competencies
- Strengthened collaboration and communication within an agile context.  
- Understood CI/CD pipelines using GitHub Actions.  
- Practiced formal documentation and evidence-based development.  

### 5.3 Sustainability and Ethics
- Applied sustainable computing principles.  
- Promoted inclusive design and equitable digital access.  

> 🧩 *Reflection:* The project cultivated a holistic engineering mindset—balancing efficiency, maintainability, and human-centered design.

---

## 🔮 6. Future Work and Deployment Plan

| Future Goal | Description | Expected Benefit |
|--------------|-------------|------------------|
| **Database Integration** | Add PostgreSQL / MongoDB persistence. | Long-term data retention and indexing. |
| **Authentication** | JWT or OAuth2-based login. | Security and personalization. |
| **Dockerization** | Containerize application. | Easier deployment to cloud. |
| **Continuous Deployment** | Connect to Render or Railway. | Automated updates post-merge. |
| **Analytics Module** | Add item view and sales metrics. | Business insights for Ramón and other collectors. |

> ⚙️ *Final Step:* Deploy production-ready version via Docker and CI/CD pipeline before integrating analytics.

---

## 📚 7. References

1. Spark Framework Documentation — https://sparkjava.com  
2. Mustache.java Official Repository — https://github.com/spullara/mustache.java  
3. RFC 6455: The WebSocket Protocol — https://www.rfc-editor.org/rfc/rfc6455  
4. Newman CLI Reference — https://learning.postman.com/docs/  
5. GitHub Actions Workflow Syntax — https://docs.github.com/en/actions  

---

## 🗂️ 8. Annex: Evidence Structure

```text
docs/
├─ screenshots/
│  ├─ 01-init.png
│  ├─ 02-crud.png
│  ├─ 04-ui.png
│  ├─ 06-ws-demo.png
│  └─ 07-tests.png
├─ videos/
│  └─ ws-demo.mp4
├─ peer-reviews.md
├─ quality-checklist.md
└─ architecture-diagram.png
```

---

## 👨‍💻 Author

**Iván Kaleb Ramírez Torres**  
PhD in Materials Science & Engineering | Full‑Stack & Frontend Developer  

- GitHub: [@rtkaleb](https://github.com/rtkaleb)  
- LinkedIn: [Iván Kaleb Ramírez Torres](https://linkedin.com/in/ivan-kaleb-ramirez-torres)  


**Miguel Raziel Jesús Fernández Noroña**  
Computer Systems Engineering | Full‑Stack & Backend Developer
- GitHub: [@Razfernandez](https://github.com/RazFernandez)  
- LinkedIn: [Iván Kaleb Ramírez Torres](https://linkedin.com/in/mrjfernandez)  

> *“Sustainable software is not only about writing clean code—it’s about designing systems that remain ethical, inclusive, and relevant in time.”*

---

*End of Part III — Sustainability, Innovation, Costs & Reflections*
