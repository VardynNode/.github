# VardynNode

VardynNode is licensed trading software for Binance that you install and run on your own server. With VardynNode, your keys stay on your own server.

## Your keys stay on your server

Most trading bots ask you to hand over your API keys. With VardynNode, your keys stay on your own server: we never receive them and never hold your funds. It never needs withdrawal permission, and it is not custodial.

## What it does

You choose and configure one main strategy at a time, and it trades in USDT or USDC:

- **DCA**: buys on a schedule or when the price drops, within a budget per coin.
- **Directional** (Experimental): trend entries with stop-loss and take-profit.
- **Grid**: buys and sells across levels in a range.
- **Funding Rate Harvest** (Pro and Elite): runs alongside the main strategy.

It is not financial advice and not a promise of profit. Cryptocurrency trading involves substantial risk of loss.

## Get it

You need your own Ubuntu 24.04 LTS server (a computer you rent online). The guided installer takes about 15 minutes.

1. Start the free 30-day trial (testnet and paper, no card) at [vardynnode.com/download](https://vardynnode.com/download).
2. On the server, run the one-line install:

```
curl -fsSL https://get.vardynnode.com | sudo bash
```

Step by step: [Quick install](https://vardynnode.com/quickstart) and the [Installation guide](https://vardynnode.com/guide). Plans and prices: [Pricing](https://vardynnode.com/pricing).

Only download VardynNode from vardynnode.com. The only legitimate sources are vardynnode.com and get.vardynnode.com.

## Repositories

- [vardynnode](https://github.com/VardynNode/vardynnode): the installer and updater files that run on your server, the notes for every release, and `verify.sh` to check a download.

## Help

- [FAQ](https://vardynnode.com/faq)
- [Contact](https://vardynnode.com/contact) or [hello@vardynnode.com](mailto:hello@vardynnode.com)
- [Security policy](https://vardynnode.com/security): how to report a vulnerability
- [About](https://vardynnode.com/about) and our own [live account](https://vardynnode.com/live), shown as percentages and delayed 15 minutes

---

A product by Vardyn Technologies
