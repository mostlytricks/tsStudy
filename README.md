# tsStudy

## nomad - memo
- https://nomadcoders.co/typescript-for-beginners/lectures/3667

## 1.5 Why not JavaScript
- Java script는 사용자에 너무 친화적인 언어

```javascript
const divide= (a,b) =>{
    return a/b;
}
```
- 이런 함수에서, 과연 a,b가 숫자가 아닌경우 / a만 주는 경우 어떠해야 하는가
- js는 그냥 실행해준다. 에러를 뱉는게 아니라.

- 최악의 에러는 런타임 에러. 실행중 콘솔에서 발생하는 유형의 에러.

```javascript
const holy = {name : "holy"};
holy.hello()
// error! > TypeError
```
- 보통 이런건 holy객체를 사전 분석해서, 실행전에 문제가 있습니다~하고 알려준다.
  - 그러나 js는 컴파일 실패는 무슨. 콘솔에서 .hello를 얌전히 실행하고 실패했습니다를 보여준다.


## 2.0 How Typescript Works
- typescript => javascript
  - 보호의 시점은 이 변환의 시점에 확인 진행. 이후 작성된 js는 브라우저에서 해석 가능