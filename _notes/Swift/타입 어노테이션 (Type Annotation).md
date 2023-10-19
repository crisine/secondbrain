# 타입 어노테이션이란?

```swift
let name: String = "misung"
```

타입 어노테이션이란, 위와 같이 자료형을 직접 지정해주는 방식을 말한다.

- 대개 타입을 명시할 때는 `:` 콜론 뒤에 한 칸을 띄고 명시한다.

## 타입 어노테이션의 장점

```swift
let name: String
let age: Int
```

- 초기값이 없어도 된다. (컴파일러가 [타입 추론](obsidian://open?vault=Obsidian%20Vault&file=900%20%EC%98%81%EA%B5%AC%20%EB%A9%94%EB%AA%A8%2FSwiftMaster%2F%EA%B0%9C%EB%85%90%EC%A0%95%EB%A6%AC%2F%ED%83%80%EC%9E%85%20%EC%B6%94%EB%A1%A0%20(Type%20Inference))을 할 필요가 없다.)
