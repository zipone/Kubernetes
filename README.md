**Multi-service-gitlab-ci.yml**

Multi-service support:
The pipeline uses a matrix strategy to handle multiple services (app1, app2, app3, app4) in parallel.

Selective deployment
Deploy a single service or all services via SELECTED_SERVICE
Option to deploy only Kubernetes configs (DEPLOY_ONLY_CONFIGS=true

Flexibility:
Supports manual and automated deployments
Allows partial deployments per service
Can run config-only updates without rebuilding images
