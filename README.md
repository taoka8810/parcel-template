# LP 作成テンプレート

- ペライチの LP を作成するための開発環境

### 使用技術
- **Pug** + **Scss** + **JavaScript**(**TypeScript**も使用可能)
- ビルドツールは**Parcel**

## 環境構築

- Node v18

### 依存パッケージのインストール

```
yarn
```

### サーバーの起動

```
yarn start
```

### デプロイ時の build

```
yarn build
```

## ディレクトリ構成

### assets
- メディアファイルなどの静的ファイルを格納する
- 画像ファイル(`.jpg`, `.png`)は `images`の中に入れる
- SVGアイコンは `icons` の中に入れる

### components
- 再利用可能なコンポーネント(`.pug`)を格納する

### scripts
- スクリプト(`.js`, `.ts`)を格納する

### styles
- スタイル(`.css`, `.scss`)を格納する
- CSS設計はプロジェクトに合わせて構築してください

### index.pug
- エントリポイント

