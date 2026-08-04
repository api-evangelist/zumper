# Zumper

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

Zumper is a rental listing marketplace that connects renters with landlords and property managers across the United States and Canada. The platform provides access to apartment listings, property data, rental price insights, and tenant application management. Founded in 2011, Zumper processes over 76 million site visits annually and syndicates listings across PadMapper, ChatGPT, Microsoft Bing, and Realtor.com.

**APIs.json Profile:** [apis.yml](apis.yml)

## API Overview

Zumper provides a syndication API and integration capabilities for property management software providers and enterprise partners. Key capabilities include:

- Rental listing publication and management
- Rental market data and price trend insights
- Tenant screening powered by TransUnion
- Digital leasing workflow integration
- Online rent payment processing
- PowerLeads AI for optimized lead delivery

## Pricing

| Plan | Listings | Price |
|------|----------|-------|
| Free | 5/month | $0/month |
| Premium Starter | 5 | $10/month |
| Premium 10 | 10 | $80/month |
| Premium 25 | 25 | $175/month |
| Premium 50 | 50 | $300/month |
| Premium 100 | 100 | $500/month |
| Premium 200 | 200 | $800/month |
| Multifamily Enterprise | Custom | Custom |

## Resources

- [Property Manager Portal](https://www.zumper.com/manage)
- [Help Center](https://help.zumper.com/hc/en-us)
- [Blog](https://www.zumper.com/blog/)
- [Enterprise Listings Contact](mailto:directlistings@zumper.com)

## Catalog Files

- [apis.yml](apis.yml) - APIs.json 0.19 profile
- [plans/plans.yml](plans/plans.yml) - Pricing plan details
- [rate-limits/rate-limits.yml](rate-limits/rate-limits.yml) - Rate limit documentation
- [finops/finops.yml](finops/finops.yml) - FinOps and cost optimization guidance
