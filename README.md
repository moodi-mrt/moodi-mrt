<!-- ─────────────────────────────  HERO  ───────────────────────────── -->

<a href="https://personalportfolio-zeta-sooty.vercel.app/">
  <img src="./assets/hero.svg" alt="Mehmood — Java Backend &amp; DevOps Engineer" width="100%">
</a>

<br>

I'm a Software Engineering student at **FAST-NUCES Peshawar**, focused on
**Java backend** and **DevOps**. I like the parts of software most people never
see — the services, data stores and pipelines that have to stay correct and
available under load. Comfortable with Spring Boot and PostgreSQL, learning the
infrastructure side, and drawn to system design, DSA and security.

<br>

<!-- ─────────────────────────────  FOCUS + BUILDING  ───────────────────────────── -->

<table>
<tr>
<td width="53%" valign="top">

<img src="./assets/status.svg" alt="Current focus" width="100%">

</td>
<td width="47%" valign="top">

#### Currently building

- Production-grade **Java · Spring Boot** backends
- Event-driven services with an **outbox + append-only ledger**
- **Docker** images and **GitHub Actions** pipelines
- **Kubernetes** and distributed-systems fundamentals
- Open-source contributions to **[JabRef](https://github.com/JabRef/jabref)**

<sub>Heading toward a Java Backend + DevOps role. Open to
internships and open-source collaboration.</sub>

</td>
</tr>
</table>

<br>

<!-- ─────────────────────────────  TECH STACK  ───────────────────────────── -->

### Tech stack

Grouped the way I reason about a system, not as a logo wall.

| Layer | Tools |
| :--- | :--- |
| **Languages** | Java · C++ · Python · SQL · Bash |
| **Backend** | Spring Boot · Spring Security · REST APIs · Servlets / JDBC · Tomcat |
| **Data & messaging** | PostgreSQL · MySQL · Apache Kafka · Redis |
| **Infrastructure** | Docker · GitHub Actions · Linux · Nginx · AWS |
| **Learning next** | Kubernetes · Terraform · Prometheus / Grafana |

<sub>Bold rows are where I work today. <em>Learning next</em> is deliberate —
I won't list a tool I'm still learning as something I've mastered.</sub>

<br>

<!-- ─────────────────────────────  FEATURED  ───────────────────────────── -->

### Featured project

#### ASCEND &nbsp;·&nbsp; <sub>append-only XP ledger for real-world effort</sub>

Real work — studying, building, training, reflection — is logged as events.
The server evaluates each event against **versioned rules** and writes an
**append-only ledger**; character and progress are disposable projections
rebuilt from that ledger. The interesting part isn't the theme — it's the
guarantees:

- **XP can never come from the client** — the request has no XP field, and unknown JSON is rejected.
- **Append-only for real** — enforced by database triggers *and* a runtime role with only `SELECT, INSERT`.
- **Exactly-once effect** — outbox pattern with unique constraints and idempotency keys, no broker.
- **Deterministic evaluation** — the rules engine is a pure function of `(event, rule versions, context)` and never reads the clock.

<sub>**Java 21 · Spring Boot 3.5 · Spring Modulith · PostgreSQL · React + TypeScript · Docker · CI**</sub>

**[View project →](https://github.com/moodi-mrt/ascend)**

<br>

<!-- ─────────────────────────────  SELECTED WORK  ───────────────────────────── -->

### Selected work

| Project | What it does | Stack | Status |
| :--- | :--- | :--- | :---: |
| **[ascend](https://github.com/moodi-mrt/ascend)** | Append-only XP ledger with versioned rules and deterministic evaluation | Java · Spring · Postgres | `Building` |
| **[nascon-webscan](https://github.com/moodi-mrt/nascon-webscan)** | Authorized-use web-scan orchestrator for CTF challenges — one clean report | Python | `Complete` |
| **[nocap OS](https://personalportfolio-zeta-sooty.vercel.app/)** | Portfolio built as an interactive terminal | React · Vite | `Live` |
| **[dsa-cpp](https://github.com/moodi-mrt/dsa-cpp)** | DSA practice — arrays, two pointers, sliding window | C++ | `Ongoing` |

<br>

<!-- ─────────────────────────────  ROADMAP  ───────────────────────────── -->

### Learning roadmap

| Now | Next | Later |
| :--- | :--- | :--- |
| Kubernetes | Terraform | Cloud architecture |
| Spring Security | Advanced Kubernetes | High-scale backends |
| System design | Distributed systems | Observability in depth |

<br>

<!-- ─────────────────────────────  BEYOND  ───────────────────────────── -->

### Beyond software

I follow financial markets seriously — less for the charts than for the
systems thinking they demand: market structure, macro, risk management and
decisions under uncertainty. It's the same discipline as good engineering:
model the system, define the failure mode, size the risk.

<br>

> **Build systems that stay understandable once they get complex.**
> Correctness first, then make it operable, then make it fast.

<br>

<!-- ─────────────────────────────  CONTACT  ───────────────────────────── -->

### Get in touch

**[Portfolio](https://personalportfolio-zeta-sooty.vercel.app/)** &nbsp;·&nbsp;
**[LinkedIn](https://www.linkedin.com/in/muhammad-mehmood-21b635431)** &nbsp;·&nbsp;
**[GitHub](https://github.com/moodi-mrt)** &nbsp;·&nbsp;
**[Email](mailto:mehmoodkhanmrt@gmail.com)**
