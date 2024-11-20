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
    - [3.2 사용자 정의 훅과 고차 컴포넌트 중 무엇을 써야 할까?.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/03%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%ED%9B%85%20%EA%B9%8A%EA%B2%8C%20%EC%82%B4%ED%8E%B4%EB%B3%B4%EA%B8%B0/3.2%20%EC%82%AC%EC%9A%A9%EC%9E%90%20%EC%A0%95%EC%9D%98%20%ED%9B%85%EA%B3%BC%20%EA%B3%A0%EC%B0%A8%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8%20%EC%A4%91%20%EB%AC%B4%EC%97%87%EC%9D%84%20%EC%8D%A8%EC%95%BC%20%ED%95%A0%EA%B9%8C%3F.md)
- 04 서버 사이드 렌더링
    - [4.1 서버 사이드 렌더링이란?.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/04%20%EC%84%9C%EB%B2%84%20%EC%82%AC%EC%9D%B4%EB%93%9C%20%EB%A0%8C%EB%8D%94%EB%A7%81/4.1%20%EC%84%9C%EB%B2%84%20%EC%82%AC%EC%9D%B4%EB%93%9C%20%EB%A0%8C%EB%8D%94%EB%A7%81%EC%9D%B4%EB%9E%80%3F.md)
    - [4.2 서버 사이드 렌더링을 위한 리액트 API 살펴보기.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/04%20%EC%84%9C%EB%B2%84%20%EC%82%AC%EC%9D%B4%EB%93%9C%20%EB%A0%8C%EB%8D%94%EB%A7%81/4.2%20%EC%84%9C%EB%B2%84%20%EC%82%AC%EC%9D%B4%EB%93%9C%20%EB%A0%8C%EB%8D%94%EB%A7%81%EC%9D%84%20%EC%9C%84%ED%95%9C%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20API%20%EC%82%B4%ED%8E%B4%EB%B3%B4%EA%B8%B0.md)
    - [4.3 Next.js 톺아보기.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/04%20%EC%84%9C%EB%B2%84%20%EC%82%AC%EC%9D%B4%EB%93%9C%20%EB%A0%8C%EB%8D%94%EB%A7%81/4.3%20Next.js%20%ED%86%BA%EC%95%84%EB%B3%B4%EA%B8%B0.md)
- 05 리액트와 상태 관리 라이브러리
    - [5.1 상태 관리는 왜 필요한가?.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/05%20%EB%A6%AC%EC%95%A1%ED%8A%B8%EC%99%80%20%EC%83%81%ED%83%9C%20%EA%B4%80%EB%A6%AC%20%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC/5.1%20%EC%83%81%ED%83%9C%20%EA%B4%80%EB%A6%AC%EB%8A%94%20%EC%99%9C%20%ED%95%84%EC%9A%94%ED%95%9C%EA%B0%80%3F.md)
    - [5.2 리액트 훅으로 시작하는 상태 관리.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/05%20%EB%A6%AC%EC%95%A1%ED%8A%B8%EC%99%80%20%EC%83%81%ED%83%9C%20%EA%B4%80%EB%A6%AC%20%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC/5.2%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%ED%9B%85%EC%9C%BC%EB%A1%9C%20%EC%8B%9C%EC%9E%91%ED%95%98%EB%8A%94%20%EC%83%81%ED%83%9C%20%EA%B4%80%EB%A6%AC.md)
- 06 리액트 개발 도구로 디버깅하기
    - [6.3 리액트 개발 도구 활용하기.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/06%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EA%B0%9C%EB%B0%9C%20%EB%8F%84%EA%B5%AC%EB%A1%9C%20%EB%94%94%EB%B2%84%EA%B9%85%ED%95%98%EA%B8%B0/6.3%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EA%B0%9C%EB%B0%9C%20%EB%8F%84%EA%B5%AC%20%ED%99%9C%EC%9A%A9%ED%95%98%EA%B8%B0.md)
- 07 크롬 개발자 도구를 활용한 애플리케이션 분석
    - [07장 크롬 개발자 도구를 활용한 애플리케이션 분석.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/07%20%ED%81%AC%EB%A1%AC%20%EA%B0%9C%EB%B0%9C%EC%9E%90%20%EB%8F%84%EA%B5%AC%EB%A5%BC%20%ED%99%9C%EC%9A%A9%ED%95%9C%20%EC%95%A0%ED%94%8C%EB%A6%AC%EC%BC%80%EC%9D%B4%EC%85%98%20%EB%B6%84%EC%84%9D/07%EC%9E%A5%20%ED%81%AC%EB%A1%AC%20%EA%B0%9C%EB%B0%9C%EC%9E%90%20%EB%8F%84%EA%B5%AC%EB%A5%BC%20%ED%99%9C%EC%9A%A9%ED%95%9C%20%EC%95%A0%ED%94%8C%EB%A6%AC%EC%BC%80%EC%9D%B4%EC%85%98%20%EB%B6%84%EC%84%9D.md)
- 08 좋은 리액트 코드 작성을 위한 환경 구축하기
    - [8.1 좋은 리액트 코드 작성을 위한 환경 구축하기.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/08%20%EC%A2%8B%EC%9D%80%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EC%BD%94%EB%93%9C%20%EC%9E%91%EC%84%B1%EC%9D%84%20%EC%9C%84%ED%95%9C%20%ED%99%98%EA%B2%BD%20%EA%B5%AC%EC%B6%95%ED%95%98%EA%B8%B0/8.1%20%EC%A2%8B%EC%9D%80%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EC%BD%94%EB%93%9C%20%EC%9E%91%EC%84%B1%EC%9D%84%20%EC%9C%84%ED%95%9C%20%ED%99%98%EA%B2%BD%20%EA%B5%AC%EC%B6%95%ED%95%98%EA%B8%B0.md)
    - [8.2 리액트 팀이 권장하는 리액트 테스트 라이브러리.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/08%20%EC%A2%8B%EC%9D%80%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EC%BD%94%EB%93%9C%20%EC%9E%91%EC%84%B1%EC%9D%84%20%EC%9C%84%ED%95%9C%20%ED%99%98%EA%B2%BD%20%EA%B5%AC%EC%B6%95%ED%95%98%EA%B8%B0/8.2%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%ED%8C%80%EC%9D%B4%20%EA%B6%8C%EC%9E%A5%ED%95%98%EB%8A%94%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%ED%85%8C%EC%8A%A4%ED%8A%B8%20%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC.md)
- 09 모던 리액트 개발 도구로 개발 및 배포 환경 구축하기
    - [9.1 Next.js로 리액트 개발 환경 구축하기.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/09%20%EB%AA%A8%EB%8D%98%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EA%B0%9C%EB%B0%9C%20%EB%8F%84%EA%B5%AC%EB%A1%9C%20%EA%B0%9C%EB%B0%9C%20%EB%B0%8F%20%EB%B0%B0%ED%8F%AC%20%ED%99%98%EA%B2%BD%20%EA%B5%AC%EC%B6%95%ED%95%98%EA%B8%B0/9.1%20Next.js%EB%A1%9C%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EA%B0%9C%EB%B0%9C%20%ED%99%98%EA%B2%BD%20%EA%B5%AC%EC%B6%95%ED%95%98%EA%B8%B0.md)
    - [9.2 깃허브 100% 활용하기.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/09%20%EB%AA%A8%EB%8D%98%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EA%B0%9C%EB%B0%9C%20%EB%8F%84%EA%B5%AC%EB%A1%9C%20%EA%B0%9C%EB%B0%9C%20%EB%B0%8F%20%EB%B0%B0%ED%8F%AC%20%ED%99%98%EA%B2%BD%20%EA%B5%AC%EC%B6%95%ED%95%98%EA%B8%B0/9.2%20%EA%B9%83%ED%97%88%EB%B8%8C%20100%25%20%ED%99%9C%EC%9A%A9%ED%95%98%EA%B8%B0.md)
    - [9.3 리액트 애플리케이션 배포하기.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/09%20%EB%AA%A8%EB%8D%98%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EA%B0%9C%EB%B0%9C%20%EB%8F%84%EA%B5%AC%EB%A1%9C%20%EA%B0%9C%EB%B0%9C%20%EB%B0%8F%20%EB%B0%B0%ED%8F%AC%20%ED%99%98%EA%B2%BD%20%EA%B5%AC%EC%B6%95%ED%95%98%EA%B8%B0/9.3%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EC%95%A0%ED%94%8C%EB%A6%AC%EC%BC%80%EC%9D%B4%EC%85%98%20%EB%B0%B0%ED%8F%AC%ED%95%98%EA%B8%B0.md)
    - [9.4 리액트 애플리케이션 도커라이즈하기.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/09%20%EB%AA%A8%EB%8D%98%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EA%B0%9C%EB%B0%9C%20%EB%8F%84%EA%B5%AC%EB%A1%9C%20%EA%B0%9C%EB%B0%9C%20%EB%B0%8F%20%EB%B0%B0%ED%8F%AC%20%ED%99%98%EA%B2%BD%20%EA%B5%AC%EC%B6%95%ED%95%98%EA%B8%B0/9.4%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EC%95%A0%ED%94%8C%EB%A6%AC%EC%BC%80%EC%9D%B4%EC%85%98%20%EB%8F%84%EC%BB%A4%EB%9D%BC%EC%9D%B4%EC%A6%88%ED%95%98%EA%B8%B0.md)
- 10 리액트 17과 18의 변경 사항 살펴보기
    - [10.1 리액트 17 버전 살펴보기.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/10%20%EB%A6%AC%EC%95%A1%ED%8A%B8%2017%EA%B3%BC%2018%EC%9D%98%20%EB%B3%80%EA%B2%BD%20%EC%82%AC%ED%95%AD%20%EC%82%B4%ED%8E%B4%EB%B3%B4%EA%B8%B0/10.1%20%EB%A6%AC%EC%95%A1%ED%8A%B8%2017%20%EB%B2%84%EC%A0%84%20%EC%82%B4%ED%8E%B4%EB%B3%B4%EA%B8%B0.md)
    - [10.2 리액트 18 버전 살펴보기.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/10%20%EB%A6%AC%EC%95%A1%ED%8A%B8%2017%EA%B3%BC%2018%EC%9D%98%20%EB%B3%80%EA%B2%BD%20%EC%82%AC%ED%95%AD%20%EC%82%B4%ED%8E%B4%EB%B3%B4%EA%B8%B0/10.2%20%EB%A6%AC%EC%95%A1%ED%8A%B8%2018%20%EB%B2%84%EC%A0%84%20%EC%82%B4%ED%8E%B4%EB%B3%B4%EA%B8%B0.md)
- 11 Next.js 13과 리액트 18
    - [11.1 app 디렉터리의 등장.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/11%20Next.js%2013%EA%B3%BC%20%EB%A6%AC%EC%95%A1%ED%8A%B8%2018/11.1%20app%20%EB%94%94%EB%A0%89%ED%84%B0%EB%A6%AC%EC%9D%98%20%EB%93%B1%EC%9E%A5.md)
    - [11.2 리액트 서버 컴포넌트.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/11%20Next.js%2013%EA%B3%BC%20%EB%A6%AC%EC%95%A1%ED%8A%B8%2018/11.2%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EC%84%9C%EB%B2%84%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8.md)
    - [11.3 Next.js에서의 리액트 서버 컴포넌트.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/11%20Next.js%2013%EA%B3%BC%20%EB%A6%AC%EC%95%A1%ED%8A%B8%2018/11.3%20Next.js%EC%97%90%EC%84%9C%EC%9D%98%20%EB%A6%AC%EC%95%A1%ED%8A%B8%20%EC%84%9C%EB%B2%84%20%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8.md)
    - [11.4 웹팩의 대항마, 터보팩의 등장(beta).md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/11%20Next.js%2013%EA%B3%BC%20%EB%A6%AC%EC%95%A1%ED%8A%B8%2018/11.4%20%EC%9B%B9%ED%8C%A9%EC%9D%98%20%EB%8C%80%ED%95%AD%EB%A7%88%2C%20%ED%84%B0%EB%B3%B4%ED%8C%A9%EC%9D%98%20%EB%93%B1%EC%9E%A5%28beta%29.md)
    - [11.5 서버 액션(alpha).md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/11%20Next.js%2013%EA%B3%BC%20%EB%A6%AC%EC%95%A1%ED%8A%B8%2018/11.5%20%EC%84%9C%EB%B2%84%20%EC%95%A1%EC%85%98%28alpha%29.md)
    - [11.6 그 밖의 변화.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/11%20Next.js%2013%EA%B3%BC%20%EB%A6%AC%EC%95%A1%ED%8A%B8%2018/11.6%20%EA%B7%B8%20%EB%B0%96%EC%9D%98%20%EB%B3%80%ED%99%94.md)
- 12 모든 웹 개발자가 관심을 가져야 할 핵심 웹 지표
    - [12.1~3 웹사이트와 성능 | 핵심 웹 지표란? | 최대 콘텐츠풀 페인트(LCP).md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/12%20%EB%AA%A8%EB%93%A0%20%EC%9B%B9%20%EA%B0%9C%EB%B0%9C%EC%9E%90%EA%B0%80%20%EA%B4%80%EC%8B%AC%EC%9D%84%20%EA%B0%80%EC%A0%B8%EC%95%BC%20%ED%95%A0%20%ED%95%B5%EC%8B%AC%20%EC%9B%B9%20%EC%A7%80%ED%91%9C/12.1~3%20%EC%9B%B9%EC%82%AC%EC%9D%B4%ED%8A%B8%EC%99%80%20%EC%84%B1%EB%8A%A5%20%7C%20%ED%95%B5%EC%8B%AC%20%EC%9B%B9%20%EC%A7%80%ED%91%9C%EB%9E%80%3F%20%7C%20%EC%B5%9C%EB%8C%80%20%EC%BD%98%ED%85%90%EC%B8%A0%ED%92%80%20%ED%8E%98%EC%9D%B8%ED%8A%B8%28LCP%29.md)
    - [12.4 최소 입력 지연(FID).md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/12%20%EB%AA%A8%EB%93%A0%20%EC%9B%B9%20%EA%B0%9C%EB%B0%9C%EC%9E%90%EA%B0%80%20%EA%B4%80%EC%8B%AC%EC%9D%84%20%EA%B0%80%EC%A0%B8%EC%95%BC%20%ED%95%A0%20%ED%95%B5%EC%8B%AC%20%EC%9B%B9%20%EC%A7%80%ED%91%9C/12.4%20%EC%B5%9C%EC%86%8C%20%EC%9E%85%EB%A0%A5%20%EC%A7%80%EC%97%B0%28FID%29.md)
    - [12.5~6 누적 레이아웃 이동(CLS) | 정리.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/12%20%EB%AA%A8%EB%93%A0%20%EC%9B%B9%20%EA%B0%9C%EB%B0%9C%EC%9E%90%EA%B0%80%20%EA%B4%80%EC%8B%AC%EC%9D%84%20%EA%B0%80%EC%A0%B8%EC%95%BC%20%ED%95%A0%20%ED%95%B5%EC%8B%AC%20%EC%9B%B9%20%EC%A7%80%ED%91%9C/12.5~6%20%EB%88%84%EC%A0%81%20%EB%A0%88%EC%9D%B4%EC%95%84%EC%9B%83%20%EC%9D%B4%EB%8F%99%28CLS%29%20%7C%20%EC%A0%95%EB%A6%AC.md)
- 13 웹페이지의 성능을 측정하는 다양한 방법
    - [13.1 애플리케이션에서 확인하기.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/13%20%EC%9B%B9%ED%8E%98%EC%9D%B4%EC%A7%80%EC%9D%98%20%EC%84%B1%EB%8A%A5%EC%9D%84%20%EC%B8%A1%EC%A0%95%ED%95%98%EB%8A%94%20%EB%8B%A4%EC%96%91%ED%95%9C%20%EB%B0%A9%EB%B2%95/13.1%20%EC%95%A0%ED%94%8C%EB%A6%AC%EC%BC%80%EC%9D%B4%EC%85%98%EC%97%90%EC%84%9C%20%ED%99%95%EC%9D%B8%ED%95%98%EA%B8%B0.md)
    - [13.2 구글 라이트하우스.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/13%20%EC%9B%B9%ED%8E%98%EC%9D%B4%EC%A7%80%EC%9D%98%20%EC%84%B1%EB%8A%A5%EC%9D%84%20%EC%B8%A1%EC%A0%95%ED%95%98%EB%8A%94%20%EB%8B%A4%EC%96%91%ED%95%9C%20%EB%B0%A9%EB%B2%95/13.2%20%EA%B5%AC%EA%B8%80%20%EB%9D%BC%EC%9D%B4%ED%8A%B8%ED%95%98%EC%9A%B0%EC%8A%A4.md)
    - [13.3 WebPageTest.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/13%20%EC%9B%B9%ED%8E%98%EC%9D%B4%EC%A7%80%EC%9D%98%20%EC%84%B1%EB%8A%A5%EC%9D%84%20%EC%B8%A1%EC%A0%95%ED%95%98%EB%8A%94%20%EB%8B%A4%EC%96%91%ED%95%9C%20%EB%B0%A9%EB%B2%95/13.3%20WebPageTest.md)
    - [13.4 크롬 개발자 도구.md](https://github.com/Jungle-JavaScript-Study/react-deep-dive/blob/main/13%20%EC%9B%B9%ED%8E%98%EC%9D%B4%EC%A7%80%EC%9D%98%20%EC%84%B1%EB%8A%A5%EC%9D%84%20%EC%B8%A1%EC%A0%95%ED%95%98%EB%8A%94%20%EB%8B%A4%EC%96%91%ED%95%9C%20%EB%B0%A9%EB%B2%95/13.4%20%ED%81%AC%EB%A1%AC%20%EA%B0%9C%EB%B0%9C%EC%9E%90%20%EB%8F%84%EA%B5%AC.md)

<!-- FOLDER_STRUCTURE_END -->