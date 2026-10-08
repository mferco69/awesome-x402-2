# Awesome x402 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome [x402 protocol](https://x402.org) projects, tools, and resources for AI agent commerce.

x402 is an open payment protocol (initiated by Coinbase) that turns HTTP 402 "Payment Required" into a real payment flow. AI agents pay for API calls with USDC micropayments on Base network — no API keys, no subscriptions.

**Stripe [just launched](https://x.com/jeff_weinstein/status/1889048618975158752) x402 support** on Feb 10, 2026, making this the standard for machine-to-machine payments.

## Contents

- [Protocol & Standards](#protocol--standards)
- [Facilitators](#facilitators)
- [Services & Endpoints](#services--endpoints)
- [SDKs & Libraries](#sdks--libraries)
- [MCP Servers](#mcp-servers)
- [Tools & Infrastructure](#tools--infrastructure)
- [Ecosystem Platforms](#ecosystem-platforms)
- [Learning Resources](#learning-resources)
- [Community](#community)

## Protocol & Standards

- [x402 Protocol Spec](https://github.com/coinbase/x402) - Official x402 protocol specification by Coinbase.
- [x402.org](https://x402.org) - Official x402 protocol website and documentation.
- [ERC-8004](https://eips.ethereum.org/EIPS/eip-8004) - ERC standard for agent-native commerce (related).

## Facilitators

Facilitators verify payments and enable the x402 flow.

| Name | Network | Currency | Status |
|------|---------|----------|--------|
| [Coinbase x402](https://x402.org) | Base | USDC | ✅ Live |
| [Stripe x402](https://stripe.com) | Base | USDC | ✅ Live (Preview) |

## Services & Endpoints

Projects offering pay-per-call APIs via x402.

| Name | Description | Endpoints | Settlement | Status |
|------|-------------|-----------|------------|--------|
| [AsterPay](https://asterpay.io) | EUR settlement layer for AI agent commerce. Market data, sentiment, DeFi analytics, whale tracking, and more. | 13 | EUR (SEPA Instant) | ✅ Live |
| [CDAS](https://x402.org/ecosystem) | Crypto Data Analytics Service | - | USDC | ✅ Live |
| [JMT x402 Agent Tools](https://jmt-x402-proxy.jmthomasofficial.workers.dev) | 25 paid endpoints: web search, AI analysis, crypto data, SEC filings, company intel, news briefing, sentiment, macro dashboard. USDC on Base. | 25 | USDC (Base) | ✅ Live |
| [The Musebook Times](https://musebooktimes.com) | News wire JSON feed, full article archive, and editions catalog. | 3 | USDC (Base) | ✅ Live |

> **Add your project!** Open a PR to add your x402-enabled service.

## SDKs & Libraries

- [@x402/fetch](https://www.npmjs.com/package/@x402/fetch) - Drop-in replacement for `fetch()` that handles x402 payments automatically.
- [@x402/express](https://www.npmjs.com/package/@x402/express) - Express middleware for x402 payment gating.
- [@asterpay-io/x402](https://www.npmjs.com/package/@asterpay-io/x402) - AsterPay x402 middleware with EUR settlement.

## MCP Servers

MCP (Model Context Protocol) servers that enable AI agents to interact with x402 services.

| Name | Package | Description |
|------|---------|-------------|
| [AsterPay MCP Server](https://github.com/timolein74/asterpay-mcp-server) | `@asterpay/mcp-server` | 13 data endpoints for Claude, Cursor, and MCP-compatible AI agents. |

## Tools & Infrastructure

- [x402scan.com](https://x402scan.com) - x402 ecosystem explorer. Tracks live x402 endpoints, transaction volumes, and reliability.
- [x402.eco](https://x402.eco) - Community-built ecosystem directory for x402 services.

## Ecosystem Platforms

Platforms where x402 services are listed or integrated.

| Platform | Type | AsterPay Listed |
|----------|------|-----------------|
| [Coinbase x402 Ecosystem](https://x402.org/ecosystem) | Official directory | ✅ Yes |
| [x402scan.com](https://x402scan.com) | Endpoint tracker | ✅ Yes |
| [Bankr OpenClaw](https://github.com/BankrBot/openclaw-skills) | AI agent skills | 🔄 PR #123 |
| [Circle Arc](https://arc.network/ecosystem) | USDC ecosystem | 📝 Submitted |
| [ClawGig](https://clawgig.ai) | AI agent marketplace | ✅ Registered |
| [mcp.so](https://mcp.so) | MCP server directory | 📝 Pending |
| [glama.ai](https://glama.ai/mcp) | MCP server directory | 📝 Pending |

## Learning Resources

- [x402 Protocol Documentation](https://x402.org/docs) - Official docs.
- [How to Charge AI Agents for Your API](https://dev.to/asterpay) - Tutorial on DEV.to.
- [Stripe Machine Payments Announcement](https://x.com/jeff_weinstein/status/1889048618975158752) - Jeff Weinstein's thread on Stripe x402.
- [Why EUR Settlement Matters for x402](https://asterpay.io/docs) - AsterPay's guide for European developers.

## Community

- [Coinbase Developer Discord](https://discord.gg/cdp) - Official `#x402` channel.
- [Telegram: AsterPay Community](https://t.me/asterpaycommunity) - AsterPay community.
- [Twitter/X: @Asterpayment](https://x.com/Asterpayment) - AsterPay updates.

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

To add your x402 project:
1. Fork this repo
2. Add your project to the relevant section
3. Open a Pull Request

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released into the public domain.
