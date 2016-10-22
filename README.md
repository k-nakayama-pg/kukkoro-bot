# kukkoro-bot

「くっころ」という言葉に反応して、「くっころ」してしまうBOTのソースコードです。

# クイックスタート（herokuにデプロイする場合）

```
git clone https://github.com/k-nakayama-pg/kukkoro-bot.git
git remote add heroku <Your_heroku_app_git_url>
heroku config:set LINE_CHANNEL_SECRET="<Your LINE_CHANNEL_SECRET>"
heroku config:set LINE_CHANNEL_ACCESS_TOKEN="<Your LINE_CHANNEL_ACCESS_TOKEN>"
git push heroku master
```
