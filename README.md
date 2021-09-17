# 여행지 분석 프로젝트

##목표
여행지 별 해시태그를 이용하여 유의미한 결과 도출

### 아이디어
1. 각 여행지별 라벨 부여 후, 모든 여행지 태그를 통합하여, 태그별 라벨 분류해서 여행지 분류
2. 각 여행지별 여행자의 유사도 판단하는 건 각각의 태그 정보를 보고 유저 유사도 분류하기

여행지별 라벨 부여 -> 여행지 통합 후 태그별 여행지 라벨 분류
여행자의 태그를 토큰화 하고, 각각의 태그에 따라 여행자를 분류 및 여행자 별 유사도 판단 -> 이후에 각각의 여행지별 태그의 유사도 및 상관관계가 있다고 판단되면 다른 여행지를 추천 할 수 있지 않을까?
