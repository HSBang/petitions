[청와대 국민청원](https://www1.president.go.kr/petitions) 사이트의
[만료된 청원](https://www1.president.go.kr/petitions?only=finished) 데이터 모음.

## 데이터

* 전체 데이터: [petition.csv](https://s3.ap-northeast-2.amazonaws.com/data10902/petition/petition.csv)
* 5% 임의추출 데이터: [petition_sampled.csv](https://s3.ap-northeast-2.amazonaws.com/data10902/petition/petition_sampled.csv)

## 저작권

CSV 데이터의 저작권은 [KOGL 제1유형](http://www.kogl.or.kr/info/license.do)을 따름.

* 출처표시
* 상업적, 비상업적 이용가능
* 변형 등 2차적 저작물 작성 가능

소스 코드는 [MIT License](LICENSE)를 따름.

## 설치 및 실행

소스코드 받기:

    git clone https://github.com/akngs/petitions.git
    cd petitions

설치 ([pipenv](https://github.com/pypa/pipenv)가 설치되어 있어야 합니다):

    pipenv install

실행:

    pipenv shell
    python petition.py

생성된 데이터 확인:

    tail data/*.csv
