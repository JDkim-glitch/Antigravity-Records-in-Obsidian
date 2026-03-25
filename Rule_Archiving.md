---
type: rule
tags: #rule #archiving #antigravity #standard
---

# 📜 Rule: Antigravity Archiving Protocol

Antigravity(AI)가 바이브 코딩 작업을 마치고 옵시디언에 기록할 때 반드시 준수해야 하는 표준 절차입니다.

## 1. 아카이빙 필수 단계 (Mandatory Steps)

1.  **버전 로그(Version Log) 생성**: 
    - `Advanced Version Note Template`을 사용하여 상세 작업 내용을 작성합니다.
    - 파일명 형식: `[Project_Name]_v[Version]_[Task_Summary].md`
2.  **마스터 노트(Master Note) 업데이트 (CRITICAL)**:
    - 해당 프로젝트의 `_Master.md` 파일을 찾아 `## 📁 4. 버전별 작업 로그` 섹션에 새 로그의 **내부 링크([[ ]])와 요약**을 반드시 추가합니다.
    - 주요 변경 사항이 있을 경우 `## 🧐 5. 주요 회고 및 피벗 기록` 섹션에도 내용을 업데이트합니다.
3.  **내부 링크 최적화**:
    - 생성된 로그 내에 마스터 노트, 이전 버전 로그, 관련 규칙(Rule)들을 상호 연결합니다.

## 2. 템플릿 구조 (Templates)

### Master Note
- YAML Frontmatter (type: project_master)
- Sections: Overview, Core & Stack, Global Context, Version History, Major Pivots.

### Version Log
- YAML Frontmatter (type: vibe_log, project: "[[Master_Link]]")
- Sections: 단계별 진행 과정 및 트러블 슈팅, 주요 성과, 회고, 다음 진행할 단계, 내부 링크.

---
**마지막 업데이트**: 2026-03-25
**적용 대상**: 모든 Antigravity 기반 작업 아카이빙
