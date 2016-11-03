# 偶数、奇数の判定

次のように、整数を偶数、もしくは奇数に分ける関数を定義してください。

## 記法

~~~javascript
let label = classifyInt(integer);
~~~

### 引数

* integer：整数

### 返り値

`"偶数"`もしくは`"奇数"`のどちらか。
`integer` が偶数の時は前者を、そうでない時は後者を返します。

## 利用例

~~~javascript
let odd = 3;
let even = 10;

let labelOdd = classifyInt(odd);
let labelEven = classifyInt(even);

console.log(`${odd} は${labelOdd}`);
console.log(`${even} は${labelEven}`);
~~~
