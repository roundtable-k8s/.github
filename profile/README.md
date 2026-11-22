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

| Repository | Description |
|---|---|
| [roundtable](https://github.com/roundtable-k8s/roundtable) | The operator: Knight, Chain, Mission and RoundTable CRDs, controllers and the Helm chart |
| [pi-knight](https://github.com/roundtable-k8s/pi-knight) | Default knight runtime, built on the Pi coding-agent SDK |
| [claude-knight](https://github.com/roundtable-k8s/claude-knight) | Alternative knight runtime, built on Claude Code |
| [roundtable-ui](https://github.com/roundtable-k8s/roundtable-ui) | Real-time dashboard for fleets, missions and chains |
| [arsenal](https://github.com/roundtable-k8s/arsenal) | Platform skills, git-synced into knights; layer your own skills repo on top with `spec.arsenals` |

Archived: [nats-bridge](https://github.com/roundtable-k8s/nats-bridge) and [knight-agent](https://github.com/roundtable-k8s/knight-agent), earlier runtimes superseded by pi-knight.

## 🚀 Install

```bash
helm install roundtable-operator \
  oci://ghcr.io/roundtable-k8s/charts/roundtable-operator \
  --namespace roundtable --create-namespace
```

Images are published to `ghcr.io/roundtable-k8s`. See the [operator README](https://github.com/roundtable-k8s/roundtable#readme) for a first Knight.
