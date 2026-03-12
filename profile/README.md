# Knights of the Round Table 🏰

**Kubernetes-native multi-agent AI orchestration**

An operator that manages AI agents as Knights, orchestrates them via Chains and Missions, all running on Kubernetes with NATS JetStream.

## ✨ Key Features

- 🛡️ **CRD-based agent lifecycle** — Define and manage AI agents as Kubernetes custom resources
- ⛓️ **Chain DAG pipelines** — Compose multi-agent workflows as directed acyclic graphs
- ⚔️ **Ephemeral missions** — Spin up short-lived agent tasks on demand
- 🗄️ **NATS KV for durable state** — Persistent key-value storage via NATS JetStream
- 💰 **Cost tracking & budgets** — Monitor and cap AI spending per agent/mission
- 📊 **Real-time dashboard** — Live visibility into your agent fleet

## 📦 Repositories

> ⚠️ **Migration from [dapperdivers](https://github.com/dapperdivers) in progress**

| Repository | Description |
|---|---|
| [roundtable](https://github.com/dapperdivers/roundtable) | Core Kubernetes operator |
| [roundtable-ui](https://github.com/dapperdivers/roundtable-ui) | Real-time dashboard |
| [pi-knight](https://github.com/dapperdivers/pi-knight) | Raspberry Pi agent runtime |
| [roundtable-arsenal](https://github.com/dapperdivers/roundtable-arsenal) | Helm charts & deployment tools |

