# LINE Bot sample

https://developers.line.biz/ja/docs/messaging-api/nodejs-sample/#routing-config

## Run bot

```sh
git clone https://github.com/tsubakimoto/linebot-with-yarp
cd linebot-with-yarp/linebot
npm install
DEBUG=express:* LINE_ACCESS_TOKEN={your-line-channel-access-token} node index.js
```

## Run yarp

1. Open *yarp.sln* with Visual Studio 2022
2. [Create dev tunnel](https://learn.microsoft.com/ja-jp/connectors/custom-connectors/port-tunneling)
3. Run project
