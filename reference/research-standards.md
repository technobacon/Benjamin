# Franklin — Research and Accuracy Standard

## Purpose

Finance and economics reward false precision. A clean number can hide a revised series, incompatible definitions, a changed denominator, or a model assumption doing most of the work. Research for Franklin must preserve enough context for the claim to remain true after it becomes narration.

## Source hierarchy

Prefer the closest available source to the underlying evidence.

1. **Primary official material** — legislation, central-bank releases and databases, statistical agencies, regulators, court records, parliamentary or congressional reports, company filings, audited reports, exchange data, original policy documents.
2. **Original research** — peer-reviewed papers, working papers from established institutions, authors' datasets and methodology, BIS/IMF/OECD/World Bank research where appropriate.
3. **High-quality contemporary reporting** — useful for chronology, interviews, and what participants knew at the time. Corroborate important factual claims.
4. **Serious secondary histories and textbooks** — useful for synthesis and contested interpretations.
5. **Tertiary summaries** — discovery only. Follow their citations before scripting.

A prestigious logo does not make every claim primary. Identify what the source directly observed, calculated, or repeated from elsewhere.

## Claim ledger

Before drafting, record every material claim in `research/source-ledger.md` with:

- exact wording of the claim;
- claim type: fact, reported figure, calculation, interpretation, or forecast;
- unit, currency, denominator, geography, relevant period, and price basis;
- source title, publisher, link, publication date, and access date;
- page, table, series code, filing section, or timestamp where possible;
- verification status and any caveat.

One source may support several claims, but each claim needs a precise location.

## Numerical checks

For every important number:

- preserve the original unit and convert explicitly;
- state whether the value is nominal, real, indexed, seasonally adjusted, annualized, or present-valued;
- identify whether a rate is a level, change, percentage, percentage point, or basis-point move;
- identify the time window and observation frequency;
- state the denominator for ratios and per-capita measures;
- distinguish market value, face value, notional value, exposure, revenue, profit, and cash flow;
- reproduce calculations with visible inputs and formula;
- sanity-check order of magnitude and reconcile totals where possible;
- do not add rounded components and present the result as exact.

If currency conversion matters, record the FX rate, date, convention, and whether the comparison should instead remain in local or real terms.

## Economic data

- Record the series code and vintage when revisions could matter.
- Do not compare nominal values across long periods without explaining inflation.
- Check changes in methodology, country boundaries, index baskets, or classifications.
- Do not infer household experience from an aggregate average without identifying distributional limits.
- Distinguish correlation, timing, mechanism, and causal identification.
- When citing “consensus,” define whose consensus and how it was measured.

## Market and security data

- Specify instrument, issuer, seniority, currency, maturity, coupon or reference rate, clean versus dirty price, and date where relevant.
- Distinguish yield, yield spread, credit spread, discount margin, option-adjusted spread, and CDS spread.
- State the compounding convention, day-count basis, settlement assumption, curve, and recovery assumption when they affect a calculation.
- Do not compare prices or spreads taken at different timestamps as though they were simultaneous.
- Treat vendor data and consensus marks as observations with methodology, not unquestionable truth.

## Historical events

Build the chronology from dated sources, then test the causal story separately.

- What did each actor know at the time?
- What options were available?
- Which constraint changed?
- What evidence connects action A to outcome B?
- Which alternative explanation has serious support?
- Is a later account correcting the record or rewriting motives with hindsight?

Avoid single-villain explanations for systemic events unless the evidence genuinely supports one.

## Quotations

- Verify against the original transcript, document, recording, or archival scan.
- Preserve enough surrounding context to avoid reversing the speaker's meaning.
- Mark paraphrases as paraphrases in notes.
- Keep on-screen quotations short and attach the source and date.
- Never fabricate a reconstruction in quotation marks.

## Forecasts, estimates, and model outputs

- Label them as estimates or scenarios.
- State the model owner, publication date, assumptions, and uncertainty range.
- Do not turn a central estimate into a prediction of what will happen.
- Explain sensitivity when one assumption drives the result.
- Compare forecasts with base rates or prior forecast errors where relevant.

## Current-information rule

Market prices, laws, policies, officeholders, data releases, company figures, product terms, and academic debates can change. Verify them at the time of research. Put a clear information cutoff in the dossier and script metadata.

## Professional-information firewall

Research and scripts must rely exclusively on public sources. Do not include or allude to:

- employer systems, reports, models, methodology, controls, or internal terminology;
- client identities, positions, trades, communications, or valuation disputes;
- non-public prices, marks, estimates, transactions, or market colour;
- information remembered from restricted documents;
- details altered just enough to appear anonymous.

If a useful example originates from professional experience, replace it with a fully public case supported from scratch. When in doubt, omit it.

## Research handoff

End every dossier with:

- **Verified:** claims supported strongly enough to script.
- **Contested:** claims with serious competing interpretations.
- **Unresolved:** missing or weak evidence.
- **Do not say:** tempting formulations that overstate the evidence.
- **Freshness cutoff:** the latest date on which time-sensitive facts were checked.

