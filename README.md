# 0120' Learning OS — GitHub Pages

Version: 2.9.0

## 公開
Settings → Pages → Deploy from a branch → main / (root) → Save。

## 更新
`index.html`、`version.json`、`sw.js`を更新。`version.json`の`version`と`sw.js`の`CACHE`識別子を毎回変更してください。`index.html`内の`const current`と画面のバージョン表記も合わせて更新。

既存のlocalStorageデータを消さないようにし、更新前にJSONバックアップを取ってください。URL（リポジトリ名）を変更すると端末内保存データは自動移行されません。
