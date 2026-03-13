# VocFlow

사용자 리뷰(VOC)를 입력하면 AI가 자동으로 분류·요약·발화 재구성까지 해주는 VOC 분석 도구입니다.

## 주요 기능

**1단계 — 분석**
CSV/TXT 파일 업로드 또는 직접 붙여넣기로 VOC 데이터를 입력하면, AI가 주제별 분류, 키워드 추출, 핵심 요약, 사용자 발화 재구성까지 수행합니다.

**2단계 — 발전**
분석 결과를 바탕으로 AI가 아이디어를 도출하고, 자동 그룹화 및 우선순위 매트릭스를 생성합니다. 태그 기반으로 추가 아이디어를 생성할 수 있습니다.

**3단계 — 전달**
분석 결과를 인사이트 카드로 정리합니다. 8종 팔레트, 블록 구성 커스터마이징, AI 최종 요약, PDF/이미지 저장을 지원합니다.

## 기술 스택

- React + TypeScript + Vite
- Tailwind CSS
- Firebase Authentication / Firestore
- Anthropic Claude API
- GitHub Pages 배포

## 배포

https://cocoa178.github.io/vocflow/

## 기타

- 다크모드 지원
- 모바일 반응형
- 프로젝트 다중 관리 (로컬 저장 + 클라우드 동기화)
