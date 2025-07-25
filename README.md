# 🌿 Tochka opory

**Tochka opory** (“Точка опоры” — _Point of Support_) is a therapeutic, privacy-focused dApp built for Russian-speaking users. It offers a soft digital space to reflect, ask deep personal questions, and interact with a mentor-like AI. The app integrates decentralized technology with human-centered design — aiming to support users emotionally, securely, and beautifully.

---

## 🌍 Languages & Cultural Intent

This application is designed primarily for **Russian-speaking users**, preserving linguistic and emotional nuance through native phrasing.  
Multilingual support (English and others) is planned for future versions.

---

## 💡 Project Goals

- 🧘 Enable gentle self-reflection and emotional awareness  
- 🤖 Build mentor-like interactions with AI based on simple keyword logic  
- 🔐 Ensure privacy through Zama’s FHEVM encrypted execution  
- 📜 Document real use cases for secure emotional dApps in Web3

---

## 🔗 Integration with Zama Builder Testnet

We actively tested this project on [Zama’s Builder Testnet](https://www.zama.ai/builder) — the first fully homomorphic EVM network.  
Test logs and contract interactions are documented in [`/testnet-journal`](./testnet-journal).

Our goals in Builder Testnet:

- Demonstrate encrypted feedback exchanges from user to contract  
- Create reflective journaling use cases that remain confidential  
- Prove real-world applications for FHEVM beyond finance: emotional safety, mentorship, and private growth  

The project also includes tasks from Zama’s [Guild](https://guild.xyz/zama-builder-guild), showcasing progression and meaningful exploration.

---

## ✨ Key Features

- 🌅 **First screen**: “Ты дома” — _You’re home_  
- 🪞 **Mirror Mode**: user interacts with reflective questions from AI  
- 🃏 **Card of the Day**: randomized prompts to start emotional clarity  
- 🔊 **Soundscapes**: calming background tracks (e.g., “Whispers of the Ocean”)  
- 💬 **Encrypted journaling**: all thoughts stored securely or deleted after session  

---

## 🛠️ Tech Stack

| Layer        | Tech                      |
|--------------|---------------------------|
| Frontend     | React + Vite              |
| AI Dialogue  | Simple keyword logic / mentor.js |
| Blockchain   | Solidity + FHEVM          |
| Storage      | IPFS (emotion cards, journals)  |
| Integration  | Zama Builder Testnet + Guild tasks |

---

## 🧪 Folder Overview

```shell
tochka-opory/
├── contracts/          # FHEVM-compatible smart contracts
├── frontend/           # Pages: safety, connection, mentor
├── scripts/            # wallet connection, contract deploy
├── testnet-journal/    # logs, screenshots, task proofs
├── README.md           # this file


## 🤝 Contributing

We welcome contributions from designers, devs, psychologists, and privacy researchers.  
Start by exploring `/cards/`, expanding `mentor.js`, or submitting prompts that feel “true enough to guide.”

🧘 Final Note
What if the place we hide our questions could become the place we finally find answers? Tochka opory offers not solutions, but space — encrypted, respectful, deeply yours.

📬 Contact
Author: Ainur Telegram: [@AinurSolar] X (Twitter): [@InurSolar91279] Farcaster: [farcaster.xyz/ainur-zk1]
Email: [jeneshka883@gmail.com]


---

🛡️ License
MIT — reuse with respect for emotional design and user integrity.

## 🔮 Future Roadmap

- Expand mentorship features
- Add multilingual prompt support
- Deploy to Zama’s encrypted mobile gateway
