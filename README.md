#Changed 2 lines as per the advice in this post
https://www.reddit.com/r/discordapp/comments/azwl9c/webhook_that_tails_a_logfile/

# log-to-discord
Tails 
logs and posts to discord

### Installation
Download the package and then either pass the webhookurl and logfile as env or edit the index.js file

### Usage  
    WEBHOOKURL=WEBHOOK_URL_HERE LOGFILE=/etc/someapp/logs/somelog.log node index.js
if you code the webhook url and logfile path into the index.js file then  

    node index.js
