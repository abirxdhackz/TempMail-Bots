<h1 align="center">TempMail Telegram Bot 💌</h1>

<p align="center">
 <a href="https://twitter.com/abirthedigital" target="blank">
        <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=flat-square&logo=twitter&logoColor=white" alt="abirthedigital" />
    </a>
    <a href="https://fb.com/abir360techsavvybhai" target="blank">
        <img src="https://img.shields.io/badge/Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white" alt="abir360techsavvybhai" />
    </a>
    <a href="https://instagram.com/abirthedigitalguru" target="blank">
        <img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white" alt="abirthedigitalguru" />
    </a>
    <a href="https://t.me/abir_xd_bio" target="blank">
        <img src="https://img.shields.io/badge/Telegram-0088cc?style=flat-square&logo=telegram&logoColor=white" alt="abir_xd_bio" />
    </a>
    <a href="https://www.youtube.com/@AbirTheDigitalGuru" target="blank">
        <img src="https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white" alt="AbirTheDigitalGuru" />
    </a>
</p>

<p align="center">
  <em>This is a Temporary email addresses Generator telegram bot script using the mail.tm API. It enables users to create temporary email addresses directly from Telegram, check their inbox, and read messages without leaving the app.</em>
</p>
<hr>

## Features

- Generate temporary email addresses.
- Check the inbox of the generated email.
- Read emails directly through Telegram.
- Supports custom username and password for email generation.
- Secure: your temporary emails and messages are private and accessible only to you.

## Requirements

- Python 3.8 or higher.
- `pyrofork`, `requests` and `beautifulsoup4` libraries.
- A Telegram bot token (you can get one from [@BotFather](https://t.me/BotFather) on Telegram).
- API ID and Hash: You can get these by creating an application on [my.telegram.org](https://my.telegram.org).

## Installation

To install `pyrofork`, `requests` and `beautifulsoup4` run the following command:

```bash
pip install pyrofork requests beautifulsoup4
```

**Note: If you previously installed `pyrogram`, uninstall it before installing `pyrofork`.**
```

## Configuration

1. Open the script with your favorite text editor.
2. Find the line that contains `API_TOKEN = '123456:ABCDEFGHIJLLJOdMttZ5hEZ78'`.
3. Replace the placeholder token with your actual Telegram bot token.

## Deploy the Bot

```sh
git clone https://github.com/abirxdhackz/TempMail-Bots.git
cd TempMail-Bots
python3 tempmail.py
```

## Bot Commands

- `/tmail` - Command for Generate Random Mail with Pass
- `/tmail [username]:[password]` - Generate a temporary email. with a specify a username and password.
- `/cmail <token>` - Check the inbox of your temporary email by providing the token received during email generation.

✨ **Note**: When you generate a mail pass, then you will receive a mail token. With the token, you can check 10 recent mails, each mail has a different token, so keep it privately. The mail generator general quota limit is 8 queries per second (QPS) per IP address.

## Author

- Name: Abir XD
- Telegram: [@abir_xd_bio](https://t.me/abir_x_official)

Feel free to reach out if you have any questions or feedback.
