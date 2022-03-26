<img src="https://telegra.ph/file/c0e014ff34f34d1056627.png" align="right" width="200" height="200"/>

# Yukki Music Bot <img src="https://img.shields.io/github/v/release/TeamYukki/YukkiMusicBot?color=black&logo=github&logoColor=black&style=social" alt="RELEASE">

[sᴀɴᴛʜᴜ ᴍᴜsɪᴄ ʙᴏᴛ](https://github.com/Podilisanthosh/YukkiMusicBot?organization=Podilisanthosh&organization=Podilisanthosh) is a Powerful Telegram Music+Video Bot written in Python using Pyrogram and Py-Tgcalls by which you can stream songs, video and even live streams in your group calls via various sources.

* ʏᴏᴜᴛᴜʙᴇ, sᴏᴜɴᴅᴄʟᴏᴜᴅ, ᴀᴘᴘʟᴇ ᴍᴜsɪᴄ, sᴘᴏᴛɪғʏ, ʀᴇssᴏ ᴀɴᴅ ᴛᴇʟᴇɢʀᴀᴍ ᴀᴜᴅɪᴏs & ᴠɪᴅᴇᴏs sᴜᴘᴘᴏʀᴛ.
* ᴡʀɪᴛᴛᴇɴ ғʀᴏᴍ sᴄʀᴀᴛᴄʜ, ᴍᴀᴋɪɴɢ ɪᴛ sᴛᴀʙʟᴇ ᴀɴᴅ ʟᴇss ᴄʀᴀsʜᴇs.
* ᴀᴛᴛʀᴀᴄᴛɪᴠᴇ ᴛʜᴜᴍʙɴᴀɪʟs, ғᴏɴᴛs ᴀɴᴅ ɪᴍᴀɢᴇs,  ᴍᴀᴋɪɴɢ ᴇxᴘᴇʀɪᴇɴᴄᴇ ᴍᴏʀᴇ ᴜsᴇʀ-ғʀɪᴇɴᴅʟʏ ᴀɴᴅ ɪɴᴛᴇʀᴀᴄᴛɪᴠᴇ.
* ʟᴏᴏᴘ, sᴇᴇᴋ, sʜᴜғғʟᴇ, sᴘᴇᴄɪғɪᴄ sᴋɪᴘ, ᴘʟᴀʏʟɪsᴛs ᴇᴛᴄ sᴜᴘᴘᴏʀᴛ
* ɢʟᴏʙᴀʟ, ᴜsᴇʀs, ᴄʜᴀᴛs ᴛᴏᴘ 𝟷𝟶 ᴘʟᴀʏᴇᴅ ᴛʀᴀᴄᴋs sᴛᴀᴛs
* ᴍᴜʟᴛɪ-ʟᴀɴɢᴜᴀɢᴇ sᴜᴘᴘᴏʀᴛ


# 🔗 An Overview

Here's a brief high-level overview of the Yukki Music Bot:

This project is based on [Pyrogram](https://github.com/pyrogram) and [Py-Tgcalls](https://github.com/pytgcalls/pytgcalls) . Pyrogram is a modern, elegant and asynchronous MTProto API framework.

* For database, Yukki uses the MongoDB to store data and keys. [MongoDB](https://www.mongodb.com/) is a document database with the scalability and flexibility that you want with the querying and indexing that you need.
* Project uses the bs4 web scrapping for getting many platform details. [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) is a Python library for pulling data out of HTML and XML files.
* The project uses the font [`Raleway`](../assets/font2.ttf) as its main font for the thumbnails.
* The projects uses attractive images and icons which you can get in [assets](../assets/) directory.

For more information on the technologies that power the Yukki Music Bot, check out the [Docs](https://notreallyshikhar.gitbook.io/yukkimusicbot/).



# ⚡️ Getting Started

### Before deploying Yukki Music Bot , please have a look towards [all available config vars](../config/README.md) , also please check [all available commands](../strings/command.yml) of the project.

> If you want to start working with Yukki Music Bot you can either fork or import repo .
> The official [documentation site](https://notreallyshikhar.gitbook.io/yukkimusicbot/) contains a lot of information. The best place to start is from the deployment section.
> If you'd like to talk to us, join us on our [Telegram Group](https://t.me/YukkiSupport)


## 🖇 Prerequisites

> In order to avoid conflicts in your project, you must have/installed

- [Python3.9](https://www.python.org/downloads/release/python-390/)
- [Telegram API Key](https://docs.pyrogram.org/intro/setup#api-keys)
- [Telegram Bot Token](https://t.me/botfather)
- [MongoDB URI](https://notreallyshikhar.gitbook.io/yukkimusicbot/deployment/mongodb)
- [Pyrogram String Session](https://notreallyshikhar.gitbook.io/yukkimusicbot/deployment/string-session)


## 🖇 Generating Pyrogram String Session

- Generate a Pyrogram String Session via [Replit](https://replit.com/@NotReallyShikhar/Yukki-Music-String-Gen)

- Generate a Pyrogram String Session via [Telegram String Generation Bot](https://t.me/YukkiStringBot)


## 🚀 Heroku Deployment

<h4>Click the button below to deploy Yukki on Heroku!</h4>    
<a href="https://yukki.tech/deploy/"><img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" width="200""/></a>

> Want detailed explanation of Heroku Deployment? [Click Here](https://notreallyshikhar.gitbook.io/yukkimusicbot/deployment/heroku)


## 🖇 VPS Deployment

> Checkout [Docs](https://notreallyshikhar.gitbook.io/yukkimusicbot/deployment/local-hosting-or-vps) for Detailed Explanation on VPS Deploy


```console
shikhar@MacBook~ $ git clone https://github.com/TeamYukki/YukkiMusicBot
shikhar@MacBook~ $ cd YukkiMusicBot
shikhar@MacBook~ $ sudo bash setup
```
> Setup will install each and every requirement, nodejs and pip packages automatically. After successfull installation of requirements , setup will ask you to input your vars.
> Please input your vars correctly.

```console
shikhar@MacBook~ $ bash start
```

> Not Getting VPS Method? [Watch Tutorial](https://t.me/TheYukki/2275)


<img src="https://telegra.ph/file/6b75b57da50ef1183fcdc.jpg" align="center">


## 🏷 Support

Reach out to the maintainer at one of the following places:

- [GitHub Issues](https://github.com/TeamYukki/yukkimusicbot/issues/new?assignees=&labels=question&template=SUPPORT_QUESTION.md&title=support%3A+)
- Contact options listed on [this GitHub profile](https://github.com/TeamYukki)
- [Telegram Support](https://t.me/YukkiSupport)

## 🎗 Project assistance

If you want to say **thank you** or/and support active development of YukkiMusicBot:

- Add a [GitHub Star](https://github.com/TeamYukki/YukkiMusicBot) to the project.
- Fork the Repo :)
- Write interesting articles about the project on [Dev.to](https://dev.to/), [Medium](https://medium.com/) or your personal blog.

PS: You can buy me a coffee too :)
<p><a href="https://www.buymeacoffee.com/notreallysy" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 35px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a></p>

Together, we can make YukkiMusicBot **better**!

## ✍🏻 Contributing

First off, thanks for taking the time to contribute! Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make will benefit everybody else and are **greatly appreciated**.

Please read [our contribution guidelines](CONTRIBUTING.md), and thank you for being involved!

## 👨🏻‍💻 Authors & contributors

The original setup of this repository is by [Team Yukki](https://github.com/TeamYukki).

For a full list of all authors and contributors, see [the contributors page](https://github.com/TeamYukki/YukkiMusicBot/contributors).

## ⚠️ Security

YukkiMusicBot follows good practices of security, but 100% security cannot be assured. YukkiMusicBot is provided **"as is"** without any **warranty**. Use at your own risk.

For more information and to report security issues, please refer to our [`SECURITY.md`](SECURITY.md)


## 🗂 License

This project is licensed under the **GNU General Public License v3**. All designs were created by [@NotReallyShikhar](https://github.com/NotReallyShikhar) .

See [LICENSE](../LICENSE) for more information.

## 📑 Acknowledgement

Special thanks to these amazing projects/people which/who help power Yukki Music Bot:

- [Pyrogram](https://github.com/pyrogram/pyrogram)
- [Py-Tgcalls](https://github.com/pytgcalls/pytgcalls)
- [CallsMusic Team](https://github.com/Callsmusic)
- [TheHamkerCat](https://github.com/TheHamkerCat)
- [Charon Baglari](https://github.com/XCBv021)


Reminder that you are great, you are enough, and your presence is valued. If you are struggling with your mental health, please reach out to someone you love and consult a professional.
