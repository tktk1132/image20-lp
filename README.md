# image20-lp

うたりお夫婦の無料チェックリスト登録用ランディングページです。HTML/CSSのみで作成しているため、GitHub Pagesでそのまま公開できます。

## 公開ファイル

- `index.html`：LP本文とセクション構成
- `style.css`：デザイン、余白、レスポンシブ調整
- `assets/reference_fv.png.png`：ファーストビュー参考画像
- `assets/assets/couple_profile.png`：プロフィール・ファーストビューで使用している夫婦画像

## GitHub Pagesで公開する方法

1. GitHubのリポジトリ画面で **Settings** を開く
2. 左メニューの **Pages** を開く
3. **Build and deployment** の Source を **Deploy from a branch** にする
4. Branch を公開したいブランチ、フォルダを `/ (root)` にして保存
5. 表示されたURLにアクセスすると `index.html` が公開されます

## 編集のコツ

- 文章を変更したい場合は `index.html` の該当セクションを編集してください。
- 色や余白を変えたい場合は `style.css` 冒頭の `:root` にある変数を編集すると全体に反映されます。
- JavaScriptや外部フレームワークは使っていません。
