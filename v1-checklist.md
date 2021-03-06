#  v1チェックリスト


### 1. プロトサイト＆環境構築
- [x] テーマ
- [x] プロト作成
- [x] プレビュー連携
- [x] Forestry連携だけ
- [x] ページ、セクション調整
- [x] Action, カスタムDNSの事前調査
- [x] SEO、OGP の出力テスト

### 2. メンバータスク
- イラスト
- [ ] アサイン
- [ ] 投票
- 翻訳
- [ ] アサイン
- [ ] 投票
- アセット
- [x] アサイン
- [x] アイコン類をチェック
- [x] 投票（バナーのみ）

###  3. 各種調整（いくつかリリース後でもOK）
- [ ] 多言語化のconfig変更（ヘッダー、フッター）
- [ ] ブログ投稿フロー
- [x] ファビコン
- [ ] ブランドアセットページのレイアウト変更
- [ ] image変更。about, signup

###  4. ブログ投稿フロー
- [x] テンプレート投稿
- [x] ファイル名 - 自動生成される。変更は右上。後で変更も可能
- [x] デフォルト画像挿入
- [x] Markdownが効いているか　- 手入力では`<p>`で囲われて効かない。GUIで選択すること。
- [x] 画像アップロード、画像ファイル格納先を`images/blog`に。
- [ ] OGP
- その他の注意事項
    - 日付入力は必須。日付を入れないと「0001年1月1日」になる。

###  5. OGPチェック
- [Twitter Card Validator](https://cards-dev.twitter.com/validator)と[OGP確認](https://rakko.tools/tools/9/)でチェック
- [ ] landing
- [ ] about
- [ ] txjp
- [ ] brand
- [ ] signup
- [ ] blog
- [ ] blog-post-official
- [ ] blog-post-writer

### 6. インフラ準備
- [x] defigeek.xyzリポジトリ作成
- [ ] 初回push & ブランチ
- [ ] ツール連携（Netlify、Forestry）
- [ ] Github Pages設定
- [ ] DNS設定
- [ ] Github Action設定
- [ ] 1ステップPRテスト
- [ ] カスタムドメイン設定
- [ ] `CNAME`で切替
- [ ] baseurlと
