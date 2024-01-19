# INSC+

### Overview

As is widely acknowledged, **INSC** represents the first-ever inscription on the Ethereum **Virtual Machine (EVM)** in history. It innovatively employs smart contract event data to store inscription information, thereby ensuring its permanent presence on the Ethereum blockchain. Moreover, this approach guarantees decentralization and significantly enhances the programmability of inscriptions, unlocking a broader spectrum of application scenarios.

**INSC**, as an experimental product 🧪, was quite successful. However, since it had never been tested nor audited by any third-party auditing firm, the experiment eventually exploded 💥, resulting in injuries to many people. From another perspective, the results of this experiment suggest that the new EVM inscription ecosystem could potentially flourish. Users have shown immense interest and enthusiasm for INSC, which has far exceeded our expectations.

To further promote the prosperity of the EVM inscription ecosystem, we are about to launch **INSC Plus(INSC+)**. **INSC+** is the first practical application of [**ERC7583**](https://github.com/insevm/ERCs/blob/master/ERCS/erc-7583.md) and the first perfect fusion of **ERC20** and **ERC721** tokens.

**INSC+** inherits the characteristic of using EVM's Event data to store inscription data. And it allows for the coexistence of both ERC721 and ERC20 token feature and functionalities. Users will be able to trade INSC+ simultaneously on Opensea and Uniswap.

We have conducted comprehensive testing on **INSC+** and invited third-party audit firm to audit **INSC+**. To prevent others from stealing our hard work, the contract code and audit report will be published before the activation of **INSC+** inscriptions.

As you might imagine, **INSC+** will pioneer a new form of asset, completely breaking down the barriers between fungible tokens (FT) and non-fungible tokens (NFT). This will link the prices in NFT markets with those in decentralized exchanges, leading to a new understanding of decentralized finance.



### What is an inscription in INSC+?

In this universe filled with light, people cannot directly see light in a vacuum. Light needs to strike an object for people to see the reflected light, distinguishing its color and shape. This material that receives and reflects light is termed a "vessel". Everyone possesses their own vessel, and "inscription" is a vessel in INSC+.

In 2 Kings 4, there's a story about a prophet's widow who, burdened with debt and her husband's death, only had a jar of olive oil left. She sought help from the prophet Elisha. Elisha instructed her to borrow empty vessels from all her neighbors, telling her "borrow not a few." The woman did so, and upon returning home, she poured her oil into these borrowed vessels until each was full. This oil was enough to pay her debts and sustain her and her children.

If it were you, how many vessels would you borrow? Initially, each inscription had a fixed quantity of 1000 FTs. You can trade inscriptions on the existing NFT marketplaces. The more inscriptions you have, the more FTs you possess. When the FT trading functionality is enabled, the FT balance of each inscription may vary.



### What is a slot in INSC+?

In simple terms, slot is a special inscription, and it is the first inscription received by each address. And among all inscriptions, the slot can only be transferred last. If you want to sell your slot, please make sure it is your last inscription. So, when you trade INSC+ on the NFT market, you may encounter some compatibility issues because existing NFT markets cannot identify whether your current Inscription is your Slot.

Slot is a vessel of FT, if you do not have a slot, you can not receive any FT, and only the FT balance in the slot can be transferred. When you want to transfer the FTs from your slot to a new address, an inscription with a balance equal to the transfer amount will be automatically minted for the new address as his slot. But, the max amount of inscriptions is 63000(21000 \* 3). If all inscriptions has been minted, the new address will need to purchase an inscription before receiving FTs.

### What is a slot in INSC+?

In simple terms, slot is a special inscription, and it is the first inscription received by each address. And among all inscriptions, the slot can only be transferred last. If you want to sell your slot, please make sure it is your last inscription. So, when you trade INSC+ on the NFT market, you may encounter some compatibility issues because existing NFT markets cannot identify whether your current Inscription is your Slot.

Slot is a vessel of FT, if you do not have a slot, you can not receive any FT, and only the FT balance in the slot can be transferred. When you want to transfer the FTs from your slot to a new address, an inscription with a balance equal to the transfer amount will be automatically minted for the new address as his slot. But, the max amount of inscriptions is 63000(21000 \* 3). If all inscriptions has been minted, the new address will need to purchase an inscription before receiving FTs.

### How to use the FTs in INSC+?

Earlier, we learned that only the FTs in the slot can be transferred, while the FTs from other inscriptions cannot. However, the inscriptions themselves can be transferred, so you can sell your FTs by selling the entire inscription.

Additionally, there is another method related to a story. Jesus performed many miracles during his time on Earth, and the first miracle was turning water into wine, just like turning the FTs in inscriptions into FTs in the slot.

You can use the waterToWine function to merge the balances of all your inscriptions into your slot. You can also distribute FTs from your slot into one of your inscriptions. That's pretty cool, isn't it! Now you can drink wine in your slot lol...

### FTs are highly valuable, NFTs are extremely valuable, and INSC+(Inscription) is the sum of both.
