# Solana-Tools

A bunch of tools to help people in the Solana ecosystem. This website includes:
- a UI to burn Solana NFTs
- a UI to burn SPL-tokens
- a UI to close empty accounts
- a multi sender (a UI to send multiple tokens in 1 transaction (same token to different people/many tokens to one person/transfer solana domain name)
- a UI to create SPL-Tokens
- a UI to upload file to Arweave
- a UI to update the metadata of your NFT
- a UI to send a NFT message to the owner of your desired NFT or solana domain name
- More tools are scheduled...

## Getting Started

Clone the repo, install the dependencies and run `yarn run dev` to run the development server.

```bash
git clone https://github.com/Immutal0/solana-tools.git
cd solana-tools
yarn install
yarn run dev
```


## Burn NFT UI
A UI for burning Solana NFTs and getting back $SOL from the associated token account.

## Burn SPL-tokens UI
A UI for burning SPL-tokens and getting back $SOL from the associated token account.

## Close empty account UI
A UI to close empty token account and getting back $SOL from the associated token account.

## Multi sender UI
A UI to send multiple tokens in 1 transaction (same token to different people/many tokens to one person/transfer solana domain name)

## Create SPL-Tokens UI
An UI to create SPL-Tokens with one click.

## Upload File
An UI to upload file to Arweave.

## Update NFT metadata UI
An UI to update the metadata of your NFT

## Send NFT message
An UI to send a NFT message to the owner of your desired NFT

## Style

[Tailwind CSS](https://tailwindcss.com/) or [daisyUI](https://daisyui.com/) are selected tools for rapid style development.

You can quickly change theme changing `daisy.themes` within `./tailwind.config.js`.
More info here: https://daisyui.com/docs/default-themes

This app encourages you to use CSS Modules over other style techniques (like SASS/LESS, Styled Components, usual CSS).
It has a modular nature and supports modern CSS. [Read more on Next.JS site](https://nextjs.org/docs/basic-features/built-in-css-support).
Anyway, if you want to connect LESS there is example code in `./next.config.js`

## Deploy on Vercel

Before push run locally `npm run build` to make sure app can be build successfully on vercel.

Vercel will automatically create environment and deployment for you if you have vercel account connected to your GitHub account. Go to the vercel.com to connect it.
Then any push to `main` branch will automatically rebuild and redeploy app.

To deploy on Vercel use the following settings :

<p align="center">
<img src="https://user-images.githubusercontent.com/35653371/157638049-4944f065-5985-4a35-bbe6-e46efc984737.png"/>
</p>


## Community
If you have questions or any troubles, feel free to reach me on 
X [@Immutal0_](https://x.com/Immutal0_) and Telegram [@Immutal0](https://t.me/Immutal0)
