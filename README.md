# Solana Candymachine NFT

Simple overview of use/purpose.

## Description

This project unites Solana tokens and the creation of a Candy Machine UI for a Candy Machine NFT Contract. The unique aspect here is prompting users to pay using a created SPL token for the minting process.

## Getting Started

- Ensure you have a deployed Candy Machine NFT Contract and have minted NFTs.
- Create or use an existing SPL token for payment.

### Installations

- Nodejs installed (version 16.15 or higher)
- Solana CLI installed
- Phantom Wallet or Solflare extension installed 
- Metaplex Sugar installed (Legacy Version, V1.x )

### Executing program

1. Create an SPL token:

    - Implement an SPL token following lessons or use a previously created token.

2. UI Development for Candy Machine:

    - Set up a UI for the Candy Machine using the provided tutorial.
    - Update start script in package.json to prevent ERR_OSSL_EVP_UNSUPPORTED error.

3. Token Payment Integration:

    - Ensure the UI enables payment using the SPL token created in Step 1.
    - Test minting by transferring or minting the SPL token to a Phantom account and attempting to mint on the website.


## License

This project is licensed under the MIT License - see the LICENSE.md file for details