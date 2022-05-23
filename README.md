# <b>MIRROR HUNTER</b>

![MIRROR HUNTER](https://media.giphy.com/media/dikubVwoUUBxLgpraV/giphy.gif?cid=790b7611c1fd9acab35e7fc75f7447316865d93043fc77b3&rid=giphy.gif&ct=s)

![GitHub Repo stars](https://img.shields.io/github/stars/anime-republic/MIRROR-HUNTER?color=blue&style=plastic)
![GitHub forks](https://img.shields.io/github/forks/anime-republic/MIRROR-HUNTER?color=green&style=plastic)
![GitHub watchers](https://img.shields.io/github/watchers/anime-republic/MIRROR-HUNTER?style=plastic)
![Docker Pulls](https://img.shields.io/github/contributors/anime-republic/MIRROR-HUNTER?style=plastic)

**This Bot** is a _multipurpose_ Telegram Bot writen in Python for mirroring files on the Internet to our beloved Google Drive.

# Repo Details
| Repo Name  | Status | Commit |
| ------------- | ------------- | ------------- |
| MIRROR HUNTER | ![Docker Pulls](https://img.shields.io/github/last-commit/anime-republic/MIRROR-HUNTER?style==for-the-badge) | ![Docker Pulls](https://img.shields.io/github/commit-activity/w/anime-republic/Mirror-New?style=flat-square) |

# Features supported:
<details>
    <summary><b>Click Here For More Details</b></summary>

## Additional Features
- Updater (**NOTE**: You must upload your **token.pickle** to Index and fill your **token.pickle** url to **TOKEN_PICKLE_URL**, because your **token.pickle** will deleted after update, for more info please check [Setting up config file](https://github.com/Anime-Republic/MIRROR-HUNTER#setting-up-config-file))
- Limiting size Torrent/Direct, Tar/Unzip, Mega, cloning Google Drive support
- Stop duplicate cloning Google Drive & mirroring Mega support
- Tar/Unzip Google Drive link support
- Sudo with Database support
- Multiple Trackers support
- Extracting **tar.xz** support
- Counting Google Drive link
- Heroku config support
- View Link button
- Shell and Executor
- YT-DLP
- Support message send to log channel/group    
- Search All Drive  
- Direct links Supported:
```
letsupload.io
hxfile.co
anonfiles.com
bayfiles.com
antfiles
fembed.com
fembed.net
femax20.com
layarkacaxxi.icu
fcdn.stream
sbplay.org
naniplay.com
naniplay.nanime.in
naniplay.nanime.biz
sbembed.com
streamtape.com
streamsb.net
feurl.com
pixeldrain.com
racaty.net
1fichier.com
1drv.ms (Only works for file not folder or business account)
uptobox.com (Uptobox account must be premium)
solidfiles.com
```

## From Original Repos
- Mirroring direct download links, Torrent, and Telegram files to Google Drive
- Mirroring Mega.nz links to Google Drive (If your Mega account not premium, it will limit 5GB/6 hours)
- Copy files from someone's Drive to your Drive (Using Autorclone)
- Download/Upload progress, Speeds and ETAs
- Mirror all Youtube-dl supported links
- Docker support
- Uploading to Team Drive
- Index Link support
- Service Account support
- Delete files from Drive
- Custom Filename (Only for URL, Telegram files and Youtube-dl. Not for Mega links and Magnet/Torrents)
- Extracting password protected files, using custom filename and download from password protected Index Links see these examples:
<p><a href="https://telegra.ph/Magneto-Python-Aria---Custom-Filename-Examples-01-20"> <img src="https://img.shields.io/badge/see%20on%20telegraph-blue?style=for-the-badge" width="150""/></a></p>

- Extract these filetypes and uploads to Google Drive
```
ZIP, RAR, TAR, 7z, ISO, WIM, CAB, GZIP, BZIP2, 
APM, ARJ, CHM, CPIO, CramFS, DEB, DMG, FAT, 
HFS, LZH, LZMA, LZMA2, MBR, MSI, MSLZ, NSIS, 
NTFS, RPM, SquashFS, UDF, VHD, XAR, Z.
```

</details>
    
## Generate Database
<details>
    <summary><b>Click Here For More Details</b></summary>

**1. Using ElephantSQL**
- Go to https://elephantsql.com and create account (skip this if you already have **ElephantSQL** account)
- Hit `Create New Instance`
- Follow the further instructions in the screen
- Hit `Select Region`
- Hit `Review`
- Hit `Create instance`
- Select your database name
- Copy your database url, and fill to `DATABASE_URL` in config.env

**2. Using Heroku PostgreSQL**
<p><a href="https://dev.to/prisma/how-to-setup-a-free-postgresql-database-on-heroku-1dc1"> <img src="https://img.shields.io/badge/See%20Dev.to-black?style=for-the-badge&logo=dev.to" width="160""/></a></p>

</details>

## How To Deploy it?
<p><a href="https://github.com/Anime-Republic/MIRROR-HUNTER/wiki"> <img src="https://img.shields.io/badge/Deploy%20Guide-red?style=for-the-badge&logo=github" width="200""/></a></p>

## SPECIAL DEPLOYMENT 👀👀👀 (Should read)
<details>
    <summary><b>Click Here For More Details</b></summary>
       First deploy from github with 4 secrets
--> Check resources tab in heroku to see a turned off dyno button
--> Turn it on. Look at the logs, it will deploy but 99% chance that heroku will suspend that app (not account)
--> Delete the app. Create new app in same account with same name
--> Deploy again on github
--> This time also look for resorces tab and turn on the dyno button
--> You should be able to see bot started
--> The bot should be able to survive after this
    
</details>
    



  
