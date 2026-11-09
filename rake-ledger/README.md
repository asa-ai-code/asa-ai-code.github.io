# バドゥーギ卓 レーキ台帳

https://badugi-3fc3a.web.app/ で公開している台帳ページのソースです。
データは Firebase Realtime Database（`ledger`）に保存されます。

## 反映のしかた

このフォルダで次を実行します。

```
firebase deploy --only hosting
```

初回は `npm install -g firebase-tools` と `firebase login` が必要です。
