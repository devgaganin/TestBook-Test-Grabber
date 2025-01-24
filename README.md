# TestBook Bot  
**A powerful Telegram bot repository to connect with TestBook via API to fetch & generate visually appealing HTML test files, using your authorised credentials**

---

## Features  
- Fetch test data using Testbook API.
- Support for multi-language questions (English and Hindi).
- Generates enhanced HTML files with styled question and answer content.
- Fixes image URLs dynamically for compatibility.
- Minimal dependencies and efficient performance.

---
## Deployment

## Requirements  
- Python 3.8+
- [Telethon](https://github.com/LonamiWebs/Telethon) library for interacting with Telegram.
- Internet access to fetch data and communicate with Telegram servers.

---

## Installation  

1. Clone the repository:
   ```bash
   git clone https://github.com/devgaganin/TestbookBot.git
   cd TestbookBot
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set environment variables in a `.env` file or directly configure them:
   ```
   API_ID=your_api_id
   API_HASH=your_api_hash
   BOT_TOKEN=your_bot_token
   AUTH_CODE=your_auth_code # eg: eyfgobtiOtrtrUzI......eyJpc3MiHRwewczovL3Rlc3Rib....
   ```

4. Run the bot:
   ```bash
   python main.py
   ```
---
## Deployment

### 1. Deploying on a VPS
To deploy the bot on your VPS:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/devgaganin/TestBook-Bot.git
   cd TestBook-Bot
   ```

2. **Install Dependencies**:
   Ensure Python 3.8+ and `pip` are installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the root directory or export the following variables:
   ```bash
   API_ID=your_api_id
   API_HASH=your_api_hash
   BOT_TOKEN=your_bot_token
   AUTH_CODE=your_auth_code # eg: eyfgobtiOtrtrUzI......eyJpc3MiHRwewczovL3Rlc3Rib....
   ```

4. **Run the Bot**:
   Start the bot using:
   ```bash
   python main.py
   ```

---

### 2. Deploying on Heroku
To deploy the bot on **Heroku**, click the button below and fill in the required environment variables:

[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

#### Steps:
1. Click the **Deploy on Heroku** button above.
2. Enter the following required environment variables during deployment:
   - `API_ID`
   - `API_HASH`
   - `BOT_TOKEN`
   - `AUTH_CODE` # eg: eyfgobtiOtrtrUzI......eyJpc3MiHRwewczovL3Rlc3Rib....
3. Deploy the app and monitor the logs to ensure the bot is running successfully.
---

## Commands  

| Command               | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| `/start`              | Display a welcome message with usage instructions.                        |
| `/fetch <test_id>`    | Fetch test data from the Testbook API for the provided test ID.            |
| `/language <lang>`    | Choose a language (`en` for English, `hn` for Hindi) to format test data. |

---

## Usage  

1. Start the bot:
   - Type `/start` in your Telegram chat with the bot.
   - The bot will respond with a welcome message and basic instructions.

2. Fetch a test:
   - Use `/fetch <test_id>`. Replace `<test_id>` with the specific test ID provided.
   - The bot will validate the test ID and retrieve the corresponding test data.

3. Select a language:
   - Use `/language en` for English or `/language hn` for Hindi.
   - The bot generates and sends an HTML file containing the test questions and answers.

---

## Example Workflow  
1. `/start`  
   Bot: "Welcome to the Testbook Bot! Use the command `/fetch <test_id>` to fetch test data."  

2. `/fetch 66fbeee4d8b88b617b0e69ab`  
   Bot: "Test data fetched successfully! Please select a language: `/language en` or `/language hn`."  

3. `/language en`  
   Bot sends the test questions as an HTML file.

---

## License  
This project is licensed under the **GNU Affero General Public License v2** (APGL-2.0).  
**Strict Provisions:**
- **No Commercial Use**: This software and its derivatives must not be used for commercial purposes or sold.
- **No part of this code, including edits, is allowed to be used for commercial or sale purposes.**

**© [GitHub.com/devgaganin](https://github.com/devgaganin)**  
Unauthorized commercial use is strictly prohibited.

---

## Disclaimer  
The bot is intended solely for personal and educational purposes.  
Use at own responsibilty and copying, modifying part of this code/reuse is not allowed.
The developer is not responsible for any misuse or breach of third-party API terms. 

## For TestBook Representatives:
Hey respected representatives,
If this project is engaging in any activities that you consider misleading, inappropriate, or in violation of your policies, please feel free to reach out to me immediately. I am committed to resolving any issues and will take necessary actions, including shutting down the project if required.

Contact Information:
[Email](mailto:business@devgagan.in)

Thank you for your understanding and cooperation.
