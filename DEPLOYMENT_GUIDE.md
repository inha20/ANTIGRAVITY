# GitHub Pages 배포 가이드 — 8개 저장소 전체

**작성일:** 2026-06-06  
**대상:** inha20 (GitHub 사용자명)  
**목적:** Phase 3 GitHub Pages 배포 — 연구자 직접 실행 단계 안내

---

## 배포 전 준비 상태 (AI 완료)

| 항목 | 상태 |
|---|---|
| `.nojekyll` 파일 (8개 전체) | ✅ 완료 |
| Paper 4 series nav 링크 오류 수정 | ✅ 완료 |
| inha20 프로필 페이지 카드 링크 → Pages URL | ✅ 완료 |
| 전체 index.html 감사(Audit) | ✅ 완료 |

---

## 연구자가 해야 할 일 — GitHub 설정 (8회 반복)

### 공통 절차 (저장소별로 동일)

```
GitHub.com 로그인
→ 해당 저장소 접속
→ [Settings] 탭 클릭
→ 왼쪽 메뉴: [Pages]
→ Source: "Deploy from a branch" 선택
→ Branch: "main" 선택  
→ Folder: "/" (root) 선택
→ [Save] 클릭
```

배포 소요 시간: 저장소당 약 1–3분

---

## 8개 저장소 배포 체크리스트

### [ ] 1. inha20 (프로필 페이지)
- 저장소: `github.com/inha20/inha20`
- 배포 후 URL: `https://inha20.github.io/`
- 역할: 공개 진입점 — 외부 방문자 최초 접촉

### [ ] 2. 1KMapStructureInvariance (Paper 1)
- 저장소: `github.com/inha20/1KMapStructureInvariance`
- 배포 후 URL: `https://inha20.github.io/1KMapStructureInvariance/`
- 역할: 경험적 사례 연구 1 — 카르노맵 구조 불변성

### [ ] 3. 2SymmetricBooleanFunctionMinorThesis (Paper 2)
- 저장소: `github.com/inha20/2SymmetricBooleanFunctionMinorThesis`
- 배포 후 URL: `https://inha20.github.io/2SymmetricBooleanFunctionMinorThesis/`
- 역할: 경험적 사례 연구 2 — 대칭 불함수 시각 패턴

### [ ] 4. 3VariableRearrangementInvarianceMinorThesis (Paper 3)
- 저장소: `github.com/inha20/3VariableRearrangementInvarianceMinorThesis`
- 배포 후 URL: `https://inha20.github.io/3VariableRearrangementInvarianceMinorThesis/`
- 역할: 경험적 사례 연구 3 — 변수 재배열 불변성

### [ ] 5. 4StructureRecognitionTheory (Paper 4)
- 저장소: `github.com/inha20/4StructureRecognitionTheory`
- 배포 후 URL: `https://inha20.github.io/4StructureRecognitionTheory/`
- 역할: 이론적 허브 — 구조 인식 이론 (H1–H7)

### [ ] 6. 5HumanAIResearchCollaboration (Paper 5)
- 저장소: `github.com/inha20/5HumanAIResearchCollaboration`
- 배포 후 URL: `https://inha20.github.io/5HumanAIResearchCollaboration/`
- 역할: 방법론 연구 — 인간-AI 장기 협업

### [ ] 7. Research-Portfolio (프로그램 허브)
- 저장소: `github.com/inha20/Research-Portfolio`
- 배포 후 URL: `https://inha20.github.io/Research-Portfolio/`
- 역할: 내부 탐색 허브 — 전체 프로그램 내비게이션

### [ ] 8. ANTIGRAVITY (AI 작업 공간)
- 저장소: `github.com/inha20/ANTIGRAVITY`
- 배포 후 URL: `https://inha20.github.io/ANTIGRAVITY/`
- 역할: AI 세션 연속성 유지 운영 레이어

---

## 배포 후 검증 체크리스트

모든 저장소 배포 완료 후 아래 URL을 직접 열어 확인:

```
https://inha20.github.io/                                               → inha20 프로필
https://inha20.github.io/1KMapStructureInvariance/                     → Paper 1
https://inha20.github.io/2SymmetricBooleanFunctionMinorThesis/         → Paper 2
https://inha20.github.io/3VariableRearrangementInvarianceMinorThesis/  → Paper 3
https://inha20.github.io/4StructureRecognitionTheory/                  → Paper 4
https://inha20.github.io/5HumanAIResearchCollaboration/                → Paper 5
https://inha20.github.io/Research-Portfolio/                           → 프로그램 허브
https://inha20.github.io/ANTIGRAVITY/                                  → AI 작업 공간
```

### 확인 항목 (각 URL마다)
- [ ] 페이지가 열리는가 (404 아님)
- [ ] 한글이 깨지지 않는가
- [ ] 이미지가 로드되는가 (Paper 1, 2 해당)
- [ ] 시리즈 내비게이션의 링크가 올바른가
- [ ] 모바일 레이아웃이 정상인가 (브라우저 폭 축소 테스트)

---

## 감사(Audit) 결과 요약 — 각 index.html 상태

| 저장소 | 이미지 의존성 | 외부 CDN | 내부 링크 | 크로스 링크 | 배포 준비 |
|---|---|---|---|---|---|
| 1KMapStructureInvariance | 없음 (카드 레이아웃) | 없음 | .md 파일 4개 존재 확인 ✅ | 없음 | ✅ 완료 |
| 2SymmetricBooleanFunctionMinorThesis | images/01–13.png 존재 ✅ | MathJax CDN | 없음 | 없음 | ✅ 완료 |
| 3VariableRearrangementInvariance | 플레이스홀더 div (그림 없음) | 없음 | 없음 | Pages URLs ✅ | ✅ 완료 |
| 4StructureRecognitionTheory | 없음 | 없음 | 없음 | Pages URLs ✅ (수정 완료) | ✅ 완료 |
| 5HumanAIResearchCollaboration | 없음 | 없음 | 없음 | Pages URLs ✅ | ✅ 완료 |
| ANTIGRAVITY | 없음 | 없음 | 없음 | Pages URLs ✅ | ✅ 완료 |
| inha20 | 없음 | 없음 | 없음 | Pages URLs ✅ (수정 완료) | ✅ 완료 |
| Research-Portfolio | 없음 | 없음 | 없음 | Pages URLs ✅ | ✅ 완료 |

---

## 참고: .nojekyll 파일의 역할

GitHub Pages는 기본적으로 Jekyll 정적 사이트 생성기를 실행합니다.  
Jekyll은 `_`로 시작하는 파일/폴더를 무시하고, 일부 파일을 처리합니다.

`.nojekyll` 파일을 루트에 두면 Jekyll 처리를 건너뜁니다.  
이를 통해 **순수 HTML/CSS/JS 정적 사이트**가 그대로 배포됩니다.

이 프로젝트의 8개 저장소 모두 `.nojekyll`이 필요합니다 — 전부 추가 완료.

---

## 이 가이드 이후 다음 단계 (Phase 4)

배포 완료 후 우선순위:

1. **Paper 1 논문 완성도** — 5.5절 플레이스홀더 처리, 이미지 명세서, 초록·결론 반영
2. **Paper 3 그림** — `pictures.txt` 기반 25개 그림 연구자 직접 제작
3. **Paper 2 이미지 originals/** — PNG 파일 백업 완료 여부 확인
4. **Search discoverability** (Phase 5) — 각 저장소 메타 태그·설명 최적화

---

*Cross-reference: ANTIGRAVITY-main/RESEARCH_STATUS.md*  
*생성: 2026-06-06 Session 8*
