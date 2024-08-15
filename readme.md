# Second Organization Repo

ローカルでリポジトリを作成してpushできるかのテスト。

どうやら下記の手順で作成すればいい様子。

1. ローカルで作成してからGithubのOrganizationに空のリポジトリを作成。
    - たぶんローカルのフォルダ名とGithub上のリポジトリ名は同一でなくてもOK
1. Github上で `https://github.com/（Organization名）/（リポジトリ名）.git` のURLをコピー
1. ローカルのVSCodeでコマンドパレットから `Git Add Remote` を選択して上記のURLを貼り付ける
1. リモート名を求められるので適当につける
    - 後から変更可能だし
