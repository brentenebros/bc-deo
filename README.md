# bc-deo
A Decentralized Exponential Organization (DEO) featuring a bonding curve for membership access, finance and reserve pool, membership proposal submitting and voting.

# Intent
Create a Decentralized Exponential Organization (DEO) with the goal of coordinating members around hardware projects that can have significant positive impact.

# Primary Functionality
- Prospective members can submit a membership deposit (e.g. ETH) to a bonding curve which creates a new DEO token (e.g. RLP)
- The bonding curve splits the membership deposit into a 'funding pool' and a 'reserve pool'
- The DEO token allows holders to submit and vote on proposals
- The number of DEO tokens held proportional to the number of DEO tokens in existence determines the weight of a members vote
- If a proposal is approved, the 'funding pool' disperses tokens (e.g. ETH) to the project to fulfill its objectives as described in the proposal
- A member can leave the DEO at any time by sending their DEO token(s) to the bonding curve which will return tokens from the 'reserve pool' to the exiting member
- The number of tokens sent from the 'reserve pool' back to the exiting member is proportional to the number of DEO tokens sent and the number of DEO tokens in existence 
- There is an exit tax on leaving members that goes directly into the 'funding pool'

![Primary Functionality Diagram](/images/pfd_01.png)

# Supplementary Features
- DEO Initialization Phase: A number of DEO tokens can be issued at a set price, regardless of number of DEO tokens in existence, in order to bootstrap community. These membership deposits are split into the same 'funding pool' and 'reserve pool'. Once a threshold of DEO tokens have been issued, the bonding curve becomes active for future prospective members. It is not possible to sell DEO tokens back to the bonding curve during the initialization phase.

# Objectives
- Create a circular economy that allows communities to form around shared interests and common goals.
- Keep it simple. Less code = winning
- Make it accessible. As simple and intuitive to get involved as possible. Emphasis on simplicity over style. UI/UX will be of utmost importance.
