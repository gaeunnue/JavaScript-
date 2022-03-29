
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

##### NOT
반대값 출력. true면 false로, false면 true로 바꿔줌. 
```
const a = !true;
console.log(a);
```
##### AND
교집합. 양쪽 다 true일때만 결과물이 true.
```
const a = true && true;
console.log(a); 
```
##### OR
합집합. 둘 중 하나라도 true면 결과물이 true.
```
let t = true || false;
```
##### 연산 순서
NOT -> AND -> OR 
## 비교 연산자 
두 값을 비교할 때 사용함.
+ `===` 키워드: 두 값이 일치하는지 확인 -> 일치하면 true, 일치하지 않으면 false.

( 타입검사까지 일치 ) 
+ `!==` 키워드: 두 값이 일치하지 않는지 확인 -> 일치하면 false

( 타입검사 실시 x )
+ `> < >= <=` : 대소관계 
# JavaScript 04. 조건문
---
## If 문 
( ): 조건문 '~라면'

{ }: 실행문 '~해라'

조건이 true가 된다면, 실행문이 실행됨.
```
const a = 1;
if (a + 1 === 2) {
  console.log('a+1이 2입니다.');
}
```
`{ }` : 코드 블록 
```
const a = 1;
if (true) {
  const a = 2;
  console.log('if문 안의 a값은'+a);
}
console.log('if문 밖의 a값은' +a);
```
## if-else 문
```
const a = 10;
if ( a>15 ) { 
  console.log('a가 15보다 큽니다.');
} else { 
  console.log('a가 15보다 크지 않습니다.');
}
```
## if-else if 문
```
const a = 10;
if ( a===5 ) {
  console.log('5입니다!');
} else if ( a===10) {
  console.log('10입니다.!');
} else {
  console.log('5도 아니고 10도 아닙니다.');
}
```
## switch/case 문
변수 값을 다양하게 바꿔서 코드를 실행하고 싶을 때 사용. 
```
const device = 'iphone';

switch (device) {
  case 'iphone':
    console.log('아이폰!');
    break;
  case 'ipad':
    console.log('아이패드!');
    break;
  case 'galaxy note':
    console.log('갤럭시 노트!');
    break;
  default:
    console.log('모르겠네요..');
}
```
`break;`: 각 case를 실행하고 마무리. 
`default:` : 그 외 case 값일 경우 






















