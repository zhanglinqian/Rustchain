# wRTC Quickstart Guide

wRTC is the wrapped version of RustChain Token (RTC) on the Solana blockchain. This guide walks you through how to buy, verify, and use wRTC safely.

**Table of Contents:**
- [Anti-Scam Checklist](#anti-scam-checklist)
- [Canonical wRTC Information](#canonical-wrtc-information)
- [Buying wRTC on Raydium](#buying-wrtc-on-raydium)
- [Bridging wRTC to BoTTube Credits](#bridging-wrtc-to-bottube-credits)
- [Withdrawing wRTC from BoTTube](#withdrawing-wrtc-from-bottube)

---

## Anti-Scam Checklist

**Before buying or bridging any tokens, ALWAYS verify:**

- [ ] **Verify the Mint Address** - Only trust this exact mint address: `12TAdKXxcGf6oCv4rqDz2NkgxjyHq6HQKoxKZYGf5i4X`
- [ ] **Verify Decimals** - Confirm the token has exactly **6 decimals** (not 9 or any other number)
- [ ] **Don't Trust Ticker Alone** - Scammers often create fake tokens with the same name/symbol. Always check the mint address.
- [ ] **Check Official Links Only** - Only use links from the official RustChain GitHub, RustChain.org, or BoTTube.ai.
- [ ] **Verify URL Before Connecting Wallet** - Scammers use typosquatting (e.g., `raydiumi.io` instead of `raydium.io`). Double-check the URL in your browser.
- [ ] **Start with Small Amounts** - Test with a tiny amount first before making large transactions.
- [ ] **Read Transaction Details** - Always review the transaction details in your wallet before confirming.

⚠️ **Warning:** If anything looks suspicious or different from this guide, STOP and ask in official RustChain/BoTTube communities.

---

## Canonical wRTC Information

| Property | Value |
|----------|-------|
| **Mint Address** | `12TAdKXxcGf6oCv4rqDz2NkgxjyHq6HQKoxKZYGf5i4X` |
| **Decimals** | `6` |
| **Symbol** | `wRTC` |
| **Network** | Solana Mainnet |

### Official Resources

| Resource | URL |
|----------|-----|
| **Raydium Swap** | https://raydium.io/swap/?inputMint=sol&outputMint=12TAdKXxcGf6oCv4rqDz2NkgxjyHq6HQKoxKZYGf5i4X |
| **BoTTube Bridge** | https://bottube.ai/bridge/wrtc |
| **Price Chart** | https://dexscreener.com/solana/8CF2Q8nSCxRacDShbtF86XTSrYjueBMKmfdR3MLdnYzb |
| **RustChain Website** | https://rustchain.org |

---

## Buying wRTC on Raydium

### Prerequisites
- A Solana wallet (Phantom, Solflare, or compatible wallet)
- Some SOL in your wallet for transaction fees

### Step-by-Step

1. **Visit the Official Raydium Swap Page**
   - Go to: https://raydium.io/swap/?inputMint=sol&outputMint=12TAdKXxcGf6oCv4rqDz2NkgxjyHq6HQKoxKZYGf5i4X
   - Verify the URL in your browser address bar

2. **Connect Your Wallet**
   - Click "Connect Wallet" in the top right corner
   - Select your wallet provider (e.g., Phantom)
   - Approve the connection request in your wallet popup

3. **Verify the Token**
   - Check that the "Sell" input shows **SOL**
   - Check that the "Buy" output shows **wRTC**
   - **Critical:** Click on the wRTC token and verify:
     - Mint address: `12TAdKXxcGf6oCv4rqDz2NkgxjyHq6HQKoxKZYGf5i4X`
     - Decimals: `6`

4. **Enter the Amount**
   - Type the amount of SOL you want to swap
   - Raydium will show you the estimated amount of wRTC you'll receive

5. **Review the Transaction**
   - Check the "Minimum received" and "Price impact" values
   - If the price impact is too high (>5%), consider reducing your amount

6. **Confirm the Swap**
   - Click "Swap"
   - Review the transaction in your wallet
   - Approve the transaction

7. **Wait for Confirmation**
   - Wait for the Solana transaction to confirm (usually 15-30 seconds)
   - You can check your balance in your wallet or on a Solana explorer

### Troubleshooting

**Error: "Insufficient SOL for fees"**
- You need at least 0.01 SOL for transaction fees. Add more SOL to your wallet.

**Error: "Slippage tolerance too low"**
- Increase the slippage tolerance setting (usually 0.1% - 3% is safe)

**Transaction stuck/pending**
- Solana network may be congested. Wait a few minutes and try again.

---

## Bridging wRTC to BoTTube Credits

BoTTube uses a bridge to convert wRTC into RTC credits for tipping on videos.

### Prerequisites
- wRTC in your Solana wallet
- A BoTTube account (create one at https://bottube.ai)

### Step-by-Step

1. **Visit the BoTTube Bridge**
   - Go to: https://bottube.ai/bridge/wrtc
   - Log in to your BoTTube account

2. **Connect Your Solana Wallet**
   - Click "Connect Wallet"
   - Select your wallet (Phantom, Solflare, etc.)
   - Approve the connection

3. **Deposit wRTC**
   - Enter the amount of wRTC you want to deposit
   - Click "Deposit" or "Bridge"
   - Approve the transaction in your wallet

4. **Wait for Confirmation**
   - The bridge will verify your on-chain transaction
   - Once confirmed, you'll see RTC credits in your BoTTube account

5. **Start Tipping**
   - Your RTC credits can now be used to tip videos on BoTTube!

### Bridge Details

| Property | Value |
|----------|-------|
| **Bridge Address** | BoTTube smart contract (handled automatically) |
| **Minimum Deposit** | Check current limits on the bridge page |
| **Bridge Time** | Typically 1-3 minutes (Solana confirmation + bridge processing) |

---

## Withdrawing wRTC from BoTTube

When you want to cash out or move your wRTC back to your wallet:

### Step-by-Step

1. **Visit the BoTTube Bridge**
   - Go to: https://bottube.ai/bridge/wrtc
   - Log in to your BoTTube account

2. **Check Your Balance**
   - Verify you have RTC credits available to withdraw

3. **Initiate Withdrawal**
   - Enter the amount of RTC credits you want to withdraw
   - Enter your Solana wallet address (double-check for typos!)
   - Click "Withdraw"

4. **Wait for Processing**
   - BoTTube will queue your withdrawal
   - Wait for the on-chain transaction to complete
   - Check your Solana wallet for the wRTC

### ⚠️ Important Notes

- **Withdrawal Fees:** There may be a small bridge fee for withdrawals
- **Minimum Withdrawal:** Check the minimum amount on the bridge page
- **Address Verification:** Always triple-check your wallet address. Mistyped addresses cannot be recovered.

---

## Frequently Asked Questions

### Q: What's the difference between RTC and wRTC?
**A:** RTC is the native token on the RustChain blockchain. wRTC is a wrapped version on Solana that makes it easier to trade and use. The bridge allows you to convert between them.

### Q: Is it safe to use the bridge?
**A:** Yes, as long as you use the official BoTTube bridge URL (https://bottube.ai/bridge/wrtc). Always verify the URL before connecting your wallet.

### Q: What if I send wRTC to the wrong address?
**A:** Transactions on Solana are irreversible. Always double-check addresses before sending.

### Q: How long do transactions take?
**A:** Solana transactions typically confirm in 15-30 seconds. Bridge operations may take 1-3 additional minutes for processing.

### Q: Can I bridge back and forth?
**A:** Yes, you can deposit wRTC to BoTTube and withdraw it back as many times as you want. Each transaction will incur network and bridge fees.

### Q: Who do I contact if something goes wrong?
**A:**
- RustChain GitHub Issues: https://github.com/Scottcjn/Rustchain/issues
- BoTTube Support: Check https://bottube.ai for contact options
- **Never share your private keys or seed phrase with anyone.**

---

## Security Best Practices

1. **Never share your private keys or seed phrase** - Not even with support staff.
2. **Always verify URLs** - Scammers often create fake websites that look real.
3. **Use hardware wallets for large amounts** - Consider a Ledger or Trezor for significant holdings.
4. **Keep your wallet software updated** - Security patches protect against vulnerabilities.
5. **Be skeptical of "free tokens" or "airdrops"** - These are common scam tactics.
6. **Double-check everything** - A few extra seconds of verification can save you from losing funds.

---

## Need Help?

If you encounter any issues or have questions:

- 📖 Read the [RustChain README](../README.md)
- 🐛 [Report an issue on GitHub](https://github.com/Scottcjn/Rustchain/issues)
- 💬 Check official community channels (linked on https://rustchain.org)

---

*Last Updated: 2026-02-12*
*For the latest information, always check the official RustChain website: https://rustchain.org*
