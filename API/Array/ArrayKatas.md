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

---

## [forEach](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/forEach)
```javascript=
arr.forEach(function(item, index, array) {
  // ... do something with item
});
```
### katas
- Use forEach to print from 0 to 9.
- Give [1, 2, 3, 4, 5, 6, 7, 8, 9], if element is odd then print 'odd', if it is even then print 'even'.
- Give ['+', '+', '-', '-', '-'] and number 10, '+' mean plus number by 1, '-' mean minus number by 1, print the result number.

---

## [indexOf](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf)
```javascript=
arr.indexOf(searchElement[, fromIndex])
```
### katas
```javascript=
let arr = ['a', 'b', 'c', 'd', 'e', 'a', 'b','c', NaN];
//what are the results?
arr.indexOf('a');
arr.indexOf('a', 1);
arr.indexOf('f');
arr.indexOf('a', -1);
arr.indexOf('a', -4);
arr.indexOf(null);
arr.indexOf(NaN);
```

---

## [includes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/includes)
```javascript=
arr.includes(valueToFind[, fromIndex])
```
### katas
```javascript=
let arr = ['a', 'B', NaN];
//what are the results?
arr.includes('a');
arr.includes('A');
arr.includes('B', 1);
arr.includes('B', 2);
arr.includes(NaN);
```

---

## [find](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/find)
```javascript=
let result = arr.find(function(item, index, array) {
  // should return true if the item is what we are looking for
});
```
### katas
```javascript=
let students = [
    {
        id: 1,
        name: 'Amy',
    },
    {
        id: 2,
        name: 'Eva',
    },
    {
        id: 3,
        name: 'Ivy',
    }
];
```
- Use find to get object which name is Ivy.
- What is the result if nothing found?

---