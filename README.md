
# Solana Explorer

**Solex** is a user-friendly Solana blockchain explorer offering real-time data and insights. Effortlessly track network performance, assets, and validator statuses with an intuitive interface.

---

## Features

### Dashboard
- **SOL Price:** Real-time SOL price updates.
- **Last Blocks:** Display of the latest blocks on the Solana blockchain.
- **Transactions Per Second (TPS):** Live TPS metrics.
- **Trending Coins:** View a list of trending coins on Solana.
- **Validators:** Overview of active validators.

### Explorer
- **Wallet Assets:** Track and manage assets in your wallet, including coins and NFTs.

### Validators
- **Network Status:** Monitor the current status of the Solana network.
- **Delinquent Validators:** Information on validators that are not performing correctly.

---

## Getting Started

### 1. Set Environment Variables

Copy the example environment file and configure your settings:
```bash
cp .env.dist .env
```

### 2. Install Dependencies

Choose your preferred package manager:
```bash
npm install
# or
yarn
# or
pnpm install
# or
bun install
```

### 3. Run the Development Server

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Visit [http://localhost:3000](http://localhost:3000) in your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

---

## Font Optimization

This project uses [`next/font`](https://nextjs.org/docs/pages/api-reference/components/font) to automatically optimize and load Inter, a custom Google Font.

---

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/) from the creators of Next.js.

Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

---

## Contributing

We welcome contributions from the community!  
Please fork this repository and submit pull requests.

---

## License

This project is licensed under the [MIT License](LICENSE).

