# FAQs

## Theoretics FAQ

### **1. Once HODL tokens are issued, does the** Theoretics **stop printing GAME until we are above peg again?**

Staking THEORY will only give you GAME rewards when the price of GAME is above the peg, but not when it is under the peg.

### **2. What happens if I interact with the** Theoretics **in any way? Are there any lockup periods?**

Yes, there are two lockup timers. One for GAME rewards and one for staked THEORY. **Any interaction with the Theoretics will reset both timers.** The lockup period for withdrawing GAME rewards is explained above.

### **3. Are the** Theoretics **rewards pro-rated by time? For example, if I stake three hours before the end of an epoch versus five hours before the end of an epoch, would I get different rewards?**

No, Theoretics rewards are determined by how much you have staked at the time of printing (i.e., at the end of one epoch and the start of the other). It doesn't matter if you stake three hours before or thirty seconds before the emissions occur.

### 4. If I remove my THEORY from the Theoretics without first collecting my GAME, will they be lost forever?

No, they will still be there to collect whenever you need.

### 5. The Theoretics APR dropped because we're in a "debt phase." What does that mean?

A debt phase takes place during expansion epochs that start after a contraction period where there are still HODL to be redeemed.

65% of expansion during a debt phase is allocated to the treasury fund to prepare for subsequent HODL redemption down the road. This amount is always reserved, regardless of whether HODL holders are redeeming bonds or not.

Once enough GAME is sufficiently stocked in the treasury to satisfy the redemption of all circulating HODL, expansion rates will resume to normal.

### 6. If we're in a debt phase, how long will it last until the Theoretics continues printing as normal?

The debt phase will last as long as is necessary to adequately pay back outstanding HODL debt. Please keep in mind that the DAO will also need to collect a little extra, as there needs to be a cushion to cover the bonus premiums when people redeem HODL over peg.\
\
There's no exact maester way of calculating how many epochs it will take, since the protocol doesn't know exactly when people will redeem their HODL. The debt phase cannot end until the treasury has enough GAME to cover the redemption of all outstanding HODL tokens plus a premium.

### 7. At the end of the epoch, the Theoretics did not print GAME, but then no HODL(s) were issued either. Why?

There is a balanced state "at peg" when GAME's TWAP is between 1.00 and 1.01, which results in no contraction or expansion of the circulating supply of GAME. This is referred to as a **zen epoch**.

### 8. If GAME continues to climb above the price of the peg, will that influence how long the debt phase lasts?

Depending on the price of GAME, the Boardroom print will have to adjust to provide a buffer for any unclaimed HODL. As the price of GAME climbs above the peg, more GAME needs to be distributed to the treasury to account for HODL redemption plus premiums.

### 9. How can I figure out what my future GAME rewards will be from the Theoretics?

Let's take a look at a simplified example for a _non-debt phase_: say you have 1 THEORY staked out of 10 total THEORYs staked in the Boardroom. In this case, you will receive 10% of the total GAME printed in the Boardroom.

For this example we are assuming that there is a total circulating supply of 10,000 GAME and the current expansion rate is at 4%, so a total of 400 GAME will be printed in the Boardroom. Under the protocol's current rules, 60% of those newly printed GAME will be distributed to THEORY stakers in the Boardroom. (See the [GAME Distribution](broken-reference) page for more details on how GAME is distributed within the protocol.)\
\
Therefore, you would get: ((0.04 _\*_ 10000) _\*_ 0.6) \* (1/10) = **24 GAME**.\
\
Thus, the formula to calculate your rewards is as follows:\
((_ExpansionRate_ \* _CirculatingGAMESupply)_ \* 0.6) \* (_YourTHEORYStake_ / _TotalTHEORYStaked_)

### 10. How long will it take for THEORY to pay itself off from GAME rewards based on current prices?

This will vary constantly as the APR in the Theoretics fluctuates, along with other variables such as the price of GAME.

For a quick estimation, however, you can do the following:

1. Take the total APR shown in the Boardroom and divide that by 365 to get the daily APR. (For this example we will say the daily APR is 5%.) 
2. Multiply that daily APR by the current market price of the total THEORY you have staked to see what your daily rewards are. (In this example, we have 5 THEORY, each worth $500, for a total amount staked of $2500. Your daily return in this case would be $2500 \* 0.05, which comes out to $125 per day.)
3. Take your initial buy-in price for THEORY and divide it by your daily rewards. If you bought these 5 THEORY at a higher price, say $700 for example, in the current market conditions you would recover your initial investment of $3500 in 3500/125 or 28 days.
