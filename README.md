# Asserlang 어쩔랭

이 프로젝트는 개발 중인 프로젝트입니다.

유행어를 본따 만든 [엄랭](https://github.com/rycont/umjunsik-lang)과 [몰랭](https://github.com/ArpaAP/mollang) 같은 언어들에 영감을 받아 만들게 되었습니다.

코드가 다소 이상하다고 느껴지신다면 언제든 PR로 리펙토링 해주시면 감사하겠습니다. 💻
그 외에도 PR은 환영입니다! 🙋

# 문법

무조건 코드의 시작과 끝에는 각각 '어쩔티비'와 '저쩔티비'가 포함되어야 합니다.

## 연산자

```
어
```

> `+`1을 의미합니다.

```
쩔
```

> `-`1을 의미합니다.

## 변수

#### 선언

```
어쩔티비
ㅇㅉ ㅇㅉㅇㅉ 어어
저쩔티비
```

> 변수 "ㅇㅉㅇㅉ"을 선언과 동시에 2라는 값으로 초기화 합니다.
>
> - 키워드는 변수 이름이 될 수 없습니다.
>   - 잘못된 예) ㅇㅉ ㅇㅉ 어어
> - 빈 변수 선언 시 0이 할당됩니다.
>   - 예) ㅇㅉ ㅇㅉㅇㅉ

#### 할당

```
어쩔티비
ㅇㅉ ㅇㅉㅇㅉ 어어어
ㅈㅉ ㅇㅉㅇㅉ 어어
저쩔티비
```

> 변수 "ㅇㅉㅇㅉ"을 선언하며 동시에 3이라는 값으로 초기화 합니다.
> 변수 "ㅇㅉㅇㅉ"에 2라는 값을 할당 해줍니다.

## 입출력

#### 입력

```

어쩔티비
티비
저쩔티비

```

> 사용자에게 입력을 받습니다

```

어쩔티비
ㅇㅉ ㅋㅋ 티비
저쩔티비

```

> 변수 "ㅋㅋ"에 입력값을 저장합니다.

#### 출력

```

어쩔티비
ㅇㅉ ㅇㅇㅈ 어어어어어
어쩔 ㅇㅇㅈ
저쩔티비

```

> ㅇㅇㅈ 변수를 출력합니다

```

어쩔티비
어쩔 티비
저쩔티비

```

> 입력값을 출력합니다

#### 실행

터미널 및 콘솔에 아래 코드를 순서대로 입력하세요.
최신 버전의 git과 node.js가 설치되어 있어야 합니다.

```
$ git clone http://github.com/assertive-lang/asserlang
$ cd asserlang
$ npm i
$ tsc
$ node dist/index.js 파일명
```

#### 에러

- 아무것도 모르죠?
  시작과 끝에 "어쩔티비"와 "저쩔티비"를 포함하지 않은 경우 발생하는 에러
- 어쩔변수
  변수에 관련된 구문에서 발생한 에러
- 어쩔파일
  파일을 제대로 불러오지 못한 경우 발생하는 에러

~~저쩔티비~~