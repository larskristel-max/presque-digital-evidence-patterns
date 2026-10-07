# Compare an offer before ranking its price

By Presque.digital · 7 October 2026 · [Français](comparison.fr.md)

Before comparing devices, specify the exact model, acceptable condition, required configuration and delivery destination.

| Field | Record | If missing |
| --- | --- | --- |
| Model and configuration | Exact model and required options, such as keyboard layout | Keep eligibility unresolved |
| Condition | New, refurbished or used, with the listing description | Do not assume the requested condition |
| Item price | Amount and whether tax is included | Do not calculate a verified total |
| Delivery | Availability to the destination and the charge | Keep the delivered total unknown |
| Mandatory extras | Costs required to meet the requirements | Include them before ranking |
| Evidence | Source URL, observation date and relevant statement | Mark unverified claims explicitly |
| Search outcome | Offer found, no matching result, blocked page or error | Preserve these as different outcomes |

## Worked example

The [fictional offers](../examples/offers.json) all describe the same invented device model, requested new with an AZERTY keyboard and delivery to Belgium. Prices include tax; there are no mandatory extras in this example.

| Offer | Item | Delivery | Keyboard | Interpretation |
| --- | --- | --- | --- | --- |
| A | €800 | €20 | QWERTY | €820 delivered, but excluded because its configuration does not meet the requirement |
| B | €830 | Unknown | AZERTY | Configuration matches; delivered total remains unknown |
| C | €850 | €15 | AZERTY | €865 delivered; suitable for price comparison |

Offer B is not a verified €830 delivered offer. Offer A is not a cheaper suitable offer. Offer C has a comparable total, but this does not establish seller reliability, warranty quality or whether buying is worthwhile. The unknown fee could change the ranking.

In the JSON, `null` means no value has been recorded. A confirmed zero charge would be `0`, with evidence supporting it. An unsuccessful search is not evidence that no suitable offer exists everywhere. A blocked page or error is not a successful search with zero results.

For actual offers, retain dated source links and the statements supporting configuration, tax, delivery and extras. The example's `example.invalid` links are fictional markers, not usable seller evidence.

[Illustrative project note](https://presque.digital/en/journal/unknown-is-not-zero/) · [Current availability](https://presque.digital/en/access/) · [License](../LICENSE.md)
