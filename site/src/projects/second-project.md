---
title: monero-merchant
emoji: 🪙
metaDescription: An app to enable Monero transactions at physical retailers
date: 2022-11-15T00:00:00.000Z
summary: An app that uses Node.js to enable merchants to accept Monero at physical retailers. It also will allow them to create QR codes for every product in their shop that act as payment requests for the amount specified by the merchant. Finally, the merchant will be able to track all of their transactions and sales statistics through the app as well.
tags:
  - Node.js
  - monero-javascript
  - monerod
  - monero-wallet-cli
---
### Currently Under Construction 🚧
### Task

Develop an application that allows merchants to accept Monero at their physical retailer seamlessly, and with little to no technical knowledge

### Solution

While the app is still being developed, the current solution utilizes Node.js through the [monero-javascript](https://github.com/monero-ecosystem/monero-javascript) library to access the Monero blockchain. I am currently hosting my own node to manage and upload transactions. The app will soon use monero-javascript to allow the merchant to accept Monero using simple QR codes, that a customer can scan to send the specified amount of Monero from their wallet to the merchant. The merchant will then be able to verify that the transaction has been completed, as well as view their transactions and sales statistics all within the app. Think [Square Point of Sale terminal](https://squareup.com/us/en/point-of-sale), but for Monero.
