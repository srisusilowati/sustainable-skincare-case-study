# Research Methodology

## 1. Purpose

This document describes the research design used to answer the core business question defined in the project README: *whether sustainability should be the brand's primary positioning pillar or a secondary differentiator behind a stronger primary driver.*

## 2. Research Design

**Type:** Quantitative-led, single-wave cross-sectional survey with a small qualitative (open-ended) component for context.

**Rationale for a survey approach:** At the pre-launch stage, the business needed breadth (patterns across a meaningful sample of the target demographic) more than depth. A structured survey allows purchase-driver ranking and attitude measurement to be compared across demographic subgroups — which a small number of qualitative interviews would not support statistically.

## 3. Target Respondents

- Adults aged 18–45
- Purchase skincare products at least occasionally (self-reported)
- `[INSERT ACTUAL TARGET MARKET / GEOGRAPHY]`
- `[INSERT ACTUAL SAMPLE SIZE]`

## 4. Recruitment & Distribution

`[INSERT ACTUAL RECRUITMENT CHANNELS — e.g. online consumer panel, relevant interest communities, paid panel service]`

Distribution notes worth documenting for a portfolio audience:
- Organic distribution through unmoderated community posting is unreliable — several general-interest and niche subreddits/forums have automated filters or moderator policies against survey links, which affected actual response collection timelines.
- Paid panel services (e.g. Pollfish-style platforms) are a viable fallback when organic community distribution underperforms, at a cost premium per completed response.

## 5. Instrument Design Principles

- Kept to 15–20 questions / 5–7 minutes to minimize drop-off
- Skip logic used to route respondents past irrelevant questions (e.g. skin-type-specific follow-ups)
- Purchase-driver importance measured via **ranking**, not independent Likert ratings, to force trade-off thinking rather than letting respondents rate everything as "important"
- One open-ended question retained to surface unprompted frustrations/language, useful for messaging development later

Full question list: [`questionnaire_structure.md`](questionnaire_structure.md)

## 6. Data Cleaning Approach

1. Remove incomplete submissions
2. Remove responses completed implausibly fast (straight-lining / speed-running indicator)
3. Deduplicate by response fingerprint (IP/session, where available)
4. Standardize free-text demographic fields into fixed categories
5. Thematically code open-ended responses into a small set of recurring categories (inter-rater check recommended if coded by more than one person)

## 7. Analysis Approach

- Descriptive statistics (frequencies, percentages) for all closed-ended questions
- Cross-tabulation of purchase drivers against demographic and skin-concern segments
- Simple segmentation based on combined purchase-driver ranking + willingness-to-pay pattern
- Thematic summary of open-ended responses, used to add qualitative color to quantitative findings, not as a standalone conclusion

## 8. Known Limitations of This Method

See [`README.md § Limitations`](../README.md#10-limitations) for the full list. The most important one for interpreting this research: **self-reported purchase intent, especially around sustainability, tends to overstate actual purchase behavior** — a well-documented "attitude-behavior gap" in sustainable consumption research. Findings here should inform hypotheses to validate against actual purchase/conversion data post-launch, not be treated as final proof of demand.
