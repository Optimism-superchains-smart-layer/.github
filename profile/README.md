# Optimism's superchains smart layer
This Guide describes how to setup a smart layer's node on any EVM data availability layer, in this case ethereum (L1) or any op-stack chain (L2). 

# Getting started 
As a pre-requisite, you will need to install Node and Foundry. Follow the instructions in https://github.com/ethereum-optimism/optimism-starter for guidance. 

1. Clone/fork the superchain-relayer repo
   ```sh
   git clone https://github.com/ethereum-optimism/superchain-relayer.git
   ```
2. Install the necessary node packages:
   ```sh
   cd superchain-relayer
   npm install
   ```
3. Start the frontend with `npm run dev`
4. Open localhost:5173 in your browser