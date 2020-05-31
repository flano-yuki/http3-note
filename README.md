# http3-note

[@flano_yuki](https://twitter.com/flano_yuki)がHTTP/3について書きました。

2020/06/01 時点です。今後加筆されます。

- [1. はじめに(HTTP/3と概要)](https://github.com/flano-yuki/http3-note/blob/master/http3-note_1.pdf) ([ダウンロード](https://github.com/flano-yuki/http3-note/raw/master/http3-note_1.pdf))
- [2 QUICについて](https://github.com/flano-yuki/http3-note/blob/master/http3-note_2.pdf) ([ダウンロード](https://github.com/flano-yuki/http3-note/raw/master/http3-note_2.pdf))
- [3 HTTP/3について](https://github.com/flano-yuki/http3-note/blob/master/http3-note_3.pdf) ([ダウンロード](https://github.com/flano-yuki/http3-note/raw/master/http3-note_3.pdf))
- [4 HTTP/3 拡張仕様と応用](https://github.com/flano-yuki/http3-note/blob/master/http3-note_4.pdf) ([ダウンロード](https://github.com/flano-yuki/http3-note/raw/master/http3-note_4.pdf))
- 5 TODO 実装、ツール紹介

## 内容

- [1. はじめに(HTTP/3と概要)](https://github.com/flano-yuki/http3-note/blob/master/http3-note_1.pdf)
  - 1.1 はじめのはじめに
  - 1.2 HTTPのセマンティクスとバージョンの話
  - 1.3 HTTP/3の概要
  - 1.4 HTTP/3 と呼ばれるまでの道のり
     - 1.4.1 Google QUICの実験
     - 1.4.2 HTTP over QUIC、標準化の開始
     - 1.4.3 HTTP/3への改称
  - 1.5 標準化動向を追うために
- [2 QUICについて](https://github.com/flano-yuki/http3-note/blob/master/http3-note_2.pdf)
  - 2.1 QUIC、はじめに
  - 2.2 QUICの概要
  - 2.3 QUICコネクションとQUICパケットの基礎
  - 2.4 フレームについて
  - 2.5 ストリームについて
  - 2.6 コネクションの確立
  - 2.7 コネクションのクローズ
  - (TODO)2.8 負荷分散・トラフィックのオペレーション
  - 2.9 その他 (FEC, Multipath, LB)
     - 2.9.1 Forward Error Correction(FEC)
     - 2.9.2 MP-QUIC
     - (TODO) 2.9.3 QUIC-LB
  - 2.10 応用例
  - TODO
- [3 HTTP/3について](https://github.com/flano-yuki/http3-note/blob/master/http3-note_3.pdf)
  - 3.1 HTTP/3のはじめに
  - 3.2 HTTP/3対応の通知とコネクションの開始
  - 3.3 QUICストリームの利用
  - 3.4 HTTP/3 フレーム
  - 3.5 HTTPメッセージの送受信
     - 3.5.1 HTTPメッセージを送るまで
     - 3.5.2 HTTPメッセージの送受信
     - 3.5.3 CONNECTメソッド
  - 3.6 ヘッダ圧縮 QPACK
     - 3.6.1 ハフマン符号
     - 3.6.2 静的テーブル、動的テーブル
     - 3.6.3 ヘッダ表現
  - 3.7 サーバプッシュ
  - 3.8 優先度制御
  - 3.9 コネクションの終了
  - 3.10 拡張性
- [4 HTTP/3 拡張仕様と応用](https://github.com/flano-yuki/http3-note/blob/master/http3-note_4.pdf)
  - 4.1 HTTP/3 拡張仕様と応用、はじめに
  - 4.2 HTTP/2の拡張フレーム
  - 4.3 DATAGRAMフレーム
  - 4.4 WebTransport
     - 4.4.1 背景と概要
     - 4.4.2 WebTransport over QUIC
     - (TODO)4.3.3 WebTransport over HTTP/3
  - (TODO) 4.5 MASQUE
  - (TODO) 4.6 RIPT
  - (TODO) 4.7 HTTP over multicast QUIC

