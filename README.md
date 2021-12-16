# UNISWAP GOVERNANCE ENHANCEMENT - PUT YOUR UNI WHERE YOUR MOUTH IS

![Futarchy enhancement](https://raw.githubusercontent.com/ivanmolto/uniswap-governance-enhancement/main/images/uni-proposal.png?token=ABYT4J53ZKHYQI3HI2XTNYTBXOHQW)

A submission for Governance Enhancements at GR12 Hackathon sponsored by Uniswap Grants.

## INTRO

The Uniswap Protocol is a public good owned and governed by UNI token holders.

## PROBLEM

UNI holders govern the protocol through an on-chain voting governance process.
Democratic voting is a good way to govern, BUT it is not perfect.

## SOLUTION

Token voting by the holders of UNI (current governance process) plus an extra phase based on the futarchy model.

Futarchy as a mode of governance tries to improve on normal voting.
The basic idea is that betting on accepted proposals on Uniswap Governance and resolving consequences of these proposals as prediction markets is a way more efficient that token voting alone (Game theory confirms it!).

By using prediction markets as an extra phase in UNI governance, the governance can combine its objective with community and public expertise and reward the participants for signaling if an accepted proposal will have the most (or expected) positive effect.

## CURRENT UNISWAP GOVERNANCE PROCESS

### Phase 1: Temperature Check - Discourse/Snapshot

The purpose is to determine if there is sufficient will to make changes to the status quo. Including forum post with a link to the associated Snapshot poll.
If the Temperature Check does suggest a change (at the end of the of 2 days will require a majority vote with a 25k UNI yes-vote threshold to win), proceed to Phase 2. 

### Phase 2: Consensus Check - Discourse/Snapshot

The purpose of the Consensus Check is to establish formal discussion around a potential proposal. A 50k UNI yes-vote quorum is required for the Consensus Check to pass.

### Phase 3: Governance Proposal - Governance Portal

The proposal should be based on the winning outcome from the Consensus Check and can consist of one or multiple actions, up to a maximum of 10 actions per proposal.
The voting period lasts 7 days and a majority vote with a 40m UNI yes-vote threshold wins.

## UNISWAP GOVERNANCE ENHANCEMENT

### Phase 4: Prediction Markets (enhancement proposed)

Once a proposal has passed the Phase 3, it represents real, executable code which will alter the functionality of Uniswap (Governance) or anything under its jurisdiction.

From now, we can identify a metric or metrics around a proposal that will reveal success or failure consequences of the proposal implementation.

Once we have identified the metric or metrics we should create a prediction market using UNI as a collateral using success and failure as outcome shares to trade (buying/selling). This will be a prediction market that rewards and empowers stakeholders to express confidence in outcomes of an accepted proposal.
In brief, to have a say in the market, you have to "put your UNI where your mouth is".

A time delay or maturity duration in weeks/months must be set up to close the market and redeem the position invested when available.

This is a great opportunity to engage not only the community but speculators to bet on the success or failure of the accepted proposals (just as a barometer). 
It is all about aligning public interest with economic value over time.

Some of the benefits are:
- Over time the UNI holders who are bad at predicting the outcome of proposals will lose UNIs, and so their influence will decrease (maybe linking to a reputational score), whereas the individuals who are good at predicting the outcome of proposals will see their UNI and influence increase.
- Gives us more accurate estimates of the success/failure of those proposals.
- Reducing irrational social influences to the governance process.
This phase is more focused on success/failure of proposals rather than personalities or crypto twitter pitching proposals.

As exposed, adding an extra phase of futarchy governance to the current process, we could formally defer to prediction markets on matters of fact, while retaining token voting on matters of value.

## IMPLEMENTATION

The prediction market can be built easily using the [Conditional Token Framework](https://docs.gnosis.io/conditionaltokens/) 

As a bonus a decentralized arbitration court such as [Kleros](https://kleros.io/) could be necessary to handle disputes that may arise in the resolution of the prediction markets.

## CREDITS

Credit to Robin Hanson for inventing [futarchy](http://mason.gmu.edu/~rhanson/futarchy.pdf) and to Vitalik Buterin for his inspiring [futarchy post](https://blog.ethereum.org/2014/08/21/introduction-futarchy/) in the Ethereum Foundation blog.