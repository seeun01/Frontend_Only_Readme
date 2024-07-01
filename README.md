🌐 Webbizcraftshop : AWS 기반 SiteBuilder 서비스
---
### 프론트엔드 팀원 소개
|                               [김원진](https://github.com/oen0thera)                                |                                            [김세은](https://github.com/seeun01)                                            |  
|:-----------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------:|
|                                       wjsj1015@naver.com                                        |                                     ssky601@gmail.com                                      |                                      
|  <img src="https://github.com/CloudService-mobile-app/backend/assets/126854628/eb420fb9-c7c1-4b1c-8762-c86110f53508" width="150" height="150"> |  <img src="https://github.com/CloudService-mobile-app/backend/assets/126854628/1aa8f1cc-cda9-4fa4-b460-1ec802567917" width="150" height="150"> |

### 📍개요
클라우드 기반의 혁신적인 플랫폼으로, AWS를 활용하여 손쉽게 고유한 웹사이트를 구축할 수 있습니다.

URL을 직접 지정하고 이미지를 업로드하여 자신만의 웹사이트를 만들 수 있으며, 방문자 수, 방문 횟수, 스토리지 용량, 트래픽과 같은 주요 지표를 실시간으로 모니터링하여 비즈니스 성과를 추적할 수 있습니다.


***※ 보안상의 이유로 코드는 공개되지 않습니다.***

---
### 📍주요 기능
| 기능 | 설명                                                                              |
|---|---------------------------------------------------------------------------------|
| 고유한 웹사이트 구축 | 사용자들은 총 3개의 웹사이트를 생성할 수 있으며, 각 웹사이트는 직접 지정한 고유한 URL과 업로드한 이미지를 통해 자신만의 웹사이트를 만들 수 있습니다. |
| 클라우드 기반 플랫폼 | AWS의 S3, Route 53, CloudFront, ACM을 활용하여 동적 도메인을 생성합니다.        |
| 방문자 및 방문 횟수 추적 | 각 웹사이트에 방문한 방문자 수와 방문 횟수를 실시간으로 추적할 수 있습니다.                                     |
| 스토리지 용량 모니터링 | AWS CloudWatch를 통해 각 웹사이트의 스토리지 용량을 실시간으로 모니터링하여 사용자가 데이터를 얼마나 저장하고 있는지를 파악할 수 있습니다. |
| 트래픽 제한 | Bucket4j와 Redis(Lettuce)를 활용한 AOP를 통해 각 웹사이트의 트래픽을 100MB 아래로 제한하여 서버 부하를 관리합니다. |
| 실시간 트래픽 모니터링 및 알림 | AWS CloudWatch를 통해 트래픽이 100MB를 넘으면 알림이 가도록 설정하여 실시간으로 모니터링하고 대응합니다. |

---
### 📍 활동
**시작일** <br>
*2024.05.03* <br>

**1차 출시** <br>
*2024.06.14* <br>

---
### 📍 결과물
**배포 사이트** <br>
*https://main.webbizcraft.shop* <br>

**시연 영상** <br>
[1차 출시](https://drive.google.com/file/d/10inKFQjI8fsM7oqXdLQUS53h_G6_GTfK/view?usp=sharing)

**간단 소개** <br>
![Slide15](https://github.com/CloudService-mobile-app/Frontend_Only_Readme/assets/90389593/9219be60-27b6-4854-b593-99beca17d53c)

---

### 📍 아키텍쳐 
![모바일앱협동조합 (5)](https://github.com/CloudService-mobile-app/Frontend_Only_Readme/assets/90389593/17846b57-66dc-4ad3-8f49-ea05a000750b)

---

### 📍 사용 기술스택
- Next.js

---


### commit message convention
- feat: 새로운 기능 추가
- fix: 버그 수정
- docs: 문서
- style: 포맷팅, 누락된 세미콜론 등
- refactor: 코드 리팩토링
- test: 테스트 관련
- chore: 기타 수정
- build: 빌드 시스템 또는 외부 의존성에 영향을 주는 변경
- remove: 파일을 삭제
