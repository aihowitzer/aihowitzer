<!-- Banner -->
<div align="center">

```
 █████╗ ██╗    ██╗  ██╗ ██████╗ ██╗    ██╗██╗████████╗███████╗███████╗██████╗
██╔══██╗██║    ██║  ██║██╔═══██╗██║    ██║██║╚══██╔══╝╚══███╔╝██╔════╝██╔══██╗
███████║██║    ███████║██║   ██║██║ █╗ ██║██║   ██║     ███╔╝ █████╗  ██████╔╝
██╔══██║██║    ██╔══██║██║   ██║██║███╗██║██║   ██║    ███╔╝  ██╔══╝  ██╔══██╗
██║  ██║██║    ██║  ██║╚██████╔╝╚███╔███╔╝██║   ██║   ███████╗███████╗██║  ██║
╚═╝  ╚═╝╚═╝    ╚═╝  ╚═╝ ╚═════╝  ╚══╝╚══╝ ╚═╝   ╚═╝   ╚══════╝╚══════╝╚═╝  ╚═╝
```

### `AI built it. I fix it.`

[![Website](https://img.shields.io/badge/aihowitzer.com-FF6A00?style=for-the-badge&logoColor=white)](https://aihowitzer.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/tilakrajgandhi)
[![Email](https://img.shields.io/badge/connect@aihowitzer.com-FF6A00?style=for-the-badge&logoColor=white)](mailto:connect@aihowitzer.com)

</div>

---

## ❯ whoami

```bash
$ ./introduce --target=cto

> Name        : Tilak Raj Gandhi
> Handle      : @aihowitzer
> Location    : Pune, India · Remote Worldwide
> Speciality  : Realtime systems · RabbitMQ · Kafka · Azure · Node.js
> Mission     : I clean up what AI and cowboy-coders leave behind in production
> Status      : ● AVAILABLE for new projects
```

I'm a **backend infrastructure specialist** with 10+ years fixing systems that were built to ship fast — not to last.

Most of my clients come to me after:
- 🔴 Their RabbitMQ silently dropped 30% of messages for 3 weeks
- 🔴 The AI-generated codebase made it to prod and is now leaking memory
- 🔴 Nobody knows why the queue is backing up at 2am
- 🔴 The dev who built it left and took the context with them

I don't just patch symptoms. I find the root cause, fix the architecture, add observability, and hand you back a system you can actually trust.

---

## ❯ stack --core

```
Message Queues     RabbitMQ · Apache Kafka · Azure Service Bus
Runtime            Node.js · TypeScript
Cloud              Azure Functions · Azure Monitor · App Insights
Realtime           SSE · WebSockets · Live log streaming
Observability      Grafana · Prometheus · Structured logging
Containers         Docker · Kubernetes
Databases          PostgreSQL · MongoDB · Redis
```

---

## ❯ services --fixed-price

| Package | What You Get | Price |
|---|---|---|
| 🔧 **Messaging Health Fix** | Queue audit · DLQ cleanup · Retry hardening · Alerts | ₹40k–80k |
| 📊 **Realtime Monitor Dashboard** | Live logs · Queue health panel · Failure alerts · Azure deploy | ₹60k–1L |
| 🧹 **AI Slop Cleanup** | Code audit · Refactor · Docs · Test coverage | ₹30k–60k |
| 🏗️ **Async Architecture Consult** | Design · Roadmap · Event-driven systems | ₹25k–50k |

> All packages are **fixed-scope, fixed-price**. No hourly surprises.
> Starts with a **free 30-minute audit call**.

---

## ❯ pinned --repos

| Repo | What it does |
|---|---|
| [`rabbitmq-health-monitor`](https://github.com/aihowitzer/rabbitmq-health-monitor) | CLI tool that audits your RabbitMQ cluster — finds silent failures, missing retry policies, DLQ overflows |
| [`dead-letter-inspector`](https://github.com/aihowitzer/dead-letter-inspector) | Visual dashboard for dead letter queues — inspect, replay, or purge messages |
| [`node-azure-observability-kit`](https://github.com/aihowitzer/node-azure-observability-kit) | Drop-in observability for Node.js on Azure — structured logs, alerts, App Insights wiring |
| [`ai-code-auditor`](https://github.com/aihowitzer/ai-code-auditor) | Checklist + scripts for auditing AI-generated backend code before it kills your prod |
| [`async-architecture-patterns`](https://github.com/aihowitzer/async-architecture-patterns) | Opinionated patterns for event-driven Node.js systems that actually hold up under load |

---

## ❯ ./audit --sample-output

```bash
$ rabbitmq-health-monitor --host=your-cluster

[■■■■■■■■░░] scanning 12 queues...

⚠  dead_letter_queue        : 4,821 unprocessed messages
✗  retry_policy             : not configured on 3 consumers
✗  message_ttl              : undefined — silent drops in progress
⚠  prefetch_count           : 0 — one slow consumer starving queue
✗  structured_logging       : absent — 47 errors completely invisible
✗  azure_monitor_alerts     : not configured

→  6 critical issues found
→  estimated message loss rate: ~18% of all published messages
→  full report: ./audit-report-2026-04-24.json
```

---

## ❯ contact --free-audit

```bash
$ curl -X POST https://aihowitzer.com \
  -d '{ "problem": "your broken system here" }' \
  --header "no-bs: true"

> Response: I'll call you back within 24 hours.
```

**→ [aihowitzer.com](https://aihowitzer.com)** · **→ [connect@aihowitzer.com](mailto:connect@aihowitzer.com)**

---

<div align="center">
<sub>
If your queues are losing messages right now — they probably are —
<a href="https://aihowitzer.com">let's talk.</a>
</sub>
</div>
