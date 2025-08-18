# Common Production Issues – Backend Systems

## 1. NullPointerException
Often caused by missing validation or unexpected null responses
from external systems.

**Prevention**
- Defensive null checks
- Validation at API boundaries
- Proper Optional usage

## 2. Performance degradation
Usually caused by:
- Missing indexes
- N+1 queries
- Inefficient loops

## 3. Memory issues
- Unreleased resources
- Large objects held in memory
- Incorrect cache configuration

## Debugging approach
1. Reproduce issue locally
2. Check logs and metrics
3. Identify recent changes
4. Apply minimal fix

## Practical Advice
Always confirm whether an issue is data-related or code-related
before attempting a fix.
