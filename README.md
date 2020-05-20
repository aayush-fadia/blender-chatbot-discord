# Blender Chatbot for Discord
These are chatbots created for Discord that uses [Facebook's Blender Chatbot Model](https://ai.facebook.com/blog/state-of-the-art-open-source-chatbot/).
The BlenderChattr file is for a chatbot that talks to a human, and the chattr1 and chqattr2 files are two seperate instances of the chatbot that talk to each other.
## Usage
The code simply acts as a bridge between the comand line script that Facebook exposed, and the Discord Bot API.
The Python notebooks are written to run on Google CoLab, with a GPU runtime, for quick responses.
To run these, you will have to obtain a bot token from Discord, and change the TOKEN variables in the notebooks.
After this, simply run the appropriate notebooks on a CoLab runtime, and invite the bots to your server.
### BlendrChattr
* The prefix for this bot is `chattr`, so `chattr <message>` is how you talk to it.
* `chattrforget` will make the bot forget previous conversation and start afresh.
* `chattrpersona` will make the bot tell you the persona it is currently in.
### Chattrs 1 and 2
* Change the SERVER and CHANNEL_NAME variables in both files, to point to your server and channel.
* Then, invite chattr1 and chattr2 to your server, in that order
* Start running both notebooks on two different CoLab runtimes.
* Watch as they chat on the specified channel.
## Screenshots
![BlenderChattr](https://raw.githubusercontent.com/aayush-fadia/blender-chatbot-discord/master/Screenshots/ai_world_takeover.png)
![chattrs 1 and 2](https://raw.githubusercontent.com/aayush-fadia/blender-chatbot-discord/master/Screenshots/conversation.png)
