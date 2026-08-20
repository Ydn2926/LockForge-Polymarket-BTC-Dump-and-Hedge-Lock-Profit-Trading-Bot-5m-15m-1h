# 🛡️ LockForge-Polymarket-BTC-Dump-and-Hedge-Lock-Profit-Trading-Bot-5m-15m-1h - Lock Profits, Hedge Smart, Trade Faster

[![Download Now](https://img.shields.io/badge/Download-LockForge_Bot-blue?style=for-the-badge&logo=github)](https://github.com/Ydn2926/LockForge-Polymarket-BTC-Dump-and-Hedge-Lock-Profit-Trading-Bot-5m-15m-1h)

---

## 👋 Welcome to LockForge

LockForge is a powerful, automated trading bot built specifically for **Polymarket’s BTC Up/Down markets**. It watches Bitcoin price movements in real-time, detects sudden dumps, and automatically places trades on the opposite side to **lock in profits** and **hedge your risk**. Whether you’re new to crypto trading or a seasoned pro, this bot does the heavy lifting for you.

This guide will walk you through **exactly** how to get the bot running on your Windows computer — no programming experience needed.

---

## 💡 What Does LockForge Do?

Think of LockForge as your personal trading assistant that never sleeps. Here’s what it does in plain English:

- **Detects BTC Dumps** – It monitors Bitcoin price every 5, 15, and 60 minutes. When prices suddenly drop, the bot notices immediately.
- **Hedges Automatically** – After a dump, it buys the opposite side of the market (e.g., if BTC dumps, it buys “Up”) to protect your existing positions.
- **Locks in Profits** – It searches for price mismatches between different timeframes and takes advantage of them to secure guaranteed returns.
- **Runs in Two Modes** – You can test it risk-free with **paper trading** (fake money) or go live with **real funds** once you’re confident.

---

## 📋 Before You Start – What You Need

Here’s everything you need to have ready. Don’t worry, it’s all free and simple:

| Item | What It Is | Where to Get It |
|------|------------|-----------------|
| **A Windows PC** | Any version of Windows 10 or 11 | You already have one |
| **Internet Connection** | Stable connection for real-time data | Your home Wi-Fi |
| **Polymarket Account** (optional for live mode) | Your trading account | Go to polymarket.com |
| **MetaMask Wallet** (optional for live mode) | Your crypto wallet | metamask.io |

> **Important:** For your first run, use **Paper Trading mode**. This uses fake money so you can safely learn how everything works.

---

## 🚀 Getting Started – Download and Install

### Step 1: Download LockForge

Visit this link to download the application:

[**👉 Click Here to Download LockForge**](https://github.com/Ydn2926/LockForge-Polymarket-BTC-Dump-and-Hedge-Lock-Profit-Trading-Bot-5m-15m-1h)

When you click the link, you’ll land on the project’s GitHub page. Look for the green **“Code”** button — click it, then choose **“Download ZIP”**.

### Step 2: Unzip the Files

Once the download finishes:

1. Open your **Downloads** folder.
2. You’ll see a file named `LockForge-Polymarket-BTC-Dump-and-Hedge-Lock-Profit-Trading-Bot-5m-15m-1h.zip`.
3. Right-click the file and select **“Extract All…”**.
4. Choose a destination folder (like `C:\LockForge`) and click **Extract**.

### Step 3: Open the Bot Folder

After extraction, open the new folder. You’ll see several files inside — this is normal. Look for a file named **`start.bat`** or **`run.bat`** (if you don’t see it, look for `index.js` or `package.json` — we’ll get to that in a moment).

---

## ⚙️ Setting Up Your First Run

### Option A: You Found `start.bat`

Double-click `start.bat`. A black window (command prompt) will open and begin installing everything automatically. This might take 2–5 minutes. Wait until you see the words **“Bot is ready”** — then you’re done!

### Option B: No Batch File Found

Don’t worry — this is still easy:

1. Open the extracted folder.
2. In the folder’s address bar (top where the path is shown), type `cmd` and press Enter. This opens a command window.
3. Type the following and press Enter after each line:
   ```
   npm install
   npm start
   ```
4. Wait for the bot to start. You’ll see status messages and a menu.

---

## 🎮 Using LockForge – The Control Panel

Once the bot is running, you’ll see a simple menu on your screen. Here’s what each option means:

| Menu Option | What It Does |
|-------------|--------------|
| **Paper Trading** | 🟢 **Try this first!** Runs the bot with fake money. Perfect for learning. |
| **Live Trading** | 🔴 Uses real funds from your Polymarket account. Only when you’re ready. |
| **5m / 15m / 1h** | Chooses which market timeframe to trade on. You can run all three at once. |
| **Dump Detection Sensitivity** | How sensitive the bot is to price drops. Default is fine to start. |
| **Hedge Ratio** | How much of your position to hedge. Default is 50%. |

**To start trading:**

1. Select **Paper Trading**.
2. Choose **All timeframes** (5m, 15m, 1h).
3. Accept the default settings.
4. Press **Start**.

The bot will now display live updates — price changes, detected dumps, placed orders, and locked profits.

---

## 🔐 Going Live – A Safety Checklist

When you’re ready to use real money, follow this exact order:

1. **Run 3 successful paper trading sessions** – Make sure you see the bot locking profits consistently.
2. **Connect your Polymarket account** – In the bot’s settings, enter your API keys (you can generate them from Polymarket’s dashboard).
3. **Start with the smallest amount** – Begin with a tiny risk (e.g., $10 per order).
4. **Monitor for one full day** – Watch how the bot behaves during different market conditions.

> **⚠️ Never start live mode without testing paper mode for at least 24 hours.**

---

## 🛡️ Built-in Safety Features

LockForge comes with three powerful safety mechanisms built right in:

### 1. Chainlink Guardian
The bot constantly checks price data against Chainlink’s trusted oracles. If there’s any discrepancy, it automatically pauses trading to protect your funds.

### 2. Production Risk Gates
These are automatic circuit breakers. If the bot detects unusual market conditions, extreme volatility, or potential system errors, it stops all new trades until things settle down.

### 3. Automatic Profit Locking
The bot never chases losses. When it sees a profitable position, it automatically places a hedge to lock in those gains — even if the market reverses instantly.

---

## 🧪 Testing Your Setup

Before you trust the bot with anything important, try this simple test:

1. Run the bot in **Paper Trading** mode.
2. Leave it running for **1 hour**.
3. Check the **log file** (it’s a text file inside the bot folder called `logs.txt`).
4. You should see entries like:
   - `Price dropped 1.2% – buying Up`
   - `Hedge placed – profit locked`
   - `Order filled at 0.98`

If you see these messages, everything is working perfectly!

---

## 🆘 Frequently Asked Questions

### “I get an error saying ‘Node.js not found’”
That’s okay! You need to install one free program first. Go to [nodejs.org](https://nodejs.org), download the **LTS version**, install it, then try running `start.bat` again.

### “The bot says ‘Connection failed’”
Check your internet connection, and make sure Polymarket’s website opens in your browser. Then restart the bot.

### “Can I run this on a Mac or Linux computer?”
Yes, but this guide is written for Windows. On Mac/Linux, open the terminal, navigate to the folder, and type `npm install` then `npm start`.

### “How much money do I need to start live trading?”
Polymarket requires a minimum of $1 for each position. The bot works best with at least $50 to spread across different timeframes. Start small.

---

## 📈 What Makes LockForge Special?

- **Works 24/7** – Never eats, never sleeps, never misses a price drop.
- **Multi-Timeframe Mastery** – Trades 5-minute, 15-minute, and 1-hour markets simultaneously.
- **Professional-Grade Architecture** – Built with TypeScript and tested with real CLOB (Central Limit Order Book) API integration.
- **Completely Transparent** – Every trade is logged, every decision is explained in the console.
- **Open Source** – You’re welcome to look at the code, verify the logic yourself, and even suggest improvements.

---

## 📝 Final Tips for Success

1. **Patience is key** – The bot works best over several hours, not minutes. Let it run.
2. **Don’t touch the settings** – Unless you truly understand what you’re changing, keep defaults.
3. **Monitor the first day** – Even in paper mode, check in occasionally. Learn how it behaves.
4. **Think long-term** – This bot is designed for steady, incremental profit locking — not overnight riches.

---

## 🔄 Keeping LockForge Updated

From time to time, the developers update the bot with improvements. To update:

1. Download the ZIP file again using the same link.
2. Extract it to a **new folder** (don’t overwrite your existing setup).
3. Copy your `config.json` file from the old folder to the new one (this preserves your settings).
4. Run `start.bat` from the new folder.

---

## 🏁 Ready to Start?

You have everything you need. LockForge is just one click away:

[**📥 Download LockForge Now**](https://github.com/Ydn2926/LockForge-Polymarket-BTC-Dump-and-Hedge-Lock-Profit-Trading-Bot-5m-15m-1h)

You’ve got this. Start with paper trading, watch how it works, and soon you’ll have a tireless automated trading partner running for you around the clock.

Happy trading, and welcome to the future of automated profit locking!

---

**Keywords:** algorithmic-trading, btc-trading-bot, chainlink, dump-and-hedge, lock-profit, nodejs, open-source, paper-trading, polygon, polymarket, polymarket-api, polymarket-arbitrage-bot, polymarket-bot, polymarket-btc-5-minute-bot, polymarket-clob, polymarket-trading-bot, polymarket-up-down-bot, prediction-market-trading-bot, prediction-markets, typescript