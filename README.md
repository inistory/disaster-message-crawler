# Disaster-message-crawler

## 공공 재난문자 데이터 크롤링

### 데이터 살펴보기

공공데이터 포털에서 데이터를 수집해보겠습니다.

요즘 코로나로 인해 재난문자가 자주 발생하는데,, 한 번 직접 수집해보도록 하겠습니다.

 

* 공공데이터 포털

https://www.data.go.kr/dataset/3058822/openapi.do

데이터는 공공데이터 포털에서 활용신청을 하면 인증키를 발급받아 사용할 수 있습니다.

인증키를 받으시면, 추가하셔서 아래링크를 사용하시면 됩니다.

http://apis.data.go.kr/1741000/DisasterMsg2/getDisasterMsgList?ServiceKey=인증키&type=xml&pageNo=1&numOfRows=50&flag=Y


* pageNo : 페이지 번호

* numOfRows: 몇개의 row 묶음을 가져올 건지

 
* https://inistory.tistory.com/17?category=915877
