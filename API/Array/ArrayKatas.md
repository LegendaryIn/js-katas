# Array katas

## [splice](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice)
```javascript=
arr.splice(index[, deleteCount, elem1, ..., elemN])
```
### katas
- Give a array ['a'], append with 'b', 'c' by splice.
- Give a array ['a', 'b', 'c'], delete 'b', 'c' elements by splice.
- Give a array ['ja', 'script'], insert 'v', 'a' between 'ja' and 'script' by splice.
- What is return by splice?

---

## [slice](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/slice)
```javascript=
arr.slice([begin[, end]])
```
### katas
- Give a array ['a', 'b', 'c', 'd', 'e'], use slice to get ['b', 'c' ,'d'].
- Give a array [1, 2, 3, 4, 5], use slice to get [4, 5].

---

## [concat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/concat)
```javascript=
var new_array = old_array.concat([value1[, value2[, ...[, valueN]]]])
```
### katas
- Give two array ['a', 'b'] and [1, 2], use concat to get ['a', 'b', 1, 2].
- Give three array [1, 2, 3], [4, 5, 6], [7, 8, 9], use concat to get [1, 2, 3, 4, 5, ,6 ,7 ,8 ,9].
- Give a array ['a', 'b'] and two value 'c' and 'd', use concat to get ['a', 'b', 'c', 'd'].