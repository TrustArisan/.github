
# Trust Arisan

<img width="1024" height="457" alt="Logo-Banner-Perplexity-Generated-Crop" src="https://github.com/user-attachments/assets/0b85bc54-c933-4727-9a60-227312b6ec1a" />

<div align="center">
  
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![Foundry v1.4.4](https://img.shields.io/badge/Smart_Contract-Foundry_v1.4.4-blue)](https://getfoundry.sh/)
[![Remix v1.3.3](https://img.shields.io/badge/Smart_Contract-Remix_v1.3.3-yellow)](https://remix.live/)
[![Next JS v16.0.3](https://img.shields.io/badge/Front_End-Next_JS_v16.0.3-white)](https://nextjs.org/)

</div>

TrustArisan is a dedicated app for Arisan running in BNB Smart Chain (BNC) Blockchain for Decentralization, allowing security, transparancy, and fairness.

Our app allows creating instant room and start an Arisan session while maintaining transparency and fairness by allowing all member to see ledgers for information regarding participant, winners, and pool amount. The pooled amount is stored by Smart Contract with automated escrow to ensure no one, including developer, can meddle with the money stored. We provide a premium for all users for better room size in a subscription-based model to ensure that you use only during the time you need it.


## Authors

- [@PressToCode](https://www.github.com/PressToCode)
- [@fifahnashwa](https://github.com/fifahnashwa)
- [@rahmaliyyah](https://github.com/rahmaliyyah)
- [@JohanArizona](https://github.com/johanarizona)



## Features

- Light/dark mode toggle
- Fully transparent transaction
- Auto-escrow and ROSCA-based rotation
- Friendly UI/UX and Ease of use
- Comprehensive Documentation


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.


## Demo

Insert gif or link to demo


## Environment Variables (Smart Contract using Foundry)

To run this project, you will need to add the following environment variables to your .env file

`PRIVATE_KEY=YOUR_WALLET_PRIVATE_KEY`

`PLATFORM_WALLET=YOUR_WALLET_TO_RECEIVE_PLATFORM_FEE`


## Installation (Frontend)

Install frontend with npm

```bash
  git clone https://github.com/TrustArisan/frontend.git
  cd frontend
  npm install
```

## Installation (Smart Contract w/ Foundry)

To use smart contract, you need to install [Rust (recommended using rustup)](https://rustup.rs/) and [Foundry](https://getfoundry.sh/) on your local system

```bash
  git clone https://github.com/TrustArisan/smart-contract-foundry
  cd smart-contract-foundry
  forge install
```

## Run Locally (Frontend)

Start the server

```bash
  npm run dev
  // or you can run build and use static
  npm run build
```

## Run Locally (Smart Contract w/ Foundry)

Start the server

```bash
  forge build
  anvil
```

then in another terminal. Refer to [foundry docs](https://getfoundry.sh/cast/reference/cast/).

```bash
  cast deploy <your_settings>
```

## Running Tests (Smart Contract w/ Foundry)

To run tests, run the following command

```bash
  forge test
```


## FAQ

#### Question 1: Is there a demo website?

Yes, our website is at ...

#### Question 2: Can i try smart contract?

Yes, you can try [our deployed smart contract](https://sepolia.etherscan.io/address/0xf57c33757e01c9b0a597f488b63bf780b6e66e81) in Etherium Sepolia Testnet. Be mindful that it uses Eth as it's main transaction coin and may have fluctuating gas prices. For our mainnet deployment, we encourage that you use our existing app using BNB as transaction method.

