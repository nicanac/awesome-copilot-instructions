# Python FastAPI API Copilot Instructions

## Key Principles
- Write concise, technical Python code with accurate examples
- Use functional programming and modular approaches
- Employ async/await patterns for non-blocking operations
- Focus on API performance, security, and scalability
- Follow FastAPI best practices and conventions

## Python/FastAPI Guidelines
- Use `async def` for I/O-bound operations, `def` for CPU-bound functions
- Implement proper dependency injection with FastAPI's `Depends()`
- Use Pydantic v2 models for request/response validation
- Structure files: routers, services, models, dependencies, utils
- Apply type hints consistently throughout the codebase

## Error Handling and Validation
- Implement error handling at the start of functions with early returns
- Use guard clauses for preconditions and invalid states
- Create custom error types and consistent error responses
- Log errors appropriately with contextual information
- Use Pydantic validators for input validation

## Performance Optimization
- Use asynchronous database operations with SQLAlchemy 2.0
- Implement caching strategies (Redis, in-memory)
- Apply lazy loading for database queries
- Optimize API endpoints with dependency caching
- Monitor and profile API performance metrics

## Project Structure
```
app/
├── routers/          # API route definitions
├── services/         # Business logic
├── models/           # Pydantic models and schemas
├── dependencies/     # FastAPI dependencies
├── database/         # Database configuration and models
├── utils/           # Utility functions
└── tests/           # Test files
```

## Security Best Practices
- Use FastAPI's built-in security utilities
- Implement proper authentication and authorization
- Validate and sanitize all input data
- Use environment variables for sensitive configuration
- Apply CORS, rate limiting, and request validation

## API Design Guidelines
- Use clear, RESTful endpoint naming
- Implement proper HTTP status codes
- Provide comprehensive API documentation with FastAPI's auto-docs
- Use consistent response formats
- Version your APIs appropriately

## Dependencies and Tools
- FastAPI (latest version)
- Pydantic v2 for data validation
- SQLAlchemy 2.0 for database ORM
- Redis for caching
- pytest for testing
- uvicorn for ASGI server


