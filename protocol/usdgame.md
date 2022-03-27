# $GAME

Contract: [0x56EbFC2F3873853d799C155AF9bE9Cb8506b7817](https://ftmscan.com/token/0x56EbFC2F3873853d799C155AF9bE9Cb8506b7817)

**$GAME** is designed to be used as a medium of exchange inside and outside of the protocol and its products. The built-in stability mechanism in the protocol aims to maintain the peg to 1 $DAI token in the long run. By pegging to a stablecoin $GAME will be able to maintain a stable price over the long term which makes $GAME perfect to be used for an in-game currency for Brutal Network and in the wider ecosystem. During epoch expansions the protocol mints $GAME and distributes it proportionally to all $THEORY holders who have staked their tokens in the [**Theoretics**](theoretics.md). $GAME is designed to be used as currency, with $THEORY representing equity in the protocol.

### **How the Algorithmic Peg works?**

**When $GAME is above peg**

When $GAME price is above peg, the token supply will have to expand to push it back down to Peg and the contract will allow the redemption of the **HODL**.

When the price of $GAME continues trading above peg after bond redemption, the contract mints an appropriate amount of new GAME and this will be **distributed** to the $THEORY stakers.

There is an additional locking mechanism in place. For more information on that, visit the [Locking](locking-and-fees.md) page.

**When $GAME is below peg**

When the $GAME time-weighted average price is below the price of $DAI (peg), token holders can purchase **HODL** and $GAME will be **burned** to reduce the circulating supply when users redeem $DAI tokens with a 1:1 ratio.

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
Note that $GAME **actively pegs via an algorithm**, but that **does not mean** it will be valued at 1 $DAI at all times as **it is not collateralized**. $GAME is not to be confused for a crypto or fiat-backed stablecoin.
{% endhint %}
