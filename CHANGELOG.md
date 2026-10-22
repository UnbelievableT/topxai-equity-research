# Changelog

## 1.1.0 (2026-10-23)

A new report form, after reading a 54-page investigative report next to our own deep dives.

- `references/investigative.md`: the claim and its value bridge, where new facts hide beyond the 10-Q, letting the
  company's own words line up (or not), times and places, taking apart management's account, how far inference may go,
  and what not to copy.
- Kickoff gate: a falsifiable claim with a per-share figure, a value bridge and at least three new facts, or no report.
- Research: `records` and `statements` lanes; every fact is recorded with its verbatim text and location.
- Writing: ordered by the argument instead of sixteen topic chapters; Markdown footnotes to the page with a URL and the
  grade at the end; screenshots of original documents with a red box; body capped at 15,000 words; no internal codes in
  the text; full-coverage findings move to an appendix table.
- Audit: a verifiability lane that opens 30 footnotes and every exhibit source; the skeptic checks that all scenarios use
  one discounting timing convention.
- Hard rules 1 and 2 revised, 13 and 14 added. Quality bar, judgment, templates and agents updated.
- New tools: `check_report.py` (standard library) and `exhibit.py` (needs PyMuPDF; HTML filings need a local Chrome).

## 1.0.0 (2026-10-13)

First public release.

- Skill `topxai-equity-research`: twelve hard rules, a ten-stage pipeline with outputs and exit gates, the research
  method (framework, tradable judgment, nine-step flows for equity, industry and macro), quality bar, indicator and
  data-source library, pitfall catalogue, coverage watch and settlement, agent roster and brief templates.
- Agents: `research-collector`, `research-bull`, `research-bear`, `research-auditor`, `research-translator`.
- Tools (Python 3.9+, standard library): `sec.py`, `ledger.py`, `desk.py`, `check_skill.py`.
- Templates: kickoff, source cross-check, writing contract, audit decisions, final checks, ledger entries, watch entry,
  and a disclosure template.
