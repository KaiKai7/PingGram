# PingGram
Simple ping utility that can ping an ip address, and optionally run a scheduled ping.

PingGram will also optionally sned a web request when a scheduled ping is unreachable, or exceeds the timeout.

PingGram will ping the target once every 30 seconds when scheduled.

Timeout is set to 2 seconds, this means if the ping time exceeds 2 seconds, then web request sent.

PingGram was made with Telegram Messenger in mind but any working web request url will work.
