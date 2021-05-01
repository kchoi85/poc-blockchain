# Blockchain with SHA256
Simple blockchain (Blocks + chain) in NodeJS - 20210430

## Packages and references
Reference: https://www.smashingmagazine.com/2020/02/cryptocurrency-blockchain-node-js/

```
npm install --save crypto-js
```

- **index**	        :   It’s a unique number that tracks the position of every block in the entire blockchain.
- **timestamp**	    :   It keeps a record of the time of occurrence of each completed transaction.
- **data**	        :   It provides data about the completed transactions, such as the sender details, recipient’s details, and quantity transacted.
- **precedingHash**	:   It points to the hash of the preceding block in the blockchain, something important in maintaining the blockchain’s integrity.