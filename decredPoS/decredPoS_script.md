## Decred In Depth: On-chain Governance
### Voice Over Script

Without a form of on-chain governance, holders of pure proof-of-work currencies like Bitcoin have no formal say in decision-making, giving all the power to miners and developers. With no way to keep proof-of-work miners in check *or* agree on consensus rule changes, Bitcoin leaves itself open to 51% attacks and community splitting hard forks.

**Decred's** **Proof-of-Stake Voting** system, (which is part of its hybrid proof-of-work - proof-of-stake protocol), puts power in the hands of its stakeholders, not its miners. By participating in proof-of-stake voting, stakeholders can stop 51% attacks, prevent unwanted hard forks, and shape the future of the project.

Here's how it works:

Decred holders time-lock funds in exchange for tickets, which have several voting functions that power Decred's governance. The decred used to buy a ticket is locked until that ticket is called through a lottery system. Time-locking of funds ensures that ticket holders have skin in the game. The more tickets a user buys, the more votes they have.

The *price* of a ticket is automatically adjusted by an algorithm at the end of each **ticket window** or every 144 blocks; ( about 12 hours, given Decred's average **block time** of roughly 5 minutes.) This keeps the number of *live* tickets in the system close to the target 40,960 tickets.

A ticket's life *begins* when it is first mined into a block, and *ends* when it is drawn from the ticket pool.

Before it is added to the ticket pool, a ticket must go through the immature stage. During this stage, the stakeholder's funds used to purchase the ticket are locked, but the ticket is not yet eligible to be drawn.

After 256 blocks (or about 20 hours), immature tickets become live and are added to the ticket pool. How long each ticket has to wait in the  pool before being drawn is entirely up to chance. Due to the design of 
the voting system, the average time to vote is 28 days and the maximum waiting time is 142 days.

For each block, 5 tickets are randomly called from the ticket pool. Once a ticket is called, the holder's signed voting ballot must be broadcast to the network from either a self-hosted voting wallet or a designated voting service provider for inclusion in the next block. If the ballot is not broadcast quickly enough, it will miss its chance to vote. This happens rarely, as most solo voters and voting service providers maintain several wallets. Missed tickets can be revoked after 256 blocks but do not get a reward.

A ticketholder's ballot will contain one **block vote** and zero to many **consensus votes** to be recorded *on-chain*.

Block votes allow stakeholders to keep proof-of-work miners in check. The 5 block votes contained in each new block decide whether to accept or reject the previous one. If stakeholders decide to reject the block, its pending transactions are returned to the mempool and the miner is stripped of their block reward.

Consensus votes allow stakeholders to change Decred's consensus rules through a two stage process where stakeholders vote for or against the proposed change.

Before the consensus voting process can begin, nodes must update to new software that has a latent copy of the proposed new rules. If the proposed rule change is approved, these will be automatically activated. The update threshold is met when 95% of the 1000 most recent blocks were mined by updated nodes and 75% of the proof of stake votes within *one* **stake version interval**, 2016 blocks (or about 1 week), have the latest version. 

After the update threshold is met voting will begin on the *first block* of the next **rule change interval**. 

Each rule change interval spans 8,064 blocks (or about 4 weeks) during which consensus votes for any active rule change proposals are collected.  For the outcome of the vote to be valid, at least 10% of the tickets must vote yes or no, as opposed to abstaining. If 75% of non-abstaining votes signal yes, then the proposed rule changes are approved and will be activated at the end of the *next* rule change interval. 

If more than 90% of tickets abstain, or the 75% Yes or No majority is not achieved, the proposal will be voted on again in the next rule change interval. 

After a stakeholder's ticket is drawn and a 256 block waiting period has passed, the funds used to purchase the ticket are unlocked along with a portion of the block reward as compensation for their active participation.

While their live tickets are waiting in the ticket pool, stakeholders also have access to proposal voting through Politeia, Decred's chain-anchored proposal system. Through Politeia anyone can shape the future of Decred by proposing new ideas for stakeholder consideration in an off-chain yet cryptographically verifiable manner.

To begin participating in the governance of Decred, download Decrediton at Decred.org and up your stake at any one of the many supporting exchanges.

Decred; Decentralized credits.



