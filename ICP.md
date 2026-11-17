# Company context and ICP

## Saved company context

The Brain describes Ennote as a team vault for passwords, API keys and .env files plus a Kubernetes agent. Positioning emphasizes managed operations, push delivery, native Secrets, automatic rollouts, volatile-memory handling, BYOK and shared governance. The saved voice is direct, technical and comparison-driven. Named alternatives include Vault, OpenBao, Infisical, External Secrets Operator, AWS Secrets Manager, LastPass, Doppler and Akeyless. No named customer references or saved motions were present. Treat sub-second sync, ephemeral identities, cryptography and compliance readiness as vendor claims.

Public docs show a Helm-installed agent with outbound connectivity to Ennote Cloud. Existing apps that read Kubernetes Secrets can generally keep that pattern. Engineers configure the secret reference and mark each workload that should restart. Test rollout health and coordinate old credential revocation. A Vault migration may need separate work, especially for dynamic credentials or PKI. Fully air-gapped environments are a poor fit.

- [Agent](https://www.ennote.io/agent/)
- [Deployment](https://docs.ennote.io/docs/agents/deployment)
- [Security architecture](https://docs.ennote.io/docs/agents/security)
- [Pricing](https://www.ennote.io/pricing/) (free Developer, Team and Enterprise tiers)
- [Governance](https://www.ennote.io/secret-manager/)

## Account targeting

Prioritize lean Seed and Series A B2B SaaS, developer tools and API infrastructure companies, plus bootstrapped software firms with production Kubernetes. Try 15–100 employees as an initial search hypothesis. Look for production ownership, several workloads or environments, and evidence of manual restarts, separate sync/restart tooling, or an active secrets migration. Recent funding and platform hiring are discovery triggers. No geography or revenue cutoff was validated.

- Champion: Senior/Staff Platform Engineer, SRE Lead, DevOps Lead, founding engineer.
- Buyer: Head of Platform, Infrastructure or Engineering. At very lean firms, the CTO.
- Security reviewer: DevSecOps, Security or Compliance when cloud approval, access controls or audit evidence matter.
- Qualification: production Kubernetes, a named owner, a workflow the engineer wants to simplify, and permission for the managed control plane.
