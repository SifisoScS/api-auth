# api-auth

Type: module

## System

Part of: backend-apis

## Related Repositories

- api-aggregator
- api-balancer
- api-health
- api-mock
- api-metrics
- api-tracer
- api-registry
- api-discovery
- api-circuit-breaker
- notification-emailer
- notification-sms
- notification-push
- notification-webhook
- notification-processor
- notification-templater
- notification-queue
- scheduling-cron
- scheduling-batch
- scheduling-pipeline
- scheduling-interval
- scheduling-deadline
- scheduling-recurring

## Configuration

`JWT_SECRET` must be set in the environment. There is no default: `generateToken` and `verifyToken` throw if it is missing.
