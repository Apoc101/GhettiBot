# GhettiBot
 > **Warning**: this bot contains some profanity, as it was designed to be more of a funny project than a professional one.
 <br>

 Bot made in node.js as a project originally spawned by non-admin users wanting to send deafend users to Bazorpa. 
 
 Most of the code is commented with descriptions.
 
 > **Note**:
 > 
 > The package requirements are commented at the top of `bot.js`
 > 
 > The prefix is `g.`
 > 
 > To add it to your server, [click here](https://discord.com/api/oauth2/authorize?client_id=941733393228505158&permissions=16777232&scope=bot)
 > 
 > If you want to run it with your own token, check that you have all of the required dependencies and then run:
 > `npm run dev` <br>
 > 
 > ('dev' is a nodemon command script I added to `package.json` for comodity while making the bot)
 > 
 > In `package.json`, the discord.js is interchangeable to 16.6.0 or whichever you need, just crosscheck bot.js with the documentation, because class properties like client.on(message, callback) are VERY prone to changes (even the Client constructor can easily change between versions).
<br>

I used an environment variable for the token (omitted from the repo for obvious reasons) in a .env file; <br> if you want to learn how to do that, [check out this link](https://nodejs.dev/learn/how-to-read-environment-variables-from-nodejs). 
 
 <br>
 Also, it's currently not hosted, as my RasPi is kind of a mess.
 <br>
 
 ## List of commands:
>
> **g.help** - Lists commands
 
> **g.baz @user / g.bazorpa @user** - Sends that dumb cretin to bazorpa: custom command for [the "gamer" server](https://discord.gg/nJQvwGb32g) (it wont work if the command is used in any other server, due to a variable containing a specific ID of the voice channel, although I might eventually make `..args` into an array so that you can add a custom ID to your own Bazorpa)

> **b @user** - Shortened bazorpa command, please don't abuse this since you will likely piss everyone off and probably regret it

> **g.ping** - Responds with a funny text

> **g.customer [num]** - Try guessing what this does

> **g.spam** - Starts spamming

> **g.stopspam** - Stops spamming

> **g.simo / cavo / mattia / gab / sigghy** - A random picture of whatever name you include
 
> **g.website** - Link to the epic Ghetti website
 
> **g.chat** - Link to Ghetti Chat
 
> **g.creator** - Link to my website
 
<br> 

The only perms this will ask for is to manage channels and it's for the bazorpa channel, at least for now.
