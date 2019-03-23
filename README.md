# netcoreutils
Playground to comprehend and build a microservice using async design patterns
Design Patterns
1. Async
2. Dependency Injection
3. Repository Pattern
4. Factory Pattern
5. Singleton 
6. Single responsibility principal

Deployment Strategy:
1. Use Kubernetes

Persistent Store:
1. Cosmos DB - Sql API


Swagger:
POST /api/helloworld
    Request Body:
    {
        "id": "<Guid>",
        "content": {
            "type": "text",
            "value": "hello world"
        }
    }

    Result: 
    204 - No Content

    Response Body:
    None

GET /api/<Guid>
    Request Body:
    None

    Result:
    200 - Ok 

    Response Body:
    {
        "id": "<Guid>",
        "content": {
            "type": "text",
            "value": "hello world"
        }
    }