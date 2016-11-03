# 総和

次のように、指定された区間に含まれる、全ての整数の総和を求める関数を定義してください。

## 記法

~~~javascript
let result = sum(lowerBound, upperBound);
~~~

### 引数

* `lowerBound`：区間の下限となる数値
* `upperBound`：区間の上限となる数値

なおこの 2 つの数値で表される区間は[閉区間](https://ja.wikipedia.org/wiki/%E5%8C%BA%E9%96%93_(%E6%95%B0%E5%AD%A6))で、それぞれの数値もその区間に含まれます。

### 返り値

指定された区間に含まれる、全ての整数の総和

## 使用例

~~~javascript
let sum10 = sum(0, 10);
let zero = sum(-10.5, 10.9);

console.log(`sum(0, 10) = ${sum10}`);
console.log(`sum(-10, 10) = ${zero}`);
~~~