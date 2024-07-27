# Hello there.
## Currently Learning: [\*nothing\*](https://youtube.com/watch?v=17Jq0QqK4k0)
## Current Project: [GeminiBot](https://github.com/AetherMagee/GeminiNew)

## Past Projects:
- **AetherManager** - A Telegram chat manager bot, designed to provide **_chat cleanup_** and **_sequrity_**, while being **_quiet_** and **_fast_**
- **MCSOTIS** - One of my first "projects", intended to help you install and manage Minecraft servers on your phone via Termux easily

## Some code because why not
```python
from life.me.mindset import favouritethings

favouritethings.add(name="programming", priority=727)  # WYSI
```

```python
from aethermanager import bot, events, logger
from database.servicelayer.service import addUserEntry

@bot.on(events.NewMessage(pattern="(?i).*hello*", func=lambda x: x.is_private))
async def hello(msg):
  await msg.reply("Hi!")
  addUserEntry(msg.sender.id)
```
