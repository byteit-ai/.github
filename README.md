<div align="center">
  <a href="https://www.byteit.ai">
    <picture>
      <img src="https://www.byteit.ai/images/logo_light_transparent.webp" alt="ByteIT Logo" height="80" />
    </picture>
  </a>
  <h3>Liberate data from documents.</h3>
  <p>Intelligent document processing that reads scans, tables and handwriting<br/>and returns clean data, checked.</p>

  [![Website](https://img.shields.io/badge/byteit.ai-website-6B75FF?style=flat-square&labelColor=0B0A1A)](https://www.byteit.ai)
  [![Studio](https://img.shields.io/badge/Studio-start%20free-1AC8ED?style=flat-square&labelColor=0B0A1A)](https://studio.byteit.ai)
  [![PyPI](https://img.shields.io/pypi/v/byteit?style=flat-square&label=PyPI&color=6B75FF&labelColor=0B0A1A)](https://pypi.org/project/byteit/)
  [![Trust Center](https://img.shields.io/badge/Trust%20Center-ISO%2FIEC%2027001-28EA8E?style=flat-square&labelColor=0B0A1A)](https://trust.byteit.ai)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-follow-6B75FF?style=flat-square&labelColor=0B0A1A)](https://www.linkedin.com/company/byteit-ai)
</div>

---

## The name

**Byte it.** *Bite*: take a document apart, piece by piece. *Byte*: turn each piece into data. Our mark says both: the outline of a page, bitten into four blocks.

## What ByteIt does

ByteIt turns unstructured documents into structured data you can use in a system, an agent or a spreadsheet. Documents arrive by API, upload, portal, scanner or inbox. Each one is read by the extraction technology that suits it best, every field comes with a confidence score, and people review only what needs it.

| Step | What happens |
|---|---|
| **Classify** | Sort mixed batches and split bundles into documents |
| **Parse** | Read text, tables, formulas, images and charts, including scans and handwriting |
| **Extract** | Return the fields you defined, as JSON, Markdown or text |
| **Validate** | Check each value and flag low-confidence fields for a person |
| **Reconcile** | Match results against the order, ledger or record they belong to |
| **Act** | Send the verified data to your systems |

Pipelines learn from every correction a person makes.

## Benchmark

| Model | OmniDocBench overall |
|---|---|
| **ByteIt** | **88.6** |
| Mistral OCR | 78.9 |
| Claude Sonnet | 78.8 |
| Azure Document Intelligence | 55.5 |

<sub>Source: OmniDocBench, as reported in our blog post [Glasses for your AI agent](https://www.byteit.ai/blog).</sub>

## Build with ByteIt

The SDKs are generated from the same contract as the API and share one version.

| Language | Package | Where |
|---|---|---|
| Python | `byteit` | [PyPI](https://pypi.org/project/byteit/) |
| TypeScript | `@byteit/sdk` | [GitHub](https://github.com/byteit-ai/byteit-sdk/tree/main/typescript) |
| C# / .NET | `ByteIt` | [GitHub](https://github.com/byteit-ai/byteit-sdk/tree/main/dotnet) |
| Java, Go, Ruby, PHP, Swift, Rust | n/a | On request: support@byteit.ai |

```bash
pip install byteit
```

```python
from byteit import ByteIt

client = ByteIt(api_key="YOUR_API_KEY")

text = client.parse("invoice.pdf")  # the parsed document, as bytes
```

Python has a sync client (`ByteIt`) and an async one (`AsyncByteIt`). Every client raises typed errors and retries automatically. See the [SDK repository](https://github.com/byteit-ai/byteit-sdk) for extraction schemas, classification and the full reference. ByteIt also works with AI agents over REST and MCP.

## Plans

[See pricing](https://www.byteit.ai/pricing).

## Security and data

- Processed in the EU. Built in Germany.
- ISO/IEC 27001 certified. GDPR compliant, with a data processing agreement.
- You decide what we keep: from encrypted 7-day retention to zero data retention.
- Hybrid and on-premises deployment for Enterprise.

Details and certificates are in the [Trust Center](https://trust.byteit.ai).

## Where teams use it

Invoices, contracts and claims. Bank statements and proofs of residence. Certificates of analysis and insurance. Delivery notes and bylaws. Browse the [document types](https://www.byteit.ai/documents) we read, with a live extraction demo for each.

## Links

[Website](https://www.byteit.ai) · [Studio](https://studio.byteit.ai) · [Documents](https://www.byteit.ai/documents) · [Pricing](https://www.byteit.ai/pricing) · [Blog](https://www.byteit.ai/blog) · [Support](https://www.byteit.ai/support) · [Trust Center](https://trust.byteit.ai) · [LinkedIn](https://www.linkedin.com/company/byteit-ai) · [Contact](https://www.byteit.ai/contact)

<div align="center">
  <sub>© 2026 ByteIT GmbH · All rights reserved</sub>
</div>
