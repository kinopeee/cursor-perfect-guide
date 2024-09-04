# 📕 第3章 Cursor の機能説明

原稿を書き上げた後の変更点について補足説明します。

## 📘「Docs参照」

カスタム Docs のリスト内にインデックスされた日付、時刻が表示されるようになりました。
ギアアイコンをクリックすると、設定画面の「Features」タブ内でカスタム Docs の設定が表示されます（設定画面でインデックスを更新することができます）。
![](../images/docs_on_chtat.png)

## 📘「Lint error参照」

0.34.2以降、@Lint error は表示されなくなっています。この現象については、公式フォーラム、公式リポジトリで不具合で修正を行なっていると説明されていますが、現在のところ変化は見られません。
https://forum.cursor.com/t/is-lint-errors-gone-in-0-34-2/5427
https://github.com/getcursor/cursor/issues/1470

## 📘「Apply」、「Copy」、 「Reply」ボタン

0.40 でボタンの並び順が変更になっています。また、「Reply」ボタンは「Ask」ボタンにラベルが変更になっています。機能的には変更ありません。

![](../images/ask_button.png)

## 📘 /edit コマンド

/edit コマンドは 0.40 で廃止になった模様です。
現在は新しいコマンドが追加され、CHAT、Composer のプロンプト入力欄で / 記号を入力すると、「Reset」、「Reference Open Editers」コマンドが表示されます。
![](../images/edit_command.png)

- 「Reset」コマンド：その CHAT、Composer のセッション情報がリセットされます（空の CHAT、Composer になります）。
- 「Reference Open Editers」コマンド：エディターで開いているファイルがまとめて、ファイルピッカーで選択される操作になります。