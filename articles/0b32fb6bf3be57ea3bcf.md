---
title: "php foreach文"
emoji: "🔥"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: [php]
published: true
---

## はじめに
phpを学習し始めたので、使った文をまとめていきます。

## foreach文
* 配列とオブジェクトに対しての処理です。
* 引数に渡した変数に現在の要素が代入されます。
* 要素の数だけ繰り返します。

```php

// 配列の要素を変数に代入
foreach (配列 as 変数){
    処理
}

// 配列のキーを変数キーに代入
foreach (配列 as 変数キー => 変数){
    処理
}
```

### 各要素を変数に代入

```php
$weather = array("sunny", "rainy", "cloudy");

foreach ($aweather as $w) {
    echo "$w \n" ;
}

// sunny 
// rainy 
// cloudy 

```

### 現在の要素のキーを変数$keyに代入
```php
$weather = array("sunny", "rainy", "cloudy");

foreach ($weather as $key => $w) {
    echo "$key.$w \n" ;


// 0.sunny 
// 1.rainy 
// 2.cloudy 
```


[foreach](https://www.php.net/manual/ja/control-structures.foreach.php#control-structures.foreach)
