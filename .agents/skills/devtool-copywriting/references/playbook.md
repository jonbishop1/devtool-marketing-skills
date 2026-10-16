# Copywriting playbook

## Fictional product context

TraceNest is a fictional local HTTP replay tool. An engineer can replay a sanitized fixture locally, but service integration needs a platform owner. Sample replay is not proof of recurring project value. Do not invent hosted behavior, speed improvements, or customer results.

## Decision to resolve

Anchor copy in the engineering task, supported environment, input/output, and evidence of reduced effort or risk. Distinguish local/open-source use from paid hosted behavior; select a runnable example or docs CTA when that fits readiness.

## Task-specific method

Prefer task and environment specificity over “developer-first” or “10x productivity.” State supported languages, execution boundaries, and what the first example actually demonstrates.

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

Facts: a local HTTP replay CLI sends an already-sanitized fixture to a running local service and prints its response. Node 22, macOS/Linux. Account and telemetry behavior unspecified.

Finished copy: **Replay a fixture against your local service.** Send an already-sanitized HTTP fixture to a running local service and inspect its response. Use the CLI with Node 22 on macOS or Linux. **CTA: Explore a sample replay** (proposed link; confirm destination).

Why: the mechanism carries the benefit. "No account", "offline", "nothing leaves your machine", and "returns a recorded response" do not follow from these facts.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Do not fabricate proof or guarantees. Do not equate open source with free managed hosting, or compliance documentation with blanket certification.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
