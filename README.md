Myth Sentinels is a play-to-earn strategy game where players summon, train, and battle unique
Sentinel NFTs. Players earn tokens through victories, stake to unlock bonuses, and trade assets
in a decentralized marketplace. The entire gameplay loop — minting, battling, trading, and
governance — is built on OG Chain for fairness and transparency.

🔹 The problem it solves

● Ownership & Trust: Traditional games keep assets locked in centralized servers. Myth
Sentinels gives players true ownership of Sentinels, items, and achievements as NFTs.
● Verifiable Battles: Most blockchain games struggle to prove fairness in gameplay. With
OG Compute + OG DA, every battle outcome is transparent and verifiable.
● Sustainable Play-to-Earn: Many P2E games inflate rewards unsustainably. Myth
Sentinels uses staking + DAO governance to create a long-term, community-driven
economy.

🔹 Challenges 

● Designing fair PvP battles that balance strategy and randomness while still being
computationally efficient on OG Compute.
● Storing dynamic Sentinel evolution data on OG Storage without bloating metadata.
● Ensuring smooth user onboarding for non-crypto players who aren’t familiar with OG
Chain wallets and transactions.
● Creating a reward system that avoids token inflation while still keeping battles and
staking attractive.

🔹 Technologies I used
● OG Chain → smart contracts for NFT minting, staking, governance, and marketplace
logic.
● OG Storage → Sentinel NFT metadata, battle logs, evolution history, and tournament
data.
● OG Compute → PvE/PvP battle simulations, ranking logic, seasonal scoring.
● OG DA → verifiable logging of gameplay events and Sentinel progression.
● NFT Standards → for Sentinel character minting and upgrades.
● Smart Contracts (Solidity / CosmWasm depending on OG stack support) → for staking,
battles, and governance.
● Frontend (Next.js / React) → for UI (minting, battles, staking dashboard).

🔹 How we built it
1. Started with Sentinel NFT contract on OG Chain (base stats + attributes).
2. Linked NFT metadata to OG Storage, so each Sentinel has a persistent history.
3. Implemented staking mechanics on OG Chain for token holders.
4. Developed basic PvE battles using OG Compute to simulate encounters.
5. Connected the backend logic with a minimal UI, allowing users to mint Sentinels, stake
tokens, and join battles.
6. Logged battle outcomes and player progression with OG DA for transparency.

🔹 What we learned

● How to leverage the full OG stack (Chain, Storage, Compute, DA) to build a game that is
both fun and verifiable.
● Balancing game design + tokenomics is critical — playability must come first, rewards
second.
● User experience on blockchain gaming still has friction; abstracting transactions and
onboarding are key.
● DAO-driven governance can actually improve gameplay balance when players
collectively vote on updates.

🔹 What’s next for Myth Sentinels
● Expand PvP battles with ranked matchmaking powered by OG Compute.
● Launch the Sentinel Marketplace on OG Chain for trading characters and upgrades.
● Add seasonal tournaments, distributing prize pools transparently via smart contracts.
● Roll out NFT badge achievements tied to on-chain performance.
● Expand governance, letting OG token holders shape new Sentinel classes, abilities, and
gameplay mechanics.
