# Virtual YouTuber Database

====

## これはなに

元々[VirTracker](https://twitter.com/virtracker/)用に蓄積していたライバーの情報をまとめたJSONファイルです。
・名前
・ファンアート
・テーマカラー
・ツイッターのID(**screen_nameでない**)
・YouTubeのチャンネルID
・所属
で構成されています。

## 構成
```JSON
    "hogehoge": [
      {
          "name": "hogehoge",
          "fanArtTag": "#hogehoge",
          "color": "#FFFFFF",
          "twitterId": 0000000000000000,
          "ytChannel": "FugAfUga",
          "pruduction": "hogehogeLiver"
      }
  ]
```