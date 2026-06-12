# Vidyard (vidyard)

Vidyard is a video platform for business that provides REST APIs for managing video libraries, generating sharing links, tracking viewer analytics, and integrating with CRM and marketing tools. The Dashboard API enables programmatic control over players, videos, chapters, organizations, teams, users, events, campaigns, webhooks, and more. The Video Agent API supports AI-powered personalized video creation workflows, and the Analytics Webhook API streams real-time viewer data to external systems. API access is available on Enterprise plans.

APIs.json: https://raw.githubusercontent.com/api-evangelist/vidyard/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=vidyard-api-evangelist&utm_content=repo

## Tags

- Video
- Video Platform
- Video Analytics
- Video Sharing
- Sales Video
- CRM Integration
- Marketing
- AI Video
- Webhooks

## APIs

### Vidyard Dashboard API
The Vidyard Dashboard API provides full CRUD access to account assets including players, videos, chapters, organizations, teams, users, roles, events, campaigns, tags, webhooks, embeds, access managers, attributes, features, and captions. Base URL: `https://api.vidyard.com/dashboard/v1/`. Authentication via org-scoped Bearer token (auth_token parameter).

- Documentation: https://developer.vidyard.com/

### Vidyard Video Agent API
Enables integration of Vidyard's AI-powered video generation into any application or custom workflow. Triggers personalized video creation of Vidyard campaigns programmatically with webhook-based delivery notifications.

- Documentation: https://knowledge.vidyard.com/hc/en-us/articles/42909331296411-Using-the-Vidyard-Video-Agent-API

### Vidyard Analytics Webhook API
Allows subscribing to and streaming video view data from Vidyard to an external application. View events are delivered as HTTP POST requests in JSON format to a configured endpoint. Management base URL: `https://analytics-api.vidyard.com/v1/`.

- Documentation: https://knowledge.vidyard.com/hc/en-us/articles/360009879654-How-to-use-the-analytics-subscription-webhook

## Plans, Rate Limits, and FinOps

- **Plans & Pricing**: [plans/vidyard-plans-pricing.yml](plans/vidyard-plans-pricing.yml) — Four tiers: Free ($0), Starter ($59/seat/month), Teams (custom), Enterprise (custom annual). API access is Enterprise-only.
- **Rate Limits**: [rate-limits/vidyard-rate-limits.yml](rate-limits/vidyard-rate-limits.yml) — Numeric limits are not publicly documented; contact Vidyard Enterprise support at support@vidyard.com.
- **FinOps**: [finops/vidyard-finops.yml](finops/vidyard-finops.yml) — Seat-based cost model; Enterprise annual contracts required for API access; Video Agent available as add-on (~$24/seat/month).

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common

| Type | URL |
|------|-----|
| Website | https://www.vidyard.com/ |
| Documentation | https://developer.vidyard.com/ |
| GitHub | https://github.com/Vidyard |
| LinkedIn | https://www.linkedin.com/company/vidyard |
| Blog | https://www.vidyard.com/blog/ |
| Pricing | https://www.vidyard.com/pricing/ |
| StatusPage | https://status.vidyard.com/ |
| X | https://x.com/vidyard |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
