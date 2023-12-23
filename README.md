![pinggram logo resized](https://github.com/KaiKai7/PingGram/assets/87836320/506f5897-8c2c-4373-9a37-9857651bd1c9)
# PingGram
Simple ping utility that can ping an ip address, and optionally run a scheduled ping.

PingGram will also optionally send a web request when a scheduled ping is unreachable, or exceeds the timeout.

PingGram will ping the target once every 30 seconds when scheduled.

Timeout is set to 2 seconds, this means if the ping time exceeds 2 seconds, then web request sent.

PingGram was made with Telegram messager in mind but any working web request url will work. Telegram is free and available on all major platforms https://telegram.org

If using with Telegram, then the app TeleFormer can help form the Telegram web request. Get info about TeleFormer here https://github.com/KaiKai7/TeleFormer

PingGram was made to be simple, that is why the interval and timeout of the ping tests are fixed and not user changeable. If the scheduled ping is unreachable or greater then the set timeout of 2 seconds, a web request is sent. 2 seconds was chosen because it gives some leeway in network congestion, but any device reporting over 2 second ping results most likely has issues and should be checked.

30 second intervals between ping tests was chosen to be able to timely report if a network issue has occurred, such as a jamming attack. Installing PingGram on a cellular device can use cell service when wifi is down to send the web request. Setting the interval any longer and the jamming attack or wifi outage would not be realized immediately. Setting the interval any shorter would only use more network resources when not really neccesary in most scenario's.

No special permissions are required to run and PingGram does not save or use your information in any way. Web requests are made in the app using http, and the help pages are hosted on github.
