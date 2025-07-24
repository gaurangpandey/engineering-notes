# Exception Handling in Spring Boot

Exception handling is a critical part of building stable REST APIs.
Without proper handling, errors can leak implementation details
or result in inconsistent API responses.

## Global Exception Handling
Spring Boot provides `@ControllerAdvice` to handle exceptions
across the whole application in a centralized manner.

This helps in:
- Returning consistent error responses
- Avoiding duplicate try-catch blocks
- Improving readability of controllers

## Common Practices
- Use custom exceptions for business errors
- Avoid catching generic `Exception`
- Map exceptions to appropriate HTTP status codes

## Why This Matters
Well-designed exception handling improves:
- API reliability
- Client experience
- Debuggability in production
