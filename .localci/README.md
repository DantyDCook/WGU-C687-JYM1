# LocalCI validation contract (proposal)

This directory declares source-versioned **validation requirements**, not executable authority. The central LocalCI engine must validate each requested check against a separately approved policy, match the exact commit SHA, and fail closed on unmet tools, samples or prerequisites.

Proposed checks: cpp-static-analysis, msvc-solution-build, cpp-unit-smoke, project-file-validation.

This contract does not authorize writes to engineering project records, unsafe database resets, production systems, publication, arbitrary commands, credential access, or changes to protected LocalCI state. Existing domain review is still required before real-world use.

RFC: https://github.com/DantyDCook/local-ci-bootstrap-test/pull/5
