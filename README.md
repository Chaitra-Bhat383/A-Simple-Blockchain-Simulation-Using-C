# A dummy blockchain implementation in C

A blockchain is a constantly growing ledger which keeps a permanent record of all the transactions that have taken place in a secure, chronological, and immutable way.In simpler terms blockchain can be described as a data structure that holds transactional records and while ensuring security, transparency, and decentralization. As we now know, blocks on Bitcoin’s blockchain store data about monetary transactions. But it turns out that blockchain is actually a reliable way of storing data about other types of transactions, as well. We here instead of money transactions, are going to emulate a voting system.The blockchain is a back-linked list of blocks,each block is identifiable by a hash.

# What is hashing?

Hashing is the process of converting a given key into another value. A hash function is used to generate the new value according to a mathematical algorithm. Here we use hashing to secure our blockchain and make it more reliable. The most popular ones are SHA-235,SHA-2,SHA-1,MD5. We used djb2 in our blockchain simulation.

![Screenshot of working of hashing](/Hashing.png)


# How does the djb2 hash work?

The simple C function starts with the hash variable set to the number 5381. It then iterates the given array of characters str and performs the following operations for each character, then Multiply the hash variable by 33. Add the ASCII value of the current character to it.

# Working of our electoral Blockchain:

We have created the enum with all the parties available in the electoral system, namely good party, mediocre party and evil party, used Random function to disturbute the votes between 3 parties randomly . Then we linked all the votes with secure hash to form a blockchain.

# How does the output look?

![Screenshot of Output](/Output.png)

# Team Members :

Charvi Bannur :  https://github.com/charvibannur

Chaitra Bhat : https://github.com/Chaitra-Bhat383
 
Ankitha C : https://github.com/Ankithac45














