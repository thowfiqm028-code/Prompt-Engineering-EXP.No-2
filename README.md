EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:

________________________________________ZERO SHOT PROMPTS:
________________________________________
PROMPT:WRITE A WELL STRUCTURED, BEGINNER FRIENDLY ARTICLE ON THE BASICS OF BLOCKCHAIN TECHNOLOY FOR 200 WORD________________________________________

CHATGPT
Basics of Blockchain Technology
Blockchain is a digital technology used to record and store information securely. It is mainly known for powering cryptocurrencies like Bitcoin, but its applications extend far beyond digital money. At its core, blockchain is a distributed digital ledger that records transactions across many computers so that the records cannot be easily changed or tampered with.
A blockchain is made up of blocks that store data. Each block contains a list of transactions, a timestamp, and a unique code called a hash. This hash connects the block to the previous block, forming a continuous chain. Because each block is linked to the one before it, changing information in one block would require changing all the blocks after it, which is extremely difficult. This structure makes blockchain highly secure.
Another important feature of blockchain is decentralization. Instead of being controlled by a single organization, the data is shared across a network of computers called nodes. Every participant in the network has a copy of the ledger, which increases transparency and reduces the risk of fraud.
Blockchain technology also uses consensus mechanisms to verify transactions. These mechanisms ensure that all participants in the network agree on the validity of transactions before they are added to the chain.
Due to its security, transparency, and reliability, blockchain is used in many fields such as finance, supply chain management, healthcare, and digital identity systems.




________________________________________

GEMINI
The Foundation of Trust: Understanding Blockchain
At its simplest, blockchain is a shared, digital ledger that records transactions across a network of computers. Think of it as a Google Doc that everyone can see, but no one can edit or delete once an entry is made. This "unchangeable" nature is what makes the technology revolutionary.
How It Works
Instead of a central bank or company controlling the data, blockchain distributes it. When a new transaction occurs, it is bundled with others into a "block."
Once a block is verified by the network, it is digitally "chained" to the previous block using complex cryptography. This creates a chronological timeline of data that is nearly impossible to hack, as altering one block would require changing every subsequent block in the chain simultaneously across thousands of computers.
Why It Matters
•	Decentralization: No single entity has total control.
•	Transparency: Every participant can view the transaction history.
•	Security: Records are permanent and verifiable.
While often associated with Bitcoin, blockchain's potential reaches far beyond currency—from tracking supply chains to securing medical records. It is the backbone of a new era of digital trust.

________________________________________

CLAUDE 
Blockchain Technology: A Beginner's Guide
What Is Blockchain?
Imagine a notebook that thousands of people share — and once something is written in it, no one can erase or change it. That's essentially what blockchain is: a shared, tamper-proof digital ledger.
How Does It Work?
Data is grouped into "blocks." Each block contains a set of records (like transactions), a timestamp, and a unique code called a hash. Once a block is full, it's sealed and linked to the previous block — forming a chain. This chain is stored across thousands of computers simultaneously, called nodes.
Why Is It Secure?
Because no single person or company controls the chain. If someone tries to alter one block, every block after it would also need to change — across every node in the network. That's practically impossible, making blockchain incredibly secure.
Key Features at a Glance
•	Decentralized — No central authority controls it
•	Transparent — Anyone can verify the data
•	Immutable — Records cannot be altered once added
Real-World Uses
Blockchain powers cryptocurrencies like Bitcoin, but its uses go far beyond. Industries use it for supply chain tracking, healthcare records, voting systems, and smart contracts — self-executing agreements written in code.
The Takeaway
Blockchain is a revolutionary technology that brings trust, transparency, and security to digital transactions — without needing a middleman.
________________________________________

COPILOT
Beginner’s Guide to Blockchain Technology
🌐 Introduction Blockchain is a revolutionary technology that powers cryptocurrencies like Bitcoin, but its uses go far beyond digital money. At its core, blockchain is a system for recording information in a way that makes it secure, transparent, and very difficult to change.
🔑 What is Blockchain? A blockchain is a digital ledger made up of blocks. Each block contains data, a timestamp, and a unique code called a “hash.” Once a block is added to the chain, it cannot be altered without changing every block after it, which makes the system highly secure.
⚙️ How It Works
•	Transactions are grouped into blocks.
•	Each block is linked to the previous one, forming a chain.
•	Computers in the network (called nodes) validate transactions through consensus.
•	Once verified, the block is permanently added to the chain.
💡 Why It Matters Blockchain eliminates the need for middlemen like banks by allowing peer-to-peer transactions. It ensures transparency, reduces fraud, and increases trust in digital interactions.
📌 Applications Beyond Cryptocurrency
•	Supply chain tracking
•	Secure voting systems
•	Healthcare record management
•	Smart contracts in business
✅ Conclusion Blockchain is still evolving, but its potential to reshape industries is enormous. For beginners, understanding its basics—blocks, chains, and decentralization—is the first step toward exploring this exciting technology.

________________________________________

FEW SHOT PROMPTING:
________________________________________PROMPT:
Example 1:
Topic: Basics of Artificial Intelligence
Output:
Artificial Intelligence (AI) refers to the ability of machines to perform tasks that normally require human intelligence. It includes learning, reasoning, and problem-solving. AI is widely used in applications such as virtual assistants, recommendation systems, and autonomous vehicles. Its benefits include automation and improved efficiency, but it also raises ethical and security concerns.

Example 2:
Topic: Basics of Cloud Computing
Output:
Cloud computing is a technology that allows users to store and access data over the internet instead of local computers. It offers services such as storage, servers, and software on demand. Common cloud models include public, private, and hybrid clouds. Cloud computing provides scalability and cost efficiency, though it depends heavily on internet connectivity.

Now generate:
Topic: Basics of Blockchain Technology WITH 200 WORDS

________________________________________

CHATGPT
Basics of Blockchain Technology
Blockchain technology is a system used to store and manage digital information in a secure and transparent way. It works as a distributed digital ledger that records transactions across many computers in a network. Instead of being controlled by a single authority, blockchain operates through a decentralized system where every participant has access to the same data.
A blockchain is made up of units called blocks. Each block contains transaction data, a timestamp, and a unique identifier known as a hash. These blocks are connected in a sequence, forming a chain. If someone tries to change the data in one block, it will affect all the following blocks, making tampering very difficult. This structure increases the security and reliability of the system.
Another key feature of blockchain is transparency. All participants in the network can view the recorded transactions, which helps build trust among users. At the same time, advanced cryptographic techniques protect the identity and data of users.
Blockchain networks also use consensus mechanisms to validate transactions. These mechanisms ensure that all nodes in the network agree before new information is added to the blockchain.
Today, blockchain technology is used in many fields such as cryptocurrencies, supply chain management, healthcare, and digital identity systems, making it an important innovation in modern digital technology.

________________________________________

GEMINI
Gemini said
The Basics of Blockchain Technology
Blockchain is a decentralized, digital ledger technology designed to record transactions across many computers. Unlike a traditional database managed by a single entity (like a bank), a blockchain is maintained by a global network of participants, making it transparent and resistant to tampering.
How the Chain Forms
When data is recorded, it is grouped into a "block." Each block contains a unique cryptographic code called a hash, along with the hash of the previous block. This creates a secure, chronological chain. If someone tries to alter a single block, the hashes no longer match, alerting the entire network to the attempted fraud.
Key Characteristics
•	Decentralization: No central authority or "middleman" is required to validate data.
•	Immutability: Once a transaction is added to the chain, it cannot be deleted or changed.
•	Transparency: Everyone on the network can view the history of transactions.
While most famous for powering cryptocurrencies like Bitcoin, blockchain technology is now used for everything from tracking global supply chains to managing digital identities and securing medical records. It essentially provides a foundation of digital trust in an untrusted environment.

________________________________________

CLAUDE
Basics of Blockchain Technology
Blockchain is a decentralized digital ledger that records transactions across a network of computers in a secure, transparent, and tamper-proof way. Unlike traditional databases controlled by a central authority, blockchain distributes its data across thousands of nodes, meaning no single entity owns or controls the information.
How It Works
Data is bundled into "blocks," each containing a set of transactions, a timestamp, and a unique identifier called a hash. Every new block links to the one before it, forming an unbreakable chain. Once recorded, data cannot be altered without changing every subsequent block — making fraud virtually impossible.
Key Features
•	Decentralization — No central authority governs the network
•	Transparency — Transactions are visible and verifiable by all participants
•	Immutability — Records are permanent and tamper-resistant
•	Security — Cryptographic hashing protects data integrity
Real-World Applications
Blockchain's most famous use is powering cryptocurrencies like Bitcoin and Ethereum. However, its potential extends to supply chain management, healthcare records, digital voting, smart contracts, and identity verification — anywhere trust and transparency matter.
Why It Matters
Blockchain eliminates the need for intermediaries like banks or brokers, reducing costs and increasing efficiency. While still evolving, it is widely regarded as a foundational technology poised to transform industries across the globe — much like the internet did in the 1990s.

________________________________________

COPILOT
Topic: Basics of Blockchain Technology
Blockchain technology is a digital system designed to record and secure information. At its core, it works like a public ledger that stores data in blocks. Each block contains transaction details, a timestamp, and a unique identifier called a hash. Once a block is added to the chain, it is linked to the previous one, forming a continuous sequence. This structure makes it extremely difficult to alter past records, ensuring transparency and security.
The process begins when a transaction occurs. Computers in the network, known as nodes, validate the transaction through a consensus mechanism. After approval, the transaction is grouped into a block and permanently added to the chain. Because the ledger is shared across many computers, no single authority controls it, making blockchain decentralized.
Blockchain is most famous for powering cryptocurrencies like Bitcoin, but its applications extend further. It can be used in supply chain management to track goods, in healthcare to secure patient records, and in business through smart contracts that execute automatically when conditions are met.
In summary, blockchain is a secure, transparent, and decentralized way of recording information. For beginners, understanding blocks, chains, and consensus is the foundation for exploring this transformative technology.

________________________________________

CHAIN OF THOUGHT PROMPTS:
________________________________________PROMPT: EXPLAIN THE BASICS OF BLOCKCHAIN TECHNOLOGY  IN 200 WORDS, GIVE ME A STEP BY STEP EXPLANATION

CHATGPT
Basics of Blockchain Technology (Step-by-Step Explanation)
Blockchain technology is a secure system used to record and store digital transactions. It works as a distributed ledger, meaning the information is shared and maintained by many computers instead of a single central authority. This makes the system transparent and difficult to manipulate.
Step 1: Transaction Initiation
A blockchain process begins when a user initiates a transaction. For example, someone may send digital currency or record information that needs to be stored securely.
Step 2: Transaction Broadcast
The transaction is broadcast to a network of computers called nodes. These nodes are responsible for checking and verifying the transaction.
Step 3: Transaction Verification
The nodes validate the transaction using cryptographic algorithms and predefined rules. This step ensures that the transaction is legitimate and prevents fraud.
Step 4: Block Creation
Once verified, the transaction is grouped with other transactions to form a block. Each block contains transaction data, a timestamp, and a unique code called a hash.
Step 5: Adding the Block to the Chain
The verified block is then linked to the previous block in the chain. This creates a continuous and secure chain of blocks, known as the blockchain.
Step 6: Permanent Record
After the block is added, the transaction becomes permanent and cannot be easily altered, ensuring security and transparency.

________________________________________

GEMINI
Here is the step-by-step process of how it works:
1.	The Request: A user requests a transaction (e.g., sending digital currency or recording a contract).
2.	The Broadcast: This request is sent to a Peer-to-Peer (P2P) network consisting of many individual computers, known as nodes.
3.	Verification: The network of nodes uses specific algorithms to validate the transaction and the user's status.
4.	Block Formation: Once verified, the transaction is combined with other transactions to create a new block of data.
5.	Hashing and Linking: The new block is given a unique cryptographic "fingerprint" (a hash) and the hash of the previous block.
6.	The Chain: The block is added to the existing chain in a permanent, unchangeable timeline.
Why it is Secure
Because each block contains the fingerprint of the one before it, any attempt to change an old record would break the entire chain's math. To hack it, you would have to change the data on more than half the computers in the world simultaneously.

________________________________________

CLAUDE
Blockchain Technology: Step-by-Step Explanation
________________________________________
Step 1: Start With a Transaction Everything begins when someone initiates a transaction — for example, sending cryptocurrency to another person.
________________________________________
Step 2: The Transaction Is Broadcast That transaction is sent out to a peer-to-peer network of computers called nodes, each holding a copy of the entire blockchain.
________________________________________
Step 3: Nodes Validate the Transaction The network's nodes use known algorithms to verify the transaction is legitimate — confirming the sender has sufficient funds and proper authorization.
________________________________________
Step 4: Transaction Is Combined Into a Block Once verified, the transaction is grouped with other validated transactions to form a new block of data.
________________________________________
Step 5: The Block Receives a Hash Each block is assigned a unique cryptographic code called a hash, plus the hash of the previous block — this is what creates the chain.
________________________________________
Step 6: The Block Is Added to the Chain The new block is permanently appended to the existing blockchain. It is now visible to all participants and cannot be altered.
________________________________________
Step 7: Transaction Complete The transaction is now fully recorded, transparent, and tamper-proof — with no bank or middleman involved.
________________________________________
💡 Key Takeaway: Blockchain's power lies in its chain of verified, cryptographically linked blocks — making it one of the most secure and trustless systems ever designed.

________________________________________

COPILOT
Step-by-Step Basics of Blockchain Technology
🌐 Introduction Blockchain is a digital system that securely records transactions. Think of it as a shared notebook that everyone can see but no one can erase. Here’s a simple step-by-step breakdown in about 200 words:
1. Transaction Begins
Someone initiates a transaction, such as sending cryptocurrency or recording data.
2. Data Packaged into a Block
The transaction details are grouped with others into a “block.” Each block contains information, a timestamp, and a unique code called a hash.
3. Verification by the Network
Computers in the blockchain network, called nodes, check if the transaction is valid. This process is known as consensus.
4. Block Added to the Chain
Once verified, the block is permanently linked to the previous block, forming a continuous chain. This makes tampering nearly impossible.
5. Decentralized Storage
The blockchain ledger is stored across many computers worldwide. No single authority controls it, ensuring transparency and security.
6. Applications Beyond Money
Blockchain is not just for Bitcoin. It can track goods in supply chains, secure medical records, enable smart contracts, and even support voting systems.
✅ Conclusion Blockchain is essentially a secure, transparent, and decentralized way of recording information. By understanding blocks, chains, and consensus, beginners can grasp how this technology is reshaping industries.

________________________________________

ROLE BASED PROMPTING:
________________________________________PROMPT:YOU ARE A BLOCKCHAIN EXPERT, GIVE ME AN ARTICLE ABOUT BASICS OF BLOCKCHAIN TECHNOLOGY IN 200 WORDS

________________________________________

CHATGPT
Basics of Blockchain Technology
As a blockchain expert, I can explain that blockchain is a secure, decentralized technology used to record digital transactions in a transparent and reliable manner. Instead of storing data in a single central database, blockchain distributes the information across a network of computers, known as nodes. This decentralized structure reduces the risk of data manipulation and system failure.
At the core of blockchain are blocks, which are units that store transaction data. Each block contains important information such as the transaction details, a timestamp, and a unique digital fingerprint called a hash. These blocks are connected to one another in a chronological order, forming a continuous chain. If someone attempts to change the data in a block, the hash will change, making the tampering immediately noticeable.
Blockchain networks also use consensus mechanisms to verify transactions. These mechanisms ensure that all participating nodes agree that a transaction is valid before it is added to the blockchain. This process increases trust and security within the system.
One of the major advantages of blockchain technology is its transparency and immutability, meaning the stored records cannot be easily altered once they are confirmed.
Today, blockchain is widely used in areas such as cryptocurrencies, supply chain management, finance, healthcare, and digital identity systems, making it a transformative technology in the digital world.

________________________________________

GEMINI
The Architecture of Digital Trust: A Blockchain Overview
As a blockchain expert, I view this technology not just as a buzzword, but as a fundamental shift in how we handle data. At its core, a blockchain is a distributed, immutable ledger that allows for the secure transfer of value or information without a central intermediary.
The Anatomy of a Block
Think of a blockchain as a digital stack of paper. Each "page" is a block containing a list of transactions. To ensure security, every block contains three vital elements:
1.	Data: The actual transaction details.
2.	Hash: A unique digital fingerprint.
3.	Previous Hash: The fingerprint of the block that came before it.
The Consensus Mechanism
The real magic happens through decentralization. Instead of one bank verifying a check, thousands of computers (nodes) across the globe must agree that a transaction is valid. Once the network reaches a consensus, the block is added to the chain. Because each block is mathematically linked to the previous one, altering even a single byte of data would require changing every subsequent block across the entire network—a feat that is computationally near-impossible.
Why This Matters
By removing the "middleman," we gain transparency, security, and efficiency. Whether it's powering DeFi (Decentralized Finance) or ensuring the integrity of a global supply chain, blockchain is the infrastructure for a trustless future

________________________________________

CLAUDE

Blockchain Technology: An Expert's Overview
________________________________________
As a blockchain architect who has worked with distributed systems for over a decade, let me break down this transformative technology in plain terms.
________________________________________
What Is Blockchain, Really?
At its core, blockchain is a distributed ledger technology (DLT) — a database that is simultaneously shared, synchronized, and governed across multiple nodes without any central authority. Think of it as a Google Doc that millions of people can read, but nobody can secretly edit.
________________________________________
The Three Pillars I Always Emphasize
1. Cryptographic Security Every block contains a SHA-256 hash — a unique digital fingerprint. Alter even one character, and the entire hash changes, instantly flagging tampering.
2. Consensus Mechanisms The network agrees on truth through protocols like Proof of Work or Proof of Stake — eliminating the need to trust any single party.
3. Immutability Once data is written on-chain, it is computationally irreversible. This is what makes blockchain ideal for financial records, contracts, and audit trails.
________________________________________
Where I See Real-World Impact
From DeFi (Decentralized Finance) and NFTs to supply chain provenance and healthcare data sovereignty — blockchain is quietly reshaping how industries handle trust, ownership, and transparency.

________________________________________

COPILOT

Basics of Blockchain Technology
As a blockchain expert, let me break down the fundamentals in a clear and concise way.
🔑 Definition Blockchain is a decentralized digital ledger that records transactions across multiple computers. Instead of relying on a single authority, it distributes data across a network, making it secure and transparent.
⚙️ How It Works
1.	Transaction Initiation – A user requests a transaction, such as sending cryptocurrency or recording data.
2.	Block Creation – The transaction is grouped with others into a block, containing details, a timestamp, and a unique hash.
3.	Verification – Network participants (nodes) validate the block using consensus mechanisms like Proof of Work or Proof of Stake.
4.	Chain Linking – Once verified, the block is added to the chain, permanently linked to previous blocks.
5.	Immutable Ledger – Altering past records is nearly impossible without changing every block, ensuring trust and security.
💡 Applications
•	Cryptocurrency: Bitcoin and Ethereum rely on blockchain.
•	Supply Chain: Tracking goods from origin to destination.
•	Healthcare: Securing patient records.
•	Smart Contracts: Automating agreements without intermediaries.
✅ Conclusion Blockchain is more than just cryptocurrency—it’s a transformative technology that ensures transparency, security, and decentralization. Understanding blocks, chains, and consensus is the first step toward appreciating its vast potential across industries.

________________________________________
COMPARISON

Prompting Technique	Best Platform	Accuracy	Coherence	Simplicity	Speed	User Experience	Reason
Zero-Shot Prompting	ChatGPT	High	High	High	Very Fast	Good	Clear explanation with balanced detail
Few-Shot Prompting	Claude	High	Very High	High	Fast	Very Good	Follows example structure very well
Chain-of-Thought	ChatGPT	Very High	Very High	Very High	Moderate	Excellent	Step-by-step explanation makes concepts clearer
Role-Based Prompting	Gemini	High	High	Medium	Fast	Good	More professional and analytical explanation


RESULT:
