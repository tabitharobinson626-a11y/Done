# Done
Winning Auction Contract (Clarity + Clarinet)

This project contains a **Clarity smart contract** that powers a **blockchain-based auction** for awarding a contract in a Web3 environment.  
It is built for **Clarinet** (the Clarity development & testing framework), and ensures that bids are fair, transparent, and trustless.

🎯 Overview

The **Winning Auction Contract** allows anyone to participate in a transparent, on-chain auction where the **highest bidder wins**.  

Key characteristics:
- **Trustless Escrow:** Bidders deposit STX directly into the contract when bidding.  
- **Clear Leaderboard:** At any time, the current leader can be queried.  
- **Safe Withdrawals:** Losing bidders can withdraw their STX deposits.  
- **Finalization:** Once the auction ends, the owner finalizes and receives the winning funds.  
- **Fair Play:** Rules enforce minimum bids, deadlines, and safe fund management.  

 🛠 Features

- **Initialization**
  - Owner sets the auction’s title, minimum bid, start block, and end block.  
- **Bidding**
  - Anyone can submit a bid higher than the current leader.  
  - Bids are locked in STX until the auction ends.  
- **Withdrawals**
  - Non-winning bidders can reclaim their deposits at any time after being outbid.  
- **Finalization**
  - Once the auction ends, the owner finalizes and receives the winning deposit.  



