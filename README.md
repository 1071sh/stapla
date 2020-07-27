# Prettier と stylelint で保存時に自動整形

表題の通りです。

## 構築手順

1. npm i -D stylelint stylelint-config-recommended
1. npm i -D prettier stylelint-config-prettier stylelint-prettier
1. npm i -D stylelint-order stylelint-config-recess-order

以下のファイルは設定済み。

-   .stylelintrc.json
-   .prettierrc.json

## stylelint の order モジュール選定

stylelint-config-recess-order
