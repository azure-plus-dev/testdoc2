---
slug: /
---

### gitコマンドでプッシュする

:::note

・変更ファイル：test.md
・branch名：test-main

【Git push実行結果】
    ・PR作成画面でbasebranch「gh-pages」を選択すると、PR作成ボタンが表示されない<br>
    　（他のbasebranchではPR作成ボタンが表示される)<br>
    ・test_main からPUSH→mainへマージ  
    ・mainからfrom_mainディレクトリへクローン  
:::

### ローカルから yarn でビルド、デプロイ

:::note

【yarn実行結果】
    結果：変更内容がページへ反映された
    ・yarn build → yarn deploy 実行後、GitHub上でPRは作成されず、Actionが自動で実行された<br>
    ・ブランチ名は自動で「gh-pages」
    ・マージも自動で行われる（gh-pages→ origin gh-pages）
:::
