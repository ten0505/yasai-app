# 家庭菜園管理アプリ

野菜の栽培スケジュール・作業記録・収穫記録を管理する単一HTMLアプリ。

- 公開URL: https://ten0505.github.io/yasai-app/
- タイムライン（野菜×日付）／野菜ごとの詳細（栽培情報・作業記録・収穫記録）
- 写真: アプリ内で追加（圧縮してFirebaseに保存・端末間で同期）
- Google Photos共有リンクを作業記録に添付可能
- データ同期: Firebase Realtime Database（設定タブで同期キーを入力）
- バックアップ: 設定タブからJSONエクスポート／インポート

## 更新方法

`index.html` を編集して push すると GitHub Pages に反映される（数分かかる）。
