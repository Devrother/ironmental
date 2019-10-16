# Contribute

## PR 규칙

`question`, `keywords`, `tags`, `answer` 란에 알맞은 내용을 기입하여 PR 날려주세요.

> `answer` 란에는 마크다운 문법으로 작성해주세요

## example

### question

webpack이란 무엇인가요?

### keywords

["webpack"]

### tags

["web", "javascript"]

### answer

``` markdown
**Javascript module bundler** 이다.

> module bundler: 여러개의 나누어져 있는 파일들을 하나의 파일로 만들어주는 라이브러리

## 웹팩 사용의 이점

* 브라우저 로딩 속도 증가
	* 여러 개의 자바스크립트 코드를 압축해서 하나의 파일로 가져올 수 있게 한다.
	* 서버와 여러번 통신하는 비효율성을 해결한다.

* 최신 문법 지원
	* 여러가지 loader를 통해 브라우저에게 코드를 전달한다.
		* ex) babel-loader, css-loader, sass-loader
	* 그로 인해, ES6+ 문법을 지원하지 않는 구형 브라우저에도 코드가 작동될 수 있게 한다.

## Reference

* [Webpack 이 뭐지?](https://velog.io/@ground4ekd/Webpack)

```

