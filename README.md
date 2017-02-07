# metacoin-transfer

A small program using truffle framework to transfer metacoin.

Start the ethereum testrpc

```
> testrpc

EthereumJS TestRPC v3.0.3

Available Accounts
==================
(0) 0x89cb12172c1c35bb41d3e981dc280052fd6112ee
(1) 0xada62f4ad8a1a687987c9bfbab1773d0e8528ed6
(2) 0x0a3f768c27d68a6f78797cd502cc1cf8fec2f07a
(3) 0x9b0e94f0efd4550da3c51795acfb874e5e68daaf
(4) 0xd6f4771dc4517637075e1f265626bd36267b28e7
(5) 0xbdb09c8b5fbd0108466d5fefdb972684abcb894a
(6) 0x44f221beca83c3c6435a58f9d35fe697fd681184
(7) 0x3df835bb2fb5b2f4fe34d1c45a9f3ce9898ae2e4
(8) 0x202bc6d21c464f9b3134315774beac3428a86fde
(9) 0xbcc32ac3d6eb618bdcdfe4575fbd70db5c23350f

Private Keys
==================
(0) bd65dea349499710e07eaef4b000046875e3244156acaa226dd256a704dff4b4
(1) 1557812fb3f535bb46ffd093314e7bb03f3f9a323f00b4a99ff2c9f704fee2d8
(2) 27f0213c5e356d974792bf15525f8c515089348fb2528bc00121d34ede21e878
(3) 3e9768da588a726ca1a78ee9410760f9b140d0af1879aac87dbcf67a43c9e46d
(4) 7d9a93303ec16a5c42980e90ff2c82de4183870df39770a58fe4ee41a64b3a46
(5) 200be400fb6c2f3a1c3b88950640477e60725662b0c7bbe1cc3591f36910a384
(6) 185b5e1c8d0f3a28d437c1ef1ed6b627555822ce27a63f3519c5c01d54b598b6
(7) 0599d449766aa04b54838ee5301930012480f4132baa1627c5b1bde61167a2c1
(8) 9a1ecde392a8b45a87df8d0509efae4105f0f3d6240b8f6ce8af70b99e3114f3
(9) 60fcb1c8ad0ea9841e798a1b76e492dcce3daec7f9b668a33b3f2cad94f6d9b6

HD Wallet
==================
Mnemonic:      maze beef cinnamon girl ethics flee wide fat inner air unknown three
Base HD Path:  m/44'/60'/0'/0/{account_index}

Listening on localhost:8545

```

Deploy the code to the ethereum test network

```
> truffle migrate

Running migration: 1_initial_migration.js
  Replacing Migrations...
  Migrations: 0x6eba5c35f55b9cc14d26f6f65d14808ab2dcebe0
Saving successful migration to network...
Saving artifacts...
Running migration: 2_deploy_contracts.js
  Replacing ConvertLib...
  ConvertLib: 0xcb73ca366f0e5490710220a270152fb4ee646f5e
  Linking ConvertLib to MetaCoin
  Replacing MetaCoin...
  MetaCoin: 0xa364f5c4eeb33bd555043ece3e7d2e3d483f7c76
Saving successful migration to network...
Saving artifacts...

```

To start the server

```
> truffle serve

Serving app on port 8080...
Rebuilding...
Completed without errors on Tue Feb 07 2017 11:15:42 GMT+0530 (IST)

```

Go to the link http://localhost:8080/ in your browser