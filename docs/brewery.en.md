# One brewery question, three separate reviews

By Presque.digital · 7 October 2026 · [Français](brewery.fr.md)

“Can this batch be bottled?” should preserve three different questions. This is a fictional evidence workflow, not a compliance checklist or a certified outcome.

| Review | Evidence to connect | Gap to keep visible | Responsible review |
| --- | --- | --- | --- |
| Production readiness | Schedule, batch notes and recorded approval | A planned date cannot establish readiness | Brewer responsible for the batch |
| HACCP and traceability | Checks specified by the brewery's own food-safety plan, ingredient lots and batch links | A missing result cannot be silently marked as passed | Person responsible for food safety |
| Excise records | Brewing register, finished-beer stock and relevant movements | An unreconciled quantity cannot become a verified declaration figure | Person responsible for excise administration |

## Worked example

For a fuller walkthrough and reusable templates, see [Brewery records and review](https://presque.digital/en/resources/brewery-records/) and the [public brewery toolkit](../toolkit/en/README.md).

In [fictional batch B-014](../examples/batch.json), bottling is planned for Thursday, but approval has not been recorded. A cleaning check specified by the invented brewery's own HACCP plan has no recorded result. Packaged quantity has not yet been reconciled with finished stock.

A useful answer names each gap, links to its source record and directs it to the appropriate reviewer. It cannot confirm readiness from the scheduled date alone. The missing records establish neither a failed check nor unpaid duty. The example does not classify this cleaning check as a universal critical control point.

A food-safety approval does not settle excise administration, and an excise entry does not establish food-safety readiness. In the JSON, missing approval and result are `null`; excise reconciliation has the separate status `not_reviewed`. These are missing evidence and review states, not automatic findings of noncompliance.

For real use, retain the brewery's applicable plan, source identifiers, observation dates and recorded reviewer decisions. Do not fill gaps with an assumed pass or an invented quantity.

## Context and project limits

Belgian official context addresses [self-checking based on HACCP principles and traceability](https://www.foodweb.favv-afsca.be/professionnels/autocontrole/default.asp), and [brewing excise administration and records](https://finances.belgium.be/fr/douanes_accises/entreprises/accises/produits-soumis-%C3%A0-accise/alcool-et-boissons-alcoolis%C3%A9es/le). These links do not make this illustration a complete statement of applicable obligations. See [source notes](../SOURCES.md).

OBIA — Operon Brewery Intelligent Assistant — is in a private pilot. Its aim is to connect operational questions to source records and prepare a compliance-dossier candidate for review. This example does not demonstrate automatic certification or declaration submission.

[Illustrative evidence](https://presque.digital/en/journal/question-source-review/) · [Project and current limits](https://presque.digital/en/work/obia/) · [License](../LICENSE.md)
