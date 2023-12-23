![pinggram logo resized](https://github.com/KaiKai7/PingGram/assets/87836320/506f5897-8c2c-4373-9a37-9857651bd1c9)
# PingGram
Simple ping utility that can ping an ip address, and optionally run a scheduled ping.

PingGram will also optionally send a web request when a scheduled ping is unreachable, or exceeds the timeout.

PingGram will ping the target once every 30 seconds when scheduled.

Timeout is set to 2 seconds, this means if the ping time exceeds 2 seconds, then web request sent.

PingGram was made with Telegram Messenger in mind but any working web request url will work. Telegram is free and available on all major platforms https://telegram.org

If using with Telegram, then the app TeleFormer can help form the Telegram web request. Get info about TeleFormer here https://github.com/KaiKai7/TeleFormer

PingGram was made to be simple, that is why the interval and timeout of the ping tests are fixed and not user changeable.

No special permissions are required to run and PingGram does not save or use your information in any way. Web requests are made in the app using http, and the help pages are hosted on github.
