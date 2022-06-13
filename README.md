# NFT 마켓플레이스
> Opensea와 유사한 NFT 마켓플레이스

<img src="https://img.shields.io/badge/Javascript-F7DF1E?style=flat&logo=Javascript&logoColor=white"/></a>
<img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=React&logoColor=white"/></a>
<img src="https://img.shields.io/badge/MobX-FF9955?style=flat&logo=Mobx&logoColor=white"/></a>
<img src="https://img.shields.io/badge/Solidity-363636?style=flat&logo=Solidity&logoColor=white"/></a>
<img src="https://img.shields.io/badge/IPFS-65C2CB?style=flat&logo=IPFS&logoColor=white"/></a>

현재 보유중인 NFT들을 리스트 형식으로 볼 수 있고 거래소에 등록된 NFT들의 목록을 보여주고 등록된 가격만큼 판매자에게 지불하면 NFT들을 구매하는 거래소 웹 어플리케이션입니다. 또한 원하는 이미지 또는 파일 등으로 새로운 NFT를 만들 수 도 있습니다.  

<img src="https://user-images.githubusercontent.com/34996487/173266988-395edca3-5148-4345-98bc-229ebb79a91f.png" width="800"></img>

## 설치 방법
```
cd client
npm install
```

## 사용 예제
### 민팅
민팅 페이지에서 NFT 이름, 설명, 이미지를 업로드하고 민팅 버튼을 클릭하면 새로운 NFT를 생성한다.  

<img src="https://user-images.githubusercontent.com/34996487/173270680-6f4a9ccf-c343-4514-af5e-5605e8cf027b.png" width="800"></img>  
### 판매
NFT 상세페이지에서 Sell 버튼을 클릭하면 원하는 금액을 입력할 수 있는 모달창이 뜨고 완료 후 거래소에 등록된다.

<img src="https://user-images.githubusercontent.com/34996487/173270683-4d901e4b-a1b0-4815-94c1-cd5f2f467718.png" width="800"></img>
### 구매
NFT 상세페이지에서 Buy 버튼을 클릭하면 버튼 아래에 있는 금액만큼 지불한 뒤 NFT를 구매하게 된다.

<img src="https://user-images.githubusercontent.com/34996487/173270684-17fee5aa-2842-496f-9f03-66ebdc041344.png" width="800"></img>

## 업데이트 내역
- 1.0.0
  - 이더리움 Rinkeby 테스트넷 지원
  - Opensea API에서 NFT 상세데이터 불러오기
  - NFT 민팅할 때 ipfs에 메타데이터 및 이미지 업로드
  - NFT 판매 및 구매

## 라이센스

## 외부 리소스
- UI 템플릿
  - [Black Dashboard React](https://demos.creative-tim.com/black-dashboard-react/#/dashboard)
  - 라이센스
    - Copyright 2020 Creative Tim (https://www.creative-tim.com)
    - Licensed under MIT (https://github.com/creativetimofficial/black-dashboard-react/blob/master/LICENSE.md)
