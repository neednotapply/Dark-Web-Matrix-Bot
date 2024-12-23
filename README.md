# Dark-Web-Matrix-Bot
 A Matrix bot that searches the dark web for your query and returns links and screenshots of the results to your Matrix channel using ahmia.fi. Developed by RocketGod.

> **Note**: You need to have the TOR Browser connected to the TOR Network for this bot to function correctly.

## 🚀 Installation

### Prerequisites

Before installing the bot, ensure you have the correct version of `chromedriver` for your system:

1. Check your Google Chrome version by navigating to the menu (⋮) > Help > About Google Chrome.
2. Go to the [ChromeDriver download page](https://chromedriver.chromium.org/downloads/version-selection) and download the corresponding version of `chromedriver` for your Chrome version. I've included the latest version as of September of 2023.
3. Once downloaded, place the `chromedriver` executable in a directory that's on your system's PATH or in the root directory of the bot. Make sure Chrome matches!

### Windows:

1. Clone this repository:
   ```bash
   git clone https://github.com/RocketGod-git/Dark-Web-Matrix-Bot
   cd Dark-Web-Matrix-Bot
   ```
2. Install dependencies and run the bot:
   ```bash
   run.bat
   ```

### Linux/macOS:

1. Clone this repository:
   ```bash
   git clone https://github.com/RocketGod-git/Dark-Web-Matrix-Bot
   cd Dark-Web-Matrix-Bot
   ```
2. Make the script executable:
   ```bash
   chmod +x run.sh
   ```
3. Install dependencies and run the bot:
   ```bash
   ./run.sh
   ```

## 🛠️ Configuration

1. Edit `config.json` in the root directory with the following format:
   ```json
   {
       "Matrix_bot_token": "YOUR_Matrix_BOT_TOKEN"
   }
   ```
2. Replace `YOUR_Matrix_BOT_TOKEN` with your actual Matrix bot token.

## 🌟 Features

- Search for onion links related to a query on the dark web.
- Get screenshots of the fetched onion sites directly in Matrix with clickable links.

## 📜 License

This project is licensed under the GNU GPLv3 - see the [LICENSE](LICENSE) file for details.

![RocketGod](https://github.com/RocketGod-git/Flipper_Zero/assets/57732082/f5d67cfd-585d-4b23-905f-37151e3d6a7d)
