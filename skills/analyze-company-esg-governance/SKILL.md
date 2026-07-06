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
4. Extract facts for six blocks: business and ESG, ownership and control, management background and fit, interest misalignment, governance track record/risk, and verification evidence.
5. Rate management fit as high, medium, or low, and explain why using role coverage, industry experience, execution record, incentives, succession, and independence checks.
6. When information is not directly disclosed, label it as an inference: "can be summarized as", "appears to", "public sources do not show", or "needs continued monitoring".
7. Draft using the Mandatory Full Output Contract unless the user explicitly asks for only ESG, only governance, or a different format. If the user asks for one paragraph, keep one paragraph. If they ask for a formal report, use concise sections while preserving the required content.

## Mandatory Full Output Contract

When the user asks to analyze a public company's "ESG and corporate governance", the final answer must include three components in this order unless the user explicitly narrows the task:

1. ESG analysis: one Chinese paragraph of about 800 Chinese characters. The ESG analysis must be about 800 Chinese characters and must not use internal headings, bullets, or numbered lists. It must answer: what business the company conducts; what the core ESG issues are; what integrated practices the company has around those issues; and the overall ESG evaluation.
2. Governance analysis: cover ownership structure, management background and fit, potential interest misalignment, historical governance performance, and governance risks. Governance analysis must cover ownership structure with traits such as SOE/private/family/founder/institution-led, concentration, actual controller, top holders, pledges/freezes when material; management fit must be rated high, medium, or low with detailed reasons.
3. Verification Expert: add a final visible section named "验证专家检查" or equivalent. The Verification Expert must perform an accuracy check against the collected sources, identify unsupported or uncertain claims, correct factual errors before final delivery, and state whether the final text is supported by annual reports, ESG reports, company website, filings, and broader internet sources. If errors, overstatements, or unsupported claims are found, the agent must revise the final answer before delivering it. If any fact remains uncertain, mark it as "需进一步核验" instead of presenting it as certain.

Do not omit any of these three components just because the user asks for a "report", "analysis", "rating", or names the skill directly. If the user asks for a Word/PDF/report deliverable, the document must still contain these three components.

## ESG Paragraph Mode

When writing the ESG part, write a single Chinese paragraph of about 800 Chinese characters unless the user specifies another length. Do not use internal headings, bullets, numbered lists, or section labels inside the ESG paragraph.

Follow this internal order inside the paragraph:

1. State what the company does: main products/services, application scenarios, industry-chain position, and business model traits.
2. Summarize the core ESG issues based on the company's business attributes and disclosures, not as an unsupported official claim. For manufacturing companies, usually check environmental compliance, energy and emissions, hazardous waste, occupational health and safety, product quality, supply-chain responsibility, customer concentration, R&D/IP protection, information disclosure, and board/internal-control governance.
3. Describe integrated practice around those issues: governance structure, management systems, certifications, environmental investment or facility upgrades, employee safety/training, quality controls, supplier/customer management, investor communication, anti-corruption, and disclosure practices. Tie each practice back to the issue it addresses.
4. Give an overall ESG evaluation: strengths, disclosure quality, gaps, residual risks, and monitoring points. Use balanced language such as "overall ESG performance is stable but disclosure depth still needs improvement".

Source requirements: use the latest annual report, standalone ESG/sustainability/social responsibility report if publicly available, company website, exchange announcements, and broader web search. If no standalone ESG report is found, say so precisely: "public searches did not show a standalone ESG report; the analysis mainly relies on annual-report ESG/social responsibility content, company website disclosures, and public information." For the recurring Lante Optics (`688127.SH`) ESG prompt, the paragraph must specifically answer: what Lante Optics does, its core ESG issues, integrated ESG practice, and overall ESG evaluation.

## Governance Analysis Mode

The governance section must answer the user's full governance question, not only summarize ownership. Include:

1. Ownership structure: company type and control traits. State whether it is state-owned, private, family-influenced, founder-led, institution-led, dispersed, or has no actual controller. Describe concentration using the controller, top shareholders, top 5/top 10 when available, voting agreements, concert parties, pledges/freezes, lockups, and insider share movements when material.
2. Management background: identify chairperson, general manager/president, CFO, board secretary, core technical or operating leaders, and relevant independent directors when useful. Connect their biographies to the company's business model and strategy.
3. Management fit rating: rate high, medium, or low. Explain in detail why the team does or does not fit the company's current stage using technology/product depth, production/quality, sales/customer resources, finance/capital markets, compliance, overseas operations, succession, and incentive alignment.
4. Potential interest misalignment: analyze controller-manager overlap, family appointments, related-party transactions, asset purchases/sales, guarantees, loans, private placements, equity incentives, buybacks, pledges, competing businesses, major customer/supplier dependence, and minority-shareholder protections.
5. Historical governance performance: check funds occupation, illegal guarantees, financial/internal-control audit opinions, regulatory penalties, exchange inquiry or warning letters, litigation/arbitration, disclosure corrections, auditor changes, independent director performance, board/committee operation, and investor relations.
6. Governance risk conclusion: give a clear risk level and explain observed red flags versus structural risks.

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

Default to this order for full ESG and governance requests:

1. ESG analysis: about 800 Chinese characters, one paragraph, no internal headings or bullets.
2. Governance analysis: ownership structure and control traits; management background and fit rating; potential conflicts or incentive misalignment; historical governance performance; governance risks and overall judgment.
3. Verification Expert: brief accuracy check, correction notes if any, and remaining uncertainties.

For Chinese investment-research writing, use direct evaluative wording equivalent to "ESG performance is medium-high", "management fit is high", "stable governance record", "medium structural risk", "monitor independent director substance", and "track related-party transactions and capital-operation fairness".

## Common Mistakes

- Do not call a company "family-controlled" without disclosed family relationships or strong public evidence.
- Do not call a company "state-owned" just because local government funds appear among shareholders; verify the actual controller.
- Do not treat a stable historical record as proof of low future governance risk when control is concentrated.
- Do not omit the date of the filing or report year when ownership or management has recently changed.
- Do not overstate ESG disclosure quality when the company has only annual-report ESG sections and no standalone ESG report.
- Do not output only governance analysis when the user asks for ESG and governance together.
- Do not skip the Verification Expert section; it is part of the deliverable, not an optional internal thought.
