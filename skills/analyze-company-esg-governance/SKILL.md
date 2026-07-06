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
4. Extract facts for seven blocks: business and ESG, ownership and control, management background and fit, interest misalignment, governance track record/risk, institutional stewardship evidence, and internal verification evidence.
5. Rate management fit as high, medium, or low, and explain why using role coverage, industry experience, execution record, incentives, succession, and independence checks.
6. When information is not directly disclosed, label it as an inference: "can be summarized as", "appears to", "public sources do not show", or "needs continued monitoring".
7. Draft using the Mandatory Full Output Contract unless the user explicitly asks for only ESG, only governance, or a different format. For full ESG and governance requests, default to producing a compact formal PDF report when the environment supports file creation. If the user explicitly asks for chat-only text, Word, Markdown, or no file, follow that requested format.

## Mandatory Full Output Contract

When the user asks to analyze a public company's "ESG and corporate governance", the final answer or default PDF report must include these components in this order unless the user explicitly narrows the task:

1. ESG analysis: about 1000-2000 Chinese characters. In the default PDF/formal-report output, split the ESG analysis into 4-6 natural paragraphs with no internal headings, bullets, or numbered lists. In chat-only output, or when the user explicitly asks for "one paragraph", use one Chinese paragraph unless that would make readability unacceptable. It must answer: what business the company conducts; what the core ESG issues are; what integrated practices the company has around those issues; and the overall ESG evaluation. Expand the ESG practice discussion with concrete, sourced practices such as ESG governance structure, environmental targets and progress, energy/carbon/waste/water actions, certifications, supplier management, employee safety/training, quality, information security, anti-corruption, investor communication, and disclosure gaps.
2. Governance analysis: cover ownership structure, management background and fit, potential interest misalignment, historical governance performance, and governance risks. Governance analysis must cover ownership structure with traits such as SOE/private/family/founder/institution-led, concentration, actual controller, top holders, pledges/freezes when material; management fit must be rated high, medium, or low with detailed reasons.
3. Institutional investor stewardship points: add a section named "机构投资者尽责管理关注点". Present 3-5 substantive points in a small table, not a long prose section. The table must connect stewardship actions with the company's development stage and financial fundamentals, such as growth drivers, margin pressure, capital expenditure, M&A, leverage, cash flow, customer concentration, supply-chain resilience, related transactions, dividend/buyback policy, or return on invested capital. Suggested columns: "关注点", "与公司发展和财务基本面的关系", "尽责管理动作", and "需跟踪信号". Internally verify every stewardship point against collected sources; if verification finds a problem, revise the table before delivery. Do not include the stewardship verification process in the report.
4. Final verification note: do not add a separate visible "报告内容二次核验情况" section. Perform the secondary verification internally, correct factual errors before delivery, and place only one short sentence at the very end of the report, such as "报告内容已基于公开资料完成二次核验。". If any fact remains uncertain, mark it as "需进一步核验" in the relevant body text instead of presenting it as certain.

Do not omit any required component just because the user asks for a "report", "analysis", "rating", or names the skill directly. By default, full ESG and governance analysis should be delivered as a PDF containing the required components and the final one-sentence verification note. If the user asks for a Word/PDF/report deliverable, the document must still contain them. If PDF generation is unavailable in the current environment, provide the full text in chat and clearly say that the PDF could not be created.

## Default PDF and Formal Report Deliverables

When the user invokes this skill for a full ESG and governance analysis, produce a PDF by default unless the user explicitly requests another format. When creating the default PDF, or when the user asks for a formal report, Word document, or PDF:

1. Preserve the required components: ESG analysis, governance analysis, "机构投资者尽责管理关注点", sources, and a final one-sentence verification note. Do not create a separate "报告内容二次核验情况" section.
2. Use a compact research-note layout. Start page 1 with only the company name, ticker, and report title, then begin the substantive content on page 1. Do not add a separate "主要依据", "报告口径", "免责声明", investment-advice disclaimer, legal-opinion disclaimer, or long source-basis paragraph on page 1 unless the user explicitly asks for it.
3. Do not create a mostly blank cover page unless the user explicitly asks for a cover. Do not put a summary table on the first page unless the user asks for it.
4. Use first-line indentation of about two Chinese characters (2em) for every body paragraph in the PDF/formal report. Table cells, headings, and source lists do not need first-line indentation.
5. Use concise section headings for report readability. In default PDF/formal reports, the ESG section must be split into 4-6 natural paragraphs and total about 1000-2000 Chinese characters while keeping the same internal logic: business, core ESG issues, integrated practices, overall evaluation. Do not leave the ESG section as one large paragraph in a PDF report unless the user explicitly asks for one paragraph.
6. Expand the governance section in formal reports. Cover ownership/control, management background and fit rating, potential interest misalignment, historical governance record, and risk conclusion with enough detail for a finance report.
7. After governance analysis, add "机构投资者尽责管理关注点" as a small table with 3-5 rows. Keep it practical, substantive, and tied to the company's development stage and financial fundamentals. Avoid generic stewardship language that could apply to any company.
8. Put the source table after the institutional-investor table. Sources should include annual report, ESG/sustainability report if available, latest governance announcements, company website, and broader web or regulatory checks used. Put only one final verification sentence after the sources, for example "报告内容已基于公开资料完成二次核验。". Do not add a separate verification title or describe the verification process.
9. For PDFs, render and visually inspect the final output before delivery. Check Chinese fonts, paragraph indentation, page breaks, tables, headers/footers, and that page 1 is not visually empty.

## ESG Paragraph Mode

When writing the ESG part in chat-only mode, or when the user explicitly asks for one paragraph, write a single Chinese paragraph of about 1000-2000 Chinese characters unless the user specifies another length. Do not use internal headings, bullets, numbered lists, or section labels inside the ESG paragraph.

For the default PDF/formal-report output, split the same ESG analysis into 4-6 natural paragraphs by idea: business profile, core ESG issues, integrated ESG practices, and overall evaluation. Keep the combined length around 1000-2000 Chinese characters, and do not add subheadings, bullets, numbered lists, or section labels inside the ESG text.

Follow this internal order inside the paragraph:

1. State what the company does: main products/services, application scenarios, industry-chain position, and business model traits.
2. Summarize the core ESG issues based on the company's business attributes and disclosures, not as an unsupported official claim. For manufacturing companies, usually check environmental compliance, energy and emissions, hazardous waste, occupational health and safety, product quality, supply-chain responsibility, customer concentration, R&D/IP protection, information disclosure, and board/internal-control governance.
3. Describe integrated practice around those issues in expanded detail: governance structure, management systems, certifications, environmental targets and progress, energy/carbon/waste/water actions, environmental investment or facility upgrades, employee safety/training, quality controls, supplier/customer management, data/privacy protection, investor communication, anti-corruption, and disclosure practices. Tie each practice back to the issue it addresses, use verified metrics where available, and avoid filling space with generic ESG slogans.
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

1. ESG analysis: about 1000-2000 Chinese characters. Use 4-6 natural paragraphs in default PDF/formal reports; use one paragraph only for chat-only output or when explicitly requested. Do not use internal headings or bullets inside the ESG text.
2. Governance analysis: ownership structure and control traits; management background and fit rating; potential conflicts or incentive misalignment; historical governance performance; governance risks and overall judgment.
3. 机构投资者尽责管理关注点: small table with 3-5 stewardship points that connect to company development and financial fundamentals, recommended actions, and tracking signals. Internally verify this table and revise any unsupported point before delivery.
4. Sources and final verification sentence: put sources at the end, then add one short sentence such as "报告内容已基于公开资料完成二次核验。". Do not create a separate verification section.

For ordinary full ESG and governance requests, use the same content order and default to a compact PDF report. In the chat response, provide the PDF path/link and a short completion note; the PDF itself should contain the full analysis, "机构投资者尽责管理关注点" table, sources, and the final one-sentence verification note. For Word/PDF/formal-report requests, use a compact report layout: title at the top of page 1, content starts immediately, body paragraphs have about two Chinese characters of first-line indentation, no separate first-page "主要依据" or "免责声明" paragraph, no mostly blank cover, no first-page summary table unless requested, sources at the end followed by the final one-sentence verification note.

For Chinese investment-research writing, use direct evaluative wording equivalent to "ESG performance is medium-high", "management fit is high", "stable governance record", "medium structural risk", "monitor independent director substance", and "track related-party transactions and capital-operation fairness".

## Common Mistakes

- Do not call a company "family-controlled" without disclosed family relationships or strong public evidence.
- Do not call a company "state-owned" just because local government funds appear among shareholders; verify the actual controller.
- Do not treat a stable historical record as proof of low future governance risk when control is concentrated.
- Do not omit the date of the filing or report year when ownership or management has recently changed.
- Do not overstate ESG disclosure quality when the company has only annual-report ESG sections and no standalone ESG report.
- Do not output only governance analysis when the user asks for ESG and governance together.
- Do not create a separate "报告内容二次核验情况" section; secondary verification is an internal step and the report should only end with one short verification sentence.
- Do not make a PDF report with a mostly blank cover page or a first-page summary table unless the user requested those elements.
- Do not default to a chat-only answer for a full ESG and governance request unless the user explicitly asks for chat-only text or PDF creation is unavailable.
- Do not keep the ESG analysis as one large paragraph in a default PDF/formal report unless the user explicitly asks for one paragraph.
- Do not put "主要依据", "报告口径", "免责声明", investment-advice disclaimer, legal-opinion disclaimer, or similar source-basis/disclaimer paragraphs on the first page unless explicitly requested.
- Do not omit the "机构投资者尽责管理关注点" table in a default PDF/formal report.
- Do not write generic institutional stewardship points. Tie them to the company's strategy, growth stage, financial fundamentals, capital allocation, cash flow, customer/supplier structure, related-party transactions, and verified ESG/governance risks.
- Do not leave stewardship points unverified. If a stewardship point cannot be supported by filings, reports, company website, regulator/court records, or reputable public sources, revise or remove it before delivery.
- Do not leave body paragraphs flush-left in a PDF/formal report; use first-line indentation of about two Chinese characters.
