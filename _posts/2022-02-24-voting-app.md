---
title: Smart Contract - Voting App
layout: post
post-image: https://kylesportfolio.s3.amazonaws.com/voting.png
description: 스마트 컨트랙트 - 투표 앱

tags:
  - Kyle
  - BlockChain
  - SmartContract
  - Voting
---

Github Link : <a href="https://github.com/pjh94/SmartContract-VotingApp">Go GITHUB</a><br/>
Vite Build Tool로 코드 리팩토링 진행하는 도중 Client에 대해 꼭 정리하고 싶은 주제가 생겨 이번 프로젝트는 컨트랙트 코드만 제공합니다.
<br/>
이에 대한 자세한 글은 벨로그 글을 제공합니다.
<a href="https://velog.io/@andy3638/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%EB%A5%BC-%EC%A7%84%ED%96%89%ED%95%98%EB%A9%B0-%EB%8A%90%EA%BC%88%EB%8D%98-%EA%B2%83">Velog</a>

---

# 스마트 컨트랙트 - 투표 앱

## 프로젝트 간단 설명

- 프로젝트 명 : 스마트 컨트랙트 - 투표 앱
- 프로젝트 팀명 : 개인작업
- 개발 기간 : 2022-02-21 ~ 2022-02-24

## 프로젝트 절차

- ~ 2/21 : 투표기능
  후보자 등록 2 .참여자 투표
  payable금액 소모
- ~ 2/21 : 거래 및 시각화
  당선시각화
  등록된 후보 이미지 출력
- ~ 2/23 : 최종결과물 피드백 및 발표 준비

## 구현 기능

- Candidate
- Voting

## 구현 기술

- Solidity Smart Contract 작성 및 구현
- Truffle, Ganache 사용한 Smart Contract 테스트 환경 구성
- web3.js 개발

## Requirements

- [NodeJS](https://nodejs.org/ko/){:target="\_blank"} 자바스크립트 언어로 작성되었습니다. 프로젝트 구동 시 자바스크립트 런타임 환경인 NodeJS를 이용합니다. **버전관리의 용이성을 위해 아래에 기술한 NVM 사용을 권장합니다.** v16으로 작성되었습니다.
- [NVM](https://github.com/nvm-sh/nvm){:target="\_blank"} Node Version Manager Github입니다. 본인 환경에 맞게 설치하실 수 있습니다.
- [node-gyp](https://github.com/nodejs/node-gyp){:target="\_blank"} Node.js native addon build tool입니다. 노드 버전에 따라 설치가 필요할 수 있습니다.
- [Metamask](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=ko){:target="\_blank"} 이더리움(Ethereum) 개인지갑을 편리하고 안전하게 관리할 수 있는 구글 확장프로그램입니다.
- [Chrome](https://www.google.co.kr/chrome/?brand=YTUH&gclid=Cj0KCQjwpcOTBhCZARIsAEAYLuVysegwe_b6xHTfek9Q9_utUWYB4B28jNiiQDwDYr9cGL5wo9bkyHAaAoaJEALw_wcB&gclsrc=aw.ds){:target="\_blank"} 메타마스크 사용을 위해 크롬 설치가 필요합니다.
- [Truffle](https://trufflesuite.com/){:target="\_blank"} 블록체인 테스트 환경을 트러플로 구성하였습니다.
- [Ganache](https://trufflesuite.com/ganache/){:target="\_blank"} 트러플 GUI인 가나슈를 사용하였습니다.
- [Velog](https://velog.io/@andy3638/%EB%B8%94%EB%A1%9D%EC%B2%B4%EC%9D%B8-%ED%85%8C%EC%8A%A4%ED%8A%B8%ED%99%98%EA%B2%BD-%EA%B5%AC%EC%84%B1%ED%95%98%EA%B8%B0){:target="\_blank"} 블록체인 테스트 환경구성의 자세한 설명은 벨로그를 참고해주세요.

## After Installing the Requirements you can follow these guides:

### 전역 모듈 설치

### yarn & truffle installation

> ###### npm i -g yarn
>
> ###### npm i -g truffle

**※주의※ 노드의 버전에 따라 설치 방식이 다를 수 있습니다.**

### 모듈 설치

package.json에서 모듈 버전 확인이 가능합니다.<br>

> ##### // with yarn
>
> ###### yarn
>
> ##### // with npm
>
> ###### npm i
>
> **go inside the directory**
>
> ###### cd client
>
> ###### yarn or npm i again

### Changing into the Directory

**We have to go inside the directory:**<br>
프로젝트 구동을 위해 클라이언트 폴더로 들어가주세요.

> ###### cd client

### 프로젝트 실행

> ###### yarn run start or npm run start
