🪙 BidAndWin - Token-Based Raffle Auction
📖 Overview

BidAndWin is a Solidity smart contract that simulates a raffle-style auction.
Participants register, receive tokens, and use them to bid on items. Each token acts as a raffle ticket — the more you bid, the higher your chance to win.
Finally, the contract owner randomly selects one winner per item.

⚙️ Features

Register and get 5 tokens

Bid tokens on 3 available items

Randomly selected winners (one per item)

Ownership controlled by onlyOwner modifier

Check bidder details anytime

🧠 How It Works

Deploy → The deployer becomes the contract owner (beneficiary).

Register → Each user gets 5 tokens.

Bid → Spend tokens to bid on items (bid(itemId, count)).

Reveal Winners → Owner calls revealWinners() to pick random winners.

Each token = one raffle entry. More tokens = higher winning chance.

🧩 Key Concepts

Uses structs, mappings, and arrays

Demonstrates ownership, require checks, and random selection logic

Educational project (not for real-world use)

⚠️ Limitations

Randomness via block.number (not secure)

Fixed bidders (4) and items (3)

No actual ERC20 or Ether transfer

🛠 Tools

Solidity ^0.4.17

Remix IDE / Foundry

MetaMask for testing

👨‍💻 Author

Shiva Nageshwar
Blockchain Developer | Smart Contract Enthusiast

🏷️ License

MIT License – Free to use and modify.
