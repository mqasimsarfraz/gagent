# Gadget Agent

A collection of AI agents designed to help troubleshoot Container/Kubernetes issues using [cagent](https://github.com/docker/cagent)

## Getting Started

Start by working a workspace for agent definition:

```bash
mkdir gagent-agents
cd gagent-agents
```

Fetch the gadget definition:

```bash
cagent pull smqasims/agent-on_call
```

Configure the agent definition as per your local environment and run it using:

```bash
cagent run ./smqasims_agent-on_call.yaml
```
