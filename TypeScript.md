# TypeScript 井上章
* 登場の背景
* 基本的な言語使用

JSのスーパーセット（上位拡張）
TypeScriptコンパイラ(tsc)がJavaSctiptを生成
altJSのひとつ

jsの機能ギャップをうめるため。実情・最新

visualstudio  or  npm typescript

.ts -> tsc -> .js
ES5なのかES6なのかなどをコンパイラのオプションで決めれる。

.d.ts TS型定義ファイル
  例）jqueryのメソッドの型をコンパイラに教える

tsc の実態は tsc.js

VSだと、ts保存した時点でコンパイルが走る。

構文解析のインテリセンスがきく。

外からアクセスするには、使いたいクラスに  export

tsc -w app.ts   app.tsを watchしてくれる。

tsconfig.json
  TypeScriptプロジェウトの定義ファイル

tsd install jquery とか

型定義ファイル
Defiintely Typed(型定義リポジトリ)

google  ts + VScode でAngularの開発をしている。

art JavaSctipt
