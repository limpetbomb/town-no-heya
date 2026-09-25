# たうんのへや

えいどたうんとじゅりたうんが暮らす、3Dのお部屋です。

それぞれが歩き回り、ソファでくつろぎ、冷蔵庫から飲み物を取って飲みます。あかりや視点を切り替えて、写真をPNGで保存できます。

## GitHub Pages

ビルド不要の静的サイトです。リポジトリの **Settings → Pages** で、**Deploy from a branch → main → / (root)** を選択して保存します。

HTML、JavaScript、モデルは相対パスで読み込むので、リポジトリ名を含むGitHub PagesのURLでも動作します。`.nojekyll`はそのまま残してください。

## ローカルで確認

このフォルダで `python3 -m http.server 8000` を実行し、ブラウザで `http://localhost:8000` を開きます。HTMLファイルの直接オープンではなく、HTTPサーバーを使用してください。

## モデル

- エイド：白い口元を顔に沿って平らにしたv13。
- じゅり：julitown v2。

GLBはサイトの表示に必要な配布ファイルです。編集用Blenderファイルはこのリポジトリには含みません。

## ライブラリ

Three.js r170（MIT）。ライセンス全文は `vendor/LICENSE-three.txt` にあります。
キャラクター、モデル、その他の独自コンテンツにThree.jsのライセンスは適用されません。

[GitHub Pages公式ドキュメント](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
