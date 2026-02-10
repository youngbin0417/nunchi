# API Usage Policy

## Introduction
The NUNCHI API provides programmatic access to relationship analysis and coaching services. Use of the API is subject to the terms and conditions outlined in this document.

## Authentication
All API requests must be authenticated via a Bearer Token transmitted in the HTTP Authorization header. API keys are issued upon registration and must be kept secure.

## Usage Limits
To ensure system stability and fair resource allocation, rate limiting is enforced based on the account tier:
- Standard: 60 requests per minute
- Professional: 300 requests per minute
- Enterprise: Custom limits based on agreement

Exceeding these limits will result in a 429 (Too Many Requests) response code.

## Data Handling
Developers must adhere to the NUNCHI Privacy Policy. Storing raw audio data extracted via the API on external servers is strictly prohibited unless explicit consent is obtained from all parties involved in the conversation.

## Error Handling
The API uses standard HTTP status codes:
- 200/201: Success
- 400: Malformed Request
- 401: Unauthorized access
- 403: Forbidden - Permission denied
- 404: Resource not found
- 500: Internal server error

## Versioning
API versions are specified in the URL path (e.g., /api/v1). Breaking changes will be introduced behind a new version identifier with a minimum 6-month deprecation period for the previous version.
