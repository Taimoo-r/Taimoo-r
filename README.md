<div align="center">

<img src="https://github.com/user-attachments/assets/74994462-03ad-42ce-abfb-44421a5430e8" alt="Taimoor — Full-Stack Engineer · AI/LLM · Distributed Systems · OSS" width="100%" />

</div>
<h1 align="center">
  Muhammad Taimoor
  <br>
  <sub>Full Stack · distributed systems · AI/ML pipelines</sub>
</h1>

I build products through deep problem solving, and ship 10x faster by pairing AI with my own
judgement. My expertise is rooted in system design, distributed systems and AI/ML pipelines. Open
source is my hobby, and where I sharpen my architectural design skills. I contribute to CNCF
projects, which need exactly that kind of depth. Whether the requirement is thinking, shaping,
breaking or manifesting the impossible, it's my job to make it happen through architecture driven
skills.

[Blog](https://medium.com/@YOUR_HANDLE) · [LinkedIn](https://linkedin.com/in/taimoor-ijaz) ·
[LeetCode](https://leetcode.com/u/TAIMOOR_IJAZ/) · mailme.taimoor@gmail.com

## Currently

- Building an **eBPF sandbox that detects malicious npm packages by what they do during install**,
  not by reading their source. It catches payloads shipped as compiled binaries, which static
  scanners cannot read.
- Contributing to [Apicurio Registry](https://github.com/Apicurio/apicurio-registry), a CNCF
  Sandbox project, in the operator and storage layers.
- Writing about AI and LLM tooling, distributed systems, and backend architecture.
- Competitive programming, and finishing my degree.
- Mentoring engineers one to one at [DevWeekends](https://www.devweekends.com/).

## Open source

| Project | Work |
|:---:|---|
| [Apicurio Registry](https://github.com/Apicurio/apicurio-registry) | [#9035](https://github.com/Apicurio/apicurio-registry/pull/9035), [#8740](https://github.com/Apicurio/apicurio-registry/pull/8740) and [#9335](https://github.com/Apicurio/apicurio-registry/pull/9335) merged. Split the operator CSV RBAC into namespace and cluster tiers, added a single-namespace least-privilege install variant, and derived readable descriptions for JSON compatibility diffs. Also a CloudEvents [webhook delivery engine](https://github.com/Taimoo-r/apicurio-registry/tree/lfx/webhook-delivery-slice) with at-least-once delivery and the retry schedule kept in PostgreSQL, so a delivery survives `docker kill` mid-backoff ([recorded run](https://youtu.be/Tn4-edB67D0)) |
| [Cognee](https://github.com/topoteretes/cognee-rs) | [#24](https://github.com/topoteretes/cognee-rs/pull/24), [#35](https://github.com/topoteretes/cognee-rs/pull/35) and [#36](https://github.com/topoteretes/cognee-rs/pull/36) merged. Removed two N+1 query loops, wrapped bulk provenance writes in a single transaction, and consolidated redundant queries in the vector and graph paths. Rust |
| [Limitador](https://github.com/Kuadrant/limitador) | [#501](https://github.com/Kuadrant/limitador/pull/501) open. Replaced `.unwrap()` calls with descriptive `.expect()` messages so panics say what actually failed. Rust |
| [Coral](https://github.com/withcoral/coral) | [#1081](https://github.com/withcoral/coral/pull/1081) merged. Vapi Voice AI source integration |
| [hookproof](https://github.com/Taimoo-r/hookproof) | Author. Fault-injection harness for HTTP webhook producers in Java. Fifteen checks over raw sockets, including faults no server library can produce, such as `200 OK` followed by half a body and then a TCP reset |

## Curated work

| Project | What it is |
|:---:|---|
| [topfived.com](https://topfived.com) | Real-time group challenges, voting and leaderboards. React and Supabase, 56 relational tables with Edge Functions and cron jobs handling the background work. Shipped for a US client in 2.5 months |
| [GitTix](https://github.com/Taimoo-r/ticketing-microservice-app) | Ticket marketplace as six services on Kubernetes over a NATS Streaming event bus. Reservations expire after 15 minutes through a delayed Bull job, out-of-order events are handled with per-document version numbers, and each service ships independently through path-filtered GitHub Actions. TypeScript, Docker, MongoDB, Redis, Stripe |
| [LMS](https://tlearning.vercel.app/) | Course platform with student enrollment, instructor tools and admin access. Next.js, secure API routes and dynamic course management |
| [Multivendor marketplace](https://github.com/Taimoo-r/Multivendor-ecommerce-application) | Role-based access with separate dashboards for admins, vendors and customers. MERN, JWT, Cloudinary |

## Experience

**Turing** — AI Model Engineer and Evaluator. C++ systems for model training, benchmarking model
performance across domains, led supervised fine-tuning work and contributed to RLHF.

**Freelance** — full-stack delivery for clients, working across time zones and mostly async.

## Teaching and community

DSA Trainer at [DevWeekends](https://www.devweekends.com/), running advanced sessions for a
community of more than 20,000 developers and mentoring 500+ students, most of them one to one.
Live sessions from [general engineering](https://youtu.be/9mEl4venemE) to
[competitive programming](https://www.youtube.com/live/EgiSU7HGves).

CP Lead at GDGoC. ICPC onsite participant. 330+ problems solved on LeetCode.

## Stack

💻 **Languages** — JavaScript, TypeScript, Java, Rust, C++, Python

🌐 **Web** — React, Next.js, Node.js, Express, React Native, REST APIs

🧠 **AI and LLM** — LangChain, LangGraph, RAG, embeddings, vector databases (Chroma, Pinecone)

🗄️ **Data** — PostgreSQL, MySQL, MongoDB, SQL Server, H2

☁️ **Infra** — Docker, Kubernetes, AWS (EC2, S3), CI/CD, Linux, Supabase
