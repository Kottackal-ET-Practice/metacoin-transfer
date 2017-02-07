# metacoin-transfer

A small program using truffle framework to transfer metacoin.

Start the ethereum testrpc

```
> testrpc
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