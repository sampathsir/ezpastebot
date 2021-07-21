# Ezpaste Bot

A Telegram bot for uploading pastes to https://ezup.dev/p/

## Requirements

- Python 3.6 or higher
- A [Telegram API key](https://docs.pyrogram.org/intro/setup#api-keys)
- A [Telegram bot token](https://t.me/botfather)

## Run

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

Create a new `config.ini` file, copy-paste the following and replace the value
with your own.

```
[pyrogram]
api_id = 1234567
api_hash = 0123456789abcdef0123456789abcdef
bot_token = 123456:ABC-DEF1234ghIkl-zyx57W2v1u123ew11
```

Run the bot

```
virtualenv venv
venv/bin/pip install -U -r requirements.txt
venv/bin/python bot.py
```

## License

AGPL-3.0-or-later

```
ezpastebot, Telegram pastebin bot for https://ezup.dev/p/
Copyright (C) 2021  Dash Eclipse

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```
