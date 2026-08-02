# Daily Healthcare Benefits Research Agent

## Purpose
Run deep research on the self-funded health plan, employee benefits, and
healthcare cost/pricing landscape for Butler Benefits and the HPHP
(High Plains Health Plan) go-to-market effort. Output feeds social media
content, so prioritize data-backed, citable findings over general news.

## Research sources (in priority order)
1. CMS Hospital/Payer Price Transparency files and analyses built on them
2. KFF (Kaiser Family Foundation) employer health benefits survey data
   and research briefs
3. BLS healthcare cost / CPI data (medical care component)
4. State All-Payer Claims Database (APCD) releases — Texas and
   comparable states
5. Direct contracting, reference-based pricing, and unbundled TPA
   studies from actuarial/consulting firms (Mercer, Aon, WTW, Milliman)
6. Peer-reviewed or working-paper research on self-funded plan
   performance, stop-loss trends, site-of-care cost variation
7. NAIC and state insurance department filings relevant to
   self-funded/ERISA plans

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
2. Write today's findings to `/reports/YYYY-MM-DD.md` using the template
   below. Commit and push this file with commit message
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
  report rather than padding with weak items.
