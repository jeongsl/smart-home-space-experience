# smart-home-space-experience
2026 LG DX School 5기 고객경험데이터 처리 서비스 프로젝트 (2반 4팀): 북미 신혼부부를 위한 스마트홈 공간 체험 서비스

## 분석 목적
북미 신혼부부의 가전에 대한 페인포인트, 니즈를 파악하기 위함


## 분석 데이터
[Reddit](https://www.reddit.com/) 내 신혼 부부, 가전 관련 게시글 59,305건 크롤링
  

## 분석 방법
* Python : Doc2Vec, Hierarchical Clustering, LDA, IPA(기회 영역 분석)


## 분석 결과
<img width="686" height="372" alt="image" src="https://github.com/user-attachments/assets/a539fab3-6134-42c5-a6c8-3b61c10d06c5" />

* Cluster 0: 비용을 줄이고 합리적인 가격에 구매하고 싶은 집단
  * Action 1: 동거, 결혼 생활에 필요한 가전을 찾는다
  * Action 2: 가정을 꾸리는데 비용을 절약하고 싶다
  * Action 3: 새 가전을 구매하는데 고민을 들인다
* Cluster 1: 스마트홈 관련 가전 정보와 후기를 탐색하는 집단
  * Action 2: 초기 구축 비용을 줄이기 위한 정보를 찾는다
  * Action 3: 프리미엄 키친 정보를 찾는다
  * Action 8: 새로운 집에서 스마트홈 환경을 구축한 후기를 찾는다
