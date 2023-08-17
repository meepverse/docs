---
title: Prepare your node
hide_table_of_contents: false
---

# Prepare your node

Type the following commands in the CLI of a UNIX based system to clone this repository to your local machine:

   ```bash
   # Clone the repository
   git clone https://github.com/shamirlabs/diva-alpha-net

   # Change directory
   cd diva-alpha-net/
   ```

To run a Diva node autonomously, you need to connect the Diva docker container to an execution client, a consensus client and a validator. Depending on your current setup, continue to one of the following options:

- If you don't have Ethereum clients running in the Goerli testnet, continue to [Option 1: Run with new ETH clients](new-clients).
- If you already have Ethereum clients running in the Goerli testnet, continue to [Option 2: Run with you own ETH clients](own-clients).


Take into account that both options contain telemetry images to help us monitor and improve the testnet. If you want to disable such telemetry, follow the instructions described in x.x.
