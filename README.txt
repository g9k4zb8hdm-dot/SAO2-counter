# SAO2 実戦カウンター PWA

このフォルダ内のファイルを同じ階層のまま HTTPS のWebサーバーへアップロードしてください。

必要ファイル:
- index.html
- manifest.webmanifest
- service-worker.js
- icon-180.png
- icon-192.png
- icon-512.png

iPhone:
1. Safariで公開URLを開く
2. 共有
3. ホーム画面に追加
4. ホーム画面の「SAO2カウンター」から起動

一度正常に読み込めば、Service Worker により主要ファイルをキャッシュするためオフライン起動にも対応します。
