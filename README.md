# production-reliability-lab
Interactive production incident simulations covering troubleshooting, distributed systems, reliability, observability, and failure recovery.
# Production Incident Lab

> Interactive simulations of real-world production failures, troubleshooting approaches, system behavior, and reliability improvements.

##  About

Production systems don't always fail because the application itself is down.

Sometimes the application is running perfectly, but one of its critical dependencies is unhealthy.

A database can become unavailable.

An authentication service can fail.

A message queue can stop processing.

A downstream API can timeout.

A synchronization process can fall behind.

These failures can create problems that are difficult to understand from the user's perspective.

For example:

> **"I can't log in. It just says Network Error."**

But the actual problem may be several layers deeper in the system.

This repository is a collection of **interactive production incident simulations** designed to visualize how these failures happen, how to troubleshoot them, how to recover from them, and how to make the architecture more reliable.

---

#What This Repository Demonstrates

Each incident focuses on a practical engineering problem and covers:

- Incident investigation
- Root cause analysis
- Request tracing
- Service dependencies
- System architecture
- Failure scenarios
- Observability
- Logging
- Health checks
- Replication and synchronization
- Timeouts and retries
- Recovery and failover
- Scalability
- Reliability improvements
- Cross-team troubleshooting

The goal is not just to show **what failed**, but to explain:

> **Why did it fail?**
>
> **How do we find it?**
>
> **How do we recover it?**
>
> **How do we prevent it from happening again?**

---

# Incident Simulations

## 1. Authentication Dependency Failure

### Scenario

Users suddenly cannot log in to a production application.

The frontend displays:

```text
Network Error
