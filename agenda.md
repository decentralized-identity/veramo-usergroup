# DIF Veramo User Group – Rolling Agenda & Minutes

[![hackmd-github-sync-badge](https://hackmd.io/XKdZ7iShTCCyMFX4I9RgOg/badge)](https://hackmd.io/XKdZ7iShTCCyMFX4I9RgOg)

## Meeting Template
- Agenda reminder
- Overview of charter
  - Reminder that this is an open group (not IPR-protected)
- PR review
- Issue Review
- Additional Topics

## Meeting - Thursday 11 July 2024 - (18:00 CET)

### Chair

Nick Reynolds

### Notes

We covered several topics:
* [a PR](https://github.com/decentralized-identity/veramo/pull/1401) that removes the isomorphic-webcrypto dependency from our did-comm package
* referenced [an unrelated PR](https://github.com/MetaMask/core/pull/3645) that has a very well documented description of CJS/ESM/node/typescript compatibility issues; potentially useful to folks that are running into issues with bundlers
* a potential solution to an [issue that was reported in ethr-did-resolver](https://github.com/decentralized-identity/ethr-did-resolver/issues/186) by building it using [ts-bridge](https://ts-bridge.dev/) 
* an issue with TypeORM in code built for production environments
* a proposal to refactor the data-store APIs basing them on simple key-value stores
* a proposal to make the [@veramo/utils#computeEntryHash](https://github.com/decentralized-identity/veramo/blob/02f200855c61237e724222f3430d20d3e0a878c4/packages/utils/src/credential-utils.ts#L86) method optional, or replaceable, so that folks can avoid problematic dependencies that are needed since veramo 6.0 to compute the CID of credentials for the internal database.

---

no notes taken in between. See [recording list](https://docs.google.com/spreadsheets/d/1wgccmMvIImx30qVE9GhRKWWv3vmL2ZyUauuKx3IfRmA/edit#gid=32419210)

---

## Meeting - Thursday 29 February 2024 - (15:00 CET)

### Chair

Mircea Nistor

### Notes

* brief discussion about deploying a Veramo agent to Azure ([Azure deployment articles](https://medium.com/@rameez.saleem/deploying-veramo-on-azure-using-terraform-and-helm-part-1-a-step-by-step-guide-for-deploying-a-aaaa75d199b9))
* [request] we need a guide for signing credentials with non-custodial wallets
* discussed a proposal for more transparent composability of Veramo agents https://github.com/decentralized-identity/veramo/discussions/1354
* merged the [Awesome.md](https://github.com/decentralized-identity/veramo/blob/next/AWESOME.md) update that mentiones the Spherity ARIES RFC implementations.
* brief update about the work happening on the SD-JWT front. The different camps have merged! 🚀 👏

## Meeting - Thursday 22 February 2024 - (18:00 CET)

### Chair

Nick Reynolds

### Agenda

- Welcome and introductions
- PR review
- Issue Review
- Additional Topics

### Attendees

### Notes

* Discussed some of the open PRs
* Discussed ARIES RFC implementations

## Meeting - Thursday 15 February 2024 - (15:00 CET)

### Chair

Mircea Nistor

### Agenda

- Welcome and introductions
- History of Veramo
- Overview of charter
    - Reminder that this is an open group (not IPR-protected)
- PR review
- Issue Review
- Additional Topics

### Attendees

### Notes

* Let's build a registry for
    * plugins built by the community
    * projects built on top of Veramo
    * There is a proto-registry in [the Awesome list](https://github.com/decentralized-identity/veramo/blob/next/AWESOME.md), but it needs more structure and better maintenance.
* We need a public roadmap with
    * features or plugins proposed
    * things being worked on
* Still unanswered
    * How to work with Veramo in non-JS tech-stacks (when is the OpenAPI interface not enough?)
* How to get in touch?
    * VeramoLabs discord server: https://discord.gg/HEFfWxSfFv
    * DIF discord / veramo-user-group channel: https://discord.gg/U7SVjGqgZz

## Previous Meeting...
