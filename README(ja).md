# sublimeMQL4compile

MetaTrader4 (MQL4) compile for Sublime Text 3  

---

sublimeMQL4compile は [MQL4 (MetaTrader)](http://www.metaquotes.net/en/metatrader4/trading_terminal) を [Sublime Text 3](https://www.sublimetext.com/3) でコンパイルし、エラー確認ログを自動表示するプラグインです。 

**<スクリーンショット>**

![sublimeMQL4compile](http://cdn-ak.f.st-hatena.com/images/fotolife/m/mofoolog/20160423/20160423130603.gif?1461384552 "sublimeMQL4compile-gif")

MetaEditor で扱う全てのファイル (`.mq4` , `.mqh`) がコンパイル可能です。また、`.dll` や `.ex4` を import した場合も動作します。  

&nbsp;

## インストール

clorn してインストールするか、 zip をダウンロード･解凍してできた `sublimeMQL4compile` を `$HOME$\AppData\Roaming\Sublime Text 3\Packages\` ディレクトリ以下 (ご自身の環境に合わせて読み替えてください) に置いてください。  

※ 今のところ Package Control には対応していません。  

&nbsp;

## 設定

`sublimeMQL4compile` ディレクトリ内の `sublimeMQL4compile.sublime-settings` ファイルを開き、`"compiler_path"` 欄にご自身の `metaeditor.exe` の絶対パスを入力してください。 

初期設定は以下になっています。  

```json
{
    "compiler_path": "C:\\Program Files (x86)\\MetaTrader 4\\metaeditor.exe"
}
```

Mac や Linux で Wine を介した MetaEditor の PATH を入力する場合の例 (未検証)

```json
{
    "compiler_path": "/home/<Your Name>/.wine/drive_c/Program Files/MetaTrader 4/metaeditor.exe"
}
```

&nbsp;

## 使い方

コンパイルしたいファイルを保存し、以下の操作でコンパイルからエラー確認ログの表示まで自動で行います。  

* ショートカットキー : [ `Ctrl` + `4` ]

または

* コントロールパネルを開き `mql` と入力して表示される `MQL4 Compile` を選択実行

&nbsp;

## その他

`sublimeMQL4compile` は Windows で動作確認済みですが、wine を利用した Mac や Linux 環境での動作確認はしていません。  

`"compiler_path"` に `metaeditor.exe` の wine を介した絶対パスを入力すれば動作するのではないかと思ってはいますが、wine 環境を持っていないので分かりません。 

どなたか Mac や Linux で使った方が居ましたら、ご一報くださいm(_ _)m

&nbsp;
