# Quickstart playbook

## Fictional product context

TraceNest is a fictional local HTTP replay tool. An engineer can replay a sanitized fixture locally, but service integration needs a platform owner. Sample replay is not proof of recurring project value. Do not invent hosted behavior, speed improvements, or customer results.

## Decision to resolve

Use one supported engineering task with sanitized input, exact prerequisites, expected output, deterministic success assertion, recovery, and cleanup. Disclose credentials or hosted costs before commands and distinguish verified execution from plausible instructions.

## Task-specific method

Include installation, authentication only if needed, a realistic input, useful output, and the boundary between local example and deployed integration.

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

Plan only; CLI syntax unavailable. Proposed fixture targets a controlled local test service returning status 200 and JSON {"id":7,"state":"ready"}. Start the service with a documented harness if available; otherwise leave its setup syntax explicitly pending. Invoke [DOCUMENTED REPLAY COMMAND] with that fixture. Assert the service received the intended request and compare the returned status/body to the oracle above. This tests forwarding and response reporting, not canned-response playback. No run is claimed; verify CLI output mapping and prerequisites before publishing commands. Stop on mismatch, inspect request/service logs; do not claim offline or account-free operation.

Do not assume missing capabilities or report proposed tests as completed. A useful answer identifies what is known, finishes the requested artifact within that scope, and names the next bounded verification when needed.

## Review criteria

Never claim a command was tested because it looks plausible. A sample working once does not prove production reliability, security, or scale.

The [shared method examples](shared-methods.md) provide additional templates and cross-product examples; apply only those that fit the product scope.
