### 발표 대본: 웹 사이트 크롤링과 Naver CLOVA Summary API를 활용한 연예인 콘텐츠 통합 제공 시스템

---

**[슬라이드 1: 제목 슬라이드]**
- 안녕하세요, 저희는 4조 김장윤, 양현정, 김정윤, 박정연입니다.
- 오늘 발표할 주제는 "웹 사이트 크롤링과 Naver CLOVA Summary API를 활용한 연예인 콘텐츠 통합 제공 시스템"입니다.

---

**[슬라이드 2: 목차]**
- 오늘 발표할 내용은 다음과 같습니다.
  1. 주제에 대한 설명
  2. 변경사항
  3. 현재까지 진행 과정
  4. 향후 계획

---

**[슬라이드 3: 주제 설명 - 선택 배경]**
- 팬덤 활동이 다양한 SNS 플랫폼으로 확장되고 있습니다.
- 검증되지 않은 루머와 비공식 뉴스 등 사이버 렉카가 성행하고 있습니다.
- 팬들에게 편의성과 신뢰를 제공하는 서비스를 개발하고자 합니다.

---

**[슬라이드 4: 주제 설명 - 기대 효과]**
- 편의성 증대: 다양한 플랫폼을 오가는 번거로움 없이 한 곳에서 통합된 정보를 확인할 수 있습니다.
- 신뢰성 강화: 연예인의 공식 입장을 중심으로 서비스를 제공하여 비공식 정보에 대한 혼란을 줄입니다.

---

**[슬라이드 5: 주제 설명 - 목표 계획]**
- 당일 공식 기사 및 SNS 콘텐츠 통합 제공 서비스 구축
- 네이버 기사, 유튜브 크롤링 자동화하여 실시간 데이터 수집
- 인스타그램, 트위터 과거 데이터를 활용한 정보 제공
- Naver CLOVA Summary API를 이용한 한 줄 요약 서비스
- 서비스 제공 웹 사이트 개발

---

**[슬라이드 6: 변경 사항 - 기존 목표와 현재 상황]**
- Chat GPT API 사용이 불가하여 Naver CLOVA Summary API를 사용하게 되었습니다.
- 인스타그램, 트위터 게시물 데이터 수집 완료
- "N년 전 오늘" 서비스 프로토타입 완성

---

**[슬라이드 7: 변경 사항 - 인스타그램 트위터 데이터 수집 방법]**
- Instagram: 글자는 txt, 사진은 jpeg, 영상은 mp4로 저장하며 날짜(YYMMDD)로 파일명 통일
- Twitter: 글자와 이미지 URL 링크로 게시된 영상 등을 CSV 파일에 저장, 트위터에 직접 올린 영상은 mp4로 다운로드

---

**[슬라이드 8: 중간 발표 질의 응답]**
- Q: 신뢰성을 어떻게 입증할 것인가?
- A: 팬의 입장에서 공식 입장만을 제공함으로써 신뢰성을 확보할 수 있습니다. 연예인의 공식 입장을 중심으로 서비스하여 비공식 정보의 혼란을 줄입니다.

---

**[슬라이드 9: Naver - 당일 발행된 아이유 공식 기사 요약 제공]**
- 검색 대상: 아이유
- 본문 내용 확인: 아이유 및 이담엔터테인먼트 포함 유무 확인
- 요약 요청: Naver CLOVA Summary 요약 요청
- 결과: 기사 제목, 본문 요약, 기사 URL 크롤링하여 csv 파일에 저장

---

**[슬라이드 10: YouTube - 유튜브 API를 사용한 아이유 공식 계정 영상 수집 제공]**
- 유튜브 API를 사용하여 아이유 공식 계정의 당일 업로드된 동영상을 수집
- 검색된 동영상 정보를 HTML 파일로 생성하여 웹 브라우저를 통해 쉽게 열람 가능

---

**[슬라이드 11: Instagram - GitHub API를 이용한 콘텐츠 DB 연동]**
- 인스타그램 콘텐츠를 DB에 연동하여 관리하고, 검색 및 조회 기능을 제공합니다.

---

**[슬라이드 12: Twitter - GitHub API를 이용한 콘텐츠 DB 연동]**
- 트위터 데이터 수집을 통해 CSV 파일로 저장된 데이터를 기반으로 트윗을 조회하고, 게시 영상을 출력합니다.

---

**[슬라이드 13: 향후 계획]**
- 연예인과 팬의 실시간 소통 플랫폼 ‘BUBBLE’ 프레임 사용
- 테마는 팬덤 공식 색상 선택
- 현재와 과거로 채팅방 분할
- 좋아하는 소식은 ♥, 수정이 필요한 소식은 👎 버튼 제공
- 이미지를 많이 포함한 게시물은 버튼을 이용해 이동
- 실제 웹 서비스 구상을 위해 Figma를 사용

---

**[슬라이드 14: 향후 계획 - 여름 방학 2학기 계획]**
- DB 선정 및 구축: 프로젝트에 맞는 DB를 선정하고 데이터를 저장
- 네이버 뉴스 유사도 검사: 중복된 기사 문제 해결
- UI/UX: Figma로 초안 작성 후 개발 예정
- 웹 사이트 개발: 백엔드 Flask 사용하여 서버 구축, 백엔드와 프론트엔드 분업 예정

---

**[슬라이드 15: 감사 인사]**
- 이상으로 발표를 마치겠습니다. 감사합니다.

---
