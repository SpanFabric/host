# Fresh BREAKER handoff — missing-parent fixture

Repository: SpanFabric/host
Base: e98e1559e2eca94910a2618097a457b147a51793
Material: 69e20f0249bbcfa235025abc0fe3650665e7da7d
Digest: 1ba241f1dc6ca8025f17adbdeccb7d492350d3cd1662b43c67b916d29efcdfe4
Changed material: tests/verification/test_lifecycle_history.py
Builder ceiling: INDEPENDENT_REVIEW_PENDING

Reconstruct independently; Builder claims and CI are untrusted until checked.
Attack loose/GC/repack storage, GC commit-graph exit0 with incomplete traversal, paired valid/corrupt tips, exact absent 40-hex nonzero grandparent, successful base guard, strict direct+immutable runner history rejection, and positive restoration with malformed objects still present but unreachable.
Reproduce historical setup failure after GC without rerunning/deleting historical Actions run39800181504. Confirm validator/policy/runner/workflows unchanged, full authority/shallow/root/history regressions, old Owner/Breaker evidence inactive, material digest exact, and exact new PR-head verification-gate/bootstrap-integrity/windows prerequisite success.
Do not remediate, merge, accept as Owner, touch UP-003 or persistence PRs, or start MIG-001.
