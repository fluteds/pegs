<br class="center">
    <img src="/media/philza-sig.png" alt="Philza Logo" />
</br>

# Phil's Early Gang Society

Also known as PEGS or Early Gang. Here you will find some useful resources for offline/online chat and useful tools that can improve your Twitch experience.

If you have any questions or want something taken off or put on whisper me on Twitch `@fluted`. If you have a hand in using GitHub or know how to do pull requests, this site is fully open sourced! This site is not affiliated with Philza directly or any streamers mentioned. Please use caution when clicking on external links.

## 📼 VODS

Looking to catch up on past streams?

- `!vods` - Chat command that sends an annoucement link to our vod sheet!
- [VOD Sheet](https://tinyurl.com/PhilzaVODList) - Community ran Google Doc that contains links, timestamps and short summaries on past VODs. You can submit your own timestamps and summaries to be reviewed using the form link on the document. Made by Skyler and the Philza archive team.
- [Unofficial Philza VODs YouTube Channel](https://www.youtube.com/@Philza_VODS) run by Mercy and is rapidly growing. Philza endorsed.

## 🖥️ Desktop Chatters

### Chatterino

Want to chat more offline and online? Most of us use a handy chat client called [Chatterino](https://chatterino.com/) to chat with fellow Pegs online and offline. *Note: You cannot gain points or interact with polls, channel point redeems or gambling points while watching a stream/being in chat using Chatterino you must have the Twitch chat in a browser open.*

*Some* of the Many Features

- Custom pings/highlights.
- Streamer mode.
- Link previews.
- Image previews.
- Mentions panel.
- User ignore.
- Chat filters, such as local sub mode.
- Highlight/filter bits, subs and more.
- Multiple chat windows.
- [Check out my filters to help you get started with them.](https://gist.github.com/fluteds/a97038a7ffa1beece30974ec8cca0291)

#### Setting Up Chatterino

Chatterino can be very overwhelming to use when you first download it. Skyler made a [very useful and helpful Google Doc](https://docs.google.com/document/d/155OY6ndhY3Iy_4xo9Nf6fkRFgsWBrjjgqHGip4Vf4D0/edit) explaining all the main features of Chatterino and how to set it up to how you want it. Link to the guide can be found [here.](https://docs.google.com/document/d/155OY6ndhY3Iy_4xo9Nf6fkRFgsWBrjjgqHGip4Vf4D0/edit)

#### Backing Up Settings

My small simple Batch script for Windows users to backup their Chatterino settings to Google Drive and vice versa. I made it for myself but I think others could also use this. The source code can be found and read [here!](https://github.com/fluteds/batch/blob/main/command/misc/copy-chatterino-settings.cmd) *Note: Requires Google Drive for Desktop to use this script out of the box.*

<details>
  <summary>How to Download and Install the Script - Click to Expand</summary>

**Download**

- To download the batch file go [here.](https://raw.githubusercontent.com/fluteds/batch/main/command/misc/copy-chatterino-settings.cmd) (GitHub)
- Save via Right Clicking and selecting `Save Page As`.

**Running**

![DinkDonk](/media/emotes/DinkDonk-1x.gif) *Copy your settings folder to a safe place before running the script for the first time. Just incase anything goes wrong.*

Out of the box the script assumes your Chatterino settings are saved at `C:\Users\%username%\appdata\roaming\chatterino2\settings\` and your Chatterino Google Drive backup is saved at `G:\My Drive\Chatterino\`. If you're tech savvy you can change the location variables (`drivePath` & `chatterinoPath`) in the script with Notepad.

- Double click on the saved `bat` file.
- Accept the Windows security pop up, this file is 100% safe. [You can double check here.](https://www.virustotal.com/gui/file-analysis/YmU2ZjA2ZGU0OTNlYjE1Njc2Y2E0MTliOWI3ZGMxMDA6MTY2NjM1ODEwMg==)
- Follow the instructions on the terminal popup.

</details>

### Chatterino Forks

There are lots of different versions of Chatterino for you to use, most of them are based upon the "nightly" version, kind of like a beta, which releases more often than major stable updates. Most of these forks use nightly as a foundation and have useful features that the normal stable version doesn't have.

- [Dankerino](https://github.com/Mm2PL/dankerino) - Adds quality of life and features (or fixes) that aren't accepted yet into the upstream repo and keeps inline with development of the nightly version. Dankerino also has 7TV badges support pulled from Chatterino7.
- [Chatterino7](https://github.com/SevenTV/chatterino7) - Chatterino but adds 7TV emote support. Kept inline with nightly Chatterino.
- [Chatterino Pronouns](https://github.com/GabeEddyT/chatterino2) - The Pronoun version of Chatterino includes support for the Twitch Chat Pronouns extension created by [Alejo47](https://pronouns.alejo.io). *Note: Pronouns need to be toggled on in settings for them to show and user pronouns are loaded for ALL users individually in ALL chats at once and is not reccomended for lower end PCs.*

**Other Desktop Chat Clients**

- [Chatty](https://chatty.github.io/) - Chatty is a chat software specifically made for Twitch, in the spirit of a classic IRC Client.
- IRC Client - You can actually connect to Twitch via an IRC client such as HexChat or any IRC client. `irc.chat.twitch.tv/6697` For login method use `/PASS` protocol and use SSL for all servers on the network. [Auth token /PASS generator](https://twitchapps.com/tmi/).

## 📱 Mobile Chatters

Want to chat on the go? These apps are useful for mobile chatters. All of the following applications are open sourced and can be sideloaded or installed using an APK.

- [Chatsen (iOS and Android)](https://chatsen.app/) - Twitch chat application for iOS and Android with support for 7TV, BTTV and FFZ. Add up to 4500 channels. Not many people know Chatsen also has livestream support. *
- [Dankchat (Android Only)](https://dank.chat/) - Chat in multiple channels at once, regardless if the streamers are live or offline, with FrankerFaceZ, BTTV and 7TV emote support built-in.
- [Frosty (iOS and Android)](https://frostyapp.io/) - Meant to be an alternative to the Twitch mobile app with browsing, vod watching, 7TV, BetterTTV (BTTV), and FrankerFaceZ (FFZ) support.

**To enable subscriber perks in the livestream video viewer (such as no ads) you will need to sign into Twitch on the livestream browser.*

## 🌐 Browser Chatters

Useful tools if you only use the Twitch browser chat. Most of these extensions provide more than just more emotes and things for chatters. More information about emotes can be found in the section below.

### BetterTTV Extension

BetterTTV enhances Twitch with new features, emotes, and more.

Features

- New emotes.
- Username pings.
- Readable username colours.
- Split chat colours.
- Disable autoplay on the frontpage.
- Hide bits, friend list and Prime promotions.
- Hide banners across chat (such as vote & predictions.)
- Hide recommended channels/recommended friends.
- Hide channel extensions that overlay on the video.

### Frankerfacez Extension

Get custom emotes and tons of new features you'll never want to go without. This extension has the same, if not a few more, features than BetterTTV. I've highlighted the most important ones below.

Features

- Even more emotes.
- Volume gain (makes stream audio louder without touching your volume.)
- Auto theatre mode.
- Auto open chat when visiting a profile.
- Addons! Enable 7tv emotes without even installing 7tv or enable some more addons like Chatterino badges.

## Emotes

Wondering why we're all spamming `catKISS` or `philzaHug`? Better Twitch TV is a browser extension which enables you to see them! Head on over to [betterttv.com](https://betterttv.com) to find out more about installing so `catKISS` turns into ![catKISS](/media/emotes/catKISS-1x.gif)

Chat command: `!bttv`

### Channel Emotes

The Philza emotes were created by [Glamist](https://twitter.com/Glamist_art) ![Ph1lEarly Emote](https://static-cdn.jtvnw.net/emoticons/v2/303887095/static/light/1.0) and the Mumza emotes (`Ph1lM`) were made by [TheElliPelli](https://twitter.com/TheElliPelli) ![Ph1lMcrow](https://static-cdn.jtvnw.net/emoticons/v2/emotesv2_fe1f2e7fd0f443dea05fd11a6423fec2/static/light/1.0) Check out their work over on  X/Twitter.

All credits for 3rd party emotes are found on the emote description [on the following site.](https://betterttv.com/users/587002e0c1869d57085734a8) For more emotes created by Early Gang and Onliners, check out the `#philza` tag on [BetterTTV.](https://betterttv.com/emotes/shared/search?query=philza)

## Commands

### Chatterino Commands

Utilise Chatterino commands and make sending repated messages easier. E.g. typing `/energy` sends `༼ つ ◕_◕ ༽つ TAKE MY ENERGY ༼ つ ◕_◕ ༽つ` in chat. Find some suggested Chatterino commands for chat [here.](https://docs.google.com/spreadsheets/d/1XFcyuSC74_OYiYEd4HdFrfWJlwt86dZEtqgrOkt6z6Y/edit#gid=0)

### Fossabot Commands

"Did you know? Philza has an Official Discord you can join for upda-" Fossabot is our chat moderation bot. Some good commands to get you started: `!project`, `!vods`, `!s4` and `!mods` or check out [Fossabot's Full Chat Command List](https://fossabot.com/philza/commands).

## Other Spreadsheets and Resources

These are all run by other people in chat or other chat members. Like most things, please use caution clicking on external links in docs and spreadsheets.

### Pronouns

A Google Doc list of Early Gang pronouns, managed by Skyler. You can find the link [here.](https://docs.google.com/document/d/1FaOotlbpACEoyPWcVbcxNf-V2vzZRp9qs8LJaZrNUZo/edit) *Note: this is an opt in/out document, if you wish to have your pronouns added or updated, please read the instructions on the document.*

### Offline Chat Names

Wonder why we mention `c_` or `innitfam` and want to know what they are? These are names for other MCYT's offline chats! Check out the full names spreadsheet [here.](https://docs.google.com/spreadsheets/d/1ZT8IBLybmwe1RKCKNK7K7T4NfrV1OX_UZnx8BHXi1bM/edit) Made by gremlxnn from `c_`. *Note: this is an opt in/out document, if you wish to have information updated or removed, please read the instructions on the document.*

### VOD Stats

Spreadsheet containing all information about the stream stats. Including vod lengths, categories, monthly stats and stream stats. [Link to spreadsheet here.](https://docs.google.com/spreadsheets/d/1wjufR0zxklO1qY_iaGoHv78hUU6kgiw_Ca7hDrJNwzw/edit#gid=0) Made by the Philza archive team.

### Open or Closed Popza Stats

Spreadsheet about whether stream ended on an open or closed Popza emote. [Link to spreadsheet here.](https://docs.google.com/spreadsheets/d/1yyeF_fQdcbVkn0ZxC7gb-A-h1TpttqvbU7DtqYTsSiU/edit#gid=0) Made by Skyler.

### Chat Stats

Streamelements webpage containing stats about top chatters, emotes and more! [Link to website here.](https://stats.streamelements.com/c/philza)

## Credits

Check out the following resources. ![catKISS](https://cdn.betterttv.net/emote/5f455410b2efd65d77e8cb14/1x)

- [Early Gang Helpful Links Doc](https://docs.google.com/document/d/11vclJ_Y3iEPQ9JVUsXhZjEeP2TMypP9aRAirz0QKTg4/edit) (If this website ever becomes inactive please refer back to this document! Maintained by Skyler.)
- [Channel Emotes](https://www.twitchemotes.com/channels/3389768) (`ph1lEarly`, `ph1lPopza` & `ph1lMcrow`)
- [BTTV Emotes](https://betterttv.com/users/587002e0c1869d57085734a8) (`catKISS`, `BONK` & `DinkDonk`)
- [Share Image](https://imgur.com/a/SVj22fn) (From Phil's Endlantis Album)
- [Philza Logo](https://ph1lzamerch.com/)
- [Site Template](https://yuanqing.github.io/single-page-markdown-website/)
