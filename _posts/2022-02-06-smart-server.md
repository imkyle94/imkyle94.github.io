---
title: Smart Server
layout: post
post-image: https://kylesportfolio.s3.amazonaws.com/smartserver.jpg
description: 블록체인 기반 거래사이트

tags:
    - Kyle
    - BlockChain
    - Smart Server
---

Github Link : <a href="https://github.com/pjh94/SmartServer-ws-">Go GITHUB</a>

---

# NFT 음악 등록 및 거래 플랫폼

## 프로젝트 간단 설명

-   프로젝트 명 : 블록체인 기반 거래사이트
-   프로젝트 팀명 : 개인 작업
-   개발 기간 : 2022-01-20 ~ 2022-02-06

## 구현 기술

-   Javascript TCP/IP 통신 .net 활용한 P2P 소켓 통신 구현 및 WebSocket 프로토콜로 확장
-   Javascript event 모듈 및 콜백 처리를 통한 이벤트 발생자 구현
-   블록 및 트랜잭션 데이터 구조화 및 채굴 진행

## 사용 라이브러리

다음의 라이브러리들이 프로젝트에 사용되었습니다<br>

-   [NextJS](https://nextjs.org/){:target="\_blank"} 서버사이드렌더링(SSR)을 위해 사용했습니다.
-   [React-Query](https://react-query.tanstack.com/){:target="\_blank"} Server Data Fecthing 및 상태관리를 위해 사용했습니다.
-   [MUI](https://mui.com/){:target="\_blank"} View Grid 작업을 위해 사용했습니다.

## Requirements

-   [NodeJS](https://nodejs.org/ko/){:target="\_blank"} 자바스크립트 언어로 작성되었습니다. 프로젝트 구동 시 자바스크립트 런타임 환경인 NodeJS를 이용합니다. **버전관리의 용이성을 위해 아래에 기술한 NVM 사용을 권장합니다.** v16으로 작성되었습니다.
-   [NVM](https://github.com/nvm-sh/nvm){:target="\_blank"} Node Version Manager Github입니다. 본인 환경에 맞게 설치하실 수 있습니다.
-   [node-gyp](https://github.com/nodejs/node-gyp){:target="\_blank"} Node.js native addon build tool입니다. 노드 버전에 따라 설치가 필요할 수 있습니다.
-   [Metamask](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=ko){:target="\_blank"} 이더리움(Ethereum) 개인지갑을 편리하고 안전하게 관리할 수 있는 구글 확장프로그램입니다.
-   [Chrome](https://www.google.co.kr/chrome/?brand=YTUH&gclid=Cj0KCQjwpcOTBhCZARIsAEAYLuVysegwe_b6xHTfek9Q9_utUWYB4B28jNiiQDwDYr9cGL5wo9bkyHAaAoaJEALw_wcB&gclsrc=aw.ds){:target="\_blank"} 메타마스크 사용을 위해 크롬 설치가 필요합니다.
-   [Truffle](https://trufflesuite.com/){:target="\_blank"} 블록체인 테스트 환경을 트러플로 구성하였습니다.
-   [Ganache](https://trufflesuite.com/ganache/){:target="\_blank"} 트러플 GUI인 가나슈를 사용하였습니다.
-   [S3](https://aws.amazon.com/ko/s3/){:target="\_blank"} 이미지 저장에 AWS S3를 사용하였습니다.

## After Installing the Requirements you can follow these guides:

### 전역 모듈 설치

### yarn & truffle installation

> #### npm i -g yarn
>
> #### npm i -g truffle

**※주의※ 노드의 버전에 따라 설치 방식이 다를 수 있습니다.**

### 모듈 설치

package.json에서 모듈 버전 확인이 가능합니다.<br>

> ### // with yarn
>
> #### yarn
>
> ### // with npm
>
> #### npm i
>
> **go inside the directory**
>
> #### cd client
>
> #### yarn or npm i again

### Changing into the Directory

**We have to go inside the directory:**<br>

> #### `cd client`

프로젝트 구동을 위해 클라이언트 폴더로 들어가주세요.

### 프로젝트 실행

> #### yarn run start or npm run start

---

### 프로젝트 설명
