---
description: "Build with kyaa: the fan participation layer that turns verified activity into Passport, Stamp, and benefit records on GIWA."
cover: .gitbook/assets/byus-docs-cover.png
coverY: 0
layout:
  width: wide
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# kyaa Developer Documentation

Kyaa. Every Fan Moment Counts.

Product captures and transaction examples from the earlier ByUs release are retained as historical evidence. Existing NFT names, addresses, and metadata remain unchanged.

kyaa turns fan participation into a persistent, verifiable record. Fans discover a favorite, verify their fandom, receive a creator-specific Fan Passport, collect Stamps through LIVE activities, and unlock benefits based on what they actually did.

<img src=".gitbook/assets/kyaa-wordmark.svg" alt="kyaa" width="180">

{% hint style="success" %}
A working kyaa MVP is live at [kyaa.io](https://kyaa.io/?locale=en). Fan Passport and Stamp mint transactions are verifiable on GIWA Sepolia.
{% endhint %}

<!-- Text-only navigation cards: pitch-deck thumbnails are intentionally omitted. -->

<table data-view="cards">
  <thead>
    <tr>
      <th></th>
      <th></th>
      <th data-hidden data-card-target data-type="content-ref"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Experience the product</strong></td>
      <td>Follow the fan journey from discovery and verification to LIVE participation and benefits.</td>
      <td><a href="getting-started/product-journey.md">getting-started/product-journey.md</a></td>
    </tr>
    <tr>
      <td><strong>Understand the architecture</strong></td>
      <td>See how Privy, the kyaa BFF, Supabase, the mint worker, IPFS, and GIWA work together.</td>
      <td><a href="architecture/overview.md">architecture/overview.md</a></td>
    </tr>
    <tr>
      <td><strong>Verify the GIWA proof</strong></td>
      <td>Inspect the deployed contracts and successful Passport and Stamp transactions.</td>
      <td><a href="giwa/network-and-contracts.md">giwa/network-and-contracts.md</a></td>
    </tr>
  </tbody>
</table>

## What kyaa provides

| Layer | What it does |
| --- | --- |
| Fan experience | Discovery, Google sign-in, fan verification, LIVE reservation, attendance, surveys, Passport, Stamps, and benefits |
| Identity | A Privy embedded EVM wallet linked to the canonical kyaa fan account |
| Operational data | Owner-scoped activity, score, level, eligibility, claims, and mint state in Supabase |
| Verifiable credentials | Soulbound Fan Passport and Live Stamp credentials issued on GIWA Sepolia |
| Operations | Server-side BFF, idempotent minting, notifications, and an internal operations console |

## Current network

| Property | Value |
| --- | --- |
| Network | GIWA Sepolia |
| Chain ID | `91342` |
| Passport standard | Soulbound ERC-721 |
| Stamp standard | Soulbound ERC-1155 |
| Product | [kyaa.io](https://kyaa.io/?locale=en) |
| Application source | [kyaa-io/kyaa](https://github.com/kyaa-io/kyaa) |
| Contract source | [kyaa-io/kyaa-contracts](https://github.com/kyaa-io/kyaa-contracts) |

## Start here

1. Run the application with the [Quickstart](getting-started/quickstart.md).
2. Learn the complete [Product journey](getting-started/product-journey.md).
3. Read the [System overview](architecture/overview.md) before changing identity, activity, or minting behavior.
4. Use [MVP and on-chain proof](getting-started/mvp-evidence.md) to verify the current implementation.

---

<img src=".gitbook/assets/sallylab-logo.svg" alt="SallyLab" width="150">

kyaa is built by SallyLab.
