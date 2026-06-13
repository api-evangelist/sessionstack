# SessionStack (sessionstack)

SessionStack is an AI-driven session replay and digital experience analytics platform that enables product and support teams to record, replay, and analyze real user sessions on web applications. It provides a REST API for retrieving session recordings, events, errors, and user-generated logs, enabling teams to integrate session playback into support workflows, export data to external systems, and automate session management. SessionStack integrates with tools such as Zendesk and Sentry to surface session replays directly alongside support tickets and error reports. The platform uses tagless autocapture and retroactive data history to ensure no user interaction is missed, and supports co-browsing for live collaborative troubleshooting sessions.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/sessionstack/refs/heads/main/apis.yml
- Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=sessionstack-api-evangelist&utm_content=repo

## Tags

- Session Replay
- User Monitoring
- Digital Experience Analytics
- Session Recording
- Co-browsing
- Error Tracking
- Support Workflows
- User Behavior Analytics

## APIs

### SessionStack REST API

The SessionStack REST API provides programmatic access to session recordings, user events, errors, and logs. Developers can retrieve and search sessions associated with their websites, get details about individual sessions, delete sessions, export session data, and add log entries to sessions. The Scale plan and above unlock data export via REST API.

- Documentation: https://docs.sessionstack.com/reference/sessions

## Plans / Rate Limits / FinOps

- Plans: [plans/sessionstack-plans-pricing.yml](plans/sessionstack-plans-pricing.yml)
- Rate Limits: [rate-limits/sessionstack-rate-limits.yml](rate-limits/sessionstack-rate-limits.yml)
- FinOps: [finops/sessionstack-finops.yml](finops/sessionstack-finops.yml)

**Pricing Summary:**

| Plan       | Price/month | Seats | REST API Export |
|------------|-------------|-------|-----------------|
| Free       | $0          | 3     | No              |
| Launch     | $79         | 5     | No              |
| Scale      | $129        | 10    | Yes             |
| Enterprise | Custom      | Custom| Yes             |

## Timestamps

- Created: 2026-06-13
- Modified: 2026-06-13

## Common

- Website: https://www.sessionstack.com
- Documentation: https://docs.sessionstack.com/docs/overview
- GitHub Org: https://github.com/sessionstack
- LinkedIn: https://www.linkedin.com/company/sessionstack
- Blog: https://medium.com/sessionstack-blog
- Pricing: https://www.sessionstack.com/pricing
- X: https://x.com/sessionstack

## Maintainers

- Kin Lane (kin@apievangelist.com)
