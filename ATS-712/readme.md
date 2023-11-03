## 설명

대충 수정한 서버 관련 파일들 참고용 

관련 링크도 첨부함 

### ATS 7.1.2 설정 관련

[Paypal에서 발견된 HTTP Request Smuggling - 실습 환경 구축 (lactea.kr)](https://lactea.kr/entry/Paypal%EC%97%90%EC%84%9C-%EB%B0%9C%EA%B2%AC%EB%90%9C-HTTP-Request-Smuggling-%EC%8B%A4%EC%8A%B5-%ED%99%98%EA%B2%BD-%EA%B5%AC%EC%B6%95)

너무 오래된 버전이라 apt install은 안되어있고 공개된 소스 코드 바탕으로 make 하는 기적을 실행해야 함 

records.config 

remap.config


----
error log (시작은 루트에서부터) 
/opt/ts-712/var/log/trafficserver$ << 이쪽에 로그 다 있음 
노드는 nohup으로 뺌 

