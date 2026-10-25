# Decision framework

FairNest separates raw evidence from the preference model.

## Raw evidence
Displayed independently of ranking:
- weekly rent;
- contract weeks;
- total contract cost;
- known booking cash;
- bills;
- room type;
- commute;
- agreement context;
- source links;
- evidence-check date;
- missing fields.

## Preference model
Users control the relative weight assigned to:
- recurring cost;
- upfront/booking cash;
- commute;
- evidence completeness.

## Governance rules
- Missing information is not silently treated as zero.
- Paid provider status is not a scoring input.
- Protected characteristics are not ranking inputs.
- Agreement context is identified before legal prompts.
- Fit Score is not presented as a safety or quality certificate.

This structure prevents the score from replacing the evidence it summarises.
