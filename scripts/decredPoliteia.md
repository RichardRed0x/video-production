#Decred in Depth: Politeia

### Keywords
`proposal`, `Timestamped`, `versioned`, `self-governance`, `immutable`, `off-chain storage`, `git`, `chain-anchored`

Decred's governance has several components. 

Ticket-holders vote on-chain on block validity and whether changes to consensus rules should be accepted. There's a lot more to governance than this however, too much to handle on-chain without bloating it significantly.

Politeia is where the rest of it happens, off-chain but anchored to the Decred chain to make it censorship resistant and to ensure that votes can only be cast by those with skin in the game.

Politeia is a reddit-like web platform for handling the submission, discussion and tracking of Decred governance proposals, from the direction and policies of the project to what the treasury funds.

The foundation of the Politeia web platform is reddit, but several features have been added which adapt it to Decred's needs.

Politeia is censor-proof, users can prove when their proposals or comments have been censored by admins. Some degree of censorship is necessary to handle inappropriate (e.g. illegal) submissions. On Politeia, proposals are vetted by administrators to ensure that they meet certain criteria before being displayed publicly. The power to censor becomes much more problematic when it can be wielded secretly, with deniability. 

Politeia accounts come with cryptographic keys that are used to sign submissions. Politeia uses DCRtime to generate censorship tokens for each submission. The submitting user can use this censorship token, along with their public key, to demonstrate cryptographically that their submission existed in a particular form at a particular point in time. Unaccountable censorship has no place in Decred's governance.

To limit spam and sock-puppetry, a fee of 0.1 DCR is charged for creating a new account, and for each proposal submission. User actions on the proposals platform are also fully transparent, including up/down voting on comments.

Once proposals have been vetted they are open for discussion by the community. Proposers can edit their proposal in response to feedback before it gets locked down and goes for a vote. Comments for different versions of a proposal are indexed as such, making it possible to trace the evolution of a proposal in response to community discussion.

Voting to approve or reject proposals happens from within the wallets that hold stakeholders' tickets. When a proposal moves to a vote, every ticket live at that block will have an opportunity to vote yes/no.

The outcomes of these votes will determine Decred's course, and how the project's fund will be used to pursue its aims.

Decred, Decentralized Credits.


 	
