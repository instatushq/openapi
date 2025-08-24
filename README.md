# Instatus OpenAPI Spec

This repository contains the [OpenAPI](https://www.openapis.org/) 3.0.3 specification for the [Instatus API](https://instatus.com/help/api).

## Specs

- **Version**: 2.0.0
- **Base URL**: https://api.instatus.com

## Get started

1. Obtain your API key from the Instatus dashboard: [dashboard.instatus.com/developer](https://dashboard.instatus.com/developer)
2. Review the API specification in either YAML or JSON format
3. Make your first API call using your preferred HTTP client (We love [Insomnia](https://insomnia.rest))

## API requests

- Requests must be encoded as JSON with this header: `Content-Type: application/json`.
- Requests must provide an API token through the Authorization header.
```
Authorization: Bearer <API_KEY>
```

## Resources

1. Status Pages
2. Components
3. Incidents
4. Incident Updates
5. Maintenances
6. Maintenance Updates
7. Templates
8. Teammates
9. Subscribers
10. Metrics
11. Monitors
12. Monitor Alerts
13. Monitor Groups
14. Routing Rules
15. Escalation Policies
16. On-call Schedules


## Files

- `instatus.yaml`
- `instatus.json`

## Get help

- Help: [instatus.com/help](https://instatus.com/help)
- API docs: [instatus.com/help/api](https://instatus.com/help/api)
- Support email: [support@instatus.com](mailto:support@instatus.com)

## What's Instatus?

[Instatus](https://instatus.com) helps you:
1. Monitor your services (soon)
2. Fix incidents with your team (soon)
3. Share your status with customers
