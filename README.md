# Haskell 文法用リポジトリ

参考記事 : https://haskell.jp/blog/posts/2017/08-ghc-4way-execution.html

Haskell用コンパイラであるGHCには、以下のように４種類の実行方法があります。

- コンパイル実行 : `ghc`
- スクリプト的実行 :`runghc` (`orrunhaskell`)
- 対話的実行 :`ghci`
- ワンライナー的実行 :`ghc -e`

以下、それぞれについて簡単に紹介します。
なお、本記事では、stack経由ではなく、素のGHCを使う場合について説明しています。
