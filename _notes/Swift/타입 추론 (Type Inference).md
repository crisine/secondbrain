# 타입 추론이란?

```swift
let name = "misung"
```

타입 추론이란, 컴파일러가 초기화된 값 (`"misung"`) 을 기준으로 타입을 추론하는 것이다.
`"misung"` 은 `String` 타입의 값이므로, 컴파일러는 추론한 값으로 타입을 지정하게 된다.

## 타입 추론의 장점

```swift
let name = "misung"
let age = "20"
```

- 타입을 명시적으로 작성([타입 어노테이션](obsidian://open?vault=Obsidian%20Vault&file=900%20%EC%98%81%EA%B5%AC%20%EB%A9%94%EB%AA%A8%2FSwiftMaster%2F%EA%B0%9C%EB%85%90%EC%A0%95%EB%A6%AC%2F%ED%83%80%EC%9E%85%20%EC%96%B4%EB%85%B8%ED%85%8C%EC%9D%B4%EC%85%98%20(Type%20Annotation)))하지 않아도 됨.

## 타입 추론의 단점

```swift
let a = "A"
print(type(of:a)) // String
```

- 원하는 타입으로 추론되지 않을 수 있음. (`"A" -> String으로 취급`)
- 초기값이 없는 경우 타입 추론을 사용할 수 없음.
- 컴파일러가 타입 추론을 하는 과정에서, 타입을 명시한 것 보다 시간이 좀 더 걸린다.