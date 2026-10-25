# Fit Score methodology

The Fit Score is a transparent preference-fit calculation.

## Components
**Recurring-cost fit**
`min(100, weekly budget / weekly rent × 100)`

**Move-in-cash fit**
`min(100, cash limit / known booking cash × 100)`

Where booking/payment information is incomplete, the interface must show the uncertainty rather than infer a favourable zero.

**Commute fit**
Declines as walking time exceeds the user's preferred commute threshold.

**Evidence completeness**
Represents traceability and coverage of the evidence fields. It is not a safety probability.

## Overall score
`Σ(component score × user weight) / Σ(user weights)`

## Interpretation
A high score means the option better fits the user's stated preferences **within the available evidence**. It does not establish legal compliance, safety, contractual fairness or property quality.
