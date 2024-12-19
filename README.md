# SnipeBot

A simple trading bot for automating trades on Solana. This bot evaluates token prices and executes buy or sell trades based on configurable thresholds.

## Features
- Automated trading based on user-defined thresholds.
- Secure configuration using environment variables.
- Simple and modular design for easy customization.

## Setup Instructions

### Prerequisites
- Node.js installed
- `dotenv` package for managing environment variables

### Installation
1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd snipeBot

Install dependencies:

bash
Copy code
npm install dotenv
Add your environment variables:

Create a .env file with the following:
plaintext
Copy code
API_KEY=your_api_key_here
PRIVATE_KEY=your_private_key_here
Add your trading parameters:

Update config.json with your thresholds.
Run the bot:

bash
Copy code
node snipeBot.js

Change gitignore_example to .gitignore
change Empty.env to .env
