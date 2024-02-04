## Candy Machine UI Setup Guide

### Introduction

This guide gets you started with configuring the user interface (UI) for your Candy Machine, allowing users to mint NFTs using your custom SPL token through their Phantom wallets.

### Prerequisites

Before diving in, make sure you have these ready:

- A well-configured Candy Machine with details like price, quantity, token symbol, fees, SPL token account, token address, launch date, and creator information in its `config.json` file.
- A designated Phantom wallet for minting.
- A newly created SPL token (refer to Lesson Three for guidance).

### Steps

1. **SPL Token Setup:**

   - If you haven't already, create your SPL token following Lesson Three and note down its address.

2. **Candy Machine Configuration:**

   - Open your Candy Machine's `config.json` file and update:
      - `splTokenAccount`: Replace with your newly created SPL token account address.
      - `splToken`: Replace with your SPL token address.

3. **UI Configuration:**

   - Follow the "Quick Node: Set Up a Minting Site" tutorial to build a UI for your Candy Machine. This UI will let users connect their Phantom wallets and mint NFTs using your SPL token for payment.

4. **Minting Logic Adjustment:**

   - Modify your SPL project's minting logic (from Lesson Three) to mint NFTs to the user's Phantom wallet address. Alternatively, adjust the transfer function to deliver minted NFTs to your designated Phantom wallet.

5. **Testing:**

   - Give everything a thorough test by transferring or minting your SPL token to a Phantom account. Use the UI to mint NFTs, ensuring a smooth user experience when paying with your SPL token.

### Additional Notes

- Remember to replace placeholders with your specific information throughout the process.
- Double-check all configurations and code changes before deployment.
- Consider security best practices and testing thoroughly before making your Candy Machine public.

I hope this rephrased guide provides a clearer and more structured approach to setting up your Candy Machine UI!

