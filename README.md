# 북작북작 ChatGPT, DALL-E 3 모델 API 서버

<div align="center">
  <h2>사용 언어 및 개발 환경</h2>
</div>


![북작북작 사용 언어 및 개발 환경](https://github.com/FairTale-Bukjak/Server/blob/main/FairTale%20Server%20folder/%EB%B6%81%EC%9E%91%EB%B6%81%EC%9E%91%20%EC%82%AC%EC%9A%A9%20%EC%96%B8%EC%96%B4%20%EB%B0%8F%20%EA%B0%9C%EB%B0%9C%20%ED%99%98%EA%B2%BD.png)
+ 사용자가 입력한 문장을 ChatGPT API 사용하여 문장 이어나가기
+ ChatGPT API에서 받은 문장을 활용하여 DALL-E 3에서 이미지 생성
+ Spring 서버에서 전달 받은 input값을 API 서버로 값을 전달하고 최종 결과값을 프론트에게 데이터를 전달하는 방식입니다.

<div align="center">
  <h2>ERD(Entity-Relationship Diagram, 엔티티 관계 다이어그램</h2>
</div>


![테이블](https://github.com/FairTale-Bukjak/Mobile/blob/main/FairyTale%20folder/%EB%B6%81%EC%9E%91%EB%B6%81%EC%9E%91%20%ED%85%8C%EC%9D%B4%EB%B8%94.png)

<div align="center">
  <h2>프로젝트 기능 설명</h2>
</div>


+ 기능 1. 사용자가 입력한 문장을 기반으로 동화 내용을 이어나감
+ 기능 2. 다음 문장을 이어나가기 어려운 경우 AI가 다음 이어나갈 문장을 추천
+ 기능 3. 작성한 문장을 기반으로 그림을 출력
+ 기능 4. 선택한 캐릭터의 음성으로 동화책을 읽어줌(TTS 기능)
+ 기능 5. 한국어를 영어로 번역 후 영어 동화책을 보여주고 동화책 읽어줌

<div align="center">
  <h2>북작북작 어플 및 웹 페이지 이동</h2>
</div>

👉[어플](https://github.com/FairTale-Bukjak/Mobile)
 
👉[웹](https://github.com/FairTale-Bukjak/Web)
