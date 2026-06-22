# SunSwap-front

[English](./README.md) | [中文](./README_CN.md)

SunSwap 是基于波场的去中心化交易协议，为自动化流动性供应商提供开放金融市场，任何用户都可以参与。支持任意 TRC20 通证兑换，安全可靠，即时成交。成为做市商可获取持续交易手续费，平台不收取任何佣金。

## 功能特性

- **通证兑换** — 支持 SunSwap V1、V1.5 多版本交易。 
- **流动性池** — 当您添加流动性时，您会获得代表您仓位的池代币。这些代币会按照您在池中的份额比例自动赚取手续费，并可随时赎回。
- **浏览器** — 探索链上通证、交易对、流动性数据、交易量及热门通证。支持 K 线图、流动性/交易量分析以及详细的交易对/通证信息
- **SUN 回购销毁** — 代币持续回购&销毁，价值赋能社区生态
- **多钱包支持** — TronLink、Binance Wallet、WalletConnect、TokenPocket、Bitget Wallet、OKX Wallet、Ledger。

## 部署

本仓库包含预构建的静态文件，可由任何 Web 服务器提供服务。

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

### 其他静态文件服务器

构建产物也可以通过任何静态托管服务提供（如 AWS S3 + CloudFront、Vercel、Netlify、IPFS）。

## 支持的钱包

- [TronLink](https://www.tronlink.org/)
- [Binance Wallet](https://www.binance.com/en/web3wallet)
- [WalletConnect](https://walletconnect.com/)
- [BitKeep (Bitget Wallet)](https://web3.bitget.com/)
- [OKX Wallet](https://www.okx.com/web3)
- [TokenPocket](https://www.tokenpocket.pro/)
- [Ledger](https://www.ledger.com/)

## 国际化

SunSwap 支持三种语言：

- English (`en-US`)
- 简体中文 (`zh-CN`)
- 繁体中文 (`zh-TC`)

可通过 URL 参数切换语言（如 `?lang=zh-CN`），也可通过应用内的语言选择器进行切换。

## 安全

如果您发现安全漏洞，请负责任地报告。请**不要**提交公开 Issue，而是通过 [sunswap.com](https://sunswap.com) 上列出的官方渠道联系团队。

## 相关链接

- 官网：[https://sunswap.com](https://sunswap.com)
- Twitter：[https://x.com/OfficialSUNio](https://x.com/OfficialSUNio)
- Telegram：[https://t.me/officialsunecosystem](https://t.me/officialsunecosystem)
