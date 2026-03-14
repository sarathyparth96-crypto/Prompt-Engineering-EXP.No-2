EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

AI TOOLS USED IN THE EXPERIMENT ARE: 
         CHATGPT 
         PERPLEXITY 
         CLAUDE 
PROMPTS USED TO COMPARE THESE AI TOOLS ARE: 
         ZERO SHOT PROMPT 
         FEW SHOT PROMPT 
         CHAIN OF THOUGHTS 
         ROLE BASED 
CHATGPT: 
Prompt given for zero shot: 

Summarize this paragraph into 100-150 words: 
“Blockchain technology is a digital system used to record and store 
information in a secure, transparent, and decentralized way. Unlike 
traditional databases that are controlled by a central authority such as a 
bank or organization, blockchain operates on a distributed network of 
computers. These computers, often called nodes, work together to 
maintain and verify a shared record of transactions. Because the data is 
distributed across many systems rather than stored in a single location, 
blockchain reduces the risk of data tampering and increases trust among 
users. The technology first became widely known through 
cryptocurrencies, especially Bitcoin, but today it is being explored for many 
other applications beyond digital currency.A blockchain is made up of a 
series of digital blocks that are connected together in chronological order 
to form a chain. Each block contains transaction data, a timestamp, and a 
unique cryptographic code called a hash. This hash links the current block 
to the previous one, creating a secure chain of records. If someone 
attempts to change the data in a block, the hash will also change, alerting 
the network that tampering has occurred. Because every block is 
connected to the one before it, altering a single block would require 
changing all subsequent blocks across the network, which is extremely 
diAicult.One key feature of blockchain technology is decentralization. 
Instead of a central authority verifying transactions, network participants 
collectively verify them using a process called consensus. Mechanisms 
such as proof of work or proof of stake help confirm that transactions are 
valid before they are added permanently to the blockchain. Blockchain also 
oAers transparency and immutability. All participants can view recorded 
transactions, which increases trust. Once information is added to the 
blockchain, it cannot easily be changed or deleted. This makes the 
technology useful for applications like supply chain tracking, digital identity 
management, and document verification. Another important concept is 
smart contracts. These are self-executing programs stored on the 
blockchain that automatically perform actions when certain conditions are 
met, such as transferring payment after a service is completed. Today, 
blockchain is being explored in industries such as finance, healthcare, 
logistics, and government services. Although it still faces challenges like 
scalability and energy consumption, many experts believe blockchain will 
play a major role in the future of digital systems and data management.” 

ANSWER GIVEN: 

Blockchain technology is a decentralized digital system used to record and 
store transactions securely across a network of computers. Instead of 
relying on a central authority, the data is maintained by multiple nodes that 
verify and update the shared record. Information is stored in blocks, and 
each block is connected to the previous one using cryptographic hashes, 
forming a secure chain of data. This structure makes it very diAicult to alter 
previously recorded information. Blockchain uses consensus mechanisms 
to validate transactions and ensure that all participants agree on the data 
stored in the network. Key features of blockchain include transparency, 
security, and immutability. Although blockchain became popular through 
Bitcoin, it is now used in many fields such as supply chain management, 
digital identity systems, and smart contracts to improve trust, eAiciency, 
and reliability in digital transaction.” 

Prompt given for Few shot: 
Example 1 
Input: 
Artificial Intelligence (AI) refers to the ability of machines to perform tasks 
that normally require human intelligence. It includes learning from data, 
recognizing patterns, and making decisions. AI is used in many fields such 
as healthcare, education, and transportation. 
Output: 
Artificial Intelligence is a technology that enables machines to perform 
tasks that usually require human intelligence. It can learn from data, 
identify patterns, and make decisions. AI is widely used in areas such as 
healthcare, education, and transportation to improve eAiciency and 
accuracy. 

Example 2 
Input: 
Cloud computing is a technology that allows users to store and access 
data over the internet instead of on local computers. It provides services 
such as storage, servers, and software through online platforms. Cloud 
computing helps organizations reduce costs and improve accessibility. 
Output: 
Cloud computing allows users to store and access data through the 
internet rather than using local devices. It provides services like storage, 
servers, and software online. This technology helps businesses reduce 
costs, improve flexibility, and access information from anywhere. 

Now summarize the following text: 
Input Text: 
“Blockchain technology is a digital system used to record and store 
information in a secure, transparent, and decentralized way. Unlike 
traditional databases that are controlled by a central authority such as a 
bank or organization, blockchain operates on a distributed network of 
computers. These computers, often called nodes, work together to 
maintain and verify a shared record of transactions. Because the data is 
distributed across many systems rather than stored in a single location, 
blockchain reduces the risk of data tampering and increases trust among 
users. The technology first became widely known through 
cryptocurrencies, especially Bitcoin, but today it is being explored for 
many other applications beyond digital currency. 
A blockchain is made up of digital blocks connected in chronological order. 
Each block contains transaction data, a timestamp, and a cryptographic 
hash that links it to the previous block. If someone changes the data in a 
block, the hash changes, alerting the network to possible tampering. 
Because all blocks are connected, altering one block would require 
changing all subsequent blocks across the network, which is extremely 
diAicult. Blockchain uses a decentralized verification process called 
consensus, where network participants confirm transactions instead of a 
central authority. Mechanisms such as proof of work or proof of stake help 
validate transactions before they are permanently recorded. Blockchain 
also provides transparency and immutability, meaning records are visible 
to participants and cannot easily be changed. Additionally, blockchain 
supports smart contracts, which are self-executing programs that 
automatically perform actions when certain conditions are met. Today, 
blockchain is used in industries like finance, healthcare, logistics, and 
government services. Although challenges such as scalability and energy 
consumption remain, blockchain is expected to play a significant role in 
future digital systems.” 

Output text: 
Blockchain technology is a decentralized digital system used to securely 
store and record information across a network of computers. Instead of 
relying on a central authority like a bank, multiple computers called nodes 
verify and maintain shared transaction records. Data is stored in blocks 
that are linked together in chronological order using cryptographic hashes, 
forming a secure chain. If any data in a block is changed, the hash also 
changes, alerting the network to possible tampering. Blockchain uses 
consensus mechanisms such as proof of work or proof of stake to validate 
transactions before they are permanently recorded. Key features of 
blockchain include transparency, security, and immutability. The 
technology became widely known through Bitcoin, but it is now used in 
many sectors such as finance, healthcare, logistics, and government 
services. Smart contracts further enhance blockchain by automatically 
executing agreements when specific conditions are met.

Prompt given for chain of thoughts: 
“Blockchain technology is a digital system used to record and store 
information in a secure, transparent, and decentralized way. Unlike 
traditional databases that are controlled by a central authority such as a 
bank or organization, blockchain operates on a distributed network of 
computers. These computers, often called nodes, work together to 
maintain and verify a shared record of transactions. Because the data is 
distributed across many systems rather than stored in a single location, 
blockchain reduces the risk of data tampering and increases trust among 
users. The technology first became widely known through 
cryptocurrencies, especially Bitcoin, but today it is being explored for 
many other applications beyond digital currency. A blockchain is made up 
of a series of digital blocks that are connected together in chronological 
order to form a chain. Each block contains a set of transaction data, a 
timestamp, and a unique cryptographic code called a hash. This hash links 
the current block to the previous one, creating a secure chain of records. If 
someone attempts to change the data in a block, the hash will also change, 
which alerts the network that tampering has occurred. Because every 
block is connected to the one before it, altering a single block would 
require changing all subsequent blocks in the chain across many 
computers in the network. This process is extremely diAicult, which makes 
blockchain highly secure and reliable.One of the key features of blockchain 
technology is decentralization. In traditional systems, a central authority 
controls the database and verifies transactions. In blockchain systems, 
however, transaction verification is carried out collectively by the network 
participants through a process called consensus. DiAerent blockchain 
systems use diAerent consensus mechanisms, such as proof of work or 
proof of stake, to confirm that transactions are valid. Once verified, the 
transaction is added to a block and permanently recorded on the 
blockchain. This decentralized approach eliminates the need for 
intermediaries and can reduce costs and processing time. Blockchain 
technology also provides transparency and immutability. Transparency 
means that all participants in the network can view the recorded 
transactions, which helps build trust among users. Immutability means 
that once information is recorded on the blockchain, it cannot easily be 
changed or deleted. These features make blockchain useful in situations 
where secure and verifiable records are required. For example, 
organizations can use blockchain to track supply chains, manage digital 
identities, or verify important documents. Another important concept 
related to blockchain is smart contracts. Smart contracts are self
executing programs stored on the blockchain that automatically carry out 
actions when specific conditions are met. For instance, a smart contract 
could automatically transfer payment once a service has been completed. 
This reduces the need for manual processing and ensures that agreements 
are executed exactly as programmed. Today, blockchain technology is 
being explored in many industries, including finance, healthcare, logistics, 
and government services. It has the potential to improve security, 
eAiciency, and transparency in digital transactions. Although the 
technology is still evolving and faces challenges such as scalability and 
energy consumption, many experts believe that blockchain will play an 
important role in the future of digital systems and data management.” 

Answer given: 
Blockchain technology is a decentralized digital system used to securely 
record and store transactions across a network of computers. Instead of 
relying on a central authority, multiple computers called nodes verify and 
maintain shared transaction records. Information is stored in blocks that 
are connected in chronological order to form a chain. Each block contains 
transaction data, a timestamp, and a cryptographic hash that links it to the 
previous block, making the system secure and diAicult to modify. 
Blockchain uses consensus mechanisms such as proof of work or proof of 
stake to validate transactions before they are permanently recorded. Key 
features of blockchain include decentralization, transparency, and 
immutability. The technology became widely known through Bitcoin, but it 
is also used in many areas such as supply chain management, digital 
identity verification, smart contracts, and other industries to improve 
security and eAiciency. 

Prompt given for role based: 
Role: You are a technology educator explaining complex topics to 
undergraduate students. 

Task: Read the given passage and summarize it in 100–150 words using 
simple and clear language. Focus on the main ideas of blockchain, how 
it works, its key features, and its applications. 
Input text: 
“Blockchain technology is a digital system used to record and store 
information in a secure, transparent, and decentralized way. Unlike 
traditional databases that are controlled by a central authority such as a 
bank or organization, blockchain operates on a distributed network of 
computers. These computers, often called nodes, work together to 
maintain and verify a shared record of transactions. Because the data is 
distributed across many systems rather than stored in a single location, 
blockchain reduces the risk of data tampering and increases trust among 
users. The technology first became widely known through 
cryptocurrencies, especially Bitcoin, but today it is being explored for 
many other applications beyond digital currency. A blockchain is made up 
of a series of digital blocks that are connected together in chronological 
order to form a chain. Each block contains a set of transaction data, a 
timestamp, and a unique cryptographic code called a hash. This hash links 
the current block to the previous one, creating a secure chain of records. If 
someone attempts to change the data in a block, the hash will also change, 
which alerts the network that tampering has occurred. Because every 
block is connected to the one before it, altering a single block would 
require changing all subsequent blocks in the chain across many 
computers in the network. This process is extremely diAicult, which makes 
blockchain highly secure and reliable. One of the key features of 
blockchain technology is decentralization. In traditional systems, a central 
authority controls the database and verifies transactions. In blockchain 
systems, however, transaction verification is carried out collectively by the 
network participants through a process called consensus. DiAerent 
blockchain systems use diAerent consensus mechanisms, such as proof 
of work or proof of stake, to confirm that transactions are valid. Once 
verified, the transaction is added to a block and permanently recorded on 
the blockchain. This decentralized approach eliminates the need for 
intermediaries and can reduce costs and processing time. Blockchain 
technology also provides transparency and immutability. Transparency 
means that all participants in the network can view the recorded 
transactions, which helps build trust among users. Immutability means 
that once information is recorded on the blockchain, it cannot easily be 
changed or deleted. These features make blockchain useful in situations 
where secure and verifiable records are required. For example, 
organizations can use blockchain to track supply chains, manage digital 
identities, or verify important documents. Another important concept 
related to blockchain is smart contracts. Smart contracts are self
executing programs stored on the blockchain that automatically carry out 
actions when specific conditions are met. For instance, a smart contract 
could automatically transfer payment once a service has been completed. 
This reduces the need for manual processing and ensures that agreements 
are executed exactly as programmed. Today, blockchain technology is 
being explored in many industries, including finance, healthcare, logistics, 
and government services. It has the potential to improve security, 
eAiciency, and transparency in digital transactions. Although the 
technology is still evolving and faces challenges such as scalability and 
energy consumption, many experts believe that blockchain will play an 
important role in the future of digital systems and data management.” 

Summary (100–150 words) 

Blockchain technology is a decentralized digital system used to securely 
record and store information across a network of computers. Instead of 
relying on a central authority like a bank, multiple computers called node 
verify and maintain transaction records. Data is stored in blocks that are 
linked together in chronological order, forming a chain secured by 
cryptographic hashes. If someone tries to change the data in a block, the 
network can easily detect the alteration, making blockchain highly secure 
and reliable. Transactions are verified through consensus mechanisms 
such as proof of work or proof of stake. Key features of blockchain include 
decentralization, transparency, and immutability. The technology became 
widely known through Bitcoin, but it is also used in areas like supply chain 
management, digital identity verification, and smart contracts to improve 
trust, eAiciency, and security in digital systems.

PERPLEXITY: 

Prompt given for zero shot :

Input text: 
Summarize this para into 100-150 words: 
“"Blockchain technology is a digital system used to record and store 
information in a secure, transparent, and decentralized way. Unlike 
traditional databases that are controlled by a central authority such as a 
bank or organization, blockchain operates on a distributed network of 
computers. These computers, often called nodes, work together to 
maintain and verify a shared record of transactions. Because the data is 
distributed across many systems rather than stored in a single location, 
blockchain reduces the risk of data tampering and increases trust among 
users. The technology first became widely known through 
cryptocurrencies, especially Bitcoin, but today it is being explored for many 
other applications beyond digital currency. A blockchain is made up of a 
series of digital blocks that are connected together in chronological order 
to form a chain. Each block contains a set of transaction data, a 
timestamp, and a unique cryptographic code called a hash. This hash links 
the current block to the previous one, creating a secure chain of records. If 
someone attempts to change the data in a block, the hash will also change, 
which alerts the network that tampering has occurred. Because every 
block is connected to the one before it, altering a single block would 
require changing all subsequent blocks in the chain across many 
computers in the network. This process is extremely diAicult, which makes 
blockchain highly secure and reliable. One of the key features of 
blockchain technology is decentralization. In traditional systems, a central 
authority controls the database and verifies transactions. In blockchain 
systems, however, transaction verification is carried out collectively by the 
network participants through a process called consensus. DiAerent 
blockchain systems use diAerent consensus mechanisms, such as proof 
of work or proof of stake, to confirm that transactions are valid. Once 
verified, the transaction is added to a block and permanently recorded on 
the blockchain. This decentralized approach eliminates the need for 
intermediaries and can reduce costs and processing time. Blockchain 
technology also provides transparency and immutability. Transparency 
means that all participants in the network can view the recorded 
transactions, which helps build trust among users. Immutability means 
that once information is recorded on the blockchain, it cannot easily be 
changed or deleted. These features make blockchain useful in situations 
where secure and verifiable records are required. For example, 
organizations can use blockchain to track supply chains, manage digital 
identities, or verify important documents. Another important concept 
related to blockchain is smart contracts. Smart contracts are self
executing programs stored on the blockchain that automatically carry out 
actions when specific conditions are met. For instance, a smart contract 
could automatically transfer payment once a service has been completed. 
This reduces the need for manual processing and ensures that agreements 
are executed exactly as programmed. Today, blockchain technology is 
being explored in many industries, including finance, healthcare, logistics, 
and government services. It has the potential to improve security, 
eAiciency, and transparency in digital transactions. Although the 
technology is still evolving and faces challenges such as scalability and 
energy consumption, many experts believe that blockchain will play an 
important role in the future of digital systems and data management. "

Output text: 
Blockchain technology is a secure, transparent, decentralized digital ledger 
that records transactions across a network of computers (nodes), unlike 
centralized databases controlled by single authorities. Data is stored in 
chronologically linked blocks, each containing transactions, a timestamp, 
and a unique hash that connects it to the previous block. Altering any block 
changes its hash, breaking the chain and alerting the network—making 
tampering nearly impossible. Key features include decentralization via 
consensus mechanisms (e.g., proof-of-work or proof-of-stake) for 
transaction verification, eliminating intermediaries; transparency for all 
participants to view records; and immutability to prevent changes. Smart 
contracts enable self-executing agreements that automate actions when 
conditions are met. Initially popularized by Bitcoin, blockchain now spans 
f
inance, healthcare, logistics, and more, enhancing security and eAiciency 
despite challenges like scalability and energy use.  (128 words) 

Prompt given for Few shot: 
"Summarize the given passage into 100–150 words using simple language 
suitable for undergraduate students. 
Below are examples of how the summary should look. 
Example 1 
Input: 
Artificial Intelligence (AI) refers to the ability of machines to perform tasks 
that normally require human intelligence. It includes learning from data, 
recognizing patterns, and making decisions. AI is used in many fields such 
as healthcare, education, and transportation. 
Output: 
Artificial Intelligence is a technology that enables machines to perform 
tasks that usually require human intelligence. It can learn from data, 
identify patterns, and make decisions. AI is widely used in areas such as 
healthcare, education, and transportation to improve eAiciency and 
accuracy. 
Example 2 
Input: 
Cloud computing is a technology that allows users to store and access 
data over the internet instead of on local computers. It provides services 
such as storage, servers, and software through online platforms. Cloud 
computing helps organizations reduce costs and improve accessibility. 

Output: 
Cloud computing allows users to store and access data through the 
internet rather than using local devices. It provides services like storage, 
servers, and software online. This technology helps businesses reduce 
costs, improve flexibility, and access information from anywhere. 
Now summarize the following text: 
Input Text: 
Blockchain technology is a digital system used to record and store 
information in a secure, transparent, and decentralized way. Unlike 
traditional databases that are controlled by a central authority such as a 
bank or organization, blockchain operates on a distributed network of 
computers. These computers, often called nodes, work together to 
maintain and verify a shared record of transactions. Because the data is 
distributed across many systems rather than stored in a single location, 
blockchain reduces the risk of data tampering and increases trust among 
users. The technology first became widely known through 
cryptocurrencies, especially Bitcoin, but today it is being explored for many 
other applications beyond digital currency. A blockchain is made up of 
digital blocks connected in chronological order. Each block contains 
transaction data, a timestamp, and a cryptographic hash that links it to the 
previous block. If someone changes the data in a block, the hash changes, 
alerting the network to possible tampering. Because all blocks are 
connected, altering one block would require changing all subsequent 
blocks across the network, which is extremely diAicult. Blockchain uses a 
decentralized verification process called consensus, where network 
participants confirm transactions instead of a central authority. 
Mechanisms such as proof of work or proof of stake help validate 
transactions before they are permanently recorded. Blockchain also 
provides transparency and immutability, meaning records are visible to 
participants and cannot easily be changed. Additionally, blockchain 
supports smart contracts, which are self-executing programs that 
automatically perform actions when certain conditions are met. Today, 
blockchain is used in industries like finance, healthcare, logistics, and 
government services. Although challenges such as scalability and energy 
consumption remain, blockchain is expected to play a significant role in 
future digital systems.” 

Output text: 
Blockchain technology is a secure, decentralized way to record and store 
data across many computers, called nodes, instead of using a central 
authority like a bank. This shared network verifies transactions together, 
reducing tampering risks and building trust. Data lives in blocks linked 
chronologically by unique cryptographic hashes. Changing one block alters 
its hash, breaking the chain and alerting everyone—making edits nearly 
impossible without controlling most of the network. Transactions get 
verified through consensus methods like proof-of-work or proof-of-stake, 
then added permanently. Blockchain oAers transparency (everyone sees 
records) and immutability (no easy changes). Smart contracts automate 
actions when conditions are met, like releasing payment after delivery. 
Famous from Bitcoin, it's now used in finance, healthcare, logistics, and 
more for better security and eAiciency, despite issues like high energy use. 
(132 words) 

Prompt given for chain of thoughts: 
Input text: 
“Blockchain technology is a digital system used to record and store 
information in a secure, transparent, and decentralized way. Unlike 
traditional databases that are controlled by a central authority such as a 
bank or organization, blockchain operates on a distributed network of 
computers. These computers, often called nodes, work together to 
maintain and verify a shared record of transactions. Because the data is 
distributed across many systems rather than stored in a single location, 
blockchain reduces the risk of data tampering and increases trust among 
users. The technology first became widely known through 
cryptocurrencies, especially Bitcoin, but today it is being explored for many 
other applications beyond digital currency. A blockchain is made up of 
digital blocks connected in chronological order. Each block contains 
transaction data, a timestamp, and a cryptographic hash that links it to the 
previous block. If someone changes the data in a block, the hash changes, 
alerting the network to possible tampering. Because all blocks are 
connected, altering one block would require changing all subsequent 
blocks across the network, which is extremely diAicult. Blockchain uses a 
decentralized verification process called consensus, where network 
participants confirm transactions instead of a central authority. 
Mechanisms such as proof of work or proof of stake help validate 
transactions before they are permanently recorded. Blockchain also 
provides transparency and immutability, meaning records are visible to 
participants and cannot easily be changed. Additionally, blockchain 
supports smart contracts, which are self-executing programs that 
automatically perform actions when certain conditions are met. Today, 
blockchain is used in industries like finance, healthcare, logistics, and 
government services. Although challenges such as scalability and energy 
consumption remain, blockchain is expected to play a significant role in 
future digital systems.” 

Output text: 
Step 1: Identify main topic and structure. 
The passage explains blockchain basics: definition, how it diAers from 
traditional systems, block structure, security via hashes, consensus, 
features (transparency, immutability), smart contracts, applications, and 
challenges. 
Step 2: Extract key points without details. 
 Decentralized network of nodes for secure, shared transaction 
records. 
 Blocks linked by hashes for tamper-proof chain. 
 Consensus (e.g., proof-of-work/stake) verifies transactions. 
 Transparency, immutability; smart contracts automate actions. 
 From Bitcoin to uses in finance/healthcare/etc.; scalability/energy 
issues. 
Step 3: Group into logical flow. 
Intro (what it is/why better), mechanics (blocks/hashes/consensus), 
benefits (features/smart contracts), real-world use/challenges. 
Step 4: Write concise summary in simple language, aiming 
100-150 words. 
Count words to fit; use active voice, short sentences for undergrad level. 
Blockchain is a secure, decentralized digital ledger that records 
transactions across a network of computers (nodes), unlike central 
databases run by banks. Nodes collaborate to verify and store data, 
minimizing tampering and boosting trust. It gained fame with Bitcoin but 
now applies widely beyond crypto. Each block holds transactions, a 
timestamp, and a hash linking to the prior block. Tampering changes the 
hash, breaking the chain—requiring network-wide updates, which is nearly 
impossible. Consensus mechanisms like proof-of-work or proof-of-stake 
validate transactions for permanent addition. Features include 
transparency (viewable records) and immutability (unchangeable data). 
Smart contracts auto-execute when conditions met, like payments on 
delivery. Used in finance, healthcare, logistics; faces scalability and energy 
hurdles but promises big future impact. (138 words) 

Prompt given for role based: 
Input text: 
Assuming role: Role: You are a technology educator explaining 
complex topics to undergraduate students. 
Key elements to cover: Core definition, decentralization vs. central 
systems, block structure/security, consensus, features, smart contracts, 
applications, challenges. 
Structure summary: Start with what/why, explain how it works, 
highlight benefits/uses, end with future outlook. Keep 100-150 words, 
everyday language. 
“Blockchain technology is a digital system used to record and store 
information in a secure, transparent, and decentralized way. Unlike 
traditional databases that are controlled by a central authority such as a 
bank or organization, blockchain operates on a distributed network of 
computers. These computers, often called nodes, work together to 
maintain and verify a shared record of transactions. Because the data is 
distributed across many systems rather than stored in a single location, 
blockchain reduces the risk of data tampering and increases trust among 
users. The technology first became widely known through 
cryptocurrencies, especially Bitcoin, but today it is being explored for many 
other applications beyond digital currency. A blockchain is made up of 
digital blocks connected in chronological order. Each block contains 
transaction data, a timestamp, and a cryptographic hash that links it to the 
previous block. If someone changes the data in a block, the hash changes, 
alerting the network to possible tampering. Because all blocks are 
connected, altering one block would require changing all subsequent 
blocks across the network, which is extremely diAicult. Blockchain uses a 
decentralized verification process called consensus, where network 
participants confirm transactions instead of a central authority. 
Mechanisms such as proof of work or proof of stake help validate 
transactions before they are permanently recorded. Blockchain also 
provides transparency and immutability, meaning records are visible to 
participants and cannot easily be changed. Additionally, blockchain 
supports smart contracts, which are self-executing programs that 
automatically perform actions when certain conditions are met. Today, 
blockchain is used in industries like finance, healthcare, logistics, and 
government services. Although challenges such as scalability and energy 
consumption remain, blockchain is expected to play a significant role in 
future digital systems."

Output text: 
Blockchain acts like a tamper-proof digital notebook shared across many 
computers, not controlled by one boss like a bank. These computers, or 
nodes, team up to record and check transactions securely, spreading data 
everywhere to prevent hacks and build trust. It shot to fame with Bitcoin 
but now powers much more. Picture blocks of info chained together by 
special codes called hashes—change one, and the whole chain breaks, 
alerting everyone. Nodes use "consensus" rules (like proof-of-work or 
stake) to agree on valid transactions before locking them in forever. It 
shines with openness (anyone sees records), unchangeability, and smart 
contracts that auto-run deals, like paying for goods on arrival. Industries 
like finance, health, and shipping love it for speed and safety, though 
scaling up and energy use are hurdles. Blockchain will reshape our digital 
world. (142 words) 

CLAUDE: 

Prompt given for zero shot: 
Input text: 
“Blockchain technology is a digital system used to record and store 
information in a secure, transparent, and decentralized way. Unlike 
traditional databases that are controlled by a central authority such as a 
bank or organization, blockchain operates on a distributed network of 
computers. These computers, often called nodes, work together to 
maintain and verify a shared record of transactions. Because the data is 
distributed across many systems rather than stored in a single location, 
blockchain reduces the risk of data tampering and increases trust among 
users. The technology first became widely known through 
cryptocurrencies, especially Bitcoin, but today it is being explored for many 
other applications beyond digital currency. A blockchain is made up of a 
series of digital blocks that are connected together in chronological order 
to form a chain. Each block contains a set of transaction data, a 
timestamp, and a unique cryptographic code called a hash. This hash links 
the current block to the previous one, creating a secure chain of records. If 
someone attempts to change the data in a block, the hash will also change, 
which alerts the network that tampering has occurred. Because every 
block is connected to the one before it, altering a single block would 
require changing all subsequent blocks in the chain across many 
computers in the network. This process is extremely diAicult, which makes 
blockchain highly secure and reliable One of the key features of blockchain 
technology is decentralization. In traditional systems, a central authority 
controls the database and verifies transactions. In blockchain systems, 
however, transaction verification is carried out collectively by the network 
participants through a process called consensus. DiAerent blockchain 
systems use diAerent consensus mechanisms, such as proof of work or 
proof of stake, to confirm that transactions are valid. Once verified, the 
transaction is added to a block and permanently recorded on the 
blockchain. This decentralized approach eliminates the need for 
intermediaries and can reduce costs and processing time. Blockchain 
technology also provides transparency and immutability. Transparency 
means that all participants in the network can view the recorded 
transactions, which helps build trust among users. Immutability means 
that once information is recorded on the blockchain, it cannot easily be 
changed or deleted. These features make blockchain useful in situations 
where secure and verifiable records are required. For example, 
organizations can use blockchain to track supply chains, manage digital 
identities, or verify important documents. Another important concept 
related to blockchain is smart contracts. Smart contracts are self
executing programs stored on the blockchain that automatically carry out 
actions when specific conditions are met. For instance, a smart contract 
could automatically transfer payment once a service has been completed. 
This reduces the need for manual processing and ensures that agreements 
are executed exactly as programmed. Today, blockchain technology is 
being explored in many industries, including finance, healthcare, logistics, 
and government services. It has the potential to improve security, 
eAiciency, and transparency in digital transactions. Although the 
technology is still evolving and faces challenges such as scalability and 
energy consumption, many experts believe that blockchain will play an 
important role in the future of digital systems and data management.” 

Output text: 
Blockchain is a decentralized digital ledger that records transactions 
across a peer-to-peer network without a central authority. Data is stored in 
encrypted "blocks" cryptographically linked in sequence, forming a chain. 
Transactions are validated through consensus mechanisms like Proof of 
Work or Proof of Stake, then added to the chain with a unique hash. 
Because each block contains the previous block's hash, altering past data 
breaks the chain, making tampering immediately detectable. Key strengths 
include transparency, immutability, and security. Modern blockchains also 
support smart contracts — self-executing programs that automate 
agreements without intermediaries. Networks can be public, private, 
consortium, or hybrid. Blockchain has evolved through three generations: 
cryptocurrency, smart contracts, and enterprise scalability. Today, its 
applications extend well beyond finance into healthcare, supply chain, and 
digital identity, oAering businesses a trusted, eAicient single source of 
truth. 

Prompt given for Few shot: 
Input text: 
“"Summarize the given passage into 100–150 words using simple language 
suitable for undergraduate students. 
Below are examples of how the summary should look. 
Example 1 
Input: 
Artificial Intelligence (AI) refers to the ability of machines to perform tasks 
that normally require human intelligence. It includes learning from data, 
recognizing patterns, and making decisions. AI is used in many fields such 
as healthcare, education, and transportation. 
Output: 
Artificial Intelligence is a technology that enables machines to perform 
tasks that usually require human intelligence. It can learn from data, 
identify patterns, and make decisions. AI is widely used in areas such as 
healthcare, education, and transportation to improve eAiciency and 
accuracy. 
Example 2 
Input: 
Cloud computing is a technology that allows users to store and access 
data over the internet instead of on local computers. It provides services 
such as storage, servers, and software through online platforms. Cloud 
computing helps organizations reduce costs and improve accessibility. 
Output: 
Cloud computing allows users to store and access data through the 
internet rather than using local devices. It provides services like storage, 
servers, and software online. This technology helps businesses reduce 
costs, improve flexibility, and access information from anywhere. 
Now summarize the following text: 
Input Text: 
Blockchain technology is a digital system used to record and store 
information in a secure, transparent, and decentralized way. Unlike 
traditional databases that are controlled by a central authority such as a 
bank or organization, blockchain operates on a distributed network of 
computers. These computers, often called nodes, work together to 
maintain and verify a shared record of transactions. Because the data is 
distributed across many systems rather than stored in a single location, 
blockchain reduces the risk of data tampering and increases trust among 
users. The technology first became widely known through 
cryptocurrencies, especially Bitcoin, but today it is being explored for many 
other applications beyond digital currency. A blockchain is made up of 
digital blocks connected in chronological order. Each block contains 
transaction data, a timestamp, and a cryptographic hash that links it to the 
previous block. If someone changes the data in a block, the hash changes, 
alerting the network to possible tampering. Because all blocks are 
connected, altering one block would require changing all subsequent 
blocks across the network, which is extremely diAicult. Blockchain uses a 
decentralized verification process called consensus, where network 
participants confirm transactions instead of a central authority. 
Mechanisms such as proof of work or proof of stake help validate 
transactions before they are permanently recorded. Blockchain also 
provides transparency and immutability, meaning records are visible to 
participants and cannot easily be changed. Additionally, blockchain 
supports smart contracts, which are self-executing programs that 
automatically perform actions when certain conditions are met. Today, 
blockchain is used in industries like finance, healthcare, logistics, and 
government services. Although challenges such as scalability and energy 
consumption remain, blockchain is expected to play a significant role in 
future digital systems.”  

Output text: 
Blockchain technology is a secure, decentralized way to record and store 
data across many computers, called nodes, instead of using a central 
authority like a bank. This shared network verifies transactions together, 
reducing tampering risks and building trust. Data lives in blocks linked 
chronologically by unique cryptographic hashes. Changing one block alters 
its hash, breaking the chain and alerting everyone—making edits nearly 
impossible without controlling most of the network. Transactions get 
verified through consensus methods like proof-of-work or proof-of-stake, 
then added permanently. Blockchain oAers transparency (everyone sees 
records) and immutability (no easy changes). Smart contracts automate 
actions when conditions are met, like releasing payment after delivery. 
Famous from Bitcoin, it's now used in finance, healthcare, logistics, and 
more for better security and eAiciency, despite issues like high energy use. 

Prompt given for chain of thoughts: 
Input text: 
“Blockchain technology is a digital system used to record and store 
information in a secure, transparent, and decentralized way. Unlike 
traditional databases that are controlled by a central authority such as a 
bank or organization, blockchain operates on a distributed network of 
computers. These computers, often called nodes, work together to 
maintain and verify a shared record of transactions. Because the data is 
distributed across many systems rather than stored in a single location, 
blockchain reduces the risk of data tampering and increases trust among 
users. The technology first became widely known through 
cryptocurrencies, especially Bitcoin, but today it is being explored for many 
other applications beyond digital currency. A blockchain is made up of 
digital blocks connected in chronological order. Each block contains 
transaction data, a timestamp, and a cryptographic hash that links it to the 
previous block. If someone changes the data in a block, the hash changes, 
alerting the network to possible tampering. Because all blocks are 
connected, altering one block would require changing all subsequent 
blocks across the network, which is extremely diAicult. Blockchain uses a 
decentralized verification process called consensus, where network 
participants confirm transactions instead of a central authority. 
Mechanisms such as proof of work or proof of stake help validate 
transactions before they are permanently recorded. Blockchain also 
provides transparency and immutability, meaning records are visible to 
participants and cannot easily be changed. Additionally, blockchain 
supports smart contracts, which are self-executing programs that 
automatically perform actions when certain conditions are met. Today, 
blockchain is used in industries like finance, healthcare, logistics, and 
government services. Although challenges such as scalability and energy 
consumption remain, blockchain is expected to play a significant role in 
future digital systems.” 

Output text: 
Step 1: Identify main topic and structure. 
The passage explains blockchain basics: definition, how it diAers from 
traditional systems, block structure, security via hashes, consensus, 
features (transparency, immutability), smart contracts, applications, and 
challenges. 
Step 2: Extract key points without details. 
 Decentralized network of nodes for secure, shared transaction 
records. 
 Blocks linked by hashes for tamper-proof chain. 
 Consensus (e.g., proof-of-work/stake) verifies transactions. 
 Transparency, immutability; smart contracts automate actions. 
 From Bitcoin to uses in finance/healthcare/etc.; scalability/energy 
issues. 
Step 3: Group into logical flow. 
Intro (what it is/why better), mechanics (blocks/hashes/consensus), 
benefits (features/smart contracts), real-world use/challenges. 
Step 4: Write concise summary in simple language, aiming 
100-150 words. 
Count words to fit; use active voice, short sentences for undergrad level. 
Blockchain is a secure, decentralized digital ledger that records 
transactions across a network of computers (nodes), unlike central 
databases run by banks. Nodes collaborate to verify and store data, 
minimizing tampering and boosting trust. It gained fame with Bitcoin but 
now applies widely beyond crypto. Each block holds transactions, a 
timestamp, and a hash linking to the prior block. Tampering changes the 
hash, breaking the chain—requiring network-wide updates, which is nearly 
impossible. Consensus mechanisms like proof-of-work or proof-of-stake 
validate transactions for permanent addition. Features include 
transparency (viewable records) and immutability (unchangeable data). 
Smart contracts auto-execute when conditions met, like payments on 
delivery. Used in finance, healthcare, logistics; faces scalability and energy 
hurdles but promises big future impact. 

Prompt given for role based: 
Input text: 
Assuming role: Role: You are a technology educator explaining 
complex topics to undergraduate students. 
Key elements to cover: Core definition, decentralization vs. central 
systems, block structure/security, consensus, features, smart contracts, 
applications, challenges. 
Structure summary: Start with what/why, explain how it works, 
highlight benefits/uses, end with future outlook. Keep 100-150 words, 
everyday language. 
“Blockchain technology is a digital system used to record and store 
information in a secure, transparent, and decentralized way. Unlike 
traditional databases that are controlled by a central authority such as a 
bank or organization, blockchain operates on a distributed network of 
computers. These computers, often called nodes, work together to 
maintain and verify a shared record of transactions. Because the data is 
distributed across many systems rather than stored in a single location, 
blockchain reduces the risk of data tampering and increases trust among 
users. The technology first became widely known through 
cryptocurrencies, especially Bitcoin, but today it is being explored for many 
other applications beyond digital currency. A blockchain is made up of 
digital blocks connected in chronological order. Each block contains 
transaction data, a timestamp, and a cryptographic hash that links it to the 
previous block. If someone changes the data in a block, the hash changes, 
alerting the network to possible tampering. Because all blocks are 
connected, altering one block would require changing all subsequent 
blocks across the network, which is extremely diAicult. Blockchain uses a 
decentralized verification process called consensus, where network 
participants confirm transactions instead of a central authority. 
Mechanisms such as proof of work or proof of stake help validate 
transactions before they are permanently recorded. Blockchain also 
provides transparency and immutability, meaning records are visible to 
participants and cannot easily be changed. Additionally, blockchain 
supports smart contracts, which are self-executing programs that 
automatically perform actions when certain conditions are met. Today, 
blockchain is used in industries like finance, healthcare, logistics, and 
government services. Although challenges such as scalability and energy 
consumption remain, blockchain is expected to play a significant role in 
future digital systems."    

Output text: 
Blockchain acts like a tamper-proof digital notebook shared across many 
computers, not controlled by one boss like a bank. These computers, or 
nodes, team up to record and check transactions securely, spreading data 
everywhere to prevent hacks and build trust. It shot to fame with Bitcoin 
but now powers much more. Picture blocks of info chained together by 
special codes called hashes—change one, and the whole chain breaks, 
alerting everyone. Nodes use "consensus" rules (like proof-of-work or 
stake) to agree on valid transactions before locking them in forever. It 
shines with openness (anyone sees records), unchangeability, and smart 
contracts that auto-run deals, like paying for goods on arrival. Industries 
like finance, health, and shipping love it for speed and safety, though 
scaling up and energy use are hurdles. Blockchain will reshape our digital 
world. 
RESULT: 
```
Factor               ChatGPT            Perplexity          Claude
                                                  
Accuracy              9/10               8.5/10              9.5/10

Coherence             9/10               8/10                9.5/10
 
Simplicity            9/10               8.5/10              8.5/10

Speed                 9/10               9.5/10              8.5/10

User Experience       9.5/10             8.5/10              9/10

```
RESULT:
       Thus, the Summarization of text using different AI tools has been done.
