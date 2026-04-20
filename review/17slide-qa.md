# 피치덱 17장 QA 검수 결과

검수일: 2026-04-20  
파일: `/Users/artist_rahyeon/code/character/presentation/pitch-deck.html`

---

## 기본 체크

| 항목 | 결과 |
|------|------|
| 총 17장인가? | PASS (slide-1 ~ slide-17) |
| 화살표 전환 정상? | PASS (ArrowLeft/Right/Up/Down + 터치 스와이프) |
| 슬라이드 번호 표시? | PASS (하단 중앙 "N / 17" 표시, 다크슬라이드 대응) |

---

## 각 슬라이드 상세

| # | 제목 | 이미지 | 텍스트 | 분량 | 메시지 명확성 | 비고 |
|---|------|--------|--------|------|---------------|------|
| 1 | 커버 | PASS (group.jpeg 존재) | PASS | 적정 | PASS | |
| 2 | 문제 | N/A | PASS | 적정 | PASS | |
| 3 | 시장 | N/A | PASS | 적정 | PASS | |
| 4 | 솔루션 시나리오 | N/A | PASS | 적정 | PASS | |
| 5 | 시연-온보딩 | N/A | PASS | 적정 | PASS | iframe 확인 |
| 6 | 핵심 플로우 | N/A | PASS | 적정 | PASS | |
| 7 | 시연-홈화면 | N/A | PASS | 적정 | PASS | iframe 확인 |
| 8 | 캐릭터 | PASS (5종 모두 존재) | PASS | 적정 | PASS | |
| 9 | 시연-마음숲 | N/A | PASS | 적정 | PASS | iframe 확인 |
| 10 | 커리큘럼 | PASS (캐릭터 썸네일) | PASS | 적정 | PASS | |
| 11 | 차별점 | N/A | PASS | 적정 | PASS | |
| 12 | 수익 구조 | N/A | PASS | 적정 | PASS | |
| 13 | 굿즈 | PASS (4개 모두 존재) | PASS | 적정 | PASS | |
| 14 | 시연-부모PIN | N/A | PASS | 적정 | PASS | iframe 확인 |
| 15 | 실행 계획 | N/A | PASS | 적정 | PASS | |
| 16 | 리스크 | N/A | PASS | 적정 | PASS | |
| 17 | 클로징 | PASS (gongbueng.jpeg) | PASS | 적정 | PASS | |

---

## 시연 4장 (슬라이드 5, 7, 9, 14)

| # | iframe src | 시작 화면 | 크기 | 조작 가능 |
|---|-----------|-----------|------|-----------|
| 5 | `../prototype/index.html` | 온보딩 (처음부터) | PASS (85vh) | PASS |
| 7 | `../prototype/index.html?screen=home` | 홈 화면 | PASS (85vh) | PASS |
| 9 | `../prototype/index.html?screen=forest` | 마음숲 | PASS (85vh) | PASS |
| 14 | `../prototype/index.html?screen=parent-pin` | 부모 PIN 입력 | PASS (85vh) | PASS |

- 모든 screen ID가 prototype에 존재 확인 완료
- iframe은 active 슬라이드에서만 display:block (성능 최적화)

---

## 굿즈 (13번)

| 상품 | 파일 | 존재 여부 |
|------|------|-----------|
| 감정 인형 세트 | plush-set.jpeg | PASS |
| 프리미엄 워크북 | workbook.jpeg | PASS |
| 마음숲 플레이 세트 | playset.jpeg | PASS |
| 생활용품 | daily-goods.jpeg | PASS |

---

## 금지 항목 검사

| 항목 | 결과 |
|------|------|
| "바통" | PASS (없음) |
| "테라피" | PASS (없음) |
| "인사이트" | PASS (없음) |
| 달러($) | PASS (없음) |
| border-left 컬러 바 | PASS (없음) |
| 그라데이션 (gradient) | PASS (없음) |

---

## 전체 품질

- 깔끔하고 프리미엄한 톤 유지: PASS
- 발표 수준 적합성: PASS
- 폰트: Pretendard (프리미엄 한글 폰트)
- 색상: 절제된 뉴트럴 + 포인트 #C4856C

---

## 수정 사항

**수정 없음.** 전 항목 통과.

---

## 최종 판정: PASS
