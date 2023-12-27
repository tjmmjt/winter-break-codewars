# winter-break-codewars

base mode challenges complete

```
// ! Challenge 1
// https://www.codewars.com/kata/5168bb5dfe9a00b126000018

function solution(str){
//   console.log(str.split("").reverse().join(""))
  return str.split("").reverse().join("");
}

solution("ZippityDooDa")
```

```
// ! Challenge 2
// https://www.codewars.com/kata/5715eaedb436cf5606000381

function positiveSum(arr) {
  let sum = 0
  for(let num of arr){
    if(num > 0){
      sum += num
    }
  }
  return sum
}
```

```
// ! Challenge 3
// https://www.codewars.com/kata/57a0e5c372292dd76d000d7e

function repeatStr (n, s) {
  return s.repeat(n)
}

// ! Challenge 4
// https://www.codewars.com/kata/57eae20f5500ad98e50002c5

function noSpace(x){
  return x.replace(/\s/g, '');
}
```

```
// ! Challenge 5
// https://www.codewars.com/kata/57eadb7ecd143f4c9c0000a3/javascript

function abbrevName(name){
  return name.split(' ').map((init) => init[0]).join('.').toUpperCase()
}
```

```
// ! Challenge 6
// https://www.codewars.com/kata/5583090cbe83f4fd8c000051

function digitize(n) {
	return n.toString().split('').reverse().map(Number)
}
```
