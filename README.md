# AltoFuse
Made in Collaboration with Dhruv Takwal https://github.com/dt6120 and Kritik Garg https://github.com/KritikGarg1

## Abstract
We created a complete decentralized Music Platform (Web and App) that will use InterPlanetary File System (IPFS) and Ethereum Blockchain to store the music files of creators and will allow collaboration of various Instrumentalists/vocalists to collaborate and contribute towards the formation of a musical masterpiece that can be listed on the platform as a Non- Fungible Token (ERC 721) available for the public or to be auctioned to a music label or a collector. Our ownership smart-contract protocol will allow multiple contributors to receive their fair share of ownership rights of the music track and will receive funds accordingly.
 
## Problem
2020 turned the music industry upside down when it eliminated live concerts, a significant income stream for artists. In traditional music platforms, the recommendations are controlled by the organizations that get paid by famous artists to selectively recommend the music. The ownership of music is often neglected for smaller artists as they fail to find major labels. Hence, there is a need for a digital platform that will pay them fairly and protect their ownership of the masterpieces along with providing features like collaboration and open auctions. 
Collaborations too are at a downfall. Although many applications permit them the above features, their security remains casual, and as they are centralized, a server shutdown would cease incoming revenue. At the same time, high intermediary costs also crib underrated artists. Considerable artists have no option but to trust an intermediary; an intermediary becomes the owner as it handles all the funds, giving rise to frauds. 
 
## Solution Approach
Since the problems faced by major and minor artists involve ownership issues and currently the ownership given to them isn't considerable. Hence, the idea behind this project was to represent their music with non-fungible tokens (NFT) making them the actual owners. A non-fungible token (NFT) is a unit of data stored on a digital ledger, called a blockchain, that certifies a digital asset to be unique and therefore not interchangeable. NFTs can be used to represent items such as photos, videos, audio, and other types of digital files. Here in this project, NFTs would represent audio files. 
On the ethereum blockchain (used in the project), ERC-721 introduces a standard for NFTs. It provides functionalities like transferring tokens from one account to another, getting the current token balance of an account, getting the owner of a specific token, and also the total supply of the token available on the network. Besides these it also has some other functionalities like to approve that an amount of token from an account can be moved by a third party account.
An artist could collaborate with another, splitting ownership equally between them. As there is no intermediary, underrated artists get more funds and hence are promoted at the same time the transaction process is more secure therefore assuring significant musicians. All this logic is coded through smart contracts which reside on the blockchain, thus providing immutability and security.
All the music files are stored on InterPlanetary File System (IPFS), a distributed system for storing and accessing files, websites, applications, and data. It is a peer-to-peer (p2p) storage network. Content is accessible through peers located anywhere in the world, that might relay information, store it, or do both.
 
## Why blockchain?
Typical centralization in an organization involves decision-making capability in the hands of top management. Hence the organization has to put forth its trust in those few people. Moreover, if someone wants to take over the decisions he just has to attack this particular body and could manipulate data as he wants to. 
A decentralized approach offers several advantages over its centralized counterparts. Each member in the network has a copy of the exact same data in the form of a distributed ledger. If a member’s ledger is altered or corrupted in any way, it will be rejected by the majority of the members in the network. In the blockchain, basically, these distributed ledgers would be nodes all over the world. Each node would have a copy of all the data that has been approved making data immutable.
 
## Technologies used
 - Blockchain (Ethereum)
 - IPFS (InterPlanetary File System)
 - Reactjs
 
## Tech Stack
### Frameworks
- Flutter (cross-platform frontend) 
- Truffle (Ethereum Smart-contracts)
- HardHat (Ethereum Smart-contracts) 
 
### Languages
- Dart (front-end)
- Solidity (smart-contracts)
- Javascript (IPFS)

### Protocol/Standards
- IPFS (InterPlanetary File system) 
- ERC-721 (Ethereum NFT)

## Libraries
- ipfs-http-client
- Mocha and Chai (Testing contracts)

## Blockchain and Wallet
- Ethereum (using Ganache) 
- Matic (now polygon) 
- Metamask (Wallet)
 
 
