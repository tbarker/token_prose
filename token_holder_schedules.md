Preamble
===

This schedule aims to define expectations and potential liabilities arising from participation in the named tokens scheme (the "Token").

It is executed within the context of a wider agreement (the "Master Agreement"), and is not complete without being included in such an agreement. Such a Master Agreement must define the jurisdiction the agreement is intended to be governed under, the arbitration procedure to be used in any dispute, and the obligation of the Sponsor to provide services to the Holders.

The agreements meaning is also determined by a number of sub-schedules, which should be attached to the Master Agreement, but who’s format should follow the examples in this reference agreement.

Prelude
===

These schedules govern the relationship of the Sponsor, or any legal successor of the Sponsor, and any legal or natural person that participates in the token scheme by holding the tokens (the "Token Holder").

There will be an information system (the "Register") which records the ownership of tokens, and is intended to be hosted on a neutral decentralised platform (the "Ledger").

Terms of the Token Holder Schedule
===

1. Tokens in the scheme are bearer instruments, redeemable by their possessor for services delivered by the _Sponsor_ according to the market conditions prevailing at the time.  

2. There is no recourse against the _Sponsor_ for lost keys, or unretrievable tokens.  

3. Only authoritative record to be the _Register_ stored on the ledger at the Location detailed in the _Sub-Schedules_. The means by which the _Holders_ will receive notifications under the _Scheme_ are also defined in the _Sub-Schedules_.  

4. In the event that the Ledger develops into two or more concurrent versions (or forks), the authoritative Ledger will be determined by the Fork Choice rule given in the _Sub-Schedules_.  

5. A new version of the token _Register_ itself might be created by the sponsor. This is a Token Fork, and may be _Forced_ or _Unforced_.  

    1. A Forced fork will be a response to either, a technical failure within the Technology Stack defined in the _Sub-Schedules_, or a judicial order in accordance with governing legal jurisdiction of the _Master Agreement_.  

        1. A technical failure will likely, but need not, be a security flaw which allows mass theft of tokens. In such cases, the _Sponsor_ may choose to revert the distribution of tokens to a point-in-time prior to the failure. Holders accept that they have no recourse against the _Sponsor_ in this case, and that such an event obliges them to ensure the performance of any undertaking who's effect was undone by the _Forced_ fork.  

        2. The Technology Stack encompasses all those components listed in the _Sub-Schedules_, and any which affects the control of 5% or more of the outstanding tokens.  

    2. An _Unforced_ fork is a planned event, undertaken at the discretion of the _Sponsor_ in order to allow improvements to the scheme. The distribution of token ownership will not be altered by an _Unforced_ fork.  

    3. _Holders_ accept that they do not have a claim against the _Sponsor_ for any cost caused by a fork.  

    4. _Holders_ will receive notice of a _Forced_ forked as soon as practicable. _Unforced_ forks will be notified 60 days or more before activation.  

6. The _Sub-Schedules_ may be varied by the _Sponsor_ with 30 days notice to all Parties.  

    1. Such variations may be challenged by any party within the first 20 days. Any challenge must be in accordance with clause 8 of this schedule.  

    2. _Sub-Schedules_ may only be varied within the _Scope of Sub-Schedules_. Any new terms exceeding this scope are void regardless of challenge.  

7. Any software placed upon the Ledger will be considered to be public domain by all Parties.  

8. Parties agree that disputes shall first be put to arbitration within the terms of the _Master Agreement_.  

Scope of Sub-Schedules
===

Notifications
---

The channels by which parties shall be made aware of new information relevant to the scheme, and by which the sponsor can discharge their responsibility to provide such notifications. It should include both on and off ledger notifications.

Location
---

Instructions, or route, through which a party can connect a client of their choice and under their exclusive control, to the ledger, e.g. consensus mechanism, that will be authoritative for this scheme.

Common knowledge to those within the field need not be repeated here, but the intended ledger must be unambiguous.

Fork Choice Rule
---

Under certain circumstances, a distributed ledger might split into one or more concurrently viable alternate instances. The purpose of the fork choice rule is to make it clear, as early as possible, which alternative instance is recognised by the scheme.

It is possible that the _Fork Choice Rule_ will involve an element of human judgement, especially if community values are relevant. In such case, this should be made explicit, and the values or principles laid out in the Master Agreement so that they may be referenced this sub-schedule.

Technology Stack
---

This defines the technology components, both hardware and software, which may be external to the scheme, on which the integrity of the scheme relies and the participants are entitled to depend.

This may be defined both a list of specific components, and as criteria including how common a particular technology is within the scheme's community. Where criteria are used, it is recommended that some mechanism exists where the community can observe which technologies are likely to currently meet the criteria.

Example Sub-Schedules
===

Notifications
---

To be posted at the following on-line locations :-

[https://example.com/notifications](https://instabridge.com/notifications)

https://twitter.com/examplecomtokens

Will also be raised as an on-ledger Notification event originating on the ledger given by the Location Schedule. It is expected that third party software should listen for this event in order to avoid interacting with the Register in an unsupported manner.

Location
---

The Ledger being the Ethereum-based network curated by The Ethereum Foundation. having the network id of 1. The Register consists of the smart contract software located at address `0xdeadbeefdeadbeefdeadbeef` on the specified Register.

Fork Choice Rule
---

The Sponsor intends to consider as the Ledger, the chain which the Ethereum Foundation refers to as Mainnet, even if this would involve a change of network id.

In the event of the Ethereum Foundation being unable to make this decision, for whatever reason, the Sponsor will choose the child fork with the greatest market capitalisation as determined by no less than three widely accepted data sources.

Technology Stack
---

- Ethereum Virtual Machine specification itself  
- The Ethereum client software distributed under the Ethereum Foundation trademark  
- Trust Wallet  
- Truffle Suite  
- Web3j  
- Web3js  
- Ledger Wallet hardware security devices (remote or key generation failures only)  
- Gnosis Multisignature Wallet Contract  
- Android OS releases still supported by Alphabet Inc.  
- iOS releases still supported by Apple in the European market.