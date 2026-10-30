<p align="center">
  <img src="https://raw.githubusercontent.com/anyformat-ai/.github/main/profile/banner.png" alt="anyformat: from docs to data. Agentic document processing platform" width="100%">
</p>

**From docs to data.** anyformat is an agentic document processing platform. It turns scans, multi-page tables and photos of paperwork into structured data, and every field links back to the exact spot in the document, with a confidence score.

[Website](https://anyformat.ai) · [Docs](https://docs.anyformat.ai) · [Get an API key](https://app.anyformat.ai/api-key)

## Start in 3 steps

**1. Create your API key** at [app.anyformat.ai/api-key](https://app.anyformat.ai/api-key)

```bash
export ANYFORMAT_API_KEY=your_key
```

**2. Install the SDK**

```bash
pip install anyformat            # Python
npm install @anyformat/sdk       # Node
```

**3. Connect anyformat to your agent**

```bash
claude mcp add --transport http anyformat https://api.anyformat.ai/mcp \
  --header "Authorization: Bearer $ANYFORMAT_API_KEY" --scope user
```

Cursor, Codex and OpenCode: [see the docs](https://docs.anyformat.ai/guides/connect-your-agent).

## What anyformat does

**Hard documents, at scale.** Scans, multi-page tables, photos of paperwork, layouts that change with every supplier, documents in many languages. Everything anyformat extracts links back to the exact spot in the document, so you don't have to go looking.

<p align="center">
  <img src="https://raw.githubusercontent.com/anyformat-ai/.github/main/profile/interface.png" alt="anyformat interface: an invoice with the extracted fields highlighted on the page" width="100%">
</p>

**Smarter with every iteration.** Your workflow gets more accurate over time, and nothing goes to production until it passes your criteria.

**Any format, any layout.** 100+ formats: PDF, Word, Excel, PNG, JPG, email, XML and more. Scanned or digital, it comes out as structured data.

**Any workflow.** Split, classify and extract.

<details>
<summary>Examples of workflows</summary>

Supplier invoices, purchase orders and delivery notes, contractor compliance, maintenance records, packaging artwork, patient records, KYC and credit files, contracts and court filings, calibration certificates, hotel contracts and availability notices, engineering and project archives, ESG and sustainability reports, utility bills and waste records, public sector forms, HR records, emails and attachments, shipping and logistics, claims and disputes, bank statements, tax forms.

</details>

**Delivered where you need it.** To Excel, your CRM or ERP, your AI agents, or wherever you need it, via API, SDKs and MCP. Connect it to your own agent: Claude, Codex, Gemini.

**Meet annie, our AI agent.** Describe what you need and set up your workflow in minutes.

## Enterprise-ready

GDPR-native · EU processing · SaaS with EU hosting · Self-hosting option · Zero-retention mode · ISO 27001:2022 certified · Integrates into your systems.

Need it on your own infrastructure? Self-hosting is not self-serve: [contact us](mailto:info@anyformat.ai) and we set it up with you.

## Recognized

#1 in Europe for parsing quality on the independent benchmark at [parsebench.ai](https://parsebench.ai), October 2026. Featured in Verdantix's Market Insight on emerging AI-native document processing platforms.

## Try it

| Repo | What it does |
| --- | --- |
| [portima-hackathon-starter](https://github.com/anyformat-ai/portima-hackathon-starter) | Turn accident statements and order forms into data, scored field by field |
| [llm-wiki](https://github.com/anyformat-ai/llm-wiki) | Turn documents into a cited, self-maintaining knowledge base in Obsidian |

## Questions

[info@anyformat.ai](mailto:info@anyformat.ai) · [docs.anyformat.ai](https://docs.anyformat.ai)
