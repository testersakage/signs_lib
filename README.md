# signs_lib + Font Select

- [English Documentation (README.en.md)](./README.en.md) under construction
- [ORIGINAL REAMDE.md (README.upstream.md)](./README.upstream.md)

Signs Lib にフォント選択機能と日本語フォント(signs_lib_unijp<page>.png)を追加しました。

Luantiの設定画面から「Signs Lib」の設定項目にある「Select Unifont」のプルダウンメニューでフォント選択が可能です。
更に日本語以外のunifontからアトラス画像を生成して `settingtypes.txt` と `unifont.tsv` を編集することでフォントを追加する事も可能です。

Luantiの設定画面  
<img width=480, height=372, src="https://github.com/testersakage/signs_lib/blob/selectfont/screenshots/settingtypes.png"></img>

中華フォント問題の解消  
<img width=480, height=332, src="https://github.com/testersakage/signs_lib/blob/selectfont/screenshots/fontcmp.png"></img>


## 導入方法

1. 画面右上の「その他の操作」から、このブランチをZIP形式でダウンロードするか、gitを使用してクローンします。
2. 展開したフォルダを、Luantiの `mods/` ディレクトリに移動します。
3. フォルダ名を正確に **`signs_lib`** に変更します。
4. ワールドの設定画面からMODを**有効**にします。

## ライセンス

[LICENSE](./LICENSE)  
License for code: LGPL 3.0  
License for media and all other assets:  CC-by-SA 4.0  
