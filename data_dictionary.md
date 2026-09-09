# Data Dictionary — `simulated_consumer_survey.csv`

> **SIMULATED DATA — FOR PORTFOLIO DEMONSTRATION ONLY.**
> This dataset was generated programmatically to demonstrate analytical method. It is *not* real survey data. Distributions were chosen to be directionally realistic (e.g. efficacy outranking sustainability as the top purchase driver, skepticism skewed in claim-trust scores) based on publicly documented consumer sustainability research patterns — not on any proprietary survey results.

**Rows:** 180 simulated respondents
**Grain:** One row per respondent

| Column | Type | Description | Values |
|---|---|---|---|
| `respondent_id` | string | Anonymous respondent identifier | R001–R180 |
| `age_band` | categorical | Respondent age band | 18-24, 25-34, 35-45 |
| `gender` | categorical | Self-reported gender | Female, Male, Non-binary/Prefer not to say |
| `skin_type` | categorical | Self-reported general skin type | Oily, Dry, Combination, Sensitive, Normal |
| `primary_skin_concern` | categorical | Main skin concern respondent is trying to address | Dryness/dehydration, Breakouts/acne, Redness/sensitivity, Dullness/uneven tone, Signs of aging, Large pores |
| `monthly_skincare_budget` | categorical (ordinal) | Self-reported typical monthly skincare spend | <$20/mo … $120+/mo |
| `primary_purchase_channel` | categorical | Where respondent most often buys skincare | Brand website (DTC), Marketplace, In-store/pharmacy, Department store/Sephora-type |
| `preferred_texture` | categorical | Preferred product texture | Gel, Cream, Lotion, Balm, Oil |
| `sustainability_claim_trust_1to5` | ordinal (1–5) | How much respondent trusts sustainability claims made by skincare brands in general | 1 = very low trust, 5 = very high trust |
| `stopped_use_due_to_exaggerated_claim` | boolean (Yes/No) | Whether respondent has stopped using a product due to a claim feeling exaggerated/misleading | Yes, No |
| `willingness_to_pay_premium` | categorical (ordinal) | How much premium respondent would pay for credible sustainability credentials | No premium … Large premium (25%+) |
| `preferred_packaging` | categorical | Preferred packaging format | Tube, Pump, Jar, Other |
| `top_ranked_purchase_driver` | categorical | The single purchase driver respondent ranked #1 out of 5 (Efficacy, Price, Ingredient safety/transparency, Brand reputation, Sustainability) | see Section C1 of questionnaire |

## Generation Notes (for transparency)

The simulated dataset was generated with fixed random seed (`42`) using weighted random sampling per field, so results are reproducible. Weights were set to reflect directionally realistic patterns commonly reported in public consumer sustainability research (e.g., Nielsen/McKinsey consumer sustainability surveys), specifically:

- Efficacy is the most commonly top-ranked purchase driver, ahead of sustainability
- Sustainability-claim trust is skewed toward low/moderate rather than high
- Willingness to pay a *large* premium for sustainability is a minority position

This is intentional — it lets the analysis in `analysis/consumer_analysis.md` demonstrate realistic, non-trivial insight generation rather than confirming an obvious or flattering conclusion.
