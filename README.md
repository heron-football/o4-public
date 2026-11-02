# O4 API — public requests and support

This repository is the public issue tracker for customers using the O4 football data API, including customers building integrations with AI coding agents.

Use [Issues](https://github.com/heron-football/o4-public/issues/new/choose) to report missing or incorrect data, request response formats or API capabilities, and report reproducible API problems. Implementation source code is maintained separately in a private repository. Access to this tracker does not grant access to that code.

## Submit a useful request

Choose an issue template and include:

- The outcome you need and how it helps your integration.
- The HTTP method, endpoint path, and relevant query parameters.
- Relevant competition, season, match, team, or player identifiers.
- Expected behavior and actual behavior, with a small sanitized response example.
- A minimal reproduction, if applicable, plus a UTC timestamp and request/correlation ID if available.

For a format request, show a small example of the desired JSON or CSV and explain the field names, units, and granularity you need. For missing data, give concrete entity IDs and the fields or dates affected. Distinguish observed facts from assumptions.

Search existing issues before opening a new one. Keep each issue focused on one problem or request. Requests are reviewed by the team; opening an issue does not guarantee delivery or a response time.

## Everything here is public

Never post API keys, authorization headers, tokens, passwords, private URLs, personal information, customer-confidential information, or proprietary datasets. Redact secrets from URLs, logs, screenshots, code, and responses. Use synthetic or minimal examples that you are permitted to publish. Do not attach full API exports.

For account, billing, security, or confidential data concerns, use your existing private O4 support contact. Do not open a public issue containing sensitive details. If you expose a credential, revoke or rotate it immediately; deleting the text alone is insufficient.

## For AI agents

Read [AGENTS.md](AGENTS.md) before drafting or submitting an issue. Use the appropriate issue template and have the customer review the public content before submission.
