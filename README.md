# RICH OR DIE. RECEIPTS

Daily TQQQ/SQQQ picks, paper-trading results, and verification records.

We keep receipts. Especially the ugly ones.

## What belongs here

This is the public record archive for RICH OR DIE., not the application source repository.

- Daily MACHINE choices and finalized MOB choices.
- Simulated open-to-close results, with price sources and observation times.
- Supporting publication and independent timestamp evidence, when available.
- Missing, late, failed and corrected records, without hiding the originals.

Private research reports, reviews, algorithm logic, credentials, visitor identifiers and raw databases do not belong here. Market data may be published only when its source permits redistribution.

## The rules

The MACHINE picks TQQQ or SQQQ each US stock-market trading day. Scheduled publication is 09:20 America/New_York. Choices remain hidden before release. Actual release times and delays must be recorded.

We pretend to buy at the regular-session opening price and sell at that session's closing price. No intraday changes. No overnight positions. Early-close sessions use their actual scheduled close.

Returns are simulated, compounded and exclude fees, taxes, spreads and slippage. Provider-reported open and close prices are not promises of achievable fills. This is not investment advice or a guarantee of returns.

MOB voting closes at 09:30 ET. The majority chooses its ETF. A tie or zero votes produces no MOB choice or return. Visitors can see the MACHINE's choice before voting ends, so this is not an independent sentiment survey. MACHINE-versus-MOB comparisons must identify their common eligible trading days.

## Records

Public records use separate directories:

- `predictions/`: dated JSON records of released choices.
- `results/`: dated JSON results referencing the original prediction.
- `receipts/`: public evidence metadata and original RFC 3161 query/response files, when available.
- `corrections/`: additional JSON records referencing an error and its correction.

Only directories containing real records are created. Results and corrections must not overwrite the original prediction. Never backdate a record or invent a prediction to fill a historical gap. A correction must retain its actual creation time.

This initial archive contains no historical prediction or performance data. Automatic publication from the website to this repository is not connected.

## What the evidence proves

Git makes changes inspectable. Its author and committer dates can be set by the person creating a commit; those dates alone do not prove pre-market publication. An operator can also rewrite repository history. Branch protection limits ordinary rewriting but is not independent time evidence.

A valid independent RFC 3161 timestamp can establish that the matching data existed by the authority's signed time. It does not establish that the data was public then. Check the authority's trust chain and the exact payload hash, not a screenshot or a claimed timestamp in JSON.

A successful Git push does not automatically make a record VERIFIED. GitHub's Verified signature badge is not this experiment's verification status. Evidence must be checked against the relevant trading session's opening time; missing or late evidence stays missing or late.

An on-time prediction does not prove the accuracy of its reported prices or returns. Those require their own source checks. Failed and unavailable checks must remain visible.

Reference: [Git commit dates](https://git-scm.com/docs/git-commit#_date_formats), [GitHub branch protection](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches), [RFC 3161](https://www.rfc-editor.org/rfc/rfc3161).
