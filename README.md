# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- リモートリポジトリ:ネット上に配置して複数人で共有するためのリポジトリ。(個人開発用にも使用可能)。

- ローカルリポジトリ:開発者一人ひとりが使用するために自分のPC上に配置するためのリポジトリ。

## プッシュとマージの違いは何でしょうか？
- プッシュ：ローカルリポジトリからリモートリポジトリへ反映させる事。

- マージ：修正前から修正後へブランチを反映させる

## コミットとプッシュの違い
- コミット：追加・変更したファイルを一つのフォルダにまとめて名前をつけてローカルリポジトリに保存する事。

- プッシュ：ローカルからリモートに反映させる事。


## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- ’change:〜〜を変更’のように先に変更、削除などした英単語を書きその後に変更した部分を記入する事。
- プレフィックスとは：接頭辞の事

- プレフィックス例）
　1. change（仕様変更による修正）
　2. clean （整理）
　3. rename （ファイルの変更）

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- ローカルでマージ：コードレビューをせず対象ブランチに反映されるため、コードにバグがあっても気づかない可能性がある。


- プルリクエストでマージ：バグや欠陥があってもプルリクエストすることによってmainブランチに反映する前に気づくことができる。また、他の人が見ることによって違うバグなど見つけやすい。


## コンフリクトを起こしてしまった場合、どう対処すべきですか？
1. 上司に相談、報告、連絡する
1. コンフリクトしてしまった相手と上司に変更内容などの確認をする
1. 先にマージされた変更内容を取り込む
1. 後にマージしようとしている変更内容を取り込む
1. どちらの変更内容も取り込む

