---
layout: post
title: "AI Sucks (for Regulatory Reporting)"
date: 2025-11-26
image: /assets/images/gpus.jpg
author: Ben Joyce FIA C.Act BA
description: Why you should stop using AI and learn to love databases and Excel.

ogtype: article
ogtitle: AI Sucks (for Regulatory Reporting)
ogdescription: Why you should stop using AI and learn to love databases and Excel
ogimage: /assets/images/gpus.jpg
ogimagealt: A photo of some slightly smashed and burned GPUs
---

AI sucks for reporting.

Canon said it: [Is data readiness the key to successful AI adoption?](https://www.itnews.asia/news/is-data-readiness-the-key-to-successful-ai-adoption-620721)

IBM said it: [Putting AI to work in finance](https://www.ibm.com/think/insights/putting-ai-to-work-in-finance)
<br />*(sort of, you need to focus on the sentence "AI and gen AI initiatives can only be as successful as the underlying data permits.")*

And I'm saying it.

Don't get me wrong, I think AI is amazing. Just look at the banner image for this post - that took ChatGPT 5.1 about 2 minutes to create. Incredible!

And AI can perform amazing analysis on well-structured data.

But what AI can't do (yet) is connect to your internal databases and reliably extract the exact number you need to report to your national regulator. How many times have you asked your AI agent something for it to give you a completely inaccurate answer, and when you call it out it just says "You're right!"? That's not helpful. If anything it wastes more time than it saves.

For accurate regulatory reporting you need three things:
- Good old fashioned structured databases
- Specialised software to convert the data you need to report into the appropriate format
- Humans

But hey, I'm just a human. What do I know?! Let's ask AI what it thinks with a (slightly biased) prompt: "Why is AI not suitable for financial reporting?"

See what it had to say about itself, complete with all the usual em-dash loveliness.

>Why AI Is Not Suitable for Financial Reporting
>---
>
>AI—especially large language models—excels at generating plausible text and summarising patterns, but financial reporting is the opposite of what AI is good at. Regulatory reporting demands determinism, reproducibility, auditability, and strict adherence to taxonomies. AI systems fundamentally lack those guarantees.
>
>Below are the core reasons.
>
>⸻
>
>1\. Financial reporting must be deterministic. AI is probabilistic.
>
>Regulators expect that:
> - Given the same inputs,
> - A reporting system must produce exactly the same output every time.
>
>AI models, by design:
> - Produce outputs via probability distributions
> - Are non-deterministic unless aggressively sandboxed
> - Can produce inconsistent responses run-to-run
>
>Even with temperature = 0, internal model updates can change behaviour without notice.
>
>For a regulatory return, that’s unacceptable.
>
>⸻
>
>2\. Financial reporting has zero tolerance for hallucinations. AI has no such guarantee.
>
>LLMs sometimes:
> - Infer missing data
> - “Fill in gaps”
> - Fabricate plausible-sounding values or structures
>
>Regulatory reporting requires:
> - No invented facts
> - No inference
> - No assumptions
> - Exact calculations based only on the dataset
>
>A hallucination in a DPM fact, an IRRD table, or a Solvency II quantitative figure would result in report rejection, penalties or supervisory escalation.
>
>⸻
>
>3\. Taxonomies and rulebooks are rigid. AI is not.
>
>XBRL taxonomies (e.g., EBA v4.0, Solvency II, PRA liquidity, forthcoming IRRD) impose:
> - Strict data types
> - Precise constraints
> - Explicit formula linkbases
> - Well-defined validation rules
> - Mandatory filing structures down to ZIP contents and filename conventions
>
>AI models:
> - Are not schema-aware
> - Do not enforce type safety
> - Cannot guarantee correct namespace handling
> - May violate dimensional or hierarchy constraints
>
>Financial reports must be machine-validated, something AI is not built to satisfy.
>
>⸻
>
>4\. AI can’t guarantee auditability or traceability
>
>Regulatory reporting frameworks demand:
> - Full audit trail
> - Line-by-line traceability
> - Clear provenance of each number (data lineage)
>
>LLMs:
> - Do not expose internal decision paths
> - Cannot justify why a particular number was produced
> - Have no intrinsic logging of reasoning steps
> - Are unrepeatable at a micro-level
>
>You cannot base a regulated process on a system that cannot explain itself.
>
>⸻
>
>5\. Security and confidentiality concerns
>
>Financial institutions handle:
> - Policyholder information
> - Balance sheets
> - Solvency capital data
> - Liquidity positions
> - Scenario stress results
>
>Most AI models:
> - Are cloud-hosted
> - Produce embeddings or logs
> - Are not tailored for regulatory-class confidentiality
> - May not meet operational resilience requirements (DORA!)
>
>DORA in particular requires:
> - End-to-end control of critical ICT services
> - Predictable, tested, stress-resistant systems
> - Avoiding opaque, non-deterministic external systems
>
>AI fails most of these tests.
>
>⸻
>
>6\. Regulators expect interpretability, not creativity
>
>Reporting systems must:
> - Apply formulae exactly
> - Follow prescriptive rules
> - Provide clear validation errors
> - Be stable over multiple reporting cycles
>
>AI systems:
> - Optimise for creativity or pattern generation
> - May reformat outputs spontaneously
> - Cannot guarantee stability across model versions
>
>Imagine GPT deciding to “simplify” an XBRL-CSV file.
>That’s an instant filing rejection.
>
>⸻
>
>7\. Financial reporting is already fully machine-checkable
>
>This is the crucial point:
>Regulatory reporting does not need interpretation or judgement.
>It needs precision engineering.
>
>XBRL, DPM, and CSV formats are:
> - Already deterministic
> - Already schema-driven
> - Already validated by rule engines
> - Already governed by formal specifications
>
>There is no ambiguous “language” for AI to interpret—just structured data.
>
>AI adds risk, not value, at the core reporting layer.
>
>⸻
>
>So where is AI useful?
>
>AI is helpful around financial reporting, but not inside it:
> - Explaining validation errors
> - Assisting with data mapping or schema comparisons
> - Summarising regulatory updates
> - Helping developers understand taxonomy changes
> - QA support, documentation, onboarding
>
>But not:
> - Producing facts
> - Converting templates
> - Mapping cells
> - Generating final XBRL/XML/CSV
> - Validating filings
> - Creating regulatory numbers
>
>Those must remain deterministic systems.

Couldn't have put it better myself. Well done, AI... this time.