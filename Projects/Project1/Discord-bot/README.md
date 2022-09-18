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

## Part 2 - Usage
1. What Command can be typed in the Discord Server:
	1. `steinke!`
	2. `towel!`
2. What response will be provided:
	1. `steinke!` will provide saying that are said by the Steinke family and when said, are caught by others and pointed out as they are said too often per the family. Sayings include:
	```
	1. Not a problem
	2. I guarantee it
	3. Mother wouldn't like that
	4. It is what it is
	```
	2. `towel!` will provide different sayings that have been provided. Sayings include:
	```
	1. There is an art, it says, or rather, a knack to flying. The knack lies in learning how to throw yourself at the ground and miss.
    2. It is a mistake to think you can solve any major problems just with potatoes.
    3. In the beginning the Universe was created. This has made a lot of people very angry and been widely regarded as a bad move.
    4. A common mistake that people make when trying to design something completely foolproof is to underestimate the ingenuity of complete fools.
	```
	3. Photo:
	![proof](Discord.png)

## Part 3 - Research and Documentation
