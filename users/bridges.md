# Bridges

## What are bridges?

Bridges are smart contracts that IndexPool uses to interact with other DeFi protocols.

For example, a bridge can execute swaps on Uniswap, perform deposits on Aave, or interact with any other DeFi protocol. Bridges extend functionality into the IndexPool protocol and emit events that are used to display transactions in the IndexPool app.

## How do bridges interact with the Portfolio NFT?

![Wallets link with bridges to enable integrations with DeFi protocols](../.gitbook/assets/image%20%286%29.png)

Bridges are always called directly from the Wallet linked to the Portfolio NFT. Bridges have the power to use all the available funds in that particular Portfolio NFT. So, it is extremely important only to interact with trusted bridges \(see below\).

_See_ [_IndexPool architecture_](https://docs.indexpool.org/developer/architecture) _for a technical reference on how bridges interact with IndexPool._

## What is a trusted bridge?

A trusted bridge is a bridge that was reviewed by the IndexPool team. Once the IndexPool protocol goes through an audit, trusted bridges will also be audited.

{% hint style="info" %}
Trusted bridges are the only available bridges by default in the IndexPool app, which means that as long you as you don't add any custom bridges to your [indexpool.org](http://indexpool.org/) app you are safe from interacting with untrusted bridges.
{% endhint %}



