Perform an independent Phase 3 financial-correctness review.

Test:

- successful operation charged once
- failed operation settlement behavior
- provider timeout
- application retry
- queue retry
- duplicate idempotency key
- concurrent balance reservation
- stale reservation recovery
- low balance
- hard quota
- allowed overage
- rollup rebuild
- webhook replay
- out-of-order webhook
- cross-tenant billing access
- unauthorized member billing call

Reconcile source usage events, ledger entries, rollups and displayed balance.

Generate:

docs/reviews/phase3-financial-reconciliation.md
docs/reviews/phase3-exit-report.md

Fail the phase for any double-charge, under-charge, cross-tenant exposure or
non-idempotent webhook.