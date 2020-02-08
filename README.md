# KkuPart
Explore Good News about Seoul, Korea Apartment Price

- Title: 부동산 정책이 실거래가에 끼치는 영향 [집값 호재 분석]
- 대상 건물 유형: 아파트
- 대상 지역: 위례 신도시
- 소스 데이터
    - 실거래가 관련: 공공데이터 부동산 실거래가 데이터 (API, file 형태 등으로 수집)
    - 정책 관련: 부동산 관련 뉴스 데이터 (Scrapping)
- 분석 컨텐츠
    - 호재 유형별 기사 매칭
    - 기사 트렌드와 실거래가 트렌드 관계 분석
- 추후 작업 내용
    - 관련 데이터 조사
        - 부동산 기사 데이터
        - 매매가 데이터
        - (계획) 부동산 정책 공고 데이터
    - 데이터별 확보 방안
        - 스크래핑, API
    - 데이터 관리 방안
        - 우선 개인 드라이브에 업로드 후 공유
        - 관리방안 세워야 함.
    - 데이터 탐색 (과정)
        - 기사 데이터
            - 연도별 부동산 관련 키워드 추출
            - 활용 라이브러리: konlpy, soynlp, kr-wordrank, khaiii
        - 매매가 데이터
            - 시계열 트렌드 확인

--------------
참고
1. Jupyter Lab 사용
- pip install jupyterlab
- "> jupyter lab"
