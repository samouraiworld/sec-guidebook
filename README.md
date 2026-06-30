

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
      - **Flagship 2025/2026 Models:**
          - **Ledger Nano Gen5** ($179) — Clear Signing, Bluetooth/NFC, Ledger Wallet app. [Product](https://shop.ledger.com/) | [Announcement](https://www.ledger.com/academy/topics/ledgersolutions/introducing-ledger-nano-gen5)
          - **Trezor Safe 7** ($249) — Dual secure elements (TROPIC01), color touchscreen, post-quantum firmware verification. [Product](https://trezor.io/trezor-safe-7)
          - **BitBox02 Nova** (~$149) — EAL6+ Infineon Optiga Trust M V3, open-source firmware, iOS via Whisper BLE. [Product](https://bitbox.swiss/bitbox02/nova/) | [Announcement](https://blog.bitbox.swiss/en/introducing-bitbox02-nova/)
          - **Coldcard Mk4 / Q** — v5.5.0+ (Mar 2026) adds BIP-322 Proof of Reserve signing. [Product](https://coinkite.com/) | [Firmware notes](https://blog.coinkite.com/bip322-wif/)

-----

### \#4 : Software Wallets & Nodes

#### Bitcoin:

  - [ ] **Desktop: Sparrow Wallet**
      - The gold standard for desktop Bitcoin wallets. Supports hardware wallets, Tor, "Coin Control", and "Stonewall" transactions (local coinjoin simulations). [Source](https://sparrowwallet.com)
      - *Link:* [Sparrow Wallet](https://sparrowwallet.com)
  - [ ] **Desktop: Wasabi Wallet**
      - *Note:* zkSNACKs shut down its native CoinJoin coordinator on June 1, 2024 amid U.S. regulatory pressure; the wallet still works with third-party coordinators. [Source](https://news.bitcoin.com/zksnacks-to-cease-coinjoin-transactions-affecting-wasabi-trezor-and-btcpay/)
  - [ ] ~~Samourai Wallet~~ *(Seized by DOJ April 2024; founders sentenced Nov 2025)*. [Source](https://www.coindesk.com/policy/2024/04/24/samourai-wallet-founders-arrested-and-charged-with-money-laundering)
  - [ ] **Mobile: Envoy or Nunchuk**
      - **Envoy:** Simple, privacy-focused, Tor built-in. Frequent v2.2.x releases in early 2026 keep it robust. Good for daily spending.
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
  * **Withdraw Protection (2026 Defense):** Enable exchange time-lock features (e.g., Binance's "Withdraw Protection," launched May 4, 2026) to freeze *on-chain* withdrawals for 1–7 days under physical coercion ($5 Wrench Attacks). This is an internal policy lock—not a cryptographic guarantee—and does not block lawful court orders. [Source](https://www.coindesk.com/business/2026/05/04/binance-is-launching-a-withdrawal-lock-to-help-deter-crypto-wrench-attacks)
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

> **2026 snapshot (through Jun 30):** Q2 2026 is the most-hacked quarter on record by incident count—**83 exploits** and **~$755M** stolen per DefiLlama/Cointelegraph analysis, with bridges still the costliest vector. April's Kelp DAO + Drift hits alone drove most of the dollar volume; May–June shifted toward **private-key / ops failures** (Resolv AWS KMS, Taiko GitHub leak, Humanity phishing) and **deprecated-contract drains** (Raydium AMM V3, Aztec Connect). [Source](https://cointelegraph.com/news/q2-2026-most-hacked-quarter-record-83-incidents)

### 🏛️ Centralized Exchange (CEX) & Infrastructure Hacks

| Year | Entity | Amount Lost | Vector | Lesson |
| :--- | :--- | :--- | :--- | :--- |
| **Jun 2026** | **Polymarket** | **$2.9M** | Supply Chain / Frontend | Malicious script injected via compromised third-party vendor dependency; users drained via wallet approvals (contracts untouched). [Source](https://cointelegraph.com/news/polymarket-vendor-compromise-drains-29m-users) |
| **Apr 2026** | **Grinex** | **$13M** | Hot Wallet / Exit? | Russia-linked CEX (Garantex successor) halted ops after ~$13.7M USDT drained; funds swapped to TRX. [Source](https://www.coindesk.com/business/2026/04/17/russia-linked-grinex-exchange-halts-operations-after-usd13-million-state-backed-hack) |
| **Feb 2025** | **Bybit** | **$1.5B** | Supply Chain / JS Injection | **Largest crypto theft in history.** Safe{Wallet} dev machine compromised; malicious JS redirected a cold-wallet transfer (FBI attributed to Lazarus). [Source](https://www.bleepingcomputer.com/news/security/fbi-confirms-lazarus-hackers-were-behind-15b-bybit-crypto-heist/) |
| **2024** | **DMM Bitcoin** | $305M | Social Eng. / Wallet | Fake job offers to employees allowed deep system access. [Source](https://chainalysis.com/blog/2024-crypto-hack-report/) |
| **2022** | **FTX / Alameda** | ~$477M | Insider / Sim Swap | The "Bank Run" hack. Occurred immediately after bankruptcy filing. [Source](https://www.elliptic.co/blog/the-477-million-ftx-hack-a-new-blockchain-trail) |
| **2018** | **Coincheck** | $530M | Phishing / Hot Wallet | Employee opened a malware email. Funds (NEM) were in hot wallets. [Source](https://www.coindesk.com/markets/2018/01/26/crypto-exchange-coincheck-halts-withdrawals-amid-hack-rumors/) |
| **2016** | **Bitfinex** | $72M | Multi-sig Bypass | 120k BTC stolen. Money laundered years later by "Razzlekhan". [Source](https://www.justice.gov/opa/pr/two-arrested-alleged-conspiracy-launder-45-billion-stolen-cryptocurrency) |
| **2014** | **Mt. Gox** | $460M | Malleability Bug | The original sin. 850k BTC lost. [Source](https://www.wired.com/2014/03/bitcoin-exchange/) |

### 🦄 DeFi Protocol Hacks (Last 5 Years - Top 40)

| \# | Year | Protocol | Amount Lost | Vector |
| :--- | :--- | :--- | :--- | :--- |
| 1 | 2022 | **Ronin Network** | $625M | Social Engineering / Validator Compromise [Source](https://rekt.news/ronin-rekt/) |
| 2 | 2021 | **Poly Network** | $611M | Cross-Chain Contract Vulnerability [Source](https://rekt.news/poly-network-rekt/) |
| 3 | 2022 | **Binance Bridge** | $570M | IAVL Proof Verification Exploit [Source](https://rekt.news/bnb-bridge-rekt/) |
| 4 | 2022 | **Wormhole** | $325M | Signature Verification Bypass [Source](https://rekt.news/wormhole-rekt/) |
| — | 2026 | **Kelp DAO** | $292M | Off-chain RPC / 1-of-1 DVN forgery (Lazarus) [Source](https://www.chainalysis.com/blog/kelpdao-bridge-exploit-april-2026/) |
| — | 2026 | **Drift Protocol** | $285M | 6-month social eng. / multisig (Lazarus) [Source](https://www.chainalysis.com/blog/lessons-from-the-drift-hack/) |
| — | 2026 | **Humanity Protocol** | $36M | Phishing / Admin keys on laptop (DPRK tooling suspected) [Source](https://cointelegraph.com/news/humanity-protocol-hack-linked-north-korean-actors-quantstamp) |
| — | 2026 | **Resolv** | $25M | AWS KMS key compromise / unbacked USR mint [Source](https://www.chainalysis.com/blog/lessons-from-the-resolv-hack/) |
| — | 2026 | **Verus Bridge** | $11.6M | Forged cross-chain import / missing amount validation [Source](https://cointelegraph.com/news/verus-ethereum-bridge-reportedly-exploited-for-millions) |
| — | 2026 | **THORChain** | $10.7M | GG20 TSS key-material leakage (malicious node) [Source](https://blog.thorchain.org/thorchain-exploit-report-1) |
| — | 2026 | **Syscoin Bridge** | ~$10M | SPV proof parsing mismatch (funds later returned & burned) [Source](https://syscoin.org/news/technical-postmortem-syscoin-bridge-incident-recovery-and-remediation) |
| — | 2026 | **Aztec Connect** | $2.2M | Deprecated ZK rollup: L1/L2 settlement boundary gap [Source](https://aztec-labs.com/blog/aztec-connect-incident.html) |
| — | 2026 | **Taiko** | $1.7M | RSA signing key exposed on public GitHub (SGX prover) [Source](https://www.halborn.com/blog/post/explained-the-taiko-bridge-hack-june-2026) |
| — | 2026 | **Raydium** | $1.3M | Deprecated AMM V3 LP-mint validation flaw [Source](https://thedefiant.io/news/hacks/raydium-drained-1-3m-attacker-bridges-ethereum-tornado-cash) |
| — | 2026 | **Gnosis Pay** | $0.27M | Zodiac Delay/Roles ERC-1271 signature bypass [Source](https://engineering.gnosisguild.org/posts/zodiac-post-mortem) |
| 5 | 2024 | **Orbit Chain** | $81M | Bridge Multi-sig Compromise [Source](https://rekt.news/orbit-chain-rekt/) |
| 6 | 2023 | **Euler Finance** | $197M | Flash Loan / Logic Error [Source](https://rekt.news/euler-rekt/) |
| 7 | 2022 | **Nomad Bridge** | $190M | Logic Error (Copy-paste vulnerability) [Source](https://rekt.news/nomad-rekt/) |
| 8 | 2022 | **Beanstalk Farms** | $182M | Governance Flash Loan Attack [Source](https://rekt.news/beanstalk-rekt/) |
| 9 | 2022 | **Wintermute** | $160M | Profanity Tool (Vanity Address) Exploit [Source](https://rekt.news/wintermute-rekt/) |
| 10 | 2023 | **Multichain** | $126M | MPC Key Leak / Insider Job [Source](https://rekt.news/multichain-rekt/) |
| 11 | 2021 | **Cream Finance** | $130M | Flash Loan (Price Manipulation) [Source](https://rekt.news/cream-rekt-2/) |
| 12 | 2022 | **Harmony Horizon** | $100M | Private Key Theft (Lazarus) [Source](https://rekt.news/harmony-rekt/) |
| 13 | 2021 | **BadgerDAO** | $120M | Frontend Injection (Cloudflare) [Source](https://rekt.news/badger-rekt/) |
| 14 | 2024 | **Munchables** | $62M | Rogue Developer (Insider) [Source](https://rekt.news/munchables-rekt/) |
| 15 | 2023 | **Curve Finance** | $61M | Vyper Compiler Bug (Reentrancy) [Source](https://rekt.news/curve-vyper-rekt/) |
| 16 | 2021 | **Compound** | $80M | Comptroller Logic Error [Source](https://rekt.news/compound-rekt/) |
| 17 | 2024 | **Radiant Capital** | $50M | Lending Logic / Flash Loan [Source](https://rekt.news/radiant-rekt/) |
| 18 | 2023 | **KyberSwap** | $48M | Infinite Approval Loop Bug [Source](https://rekt.news/kyberswap-rekt/) |
| 19 | 2022 | **Cashio** | $48M | Infinite Mint Glitch [Source](https://rekt.news/cashio-rekt/) |
| 20 | 2023 | **Socket / Bungee** | $3.3M | Approval Exploit [Source](https://rekt.news/socket-rekt/) |
| 21 | 2021 | **Grim Finance** | $30M | Reentrancy [Source](https://rekt.news/grim-finance-rekt/) |
| 22 | 2021 | **Vee Finance** | $35M | Oracle Manipulation [Source](https://rekt.news/vee-finance-rekt/) |
| 23 | 2023 | **Yearn Finance** | $11M | Misconfigured Token (yUSDT) [Source](https://rekt.news/yearn-rekt/) |
| 24 | 2022 | **Rari Capital** | $80M | Reentrancy (Fuse Pools) [Source](https://rekt.news/rari-rekt/) |
| 25 | 2023 | **Alphapo** | $60M | Hot Wallet Keys [Source](https://halborn.com/alphapo-hack/) |
| 26 | 2023 | **Stake.com** | $41M | Private Key Leak [Source](https://halborn.com/stake-com-hack/) |
| 27 | 2022 | **Mango Markets** | $114M | Oracle Price Manipulation (Avi Eisenberg) [Source](https://rekt.news/mango-markets-rekt/) |
| 28 | 2024 | **Hedgey Finance** | $44M | Arbitrary Call Vulnerability [Source](https://rekt.news/hedgey-rekt/) |
| 29 | 2024 | **Sonne Finance** | $20M | Precision Loss / Empty Market Attack [Source](https://rekt.news/sonne-finance-rekt/) |
| 30 | 2024 | **UwU Lend** | $19M | Price Manipulation [Source](https://rekt.news/uwu-lend-rekt/) |
| 31 | 2023 | **Exactly Protocol** | $7M | Bridge Vulnerability [Source](https://rekt.news/exactly-rekt/) |
| 32 | 2023 | **Rho Markets** | $7.6M | Oracle Misconfiguration [Source](https://halborn.com/rho-markets-hack/) |
| 33 | 2023 | **Galxe** | $0.4M | DNS Hijacking [Source](https://halborn.com/galxe-hack/) |
| 34 | 2021 | **bZx (Ooki)** | $55M | Private Key Phishing [Source](https://rekt.news/bzx-rekt/) |
| 35 | 2021 | **EasyFi** | $80M | Admin Key Compromise [Source](https://rekt.news/easyfi-rekt/) |
| 36 | 2022 | **Qubit Finance** | $80M | Bridge Deposit Bug [Source](https://rekt.news/qubit-rekt/) |
| 37 | 2022 | **Fei Protocol** | $80M | Reentrancy [Source](https://rekt.news/fei-rari-rekt/) |
| 38 | 2024 | **Gamma Strategies** | $6M | Reentrancy [Source](https://rekt.news/gamma-strategies-rekt/) |
| 39 | 2024 | **Abracadabra (MIM)** | $6.5M | Rounding Error [Source](https://rekt.news/abracadabra-rekt/) |
| 40 | 2021 | **PancakeBunny** | $200M | Flash Loan [Source](https://rekt.news/pancakebunny-rekt/) |

-----

# The Lazarus Group: North Korean State Hackers :flag\_kp:

*A dedicated section for the world's most dangerous crypto-threat actor. The DPRK uses stolen crypto to fund weapons programs. Through April 2026, North Korea-linked groups accounted for **76%** of global crypto hack losses—$577M from just two April incidents (Drift + KelpDAO)—per TRM Labs ([Source](https://www.trmlabs.com/resources/blog/north-korea-stole-76-of-all-crypto-hack-value-in-2026-with-just-two-attacks)). **June 2026:** Quantstamp linked Humanity Protocol's $36M admin-key theft to DPRK tradecraft (fake Bithumb phishing email). Attack pattern in 2026: fewer incidents, higher precision—long social-engineering campaigns and off-chain infrastructure compromise over brute-force contract bugs. **$6B+** in attributed cumulative theft since 2017.*


| Year | Victim | Amount (Est.) | Vector | Source/Details |
| :--- | :--- | :--- | :--- | :--- |
| **Feb 2025** | **Bybit** | **$1.5 Billion** | Supply Chain / JS Injection | Largest single heist. Safe{Wallet} dev machine compromised; FBI attributed to Lazarus. [Source](https://www.bleepingcomputer.com/news/security/fbi-confirms-lazarus-hackers-were-behind-15b-bybit-crypto-heist/) |
| **April 2026** | **Kelp DAO** | **$292 Million** | Off-chain RPC / DVN Forgery | Forged cross-chain message via poisoned RPC nodes (1-of-1 DVN config). [Source](https://www.chainalysis.com/blog/kelpdao-bridge-exploit-april-2026/) |
| **April 2026** | **Drift Protocol** | **$285 Million** | Social Engineering | Six-month infiltration; durable-nonce multisig attack (UNC4736). [Source](https://www.securityweek.com/north-korean-hackers-drain-285-million-from-drift-in-10-seconds/) |
| **June 2026** | **Humanity Protocol** | **$36 Million** | Phishing / Key Theft | Fake Bithumb email → malware on director's laptop; 7 admin keys stolen. DPRK tooling suspected. [Source](https://cointelegraph.com/news/humanity-protocol-hack-linked-north-korean-actors-quantstamp) |
| **2024** | **DMM Bitcoin** | $305 Million | Social Engineering | Attackers likely infiltrated the Japanese exchange via fake job offers to staff. [Source](https://www.elliptic.co/blog/analysis/dmm-bitcoin-suffers-305-million-hack) |
| **2024** | **WazirX** | $235 Million | Multisig Compromise | Breached the Indian exchange's multisig. [Source](https://techcrunch.com/2024/07/18/indias-wazirx-crypto-exchange-halt-withdrawals-after-cyberattack/) |
| **2023** | **Atomic Wallet** | $100 Million | Supply Chain / Update | Malicious update pushed to users of the non-custodial wallet. [Source](https://www.elliptic.co/blog/analysis/analysis-of-the-atomic-wallet-hack) |
| **2023** | **Stake.com** | $41 Million | Private Key Leak | Targeted the world's largest crypto casino. [Source](https://www.coindesk.com/business/2023/09/04/crypto-casino-stake-targeted-in-suspected-41m-exploit/) |
| **2023** | **CoinEx** | $55 Million | Hot Wallet Keys | Compromised hot wallet keys. [Source](https://www.chainalysis.com/blog/coinex-hack-lazarus-group-north-korea/) |
| **2022** | **Ronin Bridge** | $625 Million | Social Engineering | Fake job interview (PDF malware) gave access to Sky Mavis validator nodes. [Source](https://www.fbi.gov/news/press-releases/fbi-statement-on-attribution-of-malicious-cyber-activity-to-the-lazarus-group-and-apt38) |
| **2022** | **Harmony Horizon** | $100 Million | Private Key Theft | Bridge keys stolen. Funds laundered via Tornado Cash. [Source](https://www.elliptic.co/blog/analysis/over-1-billion-stolen-from-bridges-so-far-in-2022-as-harmony-s-horizon-bridge-becomes-latest-victim-in-100-million-hack/) |

-----

# Kidnappings & Physical Attacks :gun:

*Digital security means nothing when a gun is pointed at your head.*

### France (The 2025-2026 Surge)

*France has become a primary target zone for physical crypto extortion. France's National Anti-Organized Crime Prosecutor's Office (PNACO) recorded **47 crypto-linked kidnappings or sequestrations through April 2026** (18 in 2024, 67 in 2025), with **88 people charged** across 12 consolidated investigations by late April. By mid-June, police leadership cited **~70+ incidents since January 2026** as the pace accelerated into Provence and Île-de-France. Attackers correlate leaked exchange databases (Ledger, tax tools like Waltio) with public social media to select targets. [Source](https://www.crowdfundinsider.com/2026/04/275901-french-authorities-indict-offenders-in-crypto-wrench-attacks-and-targeted-kidnapping-ring/) | [Source](https://www.laprovence.com/article/faits-divers-justice/2193885092828214/quatre-hommes-arretes-en-plein-braquage-sur-fond-de-cryptomonnaies-pres-de-marseille)*

1.  **Jan 2025 (Vierzon) - Ledger Co-Founder:** David Balland, co-founder of Ledger, was kidnapped at his home. Attackers severed his finger to force him to unlock devices.
    * *Source:* [DL News](https://www.dlnews.com/articles/people-culture/ledger-co-founder-david-balland-victim-of-violent-kidnapping/) | [Le Monde](https://www.lemonde.fr/pixels/article/2025/01/23/les-kidnappeurs-d-un-cofondateur-de-ledger-et-de-sa-compagne-interpelles-apres-une-gigantesque-chasse-a-l-homme_6512799_4408996.html)
2.  **Jan 2025 (Troyes) - The Trap:** A 30-year-old entrepreneur lured to a fake client meeting, kidnapped by 4 men.
    * *Source:* [JDD](https://www.lejdd.fr/Societe/info-jdd-troyes-un-autre-entrepreneur-en-cryptomonnaies-enleve-quatre-suspects-interpelles-154239)
3.  **May 2025 (Paris) - Paymium Family:** The daughter and grandson of Paymium CEO Pierre Noizat were targeted in a kidnapping attempt in Paris.
    * *Source:* [Hyperion Services](https://hyperionservices.co/bitcoin-crypto-kidnappings/)
4.  **June 2025 (Maisons-Alfort) - The "Errand Boy":** A 23-year-old investor was kidnapped while running errands; forced to ransom his own Ledger + €5k cash.
    * *Source:* [FinanceFeeds](https://financefeeds.com/tenth-crypto-kidnapping-in-france-alarms-community/) | [Le Parisien](https://www.leparisien.fr/val-de-marne-94/maisons-alfort-enleve-et-sequestre-pour-ses-cryptomonnaies-19-06-2025-8LZ4.php)
5.  **Dec 2025 (Charente-Maritime) - The Couple:** A couple in Dompierre-sur-Mer was sequestered and robbed of ~€9 million in cryptocurrency.
    * *Source:* [Capital.fr](https://www.capital.fr/votre-argent/braquage-a-dompierre-sur-mer-un-couple-deleste-de-9-millions-deuros-en-crypto-1502541) | [CNews](https://www.cnews.fr/france/2025-12-19/charente-maritime-un-couple-sequestre-et-depouille-de-plusieurs-millions-deuros)
6.  **Dec 2025 (Val-d'Oise) - The Father:** The father of a crypto entrepreneur was kidnapped in broad daylight to extort his son.
    * *Source:* [Cryptoast](https://cryptoast.fr/enlevement-pere-famille-val-doise-rancon-crypto/)
7.  **Jan 2026 (Cholet) - The "Software Architect":** A 43-year-old crypto investor was kidnapped at his home, tied up, and released 50km away.
    * *Source:* [Ouest France](https://www.ouest-france.fr/societe/faits-divers/jai-entendu-des-cris-dans-la-rue-enleve-au-petit-matin-pour-ses-cryptomonnaies-pres-de-cholet-f97a7740-ed71-11f0-ae78-1a0629cc1f87)
8.  **Jan 2026 (Sarthe) - Family Sequestered:** A couple and their three children were held at gunpoint overnight in La Chapelle-Saint-Aubin (near Le Mans) to extort cryptocurrency access codes.
    * *Source:* [Ouest-France](https://www.ouest-france.fr/societe/faits-divers/enlevement-et-sequestration-sur-fond-de-cryptomonnaies-des-affaires-de-louest-confiees-au-tribunal-judiciaire-de-paris-c8de59d6-fe14-11f0-be0e-292cccbfadc3)
9.  **Jan 2026 (Manosque) - Home Invasion:** A woman was assaulted and sequestered at her home by attackers demanding her partner's crypto keys; a USB drive was stolen.
    * *Source:* [Le Parisien](https://www.leparisien.fr/faits-divers/victime-dun-vol-de-cryptomonnaie-une-jeune-femme-sequestree-par-plusieurs-individus-cagoules-a-manosque-06-01-2026-WS2ED2I3UFHB7JRDMUE2XXRVYI.php) | [Ouest-France](https://www.ouest-france.fr/provence-alpes-cote-dazur/manosque-04100/vol-de-cryptomonnaies-une-femme-sequestree-a-manosque-par-des-personnes-encagoulees-fbc47bda-ebba-11f0-b3e3-e584d3ee0112)
10. **Feb 2026 (Isère) - The Magistrate:** A magistrate and her mother were kidnapped and held captive for 30 hours to extort her partner, a crypto startup associate. Six individuals were arrested.
    * *Source:* [The Guardian](https://www.theguardian.com/world/2026/feb/08/french-police-arrest-five-over-crypto-linked-magistrate-kidnapping) | [Le Monde](https://www.lemonde.fr/societe/article/2026/02/11/six-jeunes-mis-en-examen-a-la-suite-de-l-enlevement-d-une-magistrate-grenobloise-le-parquet-national-anticriminalite-organisee-enquete_6666389_3224.html)
11. **March 2026 (Yvelines) - Fake Police:** A couple was sequestered in Le Chesnay by individuals posing as police officers, forcing a transfer of €900,000 in Bitcoin.
    * *Source:* [Le Parisien](https://www.leparisien.fr/yvelines-78/le-chesnay-rocquencourt-900-000-euros-en-bitcoin-derobes-lors-dun-violent-home-jacking-09-03-2026-L2ZCB6SJSRB5VJJQEYSMI2ASTM.php) | [Franceinfo](https://www.franceinfo.fr/france/ile-de-france/yvelines/un-couple-de-quinquagenaires-sequestre-et-force-de-transferer-900-000-euros-en-bitcoins-dans-les-yvelines_7856444.html)
12. **April 2026 (Yonne) - Armed Commando:** A mother and son were kidnapped at their home by an armed commando demanding a crypto ransom. They were successfully rescued by the GIGN.
    * *Source:* [Le Monde](https://www.lemonde.fr/societe/article/2026/04/14/cryptomonnaies-une-mere-et-son-fils-liberes-par-le-gign-apres-leur-enlevement-en-bourgogne-quatre-personnes-interpellees_6679919_3224.html) | [Ouest-France](https://www.ouest-france.fr/societe/justice/enlevement-sur-fond-de-cryptomonnaies-dans-lyonne-six-personnes-agees-de-17-a-20-ans-mises-en-examen-14faa522-3a8d-11f1-9f4b-ab6e07a6e59a)
13. **April 2026 (Finistère) - Family Sequestered:** Five members of a family were sequestered in Ploudalmézeau by hooded individuals aiming to steal the father's cryptocurrency wallet (~€700k).
    * *Source:* [France 3](https://france3-regions.franceinfo.fr/bretagne/finistere/brest/5-membres-d-une-famille-de-ploudalmezeau-sequestres-pour-un-portefeuille-de-cryptomonnaie-3339032.html) | [20 Minutes](https://www.20minutes.fr/faits_divers/4219671-20260422-bretagne-famille-enfants-sequestree-delestee-700-000-euros-cryptomonnaies)
14. **May 2026 (Seine-et-Marne) - Fake Delivery:** A crypto-company CEO's wife was targeted at home in Villenoy by attackers posing as delivery workers; neighbors intervened; two suspects (ages 15 & 18) arrested with fake gun and zip ties.
    * *Source:* [Le Parisien](https://www.leparisien.fr/seine-et-marne-77/seine-et-marne-deux-interpellations-apres-un-cambriolage-rate-chez-un-patron-dune-societe-de-cryptomonnaie-21-05-2026-WZLKWTPGCRDJZJTB7RY25F5MKI.php) | [Ouest-France](https://www.ouest-france.fr/economie/cryptomonnaie/tentative-denlevement-sur-fond-de-cryptomonnaies-une-femme-sauvee-par-ses-voisins-en-seine-et-marne-c5add6d6-55e6-11f1-8fb2-d4cef07cd2eb)
15. **June 2026 (Bouches-du-Rhône) - Night Commandos:** In one night, a commando hit three homes (Marseille 13e, Gardanne, Gignac-la-Nerthe); two women seized in Gignac during a forced crypto transfer; four attackers caught in flagrante by BRB Marseille.
    * *Source:* [La Provence](https://www.laprovence.com/article/faits-divers-justice/2193885092828214/quatre-hommes-arretes-en-plein-braquage-sur-fond-de-cryptomonnaies-pres-de-marseille) | [Journal du Coin](https://journalducoin.com/actualites/crypto-4-hommes-marseille-serie-sequestrations-extorquer-cryptomonnaies/)

### United Kingdom

1.  **Nov 2025 (Oxford/London):** Five people traveling in a car were stopped by masked robbers and forced to transfer £1.1M in crypto.
    * *Source:* [The Guardian](https://www.theguardian.com/uk-news/2025/nov/19/four-arrested-after-luxury-watch-cryptocurrency-stolen-oxford)

### Canada

1.  **Nov 2024 (Toronto):** Dean Skurka (CEO of WonderFi) forced into a vehicle, held for $1M ransom.
    * *Source:* [CBC](https://www.cbc.ca/news/canada/toronto/crypto-bitcoin-price-ceo-toronto-kidnapping-1.7378241)
2.  **Dec 2022 (Ontario):** Aiden Pleterski ("Crypto King" Ponzi) kidnapped, beaten, and tortured.
    * *Source:* [BBC](https://www.bbc.com/news/world-us-canada-69023845)

### United States

1.  **May 2025 (New York):** "House of Horrors". An Italian entrepreneur lured to a Manhattan townhouse, held for 17 days.
    * *Source:* [CBC News](https://www.cbc.ca/news/world/world-us-cryptocurrency-related-crimes-1.7546701)
2.  **May 2024 (Connecticut):** A couple rammed in their Lamborghini and abducted.
    * *Source:* [CNBC](https://www.cnbc.com/2024/10/17/cryptocurrency-theft-google-kidnapping-lamborghi-bar-.html)

### United Arab Emirates

1.  **Oct 2025 (Dubai):** Roman Novak and his wife were kidnapped and later found murdered in the desert.
    * *Source:* [DL News](https://www.dlnews.com/articles/people-culture/russian-crypto-millionaire-found-dead-in-dubai/)

### Hong Kong

1.  **Dec 2025 (Sheung Wan) - The "Japanese Company" Heist:** Employees were robbed of $6.4M in cash/crypto by a gang.
    * *Source:* [SCMP](https://www.scmp.com/news/hong-kong/law-and-crime/article/3337905/hong-kong-police-arrest-15-over-hk50-million-robbery-japanese-firm-staff)

### Thailand / Singapore

1.  **Sep 2022 (Thailand):** Russian couple ambushed and forced to transfer $100k.
    * *Source:* [Bangkok Post](https://www.bangkokpost.com/thailand/general/2401755/russian-realtors-lose-b1-8m-in-extortion)
2.  **Jan 2020 (Thailand):** Mark Cheng (Singaporean) kidnapped.
    * *Source:* [The Straits Times](https://www.straitstimes.com/asia/se-asia/singaporean-man-kidnapped-in-thailand-by-fellow-singaporean-ransom-paid-in-bitcoins)

-----

# Future of CyberAttacks :robot:

*The battlefield is evolving. We are moving from static phishing to dynamic, AI-driven warfare.*

### 1\. AI-Driven Social Engineering

  * **Deepfakes:** Scammers use real-time video/voice cloning of CEOs or family members to authorize transactions. (Already seen in traditional finance; increasingly relevant for multisig and treasury governance.)
  * **The 82:1 Machine Identity Gap:** Enterprise environments now average ~82 machine identities (API keys, bots, autonomous AI agents) per human employee—creating a massive, often unmonitored attack surface that adversaries target instead of humans directly. [Source](https://www.paloaltonetworks.com/perspectives/the-821-problem-securing-the-invisible-majority/)
  * **Hyper-Personalization:** AI scrapes your entire digital footprint to create spear-phishing that is nearly indistinguishable from legitimate communication.

### 2\. Quantum Threats (Q-Day)

  * **"Harvest Now, Decrypt Later":** Nation-states are recording encrypted traffic today (including your transaction signatures). When Quantum Computers mature (predicted \~2029-2030), they will break current ECDSA encryption and derive private keys from old signatures.
  * **Defense:** You must migrate to Post-Quantum Cryptography (PQC) algorithms when they become available on chains like Ethereum.

### 3\. Data Poisoning & Supply Chain

  * **Malicious Libraries:** Attackers poison open-source code repositories (npm, pip) used by wallet developers, injecting dormant backdoors that activate only when large balances are detected.
  * **OpsSec Failures (2026 trend):** Private keys committed to GitHub (Taiko), AWS KMS policy gaps (Resolv), and vendor frontend injections (Polymarket) now rival smart-contract bugs as loss drivers.
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
  * **TRM Labs Intelligence:** [trmlabs.com/resources/blog](https://www.trmlabs.com/resources/blog) (State-actor attribution, hack trends).
  * **Chainalysis Threat Intel:** [chainalysis.com/blog](https://www.chainalysis.com/blog/) (Incident analysis and laundering patterns).
  * **Jameson Lopp — Physical Attack Tracker:** [github.com/jlopp/physical-bitcoin-attacks](https://github.com/jlopp/physical-bitcoin-attacks) (Open dataset of wrench attacks worldwide).
  * **Privacy Guides:** [PrivacyGuides.org](https://www.privacyguides.org)
  * **Revoke Cash:** [Revoke.cash](https://revoke.cash)

-----

> *Stay Safe. Stay Private. Don't Trust, Verify.*
