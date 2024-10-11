
## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/vmmunoza/ScaffoldETH-MetisDemo.git
    cd ScaffoldETH-MetisDemo
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Run the local Ethereum environment:
    ```bash
    yarn chain
    ```

4. Deploy contracts:
    ```bash
    npm run deploy
    ```

## Usage

- Start the frontend:
    ```bash
    npm start
    ```
- Visit `http://localhost:3000` to interact with the dApp.

## Configuration

- Edit `.env` for environment variables like RPC URLs for testnets or mainnets.
- Smart contracts can be modified in the `/contracts` directory.

## Dependencies

- [Scaffold-ETH 2](https://github.com/scaffold-eth/scaffold-eth-2)
- Node.js & Npm
- Solidity

## Examples

- Deploy to Metis mainnet using:
    ```bash
    npm run deploy -- --network andromeda
    ```

## Troubleshooting

- Ensure you have the correct environment variables set in `.env`.
- Check RPC URL configurations and Metis network details for errors.



Deployed contract : [link](https://andromeda-explorer.metis.io/tx/0x84b92fe082b743807f74c8fe75351cd3c93605dcc77189fb3173c33d81554205)

Dapp homepage 
![image](https://github.com/user-attachments/assets/35d7e65c-d317-42c5-b21e-370d2aefa354)
![image](https://github.com/user-attachments/assets/2234aabd-02c1-4565-912b-4ec46648e3ba)
![image](https://github.com/user-attachments/assets/2e38e5b7-b7e2-4930-90bd-d0ef89f75efd)



