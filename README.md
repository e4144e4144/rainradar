# 雨雲レーダー PWA

## 配布手順（GitHub Pages を使う場合・無料）

1. [github.com](https://github.com) で無料アカウントを作成
2. 「New repository」でリポジトリを作成（名前例：`rainradar`）
3. このフォルダの全ファイルをアップロード：
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/icon-192.png`
   - `icons/icon-512.png`
4. Settings → Pages → Source: `main` ブランチを選択
5. 数分後に `https://あなたのユーザー名.github.io/rainradar/` でアクセス可能に

## 知り合いへの配り方

URLを LINE や SMS で送るだけ！

受け取った人は Chrome で開いて
**「ホーム画面に追加」** すれば、アプリとして使えます。

## 機能

- 📍 現在地取得（タップ1つ）
- 🌧️ リアルタイム雨雲レーダー（RainViewer API）
- ⏮️ 過去〜予測の時系列アニメーション
- 🔔 雨雲接近アラート（Open-Meteo API）
- 🗺️ レイヤー切替（雨雲 / 風 / 気温）
- 📱 PWA対応（ホーム画面アイコン・オフライン動作）
