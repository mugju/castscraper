# castscraper

## 개요
음악(podcast)의 일부분에 댓글을 달고 해당 부분을 scrap 할 수 있도록 하는 프로그램. 
해당 부분을 추출하여 youtube나 instagram 등에 업로드하기 쉽도록 분리된 파일로 다운가능하게 처리.
compressor 혹은 noise reducer 같은 이펙터를 통해 소스의 일부 변환을 지원.

### 생각하는 아키텍처 
redis 및 message-queue 를 이용하여 영상 최초 업로더 혹은 podcast 사용자에게 댓글 알림이 가도록 처리
사운드 클라우드 같은 스트리밍 시스템 구축
