# Uniswap V3 Built Locally

![Front-end application screenshot](/screenshot.png)

## How to Run
1. Install [Foundry](https://github.com/foundry-rs/foundry).

1. Install the dependencies:
    ```shell
    $ forge install
    $ cd ui && yarn
    ```
1. Run Anvil:
    ```shell
    $ make anvil
    ```
1. Set environment variables and deploy contracts:
    ```shell
    $ source .envrc
    $ make deploy
    ```
1. Start the UI:
    ```shell
    $ cd ui && yarn start
    ```
1. Connect MetaMask to the blockchain network
![image](https://github.com/n0bitaemon/uniswap-delayswap/assets/103978452/cf9f4017-3d83-4bff-af4a-87b97b56d1c7)

1. Get informations
The metamask account's information is shown on the console
![image](https://github.com/n0bitaemon/uniswap-delayswap/assets/103978452/ae26b5d7-2207-40ca-8f34-5809904ca6cc)
![image](https://github.com/n0bitaemon/uniswap-delayswap/assets/103978452/cec2a768-3515-4573-8342-3c310665ee71)

Using these information to test uniswap's functionality!

# Machine Learning Algorithm
The machine learning code is located at `ML` folder
