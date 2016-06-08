# EF Core

* これまで EF 6.1.3
EF everywhere

win からでも　Mac からでも linux からでもDBアクセスできる。

DBfirst, modelfirst, codefirstが選べたが、
EF Core は code first のみ
プロダクション系はまだEF6のほうがいい

* マルチストレージ
    RDBだけでなくNoSQLにもつなげる
 
 powerBI
 テーブルストレージ
 AzuleStorage   NoSQL
 
 shadow propaty
 
 EF4 -> EF5　大幅にパフォーマンス向上
 EF6 -> EF coreでも大幅に向上
 
 単純なselect文では約６倍
 
 insert５回やっていたのを、まとめて１回で処理（だから早い。）
 
 ### まとめ
 * 新たに開発した軽量な