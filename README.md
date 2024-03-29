Open in Autocode
================

To add an Open in Autocode button to your GitHub repository,
simply copy and paste the following code anywhere into README.md

[<img  data-src="https://deploy.stdlib.com/static/images/deploy.svg" width="192">](https://open.autocode.com/)

Enjoy!
  - Standard Library Team


<div align="center">
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-0-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
<h1><strong>Play Together</strong></h1>

[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)

[![npm](https://img.shields.io/npm/dt/@miudiscord/together?style=for-the-badge)](https://npmjs.org/@miudiscord/together)
</div>

# 🔩 Installation
## Install [@miudiscord/together](https://www.npmjs.com/package/@miudiscord/together)
```
$ npm install @miudiscord/together
```

## Install [discord.js](https://www.npmjs.com/package/discord.js)
```
$ npm install discord.js
```

# 🔑 Features
- Easy to use and understand
- Multiple server support
- Discord API support
- Fast

<br/>

# 💻 Code example
- [Javascript Example](https://github.com/miudiscord/together/blob/stable/examples/javascript/JavascriptBot.js)
- [Typescript Example](https://github.com/miudiscord/together/blob/stable/examples/typescript/TypescriptBot.ts)

# 🔧 Options
- Youtube
```js
client.together.generateTogetherCode(message.member.voice.channelID, 'youtube').then(async invite => {
    return message.channel.send(`${invite.code}`);
});
```

- Poker
```js
client.together.generateTogetherCode(message.member.voice.channelID, 'poker').then(async invite => {
    return message.channel.send(`${invite.code}`);
});
```

- Betrayal
```js
client.together.generateTogetherCode(message.member.voice.channelID, 'betrayal').then(async invite => {
    return message.channel.send(`${invite.code}`);
});
```

- Fishing (*This most likely crashes the game*)
```js
client.together.generateTogetherCode(message.member.voice.channelID, 'fishing').then(async invite => {
    return message.channel.send(`${invite.code}`);
});
```

# 🌌 Example of bots made with Play Together

#### [EZIO 2.0#7598 | 793127803041218590](https://top.gg/bot/793127803041218590) 

> ***If you want your bot to be listed, Contact Xanll after joining the Discord server. Open sourced bots are greatly appreciated.***

# 📷 Images/Preview

### YouTube Together (Unlimited participants)

<details><summary>Preview Image</summary>

![YouTube Together Loading Screen](https://i.imgur.com/42Nl7cG.png)
![YouTube Together Landing Screen](https://i.imgur.com/HYDZx5l.png)
![YouTube Together Player Screen](https://i.imgur.com/g4Nsixe.png)

</details>

<br>

<details><summary>Invite Link Preview</summary>

![YouTube Together Invite](https://i.imgur.com/PkatSal.png)

</details>

### Poker Night (7 participants)

<details><summary>Preview Image</summary>

![Poker Night Loading Screen](https://i.imgur.com/LLhaTMC.jpeg)
![Poker Night Landing Screen](https://i.imgur.com/AhKlD7u.png)
![Poker Night In-Game Screen](https://i.imgur.com/3p7es78.png)

</details>

<br>

<details><summary>Invite Link Preview</summary>

![Poker Night Invite](https://i.imgur.com/RP8CcWo.png)

</details>

### Betrayal.io (12 participants)

<details><summary>Preview Image</summary>

![Betrayal.io Loading Screen](https://i.imgur.com/kAgwgJr.png)
![Betrayal.io Landing Screen](https://i.imgur.com/gRBDf4C.png)
![Betrayal.io In-Game Screen](https://i.imgur.com/LpQ3dhr.png)

</details>

<br>

<details><summary>Invite Link Preview</summary>

![Betrayal.io Invite](https://i.imgur.com/6ZMiIfL.png)

</details>

### Fishington.io (Unlimited participants)

<details><summary>Preview Image</summary>

![Fishington.io Loading Screen](https://i.imgur.com/tba7scA.jpeg)
![Fishington.io Landing Screen](https://i.imgur.com/zZCP5Ri.png)
![Fishington.io In-Game Screen](https://i.imgur.com/sMi5zX3.png)

</details>

<br>

<details><summary>Invite Link Preview</summary>

![Fishington.io Invite](https://i.imgur.com/zBoXtxa.png)

</details>

# 🚀 Others

**This package is under MIT license.**

*Note: This package is not affiliated with Discord, YouTube or End Game Interactive.*

If you have any problems, you can contact the developers by joining the Discord server.
**Discord server:** [Server Link](https://discord.gg/HrHFmAceRM)

[**Github repository**](https://github.com/miudiscord/together)

<hr>

## **Made with ❤ by [Xanll#7264](https://xanll.vercel.app) & [Ayush#5234](https://ayushch.tech)**
