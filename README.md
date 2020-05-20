# Tasker-Config

Some Tasker scripts that works with github, telegram, google voice, etc.

## TOC

> For all the Telegram related xml, replace `YOUR-CHAT-ID` and `YOUR-BOT-TOKEN` accordingly  
> You may safely remove any tts related stuff, they are just for sound notification that I know tasker is working.

- [Receive Message and send to github issue](./message-github-issue.xml)
  - Replace `YOUR-REPO` and `YOUR-ACCESS-TOKEN` accordingly
- [Auto Reply Message on Google Voice](./Google_Voice_Auto_Reply.prf.xml)
  - Data Source: "Download/sao.txt", downloaded from <https://gist.github.com/NeverBehave/606d7e14436187b4d45e8657fafd40ab>
  - Random choose one from the file, you may define your own behavior
  - **Read Related Blog #2 for more details**
- [Received Message and send with Telegram bot to given chat](./Message_Arrived.prf.xml)

- [Received phone call and send notification to Telegram](./Phone_Call_Arrived.prf.xml)
- [Telegram Notification when phone plugged in or unplug](./Charged.prf.xml)
- [Telegram Notification when Battery hot](./Battery_Hot.prf.xml)

## Related Blog

1. https://blog.never.pet/2019/02/08/tasker-messenger
2. https://blog.never.pet/2020/05/20/keep-your-google-voice-with-sao