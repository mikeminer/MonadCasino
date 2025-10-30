🎰 Monad Casino by pappardelle.eth ( 0x5d69c42a3a481d0ccfd88cfa8a2a08e2bf456134 ) 
The On-Chain Slot Machine on Monad Testnet - dapp link https://mikeminer.github.io/MonadCasino/

Welcome to Monad Casino, a neon-soaked one-page dApp where every pull of the lever is a real blockchain transaction.
Select a deployed contract, connect your wallet, spin the reels, and settle on-chain with glorious finality.

💥 Three of a kind? JACKPOT EXPLOSION (visual only — this is Testnet, degen!)

🚀 Live Features

✅ Slot machine UI with animated reels
✅ Connect wallet (MetaMask / Rabby / Backpack EVM)
✅ Network auto-switch/add → Monad Testnet
✅ Select deployed contract (list or custom address)
✅ On-chain message + tip (MON token) support
✅ Cooldown feedback to prevent spam
✅ Real-time stats:

Total spins

Your spins

Cooldown remaining

Tips bank balance

✅ Event listener shows live spins from others
✅ Confetti & SFX for JACKPOT moments 🎉
✅ Responsive neon design, ✔️ mobile friendly

🧠 Smart Contract

This frontend is designed for the BigButton Solidity contract:

function press(string message_) external payable;


It tracks:

Global press count

User press count

Tip balance

Cooldown per user

🔗 Supported Deployments (Monad Testnet)

You can switch between multiple instances:

Label	Address
Machine 1	0xe13b3F32F74b3E743a11a2ff09802f09d4590507
Machine 2	0x335f7CdB18a5a97A0b7ca45b90259F30AC76018c
Machine 3	0x12B935E6DD40bA7Ca36b0478cFC50Bed98b297c8
Machine 4	0x89B32D4cd09559e2Ee9D0b86efe6f49e76b31BfD
Machine 5	0x369C93465de307657095db22FEF416a369446874
Machine 6	0x6238f423e47289822AAFB953069702c43b574b21
Machine 7	0x634999f40d8Bb6d83d1B79c98a1a73E51Fd3247d
Machine 8	0x2e15e935521E22d344B300E63ED4019E07A463Ab
Machine 9	0xE6D77a6450D1d144C42a18FDc0a5F8f4AA602590

You may also manually paste a custom address.

🛠️ Tech Stack
Layer	Tools
UI	Vanilla HTML + CSS + JS (no build step needed)
Web3	ethers.js v6 (ESM CDN import)
Network	Monad Testnet
Wallet	Any EVM wallet supporting chain switching
📦 Installation

Clone the repo:

git clone https://github.com/mikeminer/monadcasino.git
cd monadcasino


Just open index.html in your browser — no server needed ✅

Or run a tiny web server (optional):

npx serve .

🧪 Testnet Utilities

🔗 Explorer: https://testnet.monadexplorer.com/

💧 Faucet: https://faucet.monad.xyz/

🧑‍🎨 UI Preview

Pull the lever → send press(...) on-chain
Your fate is in the mempool’s hands 🎲


(optional image placeholder — add later)

🧨 Roadmap

Leaderboard for biggest degens

“High Roller Room” multiple-lever mode

Jackpot payout (maybe 😉)

Slot symbol NFT mints

Localization: 😂 🇮🇹 🇪🇬

🙏 Credits

Created by Michele Angelo Forlani
Big brain degen. Always pressing forward.

⚠️ Disclaimer

This is a testnet entertainment project.
No real value is involved.
Even the JACKPOT is imaginary.
But the fun is real. 😎
