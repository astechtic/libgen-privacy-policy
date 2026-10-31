---
title: Privacy Policy
permalink: /privacy-policy/
---

# Privacy Policy

**Effective date:** 31 October 2026

This policy covers **Maya** (“the app”, “we”), the publishing tool behind *Arxiv with Maya*. Maya makes short explainer videos about research papers and tech news, then publishes them to accounts that the account owner has connected: YouTube, Blogger, Instagram, Facebook Pages, Threads and X.

Maya is a private tool. Only its operator uses it, and only for accounts they own or manage. It has no public sign-up, and it doesn't collect data about the people who watch or read the published content.

## What we collect

When an account owner connects a platform, Maya receives and stores:

| Data | Why |
|---|---|
| OAuth access and refresh tokens | to upload and publish content on the owner's behalf |
| Account or channel ID, name and handle | to show which account is connected and to post to it |
| IDs and links of the posts Maya publishes | to show publishing status, update the blog with video links, and delete a post when the owner asks |

Maya does **not** collect passwords, payment details, contacts, private messages, or the personal data of viewers, subscribers or followers.

## Google user data

Maya asks for these Google scopes:

- `https://www.googleapis.com/auth/youtube.upload`: upload videos to the connected YouTube channel
- `https://www.googleapis.com/auth/youtube.force-ssl`: set titles, descriptions, thumbnails and scheduled publish times, and manage the videos Maya uploaded
- `https://www.googleapis.com/auth/blogger`: create and update posts on the connected Blogger blog

Google data is used **only** to publish and manage content that the owner tells Maya to publish. Maya's use of information received from Google APIs follows the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements. In particular, Google user data is:

- never sold
- never used for advertising
- never used to train AI or machine-learning models
- never shared with anyone else, except as needed to provide the publishing feature, to comply with the law, or with the owner's explicit consent
- never read by a human, except with the owner's consent, for security, or to comply with the law

Maya uses YouTube API Services. By connecting YouTube you agree to the [YouTube Terms of Service](https://www.youtube.com/t/terms), and Google's handling of your data is covered by the [Google Privacy Policy](https://policies.google.com/privacy).

## Meta (Instagram, Facebook, Threads) and X

Maya uses the Meta Graph APIs and the X API only to publish the owner's videos and posts to the owner's own accounts. It doesn't read feeds, followers, messages or insights.

## How data is stored

- Tokens are **encrypted** before storage.
- Data lives on the operator's private server (Oracle Cloud) and in a private database (MongoDB Atlas). Encrypted backups are kept in a private storage channel.
- All connections to platforms use HTTPS.
- Only the operator can reach the dashboard, and it requires an access token.

## How long we keep it

Tokens and account details are kept until the account is disconnected in Maya, at which point they are deleted. Records of published posts (IDs and links) are kept for as long as the content exists, so it can be updated or removed. Backups roll over and are replaced regularly.

## Revoking access and deleting data

You can revoke Maya's access at any time:

- **Google / YouTube / Blogger:** [myaccount.google.com/permissions](https://myaccount.google.com/permissions)
- **Facebook / Instagram:** Facebook → Settings & privacy → Settings → Business integrations (or Apps and websites) → remove the app
- **Threads:** Threads → Settings → Account → Website permissions → remove the app
- **X:** [x.com/settings/connected_apps](https://x.com/settings/connected_apps)

To have all data Maya holds about your account deleted, email the address below. We delete it within 30 days and confirm by email.

## Children

Maya is not for children under 13 and doesn't knowingly collect their data.

## Changes

If this policy changes, we update the effective date above. Material changes are noted on this page.

## Contact

Questions or deletion requests: **arxivmaya@gmail.com**
