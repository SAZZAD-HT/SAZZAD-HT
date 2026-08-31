<!--
  ============================================================
  SAZZAD HOSSAIN TASNIM — GitHub Profile README
  Repo: github.com/SAZZAD-HT/SAZZAD-HT
  ------------------------------------------------------------
  WHAT THIS FILE DOES AND DOES NOT DO FOR SEARCH:

  DOES:
  - The text below sits in the HTML of github.com/SAZZAD-HT and
    is crawlable. Name, employers, titles and technologies all
    appear as real prose, not only inside badge images.
  - github.com has high domain authority, so this page should
    rank for searches on the exact name.

  DOES NOT:
  - It does NOT control the page title or meta description.
    Google reads the GitHub BIO FIELD as the meta description,
    not this README. The bio is the highest-leverage 160
    characters available — edit it in profile settings.
  - Links here are rendered rel="nofollow" by GitHub, so they
    pass no ranking credit to LinkedIn / Scholar / X.
  - The Mermaid diagram renders client-side. It is excellent
    for human readers and worth roughly nothing for search.
  - Badge alt text is good accessibility practice and near-zero
    ranking value. Do not add badges for SEO reasons.

  For real SEO control (title, meta description, Person JSON-LD
  with sameAs, canonical, sitemap), publish a GitHub Pages site
  and link it from the profile.
  ------------------------------------------------------------
  BEFORE YOU PUBLISH:
  Delete any badge for a tool you have not actually used, and
  move it to "Currently Expanding Into" if you are learning it.
  A stack you cannot defend in an interview costs more than the
  keywords earn, and search engines discount stuffed pages.
  ============================================================
-->

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=25&duration=3200&pause=900&center=true&vCenter=true&width=860&height=70&lines=Hi%2C+I'm+Sazzad+Hossain+Tasnim;Software+Engineer+at+American+%26+Efird;AI-Driven+ERP+Modernization;.NET+%7C+Microservices+%7C+Clean+Architecture;MCP+%7C+LLM+Orchestration+%7C+RAG+%7C+Agents;Azure+%7C+Kubernetes+%7C+DevOps+%7C+LLMOps" alt="Sazzad Hossain Tasnim — Software Engineer specialising in AI-driven ERP modernization, .NET microservices, MCP, LLM orchestration, Azure and DevOps" />

# Sazzad Hossain Tasnim

### AI &amp; ERP Modernization Engineer · .NET · Microservices · MCP &amp; LLM Orchestration · Azure DevOps

<p>
<a href="https://github.com/SAZZAD-HT"><img src="https://komarev.com/ghpvc/?username=SAZZAD-HT&label=Profile%20views&color=0e75b6&style=flat-square" alt="Profile view counter for Sazzad Hossain Tasnim on GitHub" /></a>
<a href="https://github.com/SAZZAD-HT?tab=followers"><img src="https://img.shields.io/github/followers/SAZZAD-HT?label=Followers&style=flat-square&color=0e75b6&logo=github" alt="GitHub followers of Sazzad Hossain Tasnim" /></a>
<a href="https://www.linkedin.com/in/sazzadhossaintasnim/"><img src="https://img.shields.io/badge/LinkedIn-6.6k%20followers-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="Sazzad Hossain Tasnim on LinkedIn" /></a>
<a href="https://twitter.com/sazzadht0"><img src="https://img.shields.io/twitter/follow/sazzadht0?label=%40sazzadht0&style=flat-square&logo=x&color=0e75b6" alt="Follow Sazzad Hossain Tasnim on X, formerly Twitter" /></a>
<img src="https://img.shields.io/badge/Dhaka-Bangladesh-006a4e?style=flat-square&logo=googlemaps&logoColor=white" alt="Based in Dhaka, Bangladesh" />
</p>

</div>

---

## About Me

I'm **Sazzad Hossain Tasnim**, a **Software Engineer based in Dhaka, Bangladesh** with **3+ years**
of experience modernising enterprise systems for global manufacturing and FMCG organisations —
currently **Software Engineer L2 at American &amp; Efird**, previously at **British American Tobacco**,
**Ha-Meem Group** and **iBOS Limited**.

My specialty is **AI-driven ERP modernization**: taking the systems of record a business already
runs on — ERP, SAP, SQL Server, decades of scanned paperwork — and wrapping them in **retrieval,
agents and automation** without ripping them out. That means **C# and ASP.NET Core** services built
on **Clean Architecture and CQRS**, **microservices on Microsoft Azure**, **MCP servers and LLM
orchestration** over enterprise data, **PII tokenization** at the trust boundary, and the **DevOps
and LLMOps** plumbing that keeps it observable, affordable and safe in production.

- 🏢 **Software Engineer L2** at **[American &amp; Efird](https://www.amefird.com/)** — ERP automation, multilingual OCR, Azure microservices
- 🤖 Building **Model Context Protocol (MCP) servers** and agentic workflows over enterprise ERP data
- 🔐 Focused on **data tokenization, PII masking and RBAC** as the trust boundary between ERP and LLMs
- ⚙️ Shipping with **containers, CI/CD, infrastructure as code and LLM observability**
- 🎓 **BSc in Computer Science**, American International University-Bangladesh (AIUB)
- 💬 Ask me about **ERP modernization, CQRS, MCP, RAG, token cost control, Azure**
- 📫 Reach me at **[sazzadaiub1@gmail.com](mailto:sazzadaiub1@gmail.com)**

---

## What I Build — AI × ERP Modernization

Most enterprises don't need a new ERP. They need the one they have to become **queryable,
automatable and safe to expose to a language model**. This is the reference architecture I work in:

```mermaid
flowchart LR
    A["Systems of Record<br/>ERP · SAP · SQL Server<br/>Scanned Documents"]
    B["Integration Layer<br/>REST APIs · Service Bus<br/>Event-Driven Messaging"]
    C["Trust Boundary<br/>PII Tokenization · Masking<br/>RBAC · JWT · OAuth 2.0"]
    D["Retrieval Layer<br/>OCR · Chunking · Embeddings<br/>Vector + Hybrid Search"]
    E["Orchestration<br/>MCP Servers · Tool Calling<br/>Agents · RPA Workers"]
    F["Delivery<br/>Power BI · Power Apps<br/>Business Users"]
    P["Platform &amp; Ops<br/>Containers · Kubernetes · CI/CD · IaC<br/>Observability · Evals · Token Cost Controls"]

    A --> B --> C --> D --> E --> F
    P -.-> C
    P -.-> D
    P -.-> E
```

**How the layers break down**

| Layer | What it solves | What I use |
| :--- | :--- | :--- |
| **Systems of record** | Legacy ERP and paper processes that hold the real business data | SAP · SQL Server · ERP modules · Tesseract OCR |
| **Integration** | Decoupling AI features from the monolith so nothing gets rewritten | ASP.NET Core · REST · Service Bus · strangler-fig migration |
| **Tokenization &amp; trust** | Making enterprise data safe to send to a model | PII tokenization · masking · RBAC · JWT · OAuth 2.0 · Key Vault |
| **Retrieval** | Turning documents and tables into something a model can ground on | Chunking · embeddings · vector + hybrid search · reranking |
| **Orchestration** | Giving models real tools instead of guesswork | MCP servers · function/tool calling · structured outputs · agents |
| **Platform &amp; ops** | Keeping it cheap, observable and reproducible | Containers · Kubernetes · CI/CD · IaC · evals · token budgeting |

**Two kinds of tokenization, both of which matter here**

- **Data tokenization** — replacing PII and commercially sensitive fields with reversible tokens
  *before* anything reaches a model or a third-party API. This is what makes ERP data legally and
  contractually shippable to an LLM.
- **Token economics** — context-window budgeting, prompt and semantic caching, batching, and
  model routing so an automation that runs ten thousand times a day stays affordable. At A&amp;E,
  tuning batching and async processing cut latency by 30%.

---
## Professional Experience

<table>
<tr>
<td width="80" align="center" valign="top"><img src="https://www.google.com/s2/favicons?domain=amefird.com&sz=64" width="52" alt="American and Efird company logo" /></td>
<td valign="top">

#### Software Engineer L2 — American &amp; Efird

`Mar 2025 – Present` · Full-time · Dhaka, Bangladesh

Enterprise automation and AI engineering for a global sustainable-thread manufacturer operating in 22 countries.

- Designed and deployed **automation workflows integrated with a company-wide ERP system**, automating document handling and enterprise knowledge retrieval — **cutting manual processing time by 40%**
- Built a **multilingual OCR automation pipeline** (English, Mandarin, Indonesian, Sinhala) with **Tesseract** to auto-extract data from scanned documents, eliminating a manual data-entry step
- Connected automation workflows to enterprise systems via **REST APIs and a microservices architecture on Microsoft Azure**
- Tuned **batching and async processing** in production, **reducing processing latency by 30%**
- Implemented **role-based access control (JWT, OAuth 2.0)** to secure automated data retrieval
- Built **Python / Pandas** data-preparation pipelines for validation and cleaning
- Maintained backend services in **C# / ASP.NET Core using Clean Architecture and CQRS**

</td>
</tr>

<tr>
<td width="80" align="center" valign="top"><img src="https://www.google.com/s2/favicons?domain=bat.com&sz=64" width="52" alt="British American Tobacco company logo" /></td>
<td valign="top">

#### Associate Software Engineer — British American Tobacco (BAT)

`Aug 2024 – Mar 2025` · Full-time · Dhaka, Bangladesh · On-site

IDT Department — Bangladesh Automation Team.

- Built and maintained custom software using **ASP.NET Core, Power BI, SAP, SQL and Power Apps** to meet automation and efficiency goals
- **Led end-to-end automation projects** as primary developer, from requirements gathering through deployment
- Designed **Power BI dashboards** for real-time insight and **Power Apps workflows** to streamline processes
- Collaborated across international teams spanning the **US, UK, Brazil, Mexico and Sri Lanka**, working under a BAT Senior Manager

</td>
</tr>

<tr>
<td width="80" align="center" valign="top"><img src="https://www.google.com/s2/favicons?domain=hameemgroup.net&sz=64" width="52" alt="Ha-Meem Group company logo" /></td>
<td valign="top">

#### Assistant Software Engineer — Ha-Meem Group

`Oct 2023 – Sep 2024` · Full-time · Bangladesh · On-site

Manufacturing systems for one of Bangladesh's largest apparel exporters (75,000+ employees).

- Developed a **Production Tracking System** and an **Employee Efficiency Tracker**
- Modernised and improved the **legacy production module in the ERP**
- Wrote **efficient stored procedures in SQL Server**
- Built a **Challan and Approval System**
- Implemented a **custom security key** using multiple cryptographic algorithms
- Stood up an **IdentityServer** for authentication across microservices
- Built **.NET WinForms desktop applications** for factory floors
- Developed a **barcode scanning and tagging system** with .NET and React
- Created a **line-efficiency dashboard** with Node.js and React, plus a React tender-management module

</td>
</tr>

<tr>
<td width="80" align="center" valign="top"><img src="https://www.google.com/s2/favicons?domain=ibos.io&sz=64" width="52" alt="iBOS Limited company logo" /></td>
<td valign="top">

#### Back End Software Engineer (Intern) — iBOS Limited

`Jul 2023 – Oct 2023` · Internship · Dhaka, Bangladesh · On-site

SaaS ERP and HR products.

- Built **REST APIs with ASP.NET Core Web API**
- Developed a new **ERP module** and fully implemented a **Performance Management System for PeopleDesk** (HR SaaS application)
- Worked with **microservice architecture** and **Microsoft Azure**
- Diagnosed and fixed defects in the ERP, collaborating closely with frontend developers

</td>
</tr>

<tr>
<td width="80" align="center" valign="top"><img src="https://img.shields.io/badge/%F0%9F%92%BC-Freelance-1F6FEB?style=flat-square" alt="Freelance work" /></td>
<td valign="top">

#### Full-Stack Developer — Freelance

`Dec 2021 – Sep 2023` · Remote · Fiverr &amp; direct clients

- Developed **e-commerce sites and POS applications** using ASP.NET, React and WinForms
- Built an **inventory management system currently used by 40+ retail shops** in Jamuna Future Park and Bashundhara City

</td>
</tr>
</table>

---

## Education

<table>
<tr>
<td width="80" align="center" valign="top"><img src="https://www.google.com/s2/favicons?domain=aiub.edu&sz=64" width="52" alt="American International University-Bangladesh AIUB logo" /></td>
<td valign="top">

#### BSc in Computer Science — American International University-Bangladesh (AIUB)

`Jan 2020 – Dec 2023` · Dhaka, Bangladesh

Coursework and project work across **data structures and algorithms, object-oriented programming
(C++, C#), database systems, software engineering, web technologies and AngularJS**. Research
output indexed on **[Google Scholar](https://scholar.google.com/citations?user=LKWJIjAAAAAJ&hl=en)**.

</td>
</tr>

<tr>
<td width="80" align="center" valign="top"><img src="https://img.shields.io/badge/%F0%9F%8E%93-HSC-006a4e?style=flat-square" alt="Higher Secondary Certificate" /></td>
<td valign="top">

#### Higher Secondary Certificate, Science — Dr. Mahbubur Rahman Molla College (DMRC)

`2017 – 2019` · Dhaka, Bangladesh

Rover Scout **Rover Mate (group leader)** — led volunteer teams for the *Porichchhonno Dhaka*
(Clean Dhaka) world-record event, the 26th March Independence Day parade, and the Safe Road and
footbridge-awareness campaigns.

</td>
</tr>
</table>

---

## Certifications

| Certification | Issuer | Issued |
| :--- | :--- | :--- |
| **Python Data Associate** — Credential ID `PDA0018806742624` | DataCamp | Oct 2025 |
| **Claude Code in Action** — practical AI coding workflows | Anthropic Education | 2026 |
| **Technical Support Fundamentals** | Coursera / Google | Mar 2023 |

---

## Hackathons &amp; Competitions

- 🧩 **BUET CSE Fest 2022 — Hackathon**, Bangladesh University of Engineering &amp; Technology — competed with **Team CARBONITE** on **Web3 and blockchain**
- 📱 **BDApps National Hackathon 2022**, United International University campus — 10 September 2022
- 🏅 **ICT Olympiad Bangladesh** — participant
- 💡 **Dhaka University Entrepreneurship Development Club** startup competition

---

## Featured Projects

| Project | What it does | Stack |
| :--- | :--- | :--- |
| **[RepositoryPatternAsp.netCoreAPi](https://github.com/SAZZAD-HT/RepositoryPatternAsp.netCoreAPi)** | A fast, reliable REST API template using the repository pattern in a microservice architecture. | ASP.NET Core 8 · C# · EF Core |
| **[IdentityServer-Dundee-ASP.NET-core](https://github.com/SAZZAD-HT/IdentityServer-Dundee-ASP.NET-core)** | Authentication and authorization server for securing ASP.NET Core API configurations. | IdentityServer · ASP.NET Core · C# |
| **[TrifoTMS — Transport Management System](https://github.com/SAZZAD-HT/TrifoTMS-ASP-.NET-Project-Academic-)** | Entity Framework based transport management system for fleet and route operations. | ASP.NET · Entity Framework · C# |
| **[MOSJD-SOLLUTION](https://github.com/SAZZAD-HT/MOSJD-SOLLUTION)** | Business solution platform built on a NestJS backend with a vanilla JavaScript frontend. | NestJS · JavaScript · Node.js |
| **[StudyAbroad](https://github.com/SAZZAD-HT/StudyAbroad)** | Study-abroad consultancy web application with server-side rendering. | Next.js · React · JavaScript |
| **[BUET Hackathon 2023](https://github.com/SAZZAD-HT/BUET-HACKATHON-2023)** | Blockchain smart-contract project built for the BUET Hackathon. | Solidity · JavaScript · Web3 |

➡️ **[See all 85+ repositories →](https://github.com/SAZZAD-HT?tab=repositories)**

---

## Tech Stack

> Grouped by what I ship with day to day, then what I'm actively expanding into.

### Core — Languages

![C# programming language](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![TypeScript programming language](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript programming language](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python programming language](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C plus plus programming language](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Transact SQL database language](https://img.shields.io/badge/T--SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Solidity smart contract language](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)

### Core — Backend &amp; Architecture

![.NET 8 platform](https://img.shields.io/badge/.NET%208-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core web framework](https://img.shields.io/badge/ASP.NET%20Core-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white)
![Entity Framework Core ORM](https://img.shields.io/badge/EF%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Clean Architecture pattern](https://img.shields.io/badge/Clean%20Architecture-2E7D32?style=for-the-badge)
![CQRS pattern](https://img.shields.io/badge/CQRS-2E7D32?style=for-the-badge)
![Domain Driven Design](https://img.shields.io/badge/DDD-2E7D32?style=for-the-badge)
![Microservices architecture](https://img.shields.io/badge/Microservices-1F6FEB?style=for-the-badge)
![Event driven architecture](https://img.shields.io/badge/Event--Driven-1F6FEB?style=for-the-badge)
![NestJS Node.js framework](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Node.js JavaScript runtime](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

### AI Engineering &amp; LLM Ops

![Model Context Protocol](https://img.shields.io/badge/MCP%20Servers-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Large Language Models](https://img.shields.io/badge/LLM%20Integration-FF6F00?style=for-the-badge&logo=openai&logoColor=white)
![Retrieval Augmented Generation](https://img.shields.io/badge/RAG-FF6F00?style=for-the-badge)
![AI agents and agentic workflows](https://img.shields.io/badge/Agentic%20Workflows-FF6F00?style=for-the-badge)
![Tool calling and structured outputs](https://img.shields.io/badge/Tool%20Calling%20%2F%20Structured%20Output-6A1B9A?style=for-the-badge)
![Context engineering](https://img.shields.io/badge/Context%20Engineering-6A1B9A?style=for-the-badge)
![Azure OpenAI Service](https://img.shields.io/badge/Azure%20OpenAI-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Microsoft Semantic Kernel](https://img.shields.io/badge/Semantic%20Kernel-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Robotic Process Automation](https://img.shields.io/badge/RPA-1F6FEB?style=for-the-badge&logo=uipath&logoColor=white)
![Tesseract optical character recognition](https://img.shields.io/badge/Tesseract%20OCR-4E9A06?style=for-the-badge)
![LLM evaluation and observability](https://img.shields.io/badge/Evals%20%26%20LLM%20Observability-455A64?style=for-the-badge)
![Prompt and semantic caching](https://img.shields.io/badge/Prompt%20%2F%20Semantic%20Caching-455A64?style=for-the-badge)
![Token cost optimisation](https://img.shields.io/badge/Token%20Cost%20Optimisation-455A64?style=for-the-badge)

### Security, Tokenization &amp; Governance

![PII tokenization and masking](https://img.shields.io/badge/PII%20Tokenization%20%26%20Masking-B71C1C?style=for-the-badge)
![Role based access control](https://img.shields.io/badge/RBAC-B71C1C?style=for-the-badge)
![JWT and OAuth 2.0 authentication](https://img.shields.io/badge/JWT%20%2F%20OAuth%202.0-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![IdentityServer authentication](https://img.shields.io/badge/IdentityServer-5C2D91?style=for-the-badge)
![Azure Key Vault secrets management](https://img.shields.io/badge/Azure%20Key%20Vault-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Applied cryptography](https://img.shields.io/badge/Applied%20Cryptography-B71C1C?style=for-the-badge)
![Prompt injection and guardrails](https://img.shields.io/badge/Guardrails%20%26%20Prompt%20Injection%20Defence-B71C1C?style=for-the-badge)

### Cloud, Hosting &amp; DevOps

![Microsoft Azure cloud platform](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker containerisation](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes container orchestration](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions continuous integration](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Azure DevOps pipelines](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white)
![Infrastructure as code with Terraform and Bicep](https://img.shields.io/badge/IaC%20%C2%B7%20Terraform%20%2F%20Bicep-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![NGINX reverse proxy](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white)
![YARP and Ocelot API gateway](https://img.shields.io/badge/API%20Gateway%20%C2%B7%20YARP%20%2F%20Ocelot-5C2D91?style=for-the-badge)
![Redis caching](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![RabbitMQ message broker](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![OpenTelemetry observability](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)
![Linux operating system](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git version control](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Data, BI &amp; Frontend

![Microsoft SQL Server database](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL and pgvector](https://img.shields.io/badge/PostgreSQL%20%2F%20pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Microsoft Power BI business intelligence](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Microsoft Power Apps](https://img.shields.io/badge/Power%20Apps-742774?style=for-the-badge&logo=powerapps&logoColor=white)
![SAP enterprise software](https://img.shields.io/badge/SAP-0FAAFF?style=for-the-badge&logo=sap&logoColor=white)
![Pandas data analysis library](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![React JavaScript library](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js React framework](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![AngularJS framework](https://img.shields.io/badge/AngularJS-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![.NET WinForms desktop framework](https://img.shields.io/badge/WinForms-512BD4?style=for-the-badge&logo=windows&logoColor=white)

### Currently Expanding Into

Being explicit about the difference between what I ship and what I'm still learning — the second
list is where my study time goes right now.

![Vector databases Qdrant and Azure AI Search](https://img.shields.io/badge/Vector%20DBs%20%C2%B7%20Qdrant%20%2F%20Azure%20AI%20Search-2E4053?style=flat-square)
![Multi agent orchestration](https://img.shields.io/badge/Multi--Agent%20Orchestration-2E4053?style=flat-square)
![Self hosted LLM inference with vLLM and Ollama](https://img.shields.io/badge/Self--Hosted%20Inference%20%C2%B7%20vLLM%20%2F%20Ollama-2E4053?style=flat-square)
![Fine tuning and LoRA](https://img.shields.io/badge/Fine--Tuning%20%2F%20LoRA-2E4053?style=flat-square)
![Apache Kafka event streaming](https://img.shields.io/badge/Apache%20Kafka-2E4053?style=flat-square)
![Distributed systems design](https://img.shields.io/badge/Distributed%20Systems-2E4053?style=flat-square)
![FinOps and cloud cost engineering](https://img.shields.io/badge/FinOps%20%2F%20Cost%20Engineering-2E4053?style=flat-square)

---

## GitHub Statistics

<!--
  ============================================================
  IF THESE CARDS SHOW "Maximum retries exceeded":
  That is the shared public github-readme-stats instance hitting
  GitHub's API rate limit. It is not a problem with this README,
  and it usually clears within an hour.

  PERMANENT FIX — deploy your own instance (about 10 minutes):
    1. Fork https://github.com/anuraghazra/github-readme-stats
    2. GitHub → Settings → Developer settings → Personal access
       tokens → Tokens (classic) → Generate new token.
       No scopes needed for public data. Tick "repo" only if you
       want private commits counted.
    3. Sign in to vercel.com with GitHub → Add New Project →
       import your fork → Deploy.
    4. Vercel → Project → Settings → Environment Variables →
       add  PAT_1  =  your token  → redeploy.
    5. Find-and-replace "github-readme-stats.vercel.app" below
       with your own <project>.vercel.app domain.

  Once on your own instance you can also add back:
    &include_all_commits=true&count_private=true
  Those two were removed here because they need extra API calls
  the shared instance frequently cannot afford.
  ============================================================
-->

<div align="center">

<img height="165" alt="Sazzad Hossain Tasnim's GitHub statistics — commits, pull requests, issues and stars" src="https://github-readme-stats.vercel.app/api?username=SAZZAD-HT&show_icons=true&theme=gotham&hide_border=true&cache_seconds=86400" />
<img height="165" alt="Most used programming languages by Sazzad Hossain Tasnim — C#, JavaScript, TypeScript" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SAZZAD-HT&layout=compact&theme=gotham&hide_border=true&langs_count=8&cache_seconds=86400" />

<img alt="Sazzad Hossain Tasnim's GitHub contribution streak" src="https://streak-stats.demolab.com?user=SAZZAD-HT&theme=gotham&hide_border=true" />

<img alt="Sazzad Hossain Tasnim's GitHub contribution activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=SAZZAD-HT&theme=github-compact&hide_border=true&area=true" />

</div>

---

## Connect With Me

<div align="center">

[![Sazzad Hossain Tasnim on LinkedIn](https://img.shields.io/badge/LinkedIn-Sazzad%20Hossain%20Tasnim-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sazzadhossaintasnim/)
[![Sazzad Hossain Tasnim on X, formerly Twitter](https://img.shields.io/badge/X-@sazzadht0-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/sazzadht0)
[![Email Sazzad Hossain Tasnim](https://img.shields.io/badge/Gmail-sazzadaiub1@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sazzadaiub1@gmail.com)
[![Sazzad Hossain Tasnim on Google Scholar](https://img.shields.io/badge/Google%20Scholar-Publications-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=LKWJIjAAAAAJ&hl=en)
[![Buy Sazzad Hossain Tasnim a coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Support-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black)](https://www.buymeacoffee.com/sazzadht)

</div>

Plain-text contact details, so they stay readable and crawlable everywhere:

- **LinkedIn:** [linkedin.com/in/sazzadhossaintasnim](https://www.linkedin.com/in/sazzadhossaintasnim/)
- **X (Twitter):** [@sazzadht0](https://twitter.com/sazzadht0)
- **Email:** [sazzadaiub1@gmail.com](mailto:sazzadaiub1@gmail.com)
- **Google Scholar:** [Sazzad Hossain Tasnim — publications](https://scholar.google.com/citations?user=LKWJIjAAAAAJ&hl=en)
- **GitHub:** [github.com/SAZZAD-HT](https://github.com/SAZZAD-HT)

---

<details>
<summary><strong>Areas of expertise</strong> (click to expand)</summary>

<br>

**AI &amp; ERP modernization** — legacy ERP re-platforming, strangler-fig migration of monolithic
modules, SAP integration, intelligent document processing, multilingual OCR, and enterprise
knowledge retrieval over systems of record.

**AI engineering** — MCP server development and tool design, retrieval-augmented generation,
embedding and chunking strategy, vector and hybrid search, agentic workflows, tool calling and
structured outputs, evaluation harnesses, and token cost optimisation.

**Tokenization &amp; security** — PII tokenization and masking before third-party model calls, RBAC,
JWT and OAuth 2.0, IdentityServer, Azure Key Vault, applied cryptography, and guardrails against
prompt injection.

**Backend &amp; platform** — ASP.NET Core and .NET 8, Clean Architecture, CQRS, domain-driven design,
Entity Framework Core, microservices, event-driven messaging, Azure, Docker and Kubernetes, CI/CD,
infrastructure as code, and OpenTelemetry.

**Data &amp; full-stack** — SQL Server, PostgreSQL and pgvector, Power BI, Power Apps, Python and
Pandas, React, Next.js, NestJS, and Solidity.

</details>

<div align="center">

<sub>⭐️ If a repository here helped you, a star is genuinely appreciated.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer" alt="Decorative wave footer" />

</div>
