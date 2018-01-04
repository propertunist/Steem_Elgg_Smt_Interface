# Steem_Elgg_Smt_Interface
An Elgg Plugin To Allow Integration of the Steem Smart Media Token System.

![steemit smt elgg logo](https://i.imgur.com/uEmNHT4.png)

### Overview of Steem, SMTs and ELGG
---
[Elgg](https://www.elgg.org) is a social networking framework written in PHP that allows the creation of a wide variety of websites that require social profiles, social interaction and many related features.  Elgg is in use by NASA as well as several governments, universities, large corporations and many smaller groups/individuals.

[Steem](https://www.steemit.com) is a blockchain technology that rewards posts made on social networking sites with payment in the form of cryptocurrency. Posts are valued subjectively based on upvotes which are weighted according to the amount of currency held by the upvoter in their wallet. Steem operates a Delegated Proof of Stake (DOPS) system and is currently the most efficient cryptocurrency, with the most number of transactions on a daily basis of any cryptocurrency to date.

The Smart Media Token Project from Steemit Inc. ([Whitepaper](https://smt.steem.io/smt-whitepaper.pdf)) is an extension to the Steem blockchain that allows anyone to create their own form of cryptocurrency, backed by Steem and operating on the Steem blockchain. This effectively means that the cutting edge features of Steem can be relatively easily integrated into existing social networks and blogging platforms, monetising posts/comments and incentivising interactions in ways that can be tailored to fit the needs of each unique site that uses them. This overcomes several of the most difficult challenges faced by websites today - namely, the difficulty of receiving financial income from the use of the site, plus motivating new users to visit the site.

#### Functionality Of This Plugin
---
This is a PHP plugin that is intended for use with the Elgg Framework and which allows the SMT functionality produced by Steemit inc. to be integrated seemlessly into existing websites made using Elgg. 

Site Admins can choose to either fully convert their Elgg site to work only on the Steem blockchain, for maximum similarity of their site to existing Steem based services - or they can choose a hybrid system whereby users can elect to send public posts either only to the existing Elgg Database, or to both Elgg and the Steem/SMT blockchain.

In the hybrid mode, end users have the option of electing to have their public blog posts and discussion posts sent for inclusion into the Steem blockchain and to generate payout in the SMT token that the host Elgg site has been configured to use. Non-Public posts cannot be sent to the blockchain since the blockchain is inherently public and encrypted posts to the blockchain would not yield any upvotes from the majority of the network as the Steem system functions at the present time.

Relevant changes are made to Elgg by this plugin to facilitate integration of posts into the Steem blockchain. Additionally new pages/views are added to Elgg to allow posts lists to be filtered in ways that are relevant to the Steem/SMT blockchain technology - such as viewing posts by their post payout levels.

#### Project Status
---
SMTs are due to be launched in early 2018 and at the present time this plugin will not be developed until SMTs are fully active and sufficient coding documentation and resources are available. Should sufficient interest be generated in completing this project as part of an early adoption scheme between Elgg and Steemit Inc. then the release time for this code might be greatly accelerated.

<br /><hr/><em>Posted on <a href="https://utopian.io/utopian-io/@ura-soul/smt-interface-for-elgg-social-networking-framework-initial-concept-and-project-outline">Utopian.io -  Rewarding Open Source Contributors</a></em><hr/>
