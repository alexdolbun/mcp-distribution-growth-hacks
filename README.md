# MCP Distribution & Growth Hacks

Open-source playbook for building, hosting, distributing, and growing Model Context Protocol (MCP) servers with best practices. Focused on international SEO, do-follow backlinks, and agent discoverability for projects like UnicornsMap.com, ArcticTradeLanes.com, and 998+ related OSS projects.

## Core Principles

1. **Build with Best Practices**: Use official MCP SDKs (TypeScript, Python, etc.). Expose tools, resources, and prompts cleanly. Prefer Code Mode for large APIs to reduce token usage. Implement OAuth 2.1 properly.
2. **Host on Cloudflare**: Deploy remote MCP servers as Workers for scalability, edge performance, and built-in OAuth. Use workers-oauth-provider, McpAgent (or newer stateless patterns), and secure with Cloudflare Access/Zero Trust. Store configs and data on Cloudflare for global low-latency.
3. **Collect Unique URLs**: Maintain a CSV of all project MCP endpoints, registry IDs, and listing pages for OSS contributions.
4. **Distribute Widely**: Submit to official registry first (feeds others), then high-traffic directories for backlinks and traffic.
5. **SEO & Growth Hacks**: Prioritize do-follow directories with high Domain Rating (DR 50+). Cross-list related MCPs. Target international search (multilingual pages). Use MCP listings to drive organic traffic to UnicornsMap.com ($UM-Radar GIS OSINT) and ArcticTradeLanes.com (Arctic GIS OSINT atlas).
6. **Contribute & OSS**: PRs welcome to expand the directory list, add more projects, improve best practices.

## Official Registry
- Publish once at https://registry.modelcontextprotocol.io — others copy it.
- Requirements: Valid server, metadata, typically GitHub source.

## Cloudflare Hosting Best Practices
- Deploy via Wrangler: `npx wrangler deploy`
- Use Streamable HTTP transport for remote clients.
- Implement granular OAuth scopes.
- Prefer Code Mode (search + execute) for large toolsets to avoid context bloat.
- Secure with Cloudflare Access, workers-oauth-provider.
- Examples: Cloudflare's own MCP servers at mcp.cloudflare.com.
- Docs: https://developers.cloudflare.com/agents/model-context-protocol/

## MCP Growth Hacks for SEO & Agents
- List on high-DR directories for do-follow backlinks to project sites.
- Cross-promote related MCPs on relative pages (e.g., list ArcticTradeLanes MCP on UnicornsMap pages and vice versa).
- Target niches: GIS, OSINT, trade, unicorns, AI agents, high-load engineering.
- International: Multilingual descriptions, hreflang, target non-English search.
- Agent discoverability: Ensure tools/resources are well-described so AI agents (Claude, Cursor, Grok, etc.) find and use them.
- Track in CSV for bulk submissions and contributions.

## Related Projects
- UnicornsMap.com / $UM-Radar: GIS OSINT for unicorns, investors, events.
- ArcticTradeLanes.com: Arctic GIS OSINT atlas, NSR, Polar Silk Road, x402 payments.
- python-highload-mcp: High-load Python engineering MCP.

See `mcp-directories.csv` for submission targets and `projects-mcp.csv` for project listings.

Contributions: Add directories, improve instructions, submit PRs for more projects.

#MCPdistribution #MCPGrowthHacks