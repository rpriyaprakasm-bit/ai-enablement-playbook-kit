# Power Platform — maker guardrails

Short rules for citizen developers. Expand with your org’s CoE policies.

## Environments

| Do | Don’t |
|----|--------|
| Build production solutions in the designated environment | Build critical flows only in the default environment if policy forbids it |
| Use solutions for anything that must move Dev → Test → Prod | Rely on “export a single flow” with no documentation |

## Data loss prevention (DLP)

- Check whether the connectors you need are **Business** or **Blocked**.  
- Mixing blocked + business connectors can break runs — design before you build.  
- If blocked, **escalate** — don’t bypass with personal accounts.

## Licensing flags (teach makers to ask early)

| Signal | Action |
|--------|--------|
| Premium connector | Confirm license path before promising delivery |
| AI Builder / Copilot Studio capacity | Confirm capacity with platform owner |
| External guests as users | Validate guest access model |

## Design defaults

1. **Owner + backup** on every production flow/app.  
2. **Error email/Teams** on failed runs for anything business-critical.  
3. **No secrets** in Compose or hard-coded URLs with keys.  
4. Prefer **SharePoint list / Dataverse** over buried Excel on one desktop.  
5. Document the **happy path** in 10 lines on the backlog item.  

## When to stop and engage IT / platform team

- Restricted data  
- Cross-tenant or public endpoints  
- Financial posting or HR master data changes  
- Anything needing 24/7 support beyond maker best-effort  
