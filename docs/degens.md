# rETH Education

## Table of Contents
1. [General Mission](#generalMission)
2. [What is rETH](#whatReth)
3. [Liquidity Pools (yield related)](#liquidity)
4. [Lending Protocols](#lendingProtocols)
5. [How does this all work?](#howDoesThisWork)
6. [Yield Aggregators](#yieldAggregators)
7. [Derivatives](#derivitives)
8. [Moving Forward](#movingForwards)

(The examples included therein illustrate an idea of possible use cases of rETH. Keep in mind that these are currently only hypothetical ideas, and some ideas may be impossible to implement)

### General Mission <a name="generalMission"></a>
Rocket Pool is the most decentralized and trustless pooled-staking protocol ever built on Ethereum. One key goal of the protocol is to greatly increase access to Ethereum staking by lowering technical and financial barriers to entry. Users receive the staked ETH wrapper token rETH, which is fully composable in the broader DeFi ecosystem while accruing value from ETH earned through proof-of-stake (PoS) ETH staking.

Compared to other staking protocols like Lido Finance and centralized staking-as-a-service (SaaS) providers like Coinbase, the rETH wrapper token is trust and risk minimized being supported by 100s to 1000s of operators, a natural building block for the next evolution of Ethereum.


### What rETH is and Why It Is Good For You <a name="whatReth"></a>

Users that stake with Rocket Pool receive rETH, which is Rocket Pool's liquid token equivalent of staked Ethereum.

When you are staking ETH, you are helping secure the network, and in return, you get ETH rewards. You can read more about the technical details of [proof-of-stake on ethereum.org]( https://ethereum.org/en/eth2/staking/).

Traditionally you needed 32 ETH + hardware to help secure the network as a validator, but with Rocket Pool, you can stake with as little as 0.01 ETH. This can be done because one party provides 16 ETH + the node hardware (called a Node Operator) to which the Rocket Pool smart contracts match an additional 16 ETH pooled from rETH stakers to create a full 32 ETH validator (a Rocket Pool validator is called a minipool).

For example: 
- 16 ETH Minipool from Node Operator
- 4 ETH Staker 
- 2 ETH Staker 
- 0.5 ETH Staker 
- 9.49 ETH Staker 
- 0.01 ETH Staker

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;↓
- 32 ETH validator

The individual staking with Rocket Pool pays the average protocol commission (expected to be ~10%) to the Node Operators for supporting and providing the hardware services. The grouping of ETH and the commission is all handled trustlessly by a smart contract; there is no manual human on the other side organizing any of this. The staker also does not have to worry that the individual minipool  their ETH has been assigned to performing bad since rETH returns are socialized across the entire Rocket Pool protocol. This is one of the strengths of Rocket Pool's open and decentralized design; rETH rewards are supported by 100s to 1000s of individual operators who are each incentivized to perform well due to their RPL bond.

When you stake ETH with Rocket Pool, you get back rETH in return. rETH is a token that represents your right to the future rewards for the ETH you staked. It holds its value by allowing you to swap back for rETH for your original ETH stake + accumulated ETH rewards. This opens a world of opportunities with rETH! With rETH, you can do anything you want in the Ethereum market because it’s not locked like ETH in traditional staking. You can trade your rETH for that NFT you know is going to 10x. You can borrow stables against you rETH to keep exposure to an ultra-ultrasound asset while pursuing other ventures. Perhaps you could even lend your rETH to generate yield on your yield. The Ethereum ecosystem is growing at a break-neck pace and rETH allows you to explore it while still contributing to securing the chain and earning rewards.

Rocket Pool believes that this system benefits both parties:
- Node Operators 
  - Get commission from the ETH stakers.
  - Get RPL rewards for being part of the smart contract.
- ETH Stakers
  - Liquidity! You can use your rETH token right away.
  - Only need 0.01 ETH or more to stake.
  - Pay a commission of ~10% to outsource hardware maintenance to the Node Operators. This is a lower, if not the lowest, commission rate in the market right now. 
  - Decentralized smart contract staking. You don't need to rely on humans on the other side for stealing your staked ETH; it's all managed by smart-contracts. Node Operators are also required to buy RPL tokens as an insurance mechanism for you! 

Staking and ETH and getting rewards is not some radical out-of-world idea that it may seem. In traditional finance, this would be very similar to buying a government bond. The government bond sets an interest rate (or coupon rate) and a maturity date. When the maturity date is up, you get the principal amount you paid for the bond as well as the interest that was set. 

There are a couple of subtle similarities between staking ETH and purchasing traditional government bonds. 
- In Rocket Pool, you get this bond as a form of rETH that can be traded in the free market; this is similar to buying and selling government bond ETFs. 
- The staked ETH in Rocket Pool is the same as any staked ETH. The Ethereum network uses 32 ETH to secure the Ethereum network. The money used to purchase a government bond, on the other hand, can be used for a variety of different things: financing projects, roads, military, etc. In Ethereum, this would be similar to dedicating all the staked ETH into a military security budget.

By showing you are dedicating 32 ETH, you are basically proving citizenship. Since you are a citizen of the Ethereum network, you are more incentivized to commit your services to the Ethereum network. Sovereign countries require you to be a citizen to serve in the military for obvious reasons. Ethereum is applying this same approach. (Side Note: this is one of the essential differences between proof-of-stake, which Ethereum will use, vs. proof-of-work blockchains). Currently, at the time of writing this article, Ethereum still uses proof-of-work to secure the network and will transition to proof-of-stake. This event is known as The Merge. Security was not a priority at the time of Ethereum's inception, which is why Ethereum outsourced their military services but will plan to bring security in-house after The Merge. Ethereum will use its citizens to secure the network.


The future of rETH adoption looks strong. Just by holding rETH, you automatically accrue staking rewards based on the performance of the Rocket Pool protocol by holding the other side of a minipool, essentially making you a stakeholder of an PoS ETH node. You have a liquid, automatically yield generating asset instead of an illiquid staked asset that cannot be withdrawn at will. The Merge event, which will transform Ethereum into a Proof-of-stake system, will add transaction fees to the staking rewards, which is expected to be much more than the average block reward. Validators will be in very high demand due to the increased chances of significant returns from running validators using Rocket Pool. This is because it's possible to run twice as many nodes using Rocket Pool compared to the default method of staking, which increases exposure to periods of high demand for block space, netting higher gains from users' transaction fees on the Ethereum network. Due to these increased incentives, on a long enough time frame, it is safe to assume staked ETH on Rocket Pool will comprise a vast majority of the validators on the consensus layer.

In such a scenario, rETH would be the default wrapper token to be utilized in DeFi due to the inherent reward mechanism baked into the protocol and its trustless nature. The beauty of our beloved wrapper token is that you can participate in Ethereum consensus while still being liquid. Therefore, users can use rETH in Defi the same way that ETH can be used, but with the added value that comes from staking. Moreover, it doesn't have the disadvantages of being an ETH2 validator, as you have no hardware to maintain and data connectivity you must worry about. rETH can be used in dApps from lending protocols and decentralized exchanges to yield aggregators and even derivatives on platforms that haven't even been conceived yet. Let's start with…


### Liquidity Pools(Yield on Yield on Yield) <a name="liquidity"></a>

![xzibit meme here](https://user-images.githubusercontent.com/7516245/141643550-eaa2e2aa-bc7e-4a14-84c8-c0182044574c.png)

One of the main ways in which stakers can use rETH is to combine it with the normal ETH token in a liquidity pool through a dApp such as Curve Finance or Sushiswap, which would allow liquidity providers to simultaneously accrue trading fees, liquidity mining rewards, as well as base rETH staking rewards.

~~Any LP APY would have to be at the bare minimum as much as the base staking rewards and with incentives could even be multiples of what you would otherwise get running an Ethereum validator.~~ (Idk what this is trying to say)

### Lending Protocols (Enabling Max Degeneracy) <a name="lendingProtocols"></a>
rETH permits users to borrow assets while simultaneously accruing PoS ETH rewards while being staked as collateral on lending protocols such as MakerDAO or Aave.

This could allow users to take out a loan that is, in essence, constantly paying off itself. If there is excessive demand to borrow rETH, suppliers can also earn a yield on their rETH as well, earning the PoS rate simultaneously with the variable lending rate.

Users could lend their rETH on lending protocols to borrow stable coins like USDC to yield farm while being exposed to the price action of the base Ethereum asset. This will essentially be double interest, as the USDC will generate yield along with the rETH generating rewards simultaneously.

Due to this, we may see a supercharged DeFi economy. With lending and supply percentage yields being dictated by the base return of rETH, this will form a floor APY for DeFi and be a catalyst for an explosive surge in real-world adoption and demand for the whole Ethereum ecosystem.

### How does this work? <a name="howDoesThisWork"></a> 

To be used as collateral, ETH must be wrapped, opening an added layer of efficiency and Defi composability with yield farming and borrowing.

Using rETH as collateral allows for advanced composable yield farming strategies where a natively yield-bearing asset can be used as collateral for an ETH loan.

The ETH can be swapped right back for rETH to add to the existing collateral as a leveraged long position with repaying margin fees.

Price fluctuations of the underlying collateral asset will still play a prominent role in determining a user's health ratio and liquidation risk. Although, this theoretically allows users - who stake rETH as collateral while borrowing a position - to gradually improve their position's health ratio while diminishing the possibilities of any unwanted liquidations.

### Yield Aggregators <a name="yieldAggregators"></a>

Aggregators like Yearn and Harvest can use rETH in their yield farming strategies as an additional yield layer on top of their current yield farming to obtain the highest yield possible for their users.

These strategies can utilize a variety of other protocols to generate this high yield, such as farming through liquidity mining incentives, earning yield through lending protocols (discussed above), earning yield through native protocol staking, etc.

### Derivatives <a name="derivitives"></a>

Synthetic-issuing protocols may allow rETH to be used as collateral to mint derivatives, similar to how lending protocols function. In this case, users will mint a synthetic liquid asset that tracks the underlying asset's performance that can even be unrelated to DeFi (e.g., Gold, Carbon Credits, TSLA).

Since synthetics have infinite liquidity, synthetic ETH can be pooled with rETH to allow for low slippage trades between the two assets. Synthetic swaps would allow for cross-asset trades between rETH to any supported derivative, with maintenance fees taken out of the base reward.


### Moving Forward <a name="movingForwards"></a>

Through the incentives given to stakers by Rocket Pool, and future versions of zk-rollups where transaction fees can be denominated in ERC-20 tokens, rETH may very well become the primary base token for DeFi when considering its advantages over plain ETH or wETH. It can be used both as a yield-bearing asset and as a tool to increase efficiency in other protocols. Compared to other staked wrapper tokens, Rocket Pool staked ETH is highly decentralized and trustless, which will also be a significant deciding factor in its adoption by the wider Defi community.
