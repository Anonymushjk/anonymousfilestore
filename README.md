
### Features
- Fully customisable.
- Customisable welcome & Forcesub messages.
- More than one Posts in One Link.
- Can be deployed on heroku directly.

### Setup

- Add the bot to Database Channel with all permission
- Add bot to ForceSub channel as Admin with Invite Users via Link Permission if you enabled ForceSub 

##
### Installation
#### Deploy on Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/rakeshyt/DevilFilesStore)</br>


### Admin Commands

```
/start - start the bot or get posts

/batch - create link for more than one posts

/genlink - create link for one post

/users - view bot statistics

/broadcast - broadcast any messages to bot users
```

### Variables

* `API_HASH` Your API Hash from my.telegram.org
* `API_ID` Your API ID from my.telegram.org
* `TG_BOT_TOKEN` Your bot token from @BotFather
* `OWNER_ID` Must enter Your Telegram Id
* `CHANNEL_ID` Your Channel ID eg:- -100xxxxxxxx
* `ADMINS` Optional: A space separated list of user_ids of Admins, they can only create links
* `FORCE_SUB_CHANNEL` Optional: ForceSub Channel ID, leave 0 if you want disable force sub

### Extra Variables

* `CUSTOM_CAPTION` put your Custom caption text if you want Setup Custom Caption, you can use HTML and <a href='https://github.com/rakeshyt/DevilFilesStore/blob/main/README.md#custom_caption'>fillings</a> for formatting (only for documents)
* `DISABLE_CHANNEL_BUTTON` Put True to Disable Channel Share Button, Default if False

### Fillings
#### START_MESSAGE | FORCE_SUB_MESSAGE

* `{first}` - User first name
* `{last}` - User last name
* `{id}` - User ID
* `{mention}` - Mention the user
* `{username}` - Username

#### CUSTOM_CAPTION

* `{filename}` - Original Files Name
* `{file_name}` - Original Caption


CUSTOM_CAPTION
```
<code>{file_name}</code>

🤭 𝗔𝗟𝗟 𝗠𝗢𝗩𝗜𝗘𝗦 𝗛𝗘𝗥𝗘 🥱

<a href="http://t.me/RYMOFFICIAL">1☞𝙅𝙤𝙞𝙣 𝙊𝙛𝙛𝙞𝙘𝙞𝙖𝙡 𝘾𝙝𝙖𝙣𝙣𝙚𝙡</a>

<a href="http://t.me/SonalModdingGod">2☞ 𝙅𝙤𝙞𝙣 𝙈𝙤𝙫𝙞𝙚𝙨 𝙂𝙧𝙤𝙪𝙥</a>

<a href="https://t.me/JaiHindChatting">3☞ 𝙅𝙤𝙞𝙣 𝘾𝙝𝙖𝙩𝙩𝙞𝙣𝙜 𝙂𝙧𝙤𝙪𝙥</a>

<a href="https://t.me/THEDRAGONV6">4☞ 𝙅𝙤𝙞𝙣 𝙁𝙚𝙙 𝙂𝙧𝙤𝙪𝙥</a>
```
