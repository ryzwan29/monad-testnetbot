# Monad Testnet Bot

This is a JavaScript bot script designed to interact with the Monad testnet.

## Installation
Paste this script installation
```
source <(curl -s https://raw.githubusercontent.com/ryzwan29/monad-testnetbot/refs/heads/main/quick-installation.sh)
```
## Configuration

1.  **Rename `.env.example`** to .env

```bash
  cp .env.example .env
```

2. **Edit the `.env.`** file
   Replace your_evm_private_key with your actual EVM wallet private key. It should look like this:
   ```bash
   PRIVATE_KEY=0x1234...
   ```

## Usage

To run the bot, use the following command:

```bash
npm start
```

The bot will start processing each wallet based on the configured.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
