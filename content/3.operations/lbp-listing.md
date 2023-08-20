---
description: >-
  A summary of the features and advantages of Liquidity Bootstrapping Pool
  services available in the Polkadot ecosystem.
---

# LBP Listing

_<mark style="background-color:red;">Disclaimer: This article is written by</mark> <mark style="background-color:red;"></mark><mark style="background-color:red;">**Dot.alert()**</mark> <mark style="background-color:red;"></mark><mark style="background-color:red;">contributors for educational purposes only. This article should not be used as a substitute for competent legal or financial advice from a licensed professional in your country.</mark>_



## What is LBP Listing?

Liquidity Bootstrapping Pools (LBPs) are mechanisms or programmatic strategies put in place to provide liquidity for newly launched tokens or assets and facilitate price discovery. They dynamically adjust the valuation of a token or an asset based on the demand from purchasers and the participation rate of buyers over a predefined period of time. This in turn helps maintain a balance between the price of the token and the available liquidity.



### How-to: Pricing Tokens Through Community Participation&#x20;

Raising liquidity through LBPs is both a decentralised and permissionless process that ultimately aims to improve capital efficiency for new projects. In the Polkadot ecosystem, _Snek LBP_ which is deployed on the Basilisk parachain is the main platform for conducting LBP listings. The underlying mechanism is designed to put downward pressure on token prices to ensure fair distribution among interested stakeholders.

The first step in the listing process is to introduce the project and its tokenomics to the Basilisk community as a discussion thread on the governance forum. After which, project teams need to create an asset registry information for the token, including its name, symbol, decimals, and [existential deposit](../1.acquisition/existential-deposits.md). Following successful testing of all cross-chain activities, the LBP listing proposal is then presented to the Basilisk Council for voting on its approval or rejection.

LBP listing doesn't require whitelists, hard cap targets, minimum or maximum token allocations as is the case on Centralised exchanges. Instead, a starting price is set at the beginning of the LBP event and programmed to decline throughout, until buying activity occurs to set a market value for the token. Another advantage of LBP listing is that the platform supports cross-chain tokens for listing and allows teams to repurpose LBP fees for [Liquidity Provision](lending/liquidity-provision.md); features that are designed to reduce the barrier to participation for Community, DAO-based, or individual projects.

<figure><img src="../../.gitbook/assets/O_LBPCurve.jpg" alt="A sample chart with a price trajectory curve during an LBP listing."><figcaption><p>An example of the effects of a late large buy order on the overall price trajectory curve during an <a href="https://docs.bsx.fi/product_snek_lbp">LBP listing</a>.</p></figcaption></figure>



### Risks: Mitigating Assets Losses and Projects Devaluations

LBP listing relies on complex programming and evolving business logic that tap into emerging technologies such as XCMP for Asset registries and cross-chain transfers between parachains. As such, there is always the risk that transactions fail to execute, resulting in lost purchasing opportunities for LBP participants. For this reason, the LBP listing process comes with mandatory testnet trials of critical operations such as depositing, withdrawing, and buying assets.&#x20;

LBP listing operates from a variety of both technical and social parameters such as the pre-programmed price curve, the duration of the LBP event, the number of participants, the size of the purchase order, and the timing of the buying activities. This means that the price discovery schedule for a token cannot be determined in advance and that the final market value can significantly deviate from community expectations.&#x20;

Insufficient demand or limited interest in a token throughout the LBP listing could lead to an uneven pattern of token distribution at the conclusion of the event, with a potential concentration of tokens in the hands of a few holders. While this might not be a problem at an early stage of development when there are few users, the presence of long-standing whales and dolphins may become cause for concern once a project gains in popularity. This is because, in the context of on-chain governance, most of the [decision-making](voting/) can easily be captured by those who have more tokens.

