# Dacon-recommender-system

## ✔️웹 기사 추천 AI 경진대회(데이콘)
https://dacon.io/competitions/official/236290/overview/description 
  - 데이콘에서 실시한 웹 기사 추천 알고리즘 개발 대회
    - 기간 : 2024.06.03 ~ 2024.07.01
<br>      



## ✔️데이터
  1) view_log.csv : 유저가 기사를 조회한 로그 데이터
  2) article_info.csv : 기사에 대한 정보 데이터
  3) sample_submission.csv : 제출 양식, 한 유저에게 5개의 기사를 추천한 리스트
     
🙌 데이터에 대한 자세한 설명은 data 폴더 readme를 확인해 주세요.  

<br>


## ✔️추천시스템 모델 
  🧐 추천 시스템이란 ?
  
    - 정보 필터링을 사용하여 사용자에게 흥미로운 정보 아이템을 제공하는 시스템
    - 사용자의 선호도, 관심 분야 등의 정보를 기반으로 사용자의 선호도의 알맞는 정보 및 상품을 추천하거나 제공하는 방법
    - 영화, 음악, 뉴스, 책, 연구 주제 등 검색에 적용될 수 있음
    [출처] : https://terms.naver.com/entry.naver?docId=3436437&cid=42346&categoryId=42346
<br>

추천 시스템에서 대표적인 알고리즘은 협업 필터링과 컨텐츠 기반 필터링이 있다.

![image](https://github.com/sh-0620/dacon-recommender-system/assets/172260370/3a974329-9e32-41b0-8251-881cb31507ae)
 [출처] : 마음을 읽는 개인화 마케팅의 시대

<br>
  ### 👥 Collaborative Filtering (협업 필터링)
  
      - 같은 컨텐츠를 좋아하는 사람은 컨텐츠 취향이 비슷할 것이라는 가정에 기반한 알고리즘 
      - 다른 사용자와의 유사성을 기반으로 추천
  
  ### 🗂️ Content-based Filtering (컨텐츠 기반 필터링)
  
      - 사용자가 선택한 컨텐츠와 유사한 속성의 컨텐츠를 추천해주는 방식 
      - 컨텐츠 간의 유사성을 기반으로 추천


    <br>  

## ✔️사용한 모델
### Hybride Recommender System
![image](https://github.com/sh-0620/dacon-recommender-system/assets/172260370/73a4d3fe-38ba-4abb-acb7-34c7af908470)

**본 대회에서는 협업 필터링(Collaborative Filtering)과 컨텐츠 기반 필터링(Content-based Filtering)을 조합한 알고리즘인 하이브리드 추천 시스템을 활용하여 웹 기사를 추천하였다.**
