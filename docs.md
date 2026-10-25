---
title: Snooze documentation
permalink: /docs/
---

# Snooze documentation

Snooze puts reminders on Jira issues and sends them by email, only while they're still needed.

## Getting started

1. Install **Snooze: Issue Reminders & Follow-ups for Jira** from the Atlassian Marketplace.
2. Open any issue. In the right-hand column, expand **Snooze reminders**.
3. Click **Add reminder**, choose when and who, and click **Set reminder**.

Reminders are checked every 5 minutes and arrive as a Jira email with a link to the issue.

## Creating a reminder

**When**
- Quick picks: *In 1 hour*, *In 3 hours*, *Tomorrow 09:00*, *Monday 09:00*.
- *Pick a date…* for any date and time.
- *Before due date* (shown when the issue has a due date): on the due date, 1, 2 or 3 days, 1 or 2 weeks before, at a time you choose.

The blue preview shows exactly when the reminder will be sent, in your Jira time zone.

**Repeat:** once, every day, every weekday, every week or every month, always at the same local time.

**Who gets it:** you, the assignee, the reporter, the watchers, up to 20 named people and up to 5 Jira groups. Roles are resolved when the reminder is sent, so a new assignee gets it.

**Note:** optional text included in the email.

## Follow-up mode

Turn on **Follow-up mode** to send the reminder only if nobody has updated the issue since you set it. Any comment, field change or transition counts as an update.

With a repeat, a follow-up keeps nudging on schedule until someone acts on the issue, and then stops by itself.

## Due date reminders

A reminder set *before the due date* follows the issue's due date. If the due date changes, the reminder moves with it (checked every hour and again just before sending). If the due date is removed, the reminder is skipped.

## Stop when done

With **Stop when done** on, a reminder is skipped once the issue is in a Done status. Admins choose whether it's on by default.

## Managing reminders

- In the issue panel, the person who created a reminder can **edit** or **cancel** it.
- **Apps → Snooze – My reminders** lists everything you scheduled across Jira, with an **Upcoming** tab and a **History** tab showing what was sent, skipped or cancelled.

## Settings for Jira admins

**Jira settings → Apps → Snooze settings**:
- turn reminders off for specific projects (pending reminders there are not sent);
- choose the default for *Stop when done*.

## FAQ

**Who sends the email?** Jira itself, through its notification system. Recipients only get reminders for issues they're allowed to see, and Snooze never sees email addresses.

**Which time zone is used?** The time zone in the creator's Jira profile. Repeating reminders keep the same local time across daylight saving changes.

**What data does Snooze store?** Reminder settings, the optional note and Atlassian account IDs, all inside Atlassian's platform. Finished reminders are deleted after 90 days. See the [Privacy Policy](../privacy/).

**Something isn't working?** Email [getsnooze.support@gmail.com](mailto:getsnooze.support@gmail.com).
