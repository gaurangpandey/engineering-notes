# Workflow Orchestration – Requirements

## Problem Statement
Many backend systems need to execute a sequence of dependent steps
while tracking progress, handling failures, and supporting retries.

## Functional Requirements
- Create workflows with multiple ordered steps
- Track workflow and step status
- Retry failed steps
- Resume workflows from last successful step

## Non-Functional Requirements
- Scalability for large number of workflows
- Fault tolerance
- Idempotent step execution
- Observability (logs and metrics)

## Assumptions
- Workflow steps may involve external services
- Steps can be executed asynchronously
