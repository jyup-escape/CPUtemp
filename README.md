# CPUtemp
CPUの温度を取得し10秒ごとに埋め込みを編集しサーバー状態をチェックできます
# 注意ドキュメントスキッパーは許しませんよくドキュメントを読んでください!
## もし温度が取得できない等のエラーが出た場合
### If an error occurs such as not being able to obtain the temperature
```
sudo apt update
sudo apt install lm-sensors
sudo sensors-detect
sensors
```
以下のコマンドを入力してください上から3つ目のコマンドは全てyで大丈夫です
Windows勢は知りませんググってください
