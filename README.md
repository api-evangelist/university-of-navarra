# University of Navarra (university-of-navarra)

The University of Navarra (Universidad de Navarra) is a private research university founded in 1952, based in Pamplona, Spain, with campuses in San Sebastian and Madrid. It is ranked #249 in the QS World University Rankings 2025. This repository catalogs the institution's public developer/API footprint as an [APIs.json](https://apisjson.org) provider profile for the API Evangelist network.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-navarra/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-navarra-api-evangelist&utm_content=repo

## Type

- Type: Index
- Position: Consumer
- Access: 3rd-Party

## Tags

Education, Higher Education, University, Spain, Open Access, Institutional Repository, OAI-PMH

## APIs

- **DADUN Institutional Repository (OAI-PMH)** — DADUN (Deposito Academico Digital de la Universidad de Navarra) is the university's open-access institutional repository on DSpace (reported v5.3), exposing a standard OAI-PMH 2.0 metadata harvesting interface. Documentation: https://www.unav.edu/web/biblioteca/guias/dadun — Base URL: `https://dadun.unav.edu/dspace-oai/request`

## Plans

- [plans/university-of-navarra-plans-pricing.yml](plans/university-of-navarra-plans-pricing.yml)

## Rate Limits

- [rate-limits/university-of-navarra-rate-limits.yml](rate-limits/university-of-navarra-rate-limits.yml)

## FinOps

- [finops/university-of-navarra-finops.yml](finops/university-of-navarra-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://en.unav.edu/
- LinkedIn: https://www.linkedin.com/school/universidad-de-navarra-cp
- Plans: plans/university-of-navarra-plans-pricing.yml
- Rate Limits: rate-limits/university-of-navarra-rate-limits.yml
- FinOps: finops/university-of-navarra-finops.yml
- Review: review.yml

## Notes

- Verification caveats: The only publicly documented, machine-consumable interface confirmed for the private University of Navarra is the DADUN repository's OAI-PMH endpoint (registered in ROAR, Hispana, and REBIUN). The `dadun.unav.edu` host returned HTTP 403 to automated probes during review due to an Anubis bot-protection layer; LinkedIn returned HTTP 999 (its standard automated-request block). Both are known-good resources, not dead links.
- No general-purpose public developer portal, open-data API platform, documented SIS/catalog/timetable API, or official GitHub organization could be independently confirmed. The `github.com/UNAV` account exists but could not be verified as belonging to this institution and is therefore not listed.
- The institution is distinct from the Public University of Navarra (UPNA / unavarra.es) and from the regional Government of Navarra open-data platform; those are not cataloged here.
- No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
