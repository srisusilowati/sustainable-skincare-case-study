# Sustainable Skincare Consumer Research & Business Strategy Case Study

> A business analyst case study exploring consumer purchasing behavior in the sustainable skincare category, using a real early-stage direct-to-consumer (DTC) skincare venture as the underlying context.

**Skills demonstrated:** Market Research · Consumer Research · Data Analysis · Business Analysis · Strategic Thinking · SWOT Analysis · Competitor Analysis · Business Strategy · Data Visualization · Business Communication

---

## ⚠️ A note on data in this repository

This repository is a **public-portfolio adaptation** of research and strategy work I conducted for an early-stage sustainable skincare brand. To protect confidential and proprietary information (product formulation, supplier details, pricing, exact business plan, and unreleased strategy), this version:

- Uses **simulated data** for the consumer dataset, clearly labeled `SIMULATED DATA — FOR PORTFOLIO DEMONSTRATION ONLY`
- Uses **placeholders** (e.g. `[INSERT ACTUAL SAMPLE SIZE]`) where real figures cannot be disclosed
- Describes the **methodology and analytical framework** I actually used, without revealing the underlying business's confidential details
- Anonymizes the brand as **"the Client Brand"** where the real brand identity isn't relevant to demonstrating the skill

The analytical *process* — how a business question becomes a research design, a dataset, an insight, and a strategic recommendation — is real. The *specific numbers and confidential business content* are not.

---

## 1. Project Overview

This project simulates the analytical workflow of a business analyst supporting an early-stage sustainable skincare brand preparing to enter the Australian direct-to-consumer market. The brand's positioning centers on a novel, dermatologically-focused hero ingredient and a transparency-first sustainability narrative — a positioning choice that itself needed to be tested against real consumer attitudes rather than assumed.

The case study walks through a full research-to-strategy cycle: defining the business problem, designing a consumer research instrument, structuring and analyzing the resulting data, and translating findings into concrete, prioritized strategic recommendations.

## 2. Business Problem

Entering a category as crowded and skepticism-prone as "sustainable skincare" carries real risk: consumers increasingly distrust sustainability claims (a phenomenon widely documented as "greenwashing fatigue"), and effectiveness, not ethics, is usually the primary purchase driver. Before committing capital to formulation, packaging, and go-to-market spend, the business needed evidence-based answers to:

- What do consumers actually value when purchasing sustainable skincare — sustainability itself, or something else that sustainability needs to be paired with?
- What factors most strongly influence skincare purchasing decisions (efficacy, price, brand trust, ingredient transparency, sustainability)?
- How credible do consumers find sustainability claims from skincare brands in general, and what would make a new brand's claims more believable?
- What underserved need or market gap exists for a new entrant, and what should its strategic emphasis be as a result?

## 3. Research Objective

The research objective was to generate a defensible, data-informed answer to: *"Should this brand lead with sustainability as its core value proposition, or treat sustainability as a supporting differentiator behind a stronger primary driver (e.g. efficacy, safety, transparency)?"*

This is a decision-relevant question, not an academic one — the answer directly shapes brand positioning, messaging hierarchy, and marketing budget allocation before launch. The research was designed to be actionable: every question in the instrument maps to a specific downstream business decision (positioning, pricing tier, packaging, channel choice).

## 4. Research Methodology

**Target respondents:** Adult consumers (18–45) who purchase skincare products at least occasionally, recruited via online consumer panels and relevant online communities. `[INSERT ACTUAL SAMPLE SIZE AND RECRUITMENT CHANNELS]`

**Survey approach:** A structured, self-administered online questionnaire (~15–20 questions, ~5–7 minutes to complete) combining closed-ended (Likert scale, ranking, single/multiple choice) and a small number of open-ended questions to capture qualitative nuance.

**Variables examined:**
- Demographics (age band, gender, general skin type)
- Current skincare purchasing habits (budget range, purchase frequency, primary purchase channel)
- Purchase driver ranking (efficacy, price, ingredient safety/transparency, brand reputation, sustainability)
- Attitudes toward sustainability claims (trust level, past experience with misleading claims, willingness to pay a premium)
- Product preference attributes (texture, key active ingredients of interest, packaging format)
- Open-ended: biggest frustration with current skincare products

**Data collection:** Online form distribution (see [`research/methodology.md`](research/methodology.md) for full instrument design and distribution notes).

**Data cleaning:** Removal of incomplete responses, speed-run/straight-line responses, and duplicate submissions; standardization of categorical fields; recoding of open-ended responses into thematic categories for analysis.

**Analysis approach:** Descriptive statistics (frequency distributions, cross-tabulations) for quantitative variables; thematic coding for open-ended responses; segmentation based on combined purchase-driver and demographic patterns.

Full methodology detail: [`research/methodology.md`](research/methodology.md)
Questionnaire structure: [`research/questionnaire_structure.md`](research/questionnaire_structure.md)

## 5. Data Analysis

The simulated dataset (`data/simulated_consumer_survey.csv`, data dictionary in `data/data_dictionary.md`) is analyzed across five dimensions:

- **Consumer preferences** — most-desired product attributes and formats
- **Purchase drivers** — ranked importance of efficacy, price, transparency, brand, sustainability
- **Sustainability perceptions** — trust levels and prior negative experiences with sustainability claims
- **Price sensitivity** — willingness to pay a premium for sustainable formulation, by segment
- **Demographic segmentation** — how the above vary by age band and skin concern

Full analysis with tables and charts: [`analysis/consumer_analysis.md`](analysis/consumer_analysis.md) and [`analysis/segmentation.md`](analysis/segmentation.md)

*(Supporting charts are in [`visuals/`](visuals/).)*

## 6. Key Insights

Rather than reporting raw statistics, findings are translated into business-relevant insight. Example (illustrative, based on simulated data):

> Consumers show measurable interest in sustainable packaging, but rank it below efficacy and ingredient safety as a *primary* purchase driver. This suggests sustainability functions best as a **differentiator layered on top of a strong efficacy claim**, not as a standalone value proposition — a brand that leads with sustainability alone risks being perceived as prioritizing values over performance, which the data suggests is a trust risk in this category.

The full set of insights, each explicitly tracing **Research → Data → Insight → Business Decision**, is in [`analysis/consumer_analysis.md`](analysis/consumer_analysis.md) and [`strategy/strategic_recommendations.md`](strategy/strategic_recommendations.md).

## 7. Competitive Analysis

A structured competitive framework benchmarking publicly known skincare brands on sustainability communication, price positioning, and transparency — built entirely from public information (brand websites, published sustainability reports, third-party audits), with sources cited. See [`strategy/competitive_analysis.md`](strategy/competitive_analysis.md).

## 8. SWOT Analysis

A SWOT analysis for a hypothetical new entrant in the sustainable skincare category, built from publicly available category dynamics rather than the Client Brand's confidential internal plan. See [`strategy/swot_analysis.md`](strategy/swot_analysis.md).

## 9. Strategic Recommendations

Prioritized recommendations connecting research findings to concrete business actions (positioning emphasis, messaging hierarchy, pricing tier signal, and go-to-market sequencing), each with its supporting rationale. See [`strategy/strategic_recommendations.md`](strategy/strategic_recommendations.md).

## 10. Limitations

- The dataset used in this public repository is **simulated**, not the brand's real survey data — findings here are illustrative of analytical method, not literal business conclusions.
- Even where the underlying real research existed, self-reported purchase-intent surveys are known to overstate actual purchasing behavior ("attitude-behavior gap"), especially for sustainability claims.
- Sample recruited via online panels/communities may skew toward more digitally engaged, sustainability-aware consumers relative to the general population.
- Competitive analysis is limited to publicly disclosed information; private strategic details of competitor brands are not accessible.

## 11. Skills Demonstrated

| Skill | Where demonstrated |
|---|---|
| Market Research | `research/methodology.md` |
| Consumer Research | `research/questionnaire_structure.md`, `data/` |
| Data Analysis | `analysis/consumer_analysis.md`, `analysis/segmentation.md` |
| Business Analysis | Full research → insight → decision chain throughout |
| Strategic Thinking | `strategy/strategic_recommendations.md` |
| SWOT Analysis | `strategy/swot_analysis.md` |
| Competitor Analysis | `strategy/competitive_analysis.md` |
| Business Strategy | `strategy/` folder overall |
| Data Visualization | `visuals/` |
| Business Communication | This README; insight framing throughout |

---

## Repository Structure

```
sustainable-skincare-case-study/
├── README.md
├── research/
│   ├── methodology.md
│   └── questionnaire_structure.md
├── data/
│   ├── simulated_consumer_survey.csv
│   └── data_dictionary.md
├── analysis/
│   ├── consumer_analysis.md
│   └── segmentation.md
├── strategy/
│   ├── competitive_analysis.md
│   ├── swot_analysis.md
│   └── strategic_recommendations.md
└── visuals/
    ├── purchase_drivers.png
    ├── sustainability_trust.png
    └── segment_breakdown.png
```

---

## About This Project

This case study was independently developed as a demonstration of end-to-end business analyst capability — from problem framing through to strategic recommendation — using an early-stage business context as a realistic anchor while protecting that business's confidential information.

**Author:** `[INSERT YOUR NAME]`
**Contact:** `[INSERT EMAIL / LINKEDIN]`
