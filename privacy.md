---
title: Privacy Policy
permalink: /privacy/
---

# Privacy Policy

_Last updated: 2026-07-16_

Stoics ("the app") is operated by Andrew Rettek ("we", "us"). This policy
describes what data we collect, why, and how it is handled.

## What we collect

**Device identifier.** When you first launch the app, we generate a random
identifier (a UUID) and store it on your device. The identifier lets us
associate your subscription with your installation. We do not use Apple's
IDFA, and we do not link this identifier to any other account, name, or
email address you have not provided.

**Your messages.** When you send a message in a conversation, the message
text is transmitted to our server and forwarded to an AI model provider so
that a reply can be generated. Each reply is then transmitted back to your
device and stored locally in your installation of the app.

For up to seven days after a message is sent, we retain it on our server in
order to give the AI model conversational context for follow-up turns and
to investigate abuse, errors, or service problems. After seven days, server
copies of conversation content are deleted on a rolling basis.

**Subscription state.** When you purchase or restore a subscription, Apple
returns a signed transaction receipt. We forward that receipt to our server
to verify the subscription is valid and to record its expiration date. We
do not receive your name, email address, billing address, or payment card
information from Apple. Apple's privacy practices are described in their
Customer Privacy Policy.

**Diagnostics.** We log server-side errors and request metadata (timestamp,
HTTP status, generic error class) for the purpose of operating the service.
These logs do not contain message content beyond what is required to debug
a specific failure.

## What we do not do

- We do not sell or share your data with advertisers.
- We do not use third-party analytics SDKs in the app.
- We do not perform any tracking as defined by Apple's App Tracking
  Transparency framework.
- We do not attempt to identify you across apps or websites.

## Third-party processors

To deliver the service, we send message text to an AI model hosted by
DeepInfra, Inc., who routes it to DeepSeek models. DeepInfra processes the
text solely to generate a reply and does not retain it beyond the duration
of the request. See DeepInfra's privacy policy at
[deepinfra.com/privacy](https://deepinfra.com/privacy) for their full
terms.

Subscription transactions are processed entirely by Apple via StoreKit.
Server infrastructure is hosted on Amazon Web Services in the United
States.

## Children

Stoics is rated 9+ on the App Store and is not directed at children under 13. We do not
knowingly collect any data from children under 13. If you believe a child
has used the app and provided data, please contact us and we will delete
the associated installation.

## Your rights

You may delete your installation at any time by deleting the app. This
removes your device identifier and locally stored conversations. To
request server-side deletion of any retained messages associated with your
device identifier, email the support address below with the identifier you
wish to delete; we will action the request within thirty days.

## Changes to this policy

If we materially change this policy, we will update the "Last updated"
date and, where possible, surface the change in the app on next launch.

## Contact

For privacy questions or deletion requests, write to:
**support@stoics.chat**
