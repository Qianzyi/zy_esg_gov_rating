# zy_esg_gov_rating

Codex skill for listed-company ESG, ownership, management-fit, incentive-conflict, governance-history, and governance-risk analysis.

## Included skill

- `skills/analyze-company-esg-governance`

## Install

Copy the skill folder into your Codex skills directory:

```powershell
Copy-Item -Recurse .\skills\analyze-company-esg-governance "$env:USERPROFILE\.agents\skills\"
```

Restart Codex after installation.

## Example prompt

```text
Use $analyze-company-esg-governance to analyze a listed company's ESG profile, ownership structure, management fit, conflicts of interest, governance history, and governance risks.
```
