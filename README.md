# Simhadri Prasanna Kumar

Backend engineer working on APIs, data systems and AI infrastructure.

[GitHub](https://github.com/spk-2005) · [LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7363224112997060609/) · [X](https://x.com/prasann19964546) · [Email](mailto:prasannasimha5002@gmail.com)

---

## About

I'm a Computer Science graduate who enjoys backend engineering and the systems around it: databases, APIs, queues and, more recently, the infrastructure that AI applications depend on.

I like following a project from the first design sketch through implementation to deployment. I'm less interested in collecting tools than in understanding how real systems behave under load and why they fail.

## What I'm working on

**Context Trust Layer**
AI agents often pull in a lot of context from documents, databases and APIs, and not all of it is relevant or reliable. This project is my attempt at a layer that sits before the LLM and:

- retrieves the relevant context
- trims what isn't needed
- flags conflicting information
- scores how reliable each piece of context is
- tracks where it came from

Built with Python, FastAPI, PostgreSQL (pgvector), Redis, Docker and Next.js.

**CloudPrint**
A distributed document processing system. Requests come in through a REST API, jobs are stored in PostgreSQL, and background workers pick them up and process them. It covers:

- asynchronous job processing with concurrent workers
- safe job claiming using `FOR UPDATE SKIP LOCKED`
- retries and dead-letter handling for failed jobs
- Redis for supporting infrastructure

Built with .NET, ASP.NET Core, PostgreSQL, Redis and Docker.

## Experience

**Backend Engineer, SaaS product**

Worked on the backend of a SaaS product: building APIs, developing database-driven features, optimizing queries, improving performance and debugging production issues. A good part of the work was on analytics queries, where filtering early and reading fewer columns and rows (for example with ClickHouse's `PREWHERE`) made a noticeable difference.

It taught me the gap between code that works and code that holds up in production.

## Other projects

I've also built machine learning and NLP applications, AI assistants, data analysis tools, and REST APIs that serve ML models, mostly using Python, FastAPI, Flask, TensorFlow, scikit-learn, Pandas and NumPy.

## Tech stack

| Area | Tools |
| :--- | :--- |
| Languages | Python, Java, TypeScript, JavaScript, C, C# |
| Backend | FastAPI, Node.js, Express, ASP.NET Core, Spring Boot |
| Databases | PostgreSQL, MySQL, MongoDB, Redis, ClickHouse, pgvector |
| Cloud and infrastructure | Docker, AWS, GCP, Linux, message queues |
| Frontend | React, Next.js, Tailwind CSS |
| Data and ML | TensorFlow, scikit-learn, Pandas, NumPy, Jupyter |

## Achievements

- 2nd place, RupaJna National Prototype Challenge
- Participated in a 24-hour hackathon
- Open source contributor

## GitHub activity

<p>
  <img height="170" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=spk-2005&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&theme=default#gh-light-mode-only" />
  <img height="170" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=spk-2005&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&theme=dark#gh-dark-mode-only" />
  <img height="170" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=spk-2005&layout=compact&hide_border=true&theme=default#gh-light-mode-only" />
  <img height="170" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=spk-2005&layout=compact&hide_border=true&theme=dark#gh-dark-mode-only" />
</p>

<p>
  
  <img alt="GitHub streak" src="https://streak-stats.demolab.com/?user=spk-2005&hide_border=true&theme=dark#gh-dark-mode-only" />
</p>

## Currently learning

- **System design:** distributed systems, caching, message queues, database scaling, reliability
- **AI infrastructure:** RAG, vector databases, agent architecture, context engineering
- **Cloud:** AWS, GCP, containers, production deployment

## Get in touch

I'm interested in AI infrastructure, backend systems, developer tools and open source. If you're building something in those areas, feel free to reach out at [prasannasimha5002@gmail.com](mailto:prasannasimha5002@gmail.com).
