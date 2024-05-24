# react-deep-dive
[📚 모던 리액트 Deep Dive](https://wikibook.co.kr/react-deep-dive/)  
[🔗 예제 코드 Git](https://github.com/wikibook/react-deep-dive-example)


<!-- FOLDER_STRUCTURE_START -->
- 00 들어가며
    - [0.1 왜 리액트인가?.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/00%20%EB%93%A4%EC%96%B4%EA%B0%80%EB%A9%B0/0.1%20%EC%99%9C%20%EB%A6%AC%EC%95%A1%ED%8A%B8%EC%9D%B8%EA%B0%80%3F.md)
    - [0.2 리액트의 역사.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/00%20%EB%93%A4%EC%96%B4%EA%B0%80%EB%A9%B0/0.2%20%EB%A6%AC%EC%95%A1%ED%8A%B8%EC%9D%98%20%EC%97%AD%EC%82%AC.md)
- 01 리액트 개발을 위해 꼭 알아야 할 자바스크립트
    - [1.1 자바스크립트의 동등 비교.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/01%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EA%B0%9C%EB%B0%9C%EC%9D%84%20%EC%9C%84%ED%95%B4%20%EA%BC%AD%20%EC%95%8C%EC%95%84%EC%95%BC%20%ED%95%A0%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8/1.1%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%EC%9D%98%20%EB%8F%99%EB%93%B1%20%EB%B9%84%EA%B5%90.md)
    - [1.2 함수.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/01%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EA%B0%9C%EB%B0%9C%EC%9D%84%20%EC%9C%84%ED%95%B4%20%EA%BC%AD%20%EC%95%8C%EC%95%84%EC%95%BC%20%ED%95%A0%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8/1.2%20%ED%95%A8%EC%88%98.md)
    - [1.3 클래스.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/01%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EA%B0%9C%EB%B0%9C%EC%9D%84%20%EC%9C%84%ED%95%B4%20%EA%BC%AD%20%EC%95%8C%EC%95%84%EC%95%BC%20%ED%95%A0%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8/1.3%20%ED%81%B4%EB%9E%98%EC%8A%A4.md)
    - [1.4 클로저.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/01%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EA%B0%9C%EB%B0%9C%EC%9D%84%20%EC%9C%84%ED%95%B4%20%EA%BC%AD%20%EC%95%8C%EC%95%84%EC%95%BC%20%ED%95%A0%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8/1.4%20%ED%81%B4%EB%A1%9C%EC%A0%80.md)
    - [1.5 이벤트 루프와 비동기 통신의 이해.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/01%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EA%B0%9C%EB%B0%9C%EC%9D%84%20%EC%9C%84%ED%95%B4%20%EA%BC%AD%20%EC%95%8C%EC%95%84%EC%95%BC%20%ED%95%A0%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8/1.5%20%EC%9D%B4%EB%B2%A4%ED%8A%B8%20%EB%A3%A8%ED%94%84%EC%99%80%20%EB%B9%84%EB%8F%99%EA%B8%B0%20%ED%86%B5%EC%8B%A0%EC%9D%98%20%EC%9D%B4%ED%95%B4.md)
    - [1.6 리액트에서 자주 사용하는 자바스크립트 문법.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/01%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EA%B0%9C%EB%B0%9C%EC%9D%84%20%EC%9C%84%ED%95%B4%20%EA%BC%AD%20%EC%95%8C%EC%95%84%EC%95%BC%20%ED%95%A0%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8/1.6%20%EB%A6%AC%EC%95%A1%ED%8A%B8%EC%97%90%EC%84%9C%20%EC%9E%90%EC%A3%BC%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%8A%94%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8%20%EB%AC%B8%EB%B2%95.md)
    - [1.7 선택이 아닌 필수, 타입스크립트.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/01%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EA%B0%9C%EB%B0%9C%EC%9D%84%20%EC%9C%84%ED%95%B4%20%EA%BC%AD%20%EC%95%8C%EC%95%84%EC%95%BC%20%ED%95%A0%20%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8/1.7%20%EC%84%A0%ED%83%9D%EC%9D%B4%20%EC%95%84%EB%8B%8C%20%ED%95%84%EC%88%98%2C%20%ED%83%80%EC%9E%85%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8.md)
- 02 리액트 핵심 요소 깊게 살펴보기
    - [2.1 JSX란?.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/02%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%ED%95%B5%EC%8B%AC%20%EC%9A%94%EC%86%8C%20%EA%B9%8A%EA%B2%8C%20%EC%82%B4%ED%8E%B4%EB%B3%B4%EA%B8%B0/2.1%20JSX%EB%9E%80%3F.md)
    - [2.2 가상 DOM과 리액트 파이버.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/02%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%ED%95%B5%EC%8B%AC%20%EC%9A%94%EC%86%8C%20%EA%B9%8A%EA%B2%8C%20%EC%82%B4%ED%8E%B4%EB%B3%B4%EA%B8%B0/2.2%20%EA%B0%80%EC%83%81%20DOM%EA%B3%BC%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%ED%8C%8C%EC%9D%B4%EB%B2%84.md)
    - [2.3 클래스 컴포넌트와 함수 컴포넌트.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/02%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%ED%95%B5%EC%8B%AC%20%EC%9A%94%EC%86%8C%20%EA%B9%8A%EA%B2%8C%20%EC%82%B4%ED%8E%B4%EB%B3%B4%EA%B8%B0/2.3%20%ED%81%B4%EB%9E%98%EC%8A%A4%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8%EC%99%80%20%ED%95%A8%EC%88%98%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8.md)
    - [2.4 렌더링은 어떻게 일어나는가?.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/02%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%ED%95%B5%EC%8B%AC%20%EC%9A%94%EC%86%8C%20%EA%B9%8A%EA%B2%8C%20%EC%82%B4%ED%8E%B4%EB%B3%B4%EA%B8%B0/2.4%20%EB%A0%8C%EB%8D%94%EB%A7%81%EC%9D%80%20%EC%96%B4%EB%96%BB%EA%B2%8C%20%EC%9D%BC%EC%96%B4%EB%82%98%EB%8A%94%EA%B0%80%3F.md)
    - [2.5 컴포넌트와 함수의 무거운 연산을 기억해 두는 메모이제이션.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/02%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%ED%95%B5%EC%8B%AC%20%EC%9A%94%EC%86%8C%20%EA%B9%8A%EA%B2%8C%20%EC%82%B4%ED%8E%B4%EB%B3%B4%EA%B8%B0/2.5%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8%EC%99%80%20%ED%95%A8%EC%88%98%EC%9D%98%20%EB%AC%B4%EA%B1%B0%EC%9A%B4%20%EC%97%B0%EC%82%B0%EC%9D%84%20%EA%B8%B0%EC%96%B5%ED%95%B4%20%EB%91%90%EB%8A%94%20%EB%A9%94%EB%AA%A8%EC%9D%B4%EC%A0%9C%EC%9D%B4%EC%85%98.md)
- 03 리액트 훅 깊게 살펴보기
    - [3.1 리액트의 모든 훅 파헤치기.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/03%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%ED%9B%85%20%EA%B9%8A%EA%B2%8C%20%EC%82%B4%ED%8E%B4%EB%B3%B4%EA%B8%B0/3.1%20%EB%A6%AC%EC%95%A1%ED%8A%B8%EC%9D%98%20%EB%AA%A8%EB%93%A0%20%ED%9B%85%20%ED%8C%8C%ED%97%A4%EC%B9%98%EA%B8%B0.md)

<!-- FOLDER_STRUCTURE_END -->