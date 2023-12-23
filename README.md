

# PingGram
Simple ping utility that can ping an ip address, and optionally run a scheduled ping.

PingGram will also optionally send a web request when a scheduled ping is unreachable, or exceeds the timeout.

PingGram will ping the target once every 30 seconds when scheduled.

Timeout is set to 2 seconds, this means if the ping time exceeds 2 seconds, then web request sent.

PingGram was made with Telegram Messenger in mind but any working web request url will work. Telegram is free and available on all major platforms https://telegram.org

If using with Telegram, then the app TeleFormer can help form the Telegram web request. Get info about TeleFormer here https://github.com/KaiKai7/TeleFormer
