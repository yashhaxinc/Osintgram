# Osintgram 🔎📸

[![version-1.3](https://img.shields.io/badge/version-1.3-green)](https://github.com/Datalux/Osintgram/releases/tag/1.3)
[![GPLv3](https://img.shields.io/badge/license-GPLv3-blue)](https://img.shields.io/badge/license-GPLv3-blue)
[![Python3](https://img.shields.io/badge/language-Python3-red)](https://img.shields.io/badge/language-Python3-red)
[![Telegram](https://img.shields.io/badge/Telegram-Channel-blue.svg)](https://t.me/osintgram)
[![Docker](https://img.shields.io/badge/Docker-Supported-blue)](https://img.shields.io/badge/Docker-Supported-blue)

Osintgram is a **OSINT** tool on Instagram to collect, analyze, and run reconnaissance.

<p align="center">
<img align="center" src=".img/carbon.png" width="900">
</p>

Disclaimer: **FOR EDUCATIONAL PURPOSE ONLY! The contributors do not assume any responsibility for the use of this tool.**

Warning: It is advisable to **not** use your own/primary account when using this tool.

## Tools and Commands 🧰

Osintgram offers an interactive shell to perform analysis on Instagram account of any users by its nickname. You can get:

```text
- addrs           Get all registered addressed by target photos
- captions        Get user's photos captions
- comments        Get total comments of target's posts
- followers       Get target followers
- followings      Get users followed by target
- fwersemail      Get email of target followers
- fwingsemail     Get email of users followed by target
- fwersnumber     Get phone number of target followers
- fwingsnumber    Get phone number of users followed by target
- hashtags        Get hashtags used by target
- info            Get target info
- likes           Get total likes of target's posts
- mediatype       Get user's posts type (photo or video)
- photodes        Get description of target's photos
- photos          Download user's photos in output folder
- propic          Download user's profile picture
- stories         Download user's stories  
- tagged          Get list of users tagged by target
- wcommented      Get a list of user who commented target's photos
- wtagged         Get a list of user who tagged target
```

You can find detailed commands usage [here](doc/COMMANDS.md).

[**Latest version**](https://github.com/Datalux/Osintgram/releases/tag/1.3) |
[Commands](doc/COMMANDS.md) |
[CHANGELOG](doc/CHANGELOG.md)

## Installation (Termux) ⚙️

1. Clone thsi repository in termux

    `git clone https://github.com/Datalux/Osintgram.git`

2. Navigate to the directory

    `cd Osintgram`

3. Change directory to config
    `cd config`

4. We need to input our login credentials to continue
    Open the credentials.ini by typing
     `nano credentials.ini` 

5. Input your Instagram account username and password in the corresponding fields
    
6. Save the configuration by pressing `ctrl + x`

7. Run the main.py script in terminal by executing this command

    `python3 main.py id`


## External library 🔗

[Instagram API](https://github.com/ping/instagram_private_api)
