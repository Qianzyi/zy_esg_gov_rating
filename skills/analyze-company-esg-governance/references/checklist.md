# ESG and Governance Analysis Checklist

Use this checklist to build an evidence matrix before writing. Not every item must appear in the final answer, but missing high-risk items should be checked or explicitly marked unavailable.

## Mandatory Output Contract

- Full ESG and governance requests must include five required components: chapter `一、ESG分析`, the complete numbered governance chapter flow, a section named `机构投资者尽责管理关注点` with a table, a visible `数据来源` table, and the exact final sentence `报告内容已基于公开资料完成二次核验。`. The governance chapters themselves satisfy the governance-analysis component; do not add a redundant `公司治理分析` wrapper or a separate `报告内容二次核验情况` section.
- Treat ordinary prompts such as "用 analyze-company-esg-governance skill 分析XX企业的ESG和公司治理" or "用这个skill分析XX企业的ESG和公司治理" as full ESG and governance requests. The user does not need to separately ask for the stewardship table, data source table, or final verification sentence.
- ESG analysis must be about 1000-2000 Chinese characters. In default PDF/formal reports, split it into 4-6 natural paragraphs with no internal headings or bullets. Use one paragraph only for chat-only output or when explicitly requested.
- ESG paragraph must answer: company business, core ESG issues, integrated ESG practices, and overall ESG evaluation.
- Governance analysis must cover ownership structure, management background, management fit rating, potential interest misalignment, historical governance performance, and governance risks.
- Institutional investor stewardship points must connect with the company's development stage and financial fundamentals, such as growth drivers, margins, capital expenditure, M&A, leverage, cash flow, customer concentration, supply-chain resilience, related transactions, dividend/buyback policy, or return on invested capital. Internally verify this table and revise unsupported points before delivery; do not describe that verification process in the report.
- Perform secondary verification internally against annual reports, ESG reports, company website, filings, and broader internet sources. Correct unsupported claims before final delivery and flag unresolved uncertainties as "需进一步核验" in the relevant body text. End the report with the exact sentence "报告内容已基于公开资料完成二次核验。".

- Full ESG and governance requests default to a PDF deliverable when file creation is available. Use chat-only text, Word, Markdown, or another format only when the user explicitly requests it or PDF generation is unavailable.
- For Word/PDF/formal reports, use a compact research-note layout: title at the top of page 1, substantive content starts on page 1, body paragraphs use first-line indentation of about two Chinese characters, and there is no "主要依据", "报告口径", "免责声明", investment-advice disclaimer, legal-opinion disclaimer, mostly blank cover page, or first-page summary table unless requested. Put "机构投资者尽责管理关注点", a table titled "数据来源", and the exact final sentence at the end, and render-check PDFs before delivery.
- Mandatory output gate before delivery: confirm the report contains chapter `一、ESG分析`, the governance chapter flow numbered `二` through `十`, the `机构投资者尽责管理关注点` table, the `数据来源` table, and the exact final sentence `报告内容已基于公开资料完成二次核验。`. These five items are all required; the last three are additions to the ESG and governance analysis, not replacements. If any item is missing, revise before delivery.

## Dual-Mode Report Gate

- Integrated mode: use `[公司名]ESG与公司治理分析`; start with `一、ESG分析`; then number the governance chapters from `二、核心判断` through `十、治理风险等级与后续跟踪清单`.
- Integrated ESG chapter: about 1000-2000 Chinese characters in 4-6 natural paragraphs, company-specific metrics where disclosed, no internal subheadings or bullets.
- Governance-only mode: use `[公司名]公司治理分析`; start with `一、核心判断`; finish with `九、治理风险等级与后续跟踪清单`.
- Governance-only mode must not contain an ESG chapter, ESG metrics, or sustainability overview unless the user explicitly changes scope.
- Both modes: no separate cover or table of contents unless requested; keep the executive roster and capability matrix in one numbered chapter; add `机构投资者尽责管理关注点` as an unnumbered subsection; end with sources and the exact verification sentence.

## Business and ESG

- Main business, product lines, application scenarios, and industry chain position.
- Revenue drivers and whether the company is manufacturing-heavy, asset-light, platform-based, or regulated.
- ESG reports available: standalone ESG/sustainability/social responsibility report, annual-report ESG section, website responsibility page.
- ESG output: about 1000-2000 Chinese characters, no internal headings or bullets.
- For default PDF/formal reports, split the ESG analysis into 4-6 natural paragraphs while preserving the required logic and approximate length.
- If the user explicitly asks for one paragraph or chat-only text, keep the ESG analysis in one paragraph.
- ESG paragraph structure: business scope, core ESG issues, expanded integrated practices around those issues, and overall ESG evaluation.
- Environmental issues: emissions, wastewater, waste gas, solid waste, hazardous waste, energy, water, carbon emissions, clean energy, environmental penalties.
- Social issues: labor rights, training, safety, quality systems, customer concentration, product safety, data/privacy if relevant, community responsibility.
- Governance issues: board structure, internal controls, anti-corruption, information disclosure, investor relations, IP protection, supply-chain ESG.
- ESG practices to expand when supported by sources: governance structure, management systems, certifications, environmental targets and progress, energy/carbon/waste/water actions, environmental investment or facility upgrades, employee safety/training, quality controls, supplier/customer management, data/privacy protection, investor communication, anti-corruption, and disclosure practices.
- Disclosure gaps: carbon data, reduction targets, supplier audits, occupational safety metrics, diversity metrics, external assurance.

## Ownership and Control

- Controller type: SOE, private founder, family, collective, no controller, PE/VC, institution-led.
- Top 10 shareholders and top 5 concentration; combined control percentage if disclosed.
- Control chain, direct plus indirect holdings, voting agreements, concert parties, entrusted voting, waived voting rights.
- Special voting rights, dual-class shares, red-chip/VIE structure, employee platforms, partnership control.
- Share pledges, freezes, lockups, recent reductions, refinancing participation, and insider transactions.
- Family or related-party relationships among shareholders, directors, supervisors, executives, and employee platforms.

## Management Fit

Rate high, medium, or low.

High fit:
- Founder or executives have long domain experience relevant to strategy and customers.
- Team covers technology/R&D, production, quality, sales/customer development, finance, compliance, and capital markets.
- Recent operating performance supports execution ability.
- Key technical or sales leaders are retained and incentives are aligned.
- Independent directors add relevant technical, legal, accounting, or industry expertise.

Medium fit:
- Core team fits the legacy business but has gaps for new growth areas.
- Founder dependence is high and succession is unclear.
- Management turnover, external hires, or family appointments need monitoring but are not yet harmful.
- Incentive plans exist but performance targets or coverage are only partly convincing.

Low fit:
- Executives lack relevant industry or functional background.
- Frequent turnover, weak finance/compliance capacity, or loss of core technical staff appears.
- Strategy depends on areas where management has little demonstrated capability.
- Incentives encourage short-term results or conflict with minority shareholders.

## Interest Misalignment

- Chairperson and CEO/GM held by the controller or same person.
- Controller or family members serve in several key management/board roles.
- Related-party transactions, connected procurement/sales, asset transfers, guarantees, loans, or deposits.
- Private placement, M&A, equity incentive, or buyback arrangements involving controller or insiders.
- Large dividend, high cash balance, pledged shares, or financing needs that may shape controller behavior.
- Major customer/supplier dependence that could reduce bargaining power or create undisclosed conflicts.
- Protections: independent director review, related-party voting avoidance, audit committee, disclosure quality, external audit opinions.

## Historical Governance Performance

- Non-operating funds occupation by controller or related parties.
- Illegal external guarantees.
- Major litigation/arbitration, administrative penalties, regulatory letters, exchange inquiries, disclosure corrections.
- Internal-control audit opinion and financial audit opinion.
- Auditor changes, qualified opinions, emphasis-of-matter paragraphs.
- Board meetings, shareholder meetings, committee setup, independent director attendance and background.
- Executive compensation basis, clawback/deferred pay arrangements if disclosed, equity incentives, and assessment mechanisms.
- Investor relations activity: performance briefings, IR records, website, Q&A, and shareholder communication.

## Governance-Only PDF Report Gate

- The user requested governance only; no ESG section or ESG metrics are present.
- Page 1 has a visible `[公司名]公司治理分析` title and then begins with `一、核心判断`; there is no separate cover page or table of contents unless requested.
- Default numbered flow: core judgment; development stage and governance issues; ownership/control chain; directors/source/fit; executives and capability matrix in one chapter; related-party transactions; funds occupation/guarantees/litigation/internal control; capital allocation/minority protection; risk level/tracking list.
- The director section uses one continuous table with repeated headers. Each director row covers current role/committee, nomination or shareholder source when material, education/professional qualifications, career and company history, relevant capability, fit rating, and reasons.
- The executive section covers strategy-critical leaders with education, career path, company tenure, responsibilities, disclosed equity/incentives, and fit. The capability matrix is a subsection of the same numbered chapter, not a separate numbered chapter.
- Ownership evidence includes the actual controller, direct and indirect control chain, major and strategic shareholders, percentages, concert-party or voting arrangements, pledges/freezes when material, and board nomination sources.
- Related-party analysis separates recurring operating transactions from financial services and distinguishes actual amount, period-end balance, forecast/approved amount, and cap.
- Recurring transaction evidence includes counterparty, type, actual amount, forecast/approval, share or concentration, variance, and next-period forecast when disclosed.
- Financial transaction evidence includes agreement/cap, actual occurrence or balance, pricing basis, maturity when disclosed, relationship, approval, independent-director review, and recusal.
- Related-party conclusions address amount, counterparty concentration, pricing fairness, approval and recusal mechanisms, disclosure, funding safety, and minority-shareholder implications; they are not generic.
- Wind/financial-terminal data used for profiles, holdings, metrics, or discovery is cross-checked against annual reports and announcements for people, nomination sources, transaction terms, counterparties, and effective dates.
- The PDF uses a compact A4 research-note layout with consistent title, chapter styles, tables, charts, headers, and footers. Multi-page tables repeat headers and remain readable.
- Every PDF page is rendered and visually inspected. There are no orphan headings, chart/subtitle overlaps, clipped text, stranded table headers, large unexplained blank areas, or missing source/final-verification content.

## Final Risk Language

- Low governance risk: dispersed or balanced control, clean history, strong board checks, transparent disclosure, aligned incentives.
- Medium governance risk: concentrated founder/family control with clean history but limited external checks or succession clarity.
- High governance risk: control disputes, pledges/freeze pressure, related-party abuse, penalties, funds occupation, illegal guarantees, weak controls, or repeated disclosure issues.

## Institutional Investor Stewardship

- Add a section titled "机构投资者尽责管理关注点" after governance analysis and before sources.
- Use a small table with 3-5 rows, not a long prose section.
- Recommended columns: "关注点", "与公司发展和财务基本面的关系", "尽责管理动作", and "需跟踪信号".
- Focus on institutional investor stewardship actions such as engagement, voting, escalation, disclosure requests, ESG/governance risk monitoring, related-party transaction review, capital allocation discipline, and remediation tracking.
- Tie each row to the specific company's development stage and financial fundamentals: growth drivers, margins, capex, M&A, leverage, cash flow, working capital, customer/supplier concentration, supply-chain resilience, related transactions, dividends/buybacks, or ROIC.
- Internally verify the stewardship table against collected sources. If the verification process reveals a weak or unsupported point, revise or remove it before delivery. Do not include the stewardship verification process in the report.

## Internal Verification

- Check that company name, ticker, market, reporting year, and "as of" date are correct.
- Check that the business description matches annual report and company website wording.
- Check whether a standalone ESG/sustainability/social responsibility report exists; if not, say the search did not show one.
- Check ESG metrics, environmental penalties, certifications, carbon/energy data, employee/safety data, supplier practices, and governance claims against sources.
- Check shareholder percentages, actual controller, family relationships, pledges/freezes, management titles, and recent board changes against the latest filings.
- Check whether regulatory penalties, exchange inquiry letters, lawsuits, funds occupation, illegal guarantees, and auditor opinions are current and accurately framed.
- Rewrite or qualify any sentence that cannot be sourced. Do not leave a known error in the final answer.
- For integrated reports, confirm chapter `一、ESG分析` is followed by governance chapters `二` through `十`. For governance-only reports, confirm ESG content is absent and governance chapters run from `一` through `九`.
- Confirm the report includes a visible table titled "数据来源" after the institutional-investor stewardship table.
- Do not add a visible verification section. Add only this exact final sentence at the end of the report: "报告内容已基于公开资料完成二次核验。".
