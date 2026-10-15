# RIDDLE SURVIVAL

古代遺跡と地下神殿を舞台にした、PC ブラウザ向けのオリジナル 3D 謎解きアクションゲームです。現在は開発準備段階です。各機能の実装条件は [Issues](https://github.com/Hinu10/riddle-survival/issues) で管理します。

## 開発順

1. React / TypeScript / Vite / Three.js / React Three Fiber の土台、画面遷移、共通状態、クイズデータ
2. ミイラステージを開始から CLEAR / GAME OVER まで実装
3. 壁ステージのクイズ、鉄球、緊急脱出を実装
4. 床ステージの傾斜移動、クイズポイント、最終試練を実装
5. リザルト、保存、設定、UI、サウンド管理を仕上げる
6. Chrome で通しプレイし、`npm run build` と TypeScript を確認する

## 開発予定の操作

| キー | 操作 |
| --- | --- |
| W / ↑、S / ↓ | 前後移動 |
| A / ←、D / → | 左右移動 |
| Space | ジャンプ |
| E | ギミック操作 |
| Enter | テキスト回答の送信 |

ステージごとに必要な操作だけを有効にします。

## 技術スタック

React、TypeScript、Vite、Three.js、React Three Fiber、@react-three/drei。物理演算が必要な箇所は Rapier 系を検討します。

## 公開方針

GitHub Pages または Vercel に公開しやすい構成で開発します。実装後に `npm install`、`npm run dev`、`npm run build` の手順と公開方法を追記します。

本作はオリジナルのファンメイド・謎解きアクションゲームであり、既存テレビ番組・放送局とは関係ありません。既存作品の画像・映像・音声・ロゴ・問題文等は使用していません。
