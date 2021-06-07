<p><a href="https://heroku.com/deploy?template=https://github.com/kumarhariomrai/ttknew"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a></p>
DONT FORK THIS REPO ITS UNDER MAINTAINANCE MODE

# TGTK - A Telegram Bot

## Notes:
a pypi package named [tgtk](https://pypi.org/project/tgtk) containing all bot code, easily to install with 
```
pip install tgtk
```
deploying from an docker image [reaitten/tk:latest](https://hub.docker.com/r/reaitten/tk/tags?page=1&ordering=last_updated)

## Deploy via Heroku CLI
- Download [deploy.zip](https://github.com/reaitten/tgtk/releases).
- Unzip & open a command prompt.
- Change stack dyno to container:
```
heroku stack:set container --app your-app-name
```
- Initialise the project files as a Git Repository, push the repo to 'Heroku Git' and build the Docker Image:
```
git init
git add .
heroku git:remote -a your-app-name`
git commit -m "initial commit"
git push heroku main
```

# Credits

> [yash-dk's TorToolkit](https://github.com/yash-dk/TorToolkit-Telegram)

> Rahul Kapoor(Main contributer)
> [sahadz's tortoolkit-Telegram](https://github.com/sahadz/tk-Telegram)

> [dr-qaatil <3](https://github.com/dr-qaatil)

## Variables
`IS_VPS` = False
## Compulsory Vars

`API_HASH` = Obtained from Telegram 

`APP_ID` = Obtained from Telegram

`BOT_TOKEN` = Obtained from Botfather

`BASE_URL_OF_BOT` = IP/domain of your bot like "https://appname.herokuapp.com" (for heroku)

`AUTH_CHANNEL` = It is a list of IDs of all the allowed groups and useres who can use this bot in private. Seperated by spaces e.g: "-102222 -33322211 11222333"

`DB_URI` = Postgres database URL.

`OWNER_ID` = self-explanatory, get value from [@userinfobot](https://t.me/userinfobot)


## Commands
add in [@BotFather](https://t.me/BotFather)

    leech - To Leech a torrent or download a direct link
    ytdl - Donwload YouTube Video
    pytdl - Download YouTube Playlist
    about - About the bot
    status - Status of all the downloads
    stats - Get server status
    usettings - User Settings (private also)
    instadl - Instagram Post/Reel/IGTV download
    setthumb - Set the thumbnail
    clearthumb - Clear the thumbnail
    settings - Settings of the bot ⚠️ Admin Only
    pauseall - Pause all torrents⚠️ Admin Only
    resumeall - Resume all torrents⚠️ Admin Only
    purge - Delete all torrents ⚠️ Admin Only
    logs - Get the robot logs ⚠️ Admin Only
