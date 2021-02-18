Project description
Ultroid - UserBot
A stable pluggable Telegram userbot, based on Telethon.

Python Version Stars Forks Contributors License Size

More Info
Deploy
Heroku
Local Machine
Deploy to Heroku
Get your API_ID and API_HASH from here and click the below button!

Deploy
Deploy Locally
Get your API_ID and API_HASH from here
Clone the repository:
git clone https://github.com/TeamUltroid/Ultroid.git
Go to the cloned folder:
cd Ultroid
Create a virtual env:
virtualenv -p /usr/bin/python3 venv
. ./venv/bin/activate
Install the requirements:
pip install -r requirements.txt
Generate your SESSION:
bash sessiongen
Fill your details in a .env file, as given in .env.sample.
(You can either edit and rename the file or make a new file.)
Run the bot:
python3 -m ultroid
Made with 💕 by @TeamUltroid.

Credits
Lonami for Telethon
