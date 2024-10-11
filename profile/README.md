# 👋 Dehype.fun 🚀 
Dehype.fun is a decentralized prediction market and memecoin launchpad built on the Solana blockchain. Our platform enables users to trade outcome tokens related to real-world events, making it an exciting and innovative space for community engagement and speculation.

## Key Features 🌟
- **Prediction Market:** Users can trade tokens based on the outcome of real-world events, allowing for an engaging trading experience
- **Memecoin Launchpad:** The platform allows winning outcome tokens to be transformed into permanent memecoins, adding a fun twist to the trading experience
- **Liquidity Management:** Liquidity from losing tokens is automatically redirected, enhancing the overall ecosystem and providing a robust user experience

## Technology Stack 🛠️
- **Frontend:** Next.js
- **Backend:** NestJS
- **Smart Contracts:** Anchor (Rust)
- **Authentication:** 
  - Solana Wallet Adapter
  - Support for all major Solana-compatible wallets (Phantom, Solflare, Backpack, etc.)
- **Blockchain:** Solana Program (Anchor)

## Program Information 🔍
- **Program ID:** `7fKSTrQLMk4K8svWTZ6dpD7mFVVfQdZ2TUb9MfqfAUWK`
- **Network:** Solana Devnet
- **Explorer Links:**
  - [Solana Explorer](https://explorer.solana.com/address/7fKSTrQLMk4K8svWTZ6dpD7mFVVfQdZ2TUb9MfqfAUWK?cluster=devnet)
  - [Solscan](https://solscan.io/account/7fKSTrQLMk4K8svWTZ6dpD7mFVVfQdZ2TUb9MfqfAUWK?cluster=devnet)

## Resources 🔗
- [Live Application](https://dehype.fun)
- [Official Documentation](https://docs.dehype.fun)
- [Twitter](https://x.com/dehype_fun)
- [Frontend Repository](https://github.com/dehype-fun/dehype-fe)
- [Smart Contract Repository](https://github.com/dehype-fun/dehype-program)

## Detailed User Flow 📱
**New Users**
1. Connect with any Solana-compatible wallet
2. Automatic account initialization on the platform
3. Program initiates necessary PDAs and token accounts
4. All initialization fees and rent are handled by the platform

**Trading Flow**
1. Users can browse available prediction markets
2. Select desired outcome positions
3. Execute trades through wallet signature
4. Track positions and market movements in real-time
5. Claim rewards for winning positions

## Local Development Setup 💻

### Prerequisites
- Node.js (v16 or higher)
- Rust
- Solana CLI
- Any Solana-compatible wallet browser extension

### Frontend Setup
1. Clone the repository
```bash
git clone https://github.com/dehype-fun/dehype-fe
cd dehype-fe
```

2. Install dependencies
```bash
npm install
```

3. Environment Configuration
- Copy `.env.example` to `.env.local`
- Configure required environment variables:
  - NEXT_PUBLIC_SOLANA_RPC_ENDPOINT
  - NEXT_PUBLIC_API_ENDPOINT
  - NEXT_PUBLIC_PROGRAM_ID=7fKSTrQLMk4K8svWTZ6dpD7mFVVfQdZ2TUb9MfqfAUWK
  - Other necessary API keys

4. Start Development Server
```bash
npm run dev
```

### Smart Contract Development
Detailed instructions available in the [program repository](https://github.com/dehype-fun/dehype-program)

## Wallet Integration 🔐
Our platform supports all major Solana-compatible wallets including:
- Phantom
- Solflare
- Backpack
- Glow
- Brave Wallet
- And other wallets that implement the Solana wallet standard

To integrate with our platform, users simply need to:
1. Install their preferred Solana wallet
2. Ensure they have some SOL for transaction fees
3. Connect their wallet through our dApp interface

## Known Limitations & Future Improvements 🔄
- Current deployment on Solana devnet
- Planned features for enhanced liquidity management
- Future integration with additional prediction market types
- Mobile app development in progress

## About Us 🤝
Openverse is a team from Danang University of Science and Technology, with a track record of hackathon victories. We've formed a startup focused on Web3 innovation, specializing in decentralized applications and blockchain solutions.

## Contributing ✨
We welcome contributions! Please review our contribution guidelines in each repository.

## License 📜
This project is licensed under the MIT License. See the LICENSE file for details.

---
Contact us for questions or additional information:
- Email: [tech.openverse@gmail.com]
- Twitter: [@dehype_fun](https://x.com/dehype_fun)
