<div align="center">

```
███████╗██╗   ██╗██████╗ ██╗   ██╗ █████╗ 
██╔════╝██║   ██║██╔══██╗╚██╗ ██╔╝██╔══██╗
███████╗██║   ██║██████╔╝ ╚████╔╝ ███████║
╚════██║██║   ██║██╔══██╗  ╚██╔╝  ██╔══██║
███████║╚██████╔╝██║  ██║   ██║   ██║  ██║
╚══════╝ ╚═════╝ ╚═╝  ╚═╝   ╚═╝   ╚═╝  ╚═╝
```

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=Smart+Contract+Engineer;EVM+%7C+Ethereum+%7C+Blockchain+Dev;DevRel+%7C+Web3+Educator;25K%2B+Dev+Community+on+Instagram" alt="Typing SVG" />

<br/>

> 🚀 **Open to work** — Actively looking for **Smart Contract Engineering** and **DevRel** roles in Web3.
> If you're building something interesting on EVM — [let's talk.](mailto:suryasingu008@gmail.com)

<br/>

[![Instagram](https://img.shields.io/badge/Instagram-25K%2B_Followers-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/surya_code)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/contactsuryasingu)
[![Portfolio](https://img.shields.io/badge/Portfolio-Live-00D4FF?style=for-the-badge&logo=vercel&logoColor=white)](https://surya-code.vercel.app)
[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@surya_codeyt)
[![Twitter](https://img.shields.io/badge/Twitter-Follow-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/surya_singu)
[![Email](https://img.shields.io/badge/Email-suryasingu008%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:suryasingu008@gmail.com)

</div>

---

## ⚡ Who Am I

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.24;

contract SuryaSingu {
    string public name     = "Surya Singu";
    string public role     = "Smart Contract Engineer & DevRel";
    string public location = "Bengaluru, India";
    string public focus    = "EVM | Ethereum | DeFi | ZKP | Chainlink";

    string[] public stack  = [
        "Solidity", "Foundry", "Chainlink VRF", "Chainlink Automation",
        "Ethers.js", "Web3.js", "Python", "TypeScript", "Node.js"
    ];

    function mission() external pure returns (string memory) {
        return "Build trustless systems. Educate the next wave of Web3 devs.";
    }
}
```

---

## 🛠️ Tech Stack

<div align="center">

**Blockchain & Web3**

![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=for-the-badge&logo=ethereum&logoColor=white)
![Chainlink](https://img.shields.io/badge/Chainlink-375BD2?style=for-the-badge&logo=chainlink&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-000000?style=for-the-badge&logo=ethereum&logoColor=white)
![Hardhat](https://img.shields.io/badge/Hardhat-FFF04D?style=for-the-badge&logo=hardhat&logoColor=black)
![Web3.js](https://img.shields.io/badge/Web3.js-F16822?style=for-the-badge&logo=web3dotjs&logoColor=white)
![Ethers.js](https://img.shields.io/badge/Ethers.js-2535A0?style=for-the-badge&logo=ethereum&logoColor=white)

**Languages & Tools**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Cryptography**

![ZKP](https://img.shields.io/badge/Zero_Knowledge_Proofs-6C3483?style=for-the-badge&logoColor=white)
![SHA256](https://img.shields.io/badge/SHA--256-2C3E50?style=for-the-badge)
![secp256k1](https://img.shields.io/badge/secp256k1-1ABC9C?style=for-the-badge)
![Keccak256](https://img.shields.io/badge/Keccak256-E74C3C?style=for-the-badge)

</div>

---

## 🏗️ Featured Projects

### 💰 Foundry DeFi Stablecoin
> Over-collateralized, USD-pegged stablecoin — **MakerDAO-inspired DSC protocol**

- Accepts only exogenous collateral (WETH + WBTC) with health-factor based borrowing limits
- Algorithmic mint/burn logic via `DSCEngine.sol` with on-chain liquidation incentives
- `OracleLib.sol` halts the system if Chainlink price feeds go stale — safety first
- Full test coverage: deterministic unit tests + **stateful fuzz + invariant suites** with a custom handler
- CI/CD pipeline via GitHub Actions

`Solidity` `Foundry` `Chainlink Price Feeds` `DeFi` `ERC20` `Fuzz Testing` `Invariant Testing`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/surya00008/foundry-defi-stablecoin)

---

### 🎰 Foundry Smart Contract Lottery
> Provably fair on-chain raffle — **zero trusted intermediaries**

- Users enter by paying an entrance fee; winner gets the full prize pool
- Randomness powered by **Chainlink VRF v2.5** — cryptographically verifiable
- Fully automated draws via **Chainlink Automation** (`checkUpkeep` / `performUpkeep`)
- CEI pattern enforced throughout for reentrancy safety
- Deployed & verified on Sepolia testnet

`Solidity` `Foundry` `Chainlink VRF v2.5` `Chainlink Automation` `Ethereum` `Solmate`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/surya00008/foundry-smart-contract-lottery)

---

### 🔐 Zero Knowledge Proof Cryptographic System
> Python ZKP authentication — **prove a secret without revealing it**

- Schnorr-like protocol using the discrete logarithm problem on a 256-bit prime (secp256k1)
- Two real-world use cases: **password authentication** + **digital forensics / file integrity**
- Sub-1ms proof generation and verification times; 100% authentication accuracy
- Interactive Streamlit UI + CLI demo + attack simulation module
- University capstone project @ GITAM

`Python` `Schnorr Protocol` `ZKP` `secp256k1` `SHA-256` `Streamlit` `Cryptography`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/surya00008/zero-knowledge-proof-system)

---

## 🌍 Community & Content

<div align="center">

```
┌──────────────────────────────────────────────────┐
│            @surya_code  ·  Instagram             │
│                                                  │
│   👥  25,000+ Followers                          │
│   📈  Grown organically in under 6 months        │
│   🔥  Posts hitting 1M+, 420K, 343K views        │
│                                                  │
│   Dev tips · Smart contracts · AI/Tech news      │
│   Web3 careers · Student advice                  │
└──────────────────────────────────────────────────┘
```

[![Instagram Community](https://img.shields.io/badge/@surya__code-25K%2B_Devs-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/surya_code)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=surya00008&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=surya00008&layout=compact&theme=tokyonight&hide_border=true" />

<br/>

![GitHub Streak](https://streak-stats.demolab.com?user=surya00008&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

*"Blockchain is my arena, where code and consensus clash to create unstoppable systems."*

</div>
