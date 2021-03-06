# 대구가톨릭대학교 OJ 프론트 엔드 (VER 0.2)

## 개발자
+ 한재덕

## Features

+ 웹팩3(Webpack3)를 활용한 다중 페이지
+ 쉽게 사용할 수 있는 코드 에디터
+ E-chart를 활용한 시각화 모듈
+ 사용자 친화적인 명령어 기능

## Get Started

노드 JS **v6.11** 버전이 설치가 되어 있어야 합니다.

```bash
# NPM을 이용해 인스톨을 수행합니다.
npm install

# 웹팩 3 DLL 레퍼런스를 이용해 빌드 시간을 절약합니다.
# 기본적으로 이 명령어는 build/webpack.dll.conf.js 내부의 패키지를 업그레이드하지 않았다면 한 번만 수행하면 됩니다.
NODE_ENV=development npm run build:dll

# 개발 서버에서 백 엔드 서버에 프록시 테이블을 설정합니다.
export TARGET=http://Your-backend

# 기본적으로 8080 포트에서 프론트 서버가 생성됩니다.
npm run dev
```

## Browser Support

Modern browsers and Internet Explorer 10+.

## LICENSE

[MIT](http://opensource.org/licenses/MIT)
