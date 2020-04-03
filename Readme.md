# 要旨
Microsoftさんのvscode-try-python-sampleの一部を拝借して自リポジトリで再現。
ローカルに移してVSCodeのOpen Folder in Containerでは動かないのは本当に謎。
リポジトリ経由からならちゃんとWSL2上でコンテナを作ることができる。こっちを使おう。

# 使い方
要:
- Docker Desktop
- VSCode

Remote-Container拡張機能を使ってOpen Repository in Containerでリポジトリ名を打つ。

```
python -m flask run --port 9000 --no-debugger --no-reload
```

http://localhost:9000 にサーバが立ってる。めでたしめでたし
