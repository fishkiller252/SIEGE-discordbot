# SIEGEのDiscordボット

year3新オペレーター追加
- Lion
- Frank
```
$ gem install discord
```
Bundlerでインストール

Gemfileを下記のようにgem "discordrb"を追記
```
# frozen_string_literal: true
source "https://rubygems.org"


# gem "rails"
gem "discordrb"
```
```
$ bundle install
```

[ここ](https://discordapp.com/developers/applications/me)でDiscordのbotを作成してクライアントIDとトークンを取得してください。

```
bundle exec ruby ping
```
```
bundle exec ruby discord_bot.rb
```

詳しい説明はQiitaを見てください。    
[rubyで簡単discordbot](https://qiita.com/fishkiller/items/3e036ad7ef1cb0c716e1)   
[discordbot(Ruby)でGoogleSpreadSheetの内容を呼び出し](https://qiita.com/fishkiller/items/5e89bd04df81034a91ee)   
[GoogleSpreadSheetからdiscordにpost](GoogleSpreadSheetからdiscordにpost)   
