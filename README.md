# コエウチ

打った文字を自分の声でしゃべるWebアプリ(PWA)。

- `index.html` … アプリ本体(この1ファイルをブラウザで開けば動きます)
- `manifest.webmanifest` / `sw.js` / `icon.svg` … ホーム画面に追加・オフライン用
- `app.html` … claude.ai のアーティファクト公開用(中身は同じ)

## スマホで使うには
HTTPS のサーバーに置く必要があります(マイクがHTTPSでないと使えないため)。
GitHub Pages に置く場合: リポジトリにこのフォルダの中身を入れ、Settings → Pages で main ブランチを公開。
公開したURLをスマホで開き、共有メニューから「ホーム画面に追加」するとアプリのように使えます。
