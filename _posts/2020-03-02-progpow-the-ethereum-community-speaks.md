---
layout: post
title: 'ProgPoW: The Ethereum Community Speaks'
date: 2020-03-02
category: cryptocurrency, ethereum
tags: [cryptocurrency, ethereum, progpow]
---

Programmatic Proof-of-Work (ProgPoW) has been a topic of contention in the Ethereum community for a long time. This post explains the history of ProgPoW, the various arguments for and against it, and my personal opinion on the topic. I am speaking on behalf of myself, Hudson Jameson, and not on behalf of the Ethereum Foundation or any other entity.

# History

[ProgPoW](https://eips.ethereum.org/EIPS/eip-1057) is "a new Proof-of-Work algorithm to replace Ethash that utilizes almost all parts of commodity GPUs". ProgPoW aims to decrease the economic incentive to build an Application-Specific Integrated Circuit (ASIC); a highly specialized device designed for a specific purpose, in this case, mining Ethereum much more efficiently than traditional GPU mining. ProgPoW is not designed to completely prevent a ProgPoW ASIC from being created, but rather make it expensive to build and not worth it to produce. It was submitted as [a core EIP](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1.md#core-eips) on May 2, 2018, by a semi-anonymous group calling itself [IfDefElse](https://medium.com/@ifdefelse).

## IfDefElse and Kristy-Leigh Minehan

IfDefElse is a group of 3 or more developers who designed and developed ProgPoW. The only public member of IfDefElse is [Kristy-Leigh Minehan (a.k.a OhGodAGirl or Miss If)](https://twitter.com/OhGodAGirl/), who has publicly represented ProgPoW at core dev meetings (along with Dev and Else) and has spoken about ProgPoW on [podcasts](https://medium.com/blockchannel/episode-56-the-prognosis-on-ProgPoW-with-kristy-minehan-48efdd03bc22) and at [Devcon4](https://www.youtube.com/watch?v=pe1pDGDy6iE), Ethereum's largest yearly gathering.

## The EIP Process and Ethereum Core Developer meetings

An [EIP (Ethereum Improvement Proposal)](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1.md#core-eips) is a design document providing information to the Ethereum community, or describing a new feature for Ethereum or its processes or environment. Depending on the type of EIP, a process is defined that brings an EIP from draft status to Accepted/Final status. EIPs that require a consensus change are defined as [Core EIPs](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1.md#eip-types). Core EIPs are discussed and decided on during [Ethereum Core Developer Meetings](https://github.com/ethereum/pm#purpose) that happens every 2 weeks on Fridays. The meetings are live-streamed and published on YouTube, and meeting transcripts are taken. The transcripts and video links can be viewed [here](https://github.com/ethereum/pm/tree/master/All%20Core%20Devs%20Meetings).

My role since late 2016 has been to organize and run the core developer meetings (along with the help of others). I consider myself a liaison between the community and the core developers as well as a communicator whose responsibility it is to make sure both sides are made aware of sentiment from the other side. Over time we have worked to add more roles so we can better organize the process and make it more open. I used to be both the facilitator of the meetings and a hard fork coordinator. We now have a dedicated hard fork coordinator, James Hancock, and the Ethereum Cat Herders who take notes and perform other tasks needed for the meetings to go smoothly.

## ProgPoW and the Ethereum core developer meetings

The earliest mention of ProgPoW I could find in an Ethereum core developer meeting is [meeting #38](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2038.md) which occurred on May 18, 2018. There have been off and on discussions about ProgPoW during core developer meetings since that time. Below I have a list of the 13 meetings where ProgPoW was mentioned.

[#38 - May 18, 2018](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2038.md)

[#45 - August 24, 2018](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2045.md)

[#47 - September 28, 2018](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2047.md)

[#52 - January 4, 2019](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2052.md)

[#53 - January 18, 2019](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2053.md)

[#54 - February 1, 2019](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2054.md)

[#57 - March 15, 2019](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2057.md)

[#62 - May 24, 2019](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2062.md)

[#65 - July 18, 2019](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2065.md)

[#74 - November 1, 2019](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2074.md)

[#77 - December 13, 2019](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2077.md)

[#79 - January 24, 2020](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2079.md)

[#81 - February 21, 2020](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2081.md)

### ProgPoW as a bargaining chip to miners

Back when we were deciding the issuance reduction EIPs at the end of 2018, ProgPoW was brought up often. Some considered it a "bargaining chip" for miners to accept the issuance reduction. Some miners still believe that it was agreed upon that we would put ProgPoW in a network upgrade in exchange for an issuance reduction. In reality, it was decided at the time that we would investigate ProgPoW to the fullest extent possible, but made no promises of implementation. Here is the relevant clip from our discussions at the time: https://youtu.be/mAs3JZHroKM?t=2386

### ProgPoW Accepted

EIP-1 defines the Accepted state of a Core EIP as ["status signals that material changes are unlikely and Ethereum client developers should consider this EIP for inclusion. Their process for deciding whether to encode it into their clients as part of a hard fork is not part of the EIP process"](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1.md#eip-process). This is different from Final status which is when a core EIP has been implemented and deployed on the Ethereum mainnet in a network upgrade.

Sometime around or before December 2018, core developer Martin Swende, along with others, built and deployed the Gangnam testnet which tested how the transition from Ethash to ProgPoW would work, among other insights. It proved to be successful in showing that ProgPoW would not break the network and the code that IfDefElse contributed to the Geth client worked (with some tweaks by the Geth team).

ProgPow was "tentatively accepted pending an audit" during meeting #52 (January 4, 2019). The decision to move forward with ProgPoW was decided by me asking the group if anyone had any opposition to moving forward with ProgPoW and no one speaking up. It's sort of like accepting a proposal by silence, which is not ideal. To be clear, some core devs were in favor of ProgPoW and had been for a long time, so there was no need to reiterate their support at that moment. That is how I feel the silence was justified: ProgPoW was a worn-out subject to discuss. We were only looking for dissenting opinions and otherwise, we would go forward with it. The exact quote from me is:

> So not to get too much in the weeds. It sounds like what we've come to is that we are going to tentatively go-ahead with ProgPoW and by tentatively what we mean is we're going ahead with it unless there's a major problem found within the testing or things of that nature. Is anyone feeling like that's not the case or if there's different feelings? Okay great. Then we will be going forward with ProgPoW.
(From 1:24:59 in the video - https://youtu.be/iSc3TbjZu1k?t=5099)

In a later meeting (#54 - February 1, 2019), it was decided that:

1. The community (via the Ethereum Cat Herders) is conducting a 3rd party audit.
2. Miners should start vote signaling using the extraData field.
3. The Ethereum Cat Herders are going to investigate other ways to help parse community sentiment and help find a way to make a decision.

There was skepticism from some of the core developers that this audit would not quell the concerns from the community and that this would remain a controversial EIP.

At the time this was happening I had personal life events going on, so I did not communicate this to the community as I would normally do through tweets and Reddit. In late March 2019, there was surprise by some community members that these decisions had seemingly been made without alerting the community. I addressed this and some other misconstrued aspects of the ProgPoW debate in [this Reddit post](https://www.reddit.com/r/ethereum/comments/b49c26/clarification_on_the_acceptance_of_ProgPoW_into_a/) that I also posted on Twitter.

### The Ethereum Cat Herders get to work

On [February 1, 2019, during Ethereum Core Developer Meeting #54](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2054.md) it was decided that the [Ethereum Cat Herders](https://twitter.com/ethcatherders?lang=en) would raise funds for and organize an audit for ProgPoW as well as perform community sentiment analysis. The purpose of the audit (which then turned into audits from two separate entities) was to evaluate the hardware claims made by the ProgPoW team as well as look for flaws/negative effects in the ProgPoW software implementation. More details and the result of the sentiment analysis are located [in this Medium article](https://medium.com/ethereum-cat-herders/ProgPoW-audit-goals-expectations-75bb902a1f01).

#### Sentiment analysis from early 2019

Sentiment analysis of the community around ProgPoW was released in late March 2019. Gauging sentiment in a decentralized ecosystem with many different participants is very difficult. For our collection, we chose a few different types of signals to measure: Surveys/interviews, coin voting, and miner voting.

The sentiment collected at the time revealed that there was, arguably, overwhelming support for ProgPoW from those surveyed and those who participated in coin/miner voting. This is a very imperfect sentiment collection. The coin vote revealed 184,528 NO votes vs 2,936,072 YES votes, overwhelmingly in favor of ProgPoW. However, coin votes are susceptible to vote-buying and it is difficult to get community members to participate. Unless I strongly care about ProgPoW, why would I pull my coins out of cold storage? Surveys that were conducted by the Ethereum Cat Herders did not reveal the affiliations of those surveyed so there could have easily been biases. Miner voting was the most telling result of this sentiment collection. 77.2% of miners participated in the polling by indicating their position in the extraData field of mined blocks. Of that 77.2% of miners who decided to participate, 100% of them were pro-ProgPoW. In other words, there was not a single “No” vote in any mined blocks. While the voting has already concluded, some miners are still signaling “Yes”, as shown in this recent block (see “PPYE” in the “extraData” field). There is an argument to be made that it would be stupid for ASICs on the network to vote in this poll because it would reveal that they are ASICs and show what percentage of the hash rate is made up of ASICs.

It is very easy to discount signals that one does not personally agree with on either side of the argument. This is done by pointing out flaws in the signal itself and calling into question it’s legitimacy. Without a social contract to fall back on, resolving disagreements through signaling can become intractable.

#### ProgPoW software and hardware audits

The audits were released in September 2019. The delay in the audit's release was primarily due to issues raising funds. Least Authority, a well known security consulting group in the cryptocurrency space, performed the software audit and the hardware audit was performed by Bob Rao, a distinguished former Intel Fellow responsible for directing the development of advanced analytical tools and methods for microprocessor performance characterization, silicon debug and yield enhancement. The links to the audits are located [here](https://medium.com/ethereum-cat-herders/ProgPoW-audits-released-ed4973ebe073).

The main concern raised by the Least Authority audit was the modified design of the Keccak function in the algorithm. [This Twitter thread elaborates on how it isn't a big deal to the IfDefElse team](https://twitter.com/shemnon/status/1173393400214634496?s=20) and [this Twitter thread](https://twitter.com/panekkkk/status/1231247455804690433?s=20) provides even more context. It is something that may need to be further investigated, but I find IfDefElse's response sufficient and don't consider it an issue. Another finding from the Least Authority audit was that both Ethash and ProgPoW were susceptible to what they called "Light-Evaluation Method Mining Attack". We will talk more about this in the pros and cons section of this article.

### Post audit decisions from the core developers

After the audit was released, the core developers were too preoccupied with the upcoming Istanbul network upgrade to focus on ProgPoW. Others will posit that it was avoided as a topic, and I somewhat agree with that as well. I believe the core developers were tired of talking about it and were waiting for someone to take aggressive action to make a plan to enact it. It should be noted that there was community discussion around ProgPoW at this time, but it was quickly buried within 1-2 weeks by other Ethereum news/events.

During [meeting #74 on November 1, 2019](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2074.md) ProgPoW was brought up again. This time it was in response to a question on whether it was EFI (Eligible for Inclusion) or not. EFI is a state where a Core EIP is decided to be a good idea and given the go ahead by core developers to further investigate, code, and/or fund the EIP. The reason for enacting the EFI process in mid-2019 is for cases where people were worried about spending time and money on an EIP to eventually get a strong no from core developers who could have indicated their dissatisfaction with the idea earlier.

ProgPoW was officially put in EFI state during [meeting #77 on December 13, 2019](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2077.md#eip-1057).

## Recent Developments
The ProgPoW debates were resurrected in February 2020 after it was brought up during meeting [#81 on February 21, 2020](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2081.md). Discussion around the following points was had:

- We have a proposal for a network upgrade for the BLS precompile which would be called Berlin. Then, the next 3rd Wednesday of the following month we would have a fork that includes only ProgPoW. The reason for this is so people who are not in favor of ProgPoW cannot claim that it is being snuck in to a network upgrade with other EIPs (in my opinion). Note that this isn't something that is final and is still up for debate.
- Some people on the core developer call were concerned about community sentiment being anti-ProgPoW.
- In the opinion of myself and hard fork coordinator James Hancock (at the time) the chance of a network fork due to ProgPoW was small.
- We discussed whether or not there is a better venue than Hudson's personal Twitter to spread the news of ProgPoW going live on a specific date. The [Ethereum.org blog](https://blog.ethereum.org/) was brought up as a possibility, but my rebuttal was:

> There are trade-offs to doing that, and when I say that what I mean is: it looks like it's an endorsement by the EF (Ethereum Foundation), which it isn't. The Geth team, though funded by the EF, has autonomy with regards to these types of decisions. No one outside the Geth team influences — or has ever influenced — any decision for what goes into a network upgrade.

- James Hancock endeavored to hear everyone's perspectives and grievances as a part of his role as hard fork coordinator and requested that anyone with opinions come to him.
- It was decided a blog post on the Ethereum.org blog should go out sooner than other network upgrade blog posts have gone out in the past to make sure everyone is aware of the ProgPoW decision.
- I stated the following about inviting prominent ProgPoW detractors to the call:

> Artem makes a good point that we should definitely invite Stefan and Martin K. [from Gnosis/open-ethereum] if they want to come on and give their perspective of why they would like that they're splitting just so people are aware. I'm going to talk to Martin K. just to see what his position is now. I think he knows anyway if he wants to [come on the call], but I don't want to create drama for the sake of drama so I'm avoiding that as much as possible, while still making sure people are aware of what's going on and giving them voice. That's a hard thing to balance and I think James is doing a good job of that and I'm going to try to also do a good job with that.

There have been rabid debates on Twitter and from all angles of the community. There is a draft of ["EIP-2538: Information Position Statement Against Activation of ProgPoW"](https://ethereum-magicians.org/t/eip-2538-informational-position-statement-against-the-activation-of-ProgPoW/4040) which included a list of signatures of those who dissented to ProgPoW's inclusion in Ethereum. There was then [an anonymous letter to the Core Devs from a "committed investor, miner, and supporter of Ethereum" about ProgPoW expressing support for ProgPoW](https://drive.google.com/file/d/14sDp95qcAndrOXSW0NPYaN3EDa-t2FsJ/view).

# Arguments: Pros and cons
I have been collecting arguments for and against ProgPoW, as well as reading the [Kialo ProgPoW discussion site](https://www.kialo.com/ethereum-and-programmatic-proof-of-work-ProgPoW-30878). These arguments do not reflect my personal views, but have been collected to lay out both sides of the discussion as best I can. Notably, I left out anything I believe to be a conspiracy theory.

## Pros

### Motivation (PM#)


**PM1. Ethereum was designed to be ASIC resistant according to the [White Paper](https://github.com/ethereum/wiki/wiki/White-Paper#mining-centralization) and [Yellow Paper (pg. 13-14)](https://ethereum.github.io/yellowpaper/paper.pdf).**

**Rebuttal**: Although ASIC resistance was the original goal of Ethereum times have changed and [it is very difficult to prevent anti-competitive economies of scale from forming around mining](https://pdaian.com/blog/anti-asic-forks-considered-harmful/). Additionally, other algorithms that are less controversial than ProgPoW need to be explored, such as SHA3.

**Rebuttal to the rebuttal**: See Argument CT3.


**PM2. ProgPoW improves Ethereum's decentralization because commodity GPUs from individuals have a chance to mine rather than a few large corporations. It effectively decentralizes hash rate.**

**Rebuttal**: This argument assumes that ASICs will not be sold to the average person, which previous evidence disproves(see the [Antminer E3](https://www.coindesk.com/bitmain-confirms-release-first-ever-ethereum-asic-miners)). **Rebuttal to the rebuttal**: Access to cheap electricity drives the decision to mine and decentralization. The average person paying 13 cents per KWh using an E3 Ethash ASIC is no match to a miner paying 1 cent per KWh with RX580 GPU card.


**PM3. The mining community, made up largely of individual miners/hobbyists, have supported Ethereum since the beginning and their wishes, as indicated by the miner vote, should be respected.**

**Rebuttal**: Miners are service providers who secure the network for a reward. Although they are a part of the community, they should not be the only community stakeholder listened to in this debate. Miners vote can only be counted in hashrate, it is not possible to distinguish between individual miners with low hashrate and one single miner controlling many workers.


**PM4. If ASICs proliferate the network (especially if it is only 1-2 entities) they can perform attacks, such as double-spending. They have this incentive because of the move to PoS.**

**Rebuttal**: The current GPU miners are not provably altruistic so they have the same incentive to disrupt the network. They are profit-motivated and their actions in the ecosystem do not necessarily reflect how they are going to act as Eth 2.0 approaches. Ethereum’s [difficulty bomb](https://www.investopedia.com/news/what-ethereums-difficulty-bomb/) makes it difficult for any miner to disrupt the move to PoS because they would need to fork the chain and remove the bomb to create a profitable chain once the bomb goes off.


**PM5. The identities of the top Ethereum GPU mining pools are known. As ASICs proliferate the network, it will push GPU mining pools out because it will be unprofitable until 1-2 large ASIC entities control most of the network. If a secret ASIC is developed, we will not be able to hold accountable the entity that may attack the network or, at minimum, gain 51% of the has rate to threaten an attack.**

**Rebuttal**: Since the Light-Evaluation Mining Attack is a known exploit in Ethash, ASIC manufacturers have an even playing field as far as being able to produce a performant ASIC. Competition among ASIC companies will ensue, similar to Bitcoin, which isn't a bad thing.

**Rebuttal to the rebuttal**: Memory-hard ASIC's that are able to perform the light-evaluation behavior require the company creating the ASICs to have advanced knowledge of memory controllers or open-source memory controllers, which puts some ASIC companies at an advantage.


**PM6. The current GPU mining pools are supportive of the Eth 2.0 transition and will not attack the network. This is shown by the work Sparkpool has done for the Ethereum community and the work on Eth 2.0 Bitfly/Etherchain has done. If there is an unaccounted for ASIC that secretly takes a large amount of hashing power we are at risk.**

**Rebuttal**: See Rebuttal on PM4.


**PM7. ASICs are very specialized hardware which means that they are subject to licensing and import/export controls and other regulatory hassles by authoritarian governments who may seek to control the mining community or censor transactions on the network.**

**Rebuttal**: There are other means to track mining activity (e.g. electricity bills). Besides, it is a very questionable premise that Ethereum should enable resistance to government regulation.


**PM8. ProgPoW was not controversial when it was introduced. Controversy was directly correlated with certain parties, such as Kristy and IfDefElse, rather than the algorithm itself. This does actually open a threat vector that you can create enough "FUD" to reject a proposal you disagree with.**

**Rebuttal**: There have always been questions about ProgPoW. Governance capture works both ways, so if we allow ProgPoW through we are letting bad actors capture the core developer’s interest and are pushing through a proposal with significant opposition from the community. 

### Technical (PT#)


**PT1. The hardware and software audits both concluded that ProgPoW is a significant improvement over today's Ethash implementation.**

**Rebuttal**: There were a few things pointed out in the audits, including the "Light-Evaluation Mining Attack" referenced in both audits. The audits also concluded that, although ProgPoW would remove ASICs from the network, advances in hardware may make it possible that GPUs/FPGAs can no longer compete with a ProgPoW ASIC.


#### **PT2. The "Light-Evaluation Mining Attack" referenced in both audits needs to be addressed. It allows for a large increase in ASIC efficiency that would effectively push out GPU miners and allow for only a few ASIC companies on the network. This is present in both Ethash and ProgPoW, although it can be fairly easily fixed in ProgPoW.**

**Rebuttal**: If a decision is made that this is something to be concerned about we should assess other mining algorithms that may be more ASIC friendly or less ASIC friendly.


**PT3. ProgPoW has been tested using the Gangnam testnet so it is safe to use on the network.**

**Rebuttal**: There is always a risk deploying a change like this, so we have to evaluate if the risk to the network and reasons we want to implement ProgPoW are sufficient to risk the network losing security by relative hash rate dropping or the network breaking if there is a flaw in ProgPoW.


**PT4. There is a lot of evidence that [secret ASICs on the Monero network made up over 51% of the hash rate until they were forked off](https://blog.sia.tech/the-state-of-cryptocurrency-mining-538004a37f9b). The same could happen to Ethereum, which would put us at the mercy of a few anonymous ASIC manufacturers.**

**Rebuttal**: See CT1, CT2.

## Cons

### Motivation (CM#)


**CM1. The community has been ignored in the past as well as today when discussing ProgPoW. It was stealthily (maliciously or not) pushed through the Core Developer meetings without proper input from the community.**

**Rebuttal**: While it is true that the communication with the non-miner community could have been handled better, it does not negate the fact that the reasoning behind ProgPoW still stands and needs to be acted on. It has been thoroughly discussed on the core developer meetings which is shown in the videos/notes of the meetings and community was gauged appropriately with the resources and signaling systems we had.


**CM2. Since ProgPoW is mostly implemented and tested across multiple clients, it can serve as a deterrent for ASICs to be built at a significant scale.**

**Rebuttal**: ASIC proliferation can go undetected for a long time (see Monero's secret ASIC proliferation) and by the time we realize it we will already be under attack by an unknown actor. It should be implemented in clients, but commented out, to serve as a deterrent.


**CM3. Kicking ASICs off the network is discriminating against certain actors that have so far not proven themselves to not be bad actors in their mining support of the network.**

**Rebuttal**: See PM2, PM4.


**CM4. ASIC resistance makes attacks on cryptocurrencies cheaper, primarily for sophisticated and well-resourced attackers like nation-states. From [Phil Daian's blog post](https://pdaian.com/blog/anti-asic-forks-considered-harmful/):**

**Rebuttal**: Ethereum is currently 3% NiceHash attackable. To be at risk of a NiceHash attack the difficulty would need to reduce 90% or more before that attack is even possible. The likelihood that the network is made up of 90% ASICS is low. We can see this soon with the bricking of the original Antminer E3’s. It should be implemented in clients, but commented out, to serve as a deterrent.

**> General-purpose computer-secured systems are cheaper to attack than specialized systems, as general-purpose hardware can be rented and resold after an attack to substantially subsidize attack cost.  Worse still, an attacker can use general-purpose hardware advantages to overwhelm any cryptocurrency seeking to avoid specialization by carrying attacks across PoW changing / defensive forks, a feature which is not possible with ASICs, where the community has a “nuclear option” available to disable miners at any time if objectively malicious behavior is detected.  These two factors combined severely cripple the economic security of networks secured by general-purpose hardware.**

**Rebuttal**: The threat of large actors like nation-states are not applicable with how small Ethereum, and cryptocurrency in general, still is. They do not pose a big enough threat. Even smaller actors looking to destabilize the network will be stopped by our governance processes.


**CM5. ProgPoW should not be a priority because we need to focus all of our energy on PoS.**

**Rebuttal**: There are very, very little Eth 2.0 developers who have worked on, or even discussed thoroughly, ProgPoW. Eth 1.0 development will eventually merge somewhat with the governance processes and development of Eth 2.0, but as of now, they are separate. Additionally, ProgPoW is nearly implemented in 3 major clients and a custom testnet has been successfully run so there isn't more than a month of work (probably less) to do on it from a development perspective.

**Rebuttal to the rebuttal**: Contentious hard forks not only involve miners, but also Dapp developers and exchanges who will have to pick a side that can end up defeating the very purpose of making the Eth 2.0 upgrade easier.


**CM6. Most of the people behind the development of ProgPoW are anonymous so we do not know their professional affiliations and potential conflicts of interest.**

**Rebuttal**: Many anonymous developers contribute greatly to the Ethereum ecosystem. It shouldn't matter who the developers are if the code is technically sound and has no advantage to particular pieces of hardware.


**CM7. ProgPoW is a contentious issue and would likely result in a network split.**

**Rebuttal**: Arguably, this wasn't contentious until the community felt they weren't heard. People listen to influencers and prominent community members so they are influenced by those loudly proclaiming it is contentious. It has become contentious because people say it is contentious.

### Technical (CT#)


**CT1. It is no longer feasible to create a mining algorithm that is truly ASIC resistant. An ASIC will always be created. ["For any algorithm, there will always be a path that custom hardware engineers can take to beat out general purpose hardware. It’s a fundamental limitation of general purpose hardware"](https://blog.sia.tech/the-state-of-cryptocurrency-mining-538004a37f9b).**

**Rebuttal**: There are coins, such as Ravencoin and Monero, who are experimenting with ways to create ASIC resistant algorithms to stymie ASICs from joining their mining network that are showing success. [RandomX](https://github.com/tevador/RandomX) is an example of this.


**CT2. The fears that were experienced about secret ASICs mining the network and pushing GPUs out have been disproven in the 1.5+ years this has been up for debate.**

**Rebuttal**: The secret ASICs mining on Monero was there for over a year before they were detected. It is entirely possible that we will not notice, just like miners and developers did not immediately notice the ice age block time changes until late 2019.


**CT3. The ["economies of scale" argument](https://pdaian.com/blog/anti-asic-forks-considered-harmful/) dictates that "a proportionate saving in costs gained by an increased level of production." ["Miners have a variety of possible ways to gain “edges” over other miners, using even small differences in profitability at scale to dominate (and eventually purchase, if necessary) their competition, potentially centralizing production in an asymmetry of interest or resources."](https://pdaian.com/blog/anti-asic-forks-considered-harmful/).**

**Rebuttal**: [Phil's blog about economies of scale](https://pdaian.com/blog/anti-asic-forks-considered-harmful/), in addition to [David Vorick's blog](https://blog.sia.tech/the-state-of-cryptocurrency-mining-538004a37f9b) that references economies of scale assume that the PoW coins are going to indefinitely remain PoW. Ethereum switching to Proof-of-Stake in the "near future" would deter ASIC manufacturers from spending the time and money creating a ProgPoW ASIC.


**CT4. The DAG size is approaching 4GB so mining with both AMD GPUs with 4GB of memory and the main Ethash ASICs on the network [won't be able to mine Ether by the end of the year](https://www.reddit.com/r/ethereum/comments/f973yr/this_is_why_the_majority_of_the_e3_asics_will/), and [likely much earlier](https://cointelegraph.com/news/bitmains-antminer-e3-will-allegedly-stop-ethereum-mining-in-1-month-report).**

**Rebuttal**: New ASICs can be created that utilize the Light-Evaluation Mining Attack referenced in PT2 to circumvent this.


**CT5. Nvidia funded and co-designed ProgPoW. They have designed it to run better on Nvidia GPUs to compete with AMD.**

**Rebuttal**: The Nvidia funding/co-design of ProgPoW is unfounded with no solid evidence. Although in earlier versions of ProgPoW there was an advantage to mine using Nvidia GPUs this was somewhat fixed in later versions. The reason AMD vs Nvidia GPUs will not have the same performance is because Nvidia GPUs are better designed and more performant compared to AMD GPUs [in general](https://youtu.be/alhEgNvzv50). [Multiple](https://www.bitsbetrippin.io/blogs/news/cryptocurrency-gpu-card-performance-list-ProgPoW-beam-grin-eth-ubiq-rvn-xmr-bittube) [independent tests were run](https://medium.com/the-capital/comprehensive-ProgPoW-benchmark-715126798476) by the community to confirm this.

# Conclusions (biased, personal perspective)

## Will ProgPoW cause a network split

There has been concern that if ProgPoW is included in a network upgrade that there would be a contentious hard fork, like the one that created Ethereum Classic. I have been seeing a few prominent people on Twitter proclaiming that they would support this fork, or at minimum not run a version of Ethereum that includes ProgPoW. I have also seen prominent Ethereum client developers indicate that they want to avoid a fork. I believe that if a fork were to occur it would be a money grab for those who want to take advantage of having coins on both chains, but that the minority chain would fizzle out quickly. With the prominence and money involved in DeFi and other on-chain protocols it would not be in the interest of anyone to support an Ethereum fork long term over a contentious algorithm update that is primarily rallied against because the community was not properly informed or heard. However, this is still not ideal in any way! I don't want a fork.

## The role of miners in ProgPoW
I believe that GPU miners on Ethereum deserve to be heard and are more than just "service providers" who are just in it for the profit. I have worked extensively with the operators of the top two mining pools on Ethereum, [Ethermine](https://ethermine.org/) and [Sparkpool](https://www.sparkpool.com/en/). Together they currently make up [around 51% of network hash power](https://www.poolwatch.io/coin/ethereum). The [operator of Ethermine](https://bitfly.at/) operates [Ethernodes](https://ethernodes.org/), [etherchain.org](https://www.etherchain.org/), [PoolWatch.io](https://www.poolwatch.io/coin/ethereum), and [beaconcha.in](https://beaconcha.in/). They also have been very active in the core dev community helping us during network upgrades and the Geth/Parity (now open-ethereum) teams improve their clients. Sparkpool has done a lot of work for the community, including being integral in helping the network survive the [Shanghai Attacks before, during, and after Devcon2](https://medium.com/@tjayrush/defeating-the-ethereum-ddos-attacks-d3d773a9a063) and planning on supporting Eth 2.0 [staking services](https://staking.sparkpool.com/). It is impossible to prove that these entities are altruistic, and game theory suggests that they shouldn't be, but I believe that they are and I am confident that they won't attack the network.

## We are a technocracy
The process to come to a consensus on ProgPoW has been messy and not ideal. I believe that we are currently operating primarily under a technocracy since there is not a governance infrastructure in place for the community to voice their decisions without the signals for such decisions being gamed. A technocracy is defined as "the government or control of society or industry by an elite of technical experts". The core developers decide which core EIPs go into a network upgrade and a vast majority of the time the topics discussed and decided on are too technical for most of the community to be involved in deciding. A few notable exceptions to this are The DAO fork and anytime we have implemented issuance reduction. Eric Connor recently made a great post about [this issue as it relates to ProgPoW and his ideas around solutions](https://ethereum-magicians.org/t/stakeholder-group-community-participation-in-ethereum-improvement/4041/3?u=econoar). I don't have the answers on how to solve this, but I hope in time we will get better at governance systems that let as many people as possible have a voice.

## Where does the community stand today?
The early 2019 ECH sentiment collection is no longer valid. It has been nearly a year since that sentiment collection occurred and things have changed. The community has come together to loudly show dissent for reasons listed in my pros/cons list.

## My stance on ProgPoW
I have always been in favor of whatever the community wanted and never had strong opinions on if ProgPoW should be implemented or not. I have misjudged community sentiment at various times and this whole debate is one of those times. The primary reason for ProgPoW having such rabid opposition is because the community did not feel heard in this discussion. There were multiple instances of less than stellar communication from myself, other organizers, and core devs. Each side should of course be heard, however, the fate of ProgPoW should have been, ideally, decided on the merits of complex analysis and not dissent alone. Both need to be considered and in this situation community dissent won. That is not to say ProgPoW is flawless on a technical level, but the audits performed suggest that ProgPoW wouldn’t bring down Ethereum on a technical level. **In my opinion, ProgPoW isn't worth it and is dead based on overwhelming evidence of community dissent.**

The community did its job of making sure they were heard, albeit under less than ideal circumstances that should never have happened in the first place. We need to learn how to create better signaling systems and make sure everyone is heard as best we can.

## Civil discussion is needed

I have talked to people who have been directly harassed due to this debate. I think this is unacceptable and we should denounce this as a community. It doesn't matter if only a few people were "provably harassed" or if the majority of those harassed were on one side of the debate or the other. We need to have productive, civil discourse as we try to solve difficult governance and communication problems. I believe we can do it.

# Special thanks

Special thanks to [Artem Vorotnikov](https://twitter.com/vorot93), [Ben DiFrancesco](https://twitter.com/BenDiFrancesco), [Charles St. Louis](https://twitter.com/CharlieStLouis), [Collin Myers](https://twitter.com/StakeETH), [Edson Ayllon](https://twitter.com/relativeread), [James Hancock](https://twitter.com/JHancock), [Jerome de Tychey](https://twitter.com/jdetychey), [Kristy-Leigh Minehan](https://twitter.com/OhGodAGirl), [Mariano Conti](https://twitter.com/nanexcool), [Pooja Ranjan](https://twitter.com/poojaranjan19), [Samuel Dare](https://twitter.com/DistStateAndMe), and [Tim Beiko](www.twitter.com/timbeiko) for taking the time to review and offer suggestions on this article.

# Interesting links related to ProgPoW or mining
- [Kialo collaborative decision making tool site for ProgPoW](https://www.kialo.com/ethereum-and-programmatic-proof-of-work-ProgPoW-30878).
- ["Takeaways from the ProgPoW Situation"](https://ethereum-magicians.org/t/stakeholder-group-community-participation-in-ethereum-improvement/4041/3?u=econoar) by Eric Connor ([@econoar](https://twitter.com/econoar/status/1232804606842769408?s=20)).
- [Anonymous Letter to the Core Devs from a "committed investor, miner and supporter of Ethereum"" about ProgPoW](https://drive.google.com/file/d/14sDp95qcAndrOXSW0NPYaN3EDa-t2FsJ/view).
- PR for ["EIP-2538: Information Position Statement Against Activation of ProgPoW"](https://ethereum-magicians.org/t/eip-2538-informational-position-statement-against-the-activation-of-ProgPoW/4040) by [Justin Leroux](https://twitter.com/0xMidnight/status/1232766708483526663?s=20).
- "On hostile blockchain takeovers (or Goldfinger attacks revisited)" by [Joseph Bonneau](https://twitter.com/josephbonneau) [[Abstract](http://materials.dagstuhl.de/files/17/17132/17132.JosephBonneau.ExtendedAbstract.pdf) & [Full Paper](https://fc18.ifca.ai/bitcoin/papers/bitcoin18-final17.pdf)].
- ["My stance on progpow"](https://swende.se/blog/Progpow.html) by [Martin Swende](https://twitter.com/mhswende).
- ["Anti-ASIC Forks Considered Harmful"](https://pdaian.com/blog/anti-asic-forks-considered-harmful/) by [Phil Daian](https://twitter.com/phildaian)
- ["The State of Cryptocurrency Mining"](https://blog.sia.tech/the-state-of-cryptocurrency-mining-538004a37f9b) by [David Vorick](https://twitter.com/DavidVorick).
- ["Understanding ProgPoW"](https://medium.com/@ifdefelse/understanding-progpow-performance-and-tuning-d72713898db3) by [IfDefElse](https://medium.com/@ifdefelse).
- ["EIP 1057 (ProgPoW): Open Chip Design for 1% cost/power increase"](https://medium.com/@Linzhi/eip-1057-progpow-open-chip-design-for-only-1-cost-power-increase-eip-1057-progpow-d106d9baa6eb) by [Linzhi ASICs](https://medium.com/@Linzhi).
- [Coindesk articles about ProgPoW](https://www.coindesk.com/tag/progpow).
- ["ProgPoW FAQ"](https://medium.com/@ifdefelse/progpow-faq-6d2dce8b5c8b) by [IfDefElse](https://medium.com/@ifdefelse).
- [“ProgPoW : the never-ending debate”](https://medium.com/@andrea.lanfranchi/progpow-the-never-ending-debate-7e0eadbd1013) by [Andrea Lanfranchi](https://twitter.com/Lanfra68/status/1232728346099884039?s=20).
- [Reddit thread I wrote in Arpil 2018 (pre-ProgPoW) that listed the pros and cons of forking ASICs off of the network. This was shortly after the announcement of Antminer’s E3 ASICs.](https://www.reddit.com/r/ethereum/comments/8bkkv1/asic_resistant_hard_fork_discussion_overview/).
- ["ProgPoW Audit: Goals & Expectations"](https://medium.com/ethereum-cat-herders/ProgPoW-audit-goals-expectations-75bb902a1f01) Medium post by the Ethereum Cat Herders.
- ["ProgPoW Audits Released"](https://medium.com/ethereum-cat-herders/ProgPoW-audits-released-ed4973ebe073) Medium post by the Ethereum Cat Herders.
- [Ethereum Cat Herders ProgPoW Audit repository on GitHub](https://github.com/ethereum-cat-herders/ProgPoW-audit) that contains both the Least Authority audit and Bob Rao's audit.
- [GitHub repository containing](https://github.com/ethereum/pm) the notes/video links of every core developer meeting.
