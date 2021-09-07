# Bridges

## What are bridges?

Bridges are smart contracts that IndexPool uses to interact with other DeFi protocols.

For example we have a bridge to do swaps on Uniswap, a bridge to do deposits on Aave... They help us to extend functionality into the IndexPool protocol and to process transactions to make them visible in the IndexPool app.

## How bridges interact with the Portfolio NFT?

Once a bridge is called it can use the available funds in the NFT. It is extremely important only to interact with trusted bridges, which are the only available bridges by default in the IndexPool plataform, which means that as long you as you don't any any custom bridges to your [indexpool.org](http://indexpool.org/) app you are safe from interacting with untrusted bridges.

## What is a trusted bridge?

A trusted bridge is a bridge that was written or reviewed by the IndexPool team. Once the IndexPool protocol goes through an audit, bridges will also be audited.

### 



