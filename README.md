# .anon domains web app

You can mint and manage .anon domains on Polygon (Mumbai Testnet). You can:
- see what other domains have been minted so far
- mint new domains
- change your domain(s) to point to something else
  
## Deployed contract address

[`0xdE1FDEaE1c5Ad2A5c6b8947dfb38708d7918B3B5`](https://mumbai.polygonscan.com/address/0xdE1FDEaE1c5Ad2A5c6b8947dfb38708d7918B3B5)

** Note ** -- every time you deploy changes to the contract to Mumbai Testnet, you need to copy the ABI from [`anon-domains`](https://github.com/0xSmartCrypto/anon-domains) to this repo, with this command:
`npm run cp`
## Quickstart

To get started, 

1. Clone the [`anon-domains`](https://github.com/0xSmartCrypto/anon-domains) repo.

2. Clone this repo. Place your directories as:
```
.
   |-anon-domains
   |-anon-domains-frontend
```

3. Run `npm install` at the root of both `anon-domains` and `anon-domains-frontend` directories

4. Follow the instructions in the `anon-domains` README.md file
 
5. Run `npm run start` to start the web app


### What is the overall project structure?

```
.
   |-anon-domains
   |-anon-domains-frontend
```