# BlockChain
A simple BlockChain implelemtation using Python. It also has PoW(Proof of Work) concept which is how mining works.

### Block class:
```timestamp``` - Block creation time<br>
```transactions``` - Data<br>
```previous_hash``` - SHA-256 hash of previous block<br>
```nonce``` - Initial number used for PoW<br>
```hash``` - SHA-256 hash of current block<br>
```generate_hash()``` - Generates SHA-256 hash of current block<br>
```print_contents()``` - Prints the content of current block<br>

### Blockchain class:
```chain``` - Block chain (list)<br>
```all_transactions``` - All performed transactions<br>
```genesis_block``` - First block of blockchain<br>
```genesis_block()``` - Creates first block(init)<br>
```print_blocks()``` - Prints all blocks in the blockchain<br>
```add_block()``` - Adds new block to block chain<br>
```validate_chain()``` - Validates the blockchain<br>
```proof_of_work()``` - PoW function to solve the required hash<br>
<br>
## Example on how to use: [Example.ipynb](Example.ipynb)
