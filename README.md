# LancersZK

## Project Description
LancersZK is a first of its kind on-chain freelancing platform that provides a trustless way to tap the talent market with decentralized private payments and verifiable credentials.

## Unique Value Proposition

While many on-chain talent markets focus on identities and credentials, LancersZK has these as basic features AND will be the first to focus on UX and ease of use to a wider userbase.

We make it easy to transact inside the protocol by providing interoperable payments across different chains. And our digital reputation framework preserves privacy in payments, invoicing and encourages anonymous feedback.

All these features work well together to create a reimagined workplace for the on-chain future.

## Problems We're Solving

40% of people lie on their resumes, and three out of four employers have caught a lie on someone's resume. With on-chain actions in LancersZK leaving a digital trail for everyone's skills and activities, people can make sure that user profiles are 
always accurate and truthful.

There is no decentralized job platform that allows for private transactions, and this could basically lead to issues like the whole public seeing how much you earn for a living. LancersZK solves this by enabling private transactions and even private 
job postings.

## How it Works

Freelancer signs up and writes a basic description and skills list to attract potential clients. There is no credentials on his profile yet, because it will only be filled through NFTs issued by verified organizations.

He then applies for 'Quests' by initiating the Waku chat to privately discuss and negotiate the details of the job. The organization funds the escrow before awarding the job to him.

Lancer submits his work by marking the quest completed, which then sends an invoice to the org via Request Network. If approved by the Org, the escrow is released and the platform mints an NFT credential to the Lancer which is then displayed in his 
profile.

## How it's Made
We used the following technologies to build LancersZK:

- **Chainlink CCIP** - Payments to Lancers can be made either through Polygon or Ethereum to make the crypto transactions much more seamless for the users. We are also using CCIP for cross-chain posting of quests so that the Orgs do not have to switch 
chains just to post.

- **Polygon zkEVM** - We are deploying our contracts on Polygon zkEVM for seamless performance, EVM-equivalence, and securing transactions with Ethereum's consensus.

- **Filecoin** - We needed decentralized storage to store files and nft credentials, so we used Filecoin for efficient storage solution. We also leveraged IPFS (InterPlanetary File System) with NFT.storage to ensure fault tolerance and high availability 
for users' files.

- **The Graph Protocol** - we used subgraphs to query reviews for DAOs and Freelancers, and also query projects of freelancers
