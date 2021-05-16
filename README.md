## ローカル開発環境からcloud sqlに接続する
cloud sql proxyを使う
```
curl -o cloud_sql_proxy https://dl.google.com/cloudsql/cloud_sql_proxy.darwin.amd64
chmod +x cloud_sql_proxy
```

でプロキシクライアントを入れる＆実行権限付与

参考：https://cloud.google.com/sql/docs/mysql/connect-external-app?hl=JA#dotnet