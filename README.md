
# 🚀 **Solana Copy Trading Bot** 🤖

🔗 **Powered by**: Jupiter Aggregator, Solana Web3.js, and SPL Token libraries.

Welcome to the **Solana Copy Trading Bot**, a cutting-edge tool designed to replicate successful trades on the Solana blockchain! This bot monitors live transactions, automatically executes trades, and optimizes profits, making it easier for you to stay ahead in the market. 🌍🔄💰

---

## 📖 **Key Features**

### 1. **Real-Time Transaction Monitoring** 🕒  
- **Live Monitoring**: Tracks Jupiter swap transactions in real-time using WebSocket.  
- **Key Insights**: Extracts essential details, including token addresses, amounts, and prices, as soon as the transaction occurs.

### 2. **Smart and Efficient Trade Execution** 🎯  
- **Automated Trading**: Executes buy or sell trades based on monitored swap data.  
- **Maximized Profits**: Ensures an optimal SOL balance while maintaining reserves for future trades.

### 3. **Comprehensive Token Metadata** 📊  
- **Token Info**: Retrieves metadata such as token name, symbol, and logo with the help of the Metaplex SDK.  
- **Market Value**: Calculates token prices and displays them in USD for clearer insights.

### 4. **Highly Customizable** 🔧  
- **Easy Configuration**: Adjust target wallet, buy/sell limits, and RPC endpoints to fit your needs with minimal effort.

### 5. **Advanced Analytics** 📈  
- **Transaction Logging**: Keeps detailed logs of transaction values and links to Solscan for transparency, ensuring you have full control and oversight of your trades.

---

## 📦 **Installation & Setup**

### 1. **Clone the Repository**  
```bash
git clone https://github.com/Bortoom/copy-trading-bot.git  
cd solana-copy-trading-bot
```

### 2. **Install Dependencies**  
```bash
npm install
```

### 3. **Configure Environment Variables**  
- Create a `.env` file and include the following details:  
```bash
PRIVATE_KEY=<your_wallet_private_key>  
RPC_ENDPOINT=https://api.mainnet-beta.solana.com  
RPC_WEBSOCKET_ENDPOINT=wss://api.mainnet-beta.solana.com  
TARGET_WALLET=<target_wallet_public_key>  
MAXIMUM_BUY_AMOUNT=<max_amount_in_SOL>  
JUP_AGGREGATOR=<jupiter_program_id>
```

---

## 🚀 **How to Use the Bot**

### 1. **Start the Bot**  
Simply run:  
```bash
npm run start
```

### 2. **What the Bot Does**  
- **Monitors**: Tracks live Jupiter swaps and logs the transaction details.  
- **Executes**: Automatically buys or sells SOL and tokens based on predefined trading conditions.  
- **Reports**: Displays transaction outcomes, including detailed links to Solscan for easy tracking.

---

## 🛠 **How It Works**

### 1. **Real-Time Transaction Monitoring**  
- The bot subscribes to Solana transaction streams using WebSocket for live updates.

### 2. **Data Extraction & Token Insights**  
- Extracts swap data and token metadata, including name, symbol, and logos, for better decision-making.

### 3. **Automated Trade Execution**  
- Automatically buys or sells tokens based on your custom-defined logic using the best available prices via Jupiter Aggregator.

---

## ⚡ **Example Output**

```plaintext
🚀 Swap: SOL ↔️ USDC  
💰 Amount: 2 SOL = 100 USDC  
💵 Value: 50 USD = 100 USD  
🔗 Transaction Link: https://solscan.io/tx/yourtxhash
```

---

## 🛡 **Safety Features**

- **Sufficient Balance**: The bot ensures that there is enough SOL balance before executing any trade.  
- **Smart Validation**: Invalid swaps and unsupported tokens are rejected, preventing potential losses.

---

## 💡 **Contributing**

We welcome contributions! If you’d like to help improve the bot, feel free to submit pull requests or report issues. Your input is always appreciated. 🛠

---

## 👨‍💻 **Author**

Developed by **dieharye** | [Telegram](https://t.me/midaBricoll)

🌟 **Happy Trading!** 🌟

---
