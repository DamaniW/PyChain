# PyChain

The purpose of this assignment is to build a blockchain-based ledger system, complete with a user-friendly web interface. This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

## Testing the Ledger
 
 To test the ledger, I used a couple addresses from ganache, a personal Ethereum blockchain, in order to see if the Streamlit application would accept them:
 
 ![alt text](https://github.com/DamaniW/PyChain/blob/main/before_transaction.png?raw=true)
 
 On the left side of the Streamlit app, we can inspect each block, to see all the information that went into making the transaction. 
 
![alt text](https://github.com/DamaniW/PyChain/blob/main/new_block_inspection.png?raw=true)

Once the block is inspected, we can  validate the blockchain to make sure there are no errors:

![alt text](https://github.com/DamaniW/PyChain/blob/main/chain_validation.png?raw=true)

Lastly, for good measure, I checked in the terminal itself to make sure that the blockchain was validated:

![alt text](https://github.com/DamaniW/PyChain/blob/main/terminal_validation.png?raw=true)
