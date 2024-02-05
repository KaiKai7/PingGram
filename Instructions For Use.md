![pinggram logo resized](https://github.com/KaiKai7/PingGram/assets/87836320/9e4a3264-2c62-4449-ac6b-ba43e15a546f)

# PingGram Instructions For Use

Use PingGram to monitor an ip address on your network, when the ip address becomes unreachable or exceeds the limit, a web request of your choice can be sent. You also have control over the message, and determine what it will say.

PingGram can be used on its own with any http web request you may already have, including Telegram.

Enter an ip address to ping, then press the "Start" button. A toast will show if the target is unreachable or the ping exceeds 1.5 seconds.

When entering the ip address, it is not necessary to type http:// or https:// before the ip address. Simply enter the ip address, for example like this, 192.168.1.1

Web requests are sent when the ping time exceeds 1.5 seconds or when the ping is unreachable, but only if the "Start" button is pressed to start scheduling.

Enter your web request in the "Enter IP Address" field, then press the 'Start" button to begin scheduled pings. This field is unlike the ip address field and you do need to include http:// or https:// to your request.

Scheduled pings run at 30 second intervals, this was chosen as a balance between realtime reporting, and not ssending too many alerts. Be aware of potential data charges if PingGram is left to run unattended. Because PingGram will continue to send alerts every 30 seconds if the ping fails or is unreachable, you must stop PingGram manually. Understand this if you leave the device that is running the PingGram app.

## TeleFormer
I have also created the TeleFormer app, TeleFormer can automatically format the Telegram web request URL. 

Spaces and new lines require special formatting and can be a pain to form, but just type your message and TeleFormer with format the web request. 

Format message spaces,new lines and even optionally append a silent attribute with a click to the Telegram web request URL.

You type the message you want and TeleFormer will format it.

Emoji's are accepted and can be used.

TeleFormer is available at the Google Play App Store

https://play.google.com/store/apps/details?id=com.ping.it.utility.teleformer.free&pcampaignid=web_share

## Android Restrictions

Running apps in the background are subject to Android policies and future code updates may break that functionality, so this app has been coded to run with the screen open to avoid any future issues.

Of course, running with the screen open does present new issues. One of which is that Android will only allow the screen to stay open for 30 minutes before closing. Another way to keep the screen open, is the "Stay awake" toggle in Developer Options. This allows the phone screen to stay open when charging. Charging is something that should be done if the screen is open and the ping is running every 30 seconds anyway.

But if you have not already enabled Developer Options, you will first have to perform the Google "Open Sesame" (it's not really called that) command and enable the option. To do this follow these steps, and it is really not that hard at all to do.
### Developer Options
* Go to Setttings
* Select "About phone"
* Scroll down to "Build number" and tap "Build number" seven times. And then you should see a toast saying unlocked or something similiar.
* Then go back one screen to "Settings".
* Select "System"
* Scroll down to "Developer options", nice !
* Scroll to "Stay awake" and toggle

Now that you performed the Google "Open Sesame" and have Developer Options, you dont have to do that again to expose it. So if you choose to turn off the stay awake feature, it is easy. You can also undo the developer options by tapping "Build Number" 7 times again.

### Screen Brightness
Next is the screen brightness, you may want to turn this down when the app is running especially at night. The ability to control the brightness from the onscreen slider requires permission, you may be prompted to allow this permission. If you choose not to, you can simply use the brightness slider in the settings section of your device.

You are now ready to be alerted to devices on your network that are not responding, or are taking too long to communicate. 


