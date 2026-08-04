# Tettra

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

Tettra is an AI-powered knowledge management system that helps teams curate company policies, processes, and knowledge articles into a searchable internal wiki. It features an AI assistant named Kai that integrates directly with Slack and Microsoft Teams to automatically answer repetitive questions from the team knowledge base.

## API

Tettra provides a limited experimental REST API (`https://app.tettra.co/api`) for automating common tasks and building custom integrations. The API supports:

- **Search** pages in the knowledge base
- **Create Pages** from HTML content
- **Suggest a New Page** (page requests for knowledge gaps)
- **Suggest Page Updates** to existing pages
- **Create Questions** within the Q&A workflow

API keys are provisioned through account settings and are only available on the **Scaling** and **Enterprise** plans. The API is marked experimental and may include breaking changes without notice.

## Authentication

All API requests require an `api_key` query parameter. Keys are available via team account settings for eligible plan subscribers.

## Resources

- **Homepage:** https://tettra.com/
- **API Documentation:** https://support.tettra.com/api-overview
- **Pricing:** https://tettra.com/pricing/
- **Changelog:** https://changelog.tettra.co/
- **Status:** https://tettra.statuspage.io/
- **LinkedIn:** https://www.linkedin.com/company/tettra
- **GitHub:** https://github.com/Tettra

## Maintainer

Kin Lane (kin@apievangelist.com)
