# Pricing playbook

## Fictional product context

TraceNest is a fictional local HTTP replay tool. An engineer can replay a sanitized fixture locally, but service integration needs a platform owner. Sample replay is not proof of recurring project value. Do not invent hosted behavior, speed improvements, or customer results.

## Decision to resolve

Select the developer workload only when a brief also labels a separate data workload. Do not price unrelated source-row activity as CLI usage. Compare human seats, automation and team licensing; local software can be commercial without a hosted service.

## Task-specific method

Consider individual-to-team adoption, CI or automated activity, service accounts, seats versus usage, support ownership, and whether a meter discourages integration.

## Output worksheet

| Field | Record |
| --- | --- |
| Requested decision and task | |
| User, evaluator, buyer, and owner | |
| Supported behavior and environment | |
| Evidence, source, and limits | |
| Proposed action or finished artifact | |
| Meaningful result and verification | |
| Unknowns, failure, and stop condition | |

## Completed example

Facts: local CLI; pricing/license unknown; five humans, three CI identities; 50,000 manual and 700,000 automated requests/month. Vendor cost and willingness to pay unknown.

| Proposed meter | Illustrative quantity | Main tradeoff |
| --- | --- | --- |
| Human seats | 5, if CI identities excluded | Predictable; identify who needs a license |
| All identities | 8, if all billable | Could penalize automation identities; terms unvalidated |
| Requests | 750,000/month | Scales with CI activity; needs spend predictability |
| Team license | 1 team, proposed boundary | Predictable automation access; test team/value definition |

Automation is 700,000/750,000 = 93.3% of requests. Doubling CI requests leaves five human seats and raises requests to 1.45 million. Local customer CPU is not evidence of vendor compute cost. Recommendation: research a team license with an explicit proposed CI entitlement versus human seats; interview budget owners before choosing price. A hosted service is unnecessary for either proposal. This does not assert current packages or license rights.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not copy a competitor's prices without checking workload fit. No universal free tier, trial duration, margin target, or seat-based default. Final audit: does any sentence imply no current billing from an unknown price, vendor automation cost from local execution, or cost under-recovery without cost data? Remove that inference from the recommendation itself. Provide a useful proposed offer even when current terms are unknown.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
