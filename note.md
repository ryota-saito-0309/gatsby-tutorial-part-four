# データについて

## 新しいサンプルサイトを作成する

チュートリアルのこの部分用に別の新しいサイトを作成します。「Pandas Eating Lots」というMarkdownブログを作成します。たくさんの食べ物を食べるパンダの最高の写真やビデオを披露することに専念しています。途中で、GraphQLとGatsbyのMarkdownサポートにつま先を浸します。

新しいターミナルウィンドウを開き、次のコマンドを実行して、という名前のディレクトリに新しいGatsbyサイトを作成しますtutorial-part-four。次に、新しいディレクトリに移動します。

```sh
gatsby new tutorial-part-four https://github.com/gatsbyjs/gatsby-starter-hello-world
cd tutorial-part-four
```

次に、プロジェクトのルートに他の必要な依存関係をインストールします。タイポグラフィのテーマ「Kirkham」を使用して、CSS-in-JSライブラリ「Emotion」を試してみます。

```sh
npm install --save gatsby-plugin-typography typography react-typography typography-theme-kirkham gatsby-plugin-emotion @emotion/core
```

パート3で終了したのと同様のサイトをセットアップします。このサイトには、レイアウトコンポーネントと2つのページコンポーネントがあります。
