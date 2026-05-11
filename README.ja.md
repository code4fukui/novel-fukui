# novel-fukui

福井を舞台としたインタラクティブな歴史小説です。これらの物語はMarkdown形式で記述されており、ビジュアルノベルエンジン[egadv](https://github.com/code4fukui/egadv)を使用してウェブブラウザ上でプレイできるように設計されています。

## 小説一覧

### 紫式部の国府での一日 (A Day in the Life of Murasaki Shikibu)
紫式部が越前の公園を散策しながら、都からの旅路を回想し、未来の物語へのインスピレーションを見つける様子を描きます。この物語には地元の風景写真が組み込まれています。

- **[ブラウザでプレイ (egadv)](https://code4fukui.github.io/egadv/?url=https://code4fukui.github.io/novel-fukui/紫式部の国府での一日.md)**
- **[スクリプトを表示 (Markdown)](紫式部の国府での一日.md)**

### 越前市黄金伝説 (The Legend of Echizen City Gold)
歴史好きの中学生「めい」と、言葉を話す「コウノトリ」と一緒に、地元の歴史や伝説に基づいて越前市内に隠された黄金の遺物を探す宝探しに出かけましょう。

- **[ブラウザでプレイ (egadv)](https://code4fukui.github.io/egadv/?url=https://code4fukui.github.io/novel-fukui/越前市黄金伝説.md)**
- **[スクリプトを表示 (Markdown)](越前市黄金伝説.md)**

## 仕組み
このプロジェクトでは、アドベンチャーゲームやビジュアルノベルを作成するためのシンプルなエンジン[egadv](https://github.com/code4fukui/egadv)を使用しています。
- **Markdownベース:** 各物語は単一のMarkdownファイルで構成されています。
- **分岐するストーリー:** `## Scene Title` で新しいシーンを作成し、`[Choice Text](#Scene-Title)` でプレイヤーの選択肢を作成します。
- **簡単な作成:** 基本的なMarkdownの知識があれば、誰でも独自のインタラクティブな物語を作成できます。
