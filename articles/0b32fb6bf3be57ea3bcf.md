---
title: "php foreachæ"
emoji: "ð¥"
type: "tech" # tech: æè¡è¨äº / idea: ã¢ã¤ãã¢
topics: [php]
published: true
---

## ã¯ããã«
phpãå­¦ç¿ãå§ããã®ã§ãä½¿ã£ãæãã¾ã¨ãã¦ããã¾ãã

## foreachæ
* éåã¨ãªãã¸ã§ã¯ãã«å¯¾ãã¦ã®å¦çã§ãã
* å¼æ°ã«æ¸¡ããå¤æ°ã«ç¾å¨ã®è¦ç´ ãä»£å¥ããã¾ãã
* è¦ç´ ã®æ°ã ãç¹°ãè¿ãã¾ãã

```php

// éåã®è¦ç´ ãå¤æ°ã«ä»£å¥
foreach (éå as å¤æ°){
    å¦ç
}

// éåã®ã­ã¼ãå¤æ°ã­ã¼ã«ä»£å¥
foreach (éå as å¤æ°ã­ã¼ => å¤æ°){
    å¦ç
}
```

### åè¦ç´ ãå¤æ°ã«ä»£å¥

```php
$weather = array("sunny", "rainy", "cloudy");

foreach ($aweather as $w) {
    echo "$w \n" ;
}

// sunny 
// rainy 
// cloudy 

```

### ç¾å¨ã®è¦ç´ ã®ã­ã¼ãå¤æ°$keyã«ä»£å¥
```php
$weather = array("sunny", "rainy", "cloudy");

foreach ($weather as $key => $w) {
    echo "$key.$w \n" ;


// 0.sunny 
// 1.rainy 
// 2.cloudy 
```


[foreach](https://www.php.net/manual/ja/control-structures.foreach.php#control-structures.foreach)
