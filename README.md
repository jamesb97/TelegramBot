# Telegram Todo Bot

This project is built by initiating the python-telegram-bot library and Telegram BotFather. I developed a simple todo bot that is capable of creating, and maintaining tasks by utilizing 4 commands:

- /start initalizes Todo Bot
- /done marks the task completed
- /shows displays a list of todo items
- /item marks an item as completed

To get started head on over to [BotFather](https://t.me/botfather) and follow the instructions.

After setting up a bot, make sure to get a copy of the token received from BotFather as you will need it.

Create an empty directory on your machine and open it up in VS Code.

Open up the terminal and clone the python telegram bot repository

`
git clone https://github.com/python-telegram-bot/python-telegram-bot --recursive
`

Navigate into the new directory

`
cd python-telegram-bot
`

Install the necessary dependencies

`
python setup.py install
`

Paste the todo.py file into the main directory, and insert the secret token into line 8.

Open up the Telegram Bot chat and run the program

`
python todo.py
`

After testing out the program close the terminal in the upper right hand side.

Here is a video where I test the product in VS Code and Telegram ->

[Demo](https://www.mediafire.com/file/f6ur92r184hr774/demo.mov/file)