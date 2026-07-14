# Hi there, I'm Mazen Nafe 👋 🛡️

### Smart Contract Security Researcher | Full-Stack Developer | Bug Bounty Hunter

I am a cybersecurity professional focused on securing the decentralized web. I specialize in deep-dive manual auditing of smart contracts and identifying systemic logic vulnerabilities in both EVM and Solana ecosystems.

---

### 🔍 Security Expertise
- **Manual Code Review:** Identifying complex logic flaws, access control issues, and economic exploits.
- **Vulnerability Research:** Specialized in Arithmetic flaws (Overflow/Underflow), Storage Slot Poisoning, and Signature Malleability.
- **Proof of Concept (PoC):** Developing robust exploits to demonstrate impact using Foundry, Hardhat, and Solana-test-validator.

### 🛠️ Tech Stack & Tools
- **Languages:** ![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=flat&logo=solidity&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-%23000000.svg?style=flat&logo=rust&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=flat&logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white) ![Go](https://img.shields.io/badge/Go-%2300ADD8.svg?style=flat&logo=go&logoColor=white)
- **Frameworks:** ![Foundry](https://img.shields.io/badge/Foundry-%23FF4B11.svg?style=flat) ![Hardhat](https://img.shields.io/badge/Hardhat-%23FFF100.svg?style=flat&logo=hardhat&logoColor=black) ![Anchor](https://img.shields.io/badge/Anchor-Solana-blue) ![Node.js](https://img.shields.io/badge/Node.js-6DA55F?style=flat&logo=node.dot-js&logoColor=white)
- **Security Tools:** Slither, Echidna, Mythril, Cargo-audit, Burp Suite, OWASP ZAP.
- **Development:** Antigravity IDE, Linux (Ubuntu), Git.

---

### 🏆 Security Profiles & Achievements
- **HackerOne:** [HackerOne Profile](https://hackerone.com/mazennafe?type=user)
- **Code4rena:** [C4 Profile](https://code4rena.com/@mazennafe)
- **HackenProof:** [HackenProof Profile](https://hackenproof.com/hackers/MazenNafe)

---

### 🏆 Notable Findings & Contributions

#### 🔗 Web3 & Smart Contracts
| Severity | Vulnerability / Task | Target |
| :--- | :--- | :--- |
| ![Critical](https://img.shields.io/badge/Critical-red?style=for-the-badge) | **[Fund Loss & Phantom Backing in Cross-Chain Accounting](https://github.com/mazennafee/audits/tree/main/Overlayer-CrossChain-Underflow-Fund-Loss)**<br><sub>• Discovered a severe state-desync logic flaw in OFT bridging mechanics.<br>• Proved that an unconditional Panic `0x11` leads to 100% loss of user funds and artificially inflates Aave backing metrics.</sub> | Overlayer |
| ![Critical](https://img.shields.io/badge/Critical-red?style=for-the-badge) | **[Liveness Failure in BFT Consensus (Unbounded Rounds OOM)](https://github.com/mazennafee/audits/tree/main/Circle-Malachite-Unbounded-Rounds-OOM)**<br><sub>• Discovered an unbounded memory allocation flaw in the P2P buffering logic.<br>• Developed an End-to-End network exploit demonstrating a deterministic network-wide crash.</sub> | Circle Malachite |
| ![High](https://img.shields.io/badge/High-orange?style=for-the-badge) | *Pending New Research...* | TBD |

#### 🌐 Web Application & Protocol Security (HackerOne Disclosures)
| Severity / CWE | Vulnerability Class & Impact | Platform |
| :--- | :--- | :--- |
| ![High](https://img.shields.io/badge/High-orange?style=for-the-badge)<br>`CWE-840` | **Business Logic Errors**<br><sub>• Discovered critical flaws in core application workflows, allowing manipulation of the state machine and unauthorized state-based actions.</sub> | HackerOne |
| ![High](https://img.shields.io/badge/High-orange?style=for-the-badge)<br>`CWE-294` | **Authentication Bypass by Capture-Replay**<br><sub>• Successfully bypassed multi-factor/signature checks by capturing and replaying sensitive validation parameters.</sub> | HackerOne |
| ![Medium](https://img.shields.io/badge/Medium-yellow?style=for-the-badge)<br>`CWE-770` / `CWE-400` | **Allocation of Resources Without Limits & Uncontrolled Resource Consumption**<br><sub>• Identified architectural design flaws leading to system exhaustion and denial of service (DoS) under specific payloads.</sub> | HackerOne |
| ![Medium](https://img.shields.io/badge/Medium-yellow?style=for-the-badge)<br>`CWE-407` / `CWE-113` | **Inefficient Algorithmic Complexity & HTTP Response Splitting**<br><sub>• Exploited backend algorithms using high-input payloads to trigger severe performance drops and protocol response splitting.</sub> | HackerOne |

---

### 📫 Let's Connect
- **Email:** mazen.nafee@gmail.com
  
 <div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mazennafee&theme=tokyonight" alt="GitHub Streak" />
  
  <br/><br/>
  
</div>
