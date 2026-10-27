# MCP Best Practices Summary

## Building
- Official SDKs only.
- Accurate input/output schemas.
- Code Mode for scale.
- Secure tools: no hardcoded secrets, input validation.

## Hosting on Cloudflare
- Workers for edge.
- OAuth via workers-oauth-provider.
- Stateless where possible (newer MCP spec).
- Durable Objects only for app state.
- Proxy status on DNS, Access for control.

## Distribution
1. Official Registry.
2. High-traffic directories (see CSV).
3. Awesome lists via PR.
4. Niche (GIS, OSINT, AI agents).
5. Cross-list related projects.

## SEO
- Do-follow from DR 50+ sites.
- Unique URLs per project.
- Multilingual.
- Agent-friendly descriptions.
- Backlink exchange via mutual listings.

Update CSVs via PRs for community contributions.