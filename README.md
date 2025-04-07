# NFTMarketplace – Web3 NFT Interface for MuNFT Tokenized Items

This project is a full Web3 interface that allows users to create, sell, and buy tokenized NFT items based on Mu Online-style weapons. It connects directly to a smart contract deployed on the blockchain and provides a simple but complete marketplace experience using Metamask and Web3.js.

> 🧪 This frontend interacts with the contract defined in the [MuNFT](https://github.com/sbrunomello/MuNFT) repository.

---

## 🎮 Features

- Mint NFTs with custom attributes: `name`, `type`, `tier`, `price`, `imageURL`
- Put NFTs up for sale with a single transaction
- Buy NFTs directly by sending ETH
- Retrieve full NFT data by `tokenId`
- Real-time interaction with the blockchain via Metamask
- Fully functional HTML + JS interface

---

## 🛠 Technologies Used

- Solidity (contract lives in [MuNFT](https://github.com/sbrunomello/MuNFT))
- Web3.js
- JavaScript
- HTML/CSS
- Metamask

---

## ▶️ How to Use

### 1. Connect Wallet

Click the "Conectar Metamask" button to authorize and load your wallet.

### 2. Create NFT

Fill the form with the name, price, and item type (`AXE`, `SWORD`, etc.). The image will auto-load from `/img/{type}.png`.

### 3. Set NFT For Sale

Enter the token ID and set the sale flag to `true` or `false`.

### 4. Buy NFT

Provide the token ID and the exact price in WEI to buy the NFT.

### 5. Get NFT Info

Query any token ID and retrieve all data: owner, price, name, tier, type, sale status, and image.

---

## 🔗 Related Contract

All Web3 interaction is powered by the contract in:

👉 [`MuNFT`](https://github.com/sbrunomello/MuNFT)

---

## 📂 Project Structure

```
/js/crypto.js         → Web3 interaction logic
/css/style.css        → Basic styling
/img/{type}.png       → Weapon/item images
index.html            → Main marketplace UI
```

---

## 💡 Future Ideas

- Add dynamic rendering of owned NFTs in gallery
- Convert WEI to ETH and format prices
- Support multi-tiered rarity effects
- Audio/animation on item display (like games)
- Real-time listings and event listeners (onTransfer)

---

## 📬 Contact

- [GitHub Profile](https://github.com/sbrunomello)  
Built with 🛡️ by Mello
