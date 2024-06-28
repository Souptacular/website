---
layout: post
title: 'Ethereum Protocol Development Governance and Network Upgrade Coordination'
date: 2020-03-23
category: cryptocurrency, ethereum
tags: [cryptocurrency, ethereum, progpow]
---
This post will discuss how protocol level development decisions are made as well as how Ethereum network upgrades (a.k.a hard forks) are organized. There is a rich history in how Ethereum's decision making processes have developed over time. This article will focus on Eth 1.0 governance and not touch on Ethereum 2.0 governance. This article does not represent the viewpoint of the Ethereum Foundation or any other entity that I am associated with.

## Major Components of Ethereum’s Governance Structure


### Ethereum Improvement Proposals (EIPs)

![EIPs webpage](https://hudsonjameson.com/img/2020/03/eips_page.png)

Martin Becze, an early Ethereum core developer, created the GitHub repository for [Ethereum Improvement Proposals (EIPs)](https://eips.ethereum.org/) on October 2015. The EIP process is based on the [Bitcoin Improvement Proposals (BIPs)](https://github.com/bitcoin/bips) process which is based on the [Python Enhancement Proposals (PEPs)](https://www.python.org/dev/peps/) process. An EIP is a design document providing information to the Ethereum community, or describing a new feature for Ethereum or its processes or environment. The EIP should provide a concise technical specification of the feature and a rationale for the feature. The EIP author is responsible for building consensus within the community and documenting dissenting opinions. 

There are [different types of EIPs](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1.md#eip-types) including core EIPs for low-level protocol changes that affect consensus and require a network upgrade and ERCs for community standards. The most famous EIP is the [ERC-20 token standard](https://eips.ethereum.org/EIPS/eip-20) which is used to create custom tokens on Ethereum.

EIP editors are tasked with reviewing EIPs for technical soundness, correct spelling/grammar, and code style. Martin Becze, Vitalik Buterin, Gavin Wood, and a few others were the original EIP editors from 2015-late 2016. I took over as the primary EIP editor immediately after the Devcon2 Ethereum conference in October 2016 and over time more editors were added/removed. The current EIP editors are myself, Nick Johnson (ENS), Alex Beregszaszi (EWASM/Ethereum Foundation), Casey Detrio (EWASM/Ethereum Foundation), Nick Savers (Community), and Greg Colvin (former Ethereum Foundation). An EIP enters “Draft” status as long as the EIP is correctly formatted and the content makes sense. I like to say that an EIP on how to make a proper peanut butter sandwich can be put in draft status as long as it follows the rules outlined in [EIP-1](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1.md) which is the rulebook for creating an EIP. The process of how an EIP comes to consensus and is declared “Final” status is purposefully left vague to encourage community collaboration around the specifications built and implemented. Just because an EIP is not in “Final” status doesn’t mean that standards defined in the EIP cannot be used in projects. In fact that is the correct path an EIP should go down to garner acceptance.

Starting in January 2020, the EIPIP (EIP Improvement Process) group formed. The goal of this group is for community members to come together in chat rooms, a bi-weekly video conference meeting, and forums, such as the [Fellowship of Ethereum Magicians forum](https://ethereum-magicians.org/), to make plans to improve the EIP process. The bi-weekly meetings are [recorded/uploaded to YouTube and notes are taken](https://github.com/ethereum-cat-herders/EIPIP). Some of the improvements targeted will include how to attract new EIP editors and the way EIP editors become inducted. Other improvements will involve the EIP process itself and how to streamline it.


## Fellowship of Ethereum Magicians

![Fellowship of Ethereum Magicians Logo](https://hudsonjameson.com/img/2020/03/FEM_logo.png)

The Fellowship of Ethereum Magicians (FEM) was founded in February 2018 by Ethereum Foundation community liaison James Pitts and “Ethereum’s Gandalf” Greg Colvin.
It’s mission is [“to nurture community consensus on the technical direction and specification of Ethereum”](https://donations.ethereum-magicians.org/). Some people have described FEM as the IEEE of Ethereum, but it has a much more decentralized, community focused bend to it. It’s [online discussion forum](https://ethereum-magicians.org/) serves as the primary place for discussion around EIPs and technical standards in Ethereum. FEM has gatherings at most major Ethereum events where working groups called “rings” are formed. Anyone in the community can create a ring and organize volunteers to solve projects identified by the ring. You can see a list of the rings on the [FEM forum](https://ethereum-magicians.org/).


## The “All Core Developers” Calls

![All Core Devs call window](https://hudsonjameson.com/img/2020/03/ACD_meetings.png)

Beginning sometime in late 2015, Ethereum co-founder Gavin Wood created the AllCoreDevs Gitter channel to include Ethereum core developers. At the time there were only a handful of Ethereum core developers across a few clients. Martin Becze [organized the first few core developer meetings](https://gitter.im/ethereum/AllCoreDevs/archives/2015/11/29). George Hallam, the PR/communications lead for the Ethereum Foundation 2015-2016, also helped organize a few. In [October 2016](https://github.com/ethereum/pm#previous-meetings) I took over the task of organizing, moderating, and writing notes for the meetings. In 2019, Lane Rettig (SpaceMesh) joined to assist in facilitating meetings and writing notes. Today others, such as Tim Beiko (Consensys/Pegasys) and James Hancock (Ethereum Foundation), are helping with streaming and moderating meetings. Currently the Ethereum Cat Herders funds the core developer meetings notes.

The All Core Devs meeting is a technical meeting intended to bring together various Ethereum teams who play major roles in determining the direction of the protocol. Ethereum client and research teams provide updates to their projects, and discuss various [core EIPs](https://eips.ethereum.org/core/) to improve the protocol.

The attendees of the meeting include low-level protocol developers, client developers, and core Ethereum researchers. Generally every Ethereum client is represented as well as key members of Layer 1 research/scaling teams. Sometimes a non-core developer with particular expertise on a topic is invited on to discuss a specific agenda item. The meetings are bi-weekly on Fridays and are live streamed/recorded on YouTube. You can view the agenda, notes, and videos of previous meetings [at this link](https://github.com/ethereum/pm). You can view upcoming agendas for future meetings [at this link](https://github.com/ethereum/pm/issues).

The All Core Devs meetings are a primary tenet of the governance process of Ethereum. It is at these meetings where details behind network upgrades are decided and improvements to the Ethereum 1.0 stack are planned. As much as possible we try to attain rough consensus on decisions that need to be made and avoid voting. Because we design the meetings to be purely technical in nature, it makes it easier for arguments to be resolved by producing design docs, specs, and implementations to support your argument.


## Ethereum Cat Herders

![Ethereum Cat Herders Logo](https://hudsonjameson.com/img/2020/03/cat_herders_logo.png)

The Ethereum Cat Herders (ECH) group was founded in January 2019 by myself, Lane Rettig (SpaceMesh), and Afri Schoedon (former Parity) because there was a lack of organization and project management in many aspects of the Ethereum ecosystem. [“Our aim is to bring the minimum amount of order that chaos needs to move Ethereum forward”](http://www.ethereumcatherders.com/). In the beginning ECH primarily helped by [funding note taking at All Core Developer meetings](https://github.com/ethereum/pm/tree/master/All%20Core%20Devs%20Meetings) and playing a major role in organizing and fundraising for the [ProgPoW audits](https://medium.com/ethereum-cat-herders/progpow-audit-goals-expectations-75bb902a1f01) requested by the Ethereum core developers. More recently ECH has helped organizations prepare for upcoming network upgrades (hard forks) including Istanbul and Muir Glacier. As the upgrades approached, ECH reached out to exchanges, miners, and infrastructure providers to point them to [blog posts](https://medium.com/ethereum-cat-herders/ethereum-muir-glacier-upgrade-89b8cea5a210) with information and upgrade instructions. ECH releases weekly updates on their [Medium blog](https://medium.com/ethereum-cat-herders) and recently released [a post outlining their accomplishments over the past year](https://medium.com/ethereum-cat-herders/review-2019-the-ethereum-cat-herders-63e4e0315972).


## Network Upgrades

![Muir glacier upgrade image](https://hudsonjameson.com/img/2020/03/network-upgrade.png)

### Determining what goes into a network upgrade

Back when the protocol was young, changes to the Ethereum clients and specification would be quickly decided by a group of under 15 core developers. This worked fine because they were the only experts and figures like Vitalik Buterin and Gavin Wood acted as benevolent dictators of sorts. That is how it is in many early projects and that is okay. In fact it is needed and helps speed up development.

The growth of Ethereum brought with it challenges. Major decisions took longer to debate and more people got involved. That is great! We want contributions and rigor when making changes to such an important technology. Ethereum does not have an on-chain governance mechanism like other blockchain protocols. Major decisions about what goes into an upgrade at the client/protocol level is, at the end of the day, decided by the core developers. It can be argued that Ethereum is operated as a technocracy, but that isn’t the whole story. There are a lot of nuances that make Ethereum’s decision making processes effective.

My opinion is that the Ethereum core developers are altruistic and try their best to listen to community feedback when considering what is included in network upgrades. This is entirely based on personal experience and I may just be a naive optimist when it comes to gauging the situation. The alternatives to our current system, like on-chain governance mechanisms, are not appealing to me as they generally result in plutocracies being formed. We will never reach a perfect model for how decisions should be made in a decentralized manner and as time goes on the platform matures along with the governance processes.

### Improving the process

Any developer who has an idea to improve the network can submit an EIP. Before late 2019 EIPs had a messy process that made it difficult to navigate the path from idea to full implementation into the protocol. After an EIP was created EIPs would take one of several avenues. The following steps would be conducted (in no specific order):

- An EIP would be debated outside of the All Core Devs meeting.
- The EIP would be debated in the All Core Developer meetings.
- A decision would be made to implement the EIP.
- More discussion would happen.
- Test cases would be created
- The code would be fully implemented across clients.

Sometimes an EIP would quickly go from idea to implementation if it was trivial and non-controversial. Other times an EIP would go from idea, to months of debate, to implementation, then more debate, then test cases, then back to debate, then finally making its way into a network upgrade. EIPs with an implementation in a client would get more exposure and acceptance compared to ideas that did not have code behind them. A planned network upgrade that did not involve an emergency situation would bundle a group of EIPs. The image below describes the process I outlined.

In 2019 there was much ideation of process improvements for decision making around network upgrades. We realized that network upgrades would happen very infrequently, deadlines we would make for ourselves would constantly be missed, and we lacked the human resources to handle all of the tasks around planning and executing hard forks. In late 2019 James Hancock was hired to be the hard fork coordinator responsible for helping overhaul the decision making process and make sure we execute on our plans. Iterations of different strategies led to what we are calling the “EIP Centric Model'' of network upgrades. Rather than fumbling around trying to rush EIPs through the process without a set order of operations, EIPs would go through a series of easy to understand steps and network upgrades would be scheduled based on when an EIP is completed. Although this would cause more frequent network upgrades, our processes for communicating with ecosystem players are improving which would help mitigate negative side effects.

![EIP focused network upgrade graphic](https://hudsonjameson.com/img/2020/03/eip_focused_network_upgrades.png)

The diagram above shows the new way EIPs will be moved through the process and eventually end up on mainnet (image courtesy of James Hancock). We began implementing pieces of this process in late 2019 and plan to continue to improve the process into 2020 as we find out what works and what doesn’t.

### Communicating network upgrades

Network upgrades have become both more difficult and less difficult to coordinate. When Ethereum was smaller with less clients and less notoriety, the mining pools, exchanges, and infrastructure providers supporting Ethereum could easily be informed of [network upgrades](https://blog.ethereum.org/2016/02/29/homestead-release/) and [security vulnerabilities](https://blog.ethereum.org/2016/11/25/security-alert-11242016-consensus-bug-geth-v1-4-19-v1-5-2/) via a few public chat channels on Skype and IRC or what many considered (and still consider) to be a definitive source of truth, the [ethereum.org blog](https://blog.ethereum.org/).

The blog is still used to provide [updates about the ecosystem](https://blog.ethereum.org/2020/01/16/eth2-quick-update-no-7/) and [network upgrades](https://blog.ethereum.org/2019/12/23/ethereum-muir-glacier-upgrade-announcement/), but there is a concerted effort, both inside and outside of the Ethereum Foundation, to move away from the ethereum.org blog as the primary information outlet for network upgrade announcements. The Ethereum Cat Herders have been writing blog posts that announce and explain Ethereum network upgrades. It is vital for the future of Ethereum to transfer responsibility for these things from the Ethereum Foundation to the community.

As Ethereum grew and evolved so did the avenues to spread information on important upgrades and security announcements. Between 2015 and 2018 the primary way that major ecosystem players were notified of major announcements was either the blog or via chat channels. I was one of the 4 people between those years who were responsible for notifying groups of important announcements. During these times we would have about 15 chat rooms from Skype, Slack, and Gitter windows open in order to communicate with important ecosystem participants, manually letting them know the latest versions of Ethereum clients to install to stay secure and up to date. Once the Cat Herders were formed in 2019, we started to transfer those responsibilities to 10+ people who would divide the work of contacting different miners, exchanges, and infrastructure providers. This is the way it needs to be in order to better decentralize responsibilities and to not put a few individuals in a position of power that can be abused.
## Where we are today
Bottom line: Although the Ethereum Foundation and figureheads, like Vitalik, played a significant role in Ethereum’s trajectory early on, the community is taking up the torch to decentralize processes. Decision making processes in Ethereum have matured significantly as the network has grown. We have a long way to go, but given the fact that we are about 5 years old as a community, I believe we have done a good job being pragmatic and realizing we cannot build a completely optimal decision making and coordination system overnight.
