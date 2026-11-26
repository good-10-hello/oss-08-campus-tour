# 🏫 우리 학교 캠퍼스 투어 (oss-08-campus-tour)

우리 학교에 처음 오는 신입생과 방문객을 위해 **추천 투어 코스 · 주요 건물 · 교내 편의시설 · 주변 맛집**을 안내하는 웹사이트입니다.
HTML · CSS만으로 만들고, GitHub(이슈 · 브랜치 · PR · 리뷰)로 협업합니다.

- 🌐 배포 주소: (GitHub Pages 배포 후 추가)
- 🗂 진행 현황: [Issues](https://github.com/good-10-hello/oss-08-campus-tour/issues) · [Milestones](https://github.com/good-10-hello/oss-08-campus-tour/milestones)

## 👥 팀원 및 역할

| 이름(학번) | GitHub | 담당 페이지 | 추가 역할 |
|---|---|---|---|
| 장재희 (2026025641) | @good-10-hello | 메인 `index.html`, 추천 코스 `pages/course.html` | 팀장(PM): 저장소·설정 관리, 팀원 초대, 마일스톤·일정 관리, 회의 진행, 브랜치 보호 규칙 |
| 탁은서 (2026052188) | @eunseotak | 주변 맛집 `pages/food.html` | 디자인 담당: 공통 `css/style.css`(색·글꼴·레이아웃), 와이어프레임 정리, 디자인 일관성 리뷰 |
| 최효정 (2026046535) | @ericahyojung | 주요 건물 `pages/buildings.html` | 문서 담당: README, 회의록(이슈·Wiki), 이미지 출처·AI 활용 내역 정리, 발표 자료 취합 |
| 박수진 (2026053927) | @soooojinnnn | 교내 편의시설 `pages/facilities.html` | 품질 담당: 링크·이미지 깨짐 점검, 배포 사이트 테스트(PC·모바일), 리뷰 누락 PR 챙기기 |

## 📁 폴더 구조

```
oss-08-campus-tour/
├── index.html          ← 메인 (장재희)
├── pages/
│   ├── course.html     ← 추천 투어 코스 (장재희)
│   ├── buildings.html  ← 주요 건물 (최효정)
│   ├── facilities.html ← 교내 편의시설 (박수진)
│   └── food.html       ← 주변 맛집 (탁은서)
├── css/
│   └── style.css       ← 공통 스타일 (탁은서)
├── images/             ← 이미지 (영문 소문자-하이픈 이름)
└── README.md
```

## 🤝 협업 규칙

1. **할 일은 이슈로** 등록하고 담당자(Assignee) · 라벨 · 마일스톤을 지정합니다.
2. **main에 직접 커밋하지 않습니다.** 이슈마다 브랜치를 만듭니다. 예: `feat/food-page-8`
3. **커밋 메시지:** `종류: 무엇을 했는지 (#이슈번호)`
   - `feat` 새 내용 · `fix` 오류 수정 · `style` CSS · `docs` 문서
   - 예: `feat: 맛집 페이지 가격표 추가 (#8)`
4. **PR**에 리뷰어 1명 이상 지정, 본문에 `Closes #이슈번호`를 적습니다.
5. **리뷰**는 "좋아요/LGTM" 대신 근거 있는 코멘트(사실 + 이유 + 제안) 후 Approve 합니다.
6. 승인 1명 이상 받은 뒤 병합하고, 다 쓴 브랜치는 삭제합니다.
7. 파일 · 이미지 이름은 **영문 소문자 · 숫자 · 하이픈(-)** 만 사용합니다.

## 🗓 마일스톤

| 마일스톤 | 내용 | 산출물 |
|---|---|---|
| 1. 프로젝트 기획 및 설계 | 저장소 · 이슈 · 와이어프레임 | 공통 뼈대 index.html, README 초안 |
| 2. 웹페이지 제작 | 1인 1페이지 HTML + 공통 CSS | 페이지별 HTML, style.css, 병합된 PR |
| 3. 최종 점검 및 제출 | Flexbox · Pages 배포 · 문서 | 배포 주소, 완성 README, v1.0 릴리스 |

## 🖼 이미지 출처

| 파일 | 출처 | 라이선스 |
|---|---|---|
| (예) images/main-gate.jpg | 직접 촬영 (장재희) | - |

## 🤖 AI 활용 내역

| 날짜 | 도구 | 용도 | 사용한 사람 |
|---|---|---|---|
| 2026-11-26 | Claude | README 구성 · 진행 점검 초안 | 장재희 |
