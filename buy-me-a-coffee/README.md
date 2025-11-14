# Buy Me A Coffee:

My very first website that interacts with the blockchain!


- [Buy Me A Coffee:](#buy-me-a-coffee)
- [Setup](#setup)
  - [Requirements](#requirements)
  - [Quickstart](#quickstart)

# Setup 

## Requirements

- [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  - You'll know you've installed it right if you can run: `git --version`
- [Metamask](https://metamask.io/)
  - This is a browser extension that lets you interact with the blockchain.
- [anvil](https://book.getfoundry.sh/reference/anvil/)
  - You'll know you've installed it right if you can run: `anvil --version` 

## Quickstart

1. Clone the repository

```bash
git clone https://github.com/bjuhir/buy-me-a-coffee
cd buy-me-a-coffee
```

2. Run the following command:

```bash
anvil --load-state fundme-anvil.json 
```

This will load a local blockchain with our smart contract already deployed.

3. Import the anvil key into your Metamask

When you run the `anvil` command from #1, it'll give you a list of private keys. [Import one into your metamask.](https://support.metamask.io/start/how-to-import-an-account/)

You'll now have a wallet with some funds associated with our anvil chain!

4. Add the anvil chain to your metamask

[Follow this](https://support.metamask.io/configure/networks/how-to-add-a-custom-network-rpc/) and use:
- Network name: Anvil
- New RPC URL: http://127.0.0.1:8545
- Chain ID: 31337
- Currency Symbol: ETH
- Block Explorer URL: None

After doing the setup above, do the following

1. Run the `index.html` file

You can usually just double click the file to "run it in the browser". Or you can right click the file in your VSCode and run "open with live server" if you have the live server VSCode extension (ritwickdey.LiveServer).

And you should see a small button that says "connect".

Hit it, and you should see metamask pop up.

2. Press some buttons!
