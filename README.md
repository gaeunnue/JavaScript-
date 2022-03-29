---
# JavaScript 02. 변수와 상수
---
`console.log` : 값을 출력
## 변수
바뀔 수 있는 값을 선언. 

같은 블록 범위 내 let 중복 사용 불가

`let` 키워드 
``` 
let value = 1;
value = 2;
console.log(value); 
```
## 상수
constant, 불변의 값 선언.

`const` 키워드

## 데이터 타입 

선언할 데이터의 종류 
##### 숫자 (Number)
` let value = 1; `
##### 문자열 (String)
```
let text = 'hello';
let name = 'JavaScipt';
```
##### 참/거짓 (Boolean)
```
let good = true;
let loading = false;
```
##### null과 undefined 
null : 이 값이 없다! 선언 

undefined : 이 값이 아직 설정 안 되었다! 선언 
```
let criminal;
console.log(criminal); // 변수선언만 했으므로 undefined 출력
```
---
# JavaScript 03. 연산자  
---
## 산술 연산자
컴퓨터가 사칙 연산을 해줌.
+ `+`: 덧셈
+ `-`: 뺄셈
+ `*`: 곱셈
+ `/`: 나눗셈 
```
let a = 1 + 2;
console.log(a); // 3출력
```
- `++`: 특정변수에 1을 바로 더해줌. 
- `console.log(a++)`: 1 더하기 직전 값 출력
- `console.log(++a)`: 1 더한 다음 값 출력 
## 대입 연산자 
`=` 키워드 : 특정 값에 연산하고 싶을 때 
```
let a = 1;
a = a + 3;
```
```
let a = 1;
a += 3;
```
## 논리 연산자 
+ `!` : NOT (반대로)
+ `&&`: AND (교)
+ `||`: OR  (합)











