# Workflow

## General

We try to be as agile as possible while maintaining a workflow with rigorious testing.

## Code flow

1. We develop locally.
2. We create a pull request to master/main.
2. We deploy ruthlessly from master/main to FT.
4. When all devs agree, we deploy to ST.
5. When all stakeholders agree we deploy to AT.
6. When all stakeholders agree we let INFRA Team deploy to PR.

## Deploy

Scrum Master is responsible for Deployment Change Requests.

We request deploys on afternoons rather than mornings.

Scrum master is responsible for booking a meeting with verifying parties post deployment.

### Required verifying parties:
* 1 or more Developer
* 1 or more BA
* 1 responsible for contacting INFRA  if we require rollback or if the deployment was successful.