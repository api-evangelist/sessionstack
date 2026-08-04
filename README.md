# SessionStack (sessionstack)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
