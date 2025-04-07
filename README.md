# Telegram-Mass-DM-Bot
Telegram Mass DM Bot
Create a new file for the usernames to send messages, i call it usernames.txt in the code so you can use the same name .
If you use another file name , you must modify the above code then but i've tagged the whole code so is more easier to read.
In this file you must put the usernames -one per line- with the @ added , example :
@bhw
@username1
@username2
@username3

Extracting API ID, HASH ID for accounts and setting up the python file.
Go to https://my.telegram.org ( You must login )
Create an app
Fill in the app details
Extract the api ID
Extract the api hash
Input the api id in the main.py
Input the api hash in the main.py
Input the account number in the main.py

Open the Python Terminal through VSCode

Installing required libraries, only telethon. I tried to make the code easier to install so with telethon everything is covered.
First type
pip3 install telethon
pip3 = pip / May change depend on your OS

With all the steps above filled now you are ready to run the code just typing
python3 main.py
Python3 = python / May change depend on your OS

TAKE IN MIND BEFORE RUNNING
All the code is quite optimized and updated but for BULK tasks i would recommend to use bulk accounts. Do not use your own account to send 100's of DMs because I can't guarantee you won't get your accounts flagged or banned.


