# ellie プロフィールページ

## 開き方
`index.html` をダブルクリックするとブラウザで開きます。すでに開いている場合は Ctrl + R で再読み込みしてください。インストールやインターネット接続は不要です。

## 文章を変える
`index.html` をメモ帳やVS Codeで開き、タグの間の文章を編集して保存してください。
- 自己紹介：`id="about"` のセクション
- 活動内容：`id="activities"` のセクション
- 得意なこと：`id="strengths"` のセクション
- SNS：`id="social"` のセクション

活動内容と得意なことには、ellieさんからいただいた文章を反映しています。ページ冒頭のキャッチコピーと自己紹介文は、引き続き編集用のサンプルです。

## SNSのURLを設定する
今回は練習用のため、SNSのURLは設定していません。現在のSNSは準備中で、クリックできません。後から追加する際は、使うSNSの `span class="social-link pending"` の行全体を次の形に変更してください。URLはご自身のプロフィールURLに置き換えます。

```html
<a class="social-link" href="https://www.instagram.com/ご自身のユーザー名/">Instagram <span aria-hidden="true">↗</span></a>
```

同じ方法でXやnoteを設定できます。使わないSNSは行ごと削除してください。設定後は「SNSリンクは準備中です。」も変更または削除します。

## 色を変える
`style.css` 冒頭の `:root` が配色設定です。
- `--background`：ページ背景
- `--text`：本文の文字
- `--muted`：補足の文字
- `--accent`：アクセント色
- `--dark`：SNS欄の背景
- `--light`：SNS欄の文字

文字と背景のコントラストを保つと読みやすくなります。HTMLとCSSは同じフォルダーに置いてください。
