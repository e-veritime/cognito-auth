# cognito-kakao-naver-auth

## flow

### kakao

![kakao_login](./kakao_login.png)

### naver

![naver_login](./naver_login.png)

## Getting Started

### Prerequisites

global install

- node
- ts-node
- typescrpt
- nodemon

### start

1. set .env

```bash
cp .env.example .env
```

2. local development

```bash
npm i
npm run start
```

## Reference

- https://medium.com/@parkopp/amazon-cognito%EB%A1%9C-%EC%8B%9C%EB%8F%84-%ED%95%B4-%EB%B3%B4%EB%8A%94-%EB%8B%A4%EC%96%91%ED%95%9C-%EB%B0%A9%EB%B2%95%EC%9D%98-%EC%86%8C%EC%85%9C-%EB%A1%9C%EA%B7%B8%EC%9D%B8-f81fa00b8c2e
- https://github.com/santiq/bulletproof-nodejs

## issue

- ci/cd 는 프로젝트 중단하면서 disable
- enable 시 github secret setting 필요
- chatting gitops repo: https://github.com/e-veritime/gitops/tree/main/dev/kakao-auth
