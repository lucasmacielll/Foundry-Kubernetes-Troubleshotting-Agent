# Foundry-Kubernetes-Troubleshotting-Agent
Azure AI Foundry Kubernetes assistant using GPT-5.1 Codex Mini and Kubernetes Runbook ⭐

# ks8-troubleshotting-AKVA

An AI-powered Kubernetes troubleshooting assistant built with **Azure AI Foundry**.

The purpose of this project is to help Cloud Engineers, DevOps Engineers, SREs, and Platform Engineers quickly understand Kubernetes errors, identify root causes, and receive actionable remediation steps.

> **Note**
> This repository contains the project documentation and implementation guidance. Azure credentials, endpoints, and sensitive resources are intentionally excluded.

---

## Overview

Kubernetes troubleshooting often requires searching through documentation, runbooks, GitHub issues, and community discussions.

This AI Agent centralizes that process by combining:

- Azure AI Foundry Agent
- GPT-5.1 Codex Mini
- Kubernetes Runbook (Knowledge Base)
- Web Search
- Code Interpreter

The agent provides contextual troubleshooting recommendations based on both internal documentation and external sources.

---

## Agent Information

| Property | Value |
|----------|-------|
| Agent Name | **ks8-troubleshotting-AKVA** |
| Platform | Azure AI Foundry |
| Model | GPT-5.1 Codex Mini |
| Purpose | Kubernetes Troubleshooting Assistant |

---

## System Instructions

```
You are a Kubernetes Expert.

When a user provides you with a Kubernetes error, you will help them understand the error and provide suggested fixes.
```

---

# Architecture

```
                User
                  │
                  ▼
      Azure AI Foundry Agent
                  │
      ┌───────────┼───────────┐
      │           │           │
      ▼           ▼           ▼
Knowledge     Web Search   Code Interpreter
(K8s Runbook)     │              │
      │           │              │
      └───────────┼──────────────┘
                  ▼
          GPT-5.1 Codex Mini
                  │
                  ▼
       Troubleshooting Response
```

---

# Knowledge Base

The agent uses a Kubernetes Runbook as its primary knowledge source.

The runbook contains:

- Kubernetes concepts
- Common production incidents
- Troubleshooting procedures
- kubectl commands
- Best practices
- Cluster diagnostics
- Networking issues
- Storage troubleshooting
- Deployment failures
- Pod lifecycle
- CrashLoopBackOff
- ImagePullBackOff
- Node failures
- Resource management

---

# Available Tools

## Knowledge Retrieval

Retrieves information from the Kubernetes Runbook.

Used for:

- Internal procedures
- Troubleshooting guides
- Best practices

---

## Web Search

Searches external resources when additional information is required.

Examples:

- Kubernetes Documentation
- GitHub Issues
- CNCF Documentation
- Stack Overflow
- Blogs
- Microsoft Learn

---

## Code Interpreter

Used to assist with:

- Log analysis
- YAML inspection
- Resource calculations
- Parsing outputs
- Data analysis

---

# Example Questions

```
Why is my Pod in CrashLoopBackOff?

Explain ImagePullBackOff.

Why is my Deployment unavailable?

How do I troubleshoot a Pending Pod?

How do I debug CoreDNS?

Explain this kubectl output.

Analyze this YAML.

How can I fix a failing readiness probe?
```

---

# Repository Structure

```
.
├── README.md
├── requirements.txt
├── .env.example
├── screenshots/
├── docs/
├── knowledge/
└── architecture/
```

---

# Technologies

- Azure AI Foundry
- Azure AI Agent Service
- GPT-5.1 Codex Mini
- Python
- Kubernetes
- Azure AI Search (Knowledge)
- Web Search Tool
- Code Interpreter

---

# Future Improvements

- Azure Monitor integration
- AKS diagnostics
- Prometheus metrics analysis
- Grafana dashboard analysis
- Log Analytics integration
- GitHub Issue correlation
- Multi-cluster support

---

# Disclaimer

This project is intended for educational and portfolio purposes.

The Kubernetes Runbook included in the knowledge base must only contain documentation that can be legally shared.# ks8-troubleshotting-AKVA

An AI-powered Kubernetes troubleshooting assistant built with **Azure AI Foundry**.

The purpose of this project is to help Cloud Engineers, DevOps Engineers, SREs, and Platform Engineers quickly understand Kubernetes errors, identify root causes, and receive actionable remediation steps.

> **Note**
> This repository contains the project documentation and implementation guidance. Azure credentials, endpoints, and sensitive resources are intentionally excluded.

---

## Overview

Kubernetes troubleshooting often requires searching through documentation, runbooks, GitHub issues, and community discussions.

This AI Agent centralizes that process by combining:

- Azure AI Foundry Agent
- GPT-5.1 Codex Mini
- Kubernetes Runbook (Knowledge Base)
- Web Search
- Code Interpreter

The agent provides contextual troubleshooting recommendations based on both internal documentation and external sources.

---

## Agent Information

| Property | Value |
|----------|-------|
| Agent Name | **ks8-troubleshotting-AKVA** |
| Platform | Azure AI Foundry |
| Model | GPT-5.1 Codex Mini |
| Purpose | Kubernetes Troubleshooting Assistant |

---

## System Instructions

```
You are a Kubernetes Expert.

When a user provides you with a Kubernetes error, you will help them understand the error and provide suggested fixes.
```

---

# Architecture

```
                User
                  │
                  ▼
      Azure AI Foundry Agent
                  │
      ┌───────────┼───────────┐
      │           │           │
      ▼           ▼           ▼
Knowledge     Web Search   Code Interpreter
(K8s Runbook)     │              │
      │           │              │
      └───────────┼──────────────┘
                  ▼
          GPT-5.1 Codex Mini
                  │
                  ▼
       Troubleshooting Response
```

---

# Knowledge Base

The agent uses a Kubernetes Runbook as its primary knowledge source.

The runbook contains:

- Kubernetes concepts
- Common production incidents
- Troubleshooting procedures
- kubectl commands
- Best practices
- Cluster diagnostics
- Networking issues
- Storage troubleshooting
- Deployment failures
- Pod lifecycle
- CrashLoopBackOff
- ImagePullBackOff
- Node failures
- Resource management

---

# Available Tools

## Knowledge Retrieval

Retrieves information from the Kubernetes Runbook.

Used for:

- Internal procedures
- Troubleshooting guides
- Best practices

---

## Web Search

Searches external resources when additional information is required.

Examples:

- Kubernetes Documentation
- GitHub Issues
- CNCF Documentation
- Stack Overflow
- Blogs
- Microsoft Learn

---

## Code Interpreter

Used to assist with:

- Log analysis
- YAML inspection
- Resource calculations
- Parsing outputs
- Data analysis

---

# Example Questions

```
Why is my Pod in CrashLoopBackOff?

Explain ImagePullBackOff.

Why is my Deployment unavailable?

How do I troubleshoot a Pending Pod?

How do I debug CoreDNS?

Explain this kubectl output.

Analyze this YAML.

How can I fix a failing readiness probe?
```

---

# Repository Structure

```
.
├── README.md
├── requirements.txt
├── .env.example
├── screenshots/
├── docs/
├── knowledge/
└── architecture/
```

---

# Technologies

- Azure AI Foundry
- Azure AI Agent Service
- GPT-5.1 Codex Mini
- Python
- Kubernetes
- Azure AI Search (Knowledge)
- Web Search Tool
- Code Interpreter

---

# Future Improvements

- Azure Monitor integration
- AKS diagnostics
- Prometheus metrics analysis
- Grafana dashboard analysis
- Log Analytics integration
- GitHub Issue correlation
- Multi-cluster support

---

# Disclaimer

This project is intended for educational and portfolio purposes.

The Kubernetes Runbook included in the knowledge base must only contain documentation that can be legally shared.
