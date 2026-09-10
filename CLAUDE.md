# Daily Healthcare Benefits Research Agent

## Purpose
Run deep research on the self-funded health plan, employee benefits, and
healthcare cost/pricing landscape for Butler Benefits and the HPHP
(High Plains Health Plan) go-to-market effort. Output feeds social media
content, so prioritize data-backed, citable findings over general news.

## Research sources (in priority order)

### Core pricing and cost datasets
1. CMS Hospital/Payer Price Transparency files and analyses built on them
2. RAND Corporation Hospital Price Transparency studies — especially Prices Paid to Hospitals by Private Health Plans work comparing commercial payments to Medicare
3. NASHP Hospital Cost Tool — examines hospital operating costs, margins, commercial breakeven levels, and payments relative to cost for 4,500+ hospitals
4. CMS Medicare Cost Reports — hospital cost-report data for analyzing revenue, expenses, uncompensated care, payer mix, margins, and cost-to-charge relationships
5. KFF (Kaiser Family Foundation) employer health benefits survey data and research briefs
6. Peterson-KFF Health System Tracker — employer-sponsored insurance, healthcare prices, utilization, premiums, deductibles, national health spending, and household burden
7. BLS healthcare cost / CPI data (medical care component)
8. State All-Payer Claims Database (APCD) releases — Texas and comparable states
9. Health Care Cost Institute (HCCI) — commercial claims-based research on employer-sponsored populations, including annual Health Care Cost and Utilization Report
10. HCCI Healthy Marketplace Index — connects local healthcare spending and prices with hospital market concentration

### Research and analysis
11. Direct contracting, reference-based pricing, and unbundled TPA studies from actuarial/consulting firms (Mercer, Aon, WTW, Milliman)
12. Peer-reviewed or working-paper research on self-funded plan performance, stop-loss trends, site-of-care cost variation
13. Academic health-economics sources — Health Affairs, NBER, JAMA Health Forum, NEJM Catalyst, American Economic Review/AER Insights, university health-policy centers (focus on commercial hospital pricing, physician consolidation, vertical integration, site-neutral payments, private-equity ownership, employer insurance, PBMs)
14. MedPAC — annual Data Book and reports to Congress covering provider economics, hospital margins, site-of-care differences, physician reimbursement, drug spending, Medicare Advantage, and payment policy

### Regulatory and compliance
15. U.S. Department of Labor / Employee Benefits Security Administration (EBSA) — ERISA fiduciary duties, CAA compliance, fee disclosure, health plan administration, employer responsibilities
16. DOL/HHS/Treasury Transparency in Coverage and CAA implementation guidance — regulatory FAQs and enforcement guidance on data access, gag clauses, transparency, fiduciary oversight
17. NAIC and state insurance department filings relevant to self-funded/ERISA plans
18. Federal Trade Commission PBM studies, enforcement actions, and reports — vertical integration, specialty pharmacy, spread pricing, rebates, affiliated pharmacies, conflicts of interest
19. Congressional Budget Office (CBO) and Congressional Research Service (CRS) — healthcare costs in broader economic/policy context, employer-sponsored coverage, tax treatment, prescription-drug policy, consolidation

### Employer and purchaser perspectives
20. Employee Benefit Research Institute (EBRI) — self-insurance adoption, ERISA, employer-sponsored coverage, plan design, employee contributions, benefit trends, self-insured coverage by employer size
21. Business Group on Health employer surveys — what sophisticated employers are actually doing, medical trend, pharmacy, GLP-1s, plan design, delivery-system reform, chronic conditions
22. Purchaser Business Group on Health (PBGH) — price transparency, direct purchasing, PBM contracting standards, fiduciary responsibility, provider accountability, healthcare affordability, and explicit PBM purchasing standards
23. State employee health plans and public purchaser reports — CalPERS, Montana, Indiana, North Carolina, Washington, etc. for contracting strategies, reference-based pricing, centers of excellence, direct contracting, pharmacy procurement, hospital negotiations
24. Sage Transparency / Employers' Forum of Indiana — hospital price, quality, and cost information dashboards
25. HCCI Employer Health Claims Collaborative and regional employer coalitions — what commercial employers actually paid

### Specialized topics
26. Government Accountability Office (GAO) healthcare reports — PBMs, prescription drugs, healthcare consolidation, federal employee plans, price transparency, benefit administration
27. Hospital audited financial statements, municipal bond disclosures (EMMA), and IRS Form 990s — nonprofit hospital systems revealing executive compensation, investment income, cash reserves, debt, margins, charity care, acquisitions
28. Healthcare market-concentration research — FTC, DOJ, HCCI, academic economists, state AG reports on hospital mergers, physician-practice acquisitions, vertical integration
29. PBM purchasing standards and contract-model resources — PBGH, National Alliance of Healthcare Purchaser Coalitions, employer coalitions, independent pharmacy-benefit researchers for pass-through contracts, rebate guarantees, specialty-pharmacy requirements, audit rights, data ownership, formulary conflicts
30. Quality and outcomes datasets — CMS Care Compare, Leapfrog, AHRQ, NCQA for value conversations beyond price alone
31. FDA drug approvals, Orange Book/Purple Book, and drug shortage data — specialty-drug launches, biosimilars, GLP-1 developments, gene therapies, indication expansions, patent expirations, lower-cost alternatives
32. Drug Channels Institute and Adam Fein — deep-dive research on pharmaceutical supply chain, PBM economics, specialty pharmacy trends, drug pricing, biosimilar adoption, and wholesale/retail pharmacy business models
33. Transparent RX (Tyrone Squires) — independent pharmacy benefit analysis, PBM contracting transparency, pharmacy margins, spread pricing, and advocacy around fair PBM compensation models

Skip generic news coverage unless it's reporting on a specific new
dataset or study.

## For each finding, extract
- The underlying dataset or study (source, sample size/methodology, date)
- The specific number(s) that stand out — a citable stat, not a vibe
- Why it matters for employers evaluating self-funded/direct-contracting
  models
- Whether it ties to unbundled/direct-contracting positioning or
  TX-APCD data gaps specifically — flag these prominently

## Daily task steps
1. Research using the source priority list above. Aim for 3-5 findings,
   ranked by how compelling/counterintuitive the data point is.
2. Write today's findings to `/reports/YYYY-MM-DD.md` using the report
   template below.
3. Generate finished content from those same findings into
   `/content/YYYY-MM-DD/` — one file per channel (`social.md`,
   `blog.md`, `email.md`) using the content templates below. Derive
   everything from the day's report so it stays citable; never invent
   stats that aren't in the report.
4. Commit and push the report and content together with commit message
   "Daily research — [date]".

## Report template (per finding)
```
### [Headline stat or finding]
- **Source:** [org, study/dataset name, date]
- **Methodology/sample:** [brief]
- **The number:** [specific citable stat]
- **Why it matters:** [1-2 sentences, employer/self-funded lens]
- **Social angle:** [suggested post format — chart, thread, LinkedIn take]
```

## Notes
- Prefer primary sources (agency data, published studies) over
  aggregator commentary or press releases about press releases.
- If a day turns up nothing meeting the bar, say so explicitly in the
  report rather than padding with weak items. On a thin day, keep the
  content light too — don't manufacture posts around weak findings.

## Content templates

All content is derived from that day's report. Every stat must trace back
to a finding in `/reports/YYYY-MM-DD.md`. Treat output as review drafts,
not publish-ready: include a note to verify figures against the source
and route through compliance (this is regulated benefits/insurance
content). Flag unbundled/direct-contracting and TX-APCD angles
prominently in the content, just as in the report.

### `content/YYYY-MM-DD/social.md`
- One post per finding (LinkedIn or X). Lead with the number/hook, keep
  it tight, and reuse the finding's "Social angle" note.
- For each post include: the platform, the stat with its source, a
  one-line chart description, and 3–4 hashtags.

### `content/YYYY-MM-DD/blog.md`
- One 600–900 word piece synthesizing the day's 3–5 findings into a
  single narrative through the Butler Benefits / HPHP direct-contracting
  lens. Preserve source citations inline. Close with a through-line that
  ties the findings together.

### `content/YYYY-MM-DD/email.md`
- One short digest for a benefits-buyer audience (CFO/HR finance).
- Include: 2–3 subject-line options, preview text, a scannable summary
  of each finding (1–2 sentences), a through-line, and a CTA.
