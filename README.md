 # Raidbot
>[*] Made by Alex-Smir and Rhinik (github.com)

>This is Raid Bot for vk.com
## Install
```bash
git clone https://github.com/ALex-Smir/raidbot.git
``` 
## Run
At the main repo directory run `code` like a module:
```bash
cd raidbot
python3 -m code
```
## Config params
Make `config.py` at the `raidbot/code/` directory and add this params

|Name|Type|Description|
|:-:|:-:|:-|
|TOKEN|str|Your API token|
|VERSION|str|API version. Recommend '5.123'|
|GROUP_ID|int|VK group id|
|FLOOD_MSG|str|Flood message|

## Abilities
The Raidbot can flood in several chats concurrently. Because of this, usually VK starts to lag and crashes. Also, a keyboard is attached to the flood-messages, when VK's user click on it, he will send a message with the site 'vto.pe', for which VK will give a ban to this user. Be careful)  

## Recommendations
Create virtual enviroment and install packages there
```bash
cd raidbot
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
```
After session you can deacticate your env
```bash
deactivate
```
It is also advisable to use python 3.8+ (not lower than 3.8)
```bash
python=3.8+
```
Possible `FLOOD_MSG` check at the `raidbot/code/__init__.py`
