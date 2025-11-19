

-----

# The Ultimate Security Guide Book for new-cryptorich friends :notebook:

> **Offered to Web3 community by zôÖma, from [samourai.world](https://samourai.world) crew**
> *With the support of the community.*
> *Feel free to contribute.*

-----
![](https://i.imgur.com/YENeD5H.jpg)

### Introduction :wave:

This is an exciting time for those of us in the Web3 world who are exploring this new continent of decentralized protocols.

In just over a decade, this new wave of technology, initiated by Bitcoin, has proven its robust security. The growth of its market has led to ever-higher valuations, enabling profiles around the world—young and old, technical and non-technical—to access funds that are sometimes life-changing.

**But remember:** Bitcoin, just like its little sister cryptocurrencies, brings the world a totally new freedom of emancipation from banks. With this freedom comes a huge responsibility: **to be your own bank.**

Where Bitcoin liberates, it brings its own set of constraints. You may think this advice is useless because your wallet is too small to interest malicious actors. Or you may think you are safe because you live in a "safe" country.

**You are wrong.**
Your portfolio today could be worth millions in a few years. The security mistakes you make today will impact your safety tomorrow.

This book is for you—traders, builders, and holders—to ensure the safety of:

  - Young, newly rich cryptocurrency traders.
  - Celebrities and public figures entering Web3.
  - New users of this new continent.
  - Your mother, who just asked you how to buy Bitcoin.

-----

> **Note:** This document is a living standard. It will be updated by the community and remain free.

-----

## :checkered_flag: Checklist version for Top level security (TLDR)

### The Ninja Setup :martial\_arts\_uniform:

Let's build your configuration from scratch. Make yourself comfortable and let's go.

### \#1 : Before the setup :coffee:

  - [ ] **Cash is King:** Prepare cash to buy your devices physically. Avoid credit cards to prevent purchase metadata from linking your identity to a hardware wallet order.
  - [ ] **Sanitize Environment:** Set up in a private room. Close the curtains. Cover webcams.
  - [ ] **Secure Network:** Do not use public Wi-Fi. Use a private, password-protected connection (ideally a fresh 4G/5G hotspot).

-----

### \#2 : Computer configuration :computer:

  - [ ] **Dedicated Device:** Buy a separate, cheap laptop for **crypto-related activities only**.

      - *Recommendation:* A refurbished ThinkPad running Linux (Mint or Ubuntu) or a clean MacBook Air.
      - *Rule:* This laptop never visits YouTube, never opens Discord, and never checks Facebook.

  - [ ] **The "Lambda" Email:** Create a dedicated email for non-sensitive, non-crypto commercial stuff.

      - *Recommendation:* ProtonMail (free tier).

  - [ ] **VPN (Virtual Private Network):**

      - *Recommendation:* **Mullvad** (paid with cash/crypto) or **IVPN**. Avoid "free" VPNs; they sell your data.
      - *Link:* [Mullvad VPN](https://mullvad.net/)

  - [ ] **DNS Security:**

      - *Recommendation:* **NextDNS** to block trackers at the network level.
      - *Link:* [NextDNS](https://nextdns.io)

  - [ ] **Password Manager:**

      - *Recommendation:* **Bitwarden** (Open Source) or **1Password**.
      - *Tip:* Learn to create [Strong Passwords](https://berty.tech/blog/create-strong-password/).

  - [ ] **The "Crypto" Email:**

      - Create a dedicated email **only** for exchanges (Binance, Kraken, etc.).
      - *Recommendation:* ProtonMail.
      - *Security:* 20+ char password + 2FA (YubiKey or Authy/Raivo, **never SMS**).
      - *Warning:* Never share this address. If you receive spam here, your exchange leaked your data. Burn it and start over.

-----

### \#3 : Hardware Wallet :key:

  - [ ] **Procurement:** Buy a hardware wallet.
      - **Warning:** Never order to your home address\! Use a P.O. Box, an Amazon Locker (if available for direct vendors), or a friend's office.
      - *Tip:* Create a dedicated pseudonym for the order.
      - *Link:* [Ledger](https://shop.ledger.com/) (French, Secure Element) or [Coinkite](https://coinkite.com/) (Coldcard, Bitcoin Only).

-----

### \#4 : Software Wallets & Nodes

#### Bitcoin:

  - [ ] **Desktop: Sparrow Wallet**
      - The gold standard for desktop Bitcoin wallets. Supports hardware wallets, Tor, and advanced "Coin Control" (choosing exactly which coins to spend to avoid linking your history).
      - *Link:* [Sparrow Wallet](https://sparrowwallet.com)
  - [ ] \~\~Samourai Wallet\~\~ *(Deprecated/Seized by DOJ 2024)*.
  - [ ] **Mobile: Envoy or Nunchuk**
      - **Envoy:** Simple, privacy-focused, Tor built-in. Good for daily spending.
      - **Nunchuk:** Security-focused, excellent for Multi-Sig and "Vault" setups.
  - [ ] **Run a Node:** Don't trust, verify. Run a RoninDojo or Umbrel node.
      - *Link:* [RoninDojo](https://ronindojo.io/)

#### Ethereum / EVM:

  - [ ] **Rabby Wallet:**
      - Far superior to MetaMask. It simulates transactions before you sign them to warn you if you are about to be drained.
      - *Link:* [Rabby.io](https://rabby.io)

### \#5: The "Seed" Protocol (IRL Storage)

Your seed phrase is your soul. If you lose it, you die (financially).

  - [ ] **Steel Backup:** Paper burns. Ink fades. Use steel.
      - *Link:* [Cryptosteel](https://cryptosteel.com/) or [Seedplate](https://coinkite.com/).
  - [ ] **Geographic Split:** Don't keep the seed and the passphrase (salt) in the same house.
      - *Case Study:* Put the Steel Seed in a bank deposit box or buried in a PVC pipe. Put the Passphrase in a password manager or a different physical location.

-----

## Healthy Online Lifestyle :spider\_web:

### Dockerise & Split your online life :package:

The "One Device for All" era is over. If you use the same laptop to download torrents and sign multi-million dollar transactions, you are a walking target.

  * **The Qubes OS Approach:** For the paranoid (and you should be), use [Qubes OS](https://www.qubes-os.org/). It isolates every app in a separate virtual machine (VM).
  * **The "Air-Gap" Strategy:** Maintain a dedicated machine that **never touches the internet**. It only communicates via QR codes (using wallets like Keystone or Specter).

### Do care about Metadata :detective:

Every photo you take carries invisible baggage called metadata (EXIF).

  * **The Threat:** A photo of your cat posted on Twitter can reveal your exact GPS coordinates.
  * **The Solution:**
      * Use **ExifCleaner** or `exiftool` to scrub data before sharing.
      * Screenshot your photos instead of uploading the original file (quickest trick).

### Social Network Posts :shushing\_face:

The "Grey Man" theory applies here.

  * **Delay your posts:** Never post "Live". If you are at a conference in Lisbon, post about it *after* you have left the country.
  * **No "ens" names as handles:** Using `vitalik.eth` as a Twitter handle is cool, but it publicly links your identity to your wallet balance.

### Exchange Relations :bank:

  * **Whitelisting:** Enable "Withdrawal Address Whitelisting" on CEXs. If hacked, funds can only go to *your* hard wallet.
  * **Anti-Phishing Code:** Set this up in exchange settings. Every legitimate email will contain your secret word. No word? It's a scam.

-----

## IRL Life : *"Free & Anonymous is the new Rich & Famous"* :ghost:

### Be a phantom, a ninja, and care about details.

If you have a large portfolio, the best protection is anonymity.
If criminals know your face, name, and movements:

1.  **The Robbery ($5 Wrench Attack):** They wait for you, beat you, and force you to unlock your Ledger.
2.  **Social Engineering:** They befriend you, offer a "deal," and hack you via a contaminated USB drive or Wi-Fi during a meeting.

### Tips List: :notebook_with_decorative_cover:

  - [ ] **Pseudonyms for Travel:** Use nicknames or corporate booking accounts for hotels.
  - [ ] **The "Delivery" Gap:** Never use your home address for crypto deliveries or Amazon. Use Relay Points or P.O. Boxes.
  - [ ] **Data Trolling:** Deliberately pollute your data footprint. Post a photo of a snowy mountain when you are actually at the beach. Confuse the algorithms and the stalkers.
  - [ ] **The Decoy Wallet:** Keep a wallet with $500 on your phone. If mugged, give them this. It satisfies the attacker without ruining you.

-----

## How to secure your company's crypto? :office:

If you are running a Web3 startup or Treasury, personal security rules don't scale. You need **Governance**.

### 1\. Multi-Signature Wallets (The DAO Standard)

Never hold company funds on a single private key.

  * **Solution:** **Safe (formerly Gnosis Safe)**.
  * **Config:** Use a **3-of-5** or **5-of-8** setup.
  * **Rule:** Signers must use different hardware wallets (Ledger + Trezor + Coldcard) and be geographically distributed.

### 2\. MPC (Multi-Party Computation) for Institutions

For high-frequency trading or large institutional treasuries.

  * **Technology:** MPC breaks the private key into "shards" that never meet.
  * **Providers:** Fireblocks, Coinbase Prime, or Copper.
  * **Why?** It allows for policy engines (e.g., "Transactions over $1M require video approval from the CEO").

### 3\. Operational Governance

  * **The "Bus Factor":** If the CTO dies, is the company fund lost?
  * **Dead Man's Switch:** Setup a legal or smart-contract protocol (like [Sarcophagus](https://sarcophagus.io/)) that releases access to recovery keys after 30-60 days of radio silence.

-----

## Post-Hack Protocol :anger:

### How to react quickly if you've been hacked?

1.  **Disconnect:** Cut the internet immediately. Turn off Wi-Fi.
2.  **Revoke:** Use a clean device to go to [Revoke.cash](https://revoke.cash) and remove permissions for the compromised contract.
3.  **The Lifeboat:** Move remaining funds to a fresh, pristine wallet. **Do not reuse the old seed.**
4.  **SEAL 911 (Emergency Response):**
      * **What is it?** A free, 24/7 emergency hotline for crypto hacks, run by the Security Alliance (SEAL). It connects you with top-tier whitehats and security researchers.
      * **How to use:** Contact their Telegram Bot immediately.
      * **Link:** [SEAL 911](https://github.com/security-alliance/seal-911) | [Telegram Bot Info](https://t.me/seal_911_bot)
      * **Note:** Also join the **SEAL-ISAC** (Information Sharing and Analysis Center) if you are a protocol/entity to get real-time threat intel.
      * *Source:* [Business Wire](https://www.businesswire.com/news/home/20240417493276/en/Security-Alliance-SEAL-Launches-Free-Crypto-Native-ISAC)
5.  **Blacklist:** Contact major stablecoin issuers (Tether, Circle) and exchanges (Binance) immediately. They can freeze USDT/USDC/CEX funds if you act fast.
6.  **Trace:** Tag the hacker on Etherscan and file a report with [Chainabuse](https://www.chainabuse.com/).

-----

# Hacked Stories :fishing\_pole\_and\_fish:

*A Wall of Shame to remind you that even the giants fall. We separate this into CEX (Centralized Exchange) failures and DeFi (Decentralized Finance) exploits.*

### 🏛️ Centralized Exchange (CEX) & Infrastructure Hacks

| Year | Entity | Amount Lost | Vector | Lesson |
| :--- | :--- | :--- | :--- | :--- |
| **2025** | **Bybit** | **$1.5B** | Hot Wallet / Key Leak | **Largest crypto theft in history.** Attributed to Lazarus Group. |
| **2024** | **DMM Bitcoin** | $305M | Social Eng. / Wallet | Fake job offers to employees allowed deep system access. |
| **2022** | **FTX / Alameda** | ~$477M | Insider / Sim Swap | The "Bank Run" hack. Occurred immediately after bankruptcy filing. |
| **2018** | **Coincheck** | $530M | Phishing / Hot Wallet | Employee opened a malware email. Funds (NEM) were in hot wallets. |
| **2016** | **Bitfinex** | $72M | Multi-sig Bypass | 120k BTC stolen. Money laundered years later by "Razzlekhan". |
| **2014** | **Mt. Gox** | $460M | Malleability Bug | The original sin. 850k BTC lost. |

### 🦄 DeFi Protocol Hacks (Last 5 Years - Top 40)

| \# | Year | Protocol | Amount Lost | Vector |
| :--- | :--- | :--- | :--- | :--- |
| 1 | 2022 | **Ronin Network** | $625M | Social Engineering / Validator Compromise |
| 2 | 2021 | **Poly Network** | $611M | Cross-Chain Contract Vulnerability |
| 3 | 2022 | **Binance Bridge** | $570M | IAVL Proof Verification Exploit |
| 4 | 2022 | **Wormhole** | $325M | Signature Verification Bypass |
| 5 | 2024 | **Orbit Chain** | $81M | Bridge Multi-sig Compromise |
| 6 | 2023 | **Euler Finance** | $197M | Flash Loan / Logic Error |
| 7 | 2022 | **Nomad Bridge** | $190M | Logic Error (Copy-paste vulnerability) |
| 8 | 2022 | **Beanstalk Farms** | $182M | Governance Flash Loan Attack |
| 9 | 2022 | **Wintermute** | $160M | Profanity Tool (Vanity Address) Exploit |
| 10 | 2023 | **Multichain** | $126M | MPC Key Leak / Insider Job |
| 11 | 2021 | **Cream Finance** | $130M | Flash Loan (Price Manipulation) |
| 12 | 2022 | **Harmony Horizon** | $100M | Private Key Theft (Lazarus) |
| 13 | 2021 | **BadgerDAO** | $120M | Frontend Injection (Cloudflare) |
| 14 | 2024 | **Munchables** | $62M | Rogue Developer (Insider) |
| 15 | 2023 | **Curve Finance** | $61M | Vyper Compiler Bug (Reentrancy) |
| 16 | 2021 | **Compound** | $80M | Comptroller Logic Error |
| 17 | 2024 | **Radiant Capital** | $50M | Lending Logic / Flash Loan |
| 18 | 2023 | **KyberSwap** | $48M | Infinite Approval Loop Bug |
| 19 | 2022 | **Cashio** | $48M | Infinite Mint Glitch |
| 20 | 2023 | **Socket / Bungee** | $3.3M | Approval Exploit |
| 21 | 2021 | **Grim Finance** | $30M | Reentrancy |
| 22 | 2021 | **Vee Finance** | $35M | Oracle Manipulation |
| 23 | 2023 | **Yearn Finance** | $11M | Misconfigured Token (yUSDT) |
| 24 | 2022 | **Rari Capital** | $80M | Reentrancy (Fuse Pools) |
| 25 | 2023 | **Alphapo** | $60M | Hot Wallet Keys |
| 26 | 2023 | **Stake.com** | $41M | Private Key Leak |
| 27 | 2022 | **Mango Markets** | $114M | Oracle Price Manipulation (Avi Eisenberg) |
| 28 | 2024 | **Hedgey Finance** | $44M | Arbitrary Call Vulnerability |
| 29 | 2024 | **Sonne Finance** | $20M | Precision Loss / Empty Market Attack |
| 30 | 2024 | **UwU Lend** | $19M | Price Manipulation |
| 31 | 2023 | **Exactly Protocol** | $7M | Bridge Vulnerability |
| 32 | 2023 | **Rho Markets** | $7.6M | Oracle Misconfiguration |
| 33 | 2023 | **Galxe** | $0.4M | DNS Hijacking |
| 34 | 2021 | **bZx (Ooki)** | $55M | Private Key Phishing |
| 35 | 2021 | **EasyFi** | $80M | Admin Key Compromise |
| 36 | 2022 | **Qubit Finance** | $80M | Bridge Deposit Bug |
| 37 | 2022 | **Fei Protocol** | $80M | Reentrancy |
| 38 | 2024 | **Gamma Strategies** | $6M | Reentrancy |
| 39 | 2024 | **Abracadabra (MIM)** | $6.5M | Rounding Error |
| 40 | 2021 | **PancakeBunny** | $200M | Flash Loan |

-----

# The Lazarus Group: North Korean State Hackers :flag\_kp:

*A dedicated section for the world's most dangerous crypto-threat actor. The DPRK uses stolen crypto to fund weapons programs. They account for an estimated **$3 Billion+** in thefts.*

| Year | Victim | Amount (Est.) | Vector | Source/Details |
| :--- | :--- | :--- | :--- | :--- |
| **2025** | **Bybit** | **$1.5 Billion** | Supply Chain / Key Leak | Largest single heist. Suspected to involve Safe{Wallet} supply chain or deep social engineering. [Source](https://crystalintelligence.com/investigations/the-10-biggest-crypto-hacks-in-history/) |
| **2024** | **DMM Bitcoin** | $305 Million | Social Engineering | Attackers likely infiltrated the Japanese exchange via fake job offers to staff. [Source](https://www.google.com/search?q=https://www.elliptic.co/blog/dmm-bitcoin-suffers-305-million-hack) |
| **2024** | **WazirX** | $235 Million | Multisig Compromise | Breached the Indian exchange's multisig. [Source](https://www.google.com/search?q=https://techcrunch.com/2024/07/18/wazirx-india-crypto-hack/) |
| **2023** | **Atomic Wallet** | $100 Million | Supply Chain / Update | Malicious update pushed to users of the non-custodial wallet. [Source](https://www.google.com/search?q=https://www.elliptic.co/blog/analysis-of-the-atomic-wallet-hack) |
| **2023** | **Stake.com** | $41 Million | Private Key Leak | Targeted the world's largest crypto casino. [Source](https://www.google.com/search?q=https://www.coindesk.com/business/2023/09/04/stake-suspected-exploit/) |
| **2023** | **CoinEx** | $55 Million | Hot Wallet Keys | Compromised hot wallet keys. [Source](https://www.google.com/search?q=https://www.chainalysis.com/blog/coinex-hack-lazarus-group/) |
| **2022** | **Ronin Bridge** | $625 Million | Social Engineering | Fake job interview (PDF malware) gave access to Sky Mavis validator nodes. [Source](https://www.google.com/search?q=https://www.fbi.gov/news/press-releases/fbi-statement-on-attribution-of-malicious-cyber-activity-to-the-lazarus-group-and-apt38) |
| **2022** | **Harmony Horizon** | $100 Million | Private Key Theft | Bridge keys stolen. Funds laundered via Tornado Cash. [Source](https://www.google.com/search?q=https://www.elliptic.co/blog/harmony-horizon-bridge-hack-analysis) |

-----

# Kidnappings & Physical Attacks :gun:

*Digital security means nothing when a gun is pointed at your head.*

### France (The 2024-2025 Surge)

*France has recently become a primary target zone for physical crypto extortion.*

1.  **Jan 2025 (Vierzon) - Ledger Co-Founder:** David Balland, co-founder of Ledger, was kidnapped at his home. Attackers **severed his finger** to force him to unlock devices.
      * *Source:* [Le Monde](https://www.lemonde.fr/pixels/article/2025/01/23/les-kidnappeurs-d-un-cofondateur-de-ledger-et-de-sa-compagne-interpelles-apres-une-gigantesque-chasse-a-l-homme_6512799_4408996.html)
2.  **May 2025 (Paris) - Paymium Family:** The daughter and grandson of Paymium CEO Pierre Noizat were targeted in a kidnapping attempt in Paris (11th arr.). Thwarted by locals.
      * *Source:* [Hyperion Services](https://hyperionservices.co/bitcoin-crypto-kidnappings/)
3.  **Nov 2025 (Maisons-Alfort) - The "Errand Boy":** A 23-year-old investor was kidnapped while running errands; forced to ransom his own Ledger + €5k cash.
      * *Source:* [The Block](https://www.theblock.co/post/359010/france-hit-by-10th-crypto-wrench-attack-of-2025-as-kidnappers-target-23-year-old-near-paris)
4.  **Jan 2025 (Troyes) - The Trap:** A 30-year-old entrepreneur lured to a fake client meeting, kidnapped by 4 men. Rescued by police.
      * *Source:* [JDD](https://www.lejdd.fr/Societe/info-jdd-troyes-un-autre-entrepreneur-en-cryptomonnaies-enleve-quatre-suspects-interpelles-154239)

### Canada

1.  **Nov 2024 (Toronto):** Dean Skurka (CEO of WonderFi) forced into a vehicle, held for $1M ransom. Released after payment.
      * *Source:* [CBC](https://www.cbc.ca/news/canada/toronto/crypto-bitcoin-price-ceo-toronto-kidnapping-1.7378241)
2.  **Dec 2022 (Ontario):** Aiden Pleterski ("Crypto King" Ponzi) kidnapped, beaten, and tortured for days by victims of his scheme.

### United States

1.  **May 2025 (New York):** "House of Horrors". An Italian entrepreneur lured to a Manhattan townhouse, held for 17 days and tortured for Bitcoin keys.
      * *Source:* [CBC News](https://www.cbc.ca/news/world/world-us-cryptocurrency-related-crimes-1.7546701)
2.  **May 2024 (Connecticut):** A couple rammed in their Lamborghini and abducted by attackers targeting their son's crypto wealth.

### Bulgaria

1.  **Aug 2023:** Christian Peev (US Investor). Murdered and dismembered; body found in plumbing pipes in Sofia.

### Argentina

1.  **Jul 2023:** Fernando Pérez Algaba. Found shot and dismembered in a suitcase.

### Spain

1.  **Nov 2021:** Zaryn Dentzel (Tuenti Founder). Tortured in his Madrid home for hours by masked men.

### Thailand / Singapore

1.  **Sep 2022 (Thailand):** Russian couple ambushed and forced to transfer $100k.
2.  **Jan 2020 (Thailand):** Mark Cheng (Singaporean) kidnapped and tortured with electricity.

-----

# Future of CyberAttacks :robot:

*The battlefield is evolving. We are moving from static phishing to dynamic, AI-driven warfare.*

### 1\. AI-Driven Social Engineering

  * **Deepfakes:** Scammers will use real-time video/voice cloning of CEOs or family members to authorize transactions. (Already seen in traditional finance, coming to crypto governance).
  * **The 82:1 Ratio:** Autonomous AI attack agents will outnumber human defenders 82 to 1 by 2026.
  * **Hyper-Personalization:** AI will scrape your entire digital footprint to create "perfect" spear-phishing emails that are impossible to distinguish from reality.

### 2\. Quantum Threats (Q-Day)

  * **"Harvest Now, Decrypt Later":** Nation-states are recording encrypted traffic today (including your transaction signatures). When Quantum Computers mature (predicted \~2029-2030), they will break current ECDSA encryption and derive private keys from old signatures.
  * **Defense:** You must migrate to Post-Quantum Cryptography (PQC) algorithms when they become available on chains like Ethereum.

### 3\. Data Poisoning & Supply Chain

  * **Malicious Libraries:** Attackers will poison open-source code repositories (npm, pip) used by wallet developers, injecting dormant backdoors that activate only when large balances are detected.
  * **Model Poisoning:** Manipulating the data used to train AI security bots, rendering them blind to specific attack vectors.

-----

### :link: Resources & Guides

#### :detective: The "White Hat" Researchers List

*Follow these accounts for real-time security alerts.*

  * **@ZachXBT** (On-chain sleuth)
  * **@P3b7\_** (Ledger Donjon)
  * **@samczsun** (Paradigm)
  * **@SlowMist\_Team** (Asian market/Lazarus intel)
  * **@tayvano** (Phishing specialist)

#### :books: Books & Recommended Reading

  * **Extreme Privacy (5th Edition)** by *Michael Bazzell*.
  * **Mastering Bitcoin** by *Andreas Antonopoulos*.
  * **The Blocksize War** by *Jonathan Bier*.
  * **Sandworm** by *Andy Greenberg* (Understanding state-sponsored cyberwar).
  * **Tracers in the Dark** by *Andy Greenberg*.

#### :scroll: Academic & Technical Papers

  * **"SoK: Decentralized Finance (DeFi) Attacks"** (Zhou et al.) - A systematic classification of DeFi exploits.
  * **"Flash Boys 2.0: Frontrunning in Decentralized Exchanges, Miner Extractable Value, and Consensus Instability"** (Daian et al.) - The seminal paper on MEV.
  * **"On-Chain Decentralized Learning and Cost-Effective Inference for DeFi Attack Mitigation"** (arXiv 2025).

#### :earth_americas: Online Resources

  * **SEAL 911:** [github.com/security-alliance/seal-911](https://github.com/security-alliance/seal-911)
  * **Rekt Database:** [Rekt.news](https://rekt.news) (Detailed post-mortems of hacks).
  * **Privacy Guides:** [PrivacyGuides.org](https://www.privacyguides.org)
  * **Revoke Cash:** [Revoke.cash](https://revoke.cash)

-----

> *Stay Safe. Stay Private. Don't Trust, Verify.*
