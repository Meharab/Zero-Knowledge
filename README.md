# 1. What is a hash? Why do people use hashing to hide information?
A cryptographic hash function is a mathematical algorithm that maps data of an arbitrary size to a bit array of a fixed size. It is a one-way function, that is, a function for which it is practically infeasible to invert or reverse the computation.

People use hashing to hide information because hashing ensures hackers can't steal data because the hashed inputs are not in their original form, making the data useless without a key to decipher the data.

# 2. What is a smart contract?
Smart contracts are simply programs stored on a blockchain that run when predetermined conditions are met. They typically are used to automate the execution of an agreement so that all participants can be immediately certain of the outcome, without any intermediary’s involvement or time loss. They can also automate a workflow, triggering the next action when conditions are met.

# 3. What are gas fees? Why is gas optimization a big focus when building smart contracts?
A gas fee is the amount of cryptocurrency required for an blockchain network user to conduct a transaction on the network. Gas fees are used to compensate miners for their work in verifying transactions and securing the network.

Optimizing smart contracts may reduce gas consumption and therefore the associated cost of executing transactions. It also has the potential to mitigate against malicious exploitation of smart contracts.

# 4. You have the ability to quickly count the number of leaves in a tree. How can you prove this to a friend, without revealing the exact number of leaves?
Instead of giving him the actual number I can give him the range of mumber where the actual number is associated so that if he knows the actual number he can verify my answer. e.g. if the tree has 23 leaves and I give him the range 20-25, if he actually knows the answer then he would know that I am telling the truth.

# 5. How are smart contracts deployed? List the necessary steps.
In this example I'll demonstrate, how to deploy Ethereum smart contract using Rimix IDE.
* **Step 1:** Create a new file with the extension of **".sol"** in Remix and write the smart contract into that file.
* **Step 2:** Inject the web3 wallet so that you can sign the transaction using your private key.
* **Step 3:** select the right network where the smart contract will deploy.
* **Step 4:** Calculate the GAS Fees and pay the fees for the transaction so that minners can mine your transaction.
* **Step 5:** Collect the hash and look it up on etherscan to be confirmed if the transaction was successful or not. if not goto **step 4** and try again.

# 6. Write an escrowing smart contract for value transfer in a trade.
find the answer in following folders:
* [Code](https://github.com/Meharab/Zero-Knowledge/tree/main/Solidity)
* [Screenshots](https://github.com/Meharab/Zero-Knowledge/tree/main/Screenshots)

# 7. Is the new design better than having separate `confirmReceived` and `refundSeller`? Why or why not?
The conditions of new design is a vulnerable to attack because of the `modifier`. The condition requires 

# 8. Comprehend a simple `Hello World` circuit.
find the answer in following folder:
* [Screenshots](https://github.com/Meharab/Zero-Knowledge/blob/main/Screenshots/question-8-zkrepl-dev-circom.png)
