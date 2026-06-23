# 🤖 Website Source Downloader Telegram Bot

A powerful Telegram bot that downloads COMPLETE website source code including HTML pages, images, CSS, JavaScript files, and hidden API endpoints. Everything is automatically packed into a ZIP file and delivered directly via Telegram.

Optimized for Android users (Termux & Pydroid3) and also works on VPS / Ubuntu / Windows.

================================================================

FEATURES
- Full website crawling (depth based)
- HTML source downloader
- Images auto download
- CSS & JavaScript downloader
- Hidden API endpoint scanner
- Automatic ZIP creation
- Detailed stats report
- Smart folder structure
- Error handling with logs
- Async + threaded execution
- Same-domain safe scraping

================================================================

SUPPORTED PLATFORMS
- Termux (Android)
- Pydroid 3 (Android)
- Ubuntu / VPS
- Windows (Python 3.10+)

================================================================

HOW TO USE

========================
METHOD 1: TERMUX (RECOMMENDED)
========================

STEP 1: INSTALL TERMUX (OFFICIAL)
Download ONLY from F-Droid
https://f-droid.org/repo/com.termux_118.apk

DO NOT use Play Store version (outdated)

------------------------------------------------

STEP 2: UPDATE & UPGRADE TERMUX
pkg update && pkg upgrade -y

------------------------------------------------

STEP 3: INSTALL REQUIRED PACKAGES
pkg install python git wget unzip nano -y

------------------------------------------------

STEP 4: ALLOW STORAGE PERMISSION
termux-setup-storage

Allow the permission popup

------------------------------------------------

STEP 5: UPGRADE PIP
pip install --upgrade pip

------------------------------------------------

STEP 6: INSTALL PYTHON REQUIREMENTS
pip install requests beautifulsoup4 python-telegram-bot==20.7

------------------------------------------------

STEP 7: CREATE BOT FILE
nano bot.py

Paste FULL bot source code
Replace:
TOKEN = "YOUR_BOT_TOKEN_HERE"
with your real BotFather token

Save file:
CTRL + X
Y
ENTER

------------------------------------------------

STEP 8: RUN THE BOT
python bot.py

Bot is now LIVE
Keep Termux running

------------------------------------------------

TELEGRAM COMMANDS
/start
/download https://example.com

================================================================

METHOD 2: PYDROID 3 (NO ROOT)
============================

STEP 1: INSTALL PYDROID 3
https://play.google.com/store/apps/details?id=ru.iiec.pydroid3

------------------------------------------------

STEP 2: INSTALL PYDROID REPOSITORY PLUGIN
(Search on Play Store)
THIS IS VERY IMPORTANT

------------------------------------------------

STEP 3: OPEN TERMINAL
Menu → Terminal

------------------------------------------------

STEP 4: INSTALL PYTHON LIBRARIES
pip install requests beautifulsoup4 python-telegram-bot==20.7

------------------------------------------------

STEP 5: CREATE FILE
Open Editor
Create file: bot.py
Paste full bot code
Add your Telegram Bot Token

------------------------------------------------

STEP 6: RUN
Press RUN ▶ button

Bot starts instantly

================================================================

METHOD 3: VPS / UBUNTU
=====================

sudo apt update && sudo apt upgrade -y
sudo apt install python3 python3-pip git unzip -y
pip3 install requests beautifulsoup4 python-telegram-bot==20.7
python3 bot.py

================================================================

OUTPUT STRUCTURE

example_com/
├── pages/
│   ├── index.html
│   └── about.html
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── api_data/
│   └── api_response.json
├── errors/
│   └── error_log.txt

ZIP FILE:
example_com_bot.zip

================================================================

CONFIGURATION

Inside code:
MAX_DEPTH = 2
MAX_PAGES = 20

Higher values = more load + possible ban

================================================================

COMMON ERRORS & FIX

MODULE NOT FOUND:
pip install module_name

BOT NOT RESPONDING:
- Check bot token
- Check internet
- Restart script

ZIP TOO LARGE:
- Reduce MAX_DEPTH
- Reduce MAX_PAGES

================================================================

SECURITY WARNING

- NEVER share your bot token
- Do NOT scrape private / paid websites
- Use for educational purposes only
- Keep bot private if possible

================================================================

LEGAL DISCLAIMER

This project is for EDUCATIONAL PURPOSES ONLY.
Developer is NOT responsible for any misuse.

================================================================

❤️ Credit: Ashish Yadav 

================================================================

If you like this project, give it a ⭐
Happy Coding 🚀
