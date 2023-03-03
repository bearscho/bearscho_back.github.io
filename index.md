## 1. 성능테스트 정리
성능테스트 관련 정리 및 공유 목적의 Notion 페이지  
성능테스트 시 사용한 기술 및 사례들을 Notion 으로 정리하고 있습니다.  
개인 활용 목적이라 기술 블로그처럼 틀을 갖추어 정리되지는 않았지만, 공유 할 수 있는 부분은 공개용으로 제공합니다.   
<a href="https://bearscho.notion.site/Notion-8f4100a3a20c4c4eb844d33cec9bb4b0" target="_blank"  class="icon-link d-inline-flex align-items-center">Notion Main Page 로 이동</a>  

## 2. TTA 아카데미 링크
 TTA아카데미에서 진행하는 'Jmeter 기반 실전 성능테스트' 강의 시 정보 제공용 Notion 페이지  
 강의 소개 및 신청 페이지 : https://champ.tta.or.kr/  23년 1차: 4월20일 ~ 21일 , 2차: 6월8일 ~ 9일 진행합니다.  
 <a href="https://bearscho.notion.site/JMeter-6a65c25cbbea4591bcf5ddc114f2bc94" target="_blank" class="icon-link d-inline-flex align-items-center">Notion Page 로 이동</a>   
## 3. 취소티켓 찾기
인기 공연 티켓 예매 실패 시 취소표를 알림으로 받을 수 있도록 만든 서비스  
공연 취소표 발생 여부만 체크 후 취소표 발생 시 Slack 을 통하여 알림을 받을 수 있습니다.(예매는 직접)  
<a href="http://49.247.36.166" target="_blank"  class="icon-link d-inline-flex align-items-center">http://49.247.36.166	</a> 이동  
#### 구현 기술 
Back-End : Python,Flask(Jinja2)   
Front-End : bootstrap   
Database : AWS DynamoDB    
취소표 수집 : AWS Lamda (python,boto3,urllib3 등)    
Lamda 호출 관리 : K6 (GrafanaLab 의 Opensource 성능테스트 Tool)  <a href="https://k6.io/" target="_blank"  class="icon-link d-inline-flex align-items-center">https://k6.io/</a>  
