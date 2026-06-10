# smashkeys-pages

**SmashKeys** — 幼児向けアルファベット学習タイピングゲーム — の WebGL デモを GitHub Pages で配信するリポジトリ。

- ▶ Play: https://kitochio.github.io/smashkeys-pages/play/
- 実装本体: https://github.com/kitochio/ABC_Game

## 構成

- `index.html` … ランディングページ
- `play/` … Unity WebGL ビルド一式（Brotli 圧縮、`decompressionFallback` 有効）

## デプロイ

`main` へ push すると GitHub Pages が自動配信する。デモの更新は ABC_Game 側で WebGL ビルドを作り、成果物を `play/` に上書きしてコミット & push する。
