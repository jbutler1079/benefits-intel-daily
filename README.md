# benefits-intel-daily

Automated daily research digest on the self-funded health plan, employee
benefits, and healthcare cost/pricing landscape — built to feed social
media content for Butler Benefits and the HPHP go-to-market effort.

## How it works
A Claude Code Cloud task runs daily against this repo, following the
instructions in [`CLAUDE.md`](./CLAUDE.md):

1. Research CMS price transparency data, KFF surveys, BLS healthcare
   CPI, state APCD releases, and actuarial/consulting studies
   (Mercer, Aon, WTW, Milliman).
2. Write the day's findings to `/reports/YYYY-MM-DD.md`.
3. Commit and push.

No email delivery — check `/reports/` directly, or watch this repo on
GitHub mobile for push notifications on new commits.

## Structure
```
CLAUDE.md          — agent operating instructions (source list, format, rules)
reports/            — one markdown file per day's findings
```

## Setup
1. Add the Gmail/Outlook step back into `CLAUDE.md` later if delivery
   preferences change.
2. In Claude Code Desktop: Schedule → New task → Cloud task → point at
   this repo → daily cadence.
3. Run once manually before trusting the schedule, to confirm the
   agent is pulling from the named sources rather than generic news.
