
Fill the config.js and utils/gw-config.json With Your Credentials
# Config.js
```
module.exports = {
    "registercommands" : false, //Write True If You Are Launching The Bot First Time
     "token": "", //Your Super Secret Bot Token
    "imageapi": "", //Your Amethyste Api You can get it from https://api.amethyste.moe/
    "ownerID": [], //Your Discord User ID
"prefix": "", //Your Bot's Prefix
"mongourl": "", // Mongodb url You can see tutorial of it on https://www.youtube.com/watch?v=nj-lJfkgb6w
"secret": "", // Your super secret bot token You can get it from the section of Oauth2 of Discord Developer Portal named Client Secret
 "dashboardURL": "", // write https://localhost:3000 if you are hosting in your own pc/laptop and if using website hosting then connect domain and just write that website copy paste in here or enter ip of that hosting server with the port ahead of it
"chat": {
        "url": "",
        "bid": "",
        "key": "",
        "uid": ""
    }, // You can get This Things from https://brainshop.ai
"api": "", // Your Youtube Api
"youtubeAPI": "", // Your Youtube Api
mainprefix: "",  // Again Your Prefix
"owner": "G U D B O Y", // Owner Name

  basiclang: "en", //The basic language of the bot, "fr" for French and "en" for English
    embeds: {
        color: "BLUE", //Embed color (in English)
        footers: "GIVEAWAY :tada: :tada:" //Embed footer
    },

   

    events: {
        addcolor: "GREEN", //The color of the event add (in English)
        remcolor: "RED" //The color of the event remove (in English)
    },

    reaction: "🎉", //Reaction to the giveaways if you in the console you see 'unknown emoji' that's what this emoji is not recognized by Discord

    grole: "Giveaway Manager", //If the member doesn't have permission to handle messages he can still use the giveaways commands if he has the role configured right here

    auth: {
        support: "XXX", //The link of your Discord server
        dperms: "8" //The permissions that the bot asks on we want to add it on a Discord server (8 = moderator)
    }, 
} 
```
# gw-config.json
```{
    
 
    "ownerID": "720632216236851260",

    "everyoneMention": false,
    "hostedBy": true,
    "botsCanWin": false,


    "embedColor": "#000080",
    "embedColorEnd": "#FF0000",
    "reaction": "🎉",
    "giveawayEmoji": "🎉"

    
   
}
```
# Mongodb 
You can see the tutorial at https://www.youtube.com/watch?v=nj-lJfkgb6w
# Important Installation
After Downloading Project in Console Type `npm install` 
![terminal](https://user-images.githubusercontent.com/45940386/111021871-b22ee080-83e8-11eb-92cb-c2ff2ccc7b3f.png)
