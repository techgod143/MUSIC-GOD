# MUSIC-GOD
FASTEST BOT IN THIS WORLD AND WORK 24*7 Hours
<div align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Ribeye&size=50&pause=1000&color=G0B1&center=true&width=910&height=100&lines=YouTube+Channel+TECH+GOD;SIMPLE+Bot+MUSIC+GOD;WA+NUMBER+*+91+9012008456;PROGRAM+By+TECH+GOD" alt="Typing SVG" /></a>
<p align="center">  
  <a href="https://youtube.com/@techgod143">
    <img alt=MUSIC-GOD height="300" src="https://i.imgur.com/oYoObSY.jpg">
   
</a> 
    
</p>
<p align="center">
<a 

####  
MUSIC-GOD SIMPLE Whatsapp Bot.

***

#### SETUP

1. Fork The Repo
    <br>
<a href="https://github.com/techgod143/MUSIC-GOD/fork"><img title="MUSIC-GOD" src="https://img.shields.io/badge/FORK MUSIC GOD-h?color=GREEN&style=for-the-badge&logo=stackshare"></a>



## Deploy on any shell including termux

- Fork repo
- edit the config.js file as per your details
- install the following dependencies
  - ffmpeg
  - nodejs
- clone the repo
- change the directory to cloned repo
- run `npm install`
- run `npm install qrcode-terminal`
- run `node .`
- scan the qr
- Done your bot is alive
- run ``node .` again to run it again after you stop the bot

---

# Using X-asena

## Creating a plugin

```javascript
const { command, isPrivate } = require("../lib/"); //importing functions

command(
  {
    pattern: "ping", //command
    fromMe: isPrivate /*need to respond for everyone's message
true : only from sudo numbers
false : from everyone
isPrivate same as false but will be considered as true if worktype is private*/,
    desc: "To check ping", //description of the command
    type: "user", //command type
  },
  async (message, match) => {
    /*


PLUGIN CONTENT HERE


*/
  }
);
```

## Sending Messages

### Replying

```javascript
message.reply("Hi");
```

### Media

```javascript
let content = "https://wallpaperaccess.com/full/5531321.jpg"; //can also use buffer
message.sendMessage(
  content,
  {} /*options*/,
  "image" /*change to audio , video while sending audio or video */
);
```

### Sticker

```javascript
message.sendMessage(
  "url or buffer of image or video(max 10 seconds)",
  { packname: config.PACKNAME, author: config.AUTHOR },
  "sticker"
);
```

### [External Plugins](https://github.com/X-Electra/X-Asena/wiki/Plugins)

## Any Doubts ?

[![JOIN WHATSAPP GROUP](https://raw.githubusercontent.com/Neeraj-x0/Neeraj-x0/main/photos/suddidina-join-whatsapp.png)](https://chat.whatsapp.com/ESiNt1pudB1Js6QRZtM0jg)

#### Official Image

[![Docker Repository on Quay](https://quay.io/repository/xelectra/xasena/status "Docker Repository on Quay")](https://quay.io/repository/xelectra/xasena)

### THANKS TO

- [Adhiraj Singh](https://github.com/adiwajshing)
- [Yusuf Usta](https://github.com/yusufusta)
- [Neeraj-x0](https://github.com/Neeraj-x0)
- [Adityan](https://github.com/A-d-i-t-h-y-a-n)
- [SamPandey001](https://github.com/SamPandey001)
- [TSH3PHANG](https://github.com/TSH3PHANG)
- [Diegoson](https://github.com/Diegoson)
- [Viper-x0](https://github.com/Viper-X0)
- [Lord-Official](https://github.com/Lord-official)
- [Ajmal-Achu](https://github.com/Ajmal-Achu)

```
MIT License

Copyright (c) 2023 X-Electra

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```
