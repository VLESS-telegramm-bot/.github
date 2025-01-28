# Telegram VPN Subscription Bot

This organization contains the source code for a Telegram bot that facilitates the sale of subscriptions to a VPN service. The bot interacts with the 3x-ui API to manage VPN connections efficiently.

## Features

- **VPN Subscription Purchase:**
  - Allows users to purchase VPN subscriptions.
  - Handles pre-checkout queries and successful payments.

- **VPN Connection Information:**
  - Provides users with details about their VPN connection, including status and remaining days.
  - Checks client expiry times and sends Telegram notifications.

- **Interactive Menu:**
  - Utilizes inline keyboards for seamless navigation and interaction.

- **3x-ui API Integration:**
  - Connects to the 3x-ui API to manage inbounds and clients.
  - Adds new inbounds and clients with specified parameters.
  - Offers both synchronous and asynchronous methods for app interaction.

## Technologies Used

- **Python:** Main programming language.
- **Telegram Bot API:** Enables bot functionality.
- **python-telegram-bot:** A Python wrapper for the Telegram Bot API.
- **py3xui:** Python SDK for interacting with the 3x-ui API.
- **SQLite:** Database management.
- **dotenv:** Environment variable management.
- **Docker:** Containerized deployment.
- **CI/CD Pipeline:** Automated deployment using GitHub Actions with secure GitHub Secrets.

## Links

- [Telegram VPN Subscription Bot](https://t.me/fcg_vpn_bot)

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

