# Coding Problems

## JavaScript Logic
- Async execution order (setTimeout, promises, console.log)
- Find two-sum indexes in array
- Square of even numbers using map
- Count duplicates in array
- Remove duplicates using spread operator
- Reverse string
- Find missing elements between min & max in array
- Valid parentheses check

```javascript
function validPara(input){
  let matchPara = {
    '[' : ']',
    '(': ')',
    '{': '}'
  }
  
  let stack = []
  
  for(let i=0; i< input.length; i++){
    let char = input[i]
    if(matchPara[char]){
      stack.push(matchPara[char])
    }else if(stack.pop() != char){
      return false
    }
  }
  return stack.length === 0
}
let input = '[{]()'
console.log(validPara(input))
```
- Group objects by property (deptId → array of names)
- Sort array of 0s, 1s, 2s
- Longest common prefix
- Flatten array without `flat()`
- Find repeated numbers & char counts in string

## Angular
- Progress bar in Angular (increment by 10% every sec)

## SQL
- 2nd highest salary in SQL

## Guess the Output
- Hoisting
- Temporal Dead Zone (TDZ)
- Closures
- Promise resolution order


# Coding Problems - Guess the Output

## Question 1
```javascript
(function() {
    console.log(1); 
    setTimeout(function(){console.log(2)}, 1000); 
    setTimeout(function(){console.log(3)}, 0); 
    console.log(4);
})();
```
<details>
<summary>Show Output</summary>

```
1  
4  
3  
2
```
</details>

---

## Question 2
```javascript
console.log('start');
const promise1 = new Promise((resolve, reject) => {
  console.log(1)
  resolve(2)
  console.log(3)
})

promise1.then(res => {
  console.log(res)
})

console.log('end');
```
<details>
<summary>Show Output</summary>

```
start  
1  
3  
end  
2
```
</details>

---

## Question 3
```javascript
console.log(isNaN(true))
console.log(isNaN(undefined))
```
<details>
<summary>Show Output</summary>

```
false  
true
```
</details>

---

## Question 4
```javascript
let arr = [1,2,3,4,5]
let arr1 = [6,7,8]
let arr2 = [...arr, ...arr1]
arr2.splice(0, arr1.length - 1)
console.log(arr2)
```
<details>
<summary>Show Output</summary>

```
[3, 4, 5, 6, 7, 8]
```
</details>

---

## Question 5
```javascript
var a = 0;
console.log(a);
```
<details>
<summary>Show Output</summary>

```
0
```
</details>

---

## Question 6
```javascript
console.log(a);
let a = 0;
```
<details>
<summary>Show Output</summary>

```
ReferenceError: Cannot access 'a' before initialization
```
</details>

---

## Question 7
```javascript
const promise = new Promise((resolve, reject) => {
    console.log('111');
    resolve('222');
});
console.log('333')
promise.then(message => console.log(message))
```
<details>
<summary>Show Output</summary>

```
111  
333  
222
```
</details>

---

## Question 8
```javascript
const a = {}
const b = {}

const k = {...a, ...b}
a.data = {user_id:12345}
const c = a

console.log("c = ", c)
console.log("k = ", k)
```
<details>
<summary>Show Output</summary>

```
c =  { data: { user_id: 12345 } }  
k =  {}
```
</details>

