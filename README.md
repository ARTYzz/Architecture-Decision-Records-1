# Architecture-Decision-Records-1
## Context:
### Our team needs to deploy a scalable REST API with minimal operational overhead.

## Decision:
### We use Serverless Framework on AWS to deploy Lambda functions behind API Gateway.

## Rationale:

- Auto-scaling eliminates the need for server provisioning.
- Pay-per-execution reduces operational costs.
- Rapid iteration speeds up deployment & testing.
