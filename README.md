# Ecommerce competitor research by Storelens

Ecommerce competitor research from Claude Code and Codex: store spy reports, a theme detector and app detector, competitor product tracking, price tracking, best sellers and store leads. The plugin bundles the MCP connector `https://storelensapp.com/mcp` plus the `storelens` skill (which tool to use for which question, and what each one costs).

```bash
/plugin marketplace add storelensapp/plugin
/plugin install storelens@storelens
```

You sign in to Storelens and approve access the first time a tool runs. Tools use your Storelens plan's allowances, exactly as the dashboard does: monthly on Starter and Pro, and a one-time allowance on a free account (5 store scans, 3 store spy reports, 10 lead rows, no card). Docs: https://storelensapp.com/developers/

## Contact data: sources, legal basis and opt-out

Owner contacts come from a business-contact data provider, reached through the treg API gateway, that compiles what professionals publish about their work (company websites, professional profiles, public business registries); store facts come from each store's public pages. Storelens holds them for business-to-business contact with the people who run a store, on the basis of legitimate interests (Article 6(1)(f) GDPR). Anyone listed can be removed at https://storelensapp.com/opt-out/ with a work email or a store domain: no account is needed and it takes effect immediately on the website, the API, the MCP server and exports.

MIT licensed.
