---
layout: default
title: Privacy Policy
---

[Home](./) | [Terms of Use](./terms.html)
# Privacy Policy ΓÇö BidReady Intelligence

**Effective / last updated:** November 13, 2026  
**Publisher:** Lucas Matheson ΓÇö Independent Developer  
**Contact:** mathesonlj16+bidready@gmail.com

BidReady Intelligence ("BidReady") is an Atlassian Forge application that demonstrates source-linked evaluation of procurement eligibility using fictional tenders and evidence. This policy explains how the app handles information when you install or use it.

## Information handled by BidReady

- **Assessment content you provide:** tender identifiers, source excerpts, qualification requirements, evidence descriptions, document citations, review decisions, dates, and version history.
- **Atlassian user and site context:** BidReady uses the signed-in user's Atlassian account ID and Jira installation context to determine which assessment can be accessed. The app hashes the account ID to construct a user-specific storage key; the hash is a persistent pseudonymous identifier.
- **Limited Jira information:** when you ask to preview an internal remediation task, BidReady checks the selected Jira project's metadata, available issue types and your permissions. Some development-only demonstrations can create a fictional Jira Task with your express confirmation.
- **Optional Rovo interaction:** when you invoke BidReady Feasibility, the Forge action supplies your current reviewed assessment, citations and a generated invocation receipt to Atlassian Rovo. Forge logs may include the receipt and assessment revision.
- **Contact inquiries:** if you email support, your email address and the contents of your message are handled by the support mailbox to respond.

Please **do not enter real confidential procurement records, client personal information or sensitive data**. This is a demonstration application, not an approved store for such data.

## Why this information is used

To persist your reviewed assessment and history, enforce isolation between users and Jira installations, display source-linked decisions, show read-only remediation previews, support Rovo explanations at your request, and diagnose technical issues.

BidReady does not use assessment content for marketing or advertising and does not sell it.

## Where information is stored and processed

The application runs on Atlassian Forge and stores assessment records in Forge Key-Value Storage. Atlassian scopes Forge-hosted storage to the app's installation and environment; BidReady additionally partitions tender records by an account-derived key. The reviewed version has no declared external backend or outbound remote for assessment processing. Atlassian's own privacy, security, subprocessors and retention practices apply to its hosted infrastructure and Rovo services.

Your Jira site may control the region where Forge-hosted persistent data is stored through Atlassian's data residency features.

## Jira permissions and changes

The app requests `read:jira-work`, `write:jira-work` and `storage:app` in its Forge manifest. The `write:jira-work` consent permission is broad, but **BidReady's current production demo workflow disables Jira issue creation**. Controlled fictional Jira Task creation is only available in specially configured development environments, requires an explicit preview and confirmation, and checks permissions and the target project. This description is of the current code, not a promise that future releases will never change.

## Retention, deletion and requests

Assessment revisions are stored in Forge storage while an installation remains in use, unless removed through an applicable technical process. **The current app does not provide an in-app button to erase your entire assessment history.** Contact the support email above to discuss an access, correction or deletion request; we will assess the request and the available platform mechanisms rather than promise immediate self-service erasure.

Atlassian's Forge documentation states that hosted-storage data is soft-deleted on app uninstall and can be retained for up to **28 days**, with eligible recovery requests submitted within **21 days** subject to consent. Operational logs and support email may follow separate Atlassian or Gmail retention policies.

If you wish to limit stored data, do not load or enter information you do not want persisted. Uninstalling an app can affect access to its stored information.

## Security and your choices

BidReady uses authenticated Jira identity and installation context and treats document excerpts as untrusted input. Forge manages infrastructure security controls. No system can guarantee perfect security.

You can choose not to seed the fictional data, not to request a Rovo explanation, and not to initiate Jira task previews. Contact support for privacy questions or requests.

## Changes

This policy may change if the app's functionality or data handling changes. The most recent version will be available at this page, with an updated date.

**Questions:** mathesonlj16+bidready@gmail.com

*This policy describes the current software implementation and is not a certification of compliance with any particular privacy law.*