---
title: Privacy Policy
permalink: /privacy/
---


_Last updated: 22 October 2026_

This policy explains what data **Snooze: Issue Reminders & Follow-ups for Jira** ("the App") handles when it is installed on an Atlassian Jira Cloud site, and how. The App is published by **João Bastos**, a sole trader based in Portugal ("we", "us"). Contact: **getsnooze.support@gmail.com**.

## Summary

- The App runs entirely on Atlassian's Forge platform. It doesn't send data to any server outside Atlassian. It qualifies for Atlassian's "Runs on Atlassian" programme.
- The App stores only what it needs to send a reminder: Jira identifiers, the schedule, the optional message and recipients' Atlassian account IDs.
- The App does not store names, email addresses or issue content. Jira looks these up when a reminder is sent.
- Jira itself sends reminder emails, using its own notification system.
- Finished reminders are deleted after 90 days.
- There are no cookies, no analytics and no tracking.

## Data the App stores

The App stores this data in Atlassian-hosted storage (Forge SQL and Forge key-value storage) that belongs to your site's installation:

| Data | Why |
|---|---|
| Issue ID, issue key, project ID and site URL | To know which issue a reminder belongs to and to link to it in the email |
| Atlassian account ID of the person who created the reminder | To show them their reminders and let only them cancel them |
| Atlassian account IDs of named recipients, and whether the assignee, reporter or watchers should be notified | To know who to remind |
| Optional reminder message | To include it in the email |
| Date, time, time zone and repeat rule | To send the reminder at the right time |
| Delivery status, number of sends, last send time and last error | To show history and to retry failed deliveries |
| Admin settings (project IDs where reminders are turned off, default options) | To apply your site's configuration |

## Data the App reads but does not store

When a reminder is due, the App asks Jira, on the app's own behalf, for the issue summary and status and for the display name of the person who created the reminder. Jira then sends the email. The App never sees recipients' email addresses.

## Who can access the data

- **Your Jira users:** reminders are shown in the issue panel to people who can view the issue, and in "My reminders" to the person who created them.
- **Atlassian:** Atlassian hosts and processes the data as the platform provider, under the [Atlassian Privacy Policy](https://www.atlassian.com/legal/privacy-policy) and its terms with you.
- **Us:** we do not export or copy your data. Atlassian's developer console shows us operational logs, which contain reminder IDs and error messages returned by Jira. We use them only to troubleshoot problems, and Atlassian keeps them for a limited time.

We do not sell, share or use your data for advertising, profiling or training AI models.

## Retention and deletion

- Pending reminders are kept until they are sent, cancelled or no longer needed (for example, when the issue is deleted).
- Finished reminders (sent, cancelled, skipped or failed) are deleted automatically 90 days after they finish.
- When an Atlassian account is closed, Atlassian's personal data reporting service tells the App. The App then deletes the reminders that person created and removes them from other reminders' recipients.
- When you uninstall the App, Atlassian deletes the App's data according to its Forge hosted storage policy (currently 28 days after uninstallation).

## Your rights

The organisation that owns the Jira site controls the data. Individuals who want to access, correct or delete their data should first contact their Jira site administrator. You can also contact us at **getsnooze.support@gmail.com**; we will help within 30 days.

If you are in the European Economic Area, you also have the right to complain to a data protection authority. In Portugal, that is the Comissão Nacional de Proteção de Dados ([cnpd.pt](https://www.cnpd.pt)).

## Changes

We will post any changes on this page and update the date above. If a change materially affects how data is handled, we will also note it in the App's release notes.
