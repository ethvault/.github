# Ethvault

We are building infrastructure for deploying and executing transactions from a cross-chain multisig.

- Gas-optimized multisig EVM smart contracts, homed on Ethereum L1
- Free ENS name
- Ethvault provides 2 signers
  - Legacy signer that allows your wallet to be recovered in case of catastrophe (signatures are timelocked for 1 year)
  - Hot signer
- Transaction relaying and gas abstraction
- Gas refunds on batched transactions

Please get in touch if you are interested in working together!

The API is live and can be introspected via its [OpenAPI 3.0](https://swagger.io/specification/) specification. This is accessible at [api.myethvault.com/api.json](https://api.myethvault.com/api.json). Any OpenAPI 3.0 explorer will work, e.g. [the hosted Swagger Petstore explorer](https://petstore3.swagger.io/?url=https://api.myethvault.com/api.json).
