# hidemaru_ahk
[WIP] 秀丸エディタで AutoHotkey を書くための設定たち。

![hidemaru_ahk_image](https://user-images.githubusercontent.com/23325839/40694681-9a0fd71a-63f8-11e8-8da0-a23fff969951.jpg)

## 同梱物
- [ahk.txt](ahk.txt) …… 辞書ファイル
- [ahk.hilight](ahk.hilight) …… 強調表示・アウトライン表示

## How to apply

### (1) AHK 用の「ファイルタイプ別の設定」をつくる
- その他 > ファイルタイプ別の設定 を開く
- 設定のリストボタン
- 適当な設定のコピーを作成し、名前を適当に(例: AHK)に変更

### (2) 辞書ファイルについて
- ファイルタイプ別の設定を開く
- その他 > 単語補完 > 単語補完の検索対象 > 辞書ファイル にチェックボックスを入れ、辞書ファイルを指定
- 同上詳細ボタン
  - 種類は「行単位」

### (3) 強調表示ファイルについて
- ファイルタイプ別の設定を開く
- デザイン > 強調表示 > 読み込みボタン
- 「全てオン」ボタンで全てチェックを入れた後、参照ボタンで hilight ファイルを読み込む

## ahk.txt
Version 1.28.0.2 のヘルプからキーワードを抜き出して作成。たぶん余計なキーワードがちらほら混ざってる（例: `buffering` ）

### Q: Wiki の辞書ファイルは？
Ans: 古いから使ってない。

[開発環境の構築 - AutoHotkey Wiki](http://ahkwiki.net/Tools) にて Ahk_Hidemaru.zip が公開されてるが、2013 年と古い。たとえば class など最近のキーワードが網羅されてない。

## ahk.hilight
- コメントのカラー表示
- 関数、クラス、ラベルのアウトライン表示
- キーワードのカラー表示

## License
[MIT License](LICENSE)

## Author
[stakiran](https://github.com/stakiran)
