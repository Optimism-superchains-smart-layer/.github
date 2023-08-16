# Optimism's superchains smart layer
This Guide describes how to setup a smart layer's node on any EVM data availability layer, in this case ethereum (L1) or any op-stack chain (L2). 

# What is smart layer 
An OP-Stack chain that indexes its Data availability layer for events and let's smart contract developers register function hooks that should get executed when said events occur. Event's in this case could be normal events or a new L1 block being created. In summary, it creates EVM Event-Triggered Transactions and EVM Block-Triggered Transactions.

# Getting started 


1. Clone/fork the tweaked optimism monorepo 
   ```sh
   git clone https://github.com/Optimism-superchains-smart-layer/optimism.git
   ```
   
2. Build the Optimism Monorepo, by visiting:
   ```sh
   https://stack.optimism.io/docs/build/getting-started/#build-the-optimism-monorepo
   ```

3. Clone/fork the tweaked op-geth: 
   ```sh
   git clone https://github.com/Optimism-superchains-smart-layer/op-geth.git
   ```

4. Build the op-geth, by visiting:
   ```sh
   https://stack.optimism.io/docs/build/getting-started/#build-op-geth
   ```

5. Choice of Data Availability layer, ranges from ethereum, optimism, zora and base. As this is either an L2 or an L3, depending on this choice.

4. Open localhost:5173 in your browser
