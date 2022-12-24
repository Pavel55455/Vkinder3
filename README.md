VKinder diploma of Netology

Dating bot analogue of Tinder
To run the bot you need a user token and your community token.
You must add these tokens to the environment variables:

export COMMUNITY_TOKEN=vk1.aXyZy...

export USER_TOKEN=vk1.aXyZy...

Warning
Make sure that Callback API is enabled in your community settings
When creating a user token, use this link by changing client_id to the id of your application. This link generates an indefinite token with the required parameters. Not all applications support indefinite tokens, be careful! https://oauth.vk.com/authorize?client_id=1&display=page&redirect_uri=https://oauth.vk.com/blank.html&scope=friends,photos,offline&response_type=token&v=5.131&state=123456
Launch Instructions
Create an empty directory
git clone https://github.com/Pavel55455/vkinder.git ./
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
nohup python bot.py &
