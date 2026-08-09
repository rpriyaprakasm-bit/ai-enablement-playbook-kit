# Microsoft 365 Copilot — adoption playbook

## When Copilot is a good fit

- First draft of email, summary, or status from **content the user already has**  
- Turning long threads/docs into **bullets or action lists**  
- Exploring wording options (user still owns the send)  

## When to prefer Power Automate / Apps instead

- Same steps every week with **no judgment** → Automate  
- Structured intake / approval → Forms + Automate or Apps  
- System of record updates at scale → governed flow or IT project  

## Prompt patterns (business-safe)

**Status summary**
```text
Using only the text I pasted, summarize progress, risks, and asks for a director.
Do not invent metrics. Flag anything that is unclear.
```

**Meeting → actions**
```text
Extract action items with owner and due date if stated.
List open questions separately. Do not assign owners that were not named.
```

**Process draft**
```text
Draft a simple SOP from these steps. Mark assumptions with [ASSUMPTION].
Keep language operational, not marketing.
```

## Anti-patterns

| Don’t | Why |
|-------|-----|
| Paste Restricted data into prompts | Policy / leakage risk |
| Send Copilot output without review | Hallucinations, wrong tone |
| “Build me a full solution architecture” with no context | Shallow, unchecked advice |
| Replace official policy search with chat | Source-of-truth problems |

## Rollout tips

1. Start with **one persona** (e.g. ops analysts) and three approved scenarios.  
2. Pair each scenario with a **1-page tip sheet** and a live demo.  
3. Collect “time saved / quality” stories monthly for leadership.  
4. Route automation-shaped ideas to a formal **intake process**, not endless Copilot experiments.  
