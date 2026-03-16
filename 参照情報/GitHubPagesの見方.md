# GitHub Pages で図解を公開してリンクで見る

## 初回だけ（1回だけやればOK）

1. このリポジトリを GitHub に push する（まだなら）。
2. GitHub のリポジトリ画面で **Settings** → 左メニュー **Pages** を開く。
3. **Build and deployment** の **Source** で **「Deploy from a branch」** を選ぶ。
4. **Branch** で `main`、**Folder** で `/ (root)` を選び **Save**。
5. 数分後、`main` に push するたびに自動で GitHub Pages が更新される（workflow 不要）。

## 図解のリンク（公開後のURL）

- リポジトリ名が `gijiroku` で、GitHub のユーザー名が `komatsu-matsuko` の場合：
  - **図解ページ**  
    `https://komatsu-matsuko.github.io/gijiroku/参照情報/役員_求められること_図解.html`
- 初回は反映に数分かかることがあります。Settings → Pages の **「Your site is live at …」** の URL がサイトのトップです。そのあとに `/参照情報/役員_求められること_図解.html` をつけると図解のURLになります。
