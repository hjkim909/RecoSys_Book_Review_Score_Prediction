# Recosys_Project
### ISBN, 인구통계학적 데이터, 저자/출판사 데이터를 바탕으로 책 평점 예측

* 전처리
> + 이상치 제거
> + 잘못된 데이터 수정
> + 데이터 그루핑
> + 파생변수 생성

* Hybrid Modeling
> + Factorization Maching(모든 변수를 고려 가능)
> + Modified MF(Matrix Factorization의 가중합 해줄 때 딥러닝을 통해 가중치 계산)
> + 정규 분포를 따르지 않는 raw 데이터를 예측하기 위해 10점 리뷰를 분류 후 회귀 분석 진행
