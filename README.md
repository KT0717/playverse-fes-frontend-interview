# PLAYVERSE FES 2026 フロントエンド実装課題

架空のゲームイベントサイトを想定し、完成見本を参考にヘッダーとファーストビューを実装してください。

## 課題について

- 制限時間は約60分です。
- HTML / SCSSを中心に実装してください。
- PCとSPの両方に対応してください。
- PCは1440px幅、SPは375px幅を基準にしてください。
- 画面幅768px以下でSPデザインへ切り替えてください。
- 完成見本は`reference/`にあります。
- 分割素材は`public/assets/`にあります。
- 完成させること自体が目的ではありません。
- 1px単位の完全再現は求めません。
- 分からないことは自由に質問してください。
- 面接官と相談しながら進めて構いません。
- インターネット検索と、普段使用しているエディタを利用できます。
- AIを利用したい場合は、面接官に確認してください。

## セットアップ

Node.js 22を使用します。

```sh
npm ci
npm run dev
```

ブラウザに表示されたURLを開いて実装を始めてください。

ビルド確認は次のコマンドで行えます。

```sh
npm run build
```

## 主な実装場所

- HTML：`src/pages/index.astro`
- 共通スタイル：`src/styles/global.scss`
- ヒーロー：`src/styles/hero.scss`

Sassの変数、ネスト、mixinなどを使うかどうかは自由です。JavaScriptの高度な実装は必要ありません。

## 完成見本

- PC：`reference/reference_pc.png`
- SP：`reference/reference_sp.png`

## 素材

- `bg_pc.svg` / `bg_sp.svg`：背景
- `character_hina.png` / `character_ren.png`：キャラクター
- `header_logo.svg`：ヘッダー用ロゴ
- `logo.svg`：イベントロゴ
- `decoration_shapes.svg`：装飾

必要な素材を選び、HTMLとSCSSでレイアウトしてください。完成見本をそのまま背景画像として使用しないでください。

