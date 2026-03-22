# Agent-Based Access Control (AGBAC) Specification

AGBAC is an open, vendor-neutral security specification that defines how AI agents securely perform actions on behalf of humans using existing IAM technologies. It provides a framework for zero-trust authentication, authorization, and auditing within AI agent workflows, bridging the gap between autonomous systems and enterprise security standards.

## Key Features
*   Defines a standardized model for agent-initiated actions and human delegation.
*   Integrates with existing OAuth 2.0, OpenID Connect, and policy-based access control systems.
*   Specifies audit trails for accountability of agent actions.
*   Enables secure, scoped access for autonomous AI agents.

## Tech Stack
*   Specification: OpenAPI, JSON Schema
*   Core Concepts: OAuth 2.0, OIDC, Policy-Based Access Control (PBAC)

## Getting Started
Review the core specification documents in the `/spec` directory. To explore the models and examples:
```bash
git clone https://github.com/zoreanuj/agent-access-control-spec.git
cd agent-access-control-spec
```