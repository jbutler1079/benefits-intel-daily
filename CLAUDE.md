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
