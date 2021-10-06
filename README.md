# pbl-election-dapp
A blockchain-smart contracts powered e-voting mechanism. Its a miniature version - web application wherein the voters can signin via metamask and verify themselves before casting their vote. Upon voting, the votes will be recorded and the current user will not be allowed to vote again. Proof of vote, Proof of results, anonynimity and transparency is maintained.

This project was created as a part of School - PBL - Activity.


### To run the election-dapp
#### Prerequisite: 
1. Node.js - https://nodejs.org
2. Truffle - $ npm install -g truffle
3. Ganache - http://truffleframework.com/ganache/
4. MetaMask chrome extension - https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn

#### Step 1. Clone the project
$ git clone https://github.com/Mishra-Shreya/pbl-election-dapp.git

#### Step 2. Change directory to move inside project.
$ cd pbl-election-dapp

#### Step 3. Start Ganache

#### Step 4. Compile & Deploy Election Smart Contract
$ truffle migrate --reset

#### Step 5. Configure Metamask
Configure metamask in your browser - https://youtu.be/nUEBAS5r4Og

#### Step 6. Run the Front End Application
$ npm run dev

Visit this URL in your browser: http://localhost:3000

**(Also connect the imported account in metamask with http://localhost:3000)







#### Credits : dappuniversity tutorial - https://youtu.be/3681ZYbDSSk
