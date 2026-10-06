# Nasup status

The status page for [Nasup](https://app.nasup.ai), at **[status.nasup.ai](https://status.nasup.ai)**: whether the customer app answers, checked every 5 minutes from outside Cloudflare by [Upptime](https://upptime.js.org) on GitHub Actions, with incidents and planned maintenance.

- **What's checked:** `https://app.nasup.ai/v1/health`, expecting 200 within 5 seconds (`.upptimerc.yml`).
- **Incidents:** an outage opens an issue here and closes it when the app answers again. Short ones are kept on record (`skipDeleteIssues`).
- **Planned maintenance:** an issue labelled `maintenance` with its window, opened at least 3 days ahead (QA-03, NFR-AVL-01).
- **Public by design:** this repository holds the app's public health URL and its up/down history only. No secrets, no customer data.

Nasup's own runbook and alerts live in the private backend repository (`docs/runbooks/on-call.md`). This page is what customers see.

<!--start: status pages-->
<!--end: status pages-->
