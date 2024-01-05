TITLE: Blockchain Based E-Notary Service

TECH STACK:

Node : Used for the backend of the system
React : A frontend library used to make the user interface of the system
Ethereum : Ethereum blockchain used to write the smart contracts for storing the land registry data
Solidity : Solidity language is used to write the smart contracts
Ganache : It is used to set up the blockchain accounts
MetaMask: Free web and mobile crypto wallet that allows users to store and swap cryptocurrencies, interact with the Ethereum blockchain ecosystem, and host a growing array of decentralized applications (dApps)
MongoDB: Used as a file storage system


INTRODUCTION:
A blockchain-based e-notary system is a digital platform that leverages blockchain technology to authenticate and certify electronic documents and transactions. It operates as a decentralized, tamper-proof ledger that records and verifies the authenticity, time-stamping, and integrity of electronic documents, signatures, and other digital assets.
Through cryptographic techniques and consensus algorithms, the system ensures the immutability and traceability of notarized records, enhancing security and trust among involved parties. It offers transparency by creating an indelible audit trail, reducing the risk of fraud or manipulation. This system streamlines the notarization process, making it more efficient, cost-effective, and accessible, while maintaining the legal validity and compliance standards of traditional notary services.

METHODOLOGY:
Design Architecture:
Describe the Ethereum blockchain, its backend (Node.js), its frontend (React), its smart contracts in Solidity, IPFS for file storage, and Ganache for local blockchain development in a thorough system architecture.Create the database structure needed to hold information about land.
Solidity-Based Smart Contract Development:
To handle file storage functions including getFiles, uploadFiles, and verification, create Solidity smart contracts.
Provide features for getFiles, uploadFiles, and IPFS hash linking for document storage.
Configuring Ganache and the Ethereum Blockchain:
For development purposes, set up and launch a local Ethereum blockchain with Ganache. Install the smart contracts on the local blockchain and use ethers.js or web3.js to communicate with them.
Developing Backends with Node.js
Build a backend server with Node.js to manage frontend and backend interactions.Create APIs to manage user authentication, communicate with smart contracts, and perform data processing operations.
Frontend Development with React: 
Utilizing React, create and design the user interface (UI) that allows users to communicate with the land registry system.
Put in place user interface elements for  user authentication, document uploading, admin panel, and details viewing for admins.
Integration with IPFS for Document Storage: 
Integrate IPFS to store files and documents pertaining to legality in an immutable, decentralized manner. 
Provide features for uploading, retrieving, and linking documents to blockchain-stored land records.
Blockchain Account Management with Ganache: 
Create blockchain accounts with Ganache for development and testing needs. 
Provide account management and creation features so users can communicate safely with the blockchain.

EXPERIMENTAL SETUP:
Setup Tools:  Install Node.js, npm, Truffle, Ganache, and React.js for backend, smart contract development, local blockchain, and frontend
SmartContracts: Develop Solidity smart contracts using Truffle, defining files functionalities like getFiles, uploadFiles, and loadWeb3.
Local Blockchain: Configure Ganache, deploy smart contracts, and interact with them using Metamask or an Ethereum wallet for testing.
Backend Development: Create a Node.js server to handle interactions between the frontend and Ethereum blockchain via APIs.
Frontend with React: Develop a user interface using React.js for land registration, viewing details, and document upload.
IPFS Integration: Integrate IPFS for decentralized document storage, enabling upload, retrieval, and association with legalized documents.

PROPOSED SOLUTION: 
Blockchain technology is expected to facilitate the notarization process. With this technology, users can be guaranteed the integrity of data on the chain.
There are three areas of notary services that can be influenced by the implementation of blockchain technology. Using blockchain technology, these provided services cannot directly replace notary services, as stated by the law (at least, not yet), they can only enhance the whole process.
These areas are:
Proof Of Existence : Hashing the document and Storage on the blockchain.
Proof Of Ownership : A given transaction ID retrieves the record from the storage.
Document Ownership Transfer : Just like the transfer of funds between various traditional banks, you can also transfer ownership of documents and deeds on the blockchain with ease.

RESULTS:
The assessment underscores the robust functionality of the blockchain-based e-notary system's outcome analysis. It validates the seamless handling of notarization, ownership transfer, and document storage through well-executed smart contracts. The React.js-powered interface offers remarkable dynamism and user-friendly interactions, facilitating a smooth experience across various functionalities.
Integrating Ganache with the Ethereum blockchain ensures reliable transaction processing and consistent connectivity with blockchain accounts like Metamask. Additionally, the incorporation of IPFS effectively decentralizes document storage, ensuring dependable document retrieval and secure connections with blockchain data.
Despite impressive scalability and consistent response times observed during performance tests, a minor security audit identified and swiftly resolved vulnerabilities in smart contracts and APIs. Recommendations primarily focus on enhancing user feedback mechanisms, optimizing error handling, and exploring integrations, especially for scaling the utilization of Ethereum networks in practical e-notarization implementations.
Ongoing development plans encompass feature enhancements, continuous security evaluations, and performance improvements, aligning with the goal of establishing a robust foundation for a blockchain-based e-notary system.
