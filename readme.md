# Library and Additional Features
Library Used
1. Flask: A micro web framework for Python.
2. SQLAlchemy: SQL toolkit and Object-Relational Mapping (ORM) for Python.
3. Requests: Simplifies HTTP requests to external resources.
4. Pytest: Testing framework for writing and executing unit tests.
5. Docker: Containerization platform to package applications and their dependencies.
6. GitHub Actions: CI/CD platform for automating workflows.
7. Kubernetes (kubectl): Container orchestration platform for deploying and managing containerized applications.
8. Zabbix: Open-source monitoring solution for tracking and visualizing system performance. 


Guidance for MacOS / Intel 
Features Implemented:
1. List Pokemon Endpoint (/pokemon):
    - Retrieve a list of Pokemon.
2. Filter Pokemon Endpoint (/pokemon/category/{category}):
    - Filter Pokemon by category (e.g., water, fire, neutral).
3. Detail Pokemon Endpoint (/pokemon/{name}):
    - View details of a specific Pokemon.
4. Review Pokemon Endpoint (/pokemon/review/{name}):
    - Submit anonymous reviews for Pokemon (recording user IP and user agent).
5. Unit Testing with Pytest:
    - Implemented unit tests to ensure the correctness of API endpoints.
6. Docker Containerization:
    - Dockerfile created for building a Docker image of the 7.Flask application.
7. CI/CD with GitHub Actions:
    - Automated CI/CD pipeline using GitHub Actions to build push Docker image, and deploy to Kubernetes.
8. Kubernetes Deployment (kubernetes/):
    - Kubernetes manifests for deploying the Flask application.
9. Monitoring with Zabbix:
    - Integration of Zabbix for monitoring system health.
10. Postman Testing (postman/):
    - Provided Postman collection for testing API endpoints.
11. README Documentation:
    - Comprehensive README.md file with installation, usage, and development information.
