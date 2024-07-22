# SKN01-3nd-4Team
SKN01-3nd-4Team

# 1. Introduction Team (팀 소개)
<table align=center>
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
- 프로젝트 명: TransFaremrs(TF)
- 프로젝트 소개: 러닝 유저들을 위한 러닝화 쇼핑 플랫폼 통한 가입 고객 이탈 예측 및 구매 동향 예측
- 프로젝트 필요성(배경)
 ![image](https://github.com/user-attachments/assets/437f0572-0be7-4849-a690-fa9a259a98a0)</br>
위에 보이듯이 SNS상에서도 러닝은 큰 유행을 타며 이제는 일상이 되었습니다.</br>
이로 인해 러닝을 즐기는 사람들을 위해서 주요 5대 브랜드의 런닝화 상품을 판매하는 쇼핑몰을 만들고,</br>
가입고객 이탈 예측 및 구매 동향을 분석하여 관리파 페이지에 레포트로 제공하는 플랫폼을 개발하기로 하였습니다.
- 프로젝트 목표: 가입 고객 이탈 예측 및 구매 동향 예측

  
  


# 3. ERD 구성
![image](https://github.com/user-attachments/assets/f5dafd4b-5ead-4b75-91c6-c00e7c5f16ec)

# 4. 데이터 수집 방식 (크롤링)

# 5. Streamlit 애플리케이션 사용 방식

# 6. Manual Deploy (수동 배포 진행 절차)

## Frontend (UI)

## Backend (Server)

## FastAPI (AI Core Server)

# 7. Autonomous Deploy (자동 배포 진행 절차)
![image](https://github.com/user-attachments/assets/612d28ce-3f5d-4816-85d3-2269029b16f1)

## Frontend (UI)
1. 개발자가 GitHub 저장소에 작업내용을 푸쉬하거나 PR을 생성하고 관리자가 이를 승인합니다. (이 이벤트는 GitHub Actions 워크플로우를 트리거합니다.)
2. GitHub Actions 에서 CI(테스트)를 진행하고 통과하면 npm build를 통해 Docker 이미지를 빌드합니다. (빌드 결과로 html, css, javascript, 리소스 등이 나옵니다.)
3. 빌드가 완료되면 GHCR(GitHub Container Registry)에 push합니다.
4. GitHub Actions에서 AWS Security Group설정을 통해 AWS 서버와 연동합니다.
5. GHCR에서 연동된 AWS 서비스로 이미지를 pull(배포) 합니다.
6. AWS서버에서 이미지를 docker-compose로 컨테이너화합니다.
7. nginx를 구동하여 frontend코드가 동작합니다. (nginx는 구동시 docker-compose.yml을 참조하여 어떤 javascript, html, css를 참조할지 판정합니다.)
8. 이 과정이 완료되면 사용자가 AWS서버에 접속하여 서비스를 사용할 수 있습니다.

## Backend (Server)

## FastAPI (AI Core Server)

# 8. Result (수행 결과)

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


# 9. Tech Stack (기술 스택)
<div align=left><h3>🕹️ Frontend</div>
<div align=left>
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=Vue.js&logoColor=white">
  <img src="https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=Vuetify&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white">
  <img src="https://img.shields.io/badge/D3.js-F9A03C?style=for-the-badge&logo=D3.js&logoColor=white">
  <img src="https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=Axios&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=for-the-badge&logo=GitHub Actions&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub Runner-2088FF?style=for-the-badge&logo=GitHub Runner&logoColor=white">
</div>

<div align=left><h3>🕹️ Backend</div>
<div aling=left>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=Django&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white">
</div>

<div align=left><h3>🕹️ AI Core</div>
<div align=left>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
</div>
  
# 10. 테스트 보고서 (CI 테스트 결과)

# 11. Agile Board (애자일 보드)

# 12. Deploy Issue (배포 이슈)

# 13. 한 줄 회고
4팀 모두 수고하셨습니다! 많이 배워갑니다!

