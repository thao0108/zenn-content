---
title: "Javascript 変数宣言"
emoji: "🤖"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: ["Javascript"]
published: true
---

## はじめに
Javascriptの基本を復習がてらまとめていこうと思います。

## 変数宣言
変数宣言とは名前をつけた箱に値を入れておくようなイメージです。


### 宣言の仕方'
* 変数の宣言の仕方には、`const``let``var`というキーワードを使って宣言します。
* `var`はなるベく使わず`const``let`を使って宣言しましょう。

```
キーワード　+ 変数名(名前をつけた箱)
```

```js
const a = 1;

//再代入不可能
a = 4;  

//再代入不可能
const a = 5; 

```

```js
let b = 1;

// 再代入可能
b = 2; 

//再宣言不可能
let b = 4; 

```

```js

var c = 1;

// 再代入可能
c = 2;

// 再宣言可能
var c = 3; 
```

## varが良くない理由
* 変数を簡単に書き換えられてしまうと、意図しないバグが発生しやすいです
* 巻き上げのバグを生みやすいです
**以下の記事を参照してみてください。**
[JavaScriptでvarが非推奨な理由を整理してみた](https://qiita.com/taiju_suzuki/items/49ed558bd837452353b8)

[Hoisting (巻き上げ、ホイスティング)](https://developer.mozilla.org/ja/docs/Glossary/Hoisting)

