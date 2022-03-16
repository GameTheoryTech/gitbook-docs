---
description: >-
  A mechanism for initial sustainability and early rewards, derived from DeFi
  Kingdoms.
---

# Locking and Fees

To balance the high emissions rates in earlier weeks and to provide price stability, our tokenomics includes a locking model for rewards. A portion of the tokens distributed as rewards is unlocked. Once claimed, these unlocked reward tokens transfer directly into the player's wallet and are immediately usable. However, a portion of the rewards are also locked. These rewards are allocated to the player's wallet, but cannot be accessed or used in any way until they become unlocked.

### Bonuses (THEORY Rewards)

| Week  | Bonus Multiplier |
| ----- | ---------------- |
| 1     | 256              |
| 2     | 128              |
| 3     | 96               |
| 4     | 64               |
| 5     | 56               |
| 6     | 48               |
| 7     | 40               |
| 8     | 32               |
| 9     | 28               |
| 10    | 24               |
| 11    | 20               |
| 12    | 16               |
| 13    | 15               |
| 14    | 14               |
| 15    | 13               |
| 16    | 12               |
| 17    | 11               |
| 18    | 10               |
| 19    | 9                |
| 20-35 | 8                |
| 36+   | 4                |

### Locks (THEORY Rewards)

| Week  | Lock Percentage |
| ----- | --------------- |
| 1     | 95%             |
| 2     | 93%             |
| 3     | 91%             |
| 4     | 89%             |
| 5     | 87%             |
| 6     | 85%             |
| 7     | 83%             |
| 8     | 81%             |
| 9     | 79%             |
| 10    | 77%             |
| 11    | 75%             |
| 12    | 73%             |
| 13    | 71%             |
| 14    | 69%             |
| 15    | 67%             |
| 16    | 65%             |
| 17    | 63%             |
| 18    | 61%             |
| 19    | 59%             |
| 20-35 | 57% to 27%      |
| 36+   | 25% to 0%       |

### Locks (GAME Rewards)

Linearly changes based on how close to peg GAME is. At 1.01 or lower, it is 95%. At 4.0 or higher, it is 0%.

### Deposit and Withdraw Fees (THEORY and GAME)

**There are no deposit fees for staking your tokens, except the 1% deposit fee for genesis pools.** To protect against flash loans and pump and dumps, we do implement withdrawal fees for withdrawing staked tokens (not during genesis). Each withdrawal resets the fee timer. The withdrawal fees are listed below:

* **0.01%** fee if a user withdraws after **4 weeks.**
* **0.25%** fee if a user withdraws after **2 weeks but before 4 weeks.**
* **0.5%** fee if a user withdraws after **5 days but before 2 weeks.**
* **1%** fee if a user withdraws under **5 days.**
* **2%** fee if a user withdraws under **3 days.**&#x20;
* **4%** fee if a user withdraws under **24 hours.**&#x20;
* **8%** fee if a user withdraws under **1 hour.**
* **25%** slashing fee if a user withdraws **during the same block.**
