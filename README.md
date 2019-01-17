# Blockchain-school-acount-book

**Problem:** Financial managment of student council isn't clear.

**Goal:** Creating finance tracking system by using blockchain which purpose is track how the student council manages students' money.
The system should provide an easy way to check all transactions and be secure.


**1. Blockchain**


Each block will consist of information about a single transaction, these are: <br>
  -name of person who spent some money<br>
  -index of transaction<br>
  -date of transaction<br>
  -cost of transaction<br>
  -balance<br>
  -place of transaction<br>
  -type of transaction<br>
  -next block<br>
  -hash of previous block<br><br>
  
**2. Implementation**

We developed blockchain cryptocurrency with a use of Etherium system. Smart contracts are created in Solidity.
To manage wallet and transactions user can use our web3-driven website.

**2-1. Transaction process**

An individual has own wallet. If he or she wants to make a transaction, the receiver will produce QR code and show it to the sender.
Then the sender will scan it and access to web application. From QR code, the sender will get the receiver's wallet address. So when the sender press the "send" button, there will be a transaction.

**2-2. Tracking transaction records**

With our webpage with web3.js, we can track all the transaction records. And we will map some important addresses to their users' names(Student council members). So that we can track their records using their names.<br>


