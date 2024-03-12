# weatherapi
프로젝트 소개
React를 사용한 간단한 날씨 앱입니다. OpenWeatherMap API를 통해 실시간 날씨 정보를 가져오며, 현재 위치 또는 미리 정의된 도시에서 날씨를 확인할 수 있습니다.
기능
현재 위치의 날씨 정보 조회
미리 정의된 도시 목록에서 날씨 정보 조회
로딩 중에는 Spinner를 표시하여 사용자에게 로딩 상태를 알림
날씨 정보에 따라 다양한 이미지 표시
프로젝트 구조
src/components: React 컴포넌트들이 위치하는 폴더WeatherBox.js: 날씨 정보를 표시하는 컴포넌트
WeatherButton.js: 현재 위치 및 도시 버튼을 표시하는 컴포넌트
src/styles: 스타일 시트가 위치하는 폴더reset.css: 기본 스타일 초기화를 위한 CSS 파일
App.css: 앱의 전반적인 스타일을 정의하는 CSS 파일
App.js: 애플리케이션의 메인 컴포넌트와 로직이 구현된 파일
사용된 기술 및 라이브러리
React
OpenWeatherMap API
react-spinners: 로딩 중에 표시되는 Spinner를 구현하기 위한 라이브러리
