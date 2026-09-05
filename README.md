# 24 FIX

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

24 FIX is the flagship consumer home-maintenance brand of 24 Solution Group (Thailand) Co., Ltd.,
founded in Bangkok in 2018 and now operating under the 24X umbrella brand. It runs an end-to-end
property maintenance and home-solutions service — air-conditioner cleaning and repair, appliance
service, electrical, plumbing, painting, cleaning, renovation and construction — through an in-house
managed network of more than 500 fixer teams and material vendor stores across Bangkok and the
surrounding provinces, with expansion into Phuket and Singapore. Four business lines sit under the
group: 24 FIX (consumer), 24 FIX for Business (commercial and facility maintenance), 24 House
Solution, and 24 Projects (renovation and construction).

## API surface

**24 FIX publishes no public API.** This is a measured absence, recorded 2026-09-05 after a full
contract-discovery pass across every host the company operates — `24x.co.th`, `www.24x.co.th`,
`fix.24x.co.th`, `business.24x.co.th`, `housesolution.24x.co.th`, `projects.24x.co.th` and
`careers.24x.co.th`:

- No OpenAPI, Swagger, GraphQL SDL, AsyncAPI, WSDL or Protobuf contract at any probed location.
- No `/apis.json`, `/apis.yml` or `/.well-known/apis.json`.
- No `/.well-known/` discovery document at all — every named path returns a genuine 404, and so does
  the negative control, so these are true absences rather than a catch-all.
- No `/llms.txt`, MCP server or A2A agent card.
- No developer portal, API reference, SDK, CLI or webhook catalog. The strings "API", "SDK",
  "developer" and "webhook" do not appear in the served HTML of any 24X property.
- The one `/api/` tree in the estate is the internal Next.js route set of the `fix.24x.co.th`
  booking app, which the site's own `robots.txt` disallows. It is an application internal, not a
  product.
- The legacy brand domain `24fix.co` is a parked GoDaddy domain: it answers 200 on every path with a
  114-byte lander redirect, including a negative control that cannot exist, so every 200 on that
  host is discarded.

Corporate service and partnership enquiries go to business@24fix.co.

## Links

- Company: https://24x.co.th/
- 24 FIX (consumer booking): https://fix.24x.co.th
- 24 FIX for Business: https://business.24x.co.th
- 24 House Solution: https://housesolution.24x.co.th
- 24 Projects: https://projects.24x.co.th
- About: https://24x.co.th/en/about-us
- Contact: https://24x.co.th/th/contact-us
- Blog / community: https://fix.24x.co.th/blog
- Terms and conditions: https://24x.co.th/th/term-condition
- Privacy policy: https://24x.co.th/th/privacy-policy
- Secondary-market listing (harvest source): https://equityzen.com/company/24fix
