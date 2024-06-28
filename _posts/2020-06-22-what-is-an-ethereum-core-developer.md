---
layout: post
title: 'What is an Ethereum core developer?'
date: 2020-06-22
category: cryptocurrency, ethereum
tags: [cryptocurrency, ethereum, core-devs]
---

There has been a lot of debate around what makes someone an Ethereum core developer or what the term even means. I'm intimately involved in day-to-day operations involving Ethereum 1.0 protocol development as a developer liaison for the community and have been operating the Ethereum Core Developer call (a.k.a AllCoreDevs call) every other Friday since late 2016. The following is not definitive and only represents my opinion. Nothing in this blog represents the opinion of any of my employers or the Ethereum Foundation.

## History
Reference to Ethereum's "core team" can be found in [this July 2014 Reddit AMA thread](https://www.reddit.com/r/IAmA/comments/2bjmgb/hi_we_are_the_ethereum_project_team_ask_us/) from the early Ethereum team. In the thread, the Ethereum team added flair to their name that said "Ethereum core team". In late 2015, Ethereum co-founder Gavin Wood created the Gitter channel "AllCoreDevs" where Ethereum core developers would coordinate development of the protocol. It was in this channel that the first Ethereum Core Developer calls were organized. I expand on the history of the "AllCoreDevs" meetings in my previous blog post "[Ethereum Protocol Development Governance and Network Upgrade Coordination](https://hudsonjameson.com/2020-03-23-ethereum-protocol-development-governance-and-network-upgrade-coordination/)".

## Definition
**Ethereum core developers are people who currently provide significant contributions to Ethereum low-level protocol development.** One example of a significant contribution is having multiple code commits to Ethereum software at the layers below the Dapp layer, such as client code. Another example is someone who is writing protocol specifications for Ethereum 2.0. I mention the word "currently" in the definition because core dev isn't a title that you are bestowed and is permanent. If you stop providing contributions then you are considered a former Ethereum core developer. For example: Although Ethereum co-founder Gavin Wood made significant contributions to Ethereum early on, he is no longer considered by anyone to be an Ethereum core developer, bur rather a former Ethereum core developer.

Here is another definition that I wrote years ago that is included in [a repository of Ethereum Core Developer meeting notes](https://github.com/ethereum/pm#who-can-attend) defining who can attend meetings:

> Low-level protocol developers, client developers, and core Ethereum researchers are invited to attend the meetings. Generally, every Ethereum client is represented as well as key members of Layer 1 research/scaling teams. Sometimes a non-core developer with particular expertise on a topic is invited on to discuss a specific agenda item. If you feel you would contribute to the meetings by your attendance please reach out to Hudson Jameson at hudson@ethereum.org.

Since I took over the task of running Ethereum Core Developer meetings, I have been responsible for choosing who can attend core developer meetings. The vast majority of those who have requested an invite to the meeting have received one. Deciding who attends a meeting is a very non-controversial process primarily because the meetings are very boring, so unless you take interest in Ethereum 1.0 protocol changes, you won't want to attend. [Agendas are publicly published](https://github.com/ethereum/pm/issues/180), [meetings are live streamed/recorded to YouTube](https://www.youtube.com/watch?v=c_JmTqeQkU4&feature=youtu.be), and [notes are taken and published](https://github.com/ethereum/pm/blob/master/All%20Core%20Devs%20Meetings/Meeting%2089.md) so there isn't a need for non-core devs to attend the meetings virtually since they can watch on YouTube or read the notes later.

### What about researchers?
Currently there are a number of "technical ecosystem calls", including the Ethereum Core Developer call, Eth 2.0 call, and Stateless Ethereum calls. People sometimes think that Ethereum core devs are only those who attend Ethereum Core Developer calls, but that isn't accurate. Ethereum 2.0 researchers and others performing important research around topics such as beam sync and stateless Ethereum are also core developers in my opinion. I believe Ethereum 2.0 researchers are called "Eth 2 researchers" first and "core developers" second because of the name of the calls and association to them. It's easier to identify core developers and Eth 2.0 researchers by just taking a look at technical ecosystem call attendees rather than commits in a GitHub repository.

## Who decides who is a core dev?
No one. There is not a designated person who decides who is a core developer for Ethereum. It is an emergent process decided primarily by contributions and reputation. This line from Jameson Lopp's excellent blog "[Who Controls Bitcoin Core?](https://blog.lopp.net/who-controls-bitcoin-core-/)" describes what defines a Bitcoin core maintainer:

> Who are the Bitcoin Core maintainers? They are contributors who have built up sufficient social capital within the project by making quality contributions over a period of time.

This definition also applies to Ethereum core developers.

### Can anyone claim to be a core developer?
Technically, no one is stopping anyone from claiming to be a core developer for Ethereum. Anyone is able to contribute to Ethereum protocol development (although their contributions may or may not be accepted). We really haven't had a major problem with "imposter core devs" in the Ethereum community. If it did start to happen, I guess it would be up to the community to call out people. Even so, at the end of the day it is only a title so we shouldn't take it too seriously.

I've seen people ask that someone have the title of core dev stripped away because of their opinions or actions within the community. Since the title is not designated by anyone, the Ethereum community is completely within their right to declare someone to not be a core developer. This would not take away anyone's contributions to the Ethereum protocol and it would not mean that person can no longer attend Core Developer meetings. It would simply demonstrate that the Ethereum community has decided that someone shouldn't be given a title. This hasn't happened yet as far as I can tell.

## Who are the Ethereum core developers/teams?
There are too many people and teams developing across the Ethereum protocol to name them all. Additionally, there are some people who may be working on the protocol layer, but do not want the title or to be called out in a blog post. The beauty of Ethereum client development is that, in both Eth 1.0 and 2.0, there are multiple clients being developed in different languages to provide network redundancy. Clients follow a single specification rather than a single client being the specification that others have to follow. Because I am very involved in the Ethereum 1.0 client development ecosystem, I will list the active Ethereum 1.0 clients. This list does not including other important Eth 1.0 teams and groups, such as the [testing team](https://github.com/ethereum/tests) and the ConsenSys Quilt R&D team.

- [geth](https://github.com/ethereum/go-ethereum) (Go)
- [Nethermind](https://github.com/NethermindEth/nethermind) (.NET Core)
- [OpenEthereum](https://github.com/openethereum/openethereum) (Rust)
- [Trinity](https://github.com/ethereum/trinity) (Python)
- [ethereumJS](https://github.com/ethereumjs/) (JavaScript)
- [Besu](https://github.com/hyperledger/besu) (Java)

## Conclusion
Labels and titles are important, but should not be taken too seriously. Defining a group of people as core developers is helpful to know who to talk to when you have a question about Ethereum protocol layer development. Don't get too hung up on who is or isn't an Ethereum core developer because at the end of the day it is a title granted through reputation based on contributions to Ethereum and you can't take those contributions away.

If you are interested in contributing to Ethereum protocol development please don't hesitate to reach out! I would be happy to connect you to the right people to get you started.
