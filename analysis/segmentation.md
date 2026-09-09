# Segmentation Analysis

> Based on `data/simulated_consumer_survey.csv` — **SIMULATED DATA, n=180.**

## 1. Purchase Driver by Age Band

| Age band | n | Efficacy | Ingredient safety | Price | Brand reputation | Sustainability |
|---|---|---|---|---|---|---|
| 18–24 | 54 | 37% | 30% | 22% | 11% | 0% |
| 25–34 | 84 | 35% | 27% | 24% | 8% | 6% |
| 35–45 | 42 | 38% | 24% | 19% | 5% | 14% |

**Reading:** Efficacy is the top driver across every age band — this is a consistent, robust finding rather than an artifact of one segment. Sustainability, while still a minority driver everywhere, is markedly more relevant to the 35–45 band (14%) than to 18–24 (0%). This runs counter to a common assumption that younger consumers over-index on sustainability; in this simulated dataset, the opposite pattern appears.

## 2. Purchase Driver by Primary Skin Concern

| Skin concern | Efficacy | Notable pattern |
|---|---|---|
| Large pores | 52% | Highest efficacy-dominance of any concern segment |
| Dryness/dehydration | 47% | Efficacy strongly dominant |
| Breakouts/acne | 42% | Efficacy strongly dominant |
| Signs of aging | 35% | More balanced across drivers, sustainability slightly elevated (9%) |
| Dullness/uneven tone | 24% | Most balanced segment; sustainability highest here (16%) |
| Redness/sensitivity | 15% | Lowest efficacy-dominance; brand reputation and safety more relevant |

**Reading:** Consumers with acute, visible concerns (large pores, dryness, breakouts) are the most efficacy-driven — they want a specific problem solved and are least swayed by brand story or sustainability. Consumers focused on dullness/uneven tone or signs of aging show more balanced decision-making, where sustainability plays a comparatively larger (though still secondary) role.

## 3. Sustainability Trust by Age Band

| Age band | Mean trust (1–5 scale) |
|---|---|
| 18–24 | 2.81 |
| 35–45 | 2.62 |
| 25–34 | 2.51 |

**Reading:** Trust in sustainability claims is low-to-moderate across all age bands, with no dramatic generational gap in this simulated dataset — skepticism toward sustainability marketing appears to be a category-wide condition rather than an age-specific one.

## 4. Illustrative Customer Segments

Combining the above patterns, two working segments emerge for messaging and prioritization purposes:

**Segment 1 — "Problem-First Buyers" (largest segment)**
- Skin concern: acute/visible (breakouts, dryness, large pores)
- Primary driver: efficacy, by a wide margin
- Sustainability role: low priority; won't actively reject it, but won't pay for it
- Implication: needs to see specific efficacy proof (before/after, ingredient rationale) before anything else

**Segment 2 — "Values-Aware Buyers" (smaller, higher-value segment)**
- Skin concern: dullness/tone, signs of aging
- Primary driver: more balanced; efficacy still leads but sustainability and brand story carry more weight
- Sustainability role: meaningful secondary differentiator, moderate premium tolerance
- Implication: best-fit segment for sustainability-forward messaging and premium positioning — but still needs efficacy credibility first

**Strategic implication:** A single go-to-market message probably cannot serve both segments equally well. See [`strategy/strategic_recommendations.md`](../strategy/strategic_recommendations.md) for how this shapes messaging sequencing.
