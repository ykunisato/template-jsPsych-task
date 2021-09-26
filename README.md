本リポジトリには，jsPsychで行動課題・質問紙を作成する際に使用する最小限のファイル・フォルダを用意しています。こちらのリポジトリをimportして各自活用ください。

もしくは，Rを利用されている場合は，jsPsychRmdパッケージをインストールすれば，課題を作成したいフォルダに移動して，jsPsychRmd::set_cbat("課題名")で自動的にファイルとフォルダを用意できます。

```
# 最新版をインストールしていなければ以下を実行
# remotes::install_github("ykunisato/jsPsychRmd")
jsPsychRmd::set_cbat("stroop")
```