### Dinu Barbu

Senior software engineer — distributed systems and observability.

Much of my recent work has been message-driven systems and long-running workflows: the parts where
retries, partial failure and concurrency decide whether a system can be trusted.
Observability is how I keep them understandable in production.

#### Running now

Two public Go services and the shared infrastructure under them, all instrumented end to end.

- [**zibs**](https://github.com/dvinubius/zibs) · link shortener. Go, SQLite, Prometheus
  metrics, logs shipped to Loki through Alloy, Grafana dashboards provisioned from the
  repo, and a public live dashboard. [zibs.app](https://zibs.app)
- [**hooklook**](https://github.com/dvinubius/hooklook) · webhook inspector. A Go backend
  serving a Vue frontend, deployed through CI, with the same observability stack.
  [hooklook.app](https://hooklook.app)
- [**hetzner-one**](https://github.com/dvinubius/hetzner-one) · shared ingress for both.
  Caddy with TLS, routing and rate limits, plus host and proxy metrics in Prometheus and
  Grafana.

#### Before that

- **Zeit Finance** · designed and built the durable workflow behind a live vault system:
  an explicit state machine with idempotent steps, spanning blockchain, a Node.js backend
  and an external market. Co-author of the standard that came out of it,
  [PMVS](https://github.com/Autonomous-Finance/pmvs).
- **Autonomous Finance** · actor-model applications on AO, a message-passing compute
  platform: a [portfolio rebalancing agent](https://github.com/Autonomous-Finance/portfolio-agent-ao)
  running non-atomic multi-step trades, and a
  [reusable pub/sub package](https://github.com/Autonomous-Finance/aos-packages/tree/main/packages/subscribable).
- **EarnDLT** · worked on the design and build of resumable, queue-driven workflows over a private blockchain. NestJS, Bull,
  Redis, PostgreSQL, Kubernetes on AWS.

On the side: research on AI-assisted software engineering, like
[Token Police](https://github.com/dvinubius/token-police), written up on
[Substack](https://dvinubius.substack.com).

#### Elsewhere

[dinubarbu.com](https://dinubarbu.com) · [LinkedIn](https://www.linkedin.com/in/dinu-barbu) ·
[Substack](https://dvinubius.substack.com)

German and English. Open to team roles, remote across the EU, DACH focus.
