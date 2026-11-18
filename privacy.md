---
title: Lumo AI Privacy Policy
---

# Lumo AI Privacy Policy

**Last updated: November 18, 2026**

## About Lumo

Lumo is a personal, self-hosted AI assistant project. This policy describes the intended data handling for its optional Google Calendar integration. **The integration is not yet activated for live Google accounts.** We will update this policy if the implementation or data practices change before or after activation.

**Contact:** [greasebotai@gmail.com](mailto:greasebotai@gmail.com)

## Information accessed

If a Google account holder explicitly authorizes Lumo, the Calendar integration is intended to access event information from an approved Google Calendar. This may include event titles, times, descriptions, locations, and other event details needed to answer requests or create events.

The app requests the Google Calendar events OAuth permission (`https://www.googleapis.com/auth/calendar.events`). Although Google's scope can cover events on calendars accessible to the authorized account, Lumo's intended application-level configuration restricts its operations to the specifically approved family calendar.

This integration does **not** request Gmail or Google Drive access.

## How Calendar information is used

Calendar information is intended to be used only to respond to authorized requests, such as listing upcoming events, searching a date range, and creating a new event after explicit confirmation.

Relevant event details may be included in a response to the requesting authorized user and processed by the locally hosted assistant as necessary to fulfill the request.

We do not intend to sell Calendar information, use it for advertising, or share it with data brokers. Google Calendar data is transmitted to Google's APIs to carry out authorized Calendar operations.

## Storage and security

The intended design stores OAuth credentials in access-restricted encrypted storage on the self-hosted system. Credentials are not intended to appear in model prompts, chat responses, public repositories, or coding workspaces.

The application may retain minimal operational records and pending actions needed for confirmation, duplicate prevention, and error recovery. Calendar content is not intended to be published to this website or GitHub repository.

Actual retention periods and deletion procedures for operational records will be documented when the live integration is activated.

## Access and control

The Google account holder chooses whether to grant access through Google's OAuth consent screen. Authorized assistant users may access the configured shared calendar according to the application's access controls; being allowed to use shared Calendar functions does not grant access to other users' private conversations.

A user can revoke the OAuth grant from their [Google Account third-party connections](https://myaccount.google.com/connections). The system administrator can also disable the Calendar integration and remove its locally stored credentials.

Revoking Google access prevents further authorized Calendar API access, but does not automatically delete calendar events previously created in Google Calendar or local operational records. For questions about removal of locally held integration data, email the contact address above.

## Google API data use

Any use of information received from Google APIs will be subject to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including its Limited Use requirements where applicable.

## Changes

This policy may be updated as Lumo moves from offline testing to live use or adds new optional integrations. The last-updated date above will reflect material changes.
