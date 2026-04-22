# egaprotocol/core

**Reference implementation — coming soon.**

This repository will contain the reference implementation of
[EGAProtocol (EGAP)](https://egaprotocol.org) — the open protocol that brings
discipline to AI agents.

---

## What is EGAProtocol?

EGAP is an open specification for governed communication between an orchestration
Engine and AI Agents. The **5AG Governance Framework** — Authentication,
Authorization, Audit, Approvals, and Alerts — is enforced on every agentic action at
the wire level.

**The open protocol that brings discipline to AI agents.**

The reference implementation will provide:

- A production-ready engine SDK (Go, with community bindings forthcoming)
- A wire-compatible agent SDK
- A JSON-RPC 2.0 over WebSocket transport binding
- A gRPC over HTTP/2 transport binding
- Integration with OpenTelemetry for audit event export
- Docker images for local development and testing

---

## Status

The specification is published at [egaprotocol/spec](https://github.com/egaprotocol/spec).
Reference implementation is in development.

Watch this repository for progress updates, or join the discussion at
[GitHub Discussions](https://github.com/egaprotocol/spec/discussions).

---

## Links

- **Specification:** [egaprotocol/spec](https://github.com/egaprotocol/spec)
- **Website:** [egaprotocol.org](https://egaprotocol.org)
- **Conformance tests:** [egaprotocol/conformance](https://github.com/egaprotocol/conformance) *(coming soon)*
- **Contact:** [hello@egaprotocol.org](mailto:hello@egaprotocol.org)

---

## Not the Mira engine SDKs

This repository is the **reference implementation of EGAProtocol itself** — a
vendor-neutral implementation of the open wire standard. It is distinct from the
Mira engine agent SDKs
([`mirastack-agents-sdk-go`](https://github.com/mirastacklabs-ai/mirastack-agents-sdk-go),
[`mirastack-agents-sdk-python`](https://github.com/mirastacklabs-ai/mirastack-agents-sdk-python)),
which are client libraries for building agents that run on MIRASTACK LABS' Mira
orchestration engine. The Mira SDKs are expected to adopt EGAProtocol as their wire
transport in a future release and be cited as the first production implementation
of EGAP.

---

## License

Apache License 2.0. Copyright © 2026 MIRASTACK LABS Private Limited.
