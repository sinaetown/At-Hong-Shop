# 🛒 At Hong Shop
Vue.js와 Spring Boot 기반의 **온라인 쇼핑몰**

## 🚀 주요 기능

✅ **🔐 Redis 기반 보안 로그인 시스템**  
- Access Token & Refresh Token을 Redis에 저장하여 보안 강화  
- JWT 기반 인증 및 세션 관리

✅ **👥 관리자 & 일반 사용자 권한 분기 처리**  
- JWT 토큰을 기반으로 사용자 역할(Role)을 판별
- Spring Security와 커스텀 필터를 통해 로그인 이후 권한에 따른 접근 제어
- 관리자는 상품 관리·회원 조회 가능, 일반 사용자는 상품 구매만 가능

✅ **☁️ AWS 기반 클라우드 배포**  
- **EC2**: Spring Boot 백엔드 실행  
- **S3 + CloudFront**: 정적 프론트엔드 배포 (Vue 빌드)  
- **RDS**: MySQL DB 호스팅  
- **ELB**: HTTPS 요청을 백엔드에 로드밸런싱, 도메인 연결 (Route53 연동)
- **도메인 연동**:  
  - `https://at-hong.shop`
---

## 🛠️ 기술 스택

### 🖥 Frontend
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)

### ☕ Backend
![Java Spring](https://img.shields.io/badge/Java%20Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
<img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![JWT](https://img.shields.io/badge/JSON%20Web%20Tokens-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

### ☁️ Deployment & Infra

<img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=Amazon%20EC2&logoColor=white"> <img src="https://img.shields.io/badge/AWS%20S3-569A31?style=for-the-badge&logo=Amazon%20S3&logoColor=white">
<img src="https://img.shields.io/badge/AWS%20CloudFront-96588A?style=for-the-badge&logo=amazon-aws&logoColor=white">
<img src="https://img.shields.io/badge/AWS%20RDS-527FFF?style=for-the-badge&logo=Amazon%20RDS&logoColor=white">
<img src="https://img.shields.io/badge/AWS%20route53-8C4FFF.svg?style=for-the-badge&logo=amazonroute53&logoColor=white">
<img src="https://img.shields.io/badge/AWS%20Elastic%20Load%20Balancing-E74C3D.svg?style=for-the-badge&logo=awselasticloadbalancing&logoColor=white">
---
