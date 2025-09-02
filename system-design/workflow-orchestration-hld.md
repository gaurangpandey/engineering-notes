# Workflow Orchestration – High Level Design

## Core Components
- API Service – accepts workflow requests
- Orchestrator – manages workflow state
- Worker Services – execute individual steps
- Persistence Layer – stores workflow state
- Message Queue – async execution & retries

## High Level Flow
1. Client submits workflow
2. Orchestrator stores initial state
3. Steps are published to queue
4. Workers process steps
5. Orchestrator updates workflow status
