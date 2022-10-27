# Wolf.Game 

## Overview and Origin

   - **Wolf game V1**: Wolf Game is an Ethereum-based game and NFT risk protocol. The game consists of a variety of NFTs that act as the game pieces, with wolves being the most valuable. The first rendition of the game was silently released on November 18th, 2021. Within hours of the stealth drop, the first 10,000 game peices (sheep and wolves) were minted out at a price of .069420 Eth ($295) each. When minting you had a 90 percent chance of getting a sheep and a 10 percent chance of getting a wolf. Right after the mint you were able to stake your sheep and wolves to the barn (staking contract) where the sheep produced an ERC-20 token called $WOOL (10,000 $WOOL a day) and the wolves collected a tax (20%) when the sheep wanted to claim their $WOOL. If the sheep decided to unstake from the barn contract they had a 50 percent chance of getting all their $WOOL and a 50 percent chance that a random wolf (based on rarity) would steal all their $WOOL. Once you accumulated 20,000 $WOOL you were able to mint the next generation of wolves and sheep (gen 1). You still had only a 10 percent chance of getting a wolf and 90 for a sheep. But there was an added risk to minting with $WOOL; There was a 10 percent chance that your sheep or wolf got stolen by a random wolf. 

   <img src="https://openseauserdata.com/files/56c31a758486884f3563a6f96decdec7.svg" alt="drawing" width="200"/> <img src="https://openseauserdata.com/files/04a1b1226f3c9d501e159e57d146c726.svg" alt="drawing" width="200"/> <img src="https://openseauserdata.com/files/bb50ca338d656e73b1cbb739e207beec.svg" alt="drawing" width="200"/> <img src="https://openseauserdata.com/files/adf35f79fe3121f6b9dc27761b79e744.svg" alt="drawing" width="200"/>

   - Wolf Game was created by an anonymous developer who goes by the name "The Shepherd"

   <img src="https://wolf.game/images/shepherd.gif" alt="drawing" width="200"/>
  
   - From **Whitepaper V1**: "Wolf Game is a risk protocol for NFTs with novel tokenomics. It shows what’s possible with interactions between the ERC-20 and ERC-721 protocols. For the very first time, your NFT can steal other NFTs (ERC-721 tokens) for you. The rarer your NFT, the more tokens you'll accumulate probabilistically. Wolf Game is pioneering new types of NFT mechanics. Fully decentralized. No roadmaps or empty promises. Just a game in the metaverse that’s ready to play at launch."
   
   - On the 21st of November an exploit was found that allowed players to mint only wolves. This lead to the contract being paused and a new contract being created that patched the vulnerability. Players had to migrate their sheep and wolves to the new contract on the wolf.game website which locked their original assets and created an exact copy of the legacy NFT. This lead to the question of what to do with all the $WOOL that was not able to be claimed. The Shepherd came up with a novel solution: the WOOL pouch. WOOL pouches are an ERC-720 token (NFT) that release an ERC-20 token ($WOOL) over a 4 year peiod at a constant rate, and the $WOOL can be claimed by the owner at any time.

   - **Wool Pouch**: From the V2 whitepaper: "The Shepherd had intended to bring 40,000 Gen 1 Sheep & Wolves onto the farm, which would have required burning 1.8 billion WOOL. With only 3,809 minted, this left a large oversupply of an extra 1.7 billion WOOL that would have been immediately available. He chose to leverage sensible tokenomics to maintain the game's integrity, protect all Sheep & Wolves, and keep WOOL safe. WOOL Pouches are his invention to solve this: they are ERC-20 tokens that are stored within tradable NFTs. All Gen 0 and Gen 1 Sheep & Wolves, whether staked or unstaked, are eligible to receive a WOOL Pouch."
    
   - <img src="https://openseauserdata.com/files/1736552df0db8dc51bf8cf7b254f512e.svg" alt="drawing" width="200"/>
    
  -  **Risky Game**: The Shepherd decided to make pouch claiming a little bit more interesting by adding a risky element that players could opt into. Sheep were given two options: The no risk option, where they could simply claim a pouch with the amount of $WOOL they accumulated in the Barn up until the migration began (45,000-70,000 $WOOL). Or they could opt into the risky option where your sheep had a 50 percent chance of walking away with no pouch and a 50 percent chance of obtaining a much larger pouch (about 280,000 $WOOL). All wolves were guaranteed a pouch of at least 300,000 $WOOL with the higher rarity wolves getting pouches in the 600,000 to 700,000 range.

- <img src="https://wolf.game/images/risky-game.gif" alt="drawing" width="200"/>


- **Land mint**: Land was introduced shortly after the exploit to show the Shepherd had a long term vision for the project. Land is where the full game (dropping Q4 2022) will take place. "Build your domain. Prosper off the land. Only 20,000 genesis land plots will ever exist. Each is unique, with varying acreage, and capabilities. Cultivate assets in your quest for economic dominance." Out of the 20,000 land parcels, 10,000 were claimable for free (+ gas fees) to all the gen 0 sheep and wolves, and 10,000 were dutch auctioned starting at .69 and ending at .1, with a majority being sold between .15-.2. This meant that the Shepherd recieved about 1500 Eth or $5,850,000 in funding to continue developing the game.

  ![land](https://pbs.twimg.com/profile_banners/2384035274/1645663089/1500x500)
- **Farmer mint**: Farmers were introduced as a multiplier to lands. "Farmers assist you in managing your land more efficiently. You will be able to harvest more resources and get further faster with the help of farmers. Every farmer has a unique set of skills which match some plots of land better than others. Farmers are not required to own and operate your land, but they are beneficial for optimal gameplay." To obtain a farmer you had to burn 10,000 $WOOL. The Shepherd had planned on having 20,000 farmers but cut it short at 11738 which made farmers almost twice as rare as initially planned. The farmer mint burned (sent to dead address) 117,380,000 $WOOL.
- <img src="https://wolf.game/images/farmer.gif" alt="drawing" width="200"/> <img src="https://wg-farmers.s3.us-east-2.amazonaws.com/0x26f844be-animated.gif" alt="drawing" width="200"/> <img src="https://wg-farmers.s3.us-east-2.amazonaws.com/0x9513d3ca-animated.gif" alt="drawing" width="200"/> <img src="https://wg-farmers.s3.us-east-2.amazonaws.com/0xb564859d-animated.gif" alt="drawing" width="200"/>
---

- **Alpha Game**: The Shepherd needed a way to keep people engaged as he develops the Full Game. Alpha Game was his solution. He contacted each of the 12 alpha 8 wolves (rarest asset in the game) to each run a pack where people could stake their assets into for a tempting prize of $WOOL. "Alphas have one way to gather Points for their Pack: encourage other Wolves and Sheep to stake into their Pack. A Wolf or Sheep can be part of only one Pack at a time. However, they may choose to switch Packs at anytime, with a cost. Each "Sheep or Wolf staked in a Pack contributes a certain number of Points daily to its Pack: 
Sheep	50
Omega Wolf (A5)	250
Delta Wolf (A6)	360
Beta Wolf (A7)	490
Alpha Wolf (A8)	0. Alphas do not contribute points to their Pack."

- You are also able to stake $WOOL to a specific pack which increases their amount of actions. "Alphas, the leaders of each Pack, are uniquely able to utilize these Actions to Fortify their Pack or Attack other Packs: the Pack’s Alpha must utilize its Action before the Pack will continue to earn more Actions."
Two actions: 
1. Attack another Pack of their choice to reduce that Pack’s overall Points count by 3% unless they have Fortifications.
2. Fortify to protect against Attacks. Fortification is proactive. By Fortifying, you increment your Fortifications.

 <img src="https://openseauserdata.com/files/4449be6885334bc6c917ebeafe8a9567.svg" alt="drawing" width="200"/> <img src="https://openseauserdata.com/files/28f7cee9cbd927d183ce3b52e301e786.svg" alt="drawing" width="200"/> <img src="https://openseauserdata.com/files/1831db19d68100fee8027b2eac47c5fe.svg" alt="drawing" width="200"/> <img src="https://openseauserdata.com/files/fd3c7762602c6f21f788c07e431a9fd6.svg" alt="drawing" width="200"/>
 
---
- **Cave Game**: 
Cave Game is an interactive real-time minigame that required a bit more strategy than Alpha Game. In this game, Sheep and Wolves were competing against other members in their packs to hunt for a finite supply of resources including Gems, $WOOL, Merch, and Relics. Each cave was sized proportionally to the size of the pack. "Sheep and Wolves have a finite amount of energy to utilize every 24 hours. Each step taken in the Cave (excluding Lobbies) uses one Energy. There is no requirement to utilize your steps at any point of the game, though Sheep and Wolves reach their maximum Energy 24 hours after depletion." 
- Sheep: 100 energy
- Alpha 5 Wolf: 125 energy
- Alpha 6 Wolf: 150 energy
- Alpha 7 Wolf: 175 energy
- Alpha 8 Wolf: 200 energy
- <img src="https://wolf.game/images/mountainHike.gif" alt="drawing" width="200"/>  <img src="https://wolf.game/images/sheep-begin.gif" alt="drawing" width="200"/>

-  **Gems**: Any Gems, Merch, or other NFTs discovered in the Cave may be immediately claimed on the blockchain (for a small gas fee). Gems and Merch are both ERC-1155 NFTs. Gems could be burned with an unrevealed farmer to gaurantee that a players farmer be rare upon reveal. "Gems come in 6 different Farmer Types. The 7th and most common Farmer Type is not represented as a Gem." "Traditionally, NFT reveals leave everything to chance: Users mint an unrevealed NFT The project creators click a magic button to reveal the NFT and its metadata."
- "Wolf Game is a competition. Players must compete for many aspects of the game, including the rarity and desirability of their Farmers."

- <img src="https://wolf.game/images/gems/daddy.gif" alt="drawing" width="200"/> <img src="https://i.seadn.io/gae/su5En5CUkNbD0XyPj7OjQH_AzgDt2sNSWsclRm9qyueSEpyebHO6U3hNafTlRd-lcWj8fjtQjGZxLgZ0DjBRIb4G59dR-EtgBdcPxg?auto=format&w=1000" alt="drawing" width="200"/>
---
## Business Activities
- The Shepherd's goal is to make everything into a competition. Traditionally when you stake your assets you get a pre-specified percentage and there is little to no risk. In Wolf Game the decisions that you make can dramatically affect your ROI.

- Today, Wolf Game Appeals to the gambler more than anyone because of the high-stakes high-reward aspect, but the Full Game will have something for everyone. It will have safer ways to play (passive elements: Land, Wool pouches and Wolves) and riskier options that players can opt into if they want to gamble (Sheep and possibly Farmers).
---

- Wolf Game introduced several **never-before-seen mechanics** to the NFT space including: 
 - NFTs stealing other NFTs: The Wolves kidnap newborn Sheep by any means necessary
-  NFTs taxing other NFTs: The Wolves know the power of $WOOL and show a pattern of taxing WOOL production
- The ability to mint and stake your NFTs in a single transaction
-  ERC-20 tokens in the shape of NFTs: WOOL Pouches
- Gamified staking: WOOL must be won
---
- **Technologies currently used**:
- "Everything in Wolf Game happens on-chain: the decisioning, the results, the generation of the NFTs themselves. It’s split between 4 different smart contracts so that anyone can read through and get a sense of how it all talks to each other."
- **Data Packaging**: "Storage is expensive on the blockchain! One 256 bit integer costs 20,000 gas to save, which at today’s costs is about $7.50… for one number! Efficiently packing data types by designing around smaller max values can save users hundreds of thousands of dollars over the lifetime of the project."
- **Constant time algorithms and DeFi Math**: "A lot of contracts use architectures that require significant looping to accomplish tasks. Those make contracts inefficient and add to gas costs. It’s imperative to remove things like the need to search through arrays or loop through stakes. This means you can do things like unlimited simultaneous stakes while keeping things cheaper.
As an example, the minting contract uses AJ Walker’s Alias Method to efficiently select traits in constant time. Another example: tracking Wolf $WOOL earnings (taxes) proved to be very complex, requiring math used by DeFi liquidity pool protocols."
- **100% On-chain**: "Not the first, and certainly not the last. But as long as Ethereum is running, your Sheep and Wolves will survive. Always available and always yours. Your traits and all the pixel art reside in the contracts themselves, nowhere else."
- **UI at launch**: "You can use the entirety of Wolf Game by directly interacting with the blockchain (like through Etherscan). But Wolf Game is launching with a custom UI to make it easy for people to enjoy the game on day 1."
---

## Landscape

- Wolf Game is a pioneer of the play-to-earn (P2E) gaming industry.

- Axie Infinity was the first P2E game to go mainstream but there were many problems within the ecosystem which led to a significant price decline in most of the assets.
- Ether Orcs is another 100% On-chain P2E game. "it is a role-playing game that is fully encoded on-chain.  Each EtherOrc holder can upgrade their weapons and gear through pillage pools, which in turn is reflected on the Orc's metadata. They can also stake their Orcs to one of two pools:
1. Training: Level up your Orc - The higher the level, the longer it takes to level up
2. Battle: Reap the spoils of war - The higher level your Orc, the more $TEEF token rewards you earn"
---

## Results

- Wolf Game has gained quite a bit of attention since it's inception back in November 2021.

- To measure the success of an NFT company you usually have to look at the floor price of the assets compared to the mint price:
- **Sheep** (Gen 0): Minted for .069 Eth ($250)-> Floor price today (09/25/22) .9 Eth ($1,160).
- **Wolves** (Gen 0): Minted for .069 Eth ($250)-> Floor price today 7.35 Eth ($9,576).
- **Land**: Minted for average price of ~ .15 Eth ($540)-> Floor price today .37 Eth ($490)
- Wolf Game has had steady volume and stable floor prices since it was created, even with the Full Game yet to be released.

---
## Recommendations

- If I were to advise Wolf Game my only suggestion would be to create their own marketplace with lower royalty fees. Currently all collections have creator royalty fees set at 6.9% (this means that 6.9 percent of every sale goes directly to the creators). If they were to create their own marketplace with fees around 2-4 percent, I believe it would lead to more people trading their assets and it would show investors that the team is very much community oriented.
- The technologies utilized for this marketplace are already being used for other NFT collections such as CryptoPunks. They have a site completely seperate from opensea where the royalties are set to 0%.


---
Sources: 
- https://wolf.game/whitepapers
- https://luckytrader.com/nft/ether-orcs
