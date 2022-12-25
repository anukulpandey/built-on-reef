# Reef Projects I Built

Hey there! 👋🏼

I am Anukul Pandey, Final Year Undergrad . A penetration tester, Web developer & also an App developer. I like to build stuff , or BUIDL 🙂

So here are the projects I made on Reef chain, from the most basic ones to the recent ones. I hope you will like them! Without further a do. Let’s get started!

- Monkey Share 🐒
    
    This is the first dapp I ever made, here user can come , pay a one time fee of registration on the service & after that they can use unlimited free file storage services of IPFS. 
    
    ![Untitled](Reef%20Projects%20I%20Built%208b6b2f8cbbcd48de8846d1d897d0a64c/Untitled.png)
    
    It has an easy to use interface. You can read more about this by visiting the link below 🙂
    
    Project URL : https://github.com/anukulpandey/MonkeyShare-reef
    
- Pocket Monster 🦖
    
    One of the best Dapp I ever made 😀. Or maybe the first game on the Reef chain as well. So here you have to connect your wallet, select one of the characters . PS: There is no strongest or weakest character, your chances of winning depends on various criterias. Like the time in which you select that character, the actual strength of character & so on.
    
    Few glimpses of the game → 
    
    ![Untitled](Reef%20Projects%20I%20Built%208b6b2f8cbbcd48de8846d1d897d0a64c/Untitled%201.png)
    
    ![Untitled](Reef%20Projects%20I%20Built%208b6b2f8cbbcd48de8846d1d897d0a64c/Untitled%202.png)
    
    link: [https://reefpocketmonster.netlify.app/](https://reefpocketmonster.netlify.app/)
    
    [Reef's Pocket Monsters](https://reefpocketmonster.netlify.app/)
    
- Decentralised Twitter 🐦
    
   So I made this Dapp known as Dwitter, where you can post dweets & all the data will be stored in the blockchain , so a version of our web2 twitter but better with the powers of web3.
    
    ![image](https://user-images.githubusercontent.com/62092256/198824050-02ab1758-54a8-4cb9-85f6-6aba4766d937.png)
    
    Demo of Dwitter : 
    https://user-images.githubusercontent.com/62092256/198824062-d42aec4b-c5b1-4695-8867-6f91ba346879.mp4

    [Dwitter](https://dwitter-reef.netlify.app/)
    
- Token Sender 🦊
    
    I use reef’s extension a lot while development as well as in the production (ofc) but I had a problem of sending Reef tokens from one account to another, as I have multiple accounts for testing purpose. So what did I do? I built a DAPP specifically for sending Reef tokens from one account to another 😎 & the transaction fee per transaction is just 1.51 Reefs.
    
    ![Untitled](Reef%20Projects%20I%20Built%208b6b2f8cbbcd48de8846d1d897d0a64c/Untitled%203.png)
    
    It’s available on testnet: [https://reefox.netlify.app/](https://reefox.netlify.app/)
    
    [Reef0x](https://reefox.netlify.app/)

- Deflationary Launchpad 🐒
   
   This is a Decentralised Web-application [Dapp] 💰 built on top of **Reef Chain** where you can launch your own tokens without any coding experience. Not only that, you will be able to customise your token to full extent by choosing its Name, Symbol , Initial supply and the most important parameter Fees. (How much percentage of the token will be burnt). Basically you can deploy Deflationary tokens. What is it? Well... A deflationary token is the token which experiences deflation rather than inflation, i.e over time, it becomes more valuable unlike most of the currencies out there.
    
    ![image](https://user-images.githubusercontent.com/62092256/204230026-28341e61-d43d-46ba-a885-85a19c001185.png)
    
    
- Crowd Funding dApp 
    It's a crowdfunding application where artists or anyone can list their campaign and get funded by people in a given number of days, once done they get the fund.
    User can launch a campaign & others can pledge , transfer their tokens to the campaign.
    After the campaign ends, campaign creator can claim the funds if total amount pledged is more than the campaign goal.
    Otherwise if campaign doesn't reach the goal , users can take back their tokens they sent.
    Campaign creator can cancel the campaign if it hasn't started.
    Users can withdraw their funds before event ends as well as after event ends if the goal isn't met.
    
    <img width="960" alt="image" src="https://user-images.githubusercontent.com/62092256/209477736-9d4e285a-2e1a-457e-95e1-6b530829229b.png">
    
    https://reef-crowd-fund.netlify.app/

- Staking dApp
    Staking is a way of earning rewards for holding certain cryptocurrencies.So in this dApp you can stake REEF ERC20 tokens & earn a reward for it.
    User can stake any amount of tokens (upto 100).
    They can withdraw the funds any time. Also the reward claimed can be withdrawn alone, without withdrawing the staked funds.
    It is minimised version of Synthetix Staking.ou can google it to learn more about Synthetix Staking reward system.
    Don't have tokens to stake? We have a free faucet as well.
    
    <img width="960" alt="image" src="https://user-images.githubusercontent.com/62092256/209477773-604539df-fed3-4ab5-9ef8-f5a160c89e26.png">
    
    https://reef-staking-dapp.netlify.app/
 
- Reef Name Service
    REEF Name Service [RNS] is a platform where you can get free Readable Name for your long REEF wallet address.
    You can use this dApp to transfer funds without using long wallet address, just use something like 0xanukul.reef or bandar.reef and that is it.
    Send funds to this RNS.
    
    ![image](https://user-images.githubusercontent.com/62092256/209477799-9764197d-feec-4de2-9e5e-3bbb78b7b1b5.png)
    
- Liquidity Pool
    A liquidity pool is a collection of digital assets accumulated to enable trading on a decentralized exchange (DEX). A DEX is an exchange that doesn't rely on a third party to hold users' funds. Instead, DEX users transact with each other directly.
    
    <img width="960" alt="image" src="https://user-images.githubusercontent.com/62092256/209477839-0b60a773-28f8-4c51-bb1d-7f2942cb7970.png">

---

### Utility Stuff

Apart from full stack dapps, I wrote some scripts, or made some repositories , which might be helpful for other developers, specially for those who are just starting to develop on the Reef chain. 

<aside>
💡 PS: There were few problems which I encountered while learning so I am also providing the solutions I came up with 🙂

</aside>

- Minimal Reef React Dapp
    
    There are lots of minimal dapps variants of Reef chain are available , but they were not written in pure react js & to be really honest most of the developers are familiar with javascript , more than typescript. And as a beginner when someone tries to use @reef-defi/evm-provider they might encounter few errors which are not available on the internet like adding polyfills, resolving crypto browser errors and so on. So I built this dapp which consists of all the libraries & modules which a developer might require to start building on reef chain.
    
    ![Untitled](Reef%20Projects%20I%20Built%208b6b2f8cbbcd48de8846d1d897d0a64c/Untitled%204.png)
    
    Kind of a starter template for reef react dapp
    
    Repository url : https://github.com/anukulpandey/minimal-react-reef-dapp
    
    ```bash
    git clone https://github.com/anukulpandey/minimal-react-reef-dapp project
    cd project
    yarn install 
    yarn start
    ```
    
- Minimal Reef Hardhat
    
    A basic reef hardhat project (TYPICAL HELLO WORLD) but in the world of web3 🙂
    
    Serves as a template in my day to day development work.
    
    ![Untitled](Reef%20Projects%20I%20Built%208b6b2f8cbbcd48de8846d1d897d0a64c/Untitled%205.png)

- Curated list of resources for development on REEF
    
    https://twitter.com/0xanukul/status/1579477128386871298?s=20&t=DrenoPL_zxQ-q2FJVs89jA
  
This readme file is also available on web version  -> https://builtonreef.netlify.app/

I hope you liked these. Feel free to reach out to me at → 

✉️ anukul.030601@gmail.com
