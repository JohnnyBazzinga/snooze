---
title: Snooze security
permalink: /security/
---

# Security at Snooze

Last updated: 25 October 2026

**Snooze: Issue Reminders & Follow-ups for Jira** is built on Atlassian Forge and keeps all data inside Atlassian's platform.

## Architecture

- **Hosting:** the app's code runs on Atlassian Forge. There are no external servers.
- **Storage:** reminders and settings are stored only in Atlassian-hosted Forge storage (Forge SQL and Key-Value Store), isolated per Jira site by Atlassian.
- **No egress:** the app makes no requests outside Atlassian. It is eligible for Atlassian's *Runs on Atlassian* program.
- **No shared secrets:** the app never asks for passwords, API tokens or personal access tokens.

## Data

- **What's stored:** reminder settings, the optional note and Atlassian account IDs. No names, email addresses or issue content.
- **Email delivery:** Jira's own notification system sends the emails, so Jira permissions apply and the app never sees email addresses.
- **Retention:** finished reminders are deleted after 90 days.
- **Closed accounts:** personal data is erased through Atlassian's personal data reporting API.
- **Uninstall:** Atlassian deletes the app's hosted data after uninstall, according to Forge's retention policy.

## Access

- The app requests only the Jira permissions it needs, listed on its Marketplace page.
- The developer has no direct access to customer data. Operational logs, which contain reminder IDs and error messages, are kept in Atlassian's developer console.
- Developer accounts are protected with two-step verification.

## Reporting a vulnerability

Email **[getsnooze.support@gmail.com](mailto:getsnooze.support@gmail.com)** with "Security" in the subject. We acknowledge reports within 2 business days and keep you updated until the issue is resolved.

See also the [Privacy Policy](../privacy/) and [documentation](../docs/).
