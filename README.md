### README

# Backend Template - Spring Boot

Reusable backend architecture for future projects.

## Stack
- Spring Boot
- PostgreSQL
- JWT Authentication (access + refresh tokens)
- Docker
- Swagger/OpenAPI
- Spring Security

## Architecture
- Module-based structure (feature-first)
- DTO separation
- Global exception handling
- Standard API response format

## API Format

Success:
```json
{ "success": true, "data": {} }
````

Error:

```json
{
  "success": false,
  "error": {
    "code": "ERROR_CODE",
    "message": "Message"
  }
}
```

## Goals

* Consistent backend foundation
* Reusable across web + mobile apps
* Production-ready CI/CD pipeline

## Planned DevOps

* GitHub Actions CI
* Docker build pipeline
* Automated tests
* Lint + formatting checks
* Git hooks
* Dependency checker (Dependabot)
