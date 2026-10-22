# ラッキーフォーチューン

12星座の今日の運勢を楽しむ、紺とゴールドの静的サイトです。HTML・CSS・JavaScript・SVGだけで動き、外部ライブラリー、外部画像、APIキー、ビルド作業は不要です。

## GitHub Pagesで公開する

1. このフォルダーの内容をGitHubリポジトリーの `main` ブランチに配置します。`index.html` はリポジトリーの直下に置きます。
2. リポジトリーの **Settings → Pages → Build and deployment** を開きます。
3. **Source: Deploy from a branch**、**Branch: main**、**Folder: /(root)** を選び、**Save** を押します。
4. GitHubに表示される公開URLを開き、12星座の選択と結果表示を確認します。

別途用意された単一ファイル版 `lucky-fortune.html` を使う場合は、名前を `index.html` に変えて直下に置くこともできます。その場合、CSS・JavaScript・SVGはHTML内に含まれます。このパッケージは編集しやすい分割ファイル版です。

一般公開すると、サイトの内容は誰でも閲覧できます。公開リポジトリーではソースも閲覧できます。

## ファイル構成

```text
index.html
styles.css
app.js
.nojekyll
README.md
assets/
  favicon.svg
  zodiac-wheel.svg
```

## サイトの動作

- 星座を選ぶと、総合運・恋愛運・仕事運・金運、順位、ラッキーカラー・アイテム・ナンバーが表示されます。
- 日付（日本時間）と星座からブラウザー内で結果を生成します。同じ日・同じ星座の結果は同じです。
- 占いはエンターテインメントです。天体観測や実際の出来事の予測ではありません。
- 名前や生年月日の入力、外部への送信、アクセス解析はありません。
- JavaScriptを有効にして利用します。結果のコピーにはブラウザーのクリップボード許可が必要になる場合があります。
