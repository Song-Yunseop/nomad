# nomad

## 2022/02/18
바닐라 JS로 크롬 앱 만들기2.2까지 봄

자바스크립트는 변수 공백을 my_name이 아니라 myName으로 첫글자 대문자로 구분함

var는 안씀
```
alert("내용")
console.log("내용")
const 상수이름 = 상수

변수만들때 let, const, var차이
let 재선언 금지, 재할당 가능
const 재선언 금지, 재할당 금지
var 재선언 가능, 재할당 가능

let a = b;
let a = c;
//재선언 금지

let a = b;
a = c;
//재할당은 가능

const a = b;
const a = c;
//재선언 금지

const a = b;
a = c;
//재할당 금지

var a = b;
var a = c;
a = d;
//재선언, 재할당 가능
```