# SIEGEのDiscordボット

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
