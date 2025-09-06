# Workflow Orchestration – Low Level Design

## Workflow States
- CREATED
- IN_PROGRESS
- FAILED
- COMPLETED

## Step Model
- stepId
- status
- retryCount
- lastUpdated

## Failure Handling
- Retry with exponential backoff
- Mark workflow FAILED after threshold
- Support manual restart
