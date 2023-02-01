- [개발 프로세스](#개발-프로세스)
  * [1. 그라운드 룰 수립 및 컨벤션 문서화](#1.-그라운드-룰-수립-및-컨벤션-문서화)
  * [2. 애자일 스크럼 프로세스 적용](#2.-애자일-스크럼-프로세스-적용)
  * [3. gitlab을 활용한 소스코드 형상관리 및 협업](#3.-gitlab을-활용한-소스코드-형상관리-및-협업)


# 개발 프로세스

## 1. 그라운드 룰 수립 및 컨벤션 문서화
<p float="left">
  <img width="500" alt="belloga_chracter" src="https://user-images.githubusercontent.com/35598710/216036822-2ed1a9c2-392e-4bee-8179-5e6df1164904.png" style="display: inline-block">
  <img width="500" alt="belloga_chracter" src="https://user-images.githubusercontent.com/35598710/216038215-9479db23-eb71-43a0-ac54-9d13043d957e.png" style="display: inline-block">
</p>


* `jira & conflunce` 을 활용한 프로젝트 매니지먼트 및 문서화를 하였습니다.
* 우리만의 그라운드 룰을 만들고 그라운드 룰에 따라 팀을 운영하였습니다.
* 원활한 협업을 위해 `git` 컨벤션, `java` 컨벤션, 카프카 토픽 컨벤션 등 사전에 합의된 내용에 따라 문서화를 하고 개발을 진행하였습니다.

## 2. 애자일 스크럼 프로세스 적용
<p float="left">
  <img width="500" alt="belloga_chracter" src="https://user-images.githubusercontent.com/35598710/216039019-6e2e88b4-1e3f-4a98-af7a-fbca67ede9dd.png">
  <img width="500" alt="belloga_chracter" src="https://user-images.githubusercontent.com/35598710/216039100-81fa1174-0b27-4a5c-898d-5fbfe073645a.png">
</p>

- 애자일 스크럼 방식으로 프로젝트를 진행하였습니다.
    - 먼저 기획, 설계 단계에서 제품 백로그를 사용자 입장에서 스토리 기반으로 `task`를 나열하였습니다.
    - 하나의 스프린트 기간은 `15`일로 하였습니다.
    - 매일 평일 오전 10시 일일 스크럼 회의를 진행하였고 어제 한 일, 오늘 할 일, 주요 이슈사항을 공유하였습니다.
    - 스프린트를 시작하기 전 스프린트 계획회의를 하고, 스프린트가 끝날 때마다 데모 시연 및 회고를 하며 진행도를 파악하였습니다.

## 3. gitlab을 활용한 소스코드 형상관리 및 협업
<center><img width="500" alt="belloga_chracter" src="https://user-images.githubusercontent.com/35598710/216039723-65039239-cf1e-4b81-a875-9561e8b67be5.png"></center>

`gitlab` 에서 소스코드 형상관리, 코드리뷰 및 협업을 하였습니다. 브랜치 전략으로 `github flow`를 사용하였습니다.

- 스프린트 계획회의에서 자신이 할당받은 `task`를 스프린트 기간 동안 개발합니다.
- 사전에 정한 컨벤션에 따라 자신이 맡은 티켓에 해당하는 브랜치를 생성합니다. (1 ticket = 1 branch)
- 개발을 완료하고 `풀 리퀘스트`를 올려 코드 리뷰를 받습니다.
- `approve`를 받으면 자신이 `main` 브랜치에 병합을 합니다.
