APIGateway - Microservice for Routing Requests

APIGateway is a microservice that routes incoming client requests to the appropriate microservice based on the request path. It uses Eureka for service discovery to find available server hosts dynamically.

📦 Features

Routes requests to target microservices based on path mapping.

Integrates with Eureka for dynamic service discovery.

Handles request forwarding and response aggregation.


🛠️ Technologies Used

Java Spring Boot - Core framework for building the gateway service.

Spring Cloud Gateway - For routing and forwarding requests.

Eureka Client - Service discovery for locating available services.

Maven - Dependency management and build tool.
