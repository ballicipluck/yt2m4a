# ABANDONED AND SLOW, MOVE ON
## YT to .m4a bot for Telegram
Just a simple bot to get audio from youtube. Just enter a keyword and it will return the audio from the first youtube link/result it gets.

## HOW TO DEPLOY
###### HEROKU
1. Import this repo. (Don't fork as you'll need to enter your creds and that might become public)
1. Enter your creds in `config.py`.
    - If there's no file named `config.py`, just rename `sample.config.py` to `config.py` and fill that.

1. Create an empty app in Heroku.
1. Select the app and goto `DEPLOY` tab in Heroku.
    1. Select `GitHub`.
    1. Link your GitHub account(`Connect to GitHub` button at the bottom) if not already linked.
    1. Select this repo and click `Deploy`.
## COMMANDS
- `/start` - Check if bot is alive
- `/a` - {keyword} Get the audio from the keyword provided
    - `/a closer`
    - `/a psa gangnam style`
