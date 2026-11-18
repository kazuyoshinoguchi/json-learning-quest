# JSON Quest — ロボット基地のデータ管理

ブラウザで動く、全10ステージの日本語JSON学習ゲームです。HTML/CSS/JavaScriptのみで動作し、外部ライブラリは不要です。

## 遊び方
1. `index.html` をブラウザで開く。
2. ステージの指示に従ってJSONを編集する。
3. 「実行・判定」で正解を確認する。ヒントと初期化も利用可能。
4. クリア状況と入力途中の内容はブラウザのlocalStorageに保存されます（端末・ブラウザごと）。

## GitHub Pagesへの公開方法
1. GitHubで新しいPublicリポジトリ `json-quest` を作成。
2. このフォルダの `index.html` と `README.md` をリポジトリの最上位にアップロード（GitHub Desktopでも可）。
3. GitHubのリポジトリで **Settings → Pages → Build and deployment** に移動。
4. **Source: Deploy from a branch**、**Branch: main**、**Folder: / (root)** を選択し、Save。
5. 公開後、`https://あなたのユーザー名.github.io/json-quest/` にアクセス。

※ URLはユーザー名やリポジトリ名によって変わります。GitHub Pagesの設定画面に表示されるURLを確認してください。

## ファイル構成
- `index.html` — ゲーム本体（CSSとJavaScriptを内包）
- `README.md` — 説明と公開手順

## 学習範囲
文字列、数値、真偽値、複数プロパティ、配列、入れ子、オブジェクト配列、null、JSON.parse、総合演習。
