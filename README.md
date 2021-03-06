# 鱧天 for 吉里吉里2

## 概要

鱧天（Handy ADV Modules Template） for 吉里吉里2は、ゲームエンジン吉里吉里2を用いてADVやノベルゲームを作るときの、テンプレートとしてご利用いただけるものです。

もう少し具体的には、KAGをより手軽に使えるようにStudio F#で作成し、割といろいろな作品で実際に使用している、便利マクロ集のようなものです。

鱧天を使用することにより、次のような機能を比較的手軽にゲームに盛り込むことができます：

* スクリーンショット付きのグラフィカルなセーブ/ロード画面
* グラフィカルなコンフィグ画面
* スクロールバー付きバックログ
* シーン単位のシナリオスキップ
* セーブ/ロードやコンフィグ、バックログ等を呼び出せる右クリックメニュー
* 目パチをするキャラグラフィック（立ち絵）
* 閲覧済みイベントCG鑑賞モード

***

## 配布について

このリポジトリに置かれているのは原則として開発版です。<br>
リリースは鱧天の公式サイトより行っています。

鱧天公式サイト： http://hamotem.f-sp.net/

公式サイトにはマクロ等に関するドキュメントもありますので、ご一読ください。

また、二月ほづみの書いた、鱧天を使ったゲーム制作実例コラムを、無料ゲーム.com様で公開していただいております。<br>
よろしければこちらも併せてご覧ください。

無料ゲーム.com： http://www.0en-game.com/

***

## 謝辞

吉里吉里2の作者であるW.Dee氏をはじめ、吉里吉里2の発展に尽力されている方々に敬意を表すると共に、深く感謝申し上げます。<br>
吉里吉里2に関する情報は http://kikyou.info/ よりご覧ください。

また、鱧天では次の吉里吉里プラグインを内部的に利用し、同梱して配布しています：

* ktl_local_files.dll（KTLよりローカルストレージ操作 / &copy;Bolero MURAKAMI）

有用なプラグインを多数作成・公開されているBolero MURAKAMI氏に深く感謝申し上げます。<br>
KTLに関する最新版等の情報については、 http://www.boleros.x0.com/doc/ktlwiki/index.php?KTLWiki よりご覧ください。

また、鱧天では次のKAGプラグインを内部的に利用し、同梱して配布しています：

* autoInsertLabel.ks（どこでもセーブプラグイン / 作者不詳）

2015年10月現在、配布元・連絡先を見付けられず、ライセンスが不明な状態で、同梱して良いものかどうか迷ったのですが、大変有用なプラグインであり、またこれが無いと鱧天の一部機能が無効となってしまうため、やむを得ず同梱させていただいております。

作者様にはこの場を借りて深く感謝申し上げます。<br>
再配布に問題がある場合は、大変お手数ですが、本リポジトリの管理者までご連絡いただければ幸いです。 

***

## ライセンス

1. 鱧天（後述の同梱物を除く）に関する著作権はStudio F#に帰属しますが、利用者は、著作権に関する表記を行うこと無く、自由な利用、改変、及び成果物の配布が可能です。

2. また、鱧天そのものや、鱧天に手を加えたテンプレートを再配布していただいても構いませんが、その際にサポート等何らかの手間が発生する場合は、いずれも再配布者の責任に於いて対処してください。

3. ただし、上記のいかなる場合も、利用者は配布者に対していかなる保証も求めることはできません。

なお、配布アーカイブに同梱されるもののうち、次に掲げるものの諸権利は原配付者に帰属し、ライセンスも当該権利者の定めるところに従います：

* /krkr.eXe
* /pluginフォルダ内のすべてのファイル
* /data/systemフォルダ内のすべてのファイル
* /data/startup.tjs
* /data/scenario/KagPluginsフォルダ内のすべてのファイル（以上、&copy;W.Dee）
* /data/sysxmod_novel/_krplugin/ktl_local_files.dll（&copy;Bolero MURAKAMI）

ただし次に掲げるものについては、2015年10月現在配布元が不明なため、暫定的に鱧天と同等のライセンス的なもの（ただし著作権を除く）を適用するものとします：

* /data/scenario/KagPlugins/autoInsertLabel.ks

この措置は将来的に権利者が明らかになった段階等に解除されます。

***

## 免責事項

鱧天を利用したことによって生じたいかなる損害についても、Studio F#及びサークルメンバーは免責されるものとします。<br>
同様に同梱物の原配布者も免責されるものとします。

***

&copy;Studio F#.
