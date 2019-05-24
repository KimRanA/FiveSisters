## 프로젝트 기획 배경 및 목표 

- 카페 메뉴판의 수많은 메뉴 중에 어떤 것을 먹어야 할지 선택을 못했을 때 해당 카페에서 어떤 메뉴가 가장 맛있는 메뉴인지 모를 때 먼저 메뉴들을 먹어본 사람들의 평가 데이터를 종합하여 선택해주는 메뉴 추천시스템을 개발하고자 했다.

- 지능형 IOT봇을 활용한 빅데이터 개발 전문가 과정을 통해 배운 DataBase, 인공지능 API 활용 기술을 접목한 서비스를 개발하고자 한다. 메뉴판의 메뉴를 인식하고, 기존의 메뉴 평가를 점수화하여 추천 메뉴를 소개하는 서비스이다.  

- API 기술 중 광학 문자 처리 (OCR: Optical Character Recognition) 과 자연어 처리(NLU:Natural Language Understanding)를 사용한다. 메뉴판을 인식할 때 광학 문자 처리를 통해 사진에서 글자를 추출한다. 또한, 리뷰의 감정 분석을 통해 단순한 별점을 넘어 사람들의 메뉴에 대한 인식을 분석한다. 


1. Selenium을 이용한 YOGIYO Web Crawling.md	
  [https://github.com/KimRanA/FiveSisters/blob/master/1.%20Selenium%EC%9D%84%20%EC%9D%B4%EC%9A%A9%ED%95%9C%20YOGIYO%20%20Web%20Crawling.md]
2. Crawling결과 데이터 전처리.md	
3. OCR api 이용해서 이미지에서 텍스트 추출.md	
4. 2에서 만든 데이터에서 Review의 텍스트를 NLU API 돌려서 수치화 하기.md	
5. 최종 데이터 전처리 과정 (모든 컬럼 0 ~ 1로 정규화 하고 가중치 부여해서 Result 값 뽑아내기).md	
6. Oracle Database에 저장.md	
7. Django 웹 페이지 구현 원리 정리.md
