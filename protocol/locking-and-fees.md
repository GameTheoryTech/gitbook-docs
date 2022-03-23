---
description: >-
  One of our core innovations is our locking/fees mechanism that rewards early
  investors and encourages long term holders
---

# Bonuses, Vesting Schedule and Fees

Game Theory is tailored towards long term holders who want to be share-holders in our ecosystem and our RPG game. To incentivize that we have a bonus feature for early investors that vests over time. The amount of $THEORY tokens distributed is front loaded so that in the initial weeks of launch a much larger amount of tokens are emitted than in the last weeks. A large amount of these extra tokens are locked and vest over time, encouraging users to stay a part of the protocol long term.

Each staker in the Farm will get their $THEORY rewards. They will get two types of $THEORY tokens when they claim; unlocked and locked tokens. Both will be present in their wallet. The unlocked tokens are theirs to follow whichever strategy makes the most sense for them. The locked tokens will follow a vesting schedule where every week an additional 2% of the tokens unlock. The schedule will go as follows:

### Bonuses ($THEORY Rewards)

| Week  | Daily Token Emissions | Lock %/Fully Vested | Unlocked Daily Tokens |
| ----- | --------------------- | ------------------- | --------------------- |
| 1     | 10378                 | 95%/5%              | 518                   |
| 2     | 5189                  | 93%/7%              | 363                   |
| 3     | 3891                  | 91%/9%              | 350                   |
| 4     | 2594                  | 89%/11%             | 285                   |
| 5     | 2270                  | 87%/13%             | 295                   |
| 6     | 1945                  | 85%/15%             | 291                   |
| 7     | 1621                  | 83%/17%             | 275                   |
| 8     | 1297                  | 81%/19%             | 246                   |
| 9     | 1135                  | 79%/21%             | 238                   |
| 10    | 972                   | 77%/23%             | 223                   |
| 11    | 810                   | 75%/25%             | 202                   |
| 12    | 648                   | 73%/27%             | 174                   |
| 13    | 608                   | 71%/69%             | 176                   |
| 14    | 567                   | 69%/31%             | 175                   |
| 15    | 527                   | 67%/33%             | 173                   |
| 16    | 486                   | 65%/35%             | 170                   |
| 17    | 445                   | 63%/37%             | 164                   |
| 18    | 405                   | 61%/39%             | 157                   |
| 19    | 364                   | 59%/41%             | 149                   |
| 20-35 | 324                   | 57%/43%-27%/73%     | 139-236               |
| 36+   | 162                   | 25%/75%-0%/100%     | 121-162               |

### Locks ($GAME Rewards)

$GAMEs emissions in Theoretics have a locking mechanism based on the time weighted price average (TWAP). The locking schedule is linear between the TWAP of 1.01-4.0, meaning the higher the TWAP the higher percentage of each epoch that is unlocked. The same as with $THEORY every week an additional 2% of locked tokens become unlocked.

| TWAP  | Unlocked Tokens | Locked Tokens |
| ----- | --------------- | ------------- |
| 4.0+  | 100%            | 0%            |
| 1.01- | 5%              | 95%           |
|       |                 |               |



### Deposit and Withdraw Fees ($THEORY and $GAME)

**There are no deposit fees for staking your tokens, except the 1% deposit fee for genesis pools.** To protect against flash loans and pump and dumps, and to encourage long term holding there are withdrawal fees for withdrawing staked tokens (not during genesis). Each withdrawal resets the fee timer. The withdrawal fees are listed below:

* **0.01%** fee if a user withdraws after **4 weeks.**
* **0.25%** fee if a user withdraws after **2 weeks but before 4 weeks.**
* **0.5%** fee if a user withdraws after **5 days but before 2 weeks.**
* **1%** fee if a user withdraws under **5 days.**
* **2%** fee if a user withdraws under **3 days.**&#x20;
* **4%** fee if a user withdraws under **24 hours.**&#x20;
* **8%** fee if a user withdraws under **1 hour.**
* **25%** slashing fee if a user withdraws **during the same block.**
