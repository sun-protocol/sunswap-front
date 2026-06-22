# SunSwap-front

[English](./README.md) | [中文](./README_CN.md)

SunSwap is a TRON-based decentralized trading protocol for automated liquidity provision and an open financial market accessible to all. SunSwap supports secure and immediate exchange between any TRC20 tokens. Market makers will get service fees continuously without the platform taking any commission.

## Features

- **Token Swap** — Supports SunSwap V1, V1.5 multi-version trading.
- **Liquidity Pools** — When you add liquidity, you are given pool tokens representing your position. These tokens automatically earn fees proportional to your share of the pool, and can be redeemed at any time.
- **Scan** — Explore tokens, trading pairs, liquidity data, volume, and hot tokens on-chain. Supports candlestick charts, liquidity/volume analytics, and detailed pair/token information.
- **SUN Buyback & Burn** — Continuous token buyback & burn to empower the community ecosystem.
- **Multi-Wallet Support** — TronLink, Binance Wallet, WalletConnect, TokenPocket, Bitget Wallet, OKX Wallet, Ledger.

## Deployment

This repository contains pre-built static files ready to be served by any web server.

### Nginx

```nginx
server {
    listen 80;
    server_name your-domain.com;
    root /path/to/build;
    index index.html;

    location / {
        try_files $uri $uri/ /index.html;
    }
}
```

### Any Static File Server

The build output can also be served via any static hosting provider (e.g., AWS S3 + CloudFront, Vercel, Netlify, IPFS).

## Supported Wallets

- [TronLink](https://www.tronlink.org)
- [Binance Wallet](https://www.binance.com/en/web3wallet)
- [WalletConnect](https://walletconnect.com)
- [BitKeep (Bitget Wallet)](https://web3.bitget.com)
- [OKX Wallet](https://web3.okx.com)
- [TokenPocket](https://www.tokenpocket.pro)
- [Ledger](https://www.ledger.com)

## Internationalization

SunSwap supports three languages:

- English (`en-US`)
- Simplified Chinese (`zh-CN`)
- Traditional Chinese (`zh-TC`)

Language can be switched via URL parameter (e.g., `?lang=en-US`) or through the in-app language selector.

## Security

If you discover a security vulnerability, please report it responsibly. Do **not** open a public issue. Instead, reach out to the team via the official channels listed at [sunswap.com](https://sunswap.com).

## Links

- Website: [https://sunswap.com](https://sunswap.com)
- Twitter: [https://x.com/OfficialSUNio](https://x.com/OfficialSUNio)
- Telegram: [https://t.me/officialsunecosystem](https://t.me/officialsunecosystem)
