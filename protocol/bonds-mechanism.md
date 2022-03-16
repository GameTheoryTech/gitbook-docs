# Bonds (HODL)

### What is HODL? What are bonds?

The bonds, named HODL, are unique tokens that can be utilized to help stabilize the GAME price around peg (1 DAI) by reducing the circulating supply of GAME if the TWAP (time-weighted average price) goes below peg.

### When can I buy HODL/bonds?

HODL can be purchased only during periods of supply contraction and when the TWAP of GAME is below 1.

At the beginning of every new epoch during contraction periods, GAME are issued in the amount of 3% of GAME's circulating supply, with a max debt amount of 35%. This means that if bonds reach 35% of the circulating supply of GAME, no more bonds will be issued.

{% hint style="info" %}
Note that during a zen epoch (when an epoch ends with a TWAP between 1.0 - 1.01), **no HODL will be issued, even though the Theoretics does not print.**
{% endhint %}

{% hint style="danger" %}
GAME TWAP (time-weighted average price) is based on the GAME TWAP from the previous epoch as it ends. In other words, the GAME TWAP is real-time but the HODL TWAP is not.
{% endhint %}

### Where can I buy HODL/bonds?

You can buy HODL if any are available through [the bonds page](https://gametheory.tech/bonds). Anyone can buy as many HODL as they want as long as they have enough GAME to pay for them and there is enough HODL supply to do so.

There is a limit of available HODL per epoch during contraction periods (3% of GAME's current circulating supply), and are sold first-come-first-serve.

### Why should I buy HODL/bonds?

The first and most important reason to buy HODL is that they help to maintain the peg, but they are not the only measure in place to keep the protocol on track.

HODL don't have an expiration date, so you can view them as an investment in the long-term health of the protocol to be redeemed for a premium at a later date.

#### Incentives for holding HODL

The idea is to reward HODL buyers for helping the protocol, while also protecting the protocol from being manipulated by big players.

So after you buy HODL using GAME, you have two possible ways to get your GAME back:

1. Sell back your HODL for GAME **while the peg is between 1 - 1.1** with no redemption bonus. This is in place to prevent an instant dump as soon as peg is recovered.
2. Sell back your HODL for GAME **while the peg is above 1.1** with a bonus redemption rate.

The longer you hold, the more both the protocol and you benefit from HODL.

{% hint style="success" %}
Example:

1. When GAME = 0.8, burn 1 GAME to get 1 HODL (HODL price = 0.8)
2. When GAME = 1.15, redeem 1 HODL to get 1.105 GAME (HODL price = 1.27)
{% endhint %}

So, which one is better?

If I buy GAME at 0.8, and hold it until 1.15 and then sell, I'm getting +$0.35 per GAME.

But, if I buy GAME at 0.8, burn it for HODL, and redeem it at 1.15, I'm getting 1.105 GAME \* 1.15 (GAME current price) = 1,271 (+$0.47) per GAME redeemed.

But, what if getting back to peg is taking too long?

We will adjust our use cases to have different behaviors on contraction and expansion periods to benefit HODL holders when needed.  These include staking mechanisms, promotions, and more!

### What is the formula to calculate the redemption bonus for HODL?

To encourage the redemption of HODL for GAME when GAME's TWAP > 1.1 and in order to incentivize users to redeem bonds at a higher price, HODL redemption is designed to be more profitable with a higher GAME TWAP value. The HODL to GAME ratio is 1:R, where R can be calculated using the formula as shown below:

$$
R=1+[(GAMEtwapprice)-1)*coeff)]
$$

$$
coeff = 0.7
$$

### When can I swap HODL for a premium?

You can only redeem HODL for a premium when the previous epoch's TWAP is greater than 1.1.