# 最大公約数

次のように 2 つの整数の最大公約数を返す関数を定義してください。

## 記法

~~~javascript
let number = gcd(integerA, integerB);
~~~

### 引数

* integerA：最大公約数の計算に用いる 1 つ目の整数
* integerB：最大公約数の計算に用いる 2 つ目の整数

### 返り値

引数に指定された整数の最大公約数

## 利用例

~~~javascript
let a, b;
a = 128;
b = 76;
let c = gcd(a, b);
console.log(`gcd(${a}, ${b}) = ${c}`);
~~~