# Project 1 - Discord Bot

## Part 1 - Setup
1. How to generate an API token from Discord:
	1. create a new application on Discord Developer Portal
	2. Name the Appliaciton, agree to terms, and click create
	3. Go to Bot and click "Add Bot" then "Yes, do it!"
	4. Scroll down and be sure to have "Message Content Intent" set to on (blue)
	5. Click "Reset Token" > "Yes, do it!"
	7. Enter verification code
	8. Copy Token as you can only see this token once
2. Where to put the token:
	1. Within the folder you are runing the python code from put in a file named ".env"
	2. Within the file have the following: `DISCORD_TOKEN=REPLACE_ME_WITH_TOKEN`
	3. Add filepath to .gitignore file if uploading to github!
3. Packages needed to run the code and commands to install:
	1. Python 3.8 `sudo apt-get install python3.8`
	2. pip3 `sudo apt install python3-pip`
	3. discord.py version 2.0.1 `pip3 install -U discord.py==2.0.1`
	4. dotenv `python3.8 -m pip install python-dotenv`

## Part 2 - Modifications

## Part 3 - Research and Documentation
