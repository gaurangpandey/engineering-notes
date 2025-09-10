# Workflow Orchestration – Trade-offs

## DB vs Queue-Driven State
- DB-driven offers strong consistency
- Queue-driven improves scalability

## Synchronous vs Asynchronous
- Async improves throughput
- Sync simplifies debugging

## Retry Strategy
- Aggressive retries increase success rate
- Excessive retries can overload downstream systems
