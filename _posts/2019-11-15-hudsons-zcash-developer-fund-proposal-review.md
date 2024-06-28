---
layout: post
title: Hudson's Zcash Developer Fund Proposal Reviews
date: 2019-11-15
category: cryptocurrency, zcash
tags: [cryptocurrency, zcash]
---

I spent the last two days going over every dev fund proposal and writing my thoughts. I have turned this into a post on the Zcash forums. I'm proud to be a part of the Zcash Foundation Advisory Board and I take this decision very seriously. I hope the community comes together on this.

* [Zcash Forum Post](https://forum.zcashcommunity.com/t/dev-fund-review-of-all-proposals-hudsons-review/35429)
* [Tweet](https://twitter.com/hudsonjameson/status/1195392941193342976?s=20)

**Skip to the bottom for my pick**

## Who am I?

My name is Hudson Jameson and I am a cryptocurrency enthusiast who is involved in both the Ethereum and, to a lesser extent, Zcash community. I work for the Ethereum Foundation in a role for devops and community management. I hold a number of roles in the wider Ethereum ecosystem including EIP (Ethereum Improvement Proposal) Editor, Reddit moderator, Ethereum Cat Herders group co-founder, and core developer liaison responsible for organizing the bi-weekly Ethereum core developer calls. I am on the [Zcash Community Advisory Panel](https://www.zfnd.org/governance/community-advisory-panel/) that will be [polled (for sentiment collection) by the Zcash Foundation regarding NU4 proposals (dev fund proposals)](https://www.zfnd.org/blog/updated-community-sentiment-timeline/). I care about Zcash and it's community. I consider Ethereum and Zcash besties <3

## Pre-Research View

Before I started reviewing the ZIPs and community feedback, I wanted to formulate an opinion based only on what I had read so far and personal opinions. I have read or skimmed the following before I really dug into the ZIPs:

- [James Prestwhich's Opinion Piece](https://docs.google.com/document/d/1eHpO_L7yncGy_K4BslzTzDG1uAE7PSzz2eeM6dqhHEI/edit)

- [Zcash Foundation piece asking for ECC to be non-profit](https://www.zfnd.org/blog/dev-fund-guidance-and-timeline/)

- [ECC response to above piece](https://electriccoin.co/blog/a-blank-slate-the-community-to-decide-its-future/)

Before I read any of the above, I thought the following should happen:
- Cut off rewards to investors and founders

- 20% of the block reward should be split between the ECC and Zcash Foundation because they have both done an excellent job being stewards for Zcash

Once I read Jame's piece I started to question how well the ECC has been managed. I never really personally dug into the logistics of the ECC but had familiarity with their dev work and that they hire top notch folks. After reading the Zcash Foundation article that asks that the ECC become a non-profit I thought that was a neat idea. The ECC response seemed to basically say we need to explore the non-profit route and seemed to attempt to be very politcally nuetral in their messaging in the post.

Where I currently land (I wrote this part around August 2019) before diving into the ZIPs is that the Zcash Foundation should get 20% of the block reward and decide if they want to hire organizations like Parity and the ECC for development. The reasons for this are the following:

- The block reward funding is a unique way to sustain a blockchain protocol's development. The only way to feasibly have one is to launch the blockchain with one. Ethereum recently underwent some block reward funding proposals, but they have faced major disagreements and backlash from community members primarily because there is disagreement of if the money is needed and who decides who gets the money. If you're a blockchain project that starts with a block reward try to retain it.

- There are no other organizations that are non-profit in the Zcash community that have the infrastructure and reputation to handle the funds.

- Stopping the block reward would cause major financial stress to the entities and people who build Zcash. The Ethereum Foundation has a large fund of pre-sale ether and Bitcoin that has allowed them to support the development and education of the Ethereum ecosystem. There isn't a large pre-sale fund that the ECC or Zcash Foundation have.

EDITED 11/18: I gave my "Pre-Research View", but not my "Post-Research View" as far as letting everyone know my thoughts after doing some more research on the areas in the "Pre-Research View" (outside of the ZIPs). I said above that "Once I read Jame's piece I started to question how well the ECC has been managed." Zooko was kind enough to send me [this video](https://www.youtube.com/watch?v=yYFh0CCye58) that gives a great overview of the ECC. I also talked frankly to Zooko about some of the things brought up in Jame's piece and I am comfortable saying that I believe the ECC is being managed well. No organization is perfect, but the level of transparency provided based on the ECC material I have dug into shows that things are growing and successful.

## Overview of ZIPs Arguments (performed November 13-14, 2019)

The following section features some of the arguments I found in ZIPs/discussions and what I think about them.

### [ZIP proposal Keep the block distribution as initaly defined. 90% to miners](https://forum.zcashcommunity.com/t/final-zip-proposal-keep-the-block-distribution-as-initaly-defined-90-to-miners/33843)

This ZIP basically says that the FR should end and miners get 100% of the reward as promised.

I agree that the FR (Founder's Reward) should end. I haven't heard a good argument as to why it should continue. The plan was for the FR to end by this time and it should end. However, the funding situation for Zcash's future is a more complicated topic and I don't think it is sustainable for Zcash to not have some sort of block reward funding for development and other functions of a cryptocurrency.

### [ZIP Proposal - A genuine opt-in protocol level, development donation option](https://forum.zcashcommunity.com/t/final-zip-proposal-genuine-protocol-opt-in-out-donation-feature-updated-02-sept/33846)

This ZIP advocates for an opt-in system where users (miners) decide if they want to donate a portion of their funds (such as mining fees) to ensure the initial promise the ECC made about funding at the start of Zcash is honored.

I don't like this. Businesses such as the ECC and Zcash Foundation cannot create business plans and funding roadmaps that are dependent on unreliable funding. As the price of Zcash fluctuates things will change. Maybe the price will become low enough that miners can no longer afford to donate. In that scenario the entities who are benefitting from the donations will suddenly (and likely constantly) have to read just their funding plans.

### [Dev fund proposal: 20% to any combination of ECC, Zfnd, Parity, or “burn”](https://forum.zcashcommunity.com/t/dev-fund-proposal-20-to-any-combination-of-ecc-zfnd-parity-or-burn/33864)

"This proposal reserves a portion (20%) of the newly minted coins in each block for the dev fund. A fixed set of developer entities would be eligible to receive these funds. The fund would be miner directed in the sense that the miner of each block can determine how to allocate these funds to eligible developers.

During the 2nd halvening period, a fixed portion (DF%=20%) of the newly minted coins in each block are reserved for a Miner Directed Dev Fund (MDDF). A hardcoded set of developer entities (e.g., ECC, Zfnd, Parity, or others), represented in the code their t-address or z-address public keys, are eligible to receive funding from the MDDF. The fund is “miner directed” in the sense that the miner in each block chooses how to allocate the MDDF coins among the developer entities, simply by creating outputs in the coinbase transaction. The DF% is a maximum - miners can also “opt out” by minting a lower number of coins for the MDDF, or none at all.

After the 2nd halvening, the entire block reward in each block is awarded to the miner."

1. From my experience dealing with Ethereum miners upgrading their systems to new versions during network upgrades, I have doubts about the level of miner participation in this proposed system. Many of them will just go with the default settings until it affects their bottom line, at which point they will change it to a setting where they are giving little to no money to a dev fund.

2. As I mentioned in the other opt-in miner proposal, it is difficult for organizations to manage their funding roadmap without guarentees about what they will be taking in funding wise.

3. Although this could be a sort of "training wheels" period where the organizations learn to gather funds from other sources, this adds overhead that slows down other functions those orgs could be performing if they are always worried about fundraising or providing services for funds.

###  [Dev Fund Proposal: 20% split between the ECC and the Foundation](https://forum.zcashcommunity.com/t/dev-fund-proposal-20-split-between-the-ecc-and-the-foundation/33862)

I think this proposal has some strong, positive qualities I agree with. In the "Motivation" section it states:

"Strengths of this proposal:

1. Simple to implement. I would rather developers spend time scaling Zcash rather than implementing the dev funding mechanism.

2. Developers will have several years to work on a great decentralized development funding voting mechanism.

3. 20% is a large enough percentage that there should be enough dev funding for many different Zec price scenarios. To those who want to decrease this percentage: Overpaying for security is a gift to miners, to the detriment of every other stakeholder in the Zcash community. I will even make the strong statement that intentionally overpaying the miners for security is stealing from the other stakeholders.


4. With two entities receiving funds there is no single point of failure."

All 4 points are valid in my opinion. I really like the point that it aims to keep distractions away from the devs and orgs during the 2nd halvening while giving them enough time to really flesh out a proposal. However, once you get to the specification section things get less cool. The "Voting System Requirements" includes the lines "Voting should be private." and "Voting should happen on-chain." I strongly disagree with on-chain voting in general, even with timed lock-ins of ZEC. Too many whales, or organizations like the ECC and Zcash Foundation or any exchange, could anonymously sway the vote and no one would know. This is where transparency trumps privacy.

Once you decide that on-chain private voting based on coin voting is ineffective then you start to think about alternatives. What about transparent voting? That would give away addresses of whales and potentially expose their identity or at least their intentions. What about blacklisting large orgs and exchanges? Is that fair to the organizations and how would this prevent organizations from just mixing their coins using the protocol level tools Zcash provides? What about bribing and the sorts of voting cartels we currently see in EOS and Lisk cryptocurrencies? Going down this rabbit hole does no good for this point in the development of blockchains.

### [ZIP proposal: ZCFS (Zcash Community Funding System)](https://forum.zcashcommunity.com/t/zip-proposal-zcfs-zcash-community-funding-system/33898/)

The specification is basically a modification of the Monero Community Crowdfunding System (CCS) and reminds me somewhat of what Dash does for their on-chain funding mechanism. I think this is a cool idea and if enacted earlier on in the life of Zcash when things were smaller and less was on the line it would be very valuable.

The main issue is that this proposal relies on ZEC holders donating to specific causes which requires a level of participation that I doubt the community would be able to handle. Many people keep their ZEC in cold storage or on exchanges. The exchanges and wallets do not have an incentive to provide this type of governance mechanism as a feature of their wallet/exchange. The only participants would be active miners who care about Zcash and are not just mining whatever algorithm is the most profitable at the time and ZEC holders who can easily access their coins to vote if they run their own client. That is an incredibly small percentage of holders.

If the precedent of crowdfunding was built into the core protocol early on and into all of the mining and client software, I can see this working very well, but at this point we have to be realistic about the level of participation this would attain.

### [Blocktown Development Fund Proposal: 10% to a 2-of-3 multisig with community involved Third Entity](https://forum.zcashcommunity.com/t/blocktown-development-fund-proposal-10-to-a-2-of-3-multisig-with-community-involved-third-entity/34782)

I already have good feels about this proposal because it tries to tackle the financing mechanim as well as the governance mechanism without an opt-in mechanic. In fact it states that "This funding mechanism MUST be hard-coded so that 10% of newly issued ZEC from block rewards are automatically directed to the transparent address(es) of the Zcash Development Fund". The Zcash Foundation, ECC, and a "third entity" would oversee allocating the 10% dev fund to various individuals and entities. A 2-of-3 multisig would be enacted so 2 out of 3 parties must agree on where the funds go. If there is a disagreement between the ECC and Zcash Foundation with how to proceed with a decision the third entity would become involved.

I like that the process for forming the third-party entity are not determined in this proposal beyond the very basics of the governance mechanism. It leaves open the opportunity for more community discussion and formation of the group. At the same time, it leaves open the opportunity for the ECC or Zcash Foundation to abuse the system.

EDIT 11/18: On a [Zcash forum post](https://forum.zcashcommunity.com/t/dev-fund-review-of-all-proposals-hudsons-review/35429/10?u=souptacular) I was alerted to the fact that the "at current ZEC prices the 10% total dev funding in the Blocktown proposal would not allow ECC to continue in their current operations as they are today". I feel awful I missed that point since it is a very important one. I agree that 20% is much better than 10% and would ensure enough funding for all parties who get the block reward.

### [Dev Fund Supplemental Proposal: enforce devfund commitments with legal charter](https://forum.zcashcommunity.com/t/dev-fund-supplemental-proposal-enforce-devfund-commitments-with-legal-charter/34709)

"This proposal does not address the merits, motivations or terms of any particular development funding proposal.

This proposal is supplemental to any Development Fund Proposal which requires or purports to require that the Electric Coin Company (ECC) and/or the Zcash Foundation (ZF) MUST or MUST NOT use development funds in particular ways or MUST or MUST NOT take other related off-chain actions (such requirements, Covenants).

For example, the proposal 20% to a 2-of-3 multisig with community-involved governance provides that “[f]unds accruing to the Zcash Development Fund MUST be used only for … technical work directly connected to the various software implementations of the Zcash protocol.” However, once development funding is approved and implemented via a hardfork, there will be no enforcement mechanism to ensure that the ZF and ECC abide by this requirement."

I think this adds too much legal overhead and fees on something that is less of a problem than it seems. At this time the ECC and Zcash Foundation are mostly trusted entities so we should prioritize if funding should occur and not how to enforce it legally.

### [Kek’s proposal: fund ECC for 2 more years](https://forum.zcashcommunity.com/t/kek-s-proposal-fund-ecc-for-2-more-years/34778)

"continue payouts at current % to ECC (not investors) for 2 extra years with option to vote on extending or ending contract after 2 years

continued funding during these extra 2 years this is a way to kick the can down the road to allow the community to make more informed decisions that don’t feel rushed."

I don't like this proposal because it leaves out the Zcash Foundation and other entities from receiving funding. Kicking the can down the road is not what the community wants as far as I can tell.

### [Dev Fund Proposal: Strategic Council Approach](https://forum.zcashcommunity.com/t/dev-fund-proposal-strategic-council-approach/34801)

This proposal seems like a more mature and detailed version of the community involved "third party entity" mentioned in "Blocktown Development Fund Proposal: 10% to a 2-of-3 multisig with community involved Third Entity". 20% of newly minted coins would be placed in a Developer Fund. "A five-person Strategic Council would be elected by the community every two years. The Strategic Council would determine the high-level strategy, goals, and metrics to evaluate progress for the ecosystem on a six-month cadence. The Strategic Council would be responsible for allocating funding to Executing Entities for the subsequent six months and summarizing the performance of Executing Entities in the prior six months."

This Strategic Council would be paid for their work and seats on the council would not be permanent. This next part seems potentially troubling:

"For the purposes of voting to determine seats (not having seats vote on issues): 1 of the 5 seats should be allocated for miners and signaled through nodes. 1 of the 5 should be ZEC holding weighted so 1 ZEC = 1 vote. 3 of the 5 should be 1 person = 1 vote."

I don't like on-chain weighted votes based on ZEC as I mentioned at previous points in this article. In fact, most of the methods to determine who the seats should be are not fully fleshed out except the miner signaling one. The coin voting one doesn't address all of the flaws coin voting can bring nor does it address how to perform a 1 person = 1 vote identity mechanic.

I've seen an argument that this system is structurally not very distinct from the Zcash Foundation's Board of Directors and that their role can be modified to make them more in line with this proposal. At the same time, having a board that is connected to an entity asking for funding can be problematic and affect the accountability of deliverables as well as create biases on where funds should go.

### [A Grand Compromise/Synthesis ZIP Proposal (Note: The page this is linked to is Josh's latest revision to the proposal.)](https://forum.zcashcommunity.com/t/a-grand-compromise-synthesis-zip-proposal/34812/62)

This looks like a really good proposal because it combines a few of the ideas from previous proposals (thus the name "A Grand Compromise"). 20% of the mining reward would be disbursed between the ECC (30%), the Zcash Foundation (30%), and as a restricted donation for the disbursement through ZF Grants (40%). Josh makes the point that the 2-of-3 multisig approach/third party approach would create a situation where:

"either the ECC or the Zcash Foundation would spend a great deal of their time currying favor in either the process or selection of the party in question in the limited time between now and that party’s selection. Given that the Zcash Foundation is charged with representing community interests, I’m not sure why another community-focused representative would really make sense from the ECC’s perspective — they’d be constantly outvoted if interests clashed, so from a balance of power perspective I’m not sure why the ECC would find that tenable. And I’m not sure the community would want the “third party” to be another profit-generating enterprise, like a VC or another startup, which would tip power another way.".

I like the idea of a trust for carrying out the ZF Grants portion because it "reduce[es] complexity creep in consensus code. Rather than try to incorporate some complex mechanism for dev fund disbursements on-chain, we can meet the NU4 with the simplest possible code-change and spend more time ironing out the details of the trust “off-chain”". The ZF Grant Review Committee makeup is also a good balance because it includes 1 seat for the ECC, 1 seat for the Zcash Foundation, 2 seats that are voted in, and 1 seat that is an elected technical member voted in by the other 4 seats. Additionally, there are a lot of requirements tied to all entities who receive funding from the developer fund.

### [Dev Fund Proposal: Carbon offsetting](https://forum.zcashcommunity.com/t/dev-fund-proposal-carbon-offsetting/34834)

This proposal wants to reward a portion of the developer funding from other proposals towards the offsetting of carbon emissions via donations to carbon offsetting entities elected by the Zcash community. I like novel ideas that help with environmentalism, but at this stage in Zcash's history I think figuring out how to sustain development should be a higher priority.

### [Decentralizing the Dev Fee](https://forum.zcashcommunity.com/t/decentralizing-the-dev-fee/35252)

This proposal lays out some very detailed specifications that I really like. It would be a great proposal I would get behind if:

1. The price of ZEC was higher.

2. Zcash, both the technology and community, was more mature (meaning has existed for a longer amount of time in order to have more experience).

This proposal aims to take Zcash beyond just a Bitcoin clone with privacy by having robust ways to encourage outside development through the dev fund, among other goals they state in the "Requirements" section of their proposal. Here is how the dev fee is divided:

- The Foundation shall receive 25% of the dev fee.
- The remaining 75% of the dev fee shall be distributed between development teams working to maintain clients.
  - One third of the remaining fee (25% of the total) shall be reserved for the role of the “principal developer”, a developer with additional voice in Zcash governance.
  - The remaining two thirds of the fee (50% of the total), called the “outside development fee”, shall be distributed between at least two development teams, chosen semi-annually by the Foundation, coinciding with network upgrades.

The dev fee's given to the Foundation and "principal developer" are governed via a formula making sure they don't receive too much money if the price of ZEC becomes very high. "Prior to each network upgrade, the Foundation shall recommend a list of
addresses and a total number of ZEC per block each address is meant to receive from the dev fee. The recommendation will be “ratified” by the miners as the network upgrade activates."

The idea of a "principal developer" is my main qualm. In the proposal Matt suggests ECC to be the principal developer. The role of the principal developer requires that they focus exclusively on Zcash research and development in exchange for the indefinite fee allocation. The ECC should be allowed to focus on whatever they want as a company because in the event Zcash is unprofitable via a variety of metrics the company could go under. Additionally, Zooko (CEO of the ECC) recently [posted a response on the thread](https://forum.zcashcommunity.com/t/decentralizing-the-dev-fee/35252/83?u=souptacular) saying:

"I’m really not sure if ECC would apply for the job of Principal Developer in this scenario. We will serve Zcash however we are needed, provided that we could be effective. However, I’m not sure we could be effective in the role of Principal Developer as described here.

So if this ZIP were the community’s choice, ECC would support it, in cooperation with Zfnd, with software and with the trademark, as we’ve consistently pledged to do, but we might not apply for the role of Principal Developer...

At the coin price of $40, the Principal Developer would have only $219k/mo to do their work, and they would be prohibited from seeking external funding."

If I was in Zooko's position I would do the exact same thing.

There are other parts of the proposal such as the requirement of bi-weekly dev call for all dev fee recipients and its innovative ways for solving the "crowding out" problem, even if they do not work in Zcash's case. If Zcash were more mature and had another candidate as well qualified as the ECC to be a principal developer candidate I may have a different opinion on this proposal, but if the ECC is out of the running for the Principal Developer position this proposal is a no-go.

### [Dev Fund Proposal: Dev Fund to ECC + Zfnd + Major Grants](https://forum.zcashcommunity.com/t/dev-fund-proposal-dev-fund-to-ecc-zfnd-major-grants/35364)

This proposal is a fork of "Decentralizing the Dev Fee". It is 20% of block rewards split into 3 parts:

- 35% for the Electric Coin Company

- 25% for Zcash Foundation (for internal work and grants)

- 40% for additional “Major Grants” for large-scale long-term projects (decided by the Zcash Foundation, with extra community input and scrutiny)

I'll go ahead and copy/paste the differences between Matt's proposaland this one as listed in the proposal:

- The Dev Fund slice intended for external recipients (beyond ECC, Zfnd and existing Zfnd grants) may be used to fund ECC if no competitive alternatives present themselves, to mitigate unwarranted loss of existing capabilities.

- For simplicity, the above slice is combined with the Foundation’s existing grant system; but is accompanied by explicit requirements to achieve its goals, independent advisory input, and a Restricted Funds mechanism to enforce these requirements.

- The “easing function” coin value cap is removed, in favor of capping each slice at $700k/month funding target. Any excess is kept in a reserve, from which it can be withdrawn only to maintain the funding target in the future.

- Strengthened the transparency and accountability requirements, and harmonized them across ECC, Zfnd and major grantees.

- Removed Zfnd’s supervisory role in determining the “principal developer”, fixing it to be ECC (changing this would be sufficiently dramatic to merit a fork).

- Small differences in prescribed changes to the Zfnd board.

- Call for, and incentivize, development of decentralized voting and governance.

- Clarity and brevity.

I like this proposal more than Matt's and I agree it is an improvement. I would imagine that this may be more palatable to Zooko since the ECC would get more money and be getting guaranteed money.

The "Volatility Reserve" is a great idea:

"Each Dev Fund slice has a Funding Target, initially US $700,000 for each slice. At the end of each calendar month, the fair market value of the Dev Fund ZEC received during that month will be computed, and the excess over the Funding Target will be put into a dedicated Volatility Reserve account by the funds’ recipient."

The transparency and accountability are similar to Matt's proposal which I find acceptable, although it may be a little hard to define some of the broader terms such as "major activity" and "detailed review". Not a huge issue though.

## EDIT 11/18: [ZIP: “Keep It Simple, Zcashers (KISZ): 10% to ECC, 10% to ZFnd”](https://forum.zcashcommunity.com/t/zip-keep-it-simple-zcashers-kisz-10-to-ecc-10-to-zfnd/35425)

This was a last minute proposal that gave 10% of the 20% dev fund block reward to the ECC and the other 10% to the Zcash Foundation. It is very simple (as described in the title) which is nice, but it kicks the can down the road with regards to direct community involvement in how the funds are managed, which I believe is important for a large portion of the Zcash community.

## My Perspective

After reading through all the proposals I have decided which one I will be voting on in the Community Advisory Panel poll.

I'm always in favor of pragmatism over dogmatism. That shapes many of my final opinions after viewing all the official proposals. The reality is that without some sort of funding for major Zcash entities such as the ECC and the Zcash Foundation, I don't see a bright future for Zcash. As Josh Cincinnati puts it in his proposal "A Grand Compromise/Synthesis ZIP Proposal":

"The fundamental assumption is that Zcash won’t thrive without a dev fund. I wish this wasn’t true (I really do), and for the longest time I was against the idea. But I’ve come to fear the alternative without one; I fear the privacy technology pioneered by Zcash may never reach its true potential — not just for our community, but for others interested in novel approaches to private money."

Before people say "This gives the ECC and Zcash Foundation too much power" we need to understand that right now there are only 2 major entities heavily supporting Zcash in the ecosystem because Parity is no longer working on Zebra (the Zcash Foundation is). Most of these proposals would be garbage if any entity other than the ECC and Zcash Foundation were as trustworthy by community standards. Realistically the ECC and Zcash Foundation will be the main 2 entities receiving funds from the proposed Zcash Developer Fund in all of these proposals and that is okay.

This reminds me a lot of the choice the Ethereum community had to make during The DAO hack hard fork in 2016 that caused a chain split creating Ethereum Classic. You can read about the DAO hack in [this article](https://medium.com/@ogucluturk/the-dao-hack-explained-unfortunate-take-off-of-smart-contracts-2bd8c8db3562). Back then Ethereum was young. Many of us came into the Ethereum community following the ideals of immutability at all costs to protect against government censorship and other threats. Then a very large portion of the community’s funds were put at risk and a decision had to be made. Do we stick to our dogma and let the attacker keep the funds or should we be pragmatic and think about the future?

The future could be grim for Ethereum if we let the attacker keep the funds. I think it would have made a lot of community members who lost their investment leave and marred Ethereum as a failed project with most of the ether in circulation at that time going to an unknown bad actor. I think the Ethereum community made the correct decision by choosing pragmatism over "code is law". Promises should be able to be broken when the fate of the project itself hangs in the balance. In the case of Zcash I hope the Zcash community chooses pragmatism and chooses a proposal that allows for funding entities helping build and support Zcash in these early days.

## My Dev Fund Proposal Picks

Here are my top 3 proposals. I will be voting for #1 but want to include #2 and #3 in case you are an Advisory Board member and want other options.

**EDIT 11/18: Here is what I decided to do: rather than picking my top 3 choices, I am eliminating the #2 and #3 choices for simplicity and only including my top choice (it has not changed, but there is additional reasoning).**

#1: [A Grand Compromise/Synthesis ZIP Proposal by Josh Cincinnati (Note: The page this is linked to is Josh's latest revision to the proposal)](https://forum.zcashcommunity.com/t/a-grand-compromise-synthesis-zip-proposal/34812/62)**

This proposal is the most pragmatic in my mind. It gets straight to the point: the ECC and Zcash Foundation are best suited to manage this level of funding, but we still need a third entity/group to keep things in check. The community is still close-knit enough that it would be easier for the major orgs to find community members to fit the ZF Grant Review Committee than to start a third-party entity from scratch or make it more complicated than it has to be.

I highly doubt an organization as well trusted and suitable for managing a large development fund as the Zcash Foundation and the ECC is will form in the next 2 years. Splitting the fund between those two entities would probably happen anyway so why be overzealous in making things compeltely fair and unbiased and perfectly decentralized this early in the game.

So what makes this proposal better than all of the rest? I feel like it strikes a balance between simply giving 10% each to two organizations and pleasing those in the community who want a more specific say in how things happen. The largest piece (40%) of the dev fund would go "to the fund [of] the Zcash Foundation as a RESTRICTED donation purely for disbursement through ZF Grants...". I don't think Zcash wants anyone else leaving the community due to disagreements and this proposal gives power to the community by making an "independent body to both organizations" that can choose to donate to those who most need it.

## EDIT 11/18: A note on ECC's Funding from my perspective
I know there is a lot of fear about the ECC having to wind down if their budget is not met. That is a real concern. The fact that they now have around 30 employees and their quarterly cost [(as described in the Q3 2019 transparency report)](https://electriccoin.co/blog/electric-coin-company-q3-2019-transparency-report/) is well under $1m is really astounding for the level of expertise they have on their team. It would be prudent to donate some of the ZF Grants funds to the ECC in addition to the 30% of the dev fund that the ECC will already receive under this plan. It is important to keep the ECC afloat. It really hurt me to choose a proposal that would potentially put the future of the ECC in jeopardy, but I wanted my choice, above all else, to be reflective of what I felt was best for Zcash according to what the Zcash community wanted and that reflected the values of Zcash.

## Conclusion

Thank you for taking the time to read this and thank you to the Zcash Foundation Advisory Board Members who read this and consider the proposals carefully.

-------------


**EDIT 11/18: My original ordering for propsals is below.**

**NOTE: OLD ORDER - #1: [A Grand Compromise/Synthesis ZIP Proposal by Josh Cincinnati (Note: The page this is linked to is Josh's latest revision to the proposal)](https://forum.zcashcommunity.com/t/a-grand-compromise-synthesis-zip-proposal/34812/62)**

This proposal is the most pragmatic in my mind. It gets straight to the point: the ECC and Zcash Foundation are best suited to manage this level of funding, but we still need a third entity/group to keep things in check. The community is still close-knit enough that it would be easier for the major orgs to find community members to fit the ZF Grant Review Committee than to start a third-party entity from scratch or make it more complicated than it has to be.

I highly doubt an organization as well trusted and suitable for managing a large development fund as the Zcash Foundation and the ECC is will form in the next 2 years. Splitting the fund between those two entities would probably happen anyway so why be overzealous in making things compeltely fair and unbiased and perfectly decentralized this early in the game.

**NOTE: OLD ORDER - #2: [Blocktown Development Fund Proposal: 10% to a 2-of-3 multisig with community involved Third Entity by Blocktown, James Todaro, and Joseph Todaro](https://forum.zcashcommunity.com/t/blocktown-development-fund-proposal-10-to-a-2-of-3-multisig-with-community-involved-third-entity/34782)**

As I said in my #1 choice, this proposal realizes the fact that the Zcash Foundation and the ECC are best suited for managing this funding. It doesn't use on-chain voting mechanisms that would complicate things and leaves the decision on how to create the third-party entity open. I believe that the community could come up with a third-party entity proposal in a matter of months, but that still provides a lot of headaches and potentially a second poll so for that reason it isn't my #1 choice.

**NOTE: OLD ORDER - #3: [Dev Fund Proposal: Dev Fund to ECC + Zfnd + Major Grants by Eran Tromer](https://forum.zcashcommunity.com/t/dev-fund-proposal-dev-fund-to-ecc-zfnd-major-grants/35364)**

A lot of the issues I had with the "[Decentralizing the Dev Fee](https://forum.zcashcommunity.com/t/decentralizing-the-dev-fee/35252)" proposal are fixed in this one. It seems to be a good balance of concerns and takes into account different party’s incentives to participate, including the ECC.

**EDIT 11/18**: I originally said, "The reason it doesn't beat Blocktown's proposal is because I am not sure the exclusivity clause for the principal developer would work for the ECC as they may want the flexibility to mature into an organization beyond specifically Zcash." This statement was inaccurate as there is no "exclusivity clause" in this proposal.

The "strengthened" transparency and accountability requirements, while solid, may be a bit too much for organizations and individuals to keep up with and cause some pressure and inflexibility on the part of the Zcash Foundation.
