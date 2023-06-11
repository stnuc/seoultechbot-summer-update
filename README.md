# seoultechbot-summer-update
https://github.com/Graval504/seoultechbot  
2023 6월부터 8월까지 진행한 seoultechbot 업데이트에 대한 프로젝트입니다.
# 진행할 내용
## 1. 함수형 프로그래밍을 적용하여 전체 코드 리팩토링
### 참고할 서적 목록
https://ecip.libbook.co.kr/DetailView_new_utf.php?pUser=&savepoint=acuser&isbn=eGEyYktGOUVvVUNIcHg1Z1hoejVZenZBQU90U2gvY1F6RFE3aUZzMTVHejZITERlL05ETUpwNS8wRE16VWJJZg==&pchunggu=  
Go로 배우는 함수형 프로그래밍

https://ecip.libbook.co.kr/DetailView_new_utf.php?pUser=&savepoint=acuser&isbn=eGEyYktGOUVvVUNIcHg1Z1hoejVZMGRyckxXODlLQ083NVJUeTl1c3VpTmJPRjRaVkpnU3c5dWR2TUlncFlJQQ==&pchunggu=  
(쏙쏙 들어오는)함수형 코딩 : 심플한 코드로 복잡한 소프트웨어 길들이기

https://ecip.libbook.co.kr/DetailView_new_utf.php?pUser=&savepoint=acuser&isbn=eGEyYktGOUVvVUNIcHg1Z1hoejVZOFhtby9nNUNKY1c5eUNNOWtRNDMrM3ZKSWZDQm01anZTbEV3OFNleU9sdQ==&pchunggu=  
함수형 반응형 프로그래밍 : FRP 입문자를 위한 종합 안내서

## 2. 메시지의 형태 변화
게시글 내 사진은 별도로 링크를 추출하여 보낼 예정  
나머지 글부분을 메세지로 보낼지, 지금처럼 브라우저로 렌더링한 이미지를 보낼지는 테스트 후 결정  
게시글이 작성된 사이트를 별도로 기재  

## + 별도로 진행해볼 내용
docker를 사용해보고, docker 내에 ssh서버를 열어 동아리 내부적으로 공유해볼 것.  
해당 서버는 리눅스를 사용해보고 싶거나, 간단한 웹 서버나 디스코드 봇 서버를 열려고 할 때 편히 사용할 수 있도록 공유할 것임. (무거운 작업 X)  
DNS가 기본적으로 제공되어 graval504.asuscomm.com 주소를 기반으로 일부 범위 포트를 자유롭게 사용할 수 있도록 포트포워딩 할 예정.  
WSL + 리눅스에 대한 간단한 세미나를 방학 말에 시도해볼 수 있음  
