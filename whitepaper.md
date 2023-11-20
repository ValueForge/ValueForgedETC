# ValueForgedETC

*A decentralized autonomous algorithmic stablecoin platform for Ethereum Classic*

## Abstract

ValueForge, in its mission to bring value-adding products to Ethereum Classic, introduces a groundbreaking dual asset value-pegged stablecoin ecosystem built on the Ethereum Classic network. The ecosystem aims to provide sophisticated cryptocurrency investors, blockchain technology developers and everyday users of the ETC network and its dApps with a decentralized, transparent, and secure financial solution. This whitepaper presents the technical details of the ValueForgedETC ecosystem, which includes two value-pegged stablecoins, the ANVIL Tokenomics Balancer Model, and the governance and liquidity mechanisms underpinning the platform.

## Table of Contents

1. Introduction
2. Overview of the ValueForgedETC Ecosystem
3. Market Analysis
4. The ValueForgedETC Technology Stack
5. The Tokenomics of ValueForgedETC
   1. 5.1 Stablecoin: ForgedUSD (FUSD)
   2. 5.2 Stablecoin: ForgedBTC (FBTC)
   3. 5.3 Value flow control: ValueForgedAnvilSwitch (VFAS)
6. Smart Contracts of the ANVIL Tokenomics Balancer Model
   1. 6.1 Algorithmic Design Overview
   2. 6.2 Fixing and Maintaining the Value Pegs
   3. 6.3 The Arsenal of Volatility Mitigation
7. Governance: ValueForgedHammerControl (VFHC)
   1. 7.1 Token Distribution
   2. 7.2 Governance Mechanism
   3. 7.3 Voting and Decision Making
8. Liquidity Provision: ValueForgedBellowsShare (VFBS)
   1. 8.1 Incentivized Liquidity Pools
   2. 8.2 Reward Structure
9. Value Adjustment: ValueForgedAnvilSwitch (VFAS)
   1. 9.1Token Conversion
   2. 9.2 Integration with DeFi Platforms
10. Security and Audits
11. Roadmap and Future Development
12. Conclusion

## Introduction

Rapid growth of the cryptocurrency market and decentralized finance (DeFi) has highlighted the need for stable financial instruments that can mitigate the risks associated with market volatility. Stablecoins, which have their value pegged to stable assets like fiat currencies or commodities, have emerged as a solution to this challenge. They provide a stable entry point for users transitioning from traditional financial systems to the world of cryptocurrencies, acting as a bridge between these two realms and enabling seamless integration with various financial services.

ValueForge aims to build a dual asset value-pegged algorithmicly controlled stablecoin ecosystem on the Ethereum Classic network, providing stability and value for users seeking a reliable and secure financial solution within the DeFi space. By offering two value-pegged tokens, ForgedUSD (FUSD) and ForgedBTC (FBTC), ValueForgedETC caters to users who want to avoid exposure to cryptocurrency fluctuations, as well as those who wish to enjoy the benefits of holding and transacting with Bitcoin while minimizing the effects of short-term market volatility.

The ValueForgedETC ecosystem is designed to be decentralized, transparent, and secure, in line with the principles of the Ethereum Classic community. It will utilize a suite of autonomous smart contracts to maintain the pegs of FUSD and FBTC, as well as a decentralized governance system that allows the community to actively participate in making critical ecosystem decisions and guiding the project's future development. By integrating with DeFi platforms and services, ValueForgedETC unlocks a wide array of financial opportunities, including lending, borrowing, staking, and trading within a decentralized finance environment. This innovative design makes it an ideal platform for users seeking a reliable and secure financial solution on the Ethereum Classic network.

In summary, ValueForgedETC represents a significant step forward in stablecoin technology, combining the best features of decentralized finance with the stability and transparency that sophisticated cryptocurrency investors and blockchain users demand. By offering a native stablecoin solution for the Ethereum Classic network, ValueForgedETC enables a more accessible and efficient on-ramp for users transitioning from fiat currencies to cryptocurrencies and facilitates growth within the DeFi ecosystem.

## ValueForgedETC Overview

We envision ValueForgedETC as an algorithmicly-pegged stablecoin platform deployed on the Ethereum Classic network with no dependency on banks or off-chain collateralization, fully adherent to the principles of the ETC Foundation through exhibiting the following properties:

Decentralization: ValueForgedETC will operate natively on the Ethereum Classic decentralized platform ensuring that no single entity has control over the network. This will involve the deployment of a suite of smart contracts to govern and maintain the stablecoin ecosystem without any central authority or intermediary.

Algorithmic pegging mechanism: The ValueForgedETC stablecoin platform will rely on an innovative algorithmic approach, the ANVIL Tokenomics Balancer model, to maintain its value peg. The ANVIL,  which stands for Aggregation Normalized Value Incentivized Liquidity, analyzes shifts in the market valuations of its controlled assets and utilizes a combination of complex algorithms to modify the asset's parameters using adjustable transaction fees, seigniorage shares, and automated market makers to adjust the circulating supply, market availability and liquidity of its stablecoin tokens to maintain the peg to a specific off-chain asset's value target without requiring any collateral from banks.

Governance: A decentralized and autonomous governance system will be used to make decisions about updates or modifications to the ValueForgedETC stablecoin platform's protocol. Governance token holders will be able to propose changes and vote on them, ensuring that the community remains in control of its stablecoins' future.
Transparency: All transactions, smart contracts, token balances held, and governance decisions made within the ValueForgedETC ecosystem will be public and verifiable on the Ethereum Classic blockchain. This ensures trust and openness within the community.

Security: ValueForgedETC will inherit the security properties of the Ethereum Classic network, including its proof-of-work consensus mechanism. This will help protect the stablecoin from potential attacks and maintain its integrity. Additionally, ValueForgedETC will be designed as fully auditable and accountable.
Interoperability: ValueForgedETC is designed to interact with other decentralized applications (dApps) and tokens within the Ethereum Classic ecosystem. This will enable seamless integration with various financial services, such as lending, borrowing, and trading.

Scalability: To ensure that the ValueForgedETC platform remains efficient and cost-effective, it will be designed to implement solutions that address the scalability limitations of the Ethereum Classic network, such as layer-2 scaling solutions or sidechains,.

Self-sustainability: The ValueForgedETC stablecoin ecosystem will have built-in incentives intended to encourage participants to contribute to its stability and growth. This will include mechanisms such as transaction fees, seigniorage rewards, and other incentives for users who help maintain the stablecoins' peg.
Compliance with ETC principles: Above all, ValueForgedETC will respect the Ethereum Classic community's values, including immutability, decentralization, and permissionless innovation. This means avoiding any centralized control or reliance on traditional financial institutions while still offering viable stablecoin alternatives for the Ethereum Classic community.

Designed with these properties in mind, we are confident that the ValueForgedETC stablecoin platform will fill a much needed role currently absent from Ethereum Classic's DeFi ecosystem without compromising the principles of the ETC Foundation.

## Market Analysis

Currently, no stablecoin exists natively on the Ethereum Classic network. As such, the existing DeFi ecosystem, consisting of HebeSwap, ETCswap, Fusion DeFi, PancakeSwap and a few other projects, functions without the flexibility and ease-of-use that access to a native stablecoin provides by utilizing more difficult, potentially confusing, and less secure cross-chain bridging techniques to accomplish transacting with USD-pegged stablecoins on other networks. Stablecoins available include Tether (USDT), BinanceUSD (BUSD), USD Coin (USDC), and Dai stablecoin (DAI) through bridged transactions that make use of Ethereum (ETH), Binance (BNB), and other networks.

With the deployment of ValueForgedETC, the Ethereum Classic ecosystem will have its own USD-pegged stablecoin token with which transactions can be made simply and safely in a secure, decentralized manner.

## The ValueForgedETC Technology Stack

ValueForgedETC is a system intended to provide a solution to a complex technical issue that requires it to function across multiple interrelated yet separate networks. It must be zero-downtime accessible 24 hours a day, every day from anywhere on Earth. Additionally, it must function the same for all users no matter what physical device is used to access its User Interface or in what language that interaction is conducted. A complex problem can mean that complex technology is needed. We have attempted to reduce the complexity of our solution wherever possible with a goal of creating an efficient, secure, cost-effective, streamlined and easily maintained technology stack comprised of well known and widely used components.

The technology stack ValueForgedETC uses to implement its stablecoin platform begins with the Ethereum Virtual Machine (EVM) and the Ethereum Classic blockchain network itself whereon a suite of open-source smart contracts written in Solidity and utilizing the OpenZeppelin library of standard upgradeable contracts will be deployed. All tokens created by and used within the platform are fully compliant with the ERC-20 token standard. An open-source website-based User Interface front-end, written in HTML and CSS, will be initially hosted on INSERT BWCD HOST until the governance mechanism is in place and a decentralized hosting decision is made. Additionally, a containerized version will be made publicly available allowing for mirrored instances to be run locally alongside self-hosted Ethereum Classic node clients to include Besu and CoreGeth. The UI will interact with the smart contracts on ETC network and other blockchain networks through the use of a network's exposed RPC endpoints using a JSON API running as a back-end React database under node.JS on a INSERT BWCD HOST load-scaled AWS- or Azure-style virtual server.

## The Tokenomics of ValueForgedETC

The ValueForgedETC ecosystem utilizes several tokens on the ETC network and will deploy on other networks in the future as needed. The following table lists the tokens included in the initial deployment and their function within the ecosystem:

The tokens of ValueForgedETC
Token name
Token symbol
Role
ERC-20
ForgedUSD
FUSD
stablecoin
x
ForgedBTC
FBTC
stablecoin
x
VFHammerControl
VFHC
governance
x
VFBellowsShare
VFBS
liquidity
x
VFAnvilSwitch
VFAS
utility
x

### 5.1  ForgedUSD  (FUSD)

The ForgedUSD token is ValueForgedETC's flagship product and its reason for existence. The total supply of ForgedUSD in circulation will be fluctuated as required by the controller smart contracts' algorithms in order to hold its value to within 0.4% of its value-pegged asset, the U.S. Dollar. The contract will utilize a number of off-chain oracles for fixing of the ETC/USD price ratio. The same oracles that the contract uses for the price fixing function will be used whenever ForgedUSD is newly minted which can be accomplished in only two ways: either 1) by sending ETC to the controller contract through transactions created using the ValueForgedETC User Interface application or, in rare instances, 2) autonomously by the controller contract itself while maintaining the value peg.

### 5.2  ForgedBTC (FBTC)

The second stablecoin token of the ValueForgedETC ecosystem, ForgedBTC, will be algorithmicly pegged to the value of Bitcoin. Its circulating supply will be controlled using the same smart contracts as ForgedUSD; holding its value to within 0.4% of Bitcoin's value as price fixed by the oracle contract. The addition to the platform of a second token that is value-pegged to an off-chain asset provides an added layer of liquidity protection for participants in the ValueForgedETC ecosystem and should buffer the effects of market volatility on the platform's ability to maintain the value peg of its assets. FBTC will be minted in the same way and by the same contract and User Interface application as is FUSD.

### 5.3 VFAnvilSwitch Token (VFAS)

The VFAnvilSwitch token is the innovative, stabilizing third leg of the ValueForgedETC platform. It is a utility token used within the ecosystem to control the flow of value through the platform. Minted at a 1:1 ratio with the transactional value of ETC sent by an external transaction into the platform making them equivalent to wrapped ETC for use inside the ValueForgedETC ecosystem, VFAS are ERC-20 compliant tokens used by the platform as an internal store of value, a representation of entitlement portions, an authorization token, and serving other valuable and necessary functions within the ValueForgedETC platform, but possessing no inherent monetary value or functionality outside that system. It should not be directly traded or be listed on any DeFi or CeFi exchange. As stablecoin tokens are newly minted, whether FBTC or FUSD, the process is facilitated and monetized with the ETC first being converted into VFAS to carry the ETC's value into the ValueForgedETC ecosystem along with the instructions included in the transaction that the various contracts will then use to fulfill the actions as requested by the transaction sender.

6. Smart Contracts and the ANVIL Tokenomics Balancer Model

It is expected that a number of interrelated smart contracts will be deployed to the Ethereum Classic blockchain in the deployment of ValueForgedETC. The platform's contract design is modular in nature which allows for future upgrades, adding features, fixing latent bugs not evident until after deployment, or other necessary changes to the live contract. Upgradeability is accomplished through use of the proxy method in OpenZeppelin's upgradeable smart contract library.

The platform's core functions are divided into separate groups of contracts, the Forge, the Bellows, the Hammer, and the Anvil. Each contains the logic of one particular aspect of the platform, but are not standalone functional. Working together, however, these four contract groups bring the ValueForgedETC ecosystem to life and open the door to many exciting, reliable, and secure financial services for Ethereum Classic users.

### 6.1 Algorithmic Design Overview

The `Anvil.sol` smart contract is the ValueForgedETC ecosystem's entry and exit point. It contains the logic of the ANVIL Tokenomics Balancer algorithm responsible for maintaining the controlled assets' value-peg and controls the flow of value throughout the entire platform. The ANVIL algorithm, which stands for Aggregate Normalized Value Incentivized Liquidity, uses an array of functions and adjustable parameters  throughout the contract structure to accomplish the primary function of ensuring that the stablecoin tokens' value remains as close as possible to its off-chain pegged asset's value. At each activation of the Anvil contract, the ANVIL algorithm analyzes the platform's ecosystem by taking the following steps:

Determines the value of USD and BTC expressed in ETC.

Collects latest data from available oracles.

Calculates the pegged assets aggregate value.

Determines deviation from peg value expressed in ETC

Retrieve the balances and ratios of liquidity pool assets

Checks status of algorithm-placed AMM orders on DeFi exchanges.

Retrieves market sentiment index

Combines all data points using a proprietary weighting calculation with the result expressed as a derived numerical score.

This derived score is important as it is used throughout the ANVIL algorithm in many of its analytical functions. It is a qualifying indicator of the severity of the current deviation from peg value for each controlled asset. Using a trend line created from historical derived score data, the algorithm can determine if its prior adjustment actions have achieved the desired impact on the stablecoins' valuation. Comparison with the  value deviation can sometimes be couterintuitive due to anomalies in the oracle data set or sudden unexpected market moves. Over time, the relationship between value deviation and derived score can be readdressed and adjustment made in a future contract upgrade with greater understanding of the complexities these two factors attempt to encapsulate.

In addition to the broad generalizations above, the algorithm affects each contract group individually and the platform as a whole in subtle yet crucial ways. For example, the ValueForgedETC web-based user interface app will offer to users any discounts to fees or other incentives the algorithm has determined would be in the best interests of the ecosystem when FUSD or FBTC is newly minted by the Forge contract group. To better understand the ANVIL algorithm's non-action effects on the platform it is useful  to visualize the pathway data and value take through the various functions of the Bellows, Hammer, Forge, and Anvil contract groups.
The following chart illustrates the flow of logic and value throughout the ValueForgedETC platform:

Insert contract data-value flowchart

### 6.2 Maintaining the Value Peg

In order to decide what actions, if any, to implement in order to keep the platform's stablecoin value deviation from the pegged asset's value as low as possible requires the algorithm to first determine an accurate current aggregate value of the stablecoin assets. This is the “fixed price” that will be used for minting of new FUSD or FBTC before any ANVIL remediation actions are implemented for this round. To obtain accurate information on which to base the “fixed price” will require an oracle data feed which includes current spot market price data from at least six major centralized exchanges, preferably more, all swap exchanges available on the ETC network, and at least three independent industry analysis reporting agencies such as CoinGecko and CoinMarketCap. The data should include, where applicable, market summaries including order book depth, trading volume, and 24-hour transaction count.

At the time this whitepaper was produced, no such oracles exist on the ETC blockchain. This situation must be rectified before the ValueForgedETC project can be continued. If no other software company or development group deploys an oracle contract with an acceptable data set on the Ethereum Classic mainnet by the time this project is ready to move forward, VaueForge will take up the task of delivering an oracle to facilitate this project.

1. Adjustable, scaled seigniorage rewards – a sliding scale cost imposed on minting new FUSD or FBTC tokens with increasing fees intended to slow growth of the circulating supply of stablecoin tokens in existence. At minimum, a 1% seigniorage reward will be deducted from the transaction value of a minting order. The value reduction will increase up to an adjustable cap limit initially set to 18%. Seigniorage is calculated and collected on the amount of ETC sent to the ecosystem with order to mint new stablecoin tokens. As the size of minting order increases, so does the  seigniorage collected. This is the first and most used method the algorithm will employ to influence the value-pegged stablecoin token's market price.
2. Bonus minting incentives – a bonus of ETC added to an amount of ETC sent into the ecosystem with a minting order for FUSD or FBTC tokens designed to encourage growth of the circulating supply of FUSD or FBTC.. Minimum minting order sizes or other conditions may apply. Bonus may be a percentage of the ETC the user is converting or may be a fixed amount of ETC. The bonus ETC added to the minting order comes from ETC reserves held by the contract suite for such matters and does not affect the redeem value or fungibility of FUSD or FBTC tokens that are subsequently swapped back into ETC.
3. Burn call –  a bonus amount of ETC applied to swap transactions that result in FUSD or FBTC being burned and its value converted to ETC. It has the same parameters and options as the ETC bonus to minting above. This action may be initiated to foster a reduction in a controlled asset's total circulating supply.
4. Automated Market Maker (AMM) orders – Buy and sell orders may be opened by the algorithm in the DeFi markets on the Ethereum Classic mainnet. This tool can be used to influence several market conditions or platform tokenomics. Orders placed may be canceled if the market conditions or value deviation changes before orders placed are filled.
5. Liquidity Pool participation incentives – As conditions warrant, the Bellows contract liquidity pool may offer incentives for participants to enter or exit the liquidity pool. While incentives may be offered for both entry and exit, there will never be a penalty applied for remaining in the pool when exit is being encouraged. Some incentives offered may be in the form of a deferred redeemable discount on future token minting. There will always be on such discount-minting offerings a stated deferral period before discount-minting may be used and an expiry date after which the incentive will no longer be valid. Other conditions may apply which could potentially prevent the use of discount-minting until after an incentives expiry date resulting in 100% loss of value.
6. Liquidity pool stability-locking – At various times and in certain circumstances, the liquidity pool may be locked to arrest sudden, sharp demands on liquidity which could damage the platform's ability to maintain the value peg. Stability-locking freezes all liquidity pool token balances for a defined period of time. The pool will never be stability-locked for more than an adjustable, stated time period initially set to 72 consecutive hours. A minimum of at least 4 hours of normal pool operations are mandated between stability-locked periods. Stability-locking is in addition to the periods of time during which the liquidity pool may be locked or under restrictions that are a normal part of the platform's routine operation.
7. Token rebase – In extreme instances, should one or both stablecoin tokens lose the value peg with its corresponding off-chain asset and all other attempts to reduce the value deviation have failed, an emergency rebasing of the stablecoin may be enacted. This extraordinary measure will lessen the effects of a market detachment event on individual investors by spreading those losses across the entire supply of the token, resetting the platform with all token balances reduced at the same rate regardless of a token's location and whether it is within or outside the platform. Should a token experience rebase, it may or may not affect the platform's other tokens. Rebasing may include and affect only one token, multiple tokens or all tokens controlled by the algorithm.
8. Governance: VFHammerControl (VFHC) Token
   In keeping with ValueForge's dedication to the foundational principles of Ethereum Classic, maximizing decentralization is one of the constant goals of all our development activities. Incorporating a governance protocol that fairly serves everyone, one that does not have a group of oligarchic curators filtering proposals or that requires so large a stake it becomes a barrier to participation, has been challenging. The unique way in which we utilize the Hammer token as a governance mechanism while it also serves a vital stabilization role in the ANVIL tokenomics model is our attempt to reduce gaming of the system, promote broad governance participation, scale influence so that small stakeholders are not lost under the weight of staking whales and, most importantly, allow for maximal decentralization in as short a time span as possible.

7.1 Token Distribution
VFHammerControl (VFHC) tokens, like all the other tokens that are part of the ValueForgedETC platform, are minted by the Forge contract. When a transaction to mint new stablecoins (FUSD or FBTC) injects new value in the form of ETC into the platform, a number of VFHC tokens are also minted and sent to the same user address that receives the FUSD or FBTC. VFHammerControl tokens are bot produced on a 1:1 ratio nor is there a fixed emission schedule or amount. Rather, a number of factors are monitored by the ANVIL algorithm that will influence how many VFHC are produced with each minting event. This variability in minting quantity allows the algorithm to manipulate VFHC token emission as a method of capturing and releasing value within  the platform's ecosystem ensuring greater stability. Also, at the algorithm's discretion, there may be incentivized offers made to platform users to opt out of or increase participation in the governance system by minting more or fewer VFHammerControl governance tokens when stablecoin minting orders are placed. Exersizing such an option may result in a bonus of other platform tokens being minted as part of the same transaction.
Overall, the dual functionality of the VFHammerControl token and the algorithmicly controlled dynamic variation in its minting rate provide a disconnect between the percentage of the total value one controls within the platform ecosystem and the influence over governance that control would bestow in a static governance model.

7.2 Governance Mechanism
As a governance token, VFHammerControl tokens will behave much like any other token used within a DAO governance system. Governance is primarily achieved through a process of proposal approval or rejection. Since exercising control over a system which contains value is itself valuable, the ValueForgedETC platform requires that one expend some value in order to wield that power. An amount of VFHC tokens will be required to interact with the Hammer contract for such governance functions as initiation of a new proposal process, calling a proposal to a vote, voting to accept or reject a proposal, or delaying the call to vote on a proposal, among many other functions. The initial amount of VFHC required for each function call has yet to be determined, but these amounts as well as many other variables within the governance system will be programmaticly variable after deployment of the platform though an upgrade to the Hammer smart contract logic. Such modifications will only be possible through the acceptance of a governance proposal to make said modifications.
This section of the whitepaper will be expanded to include an exhaustive list of the interactive transactions possible using VFHammerControl tokens as development of the ValueForgedETC governance mechanism progresses. Design philosophy for the interactive mechanism is that it be user friendly, comprehensive, and modifiable while maintaining its complete auditability, full transparency, and absolute immutability.

7.3 Voting and Decision Making
It is important to remember that exercising one's power always expends one's ability to do so. This value for value principle is what limits and regulates governance of the ValueForgedETC platform and ecosystem. Periodically as needed but at least once a year, the ANVIL algorithm will initiate a governance proposal for consideration by the platform's user base concerning what, if any, modifications to its parameters should be made. With this one exception, all other proposals are the submissions of platform participants through the governance section of the ValueForgedETC User Interface. Every interaction one initiates with the governance mechanism has an associated cost in VFHC which is consumed by the transaction's successful completion.
Proposal submission costs are calculated off-chain in the ValueForgedETC UI based upon transparently available and verifiable on-chain factors. Base submission costs are scaled into three tiers depending upon such factors as which system's variables are modified, the level of approval required for proposal acceptance, and the time allotted for proposal discussion and voting. While many proposals may be active within the system at the same time, only one proposal may be under a call to vote at any given time.  The faster a user submitted proposal is moved through the process the  more expensive it becomes to advance it to the next step.
A proposal flows through a number of stages on its path toward Acceptance or Rejection in the final Open Voting process as laid out below:

Proposals are submitted from the ValueForgedETC UI with one of three flags: Standard, Grassroot, or Expedited.
Proposals are queued in a Submission Pool where its parameters are publicly viewable until advancement is triggered.
For Standard proposals, advancement is triggered when that proposal has been in the Pool for at least 14 days and is the oldest proposal in the Submission Pool.
For Grassroot, advancement is triggered when a proposal has received a number of “nods” from unique EOAs indicating sufficient interest in its advancement and it is the oldest proposal in the Pool. The number of nods required is initially set to 150.
For Expedited, advancement triggers automatically when there is availability in the space-limited next stage.
Advancement moves a proposal submission to Active Discussion status. There is a limit on the number of proposals in Active Discussion status at one time, initially six. This limitation may be adjusted upwards or downwards by one every three months, if conditions warrant.
Proposals remain in Active Discussion status until they are advanced, retracted, or become dormant. Dormant proposals expire after 7 days of inactivity. Proposals may be Retracted from Active Discussion by the submitting owner at any time.
Advancement from Active Discussion status occurs when a platform user, who may be but is not required to be the proposal's author, makes a Call for Vote. This advances the proposal status to Under Consideration.
The Under Consideration period is initially set to five days. During this period, debate can continue until the Call for Vote terminus or the vote may be accelerated by a second Call for Vote which cannot be made from the same EOA as the original Call. This is congruent with the Motion and Second actions found in common Parliamentary Procedure. A Second Call to Vote immediately advances the proposal and begins the Voting Open procedure.
During the period that a proposal is Under Consideration, circumstances could arise which cause the ANVIL alogrithm to pause all contract execution for a period of time during which token movement within the platform will be frozen. Should this happen, the Call for Vote terminus will be delayed for the corresponding amount of time that token movement was frozen.
When a proposal is advanced to Open Voting, an event notification is sent to the sponsor EOA from which it was submitted, the EOA which issued a Call to Vote or Second Call to Vote, if any, and all EOA participants in the on-chain discussion notifying them of the number of ValueForgedHammerControl tokens  that have already been expended interacting with this proposal and that they have 48 hours in which to vote those tokens or they will be counted as Voting Abstain votes.
The Open Voting period lasts 48 hours during which all VFHC tokens in existence have the right to be cast as votes either For or Against the proposal or as Voting Abstain. Voting Abstain votes are counted neither for nor against passage of a proposal but do count towards calculating the Quorum and Margin of Victory requirements for a proposal to be Approved. All VFHC tokens that are voted are subsequently burned without consideration of whether the proposal on which they were voted was Approved, Rejected, or procedurally Disqualified for failure to meet Quorum or Margin requirements.
After the 48 hour time for Open Voting has expired, the proposal ends and is declared to be Approved, Rejected, or Procedurally Disqualified.

8. Liquidity Provision: ValueForgedBellowsShare (VFBS) Token
   One of the most important aspects of a DeFi ecosystem is liquidity. Without sufficient liquidity, users are unable to buy or sell tokens at fair market prices. The ValueForgedETC platform incentivizes liquidity providers through an incentivized liquidity pool facilitated by the Bellows contract. Users deposit various tokens into the pool, which is then used to facilitate trades on the platform.
   8.1 Token distribution
   When a user deposits tokens into the liquidity pool, they are issued a proportional amount of ValueForgedBellowsShare (VFBS) tokens, which represent the value held in the pool. The value of each user's deposit is determined by ANVIL analysis and the user's chosen conditions, such as the length of time the tokens are locked in the pool.
   8.2 Incentivized Liquidity Pools: Rewards, Penalties and Distribution
   ANVIL controlled
   8.3 Caveats for Liquidity Providers
   Impermanent loss.
   Permanent loss.
   Likely a security.
   Taxes.
   Private keys.
   Disclaimer.
9. Valuation Adjustments: ValueForgedAnvilSwitch (VFAS) Token
   Internal store of value. Will interact with other DeFi when integrated.
   9.1 Token distribution
   1 : 1 with ETC entering the ecosystem.
   9.2 Incentivized Liquidity Pools: Rewards, Penalties and Distribution
   Liquidity is incentivized, and penalized as directed by ANVIL.
   9.3 Integration with other DeFi platforms
   Hopeful...
10. Security, Audits, and Regulatory Compliance
    Thorough in-house testing on a private development network
    Alpha smart contracts deployment testing on Mordor testnet
    External code audits and security reviews
    Revision and stress/load beta testing on Mordor testnet
    Continuous bug bounty programs
11. Roadmap and Future Development
    ValueForge is committed to the continued development and improvement of the ValueForgedETC platform. The current roadmap includes the following milestones:
    Q2 2023: ValueForgedETC whitepaper released to the public.
    Q3 2023: Deployment or adoption of required utility infrastructure (ie. Beacons, DappNode for RPC endpoints, IPFS, etc.)
    Q4 2023: Closed alpha testing of the contract suite. Development of UI/UX.
    Q1 2024: External security audit. Internal financial auditability reports.
    Q3 2024: Mordor deployment for open beta testing. UI deployment. Phased release deployments scheduled.
    Late Q4 2024: Phase 1 mainnet initial release and UI v1 release. [ANVIL, Forge, FUSD, VFAS]
    Early Q1 2025: Phase 2 mainnet update release [FBTC, VFBS, liquidity pool]
    Late Q1 2025: Stage 3 mainnet full production update release [VFHC, governance]
12. Conclusion
    The ValueForgedETC platform is a decentralized finance ecosystem built on the Ethereum Classic blockchain. It offers a range of stablecoins and incentivized liquidity pools, as well as governance, with value exchange mechanisms to ensure the stability,  continued growth and decentralization goals of the platform.
    The development team is committed to providing a secure and reliable platform for users, continuously working to improve and expand the platform's capabilities and provide seamless integrations with other DeFi products. The team is also dedicated to maintaining strict compliance with all the Foundational principles of Ethereum Classic such as decentralization, immutability, censorship resistance and open source. Where applicable, we will remain compliant with relevant regulatory requirements further ensuring the safety of user funds.
    Our pledge is to develop and maintain the ValueForgedETC ecosystem with integrity and professionalism, transparently auditable and openly accountable. Overall, the ValueForgedETC platform represents a new era in decentralized finance, providing users with greater flexibility, security, and decentralization in their financial transactions now and into the future.

Contract
Role
Tokens Affected
Uses and options
Forge
Minting
Burning
FUSD, FBTC, VFAS, VFBS, VFHC
Mints and Burns stablecoin tokens as directed by the ANVIL algorithm
May only be called internally
Bellows
Liquidity
VFBS
Liquidity pool management
Determines liquidity incentive
Distributes liquidity incentives
May only be called internally
Hammer
Governance
VFHC
Governance framework
Receives proposed initiatives
Receives initiative votes
Determines governance participation incentive offset
Called internally and externally
Anvil
Algorithmic Balancer
VFAS
Algorithm flow control
Accepts external (user) input
Processes transactions into and out of the ecosystem
Accumulates converted ETC

This section holds an in-depth discussion of the actions that the ANVIL Tokenomics Balancer Model algorithm may use for effect on the market. It is expected that the value of the stablecoin assets FUSD and FBTC will show the most volatility in the first few weeks following introduction becoming less volatile over time under normal market conditions. As adjusting actions are used and market response is then evaluated, the decision-making abilities of the algorithm will gain precision through analysis of its own historical data.
Among the actions that the algorithm may take to exact a reduction in the current value deviation are:
