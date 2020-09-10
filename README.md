### readme 呈現 code 使用狀況
------

1. 引用 https://github.com/WEGFan/codestats-profile-readme#deploy-on-your-own-server

2. 申請至Heroku並得到 heroku網址

3. 申請codestats 並得到 username

4. 更改 run.py --> app.run(host='0.0.0.0',port=int(os.environ.get("PORT",88)))

5. 將程式部屬上Heroku

6. 將以下程式放入readme，並修改 { heroku IP } ，{ codestats username }

```
<a href="https://codestats.net/users/nativeone">
<img src='{heroku IP}/history-graph/{codestats username}?width=850&height=300&timezone=08:00&history_days=21&max_languages=9&language_colors=["3e4053","f15854","5da5da","faa43a","60bd68","f17cb0","b2912f","decf3f","b276b2","808080"]' alt="{codestats username}'s Code::Stats history graph" />
</a>
```

7. github readme 觀察程式使用結果
