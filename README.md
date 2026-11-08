# GSPC Exchange Embeddable Swap & Rate Calculator Widget

A lightweight, responsive, dark-mode crypto swap and price calculator widget powered by **[GSPC Exchange](https://exchange.gspcoin.us)**.

## Live Demo
👉 **[https://gamgsp.github.io/gspc-swap-widget/](https://gamgsp.github.io/gspc-swap-widget/)**

## Supported Cryptocurrencies (21 Assets)
Direct rate calculation across 21 multi-chain cryptocurrencies:
- **Core Ecosystem:** GSPC, BTC, ETH, LTC
- **Stablecoins:** USDT (BEP-20 / TRC-20), USDC (BEP-20 / TRC-20)
- **Layer 1 & High-Throughput:** BNB, SOL, XRP, DOGE, ADA, TRX, AVAX, SUI, NEAR
- **UTXO & Privacy:** BCH, ETC, DASH, ZEC, KAS, DGB

## How to Embed

Add this iframe to any website, blog, documentation, or dApp:

```html
<iframe 
  src="https://gamgsp.github.io/gspc-swap-widget/" 
  width="100%" 
  height="480px" 
  frameborder="0" 
  style="border-radius: 16px; box-shadow: 0 8px 32px rgba(0,0,0,0.4);" 
  allow="clipboard-write">
</iframe>
```

## Features
- **Auto-fetching Rates**: Connects to the public `/api/v1/summary` endpoint on GSPC Exchange.
- **21 Assets Supported**: Full coverage of all exchange digital assets and 100+ pairs.
- **1-Click Deep Links**: Sends traders straight to the GSPC Exchange Swap terminal.
- **Pure Self-Custody**: Zero custodial escrow security guarantees.
