<h1>Title</h1>

** This file is a work in progress - but wanted to have something to show before my flight home in case I don't have time to update before midnight. **

I will be working on this project on my own.

Throughout this semester, I've been working on a personal project exploring the use of IPFS in preserving digital evidence for open-source and online investigators. There are a few problems that I've identified with the use/implementation of IPFS. One of these problems is that there is no inherent notion of a "creator" for files stored in IPFS. The files shared on the IPFS network can be pinned and redistributed by anyone else on the network. There is no way to guarantee that a file first originated from a specific user, making it difficult to receive context from the source of the page.

What I am hoping to do in this project is explore the idea of human interaction with IPFS. The files stored on IPFS are more or less permanent - the vision of the protocol is to create a permanent, versioned history of the internet. In this project, I will create a way for users to interact with each other and with the protocol in a permanent, versioned manner as well.

In this project, I will create a smart contract for an online community/world that anyone can generate. Users will be allowed to join these worlds, and make posts and replies in a message board style. I also hope to explore other ideas, such as moderation of the community or governance.

All of the data for the project (posts, comments, etc) will be stored on IPFS. The hash for this data will live within the smart contract. I hope to create a front end interface that will take user input and store it on IPFS, and then interact with the smart contract using the hashes it has created for the data. It will be given hashes from the contract and display the data to the user.