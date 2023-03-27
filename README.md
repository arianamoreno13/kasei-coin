# kasei-coin
The objective of this project is to establish a crowdsale for a newly minted ERC-20 token named KaseiCoin. The contract for KaseiCoin is being developed in Remix, while Ganache is utilized to test it on a blockchain. To purchase tokens and sign transactions, the team will be utilizing the MetaMask wallet.

Initially, the team will create a MetaMask test network, following which they will import two accounts via private keys from Ganache to allow them to interact with the test network. Upon completion of this process, the MetaMask wallet will display a balance of 100 ETH by default, and should look similar to the image below:

![MetaMask Dev](media/metamaskdev.gif)

The next task is to test the contracts. You can see below the KaseiCoin contract has been compiled successfully. 

![KaseiCoin contract Compiled](media/KaseiCoinSolcompiled.gif)

Subsequently, it is important to confirm that the KaseiCoinCrowdsale contract and deployer compiles without any issues. You can see that in the imagine below. 

![KaseiCoin Crowdsale Compiled](media/KaseiCoinCrowdsaleCompiled.gif)

After finishing the task, our objective is to deploy the 'KaseiCoinCrowdsaleDeployer' contract. This will generate the two additional contracts simultaneously. To achieve this, we need to access the Deploy and run transactions section in Remix, in the enviroment drop-down section select the Injected Provider - MetaMask option, and in the contract drop-down menu select 'KaseiCoinCrowdsaleDeployer'. Upon selecting this option, MetaMask should automatically launch, and the window should appear as follows:

![MetaMask contract deployed](media/contracted-deployed.gif)

Make sure you hit the confirm button in MetaMask. Then you can head over to Ganache, where you should see the contract creation listed in your Transactions tab, as depicted in the image below.

![Ganache Contract Creation](media/ganache-deployed.gif)

Our contract is now set up for testing and interaction! As we enter the crowdfunding phase, we have various capabilities such as purchasing tokens, verifying the balance of different addresses (i.e., addresses that have bought tokens), reviewing the total amount of Wei raised, and checking the total supply, among others. As we carry out multiple transactions, the total supply can be observed below.

![KaseiCoin Remix GIF](media/kaseicoin-remix-GIF.gif)

