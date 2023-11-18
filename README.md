# 🤖 Pirogram - Telegram Auto Reply Bot

<p align="center">
  <img src="https://user-images.githubusercontent.com/5070591/115477479-2a8d2f00-a28a-11eb-85e7-aedbf1a9f829.png">
</p>

<p align="center">
  <a href="https://github.com/hk4crprasad/pirogram">
    <img src="https://img.shields.io/github/stars/hk4crprasad/pirogram?style=for-the-badge&color=ee6712"> 
  </a>
  <a href="https://pypi.org/project/pirogram">
    <img src="https://img.shields.io/pypi/v/pirogram?style=for-the-badge&color=11b8cc">
  </a>
</p>

Pirogram is a Python library that allows you to auto-reply to messages on Telegram when you are offline!

## 🚀 Features

- Send automatic replies when offline ✔️
- Block spammers who send too many messages ❌️  
- Reply with jokes, quotes to engage users 🃏
- Get notifications when someone messages you 📨
- Customize replies easily!

<br>
  
<p align="center">
  <img src="https://user-images.githubusercontent.com/5070591/115477657-767b7e80-a28a-11eb-9b50-f59221c9e15d.png">
</p>

<p align="center"> 
  <b>Demo of Pirogram auto-replying on Telegram</b>
</p>

## 📥 Installation

```bash
pip install pirogram
```

```bash
git clone https://github.com/hk4crprasad/pirogram.git
cd pirogram
pip install .
```

## 🤹 Usage

### Get API Credentials

<a href="https://my.telegram.org"><img src="https://user-images.githubusercontent.com/5070591/115477866-d465d980-a28a-11eb-80e1-f3f5dcfbbdc3.png" width="240px"></a>

- Visit [my.telegram.org](https://my.telegram.org) and login  
- Go to API Development tools
- Create a new app
- Copy `api_id` and `api_hash`

### Run the Bot

```python
from pirogram import Pirogram

api_id = 'YOUR_API_ID' 
api_hash = 'YOUR_API_HASH'

bot = Pirogram(api_id, api_hash)
bot.run()
```

Now your account will auto-reply when offline! 🎉

### Customize Replies

```python
replies = [
  "I'm offline!",
  "Leave a message after the beep...",
  get_random_joke()
]

bot.set_replies(replies) 
```

## 🧑 Author 

Made with ❤️ by [hk4crprasad](https://github.com/hk4crprasad)

## 📄 License

[GPL-3.0](https://github.com/hk4crprasad/pirogram/blob/master/LICENSE)

Let me know if you would like me to modify or enhance this README further!
