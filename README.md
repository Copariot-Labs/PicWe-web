# PicWe trading

This is a Web3-based trading platform built with Wagmi, Vite, and Tailwind CSS. The platform allows users to connect their crypto wallets, trade tokens, and manage orders.

## Tech Stack

- **Frontend Framework**: React
- **Build Tool**: Vite
- **Web3 Integration**: Wagmi
- **Styling**: Tailwind CSS
- **Smart Contract Interaction**: Ethers.js

## Key Features

1. **Wallet Connection**: Support for multiple crypto wallets such as MetaMask, WalletConnect, etc.
2. **Token Trading**: Users can swap and trade tokens on the platform.
3. **Order Management**: View and manage current open orders.
4. **Multi-Chain Support**: Support for multiple blockchain networks, including mainnet and testnet.
5. **Token Info Display**: Automatic display of token icons and symbols.

## Usage Guide

1. **Connect Wallet**:
   - Click the "Connect Wallet" button in the top right corner.
   - Choose your wallet type (e.g., MetaMask).
   - Follow the wallet prompts to complete the connection.

2. **Switch Network**:
   - Ensure your wallet is connected to a supported network (e.g., Arbitrum, Base).
   - If needed, manually switch networks in your wallet.

3. **Trade Tokens**:
   - Select the token pair you want to swap on the trading interface.
   - Enter the trade amount.
   - Click the "Swap" button to confirm the trade.

4. **View Orders**:
   - Navigate to the "Orders" page to view your open orders.
   - Cancel open orders if needed.

5. **View Token Information**:
   - Token icons and symbols are automatically displayed in the trading interface and order list.

## Development Setup

1. Clone the repository:
   ```
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Install dependencies:
   ```
   cd your-repo-name
   npm install
   ```

3. Run the development server:
   ```
   npm run dev
   ```

4. Build for production:
   ```
   npm run build
   ```

## Configuration

- Configure supported networks and tokens in the `src/components/networkconfig.ts` file.
- Toggle between mainnet and testnet by modifying the `isTestnet` variable.

## Contributing

Pull requests are welcome to improve this project. Before submitting, please ensure your code adheres to the project's coding standards and passes all tests.

## License

[MIT License](LICENSE)
