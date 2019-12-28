# Welcome to the Redditor bot github
<p align="center">
  <img src="https://top.gg/api/widget/557580985646972928.svg?usernamecolor=FFFFFF&topcolor=000000" width="350" title="hover text">
</p>

### Find my discord bot page [Here](https://top.gg/bot/557580985646972928)

# About
Redditor is a bot that is capable of automatically grabbing new posts from subreddits, and posting them to your discord server. You pick which subreddit you want to see in which text channel.You can only have one subreddit in one text channel, so it's not possible (yet) to subscribe a single subreddit to multiple text channels.

Redditor sends out new posts about every 1-5 minutes. This depends on how many new posts there are to grab, as reddit has a rate limit for how much requests one single client is allowed to send.

A server is limited to a maximum of 10 subscriptions, after that you'll have to vote for the bot to unlock unlimited subscriptions for the next 24 hours.

My aim is to keep redditor completely free and rely solely on my own funds or donations. Redditor is hosted on a server located in France and is online 24/7.


# Important notes
Redditor will NOT post in channels that have slowmode enabled, redditor will automatically unsubscribe any channel that has slowmode enabled although you can still subscribe slowmode enabled channels to subreddits.

 

To subscribe/unsubscribe you MUST have either a role called "Redditor" or Administrator permissions. This is to avoid spam from unauthorized users.

# Commands
### .//Subscribe - Subscribe a text channel to a subreddit - Requires "Redditor" Role or Administrator Permissions
.//subscribe [subreddit name here] [text channel name here]
Do not include the brackets []!

Heres an example if you want to subscribe a text channel called memes to r/dankmemes :

.//subscribe dankmemes memes

 

### .//Unsubscribe - Unsubscribe from a text channel - Requires "Redditor" Role or Administrator Permissions
.//unsubscribe [subreddit]
Do not include the brackets []!

Heres an example if you want to unsubscribe from the subreddit r/dankmemes

.//unsubscribe dankmemes

Note that you do not need to enter a text channel

 

### .//List - See a list of all the subreddits you're subscribed to and which text channel they are in
.//list

No further parameters are needed for this command.

 

### .//Help - If you need to refresh your memory on the commands, this will help you
.//help

No further parameters are needed for this command.

 

### .//Vote - Sends a link to vote for Redditor
.//vote

No further parameters are needed for this command.

 

### .//Interval - Shows how long it took last time for the bot to grab all new posts
.//interval

No further parameters are needed for this command.
