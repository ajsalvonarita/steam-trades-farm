# Node.Js Steam Trade Farm for Replit

## Increase amount of "Trades Made"

It's fork of https://github.com/RobertSkonieczny/node-steam-trade-farm

## Starting amount.
![Trades Made Example](https://gyazo.com/c90de4cbb61d720b458170475399728e.png)

## 8 hours later
![Trade Made Result Example](https://gyazo.com/f251d419d5eb64efa55791e9b8f17570.png)

## Features
- Increase amount of trades made. (500+ Trades an hour!)
- Automatically send trades from your main account and bot account.
- Message security to ensure all trades accepted are secure and is from the other bot account.

## Installation Guide

- Register repl.it account
- Run on replit https://replit.com/new/github/Gunthersuper/node-steam-trade-farm-replit
  - You will be redirected to Replit, you might have to create an account (you can Register with Google).
  - Replit is a website, and does not run off your computer!
- Edit this config for your accs:
```
"shared_secret1": "randomStringOfChars418=",
"identity_secret1": "randomStringOfChars21w=",
"username1": "Robbie",
"password1": "Password",
"tradelink1": "https://steamcommunity.com/tradeoffer/new/?partner=202877252&token=04S9nN_6",

"shared_secret2": "randomStringOfChars418=",
"identity_secret2": "randomStringOfChars21w=",
"username2": "Robbie",
"password2": "Password",
"tradelink2": "https://steamcommunity.com/tradeoffer/new/?partner=202877252&token=04S9nN_6",

"gameCode" : "440"
```
  - `440` - Team Fortress 2, `304930` - Unturned (You must have some items in the inventory)
  
- Go to secrets, Edit raw JSON. Paste your config.
- Run the bot
