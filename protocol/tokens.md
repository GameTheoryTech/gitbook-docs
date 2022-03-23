# Tokens

### $GAME - Platform Token

Contract: [0x56EbFC2F3873853d799C155AF9bE9Cb8506b7817](https://ftmscan.com/token/0x56EbFC2F3873853d799C155AF9bE9Cb8506b7817)

**$GAME** is designed to be used as a medium of exchange inside and outside of the protocol and its products. The built-in stability mechanism in the protocol aims to maintain the peg to 1 $DAI token in the long run. By pegging to a stablecoin $GAME will be able to maintain a stable price over the long term which makes $GAME perfect to be used for an in-game currency and in the wider GT ecosystem.&#x20;

### **How the Algorithmic Peg works?**

**When $GAME is below peg**

When the $GAME time-weighted average price is below the price of $DAI (peg), token holders can purchase **HODL** and $GAME will be **burned** to reduce the circulating supply when users redeem $DAI tokens with a 1:1 ratio.

**When $GAME is above peg**

When $GAME price is above peg, the token supply will have to expand to push it back down to Peg and the contract will allow the redemption of the **HODL**.

When the price of $GAME continues trading above peg after bond redemption, the contract mints an appropriate amount of new GAME and this will be **distributed** to the $THEORY stakers.

There is an additional locking mechanism in place. For more information on that, visit the [Locking](locking-and-fees.md) page.

**$GAME Distribution:**

Every epoch $GAME expansion is distributed as follows:

85% of Epoch expansion goes to $THEORY stakers in theoretics.

15% of Epoch expansion goes to treasury for supporting the protocol

| Circulating Supply | Max $GAME Minted |
| ------------------ | ---------------- |
| Bootstrap          | 5% expansion     |
| Up to 500k         | 4.5% expansion   |
| Up to 1M           | 4% expansion     |
| Up to 1.5M         | 3.5% expansion   |
| Up to 2M           | 3% expansion     |
| Up to 5M           | 2.5% expansion   |
| Up to 10M          | 2% expansion     |
| Up to 20M          | 1.5% expansion   |
| Up to 50M          | 1.25% expansion  |
| 50M+               | 1% expansion     |

{% hint style="warning" %}
Note that $GAME **actively pegs via an algorithm**, but that **does not mean** it will be valued at 1 $DAI at all times as **it is not collateralized**. $**GAME is not to be confused for a crypto or fiat-backed stablecoin.**
{% endhint %}

### $THEORY - Share Token

Contract: [0x60787C689ddc6edfc84FCC9E7d6BD21990793f06](https://ftmscan.com/token/0x60787C689ddc6edfc84FCC9E7d6BD21990793f06)

The share token ($THEORY) is one of the ways to measure the value of the Game Theory and shareholder trust in its ability to consistently maintain $GAME close to peg and/or deliver. During epoch expansions the protocol mints $GAME and distributes it proportionally to all $THEORY holders who have staked their tokens in the [**Theoretics**](theoretics.md). The starting price of $THEORY is approximately 71.54 $DAI. There is an additional locking mechanism in place. For more information on that, visit the [Locking](locking-and-fees.md) page.

$THEORY has a **maximum total supply of 363,433** tokens distributed as follows:

1. Initial mint: 1 $THEORY minted upon contract creation for the initial pool
2. _Rewards: 308,918_ $THEORY are allocated for incentivizing liquidity providers in two farming pools for 12 months
3. _Treasury/Community Allocation: 28,555_ $THEORY vested linearly 12 months. Unlike many tomb forks, this allocation is minted upfront and distributed slowly.
4. _Team/Dev Allocation: 25,959_ $THEORY vested linearly over 12 months. Unlike many tomb forks, this allocation is minted upfront and distributed slowly.

{% hint style="success" %}
The team/dev will use the treasury funds in any way that they feel is best for the long-term success of the protocol.
{% endhint %}

### [HODL - Bond Token](bonds-mechanism.md)

Contract: [0xFfF54fcdFc0E4357be9577D8BC2B4579ce9D5C88](https://ftmscan.com/token/0xFfF54fcdFc0E4357be9577D8BC2B4579ce9D5C88)

The main purpose of HODL is to help incentivize fluctuations in the supply during epoch contraction periods. When the last TWAP (time-weighted average price) of $GAME falls below 1 $DAI, HODL tokens are issued and can be bought with $GAME at the current price. These bonds will be incentivized in various ways, such as staking and special offers. Exchanging $GAME for HODL burns $GAME tokens, taking them out of circulation (deflation) and helps to get the price back up to peg. These HODL tokens can be redeemed for $GAME when the price is above peg in the future, plus a premium based on how high above peg we currently are. This conversely creates inflation and subsequent sell pressure for $GAME when it is above peg, helping to push it back toward 1 $DAI.

{% hint style="info" %}
Unlike early algorithmic protocols, HODL does not have an expiration date.
{% endhint %}

All HODL holders will be able to redeem their HODL for GAME tokens as long as the treasury has a positive GAME balance, which typically happens when the protocol is in epoch expansion periods.
