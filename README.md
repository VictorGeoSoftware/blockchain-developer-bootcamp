# My very first Blockchain project

This project demonstrates a basic Blockchain implementation. It's mainly about showing up a web with several components for tracking all the generated Blockchain operations.
The "backend" part of the project is based on Solidity and deployed on a local blockchain (Hardhat).

**Starting it up**
If you don't have npx installed, do:
- npm init -y
- npm install --save-dev hardhat

When you have npx installed, in a terminal window, do:
1.- npx hardhat node

Open another tab

2.- npx hardhat run —network localhost scripts/1_deploy.js

3.- npx hardhat run —network localhost scripts/2_seed_exchange.js

Open a new terminal

4.- npx react-scripts start
