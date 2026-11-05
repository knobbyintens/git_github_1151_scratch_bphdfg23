# Architecture overview

| Service | Owner | Notes |
| ---- | ---- | ---- |
| `workspace-api` | Platform | Tenant and workspace lifecycle |
| `identity-edge` | Auth | SSO, session management |
| `reporting-worker` | Insights | Scheduled report generation |
| `notification-relay` | Platform | Email and webhook delivery |

All services write structured audit events to the shared event bus.
