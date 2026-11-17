# Outbound

## Research contacts

| Person | Reason to talk | Contact |
|---|---|---|
| Jacques Vermaak, listed at Stage Zero | Public Vault/ESO migration. Confirm managed-cloud fit and current rollout workflow. | [LinkedIn](https://za.linkedin.com/in/jacquesvermaak) |
| Viktoria Bisova, ITGix | Documented multi-account Kubernetes secret distribution. Practitioner or partner conversation. | [LinkedIn](https://bg.linkedin.com/in/viktoriabisova) · [CNCF article](https://www.cncf.io/blog/2026/06/09/solving-secret-sprawl-in-multi-account-kubernetes-with-external-secrets-operator/) |
| Chris Jaimon | Described OpenBao, ESO and Reloader doing three separate jobs. Technical discovery. | [Professional site](https://chrisjaimon.com/) · [Writeup](https://chrisjaimon.com/writeups/rotate-your-secrets-when-you-sleep) |

These are public research leads. Funding fit and purchasing authority remain open. Treg contact enrichment failed to connect and direct work emails were not verified.

## Three-touch sequence

Email one production owner per account. Personalize with a public technical signal. Use funding as a search filter, not as evidence of rollout pain.

### Day 1 · Kubernetes secret rotation at {{company}}

Hi {{first_name}},

I saw {{specific public signal}}. When you rotate a credential, do the apps that use it pick up the change automatically, or does someone still have to trigger a rollout?

We built Ennote to push updated credentials into native Kubernetes Secrets and roll the workloads you mark for restart.

If that step is still manual at {{company}}, open to seeing what it looks like on one workload?

{{your_name}}

### Day 4 · Reply in thread

Hi {{first_name}},

The workflow I mean is the gap between changing a password and knowing the running app actually picked it up.

We can show it on a test workload using the Kubernetes Secret format your app already reads. Change one credential and see how long it takes for the workload to be healthy and using the new value.

Worth a 15-minute look?

{{your_name}}

### Day 8 · Reply in thread

Hi {{first_name}},

Is secret rotation something you own at {{company}}? If it sits with someone else, I'd appreciate a pointer. If your setup already handles the rollout reliably, I'll leave it there.

{{your_name}}

## Discovery and pilot

Ask about the last production rotation: who changed the credential, what delivered it, what restarted the app, and how the team knew the app was using the new value. Test one workload with the agent, measure time to healthy workloads and manual steps, and check rollout safety before proposing migration. Start with 20 qualified accounts and track confirmed pain and pilot commitments by source signal.
