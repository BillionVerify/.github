# BillionVerify

<div align="center">

[![Website](https://img.shields.io/badge/Website-billionverify.com-0070f3)](https://billionverify.com)
[![Docs](https://img.shields.io/badge/Docs-API%20Reference-181717)](https://billionverify.com/docs/api-reference)
[![Email](https://img.shields.io/badge/Email-support%40billionverify.com-EA4335)](mailto:support@billionverify.com)

**Email verification for sign-up forms, CRMs and outbound lists.**

[Website](https://billionverify.com) • [Quick start](https://billionverify.com/docs/quickstart) • [API reference](https://billionverify.com/docs/api-reference) • [Integrations](https://billionverify.com/docs/integration-guides)

</div>

---

## What BillionVerify does

BillionVerify checks whether an email address can receive mail before you send to it, so bounces and fake sign-ups stay out of your lists.

- **Real-time verification** for a single address, built into sign-up and checkout forms. [Learn more](https://billionverify.com/email-verification)
- **Bulk verification and list cleaning** for CSV files and existing lists. [Learn more](https://billionverify.com/bulk-email-verification)
- **Risk signals** beyond valid / invalid: [catch-all domains](https://billionverify.com/catch-all-verifier), [disposable addresses](https://billionverify.com/disposable-email-detection) and [role accounts](https://billionverify.com/role-account-detection).
- **Free email tools** for SPF, DKIM, DMARC, MX and blacklist checks. [Browse the tools](https://billionverify.com/free-email-tools)

## Quick start

Create an API key in the BillionVerify dashboard, then verify an address:

```bash
curl -X POST https://api.billionverify.com/v1/verify/single \
  -H "BV-API-KEY: YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"email": "test@example.com"}'
```

Base URL `https://api.billionverify.com/v1`. The full contract is in the [API reference](https://billionverify.com/docs/api-reference) and the [OpenAPI spec](https://api.billionverify.com/openapi.yaml).

## Open-source projects

| Project | What it is |
| --- | --- |
| [billionverify-node](https://github.com/BillionVerify/billionverify-node) | Node.js SDK |
| [billionverify-python](https://github.com/BillionVerify/billionverify-python) | Python SDK |
| [billionverify-go](https://github.com/BillionVerify/billionverify-go) | Go SDK |
| [billionverify-java](https://github.com/BillionVerify/billionverify-java) | Java SDK |
| [billionverify-php](https://github.com/BillionVerify/billionverify-php) | PHP SDK |
| [billionverify-cli](https://github.com/BillionVerify/billionverify-cli) | Command-line tool |
| [billionverify-mcp](https://github.com/BillionVerify/billionverify-mcp) | MCP server for AI assistants |
| [billionverify-skill](https://github.com/BillionVerify/billionverify-skill) | Agent skill for AI coding agents |
| [wordpress](https://github.com/BillionVerify/wordpress) | WordPress plugin |
| [n8n-nodes-billionverify](https://github.com/BillionVerify/n8n-nodes-billionverify) | n8n community node |
| [disposable](https://github.com/BillionVerify/disposable) | Open-source disposable email detection |

SDK docs: [billionverify.github.io](https://billionverify.github.io)

## Use it where you already work

- **Forms and CMS**: [WordPress](https://billionverify.com/docs/integration-guides/cms-platforms/wordpress), [Google Forms](https://billionverify.com/docs/integration-guides/form-builders/google-forms), [Typeform](https://billionverify.com/docs/integration-guides/form-builders/typeform)
- **E-commerce**: [Shopify](https://billionverify.com/docs/integration-guides/ecommerce/shopify), [WooCommerce](https://billionverify.com/docs/integration-guides/ecommerce/woocommerce)
- **CRM and email marketing**: [HubSpot](https://billionverify.com/docs/integration-guides/marketing-crm/hubspot), [Mailchimp](https://billionverify.com/docs/integration-guides/marketing-crm/mailchimp)
- **Automation**: [Zapier](https://billionverify.com/docs/integration-guides/automation/zapier)
- **AI agents**: [MCP server](https://billionverify.com/docs/ai-guides/mcp), [agent skills](https://billionverify.com/docs/ai-guides/agent-skills)

## Support

- Email: [support@billionverify.com](mailto:support@billionverify.com)
- Documentation: [billionverify.com/docs](https://billionverify.com/docs)
- Guides: [Email Marketing Bible](https://billionverify.com/email-marketing-bible) and the [blog](https://billionverify.com/blog)
