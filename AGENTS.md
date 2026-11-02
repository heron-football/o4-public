# Instructions for customer AI agents

This repository is a public support and feature-request tracker for the O4 football data API. It contains no implementation source code.

When a customer asks you to report a problem or request a change:

1. Read README.md and search existing issues for the same request. Add useful context to an existing issue when appropriate.
2. Choose the matching template in .github/ISSUE_TEMPLATE/.
3. Describe the customer's goal, the endpoint and parameters, relevant entity IDs, and expected versus observed results. For format requests, provide a small desired-output example with field meanings and units.
4. Include a minimal sanitized reproduction where possible. Report timestamps in UTC and request/correlation IDs if available. State what you verified and what remains uncertain; do not invent API behavior or data.
5. Remove credentials, authorization headers, tokens, sensitive URLs, personal information, confidential customer information, and proprietary data. Prefer synthetic examples and never attach full exports.
6. Show the complete proposed issue to the customer and obtain their approval before publishing it or posting a comment. Do not submit automatically merely because an API call failed.
7. Use the customer's existing private O4 support contact for account, billing, security, or confidential concerns.

Keep each issue focused on one request. Do not claim access to the private implementation or promise a fix or delivery date.
