#SAS
-> C 언어로 구성 되어있음.

#R
데이터 분석을 위한 통계 및 그래픽스를 지원.
하나의 컴퓨터 언어이자 다양한 패키지의 집합이며, 사용자들이 직접 라이브러리를 확장함.

#R_studio
R 을 위한 통합 환경으로 R 사용에 필요한 부가 정보들을 한눈에 볼 수 있게 해줌.
R Studio 를 설치하기 위해서는 먼저 R을 설치해야한다.
R_studio의 설치가 완료 되어있는 상태임.


# working directory 의 설정
- working directory로 설정된 폴더의 하위 폴더는 인식하지 않으므로, 읽거나 쓰고 파일은 working directory를 클릭하면 바로 보여야함.
- 작업을 하고 싶은 폴더가 여러 개라면, 툴바에서 수작업으로 폴더를 고쳐주기 보다 setwd() 함수를 필요에 따라서 여러 번 사용하는 방법을 추천함.



# 자료의 타입과 관련된 함수 변환 함수

Numeric - as.numeric()
Logical - as.logical ()
Character - as.character
Factor - as.factor

sum() 
mean()
max()
min()
range() = min + max 동시 반환
var() 
sd(0
median()
rank()
summary() - min 1stQu median Mean 3rdQu max
quantile(k_score,0.3) - linear interpolation option

letters[1:x]
LETTERS[1:x]

