# Theoretics

## The Theoretics User Interface

1. **NEXT EPOCH**\
   The amount of time remaining until the next epoch.
2. **CURRENT EPOCH**\
   The number of the current epoch.
3. **$GAME PEG (TWAP)**\
   The TWAP (time-weighted average price) of the $GAME peg. The Theoretics only mints new $GAME as rewards for $THEORY stakers when this value **is above 1.01** **at the end of the current epoch**.
4. **APR**\
   The yield for $THEORY stakers in the Boardroom **if the Theoretics was printing every epoch**. This calculation is based on **the last recorded print in the Theoretics**.
5. **THEORYS STAKED**\
   \*\*\*\*The total amount of $THEORY currently staked in the Theoretics.
6. **$GAME Earned**\
   \*\*\*\*The amount of $GAME you've earned as rewards for staking $THEORY in the Theoretics.
7. **$THEORY Staked**\
   The amount of $THEORY you currently have staked in the Theoretics.

### Theoretics Specifications

* Epoch duration: 6 hours
* Any interaction with the Theoretics (staking/unstaking $THEORY or withdrawing $GAME rewards) will **lock your staked $THEORY for 6 epochs and $GAME rewards for 3 epochs at max.** The actual value is linear to the unlocked THEORY percentage in the farms.
* Epoch Expansion: The current expansion cap is based on the currently circulating $GAME supply (see [GAME Distribution](broken-reference) for details). If there are bonds to be redeemed, 65% of minted GAME goes to the treasury until its sufficiently stocked to satisfy future bond redemption.

{% hint style="info" %}
Note that the Theoretics **does not** print any rewards for $THEORY stakers when the Theoretics TWAP < 1.01, except during the bootstrap phase.
{% endhint %}

