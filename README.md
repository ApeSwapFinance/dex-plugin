# ApeSwap DEX Plugin 🐵
This repo gives a quick overview on ApeSwap's current DEX plugin capabilities, to harness the full power of our smart router, and bonus router all on your platform!


## Setting Up the Plugin
The plugin utilizes a pretty commonly accepted iFrame to host ApeSwap's platform on your UI. Without any customization, it may look something like:

```
<iframe src="https://apeswap.finance/swap" width="400px" height="700px" scrolling="no" />
```

For a working demo, clone this repo & open the `index.html` file on your local machine.


## How it Works
ApeSwap's frontend senses if the host of our application is through an iFrame. If it turns out to be the case, we hide the non essentials, such as the nav bar & footer.

Users still have the core functionality:
- Connect Wallet
- Swapping
- Mulitchain
- Liquidity Adds / Removals
- Limit Orders (on BNB Chain)

There are tradeoffs to this approach of course.

From a positive perspective - whether you have a legacy web2 app, a web3 dapp, or anything in between - this offers the entire power of ApeSwap's DEX with a single line of code on your frontend. You can get up and running in no time.

This comes at the cost of customization, feature selection, and some usability. If you're looking for a more bespoke solution, please get in touch with our product team!