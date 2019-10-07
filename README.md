# 2019年度「プロジェクト演習A」
## 課題プロジェクト(1)

このリポジトリ（スターターキット）にすでにあるファイルは，課題プロジェクト(1)のひな型ファイルです．

### clone方法
- 自分の作業ファイルを開いた上で、コマンドプロンプトにおいて``git clone https://github.com/Infosys-ProjectA-2019/proa2019-project1-5101_c``を実行する。

### push方法
``git add``を行い、``git commit -m "コミット名"``(例：[FIX]画像が表示されない問題を修正する。/[UPDATE]新しくBootStrapを読み込む/[ADD]施設を追加する),そして``git push https://github.com/Infosys-ProjectA-2019/proa2019-project1-5101_c``

### ファイルの一覧
- README.md：このファイル
- .gitignore：Gitの管理対象外のファイルやフォルダを指定（今回の初期設定ではphotosフォルダを除外）
- detail_example.html：紹介施設のページのテンプレート（→別名でファイルを保存して，各施設の紹介ページを作成）
- data.json：紹介対象の施設などのデータを記入するJSON形式のファイル（要編集）
- js/フォルダ
  - js/readJSON.js：各チームで作成したデータファイルをページに書き込むJavaScriptプログラム（要編集）
- css/フォルダ
  - css/ProA_style.css：各チームで装飾を行うCSSファイル（要編集）
  - css/star-rating.css：評価（☆の数）を表示するためのCSSファイル（編集不要）

### ファイルの編集方法
- 1コミットあたりの編集量は最小限に抑えることが望ましいです。
- コミットの名称の頭は英単語で始めると後にRevertする際にやりやすくなるのでおススメです
