# MT4DelTooltip

----------------------------------
version 4
dll をマルチスレッドにして、MT4 本体の待ち時間が最小になるようにしました。
https://github.com/TTSS000/MT4DelTooltip/blob/main/MT4DelTooltipV4.zip
この URL にアクセスして、download ボタンでダウンロードしてください。

----------------------------------
version 2

tooltips の内容に含まれる文字列を二個検索して両方が見つかれば、表示されないようにしました。
二個の文字列が含まれない tooltips はそのまま表示されつづけます。

https://github.com/TTSS000/MT4DelTooltip/blob/main/MT4DelTooltipV2.zip
この URL にアクセスして、download ボタンでダウンロードしてください。
mq4 もバージョンアップして、コードのなかで、文字列(初期値は "バー" と "最終価格")を指定するようになってます。

以上


----------------------------------
version 1

https://github.com/TTSS000/MT4DelTooltip

サイトにアクセスしていただくと、code という緑のボタンがあります。そこから download zip で zip ファイルをダウンロードします。
次に、Windows 上でダウンロード済の zip ファイルをマウス右クリックして、メニューが出たら「すべて展開」します。zip が入れ子になってたら、またそれもすべて展開してください。

いくつかある、フォルダから、 DelTooltip.dll というファイルを探していただいて、これは MT4 の Libraries フォルダーに入れてください。
同じように DelTooltips.mq4 を探して、これは MT4 の indicators フォルダーに入れてください。
Libraries と indicators のフォルダーは、MT4 のメニューから、[ファイル] ⇒ [データフォルダを開く] をして、フォルダが開いたら、さらに MQL4 というフォルダーを開くと見つかります。

MT4 を再起動するか、Navigator のツリーのところで、マウスを右クリックして「更新」すると、インジケーター一覧のツリーにこのインジが出てきます。

MT4のどれか一つのチャートにこのインジを入れてください。入れるときに 「DLLの使用を許可する」にチェックをつけてください。
最初は、何回か、tooltip が表示されますが、そのうち表示されなくなります。

注 : MT4 に表示される、すべての tooltip が消えるので、必要な tooltip も消えるかもしれません。

以上
