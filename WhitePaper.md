# TrueDeck WhitePaper

**October 13, 2018**

<!-- MarkdownTOC depth=2 autolink=true bracket=round list_bullets="-*+" -->

# Contents
- [Disclaimer](#disclaimer)
- [Vision](#vision)
- [A note on Regulation and Compliance](#a-note-on-regulation-and-compliance)
- [Abstract](#abstract)
- [Background](#background)
- [Introduction to TrueDeck](#introduction-to-truedeck)
  * [Online gambling and the Blockchain](#online-gambling-and-the-blockchain)
  * [Objectives](#objectives)
  * [The solution and benefits](#the-solution-and-benefits)
- [Platform](#platform)
  * [Layers](#layers)
  * [Technology](#technology)
	+ [Modules](#modules)
	+ [Selection of Blockchain](#selection-of-blockchain)
	+ [Storage](#storage)
  * [Entities](#entities)
  * [Tokens](#tokens)
- [Development Plan](#development-plan)
  * [Proof of concept](#proof-of-concept)
  * [Platform development](#platform-development)
  * [Ongoing research](#ongoing-research)
- [Token Sale](#token-sale)
- [Conclusion](#conclusion)

<!-- /MarkdownTOC -->

# Disclaimer
*This document is a working document and will be reviewed and updated throughout the course of the development of the platform. TrueDeck Ltd reserves the right to update the information contained within this document, at its discretion. The latest version will always be available at http://truedeck.io.*

*This high-level whitepaper sets out Truedeck Ltd. as a business, outlines its products, current and future developments including the TrueDeck Platform and TrueDeck ecosystem. This whitepaper is for information purposes only and is not a statement of future intent. Unless otherwise specified, the products set out in this paper are currently under development and are not currently in deployment. Through this whitepaper, Truedeck Ltd. outlines the strategies being implemented and products developed to ensure success. However, Truedeck Ltd. makes no warranties and no person is entitled to rely on the contents of this paper or any inferences drawn from it, including in relation to any interactions with TrueDeck or the technologies mentioned in this paper. TrueDeck Ltd rejects any and all liability for any loss or damage of any kind \(whether foreseeable or not\) which may arise from any person acting on any information and opinions relating to TrueDeck, the TrueDeck Platform or the TrueDeck Ecosystem; as contained in this paper or any information which is made available in connection with any further enquiries, notwithstanding any negligence, default or lack of care.*

*Trudeck Ltd. does not encourage the buying of TDP tokens with the intention of short-term speculative investment. TDP tokens do not represent equity entitlement. TrueDeck tokens should be bought by those individuals who wish to be a part of the ecosystem. They must believe in the future of online casino industry for which TrueDeck is laying the foundation today.*

*The information contained in this publication is derived from data obtained from sources believed by TrueDeck Ltd to be reliable and given in good faith, but no warranties or guarantees, representations are made with regard to the accuracy, completeness or suitability of the information presented. It should not be relied upon, and shall not confer rights or remedies upon, you or any of your employees, creditors, holders of securities or other equity holders or any other person. The opinions reflected herein may change without notice.*

*TrueDeck Ltd, its directors, employees, contractors and representatives do not have any responsibility or liability to any person or recipient \(whether by reason of negligence, negligent misstatement or otherwise\) arising from any statement, opinion or information, expressed or implied, arising out of, contained in or derived from or omissions made from or in this paper. Neither TrueDeck Ltd nor its advisors has independently verified any of the information, including the forecasts, prospects and projections contained in this paper. All information has been researched according to the current marketplace and business landscape. Whilst every effort has been made to ensure that statements of facts made in this paper are accurate, all estimates, projections, forecasts, prospects, expressions of opinion and other subjective judgments contained in this paper are based on assumptions considered to be reasonable as of the date of the document in which they are contained and must not be construed as a representation that the matters referred to therein will occur.*

*Any plans, projections or forecasts mentioned in this paper may not be achieved due to multiple risk factors, including without limitation: defects in technological developments, legal or regulatory exposure and changes, market volatility, sector volatility, corporate actions, or the unavailability of complete and accurate information. This being said, all measures are being taken to ensure Truedeck Ltd. produces the best possible technology, which is compliant across jurisdictions.*

*TrueDeck Ltd may provide hyperlinks to websites of entities mentioned in this paper, however the inclusion of a link does not imply that TrueDeck Ltd endorses, recommends or approves any material on the linked page. Such linked websites are accessed entirely at your own risk. TrueDeck Ltd does not accept responsibility for any such material, nor for consequences of its use.*

*This paper is only available on http://truedeck.io and may not be redistributed, reproduced or passed on to any other person or published, in part or in whole, for any purpose, without the prior, written consent of TrueDeck Ltd. The manner of distributing this paper may be restricted by law or regulation in certain countries. Persons into whose possession this paper may come are required to inform themselves about and to observe such restrictions. By accessing this paper, a recipient hereof agrees to be bound by the foregoing limitations. Truedeck Ltd. is not liable for any litigation that may arise from the unlawful redistribution, reproduction, or publication - in part or as a whole.*

---

### Vision
To be the world’s largest casino platform by reshaping the standard of the online casino industry.

### What is TrueDeck
TrueDeck is a unified blockchain-based platform built for the online casino industry. TrueDeck provides a medium of exchange for all actors involved i.e. players, developers, operators etc. Instead of being a blockchain counterpart of online casino businesses, TrueDeck aims to provide better tools, business insights and infrastructure which enables them to provide better experience to players while reducing cost.

### Mission
To create a robust but simple protocol which leverages Smart-Contracts and Blockchain, coupled with Data Science, to provide services within the online casino industry and beyond, that have so far not been envisaged.

### Values
TrueDeck values transparency, decentralization, compliance and community above all else.

---

# A note on regulation and compliance
The online gambling industry has grown and changed over the last 20 years. TrueDeck is committed to helping this industry by providing game-changing technology which provides entertainment, but most importantly builds trust. 

The legal and regulatory landscape has also evolved and will continue to evolve as time goes by. At TrueDeck, we are not only reshaping the standard but aiding in the progression and implementation of best-practices across the gambling world using blockchain technology. TrueDeck wants to become a key contributor in redeveloping the technological body of this industry from ground up while adhering to the standards set by law and respect existing jurisdictional laws, even at the detriment of platform adoption, if necessary.  

Our team is based around industry veterans, who have pledged to help the evolution of the TrueDeck platform and its features to provide ground-breaking, open, fair and economically-sustainable products for businesses, developers and players alike. 

For the reasons stated above, TrueDeck aims to partner with leading global providers of age and identity verification solutions to ensure compliance to KYC/AML needs and perform  due diligence of corporate social responsibility to protect minors from underage gambling.

---

# Abstract
TrueDeck is an online casino platform to enable operators, developers and players to interact transparently through blockchain. TrueDeck leverages Smart Contracts & Blockchain technology to provide a truly transparent and cryptographically secured casino experience. The platform caters to online gambling businesses and entities i.e. casino operators, gaming solution providers, affiliates and players. The platform intends to be a “one-stop shop” for all services related to online gambling that includes but not limited to blockchain-hosted games, KYC/AML services, smart contract based bankroll management, data intelligence, crypto payment gateway integration and games from leading gaming solution providers.

TrueDeck token is the cryptographic asset that will be sold during the development journey of TrueDeck in order to collect enough resources that can help TrueDeck achieve its milestones. TrueDeck tokens should be bought by those individuals who wish to be a part of the ecosystem. They must believe in the future of online casino industry for which TrueDeck is laying the foundation today.

Over the time, man has found a million different ways to gamble, even at gas stations, bars, open fields, casinos and even the virtual world since the start of the millenium. But the actors involved in this industry still faces many problems; being cheated by rigged odds, long delays in payments, security of funds, stress of being compliant to KYC/AML checks, round the clock availability to name a few. Although online gambling industry has enjoyed the benefits of recent developments in software industry to provide real-time gambling to millions of users, still legacy infrastructure keeps their mechanisms behind closed walls. 

With TrueDeck, operators, developers and players will witness a new way to gamble which provides the same experience but offers a great level of transparency and access to valuable insights. TrueDeck will aid online casino ecosystem to discover new possibilities by incorporating blockchain and getting it reshaped from ground-up.

We believe the unified platform should cater all actors involved. The platform should be structured in such a way that the ecosystem can nurture itself in a self-governed way whilst maintaining complete harmony with the needs of all.

---

# Background
Gambling is one of the oldest known pursuits of mankind. The first online casino went live in 1994. Over the past 20 years, the online gambling industry has rapidly grown to become a multi- billion dollar industry. Its history has been full of twist and turns and highs and lows, with each step helping to make it into the immense industry it is today. In 2018, the online gambling market is predicted to grow to $56.05 billion. Online gambling takes on many forms - Poker and other Casino games, Sportsbetting, Novelty betting, Bingo, Fantasy sports, among others. 

However, although advances have been made, there is a lack of unified standard within the industry which has lead to hacks or scams. Existing platforms do not offer enough transparency to players, and their trust is placed in the hands of auditors and gambling commissions who strive to ensure that trust is kept. Despite numerous and continued changes, there is still a scope for improvement using recent technological developments.

The idea was born when a group of people, with a background in online gambling industry and technology, came together to innovate the industry through blockchain. We wanted to create a protocol which makes predicting outcomes impossible and a platform which connects all the actors involved.

We started writing, planning and brainstorming the ideas which have gone into shaping TrueDeck. While several blockchain casino projects had implemented games through state-channels, TrueDeck has come up with innovative approach with real-time game speed. TrueDeck has been the first in the industry to come up with full decentralized architecture for the platform, whilst giving casino businesses complete power to define their own strategies.

Other blockchain casinos focus on just creating a single casino or deploying independent games for different casinos, however the ground-breaking innovations of the TrueDeck platform will reform the entire online gambling industry.

---

# Introduction to TrueDeck
TrueDeck wants to reinvent the way online gambling industry operates. There are several impressive implementations by other blockchain casino projects, however TrueDeck is different because:

- A unified platform which caters to all actors involved: players, developers, operators etc.
- Provides complete decentralization from random number generation to payout distribution.
- Has developed technology to provide blockchain casino dApps with real-time game speed.
- Is the first casino platform running as a Decentralised Autonomous Organization.
- Only the one which can save operators a significant amount in operational cost.

TrueDeck will be working with existing online casinos to strengthen the foundation of online gambling industry, initiating an industrial wave to provide better and safer gambling experience to players.

## Online gambling and the Blockchain
Blockchain can be the real savior, iGaming industry was waiting for. It’s a match made in heaven. The synergies for demographic interest and the pain points that blockchain resolves for this industry, can’t be ignored. Despite the radical improvement in iGaming technologies, there is still a lot left to be disrupted. Blockchain technology will surely set the standard for future of iGaming.

But many blockchain casino projects have created smart-contracts to payout dividends to their token holders. Whereas TrueDeck is creating a value proposition to online casino businesses and its token holders. TrueDeck is strictly against paying dividends to its token holders, instead we have defined plenty of utilities around the token. TrueDeck has combined the best of what blockchain technology can offer, in order to create the ultimate platform to facilitate online gambling in a truly transparent manner.

### Setting the standard for the Online Gambling Industry
With the advent of blockchain technology and its endless possibilities, online casino industry can voyage into a whole new era. In order to get the full exposure, the industry should join hands in defining a common standard. TrueDeck believes the following practices must be carried out by actors involved:

#### Decentralised RNG
A random number generation mechanism which is decentralized and completely unpredictable. Generation should be as per the industry standards; fast and fair. It should be provably verifiable and auditable by anyone. 

#### Real-time Monitoring
All actions should be public and monitored in real-time to detect any cheat or fraud. Random number generation should also be monitored real-time instead of a few checks in a year. 

#### Strong KYC/AML Checks
Being the highly regulated industry, strong KYC & AML checks should be carried out by all entities involved. However the blockchain technology provides anonymity, but the actors involved should enforce these checks wherever applicable in support of “Responsible Gambling” standards and AML laws.

#### User Protection
User data protection should be the utmost priority across this industry. Operators must have robust systems in place to keep their information safe. They should also comply with the laws enforced by the jurisdictions in which they operate.

#### Security of players’ funds
Online casino industry used to be loosely regulated, but has been transformed into a credible and thriving industry. Thus, it is most important to keep the players’ fund secured. Operators and gaming solution providers should come up with solutions to keep them secured from hackers and remove any vulnerability from their systems.

#### Fast Deposits and Withdrawals
Deposits and withdrawals has always been a dissatisfaction to players while playing games online. Despite internet banking has made the process much faster but it is expensive due to involvement of so many third parties. They take their chunk of profit for providing this service. Deposits and withdrawals should be faster and cheaper for easy on-boarding of new players. Still they should be processed in accordance with the AML laws.

#### Performance
To keep up with the industry advancements, casino websites should strive for 99% uptime in order to provide best gaming experience to players. 

## Objectives
TrueDeck wants to aid in reshaping the standard for online gambling industry, bringing forth new technology in order to establish a best-practice policy for the future. The entire objective of TrueDeck is to create a unified platform built on the foundation of Blockchain technology that implements all of the practices described above and set the standard for the future of this industry.

TrueDeck does not seek to preside over the casino industry, but it wants to empower and strengthen every aspect of it. TrueDeck strives to develop a way to make online casino mechanisms transparent as well as a medium of exchange between all actors to facilitate the operations of online casino industry.


## The solution and benefits
At TrueDeck, our focus is to create a platform to provide solutions for all actors of online casino industry; as well as potentially many satellite business sectors.

TrueDeck platform will be developed in a way that it caters to the needs of all. The solution will bring following benefits to the entities involved:

### Operators
Operators can migrate their infrastructure to the TrueDeck platform and be assured of 99% SLA for coverage, as well as take advantage of huge savings on operational overheads. Outsourcing operational functions of business units with confidence in regulatory compliance and apex level performance is not only desirable, but it is what TrueDeck will offer. Innovating and evolving with the best in the business to set new best practice every day.

**Benefits:**
- Save money on RNG audits.
- Reduces need of security & technical staff.
- No chargebacks, Cheaper payment charges.
- Market leading SLA for minimum downtime.
- Lower compliance overheads amongst others.
- No need to setup hardware or maintain cloud instances.
- Integrated loyalty program and gamification functionality.
- All-in-one Casino management interface with no additional cost.
- Useful business insights and casino analytics to increase revenue and reduce cost.
- Handful of games by leading gaming solution providers on TrueDeck Marketplace.

### Developers
Develop games for the future of the online gambling industry and sell your services on the TrueDeck Marketplace to leading operators. Use TrueDeck Platform SDKs to build and offer fair casino games using Blockchain technologies. 

**Benefits:**
- Provide casino games to operators that offer great transparency to players.
- Exposure to a large base of operators on a single platform.
- Build up your reputation on the marketplace by providing quality games.
- Build and sell new games and services on the platform.
- Expand your product line by offering blockchain based games.
- Get “Platform Rewards” by contributing to the platform for mass-adoption.

### Affiliates
Affiliates have the opportunity to grow their affiliate business in blockchain casino space through TrueDeck.

**Benefits:**
- Join hands to promote the future of online gambling industry.
- Transparent tracking of your player base and commission.
- Attractive payment terms and instant payout governed by smart-contracts.
- Get “Platform Rewards” by contributing to the platform for mass-adoption.


### Players
Players are the key actors TrueDeck platform will cater to. TrueDeck aims to make every part of this industry transparent, a thing that was thought to be impossible due to the legacy infrastructure of casino technology. Players now don’t have to trust licensed website badges and certificates that can be faked. They can now play casino games without worrying about the fairness of games which is being monitored in real-time by the platform validators.

**Benefits:**
- Fully trust that you are playing fair and random games.
- Each action being validated by platform validators to detect any cheat in real-time and prevent the cheater from being successful.
- Low friction compliance for platform on-boarding.
- Platform wide coalition loyalty program and gamification experience.
- Lower house edge and rake on all TrueDeck platform games.
- Constantly innovative new games
- Confidence for your funds being secured by smart-contracts.
- No middlemen while depositing and withdrawing money, so cheap and fast withdrawals.


### Workers and Providers
Workers and providers perform the work assigned to them continuously. In return of their service, workers are rewarded with platform native tokens either through the platform fund. Providers get paid by consumers in TDP tokens as per their quoted fees in marketplace. Read more about workers and providers in “Entities” section.

**Benefits:**
- Opportunity to secure the platform which will be the key contributor in the future of online casino industry.
- Good and regular compensation for your service to the platform.
- Ease of deploying worker machines on cloud or on-premise facility.
- Free market for providers like Identity, Gaming, Payment solution providers etc.
- Open elections for elected worker slots to be volunteered by any individual or organization.
- Transparent, fair and decentralized election process.


## Platform
Many other projects in this space are trying to launch a single decentralized casino that caters only to players. Over time, decentralized casinos will take down the online casino industry. Whereas TrueDeck is creating a unified platform which caters to all actors involved. 

The TrueDeck platform will facilitate existing online casinos to offer blockchain based casino games. The platform will enable online casino businesses to reduce their operational cost significantly. Thus, they will be able to lower the house edge in order to compete with edgeless or zero-edge decentralized casinos.

The TrueDeck platform comprises of numerous technologies which will facilitate:
- the operations of online casinos,
- the development of casino games,
- the management of casino affiliate programs,
- and the gambling for players improving their experience.

TrueDeck team is working on some ground-breaking concepts to scale and speed up the platform to meet the needs of global online casino industry and to bring continuous innovation.


### Layers
Let’s dig into the layers of TrueDeck platform, which are defined in such a way that platform is robust, rapidly scalable and easy to maintain.

The TrueDeck platform has divided into following primary layers:
1. Core Layer
2. Services Layer
3. Applications Layer
4. Interface Layer


#### 1. Core Layer
  The “Core Layer” is the foundation of TrueDeck Platform. The core layer provides several functions i.e. identity management, on-chain governance, worker management, proposal management etc. TrueDeck platform will be adaptable to changes as agreed by DAO through on-chain governance model. This layer hosts smart-contracts that carries out essential core tasks:
  - from managing identities to restricting platform access;
  - from worker elections to their payouts;
  - from proposal submission to their adoption, rejection and implementation;
  - from on-boarding trustees to managing stakeholders etc.


#### 2. Services Layer
  The “Services Layer” offers several services combining which a whole TrueDeck application can be created. Normally, multiple services are necessary for most applications to be built on TrueDeck Platform. Individual services are hardly of any use. Notable services provided through TrueDeck Platform’s service layer will be:
  - Decentralised Random Number Generation
  - Bankroll Management
  - Payout Management
  - Fiat and Crypto Payments
  - Platform-wide Coalition Loyalty Program
  - Cheat and Fraud Detection
  - Casino Analytics
  More services will be developed as deemed useful or demanded through proposals.


#### 3. Applications Layer
  The “Applications Layer” consists of open-source smart-contact libraries and game logics required to create casino dApps or any other game dApp. Developers will be able to reuse the libraries and integrate their own game smart-contracts to TrueDeck platform. To prevent a developer of new game from cheating players, all smart-contracts will have to be audited by the smart-contract auditing providers through TrueDeck Marketplace. Only after approved by the smart-contract auditors, developers would be able to integrate their new game smart-contract with TrueDeck Platform.


#### 4. Interface Layer
  On top of all platform layers, there will be an “Interface Layer”. This layer will comprise of front-end libraries, open-source skins and applications for several user-interfaces of the platform. A developer will be able to create his own front-end for existing games or a completely new game. TrueDeck team will develop default interfaces of all popular games and platform apps. 

### Technology
Blockchain technology is revolutionary but it’s still in its infancy phase. Ethereum was the first turing complete smart-contract blockchain platform, having a blocktime of 15 seconds and finality in 20 confirmations. Many projects are now trying to achieve sub-second block time and finality in 2 seconds. However, it’s good for fast payments and other use-cases but still not enough for casino games. For example, ideal hand speed in BlackJack game should be 0.3 second for great user experience.

The best solution is to have task-specific blockchains instead of generalized blockchains. Blockchains intended for general use-case have properties that are suitable for broad range of actions like having a large block time. It’s fine for cryptocurrency payment transactions taking minutes for confirmation, but actions which are triggered by players in a game require instant feedback else it hinders with player experience.

TrueDeck is adopting cross-blockchain approach for its platform to combine the best of every blockchain. This seems ambitious but recent developments in inter-blockchain communication will make it possible.

#### Modules
At TrueDeck, we are building the platform in separate independent modules. We have classified following modules as per the use-cases:
1. Governance
2. Assets
3. Game Logic
4. Player Actions

We have also defined four criterias to help us choose the right blockchain platform. The four criterias are defined as follows:
- Decentralisation
- Speed
- Stability
- Developer Ecosystem

Now let’s consider each module along with its use-cases and try to find the ideal blockchain properties:
#### 1. Governance
  Governance is undoubtedly the most important part of a decentralised platform. If it is not implemented the right way, doesn’t matter how good your use-case is and how better it has been developed, it’s not going to work out. On-chain governance has surely its benefits over off-chain governance but has some caveats also. 

  Thus, decentralisation and stability criteria carry more weight when considering the right blockchain platform for Governance mechanism. Speed is not of much importance for Governance as it does not require real-time response, confirmation within a minute would be fine.


#### 2. Assets
  An asset is the key property on TrueDeck platform. It’s anything that has a store-of-value and is used to gamble on the platform, simply put it’s players’ fund. Security of players’ fund is the utmost priority of TrueDeck platform and it cannot be taken lightly. Liquidity of crypto assets is also a key metric for a project that addresses crypto market. Supporting assets with more liquidity means more traffic on your platform and greater the adoption.

  Thus, a platform that is stable will be ideal for Asset Management to provide the apex level of security. The platform should have Developer Ecosystem with plenty of projects around assets that can facilitate the asset layer development of TrueDeck Platform. In regards to speed, the underlying platform should be capable of doing fast settlement of assets across many wallets during gameplay and moderate speed during deposits and withdrawals.


#### 3. Game Logic
  Being TrueDeck a casino platform, it must handle casino game logics with ultimate level of accuracy. The smart-contracts should be rigorously tested and audited by third-parties as well as bounty hunters. There must not be any vulnerability through which platform can be compromised. 

  Due to the above reasons, the smart-contract logics must be carried out in a language that is being widely used for a while. There should a good amount of activities and known vulnerabilities around it, so auditors can easily identify them before any mishappenings. It is also very hard to find good experts for new languages or technology.

  The speed of this use-case directly impacts the player-experience. However, the logics are only triggered when player wants to resolve the outcome and not during gameplay. Still, it is necessary that game logics are cheaper to perform and faster in calculating the outcome. Decentralisation and stability criteria carry moderate weight for this module. It would be great if there can be a blockchain implementation which is fast without compromising with decentralisation.
  
#### 4. Player Actions
  Casino games require instant response to player actions. There are a few off-chain solutions to provide real-time response like state-channels. Generalized state-channels are great when participants are going to exchange many state updates over a long period of time, but is not the ideal solution for building casino games. 

  At TrueDeck, we will use a task-specific blockchain with sub-second blocktime for catching player actions and random number generation. As player actions will be recorded on blockchain and will be immutable. It cannot be denied that an action was not triggered. 

  A very short blocktime will be required for this specific blockchain which can be achieved by ensuring only high performant nodes producing blocks. In order to ensure random number is completely decentralized, a cryptographic mechanism will be used to prevent any node from predicting the number before it is revealed in public.
  
Hence, we have identified modules along with their major use-cases.


#### Selection of Blockchain
TrueDeck team invested considerable time on exploring the best blockchain implementation for each module. We have researched the merits and demerits, current situation and possible future developments of each implementation currently live in the market.

Let’s define each module’s ideal blockchain implementations as per their requirements addressed in the modules section above:

#### 1. COREChain
  There have been a lot of new blockchain implementations to provide better security, decentralisation and scalability. Before finalizing any implementation right now, it would be better to watch this space for a few months to come. The COREChain will host the “Core Layer” of the TrueDeck Platform composed of “Governance” and “Assets” modules.

#### 2. GAMEChain
  Primarily, GAMEChain will comprise of “Game Logic” module. GAMEChain will be a task-specific blockchain responsible to hosting game smart-contracts managing game logic as well as asset settlement during gameplay. 

  Speed is the priority of “Game Logic” module followed by Decentralisation and Stability. The ideal blockchain implementation for GAMEChain must be able to achieve finality in seconds while maintaining fair amount of decentralisation among network nodes. We have shortlisted some blockchain implementations for GAMEChain, but we will watch this space for upcoming months before deciding which implementation to choose and whether to run our own GAMEChain or use the existing blockchain.

#### 3. DICEChain
  DICEChain is another task-specific blockchain accountable for catching & responding to player actions and decentralised random number generation. Speed and immediate finality is essential for DICEChain. The DICEChain must have following properties:
  - All participating peer-to-peer nodes must have low latency.
  - A block must be produced as fast as it can be broadcasted to all nodes.
  - The block must be final as soon as it enters in blockchain.
  - The DICEChain doesn’t need to be turing complete.
  - The block structure should be very basic in order to achieve small blockchain size.
  Properties mentioned above can enable the platform to achieve 0.3 second hand speed required for casino card games.

Blockchain technology is still in its nascent stage, due to which many new implementations have a degree of risk associated with them. Keeping TrueDeck’s long-term vision in mind, we are taking an approach that will allow TrueDeck to survive even when an underlying implementation goes down. This is why, the most important aspects of TrueDeck platform Governance and Assets will be built upon the most secure platform. Risk associated with any other blockchain implementation will be reduced through modular architecture of the platform and a blockchain migration tool that will allow the platform to migrate the module on a more suitable blockchain implementation.


#### Storage
Storing all game records and state of past games on blockchain is not the good design. TrueDeck casino dApp smart-contracts have been optimized to off-load all game state outside blockchain and only keeping the hash of each player’s current game state on blockchain. It is only when the game outcome needs to be resolved, the state is submitted to replay the game by smart-contract and decide the outcome. 

TrueDeck Platform will keep a record of every game on peer-to-peer file system i.e. IPFS. This data will be processed by “Data workers” to detect any cheat or fraud in real-time and preventing the cheater from being successful. This data can also be processed to create useful analytics for the casinos.

### Entities
TrueDeck is the first truly decentralised blockchain casino platform. Thus, it is important to evaluate the various types of entities and their contribution to the network in order to setup a fair incentive for each.

Entities are classified into 4 categories: User, DAO Member, Worker & Provider.

#### 1. User
Users are platform end-users who are directly associated with online casino industry. They form the most upper layer of TrueDeck ecosystem. They can be a business entity or an individual.


##### Operator
  An operator is a business entity that houses online casino games on his website or app. Operators can offer online casino games through TrueDeck platform, either migrating their existing games or using games from TrueDeck Marketplace provided by Gaming Solution Providers. A TrueDeck operator have these options for bankroll:
  - fund his own private bankroll,
  - invite bankrollers to fund the bankroll,
  - join TrueDeck’s public bankroll to attract players using large payouts.
  **Incentive:** There will be an incentive for a limited period of time for operators joining TrueDeck platform. Detailed incentive structure will be decided later.
  
##### Bankroller
  A bankroller is an entity who invests in a bankroll to get return on the investment. On TrueDeck platform, individuals, investors and businesses will be able to invest in private and public casino bankrolls. Bankroll management and distribution will be completely carried out by smart-contracts.
  **Incentive:** In order to promote investors to fund TrueDeck platform public bankroll, there will be an incentive for a limited period of time. Detailed incentive structure will be decided later.
  
##### Affiliate
  An affiliate is a business or individual who drives traffic to an online casino and get rewarded with commission. Affiliates can join programs started by operators for their casino or TrueDeck’s community casino affiliate program. TrueDeck platform manage affiliate payouts through smart-contracts. So affiliates can be assured of guaranteed payments and only work with verified online casinos.
  **Incentive:** Affiliate network is the strongest medium to promote a new platform to players. There will be an extra incentive for a limited period of time for affiliates to do marketing of TrueDeck platform. Detailed incentive structure will be decided later.
  
##### Player
  A player is the user who plays casino games with real money or social games just for fun. TrueDeck platform provides fair games to players whose mechanisms are completely transparent and can’t be manipulated by anyone. Game logics are programmed into smart-contracts and audited by third-party auditors to verify fairness. Once game smart-contracts are deployed they becomes immutable and even developers cannot change its mechanism.
  **Incentive:** Players will be rewarded with loyalty points while playing TrueDeck games. For a limited period of time after platform goes live, extra loyalty points will be rewarded. Detailed incentive structure will be decided later.

#### 2. DAO Member
TrueDeck will work as “Decentralised Autonomous Organization (DAO)” through an on-chain governance mechanism. This will help TrueDeck managing complex business functions in a completely decentralized manner. DAO Members will take decisions on proposal submitted by the community through a smart-contract voting mechanism. 

TrueDeck team is currently researching on the various governance models and designing the most effective governance model for TrueDeck Platform. 

#### 3. Worker
Workers are computers deployed by elected individuals or organizations in order to secure the platform and perform the work assigned to them continuously, throughout the day and night. We are defining more worker entities in order to keep the network efficient and secured from any attack.

DICE Worker is responsible to secure the task-specific DICEChain. It’s main task is to produce blocks for DICEChain at a very high speed. To maintain very low latency between DICE Workers, all DICE worker nodes are tested regularly and voted by TrueDeck DAO. Only the best workers with highest performance make it to the top. For every new block, a group of workers are elected at random from top workers and they jointly create a random number which is included in the new block. Before being included in block, random number cannot be predicted by anyone, not even elected workers. The complete mechanism of decentralized random number generation by DICE workers cannot be disclosed at this point.
**Incentive:** For each new block, DICE workers are rewarded with tokens. Detailed mechanism for DICE worker incentives will be decided later.

#### 4. Provider
Providers are business entities or developers that provides various kind of services to operators. Providers aids the platform growth with their offered services in key areas like gaming, identity, payments etc. All providers are not rewarded with incentives as they make profit by offering their services to operators. However, top developers of TrueDeck’s Platform will be rewarded to offer high-end games to platform operators.

## Tokens
A proper token mechanism lays the foundation of a successful decentralised project. TrueDeck token mechanism is the most significant and crucial part of TrueDeck ecosystem. After working with several legal firms and qualified lawyers, we have revised our token mechanism to minimize “token security” issues and to maximize benefits for token holders.

### TrueDeck (TDP) Token
The “TrueDeck Platform (TDP)” token is the core utility token of the platform. TDP token should be purchased with an intent to take part in the future of online casino industry, the TrueDeck Platform. TDP scope of utility is limited to the TrueDeck platform only and it does not carry any value outside the platform.

TDP token is a claim on TrueDeck Platform’s resources and a “commitment to stake” in order to avail the services offered by the platform. It is intended to be used by online casino businesses and individuals who want to be a part of the TrueDeck Platform. Here are some notable utilities of TDP token:
#### 1. Locking by casinos
  Casino operators will have to lock a certain amount of TDP in order to run their Casino on TrueDeck Platform. More amount of TDP will have to be locked to support more players.
#### 2. Locking by workers
  To be able to become a candidate in worker elections, individuals will have to lock a certain amount of TDP. The election process will be carried out by smart-contracts and DAO Members will vote for best workers as per their profile.
#### 4. Locking by providers
  Providers who will sell their services or products on TrueDeck Marketplace will have to lock a specific amount of TDP. There will be a variety of services offered on TrueDeck Marketplace i.e. Data analytics, KYC, Game development & customisation etc.
#### 5. Locking by bankrollers
  Individuals will be able to invest with a major cryptocurrency in TrueDeck bankroll to support the platform. But to be able to invest, one will have to lock a small amount of TDP. However, TDP token itself cannot be used to fund the bankroll.
#### 6. Proposal submission fees
  Proposals can be submitted by anyone to the DAO for a small fee paid in TDP which is collected in a pool. Submitter of an adopted proposal get a reward from the pool along with their fee.
#### 7. Paying for services on TrueDeck Marketplace
  Only TDP tokens can be used in order to buy services from providers on TrueDeck Marketplace and a small part of fees will either go to a platform fund or will be burned.

Instead of buying TDP tokens in order to lock it, you can get TDP tokens on lease from token holders in return for a recurring fees. This will bring benefits to TDP token holders without giving away their TDP tokens. This will also prevent speculators from holding on TDP tokens.

### TrueDeck eXperience Points (TDXP)
TDXP tokens are “TrueDeck eXperience Points”. In order to get the traction of users before the platform goes live, TDXP tokens will be rewarded to players while playing TrueDeck games. TDXP tokens does not carry any real-world value and will not be listed on exchange. It is designed to reward early supporters of TrueDeck.

When the TrueDeck platform will go live, TDXP token holders will be able to use them for in-game purchases and utilities. TDXP tokens cannot be converted to any other form of tokens, however, they can be transferred just like other tokens.

---

# Development Plan
TrueDeck team has been developing the game smart-contracts since the starting of 2018. In the past couple of months, we have been successful in optimizing the smart-contracts to an exceptional level. Through the experience that we have gained, we are now able to come up with the right approach to develop games which are fully secured by blockchain. The gained experience will lay the foundation of TrueDeck’s proof-of-concept games and the whole platform.

### Proof of concept
For proof-of-concept games, TrueDeck will be using the approach that will enable us to be live in market as soon as possible. TrueDeck will be partnering with different blockchain platforms to deploy these proof-of-concept game dapps on their platforms. This will enable TrueDeck to seek the advantages of each platform and prepping up the right mix of blockchain technology for the official platform.

### Platform development
Platform development will continue throughout the testing of proof-of-concept games. We will use the valuable feedback from community to improve our games. Platform development will be carried out in multiple stages and key goals in place. The high priority will surely be fully provably fair casino games with a common bankroll and offering them through our gaming partner channels. 

### Ongoing research
**1. Inter-Blockchain Communication (IBC):** TrueDeck is researching on achieving inter-blockchain communication. We will use this mechanism to make communication possible between TrueDeck’s task-specific blockchains in a decentralized manner.

**2. DICE Chain:** TrueDeck team is working on some approaches to create a blockchain which has the lowest latency between participating nodes and achieves instant finality without any forks. This will make developers to create highly performant blockchain based games without compromising with speed.

---

# Token Sale
Kickstarting any crypto project takes a lot of effort & resources. The foundation of a successful project is to put together a great team that put honest hard work. Raising a large capital at the early stages of a project does not make it successful. That’s why TrueDeck will take a lean approach and generate value proposition on each stage of development with fewer resources and zero waste. 

Raising large funding round would have enforced needless stress and financial obligations. Launching an ICO could have also restricted the project adaptability in various stages of it's development.

TrueDeck (TDP) Token will be used in token sales to raise funding. TDP token is not equity entitlement and should only be bought to be a part in future of TrueDeck platform. TDP token is a utility token and does not carry any use-case outside the TrueDeck platform.

**TDP Token Specification:**

Total Supply | Private Seed | Team (Escrow)
:---: | :---: | :---:
200 million | 5% | 95%


### Private seed
TrueDeck was a mere thought when we had started working on the idea. But we had a working concept ready within a couple of weeks. Instead of raising funds through Initial Coin Offering (ICO), we had raised a small amount. With that amount, we built a strong foundation by putting together a great team and started working on our proof-of-concept games.

TrueDeck had undergone a "private seed round" in January 2018. We conducted the private seed round in January 2018. We agreed on giving 10 million TDP (5% of the total supply) with 5 months of locking period. After locking period, tokens were credited to partner wallets.

**Private seed round details:**

When | Tokens | Locking
:---: | :---: | :---:
January 2018 | 10 million TDP | 5 months

In future, TrueDeck will conduct further rounds to raise additional funding when required.

---

# Conclusion
Blockchain technology has started the revolution of disrupting everything about 21st century. It is providing a way to create ideas that was not possible with current technologies. Even though blockchain technology is in its nascent stage, the implementation of the ideas have to start now.

We envision TrueDeck as the unified platform which benefits to every actor involved in online casino industry. Operators, developers and players will witness a new way to gamble which provides the same experience but offers a great level of transparency and access to valuable insights. 

Our future goal is to transform TrueDeck into a Decentralised Autonomous Organization (DAO) that is completely govern and driven by the community. A thriving community will propel the TrueDeck platform to new heights and establishing as a key contributor in reshaping of online casino industry.

We have an ambitious vision but we are taking a lean approach of building the platform the right way. We invite you to be a part of our journey which is going to take online casino industry to a whole new era.
