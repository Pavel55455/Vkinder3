VKinder diploma of Netology

Dating bot analogue of Tinder.

To run the bot you need a user token and your community token.

You must add these tokens to the environment variables:

export COMMUNITY_TOKEN=vk1.aXyZy...

export USER_TOKEN=vk1.aXyZy...

Warning
1. Make sure that Callback API is enabled in your community settings
2. 
3. When creating a user token, use this link by changing client_id to the id of your application. This link generates an indefinite token with the required parameters. Not all applications support indefinite tokens, be careful! 
https://oauth.vk.com/authorize?
client_id=1&display=page&redirect_uri=https://oauth.vk.com/blank.html&scope=friends,photos,offline&response_type=token&v=5.131&state=123456

Launch Instructions

1. Create an empty directory
2. 
3. git clone https://github.com/Pavel55455/vkinder3.git ./
4. 
5. python3 - m venv venv
6.
7. source venv/bin/activate
8. 
9. pip install -r requirements.txt
10. 
11. nohup python bot.py &

