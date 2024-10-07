# Instatus API Documentation

## Overview

This repository contains the OpenAPI 3.0.3 specification for the Instatus API. 

[Instatus](https://instatus.com) helps you:
1. Monitor your services (soon)
2. Fix incidents with your team (soon)
3. Share your status with customers

## API Specification

- **Version**: 2.0.0
- **Base URL**: https://api.instatus.com

## Key Features

- RESTful architecture
- JSON-encoded requests and responses
- Authentication via API token


## Usage

All endpoints are under the URL https://api.instatus.com. They generally follow the REST architecture.

Requests must be encoded as JSON with this header: `Content-Type: application/json`.

Requests must provide an API token through the Authorization header. 

```
Authorization: Bearer <API_KEY>
```

You can get your key from User settings in developer settings section: [dashboard.instatus.com/developer](https://dashboard.instatus.com/developer)

Responses from the Instatus API, including errors, are encoded as JSON.


## Main Resources

The API provides endpoints for managing:

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


## File Structure

- `instatus.yaml`: The OpenAPI specification in YAML format
- `instatus.json`: The OpenAPI specification in JSON format


## Getting Started

To get started with the Instatus API:

1. Obtain your API key from the Instatus dashboard
2. Review the API specification in either YAML or JSON format
3. Make your first API call using your preferred HTTP client (We love [Insomnia](https://insomnia.rest?ref=instatus))

## Support

- Help: [instatus.com/help](https://instatus.com/help)
- API docs: [instatus.com/help/api](https://instatus.com/help/api)
- Support email: [support@instatus.com](mailto:support@instatus.com)

For any questions or issues, please contact  or refer to the (official documentation).
