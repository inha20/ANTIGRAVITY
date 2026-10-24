# ANTIGRAVITY

**AI Collaboration Workspace — Structure Recognition Research Program**

> Maintaining continuity between AI sessions for long-term research development.

---

## Keywords

AI collaboration, research continuity, session handover, human-AI research collaboration, context preservation, long-term research management, structure recognition, AI workflow, research infrastructure, operational workspace

---

## What This Repository Is

ANTIGRAVITY is the **AI collaboration workspace** for the Structure Recognition Research Program. Its primary function is to preserve research context, document decisions, and enable continuity between AI-assisted work sessions.

This repository does not contain research papers. It contains operational infrastructure: handover documents, status records, architecture decisions, and workflow guidelines.

---

## Role in the Research Program

```
Research-Portfolio — Program Hub (public-facing navigation)
         |
         ↓
ANTIGRAVITY — AI Workspace (session continuity, operational layer)
         |
         ↓
Paper Repositories 1–8 — Research content (1–6: archived research notes; 7–8: current papers)
```

ANTIGRAVITY operates as the **operational layer** beneath the Research-Portfolio hub. While Research-Portfolio is the public-facing navigation point, ANTIGRAVITY is where AI session context is preserved across sessions.

---

## Key Files

> **[2026-06-20 압축 현행화]** 이 저장소는 문서 압축 이후 `README.md` 단일 파일로 운영됩니다.  
> 이전에 별도로 존재하던 `RESEARCH_STATUS.md`, `MESSAGE_TO_ANTIGRAVITY.md`, `PROGRAM_ARCHITECTURE_REVIEW.md`, `ANTIGRAVITY_TheoryIntegrationTask.md`의 내용은 모두 이 파일(`README.md`)에 통합되었습니다.

| File | Purpose |
|---|---|
| `README.md` | **Start here.** Current state of all repositories, operating principles, Architecture B decision record, Phase priorities, session handover context. (압축 통합본) |

---

## For AI Collaborators Starting a New Session

> **⚠️ 2026-06-21 업데이트 (Session 33):** 아래 읽기 순서가 현행화되었습니다. 이전 버전에 기술되어 있던 `MasterHandoverDocument.md` 및 `ProjectStatus.md` 경로는 더 이상 유효하지 않습니다.

**Required reading order:**

1. `inha20/SESSION_START.md` — **단일 AI 진입점 (v5.4)**. 프로그램 전체 구조, AI 운영 원칙, 작업 이력 포함.
2. 같은 문서의 **Active Queue**와 **Repository Health** 절 — 현재 대기 중인 작업 목록 및 저장소 헬스 현황 (구 `ProjectDashboard.md`는 `SESSION_START.md`에 통합되어 더 이상 없습니다).

**Then ask the researcher:** "Where did we leave off?"

Do not begin modifying any repository until you understand the Architecture B program structure.

---

## Current Research Program State

**Architecture:** Architecture B (Empirical Foundation Model) — adopted 2026-06-05

```
Paper 1: KMap Structure Invariance       — Empirical Case Study 1
         ↓
Paper 2: Symmetric Boolean Functions     — Empirical Case Study 2
         ↓
Paper 3: Variable Rearrangement          — Empirical Case Study 3
         ↓
Paper 4: Structure Recognition Theory    — Theoretical Hub
```

Papers 1–6 are archived, read-only research notes (2026-10-18). The two current papers are standalone and can be read without the earlier ones:

```
Paper 7: Karnaugh Group Classification                  — Standalone mathematics paper
Paper 8: Structural Thinking and Human-AI Collaboration — Standalone framework proposal
```

**Current Phase (2026-10-19):** 1~6번 저장소는 보관(읽기 전용)되었고 7·8번 독립 논문의 정리가 끝난 상태입니다. 투고 준비는 학회가 정해진 뒤 진행합니다. 이전 기록: Phase 4 — Repository Content Improvement + Phase 5 SEO (June–July 2026)

---

## Operating Principles

1. **Preserve** all existing filenames unless explicitly asked to rename
2. **Preserve** discovery history — never delete historical material
3. **Prefer** incremental improvements over full rewrites
4. **Document** all significant decisions in CHANGELOG or handover files
5. **Avoid** forcing theoretical frameworks onto early observations
6. **Prefer** conceptual organization over producing more content
7. **When in doubt**, preserve more information rather than less

---

## Phase Queue (2026-06 plan, status as of 2026-10-19)

| Phase | Scope | Status |
|---|---|---|
| Phase 1 | Repository stabilization, README updates | ✅ 완료 (2026-06-07; 2026-10에 1~8번의 링크·이름 정리) |
| Phase 2 | Figure standardization | ✅ 종결 (2026-10: 1~6번은 보관, 3번 images/는 31개로 정리, 그림은 7번에 정리하고 8번에는 기존 그림 3개를 삽입) |
| Phase 3 | GitHub Pages construction | ✅ 완료 (2026-06-07, Session 16; 2026-10에 1~6번 사이트 재배포) |
| Phase 4 | Repository content improvement | ✅ 7·8번 독립 논문으로 통합·정리 (2026-10) |
| Phase 5 | Search discoverability (SEO) | ⚪ 하지 않음 (미착수 상태로 종결) |
| Phase 6 | Future projects exploration | 🔵 투고 준비와 후속 연구 (학회 선정 후) |

Full detail: `Research-Portfolio/ProjectManagement/Expand_Summer2026_ResearchMaintenancePlan.md` — 이 문서는 2026-06-20에 삭제되어 현재는 없으며, git 이력(`0caed63^`)에서만 볼 수 있습니다.

---

## Research Program Links

This repository is part of the **Structure Recognition Research Program**.

| Repository | Role |
|---|---|
| [Research-Portfolio](https://github.com/inha20/Research-Portfolio) | Program Hub |
| [1KMapStructureInvariance](https://github.com/inha20/1KMapStructureInvariance) | Empirical Case Study 1 |
| [2SymmetricBooleanFunctionMinorThesis](https://github.com/inha20/2SymmetricBooleanFunctionMinorThesis) | Empirical Case Study 2 |
| [3VariableRearrangementInvarianceMinorThesis](https://github.com/inha20/3VariableRearrangementInvarianceMinorThesis) | Empirical Case Study 3 |
| [4StructureRecognitionTheory](https://github.com/inha20/4StructureRecognitionTheory) | Theoretical Hub |
| [5HumanAIResearchCollaboration](https://github.com/inha20/5HumanAIResearchCollaboration) | Methodological Meta-layer (Paper 5) |
| [6BooleanFunctionSpaceTheory](https://github.com/inha20/6BooleanFunctionSpaceTheory) | Applied Mathematics Extension (Paper 6, TODO.md 기반 통합 운영) |
| [7KarnaughGroupClassification](https://github.com/inha20/7KarnaughGroupClassification) | Standalone Mathematics Paper (Paper 7) |
| [8StructuralThinkingAndHumanAICollaboration](https://github.com/inha20/8StructuralThinkingAndHumanAICollaboration) | Standalone Framework Proposal (Paper 8) |
| [inha20](https://github.com/inha20/inha20) | GitHub Profile — 공개 진입점 + 중앙 허브 |

Papers 1–6 are archived, read-only research notes (2026-10-18); Papers 7 and 8 are the current papers.

**AI Entry Point:** [SESSION_START.md](https://github.com/inha20/inha20/blob/main/SESSION_START.md)

---

## Author

Choi Jonghun  
Independent researcher · 2nd-year student at Inha Technical College

*ANTIGRAVITY — maintained across AI sessions as part of the Structure Recognition Research Program*
