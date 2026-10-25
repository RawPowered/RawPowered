# Systems & operations

[Profile](../README.md) · [Expert Solar case](EXPERT-SOLAR.md) · [Security & privacy](SECURITY-AND-PRIVACY.md)

I work where operational requests become system changes: understand the process, identify the right source of data and authority, build the workflow, and leave the next operator a clear way to understand it.

## Start with real operating experience

At Expert Solar, my work included Salesforce/Zoho administration, internal tooling, user lifecycle and access, migrations, and cross-team support. The [preserved-history case](EXPERT-SOLAR.md) connects those responsibilities to surviving account evidence and separates it from my reported financial outcome.

My wider administration work includes Microsoft 365/Google Workspace transitions and Apple MDM configuration for field iPhones and tablets. [Background and scope](BACKGROUND.md).

## Then inspect the tools

| Operational question | Relevant work |
|---|---|
| How does a request become a reviewable workflow? | [Flow Fountain](https://github.com/RawPowered/flow-fountain-for-crms): triggers, conditions, actions, connection scope, and execution review |
| What survives a remote delivery interruption? | [305UGC CRM architecture](https://github.com/RawPowered/305UGC-Showcase/blob/main/docs/CRM-AND-AUTOMATION.md): local receipts, stable request identity, retry-aware transport |
| How do you investigate migration problems? | [DNS Sentinel](https://github.com/RawPowered/DNS-Sentinel): domain/email diagnostics; [OrphanHunter](https://github.com/RawPowered/OrphanHunter): reference mapping and migration investigation |
| Who may see a customer's project? | [Portal access walkthrough](SECURITY-AND-PRIVACY.md#portal-access-is-more-than-a-successful-login): identity, role, record scope, and project membership |
| How does research retain its context? | [Dive Deep](https://github.com/RawPowered/osint-dive-deep-v1): cases, provenance, provider boundaries, and job lifecycle |

## My operating approach

1. Establish the user, impact, urgency, and source of truth.
2. Separate a one-off fix from a recurring workflow problem.
3. Make ownership, permissions, failure behavior, and handoff explicit.
4. Review the implementation and evidence before describing the outcome.
5. Document what is complete, what remains dependent on another system, and the next acceptance check.

These are my working principles. They are not an assertion of a named ticketing-platform deployment, measured SLA improvement, or completed incident drill unless the linked case documents it. I use AI tools for investigation and implementation, with human review of the resulting changes.
