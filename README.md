# yaya-dic

YAYA向けシステム辞書＆あやりりすのリポジトリです。別プロジェクトに分離し参照しやすくしました。

A repository of system dictionaries for YAYA and Aya Lilith. Separated into another project for easier reference.

## 使い方 -- How to Use

基礎設定ファイルに下記を追記してください。

Please add the following to the basic configuration file.

```
dicdir, aya_lilith
dicdir, yaya_base
```

必要に応じて`yaya_base/config.dic`を修正してください。

Modify `yaya_base/config.dic` if necessary.


また、_loading_order.txt を編集することで、`yaya_base/optional.dic`を無効にしたり、`yaya_base/compatible.dic`を有効にすることが可能です。

Also, by editing _loading_order.txt, you can disable `yaya_base/optional.dic` or  enable `yaya_base/compatible.dic`.

## ライセンス -- License

Public Domain (Unlicense)

煮るなり焼くなり好きにしてください。

You can boil it or bake it or do whatever you like.
