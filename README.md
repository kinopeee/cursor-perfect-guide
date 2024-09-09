# 「AIエディタCursor完全ガイド」 サポート

## 📕 このGitHubリポジトリについて

書籍「AIエディタCursor完全ガイド」 について下記のサポートを行うリポジトリです。

- 書籍に掲載されているハンズオン用コード、生成されたサンプルコード、プロンプトの公開。
- 原稿を書き上げた後の Cursor のアップデートによる変更点の補足説明。

まだお持ちでない方は、ぜひお買い求めください！

[![AIエディタCursor完全ガイド](images/cover_cursor_boook.jpg)](https://amzn.to/4c2tjdt)

## 🌟 アップデート情報 🌟

- 2024/9/4 書籍発売日に備えた初版リリース。
- 2024/9/5 「第6章 Cursor開発テクニック」 Composer Projects の説明を追加。
- 2024/9/6 「第4章 Cursorのカスタマイズ設定」 Composer、Chatの設定事項を追記。「第3章 Cursorの機能説明」 参照情報の表示変更の説明を追加。正誤表更新。
- 2024/9/8 チャットモードのプルダウンが表示されない場合についての対策と説明を追記。
- 2024/9/9 「第5章 プロンプト・プログラミング実践例」掲載データを追加。

## 📕 このリポジトリの構成

各章のハンズオン用コード、サンプルコード、プロンプトなどは章ごとにまとめてあります。各章のリンクから該当章に移動して、内容をご覧ください。

### 📘 第1章 Cursor の導入

#### 📗 Cursor の概要（P2）

本書内では OpenAI などからの Anysphere 社への出資の紹介をしていますが、2024年8月22日に、Stripe、Github、Ramp、Perplexity、OpenAI の創設者などから、さらに6000万ドル（約88億円）の出資があったことが公式にアナウンスされました。心強いニュースですね。
- [We Raised $60M](https://www.cursor.com/blog/series-a)

#### 📗 Cursorの料金体系（P3）

- 「高速 GTP-4」という呼び方から「高速プレミアムモデル」に変更になっています。
- 「高速プレミアムモデル」には下記モデルが含まれます。
    1. GPT-4
    2. GPT-4o
    3. Claude 3.5 Sonnet
- [料金ページ](https://www.cursor.com/pricing)には記載されていませんが、GPT-4o mini は料金体系上 cursor-small と同じ扱い（Pro 以上は回数制限なし）になっています（コストパフォーマンスが良いので、活用の価値が高い）。

### 📘 第2章 Cursor の基本操作

[🔗 プロンプト](chapter2/PROMPT.md)

[🔗 「cursor-tutor」リポジトリ](https://github.com/kinopeee/cursor-tutor/)

- 2024年6月以前に Cursor をインストールされた方は、書籍の手順通りで操作を進めていただくことができます。
- ローカルに「.cursor-tutor」フォルダがない場合は、「cursor-tutor」リポジトリをダウンロードしてご利用ください。

### 📘 第3章 Cursor の基本操作

[🔗 補足説明](chapter3/README.md)

### 📘 第4章 Cursorのカスタマイズ設定

[🔗 補足説明](chapter4/README.md)

### 📘 第5章 プロンプト・プログラミング実践例

[🔗 補足説明 / サンプルコード](chapter5/README.md)

[🔗 プロンプト](chapter5/PROMPT.md)

### 📘 第6章 Cursor開発テクニック

[🔗 補足説明](chapter6/README.md)

## 📕 誤植などのお知らせ

こちらの[正誤表](errata.md)を随時更新します。

## 📕 エラー等を見つけた際は

本リポジトリの [Issues](https://github.com/kinopeee/cursor-perfect-guide/issues) にご報告ください。ベストエフォートで対応いたします。
