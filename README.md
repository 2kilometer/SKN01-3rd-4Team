# SKN01-3nd-4Team
### 🧑🏻‍🌾 TextFarmers(TF)

# 1. Introduction Team (팀 소개)
<table align="center">
  <tbody>
    <tr>
      <td align="center">
        <div>
          <img src="https://github.com/user-attachments/assets/7cbbcc77-39de-4dc6-be12-a2879ce15a0b"width="100px;"height="100px;" alt=""/>
          <a href="https://github.com/yhoon3002"><div align=center>팀장 임영훈</div></a>
        </div>
      </td>
      <td align="center">
        <div>
          <img src="https://github.com/user-attachments/assets/c7df2eb9-d897-4acc-87a9-3cdbca2863a6"width="100px;"height="100px;"" alt=""/>
          <a href="https://github.com/2kilometer"><div align=center>이경민</div></a>
        </div>
      </td>
      <td align="center">
        <div>
          <img src="https://github.com/user-attachments/assets/4d97616d-34b6-4495-aa18-dc1bb2733d4a"width="100px;"height="100px;" alt=""/>
          <a href="https://github.com/JUNGUIHEON"><div align=center>정의헌</div></a>
        </div>
      </td>
      <td align="center">
        <div>
          <img src="https://github.com/user-attachments/assets/c6970ea6-9c4d-4cc9-ba64-89db9bfe586f"width="100px;"height="100px;" alt=""/>
          <a href="https://github.com/RUVIST"><div align=center>최명근</div></a>
        </div>
      </td>
    </tr>
  </tbody>
</table>

# 2. Introduction Project (프로젝트 개요)
### 🧡 소개 🧡
러닝 유저들을 위한 러닝화 쇼핑 플랫폼을 CI/CD 구축하기 
### 💚 필요성 💚
 ![image](https://github.com/user-attachments/assets/437f0572-0be7-4849-a690-fa9a259a98a0)</br>
위에 보이듯이 SNS상에서도 러닝은 큰 유행을 타며 이제는 일상이 되었습니다.</br>
이로 인해 러닝을 즐기는 사람들을 위해서 주요 5대 브랜드의 런닝화 상품을 판매하는 쇼핑몰을 만들고,</br>
가입고객 이탈 예측 및 구매 동향을 분석하여 관리파 페이지에 레포트로 제공하는 플랫폼을 개발하기로 하였습니다.

## CI/CD란 ?
대충 CI/CD 관련해서 작성
CI/CD는 현대 소프트웨어 개발에서 필수적인 도구로, 개발 속도를 높이고 품질을 유지하는 데 중요한 역할을 합니다.

### CI/CD의 중요성

**CI (Continuous Integration)**

- **자동화된 테스트와 빌드:** 코드 변경 시 자동으로 테스트와 빌드를 실행하여 오류를 빠르게 발견하고 수정할 수 있습니다.
- **통합 주기 단축:** 작은 변경 사항을 자주 통합하여 개발자들이 항상 최신 코드를 사용할 수 있도록 합니다.

**CD (Continuous Deployment/Continuous Delivery)**

- **자동 배포:** 코드가 검증을 통과하면 자동으로 사용자에게 배포되어 새로운 기능을 빠르게 제공할 수 있습니다.
- **피드백 수렴:** 실제 사용자들로부터 빠르게 피드백을 받아 개선 사항을 신속하게 반영할 수 있습니다.

### CI/CD의 필요성

- **효율성 향상:** 개발, 테스트, 배포 과정을 자동화하여 개발팀의 생산성을 높입니다.
- **위험 감소:** 작은 기능 단위로 빈번히 배포하여 시스템 전체의 안정성을 유지하고 문제를 조기에 해결할 수 있습니다.
- **신속한 시장 반응:** 빠르게 변화하는 시장 요구를 충족시키기 위해 새로운 기능을 신속하게 배포할 수 있습니다.
- **팀 협업 강화:** 일관된 개발 및 배포 프로세스를 유지하여 개발자들 간의 협업을 촉진하고 코드 품질을 유지할 수 있습니다.


# 3. ERD 구성
![image](https://github.com/user-attachments/assets/f5dafd4b-5ead-4b75-91c6-c00e7c5f16ec)

## 애자일 보드를 사용하는 이유
```
과거 정의서들을 일일히 작성하였지만 빠른 속도로 무언가를 개발하는데 한계가 있습니다.
처음부터 많은 것들을 빌드업하면서 빠른 생산성을 기반으로 움직이려면 반드시 애자일해야합니다.
고로 폭포수 설계 방식이 아닌 애자일 프로세스 방식으로 애자일 보드를 작성하면서 진행했습니다.

애자일 보드는 자체적으로 제목이 요구 사항을 내포하며 각 카드 내부에는 정의한 Domain의 세부 사항이 기록됩니다.
고로 빠르게 팀원들과 협업 할 수 있고 소통 비용을 최소화시킬 수 있습니다.
작은 것 같지만 이와 같은 것들이 쌓여서 아주 기민하고 민첩한 조직을 만들어 냅니다.
```

# 4. Backend 애자일 보드 - 요구사항 정의서
<img src="https://github.com/user-attachments/assets/d749633c-5a18-423f-a709-4b1dadcef73b" />

<!-- ## 더미데이터 생성 방식
**계정 생성**</br>
![image](https://github.com/user-attachments/assets/4e395179-bae0-4643-954a-09270f696573)</br>
**로그인 기록 생성**</br>
![image](https://github.com/user-attachments/assets/37f684fe-03d5-411a-ad32-8b830eac1e34)</br>
**주문 생성**</br>
![image](https://github.com/user-attachments/assets/56cdf0c6-366c-4900-b937-9bb92c845f17)</br>
-->

# 5. Frontend 애자일 보드 - 화면 설계서
<img src="https://github.com/user-attachments/assets/13856381-cd4e-453e-a1f7-a66a8c0e8744" />

![image](https://github.com/user-attachments/assets/e241a2e2-56c8-4e8f-933b-3890e2ec9959)

![image](https://github.com/user-attachments/assets/fa154f7c-a0dc-4049-b8b0-d7848aea9ada)

# 6. FastAPI 애자일 보드 - AI 서빙 설계서
<img src="https://github.com/user-attachments/assets/41b3c5e2-0784-46cb-8e09-cf494f34ce58" />

# 7. 시스템 구성도
![image](https://github.com/user-attachments/assets/612d28ce-3f5d-4816-85d3-2269029b16f1)

# 8. Manual Deploy(수동 배포 진행 절차)
## Frontend (UI)

## Backend (Server)
1. 개발자가 GitHub 저장소에 작업내용을 푸쉬하거나 PR을 생성하고 관리자가 이를 승인합니다. (이 이벤트는 GitHub Actions 워크플로우를 트리거합니다.)
2. GitHub Actions 에서 CI(테스트)를 진행하고 통과하면 npm build를 통해 Docker 이미지를 빌드합니다. (빌드 결과로 html, css, javascript, 리소스 등이 나옵니다.)
3. 빌드가 완료되면 GHCR(GitHub Container Registry)에 push합니다.
4. GitHub Actions에서 AWS Security Group설정을 통해 AWS 서버와 연동합니다.
5. GHCR에서 연동된 AWS 서비스로 이미지를 pull(배포) 합니다.
6. AWS서버에서 이미지를 docker-compose로 컨테이너화합니다.
7. nginx를 구동하여 frontend코드가 동작합니다. (nginx는 구동시 docker-compose.yml을 참조하여 어떤 javascript, html, css를 참조할지 판정합니다.)
8. 이 과정이 완료되면 사용자가 AWS서버에 접속하여 서비스를 사용할 수 있습니다.
## FastAPI (AI Core Server)
FastAPI 프로젝트 수동 배포 절차
배경 설명
FastAPI는 빠르고 효율적인 웹 API를 개발할 수 있는 프레임워크입니다. 이 프로젝트는 FastAPI를 사용하여 개발된 애플리케이션을 AWS와 같은 클라우드 환경에 수동으로 배포하는 절차를 설명합니다.

1. 필수 소프트웨어 설치
먼저 개발된 애플리케이션의 필수 소프트웨어 패키지들을 정리합니다. 이는 애플리케이션이 동작하기 위해 필요한 Python 패키지들의 목록을 생성하는 과정입니다.

2. Docker 컨테이너 설정
다음으로 Docker를 사용하여 애플리케이션을 컨테이너화합니다. Docker는 애플리케이션을 격리된 환경에서 실행할 수 있도록 도와주는 도구입니다. 이를 통해 애플리케이션의 개발 환경과 운영 환경의 차이를 줄이고, 배포를 더욱 쉽게 할 수 있습니다.

3. Dockerfile 작성
Dockerfile을 작성하여 애플리케이션의 도커 이미지를 빌드합니다. Dockerfile은 애플리케이션을 어떻게 설정하고 실행할 것인지를 정의하는 파일입니다. 여기서는 ARM 아키텍처를 기반으로 한 Python 환경을 설정하고, 필요한 패키지를 설치하며, 애플리케이션을 실행할 준비를 합니다.

4. Docker-compose 설정
이어서 docker-compose를 사용하여 다수의 Docker 컨테이너를 관리하고 실행할 수 있도록 설정합니다. docker-compose.yml 파일은 여러 컨테이너 간의 네트워크 설정과 실행 방법을 정의합니다. 여기서는 FastAPI 애플리케이션을 컨테이너로 묶어서 실행하고, 외부와의 통신을 위한 포트 설정을 추가합니다.

5. 클라우드 환경 설정
AWS와 같은 클라우드 환경에 접속하여 환경 변수 및 기타 설정을 추가합니다. 이 단계에서는 AWS의 환경 변수 설정을 통해 애플리케이션이 정상적으로 운영될 수 있도록 준비합니다.

6. 로컬 빌드 및 배포
로컬에서 애플리케이션을 빌드하고, GitHub Actions과 같은 자동화 도구를 대비하여 로컬에서 먼저 테스트를 진행합니다. 이 과정에서는 Docker 이미지를 빌드하고, GitHub Container Registry (GHCR)에 푸시하는 과정을 수행합니다.

7. 클라우드 배포
애플리케이션을 클라우드 환경으로 배포합니다. AWS에 접속하여 애플리케이션을 위한 디렉토리를 만들고, 앞서 작성한 docker-compose.yml 파일을 사용하여 컨테이너를 실행합니다. 이 단계에서는 애플리케이션이 외부에서 접근 가능하도록 네트워크 설정을 완료합니다.

8. 테스트 및 외부 접속 설정
외부에서 API를 테스트하고, 필요한 경우 인바운드 규칙을 설정하여 외부 접속을 허용합니다. 이 과정에서는 애플리케이션이 정상적으로 작동하는지를 확인하고, 문제가 발생할 경우 신속하게 대응할 수 있도록 준비합니다.

9. 백그라운드 실행
애플리케이션을 백그라운드에서 실행하여 실제 사용자들이 서비스를 이용할 수 있도록 합니다. 이 단계에서는 서버가 계속해서 실행되도록 설정하고, 오류 없이 안정적으로 운영될 수 있도록 관리합니다.

# 9. Autonomous Deploy (자동 배포 진행 절차)
수동 배포는 개발자가 직접 로컬 환경에서 빌드하고 클라우드로 배포하는 과정을 수행하는 반면, 자동 배포는 코드 변경이 감지되면 CI/CD 파이프라인을 통해 자동으로 빌드, 테스트, 배포되어 개발 생산성과 안정성을 높입니다.



# 10. Result (수행 결과)

**사이트 화면**
![image](https://github.com/user-attachments/assets/83f21247-56f8-41d8-ab75-1197fa020d03)
![image](https://github.com/user-attachments/assets/cd8d817f-5fe2-41bc-9f3f-8c4112efba4e)
![image](https://github.com/user-attachments/assets/faa7942a-0d82-45de-b6b1-e9d6c6c4da35)
![image](https://github.com/user-attachments/assets/386da3c1-478d-427d-8e9e-d70c34898af7)
![image](https://github.com/user-attachments/assets/c64c8885-23ed-4093-be4e-f051b3586627)
![image](https://github.com/user-attachments/assets/8bbf74bc-3c9b-433f-9c71-0b6e63a3bb9b)
![image](https://github.com/user-attachments/assets/bd147f60-458f-4353-bb61-f780b8871ba2)


**회원 예측**
![image](https://github.com/user-attachments/assets/f3d259ef-a6d3-4558-9766-9a15fca97e97)
![image](https://github.com/user-attachments/assets/1913abfc-e505-41d2-872b-dee1fcaebde8)
![image](https://github.com/user-attachments/assets/f4970285-4242-4bfa-a107-2ec114ae76e2)
![image](https://github.com/user-attachments/assets/25ed50c0-76a3-4fb6-be93-c6e4dde1a708)
![image](https://github.com/user-attachments/assets/cf0a1767-2ab7-4d79-820e-06c80b0cf756)

# 11. Tech Stack (기술 스택)
<div align=left><h3>🕹️ Frontend</div>
<div align=left>
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=Vue.js&logoColor=white">
  <img src="https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=Vuetify&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white">
  <img src="https://img.shields.io/badge/D3.js-F9A03C?style=for-the-badge&logo=D3.js&logoColor=white">
  <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white">
</div>

<div align=left><h3>🕹️ Backend</div>
<div aling=left>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=Pandas&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=Redis&logoColor=white">
  <img src="https://img.shields.io/badge/KakaoDev-221E68?style=for-the-badge&logo=Kakao&logoColor=white">
</div>

<div align=left><h3>🕹️ AI Core</div>
<div align=left>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
</div>

<div align=left><h3>🕹️ Infra</div>
<div align="left">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=GitHub Actions&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub Runner-2088FF?style=for-the-badge&logo=GitHub Runner&logoColor=white">
</div>
                                                                                                       

# 12. Deploy Issue (배포 이슈)
- **FastAPI 수동 배포 중 Docker Image 오류**
  ![image](https://github.com/user-attachments/assets/aacbbebb-578a-4baf-94a9-1de2f7199b89)
  - **오류** : "Error response from daemon: mainfest unknown"
  - **오류 원인** : 진행할 Docker Image가 없거나 사용이 불가한 상황
  - **오류 해결** : Docker Build 과정에서 사용한 Github 계정은 Login할 때도 동일하게 사용
    - Docker Build를 진행하는 프로젝트에서도 Docker Login <br>
      ```bash
      echo "GHCR토큰" | docker login ghcr.io -u 계정 --password-stdin
      ```
    - AWS 접속 후 docker-compose.yml 파일 구동 시에도 Docker Login <br>
      ```bash
      echo "GHCR토큰" | docker login ghcr.io -u 계정 --password-stdin
      ```
    - .env로 관리하는 정보에 Github 계정은 docker build 구성할 때 사용한 계정

- **Frontend에서 Backend 요청을 받지 못하는 오류**
  - **오류** : Bakcend가 실행되지 않음
  - **오류 원인** : 진행할 Docker Image가 없거나 사용이 불가한 상황
  - **오류 해결** : Docker Build 과정에서 사용한 Github 계정은 Login할 때도 동일하게 사용
    - Docker Build를 진행하는 프로젝트에서도 Docker Login <br>
      
echo "GHCR토큰" | docker login ghcr.io -u 계정 --password-stdin
    - AWS 접속 후 docker-compose.yml 파일 구동 시에도 Docker Login <br>
      
echo "GHCR토큰" | docker login ghcr.io -u 계정 --password-stdin
    - .env로 관리하는 정보에 Github 계정은 docker build 구성할 때 사용한 계정


# 13. 테스트 보고서 (CI 테스트 결과)

# 14. 한 줄 회고
### 🌊 이경민
자동화된 테스트 덕분에 코드 품질이 눈에 띄게 향상되어 뿌듯했지만, 설정 과정에서 많은 시행착오를 겪으며 좌절하기도 했다.
### 😈 임영훈
CI/CD 도입으로 배포 시간이 크게 단축되어 팀 전체가 성취감을 느꼈지만, 새로운 시스템을 배우느라 초반에는 많이 혼란스러웠다.
### 🌋 정의헌
자동화된 파이프라인 덕분에 팀원들과의 협업이 한결 수월해졌고, 문제 해결 과정에서도 큰 만족감을 느꼈다.
### 🌾 최명근
지속적인 통합 덕분에 작은 변화들도 빠르게 배포할 수 있어 좋았지만, 예상치 못한 문제들이 발생할 때마다 긴장감이 느껴졌다.
