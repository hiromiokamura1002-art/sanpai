# 産廃講習ドリル

産業廃棄物の収集運搬業の許可講習会（新規・収集運搬課程）の修了試験にそなえる学習アプリ「産廃講習ドリル」の、サポートページ・プライバシーポリシー・利用規約・特定商取引法に基づく表記です。アプリは非公式の学習用アプリで、講習会の実施団体や公的機関とは関係がありません。

- サポート：https://hiromiokamura1002-art.github.io/sanpai/support.html
- プライバシーポリシー：https://hiromiokamura1002-art.github.io/sanpai/legal/privacy.html
- 利用規約：https://hiromiokamura1002-art.github.io/sanpai/legal/terms.html
- 特定商取引法に基づく表記：https://hiromiokamura1002-art.github.io/sanpai/legal/tokushoho.html

問い合わせ：elplancho.cheese@gmail.com

## 公開のしかた（GitHub Pages）

1. GitHub に公開（Public）のリポジトリ `hiromiokamura1002-art/sanpai` を作り、このフォルダの中身をそのまま入れる
2. リポジトリの Settings → Pages → 「Build and deployment」の Source を **Deploy from a branch**、Branch を **main**、フォルダを **/ (root)** にして Save
3. 1〜5 分待って、上の 4 つの URL が開くことを確かめる

## 文面を直すとき

ここのファイルは、アプリのリポジトリ（非公開の `sanpai-app`）の `src/lib/legalTexts.ts` から `npm run gen:legal` で書き出した `docs/index.html`・`docs/support.html`・`docs/legal/*.html` の写しです。ここを直接直さず、アプリ側で直して書き出してから写します。
