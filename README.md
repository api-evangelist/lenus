# Lenus eHealth

Lenus eHealth is a Copenhagen-headquartered health and fitness technology company that builds a
coaching platform for online health and fitness coaches. Coaching partners run client onboarding,
training and nutrition programming, progress tracking, messaging, content and subscription billing
through the Lenus web dashboard and branded consumer mobile apps. The company also runs Lenus Academy,
a certified education program for coaches, and a US GLP-1 weight management program delivered with
independent medical partner Beluga Health. Backed by EQT Ventures.

- Website: https://lenusehealth.com/
- Coach dashboard: https://eu.lenus.io/dashboard/login
- GitHub: https://github.com/lenus-ehealth

## API surface

**Lenus eHealth publishes no public API.** Probed and confirmed absent as of 2026-07-19:

- No developer portal or documentation host — `developer.`, `docs.`, `developers.` do not resolve.
- No OpenAPI, Swagger, GraphQL or AsyncAPI definition at any public path.
- `api.lenus.io` resolves but returns HTTP 302 to the marketing site; not a public API surface.
- No `/.well-known/` discovery documents on any host (all 404).
- No first-party client libraries on npm, PyPI or other public registries.
- The `lenus-ehealth` GitHub org contains only forks and archived internal utilities.

The platform is closed and invitation-based, accessible to coaching partners under a partnership
agreement. This repo therefore carries identity, legal and domain-security artifacts only — no spec,
SDK, MCP, skills or workflow artifacts, none of which can be grounded without a public API.

## Disambiguation

Lenus eHealth (lenus.io / lenusehealth.com, Copenhagen, Denmark — fitness and health coaching) is a
**different company** from Lenus Health (lenushealth.com, Edinburgh, Scotland — an NHS-facing digital
health platform that *does* publish developer documentation and integration samples at
https://github.com/lenushealth). Do not merge the two profiles.
