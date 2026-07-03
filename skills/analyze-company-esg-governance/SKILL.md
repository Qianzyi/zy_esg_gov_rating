---
name: analyze-company-esg-governance
description: Use when analyzing a public company for ESG profile, ownership structure, controller/family/SOE traits, management background and fit, incentive conflicts, governance history, or governance risks, especially when drafting investor due diligence or research-note text from annual reports, ESG reports, exchange filings, company websites, and web sources.
---

# Analyze Company ESG Governance

## Overview

Produce evidence-backed ESG and governance analysis for listed companies. Separate disclosed facts, analytical inferences, and valuation-style judgments so the final text is useful for research notes and due diligence.

## Workflow

1. Confirm the target company, ticker, market, reporting year, and "as of" date. For current public-company facts, verify with fresh sources before writing.
2. Collect primary sources first: latest annual report, ESG/sustainability/social responsibility report if available, prospectus or refinancing documents, exchange announcements, company website, and investor relations materials. Use broader web search for regulatory penalties, litigation, controversies, or missing context.
3. Read `references/checklist.md` before doing the analysis. Use it as the evidence matrix, not as a writing template.
4. Extract facts for four blocks: business and ESG, ownership and control, management fit, and governance track record/risk.
5. Rate management fit as high, medium, or low, and explain why using role coverage, industry experience, execution record, incentives, succession, and independence checks.
6. When information is not directly disclosed, label it as an inference: "can be summarized as", "appears to", "public sources do not show", or "needs continued monitoring".
7. Draft in the user's requested style. If the user asks for one paragraph, keep one paragraph. If they ask for detailed analysis, use concise sections.

## ESG Paragraph Mode

When the user asks for an ESG analysis paragraph, write a single Chinese paragraph of about 800 Chinese characters unless the user specifies another length. Do not use headings, bullets, numbered lists, or section labels.

Follow this internal order inside the paragraph:

1. State what the company does: main products/services, application scenarios, industry-chain position, and business model traits.
2. Summarize the core ESG issues based on the company's business attributes and disclosures, not as an unsupported official claim. For manufacturing companies, usually check environmental compliance, energy and emissions, hazardous waste, occupational health and safety, product quality, supply-chain responsibility, customer concentration, R&D/IP protection, information disclosure, and board/internal-control governance.
3. Describe integrated practice around those issues: governance structure, management systems, certifications, environmental investment or facility upgrades, employee safety/training, quality controls, supplier/customer management, investor communication, anti-corruption, and disclosure practices. Tie each practice back to the issue it addresses.
4. Give an overall ESG evaluation: strengths, disclosure quality, gaps, residual risks, and monitoring points. Use balanced language such as "overall ESG performance is stable but disclosure depth still needs improvement".

Source requirements: use the latest annual report, standalone ESG/sustainability/social responsibility report if publicly available, company website, exchange announcements, and broader web search. If no standalone ESG report is found, say so precisely: "public searches did not show a standalone ESG report; the analysis mainly relies on annual-report ESG/social responsibility content, company website disclosures, and public information." For the recurring Lante Optics (`688127.SH`) ESG prompt, the paragraph must specifically answer: what Lante Optics does, its core ESG issues, integrated ESG practice, and overall ESG evaluation.

## Source Discipline

Prefer sources in this order:

- Exchange filings and official annual/ESG reports.
- Prospectus, refinancing documents, and formal announcements.
- Company website and investor relations pages.
- Regulator, court, credit, and official penalty databases.
- Reputable financial media and data terminals as supporting context.

Do not turn company self-description into an unqualified conclusion. For example, "core ESG issues" should usually be framed as "based on business attributes and disclosures, key ESG issues can be summarized as..."

## Judgment Rules

- Ownership: state explicitly whether the company is SOE, private, founder-led, family-influenced, dispersed, or institution-led. Include top holders, combined control, special voting rights, pledge/freeze status, related parties, and family relationships when disclosed.
- Management: connect biographies to the company's development stage. Technical manufacturing companies need technology, production, quality, customer, finance, capital markets, and compliance coverage.
- Interests: look for controller-manager overlap, family appointments, related transactions, private placements, equity incentives, pledges, competing businesses, major customer/supplier dependence, and minority-shareholder protections.
- Historical governance: check funds occupation, illegal guarantees, penalties, litigation/arbitration, internal-control opinion, auditor changes, disclosure corrections, board/committee functioning, independent director background, executive turnover, and investor communication.
- Risk conclusion: distinguish "observed red flags" from "structural risks". A founder-controlled company with no historical violations can still have medium structural governance risk.

## Output Pattern

Use this compact order unless the user asks otherwise:

1. Ownership structure and control traits.
2. Management background and fit rating.
3. Potential conflicts or incentive misalignment.
4. Historical governance performance.
5. Governance risks and overall judgment.

For Chinese investment-research writing, use direct evaluative wording equivalent to "high fit", "stable governance record", "medium structural risk", "monitor independent director substance", and "track related-party transactions and capital-operation fairness".

## Common Mistakes

- Do not call a company "family-controlled" without disclosed family relationships or strong public evidence.
- Do not call a company "state-owned" just because local government funds appear among shareholders; verify the actual controller.
- Do not treat a stable historical record as proof of low future governance risk when control is concentrated.
- Do not omit the date of the filing or report year when ownership or management has recently changed.
- Do not overstate ESG disclosure quality when the company has only annual-report ESG sections and no standalone ESG report.
