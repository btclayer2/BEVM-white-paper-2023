# [BEVM-white-paper-2023](https://github.com/btclayer2/BEVM-white-paper/blob/main/BEVM%20%E2%80%94%20An%20EVM-compatible%20Bitcoin%20Layer%202.pdf)

## BEVM Development Phases
The development of BEVM has undergone a deep reflection on the core design concepts of Bitcoin and Ethereum, and has gradually formed the current paradigm through multiple technical explorations.
### 1. BTC Layer2 Exploration
- **Goal**: Address Bitcoin’s limited scalability by using Layer2 solutions to improve transaction throughput.  
- **Lessons Learned**: While technically feasible, Layer2 solutions lacked strong ecological demand, meaning they did not fundamentally change Bitcoin’s usage or achieve broad adoption.  
- **White Paper**: 
  - [BTC Layer2 White Paper(English)](https://github.com/btclayer2/BEVM-white-paper-2023/blob/main/BEVM%20%E2%80%94%20An%20EVM-compatible%20Bitcoin%20Layer%202.pdf) 
  - [BTC Layer2 White Paper(Chinese)](https://github.com/btclayer2/BEVM-white-paper-2023/blob/main/BEVM%E7%99%BD%E7%9A%AE%E4%B9%A6.pdf)

### 2. Taproot Consensus
- **Innovation**: Combined Bitcoin SPV state channels with Taproot technology to enable decentralized custody and expand Bitcoin’s smart contract capabilities.  
- **Reflections**: Bitcoin (BTC) is already widely adopted as a currency in centralized exchanges and mining pools, with relatively limited demand for decentralization-based expansion. What truly requires enhancement is Bitcoin’s consensus mechanism rather than BTC’s monetary function alone.  
- **White Paper**: 
  - [Taproot Consensus White Paper(English)](https://github.com/btclayer2/Taproot-Consensus/blob/main/Taproot%20Consensus%20yellow%20paper.pdf)
  - [Taproot Consensus White Paper(Chinese)](https://github.com/btclayer2/Taproot-Consensus/blob/main/Taproot%20Consensus%20%E9%BB%84%E7%9A%AE%E4%B9%A6.pdf)

### 3. SuperBitcoin
- **Direction**: Proposed a new crypto system that shares the security advantages of Bitcoin’s consensus.  
- **Limitations**: Improved consensus security but did not solve the “dreamworld disconnection” in Ethereum-like VMs. Such systems run only within their internal liquidity environment and lack the ability to perceive and interact with real-world data and states.  
- **White Paper**: 
  - [SuperBitcoin White Paper(English)](https://github.com/btclayer2/SuperBitcoin/blob/main/Super%20Bitcoin%20Whitepaper.pdf)
  - [SuperBitcoin White Paper(Chinese)](https://github.com/btclayer2/SuperBitcoin/blob/main/Super%20Bitcoin%20%E4%B8%AD%E6%96%87%E7%99%BD%E7%9A%AE%E4%B9%A6.pdf)

### 4. BitAgere
- **Problem**: Identified parallels between Bitcoin’s mechanical consensus and AI Agents’ abstract cognition, leading to the concept of BitAgere.  
- **Innovation**: Based on SuperBitcoin, focused on solving mechanical consensus’ perception gap. AI Agents’ input-sensing capability is abstracted and connected on-chain, enabling crypto systems to have real-world perceptive power. This deep integration of Crypto and AI Agents forms the basis for BitAgere.  
- **White Paper**:  
  - [BitAgere White Paper (English)](https://github.com/BitAgere/BitAgere_WhitePaper/blob/main/docs/BitAgere_A_multi-dimensional_Agere_interconnection_system_based_on_Bitcoin.pdf)
  - [BitAgere White Paper (Chinese)](https://github.com/BitAgere/BitAgere_WhitePaper/blob/main/docs/BitAgere_一个以Bitcoin为底层的多元Agere互联系统.pdf)  

### 5. BEVM(λ) Paradigm
- **Discovery**: Through introspecting Bitcoin’s design philosophy, we formulated the BEVM(λ) paradigm. It provides systemic theoretical guidance by examining Bitcoin’s success from four core aspects: the Individual model, lambda calculus, consensus algorithm, and consensus-aware algorithm.  
- **Direction**: BEVM(λ) inherits Bitcoin’s principles of energy conservation and decentralized emergence while enhancing autonomy and intelligence. Powered by the Agere subsystem and supported by distributed stateless computation and consensus-aware algorithms, BEVM(λ) paves the way for diverse future applications and the comprehensive development of intelligent crypto systems.  
- **White Paper**:
  - [BEVM(λ) White Paper(English)](https://github.com/btclayer2/Agere-Consensus/blob/main/docs/Agere_Consensus_Intelligent_Cryptocurrency_Design_Based_on_BEVM.pdf)
  - [BEVM(λ) White Paper(Chinese)](https://github.com/btclayer2/Agere-Consensus/blob/main/docs/Agere%E5%85%B1%E8%AF%86_%E5%9F%BA%E4%BA%8EBEVM(%CE%BB)%E7%9A%84%E6%99%BA%E8%83%BD%E5%8A%A0%E5%AF%86%E8%B4%A7%E5%B8%81%E8%AE%BE%E8%AE%A1.pdf)
# Contributing
Contributions are welcome! Join the discussion or submit issues and pull requests to help refine BEVM(λ) and Agere Consensus.

# License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.



Finished in 29/11/2023, by BEVM Foundation  
"5507 days ago, on October 31, 2008, the Bitcoin whitepaper was released.  
5507 days later, on November 29, 2023, the Bitcoin Layer 2 solution BEVM unveils its whitepaper!The era of Bitcoin Layer 2 and BEVM has arrived!  
Bitcoin took over a decade to reach a trillion-dollar Market Cap".  
**How long will it take for BEVM to achieve the same milestone?**  
  
BTC commands nearly 50% of the cryptocurrency market share, yet since its inception, Bitcoin has lacked a mature Layer 2 (L2) solution. Following key technological upgrades such as Segwit and Taproot, along with the popularity of the Ordinals protocol and BRC20 tokens, a fully decentralized, EVM-compatible Bitcoin Layer 2 solution, BEVM, has been introduced, using Bitcoin as its gas.

## The Positioning of BEVM  
BEVM is a decentralized and EVM-compatible Bitcoin Layer2 using BTC as Gas.  
BEVM is based on technologies such as the Schnorr's signature algorithm, brought about by the Taproot upgrade, allowing BTC to cross-chain from Bitcoin mainnet to Layer 2 in a decentralized approach. Since BEVM is compatible with EVM, it allows all DApps which can run in the Ethereum ecosystem to operate on BTC Layer 2, with BTC serving as Gas.  
## The Background of BEVM's Inception 
1. SegWit and Taproot Upgrades. The birth of BEVM is entirely based on Bitcoin's 2017 SegWit upgrade and the 2021 Taproot upgrade. The SegWit upgrade allowed Bitcoin blocks to accommodate larger data. The Taproot upgrade not only allowed the expanded space to contain more complex data but also introduced the Schnorr's signature algorithm, making decentralized Bitcoin multisig a reality. This, in turn, enabled decentralized Bitcoin cross-chain operations, and ultimately, decentralized BTC Layer2 became a reality. BEVM is the best example of a decentralized BTC Layer2.
The SegWit and Taproot upgrades have once again made Bitcoin great, evolving Bitcoin from the 1.0 era to the Bitcoin 2.0 era, allowing us to see a richer Bitcoin ecosystem.
2. The Explosion of Token Launch Protocols on Bitcoin like Ordinals in 2023
The explosion of Token Launch Protocols on Bitcoin such as Ordinals in 2023 is a result of Bitcoin's SegWit and Taproot upgrades. It has shown the Bitcoin community that issuing assets based on Bitcoin has become possible. Issuing assets is just the first step; a richer and more diverse ecosystem of applications needs to be established on BTC Layer2. Therefore, BEVM was born.
3. Six Years of BTC Layer 2 Exploration by the BEVM Team. The BEVM team has been exploring Bitcoin Layer 2 since 2017. In 2018, the BEVM team's BTC Layer 2, ChainX, achieved 100,000+ BTC cross-chain, but due to industry development, ChainX did not experience a real explosion. In 2021, Bitcoin completed the Taproot upgrade, making real decentralized cross-chain possible for BTC. Therefore, the BEVM team began to build BTC Layer2 based on the Taproot upgrade. In 2023, the explosion of Bitcoin issuance protocols like Ordinals showed the BEVM team that a new era of the Bitcoin ecosystem was coming. Thus, they launched the BEVM pilot network and planned to launch the mainnet in Q1 2024.

   
## The Vision and Market Space of BEVM

### BTC EVM  
Building a decentralized  BTC Layer2 that uses BTC as Gas and is compatible with EVM, enabling various applications from the EVM ecosystem to be seamlessly and easily deployed on BEVM, thereby increasing the use and consumption scenarios for Bitcoin. To better maintain the security of the Bitcoin network, BEVM will launch BEVM - Stack in the future, which will help developers and Bitcoin projects with high throughput demands to build their own BTC Layer 2.  
### BTC to VM  
BEVM plans to build the DBFX Protocol, a decentralized Bitcoin "foreign exchange system," aimed at introducing Bitcoin(digital gold) into any chain and ecosystem. It aims to help various blockchains and Layer 1 increase their Bitcoin foreign exchange reserves and enhance their monetary credibility. In our view, although WBTC allows Bitcoin to circulate within the EVM ecosystem, it is an asset produced by centralized institutions and contradicts the decentralized philosophy of Bitcoin. By using the DBFX protocol, BEVM enables native BTC to circulate between any chains, allowing users to truly have control over their Bitcoin assets on any chain (being able to freely redeem and generate native Bitcoin on any chain).

## BEVM Whitepaper NFT Launch
5507 days since the Bitcoin whitepaper, BEVM, an EVM-compatible Bitcoin Layer 2 innovation, announced its whitepaper on November 29, 2023. To mark this significant milestone, BEVM introduced a commemorative collection of 10,000 NFTs on the Bitcoin network, based on the innovative [Ordinals protocol](https://github.com/ordinals/ord).

### NFT Details:
* Quantity: Limited to 10,000 NFTs.
* Availability: Offered on a first-come, first-served basis, with validity ceasing once the limit is reached.
* Activation Block: The distribution starts from Bitcoin block number 819249.
* Value Proposition: The NFTs are solely commemorative, devoid of any intrinsic monetary value.

### Participation Process:
1. **Downloading the NFT**: Users can view and download the SVG file of the NFT by visiting [this GitHub page](https://github.com/btclayer2/BEVM-white-paper/blob/main/bevm-whitepaper-nft.svg). Once on the page, click on "Download raw file". 
2. Enthusiasts have the option to mint these NFTs on platforms like Unisat.
