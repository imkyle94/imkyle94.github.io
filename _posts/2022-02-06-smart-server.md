---
title: Smart Server
layout: post
post-image: https://kylesportfolio.s3.amazonaws.com/smartserver.jpg
description: 블록체인 기반 메인넷 & 거래사이트

tags:
    - Kyle
    - BlockChain
    - Smart Server
---

Github Link(No Client Design) : <a href="https://github.com/pjh94/SmartServer-ws-">Go GITHUB</a>
　　 Typescript ver. Link(진행 중. 타입스크립트 버전으로 보는 걸 권장합니다.) : <a href="https://github.com/pjh94/SmartServer-WebSocket-TypeScript">Go GITHUB</a>

---

# 블록체인 기반 거래사이트

## 프로젝트에 들어가기에 앞서

-   블록체인에 관한 사전 지식들이 많이 요구됩니다. 벨로그를 확인하시면 도움이 되는 글을 많이 보실 수 있습니다.
-   [BlockChain](https://velog.io/@andy3638/%EB%B8%94%EB%A1%9D%EC%B2%B4%EC%9D%B8%EC%97%90-%EB%8C%80%ED%95%98%EC%97%AC%EB%B8%94%EB%A1%9D%EC%B2%B4%EC%9D%B8%EC%97%90-%EB%8C%80%ED%95%9C-%EB%B8%94%EB%A1%9C%EA%B7%B8-%EA%B8%80-%EB%9D%BC%EC%9A%B0%ED%8C%85)

## 프로젝트 간단 설명

-   프로젝트 명 : 블록체인 기반 거래사이트
-   프로젝트 팀명 : 개인 작업
-   개발 기간 : 2022-01-20 ~ 2022-02-06

## 구현 기술

-   블록 및 트랜잭션 데이터 구조화 및 채굴 진행
-   Javascript TCP/IP 통신 .net 활용한 P2P 소켓 통신 구현 및 WebSocket 프로토콜로 확장
-   Javascript event 모듈 및 콜백 처리를 통한 이벤트 발생자 구현

## 사용 기술 & 라이브러리

다음의 기술 & 라이브러리들이 프로젝트에 사용되었습니다<br>

-   Elliptic 알고리즘이 사용되었습니다.
-   Merkle Tree 알고리즘이 사용되었습니다.
-   POW 알고리즘이 사용되었습니다.
-   WebSocket 프로토콜이 사용되었습니다.
-   Event 모듈이 사용되었습니다.

## Requirements

-   [NodeJS](https://nodejs.org/ko/){:target="\_blank"} 자바스크립트 언어로 작성되었습니다. 프로젝트 구동 시 자바스크립트 런타임 환경인 NodeJS를 이용합니다. **버전관리의 용이성을 위해 아래에 기술한 NVM 사용을 권장합니다.** v16으로 작성되었습니다.
-   [NVM](https://github.com/nvm-sh/nvm){:target="\_blank"} Node Version Manager Github입니다. 본인 환경에 맞게 설치하실 수 있습니다.
-   [node-gyp](https://github.com/nodejs/node-gyp){:target="\_blank"} Node.js native addon build tool입니다. 노드 버전에 따라 설치가 필요할 수 있습니다.

## After Installing the Requirements you can follow these guides:

### 전역 모듈 설치

### yarn installation

> ###### npm i -g yarn

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

### 프로젝트 실행

> ###### yarn run start or npm run start

---

### 프로젝트 시연

---

### 프로젝트 특이점

#### BlockChain Mainnet

블록체인 메인넷에 대한 기본 개념이 포함되어 있습니다.

##### Coupling Degree

타입스크립트로 코드를 리팩토링하면서 결합도에 대해 깊은 고민을 하였습니다.

##### Chained & Valid Block

블록 구현에 있어서 클래스를 이용하였습니다. 이더리움 네트워크로의 확장성을 고려했습니다.

##### Nonce

블록 해시를 찾는 과정에서 넌스를 구현하였습니다.

##### UTXO Transaction

블록과 그 안에 담기는 내용인 트랜잭션에 대한 처리를 구현하였습니다.

##### Cryptocurrency Wallet

##### Websocket Protocol

기본 net 통신에서 WebSocket으로 이전하며 웹 서비스 구현에 대한 고민을 하였습니다.

#### Javascript Event Emitter

사용하는 자바스크립트를 잘 이해하고자 이벤트 발생자와 그에 대한 콜백 함수에 대한 처리를 구현하였습니다.
