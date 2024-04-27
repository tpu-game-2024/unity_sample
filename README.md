# unity_sample
GitHubでのUnityプロジェクトのフォルダ構成の一例

# ポイント
- srcというディレクトリを掘って、Unityのプロジェクトのルートにする
  - ディレクトリを作らなくても良いが、ドキュメントなどの別のファイルが入ることを考えると別にするのが良い
- .gitignoreをUnityのプロジェクトのルート(src)に置く

# 作り方
- GihHubでプロジェクトを作る
  - .gitignoreはUnityを指定する
- ローカルにclone
- クローンしたフォルダにUnityのプロジェクトを作る
- Unityのディレクトリ名をsrcに変える
- .gitignoreをsrcに移動する
- pushして更新する
