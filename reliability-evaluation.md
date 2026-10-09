# Reliability Evaluation

| Insight | Source quality | Cross-source consistency | Timeliness | Confidence | Limitations and risks |
|---|---|---|---|---|---|
| 97.0% delivered and 0.6% canceled | High for the historical dataset | Needs current logistics comparison | Low to medium because data ends in 2018 | Medium | Marketplace and category mix may have changed; status is not the same as delivery quality or profitability. |
| Revenue concentration in five categories | High for item/category arithmetic | Needs current market and competitor validation | Low to medium | Medium | Item price is not net revenue, margin, or market share; missing currency and current demand context. |
| 1.14 items per order | High for the dataset tables | Needs behavioral and current-market validation | Low to medium | Medium | Does not explain customer motivation, shipping economics, or repeat purchase. |
| Pilot is preferable to broad launch | Medium, because it is an interpretation | Consistent with the historical concentration and uncertainty | Medium | Medium | Requires current pricing, legal, tax, logistics, and unit-economics research. |
| Historical evidence is useful for direction, not forecasting | High for historical completeness | Consistent with external e-commerce research on market evolution | Low for current applicability (data ends in 2018) | Medium | Past marketplace activity does not guarantee 2026 performance; current local logistics and competitor data are missing. |

## Concrete limitations and risks
1. The Kaggle data is historical and ends in October 2018; it cannot establish current Brazilian demand.
2. The dataset represents one marketplace context and may not represent NovaTech's customer segment or operating model.
3. Item price is not contribution margin; shipping, returns, taxes, seller fees, and marketing costs are not fully modeled here.
4. External research may be affected by publication bias, vendor incentives, or inconsistent definitions of market size.
5. Category totals are directional signals, not a forecast or proof of causal demand.

## Validation plan
Before committing to a launch:
- refresh competitor and price evidence using current Quick Research outputs
- validate delivery and return economics with local logistics partners
- test category-level margins and repeat purchase
- define a pilot stop rule based on contribution margin, delivery completion, and customer experience
