## Return Negative

```js

function makeNegative(num) {
  if (num < 0) {
    return num * 1
  } else { return num * -1
  }
}
makeNegative()

## Sum of Positive

```js
````
\\\\
const randomNumber = [1, -2, -4, 2]
let sum = 0;
for (let i = 0; i < randomNumber.length; i++) {
    if (randomNumber[i] > 0) {
    sum += randomNumber[i];
    }
}
## Function 2

```js

`````

function square(num){
console.log(num ** 2)
}
square(num)
## Sum Arrays

```js
`
function sum(numbers) {
 let sum = 0
 for (let i = 0; i < numbers.length; i++){
    sum += numbers[i]
 }
      return sum
}
sum()

## Reversed Strings
function solution1(str){
    let splitArr = str.split('');
    let reverseArr = [];
    for(let i=splitArr.length-1; i>=0; i--) {
        reverseArr.push(splitArr[i])
    }
    return reverseArr.join('')
}

function solution2(str){
    return str.split('').reverse().join('')
}
```js

```
