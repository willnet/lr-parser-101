# LR parser 101

## LR parser 101 とは

Rubyで書かれたLALR(1) パーサジェネレーター [Racc](https://github.com/ruby/racc)を使った電卓の実装を通じて、パーサジェネレーターを利用したパーサの作り方について学びます。

* 第0章 "セットアップ" (必要?)
* 第1章 "数字を受け取って数字を表示する" ではタイトルのとおり数字を受け取ってそのまま数字を表示するシンプルなパーサをつくります
* 第2章 "足し算と引き算" では足し算と引き算を実装します
* 第3章 "複数回の足し算と引き算" では複数回の足し算と引き算ができるようにパーサを拡張します
* 第4章 "掛け算と割り算" ではいよいよ掛け算と割り算を実装します
* 第5章 "括弧の導入" では括弧の実装おこないます
* 第6章 "演算子優先順位(Operator Precedence)" では優先順位機能を使って少ないルールで電卓を実装します

## 応用的な課題 (未実装)

* "1_000_000" のような記法をサポートする (Lexerを修正する課題)。
* 電卓の実装を発展させる。アクションで計算を行うのをやめて抽象構文木(AST)をつくって、構文木を別で評価する。
* "RubyでつくるRuby"用のparserのsubsetをraccでつくる。"RubyでつくるRuby"が複雑な場合そのsubsetにする。

## TODO

* 参考文献や参考になるサイトをまとめる
  * [『Rubyソースコード完全解説』](https://i.loveruby.net/ja/rhg/book/)
* Lexerについて説明する (chapter_7 or later)

## ライセンス

MIT License.
