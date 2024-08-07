---
title: lightning-browser-extension
categories: ['typescript', 'bitcoin', 'lightning']
---
## [lightning-browser-extension](https://github.com/getAlby/lightning-browser-extension)

### The Bitcoin Lightning Browser extension that connects to different wallet interfaces and brings deep lightning integration to the web


The extension provides deep Lightning Network integration for websites (for payments and authentication flows).

The goal is to write a minimal web extension to allow browsers to interact with the Lightning Network programmatically. It focuses on the web-payments process and does not try to be a full node UI with advanced channel-management or similar features.

The extension implements the WebLN standard as the interface that allows websites to connect to Lightning Network nodes (to request payments, invoices, signatures, login, etc.) and enable seamless UX of web payments and authentications.

The extension can connect to different node implementations and supports custodial and non-custodial setups.
