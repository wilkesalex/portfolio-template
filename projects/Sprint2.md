---
title: Sprint 2 Project - GCNFT
layout: page
---

## Inspiration
NFT (Non-Fungible Token) is a digital token quite akin to cryptocurrency, but not quite. NFTs are unique due to which they cannot be replicated. Thus, NFTs can be used for trades or exchanges where one needs to ensure that no one else can create fakes.  
  
A very good example of this is when Twitter CEO Jack Dorsey sold his first tweet as an NFT for $2,915,835.47. This highlights the potential of NFTs, and we wanted to create a marketplace for people who want to trade NFTs of Github Commits for various projects.  
## What it does
GCNFT is a proof of concept that a Github Commit NFT marketplace can be built.  Our project is split into 3 bits:  
1. We authenticate the user's Github ID through a Github login. By doing this, we ensure that a user can only put commits and PR's authored by them up for sale.  
2. We generate a hash for the commit/PR and upload it to the IPFS (InterPlanetary File System), which is a distributed peer-to-peer media protocol. We do this because an item must be on a distributed filesystem (like IPFS) in order to have an NFT minted for it.  
3. We generate the unique NFT.
4. We list it on the marketplace.

## How we built it
We used a combination of Blockchain (Flow, IPFS) and webdev (React.js and Nodejs), and tears because of all the bugs we ran into xD  
## Challenges we ran into
All of us are newbies at Blockchain, and two out of the three of us didn't have webdev experience. There was a steep learning curve, but we managed to resolve the bugs.  
## Accomplishments that we're proud of
We were actually able to mint an NFT using the Flow Blockchain. We were able to implement stuff that we'd never even thought of learning in the first place. Working together across time zones and collaborating over discord was really awesome.   
## What we learned
Cross-timezone collaboration and the benefits of coffee. 

In a more technical sense, Blockchain, a bit of crypto, NFTs, React and webdev, how to build backends with node. 
## What's next for GCNFT
Extend the NFT functionality to other item classes and not just Github commits. This can include things like digital art or music.