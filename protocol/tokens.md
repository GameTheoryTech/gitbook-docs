# Tokens

### GAME - Game Token

Contract: [0xe5c495DEE0A78a12e44d946b7E9931d46B35dF62](https://ftmscan.com/token/0xe5c495DEE0A78a12e44d946b7E9931d46B35dF62)

**GAME** is designed to be used as a medium of exchange inside and outside of the protocol and its products. The built-in stability mechanism in the protocol aims to maintain the peg to 1 **DAI** token in the long run.

### **How the Algorithmic Peg works?**

**When GAME is below peg**

When the GAME time-weighted average price is below the price of DAI (peg), token holders can purchase **HODL** and **GAME** will be **burned** to reduce the circulating supply when users redeem DAI tokens with a 1:1 ratio.

**When GAME is above peg**

When **GAME** price is above peg, the token supply will have to expand to push it back down to Peg and the contract will allow the redemption of the **HODL**.

When the price of GAME continues trading above peg after bond redemption, the contract mints an appropriate amount of new GAME and this will be **distributed** to the **THEORY** stakers.

There is an additional locking mechanism in place. For more information on that, visit the [Locking](locking-and-fees.md) page.

{% hint style="warning" %}
Note that GAME **actively pegs via an algorithm**, but that **does not mean** it will be valued at 1 DAI at all times as **it is not collateralized**. **GAME is not to be confused for a crypto or fiat-backed stablecoin.**
{% endhint %}

### THEORY - Share Token

Contract: [0xDbF138c66cbacd169017d8bEcFBBEeD84f6e6315](https://ftmscan.com/token/0xDbF138c66cbacd169017d8bEcFBBEeD84f6e6315)

The Theory Token (THEORY) is one of the ways to measure the value of the Game Theory and shareholder trust in its ability to consistently maintain GAME close to peg and/or deliver. During epoch expansions the protocol mints GAME and distributes it proportionally to all THEORY holders who have staked their tokens in the [**Theoretics**](theoretics.md). The starting price of THEORY is approximately 71.54 DAI. There is an additional locking mechanism in place. For more information on that, visit the [Locking](locking-and-fees.md) page.

All the following values are truncated for simplicity. THEORY has a **maximum total supply of 363,433** tokens distributed as follows:

1. _Treasury/Community Allocation: 28,555_ THEORY vested linearly 12 months. Unlike many tomb forks, this allocation is minted upfront and distributed slowly.
2. _Team/Dev Allocation: 25,959_ THEORY vested linearly over 12 months. Unlike many tomb forks, this allocation is minted upfront and distributed slowly.
3. _Rewards: 308,918_ THEORY are allocated for incentivizing liquidity providers in two farming pools for 12 months
4. Initial mint: 1 THEORY minted upon contract creation for the initial pool

{% hint style="success" %}
The team/dev will use the treasury funds in any way that they feel is best for the long-term success of the protocol.
{% endhint %}

### [HODL - Bond Token](bonds-mechanism.md)

Contract: [0x02e808efd8a8cb8af0719c5270c64ab462535db7](https://ftmscan.com/token/0x02e808efd8a8cb8af0719c5270c64ab462535db7)

The main purpose of HODL is to help incentivize fluctuations in the supply during epoch contraction periods. When the last TWAP (time-weighted average price) of GAME falls below 1 DAI, HODL tokens are issued and can be bought with GAME at the current price. These bonds will be incentivized in various ways, such as staking and special offers. Exchanging GAME for HODL burns GAME tokens, taking them out of circulation (deflation) and helps to get the price back up to peg. These HODL tokens can be redeemed for GAME when the price is above peg in the future, plus a premium based on how high above peg we currently are. This conversely creates inflation and subsequent sell pressure for GAME when it is above peg, helping to push it back toward 1 DAI.

{% hint style="info" %}
Unlike early algorithmic protocols, HODL does not have an expiration date.
{% endhint %}

All HODL holders will be able to redeem their HODL for GAME tokens as long as the treasury has a positive GAME balance, which typically happens when the protocol is in epoch expansion periods.
