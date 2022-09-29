ERC-20  
Crowdsale 




What is Crowdsale :

Although a crowdsale is similar to crowdfunding, there are marked differences between the two. It’s important to understand how a crowdsale works before choosing to invest your money.
A start-up company trading in blockchain launches an Initial Coin Offering (ICO). One part of this process is known as the crowdsale, an opportunity to sell cryptocurrency digital units or ‘tokens’ to investors to raise money for a project or service that is in development.
An investor wishing to participate sends cryptocurrency to the project address and, in return, receives a token that is stored on their computer or device.
Tokens act as a promise that you can participate in that project or service once it is up and running.
The tokens do not have a set value, their value can rise or fall depending on the success of the project. In this way, crowdsales hold some similarity to trading in traditional shares.














Implementation:- 
( All contracts are optimized )

Crowdsale

Ethereum Chain:-

Token:  https://goerli.etherscan.io/address/0x48bba484412095293ea11215269708ded0f3e8cb#code ( Gas used: 0.00199319GoerliETH   )

Sale: https://goerli.etherscan.io/address/0x9e873e31bc45518bdaae80adc8a6c274e13b475b#readContract
(0.00222483GoerliETH Gas Fee)

Deployment procedure:- ( Remix )

Deploying a Contract to Mainnet or Testnet Using Remix.
Step 1- Create a file in Remix with your project name. And paste your code. Select the correct compiler version.

Step 2- Navigate to the Compile sidebar option and press the Compile Sale.sol button or just CTRL + S, it will compile your contract.

Step 3- Select your desired contract with a contract name from CONTRACT. 

Step 4- Now you can deploy the contract by navigating to the Deployment sidebar option. You need to change the topmost ENVIRONMENT dropdown from JavaScript VM to Injected Web3. This tells Remix to use the MetaMask injected provider to point it to your Mainnet or Testnet development node.
If you wanted to try this using another network, you would have to connect MetaMask to the correct network instead of your local development node.

When you select Injected Web3, you will be prompted to allow Remix to connect to your MetaMask account. Press Next in MetaMask to allow Remix to access the selected account.

Step 5- Back on Remix, you should see that the account you wish to use for deployment is now managed by MetaMask.  
Select Deploy.

You will be prompted in MetaMask to confirm the contract deployment transaction.
After you press Confirm and the deployment is complete, you will see the transaction listed in MetaMask. The contract will appear under Deployed Contracts in Remix.


Video Tutorial: Ethereum Smart Contract with Remix

Crowdsale :


NOTE:- We are using Interface in this Contract. You can learn about the Smart Contract Interface by providing the link (https://www.newline.co/courses/creating-an-erc20-token-on-ethereum/smart-contract-interfaces)

Read Functions:-

1.ETHWallet
    This function will return the address of the current wallet.

2.Token
    This function will return the address of the token for crowdsale.

3.creator
    This function will return the creator of the contract.

4.endTime
    This function will return the end time of the block.

5.exchangeRate
    This function will return the exchange rate of the token.

6.isFunding
    This function will tell you about the status of your token in the funding phase or not in bool(True/False) value.

7.maxMintable
    This function will return the maximum number of mintable tokens for fundraising.

8.startTime
    This function will return the starting time of sale.

9.totalMinted
    This function will return the total minted token.


Write Functions:-
1.changeCreator
          When will be call this function you can change the address of creator with current creator to new creator, by inputting the new creator address.

    
2.closeSale
    This function will close the sale and convert the contract at the initial stage.



3.contribute
    This function is payable, when calling this function will automatically by inputting Eth value gives you the token at the given wallet address.


4.setup
    This function will put the Token on sale as inputting token address and end block time in UNIX TimeStamp.

5.updateMaxMintable
    You can update the maximum mintable of the token by calling this function.

5.updateRate
    You can update the rate of the token by calling this function.




Usage Flow:-

After the deploying of the Sale & ERC20 token on Ethereum.

Step 1: Call the function setup from the Sale contract to put the token on sale .


Step 2: Then after calling the function, contribute to accept ETH value and give a token according to the rate .

Step 3:The owner can close the sale and also change the creator and rate of the token .







Disclaimer:-

This ERC-20-based Crowdsale smart contract was created for use in production-level blockchain applications and is thoroughly tested to the best of the developers' knowledge to work as intended.

That's it! you're done. 
