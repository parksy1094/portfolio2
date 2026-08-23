# Bio Research Portfolio

Version: v3.1.1  
Last Updated: 2026-08-24

---

## 1. 프로젝트 개요

본 프로젝트는 바이오·제약 연구자의 실제 연구 경험과 전문 역량을 전달하기 위한 GitHub Pages 기반 Bio Research Portfolio이다.

단순한 이력서 요약이 아니라 세포 기반 효능평가, 비임상 연구, 데이터 통합, 외부 연구 운영 및 후보물질 개발 의사결정 지원으로 확장된 연구 경험을 구조적으로 보여주는 것을 목표로 한다.

---

## 2. 현재 상태

### Status

- 포트폴리오 `v1.3.0` HTML 수정 및 정적 검수 완료
- 단일 `index.html` 기반 정적 웹사이트 구조 유지
- GitHub Pages 공개 주소는 `portfolio2` 사용
- 최종 배포 전 검수본: `index_portfolio2_v1.3_reviewed.html`
- GitHub의 운영 파일은 배포 시 `index.html`로 교체
- GitHub Pages 배포 후 실제 PC·모바일 화면 및 링크 최종 검수 필요

### Public URL

- https://parksy1094.github.io/portfolio2/

### Current Implementation

- Web version: `v1.5.0`
- 공식 운영 문서:
  - `README.md`
  - `Portfolio_Guideline.md`

---

## 3. 현재 구현 구조

현재 `v1.5.0` 기준 정보구조는 다음과 같다.

1. Home / Hero
2. Career Metrics
3. Career Snapshot
4. Flagship Projects
5. Career Growth
6. Evidence to Decision
7. Research Workflow
8. Supporting Projects
9. Core Research Competencies
10. Collaboration & Leadership
11. Scientific Outputs
12. AI-Assisted Data Analysis
13. Contact

Hero와 주요 메시지는 유지하면서, 중간 섹션의 가독성·정보 위계·프로젝트 전달력을 개선한 구조이다.

---

## 4. 현재 반영 콘텐츠

### Hero

- 이름: 박신영
- 직무 타이틀: `Drug Discovery & Translational Research Scientist`
- 핵심 메시지:

> 실험 결과를 다음 개발 의사결정으로 연결하는 연구자

- 주요 연구 범위:
  - 비임상 효능평가
  - 후보물질 개발
  - Translational Research
- 주요 모달리티:
  - Protein Therapeutics
  - Peptide Therapeutics
  - mRNA Therapeutics
  - DDS

### Career Metrics

기존 확정 숫자 구성을 유지한다.

- `9+` 바이오·제약 R&D 경력
- `5` 대표 신약개발 프로젝트
- `3` Peer-reviewed Publications
- `15+` 글로벌 제약사 대응 실험

Metrics 영역은 어두운 배경 대신 밝은 배경과 강화된 숫자 대비를 사용한다.

### Career Snapshot

아래 세 축으로 경력 흐름을 요약한다.

- Career: 약 9년 신약개발 R&D
- Modality: Protein → Peptide · mRNA
- Role: Wet Lab → Strategy & Collaboration

직접 실험 중심 역할에서 비임상 전략, CRO·외부협업, 데이터 통합 및 후속 개발 판단 지원으로 역할이 확장된 흐름을 보여준다.

### Flagship Projects

Flagship은 3개 프로젝트로 구성한다.

1. 면역항암 펩타이드 후보물질 개발
2. 희귀질환 mRNA 치료제 개발
3. 재조합단백질 기반 신약개발

공통 정보구조:

- My Role
- Key Work
- Outcome / Decision

공개 화면에서는 `DKF-LC101`, `DKF-DC101`, `CP-FXN` 등 내부 프로젝트 코드를 사용하지 않는다.

### Evidence to Decision

다음 세 단계로 구성한다.

1. Evidence
2. Interpretation
3. Decision

효능·MoA·발현·전달성·비임상 데이터를 통합하고, 데이터의 일관성·한계·리스크를 해석하여 후보 우선순위와 후속 개발 방향 판단 근거로 연결하는 연구 방식을 보여준다.

### Research Workflow

7단계 연구과정을 유지한다.

1. Candidate / Technology
2. Assay Strategy
3. Cell-based Efficacy
4. Protein · Tissue · in vivo
5. External Data Review
6. Candidate Prioritization
7. Development Decision Support

Desktop과 Mobile에서 동일한 내용 구조를 사용한다.

### Supporting Projects

- iCP-Parkin
- iCP-SOCS3

Flagship보다 낮은 정보 위계로 유지하며 세포 기반 효능평가, 질환모델 구축 및 직접 실험 경험을 보완한다.

### Core Research Competencies

현재 네 개 역량 축으로 구성한다.

- Experimental Evidence
- Nonclinical & Translational
- External Research Operations
- Decision & Leadership

### Collaboration & Leadership

외부 협업 기관과 연구 운영 경험을 함께 제시한다.

현재 공개 화면에서 사용하는 협업 범주:

- Joint Research
- Technical Review
- University
- CRO
- CMO / CDMO

협업 대상 자체보다 시험계획, 연구 데이터, 생산·품질자료 검토와 내부 연구전략 반영 역할을 중심으로 작성한다.

### Scientific Outputs

현재 공개 화면 기준:

- Peer-reviewed Publications: 3
- Co-first-author Publication: 1
- AACR Posters: 4
- Joint Research Data Packages: 2
- 국가연구개발과제 결과보고서: 2

주요 논문 3건과 DOI 링크를 제공한다.

### AI-Assisted Data Analysis

기존 신약개발 경력과 별개로, 개인 학습 목적의 데이터 분석 실습을 소개하는 섹션. 분석 방향과 의사결정은 직접 수행하고 Claude Code를 구현·검증 보조 도구로 활용했음을 도입부에 명시한다. `Ongoing` 배지(그라디언트 스윕 애니메이션, `prefers-reduced-motion` 대응)로 프로젝트 목록이 계속 추가될 예정임을 표시한다.

현재 공개 프로젝트 3건 (각 GitHub 저장소로 연결):

- Bike Sharing Demand Analysis (`bike-sharing-portfolio`) — XGBoost 튜닝 모델 Test R² 0.889
- London Bike Sharing Demand Analysis (`london-bikeshare-demand-regression`) — Ridge 회귀 Test R² 0.788
- DPP-IV Inhibitory Peptide Classification (`dpp4-inhibitory-peptide-classification`) — XGBoost 모델 Test ROC-AUC 0.967

### Contact / Downloads

- Email
- GitHub
- 공개용 Resume
- 공개용 경력기술서

현재 연결 파일 (상대경로 `assets/documents/` 참조):

- `assets/documents/Park_Shinyoung_Public_Resume_v1.2.pdf`
- `assets/documents/Park_Shinyoung_Public_Career_Description_v1.2.pdf`

---

## 5. 콘텐츠 및 공개 범위 핵심 원칙

- 실제 수행·분석·검토·운영한 범위를 구분하여 작성한다.
- 확인되지 않은 업무, 성과 또는 정량 수치를 새로 만들지 않는다.
- 비공개 질환명·타깃명·단백질명·파트너 정보를 임의로 추가하지 않는다.
- Flagship 내부 프로젝트 코드는 공개하지 않는다.
- 외부 분석·AI 모델링은 직접 수행한 것으로 표현하지 않는다.
- Supporting Projects의 기존 공개 명칭은 현재 구현 범위를 유지한다.
- 공개 페이지에는 제작 의도, UX 설명, 채용 최적화 목적과 같은 내부 메타 문구를 노출하지 않는다.
- Footer 공개범위 문구는 다음과 같이 간결하게 유지한다.

> 본 포트폴리오는 공개 가능한 연구 경험과 성과를 기준으로 작성함

---

## 6. 포트폴리오 대상

공개 포트폴리오의 주요 독자는 다음과 같다.

- 바이오·제약 기업 채용 담당자
- 연구소 및 연구기관
- 공동 연구 협력자
- 대학원 지도교수 및 연구 책임자
- 연구자의 경력과 연구 경험을 확인하려는 일반 방문자

특정 독자만을 대상으로 하는 문구보다는 연구 경험과 역할 자체가 자연스럽게 전달되도록 작성한다.

---

## 7. 디자인 및 개발 기준

- 단일 `index.html` 기반 정적 웹사이트
- HTML, CSS, JavaScript를 한 파일에 포함
- 별도 빌드 과정 없음
- GitHub Pages 배포
- Desktop / Tablet / Mobile 반응형 구현
- Warm Ivory 기반 밝은 배경
- Violet, Gold, Sage, Plum을 보조 강조색으로 사용
- Hero의 밝고 선명한 시각적 정체성을 전체 디자인의 기준점으로 유지
- 중간 섹션에서 과도한 어두운 배경을 피하고 충분한 명도·대비 확보
- 큰 타이포그래피, 충분한 여백, 제한된 카드 반복 사용
- 영문 연구·기술 용어와 한글 설명을 혼합하되 동일 수준 항목의 표기 방식 통일
- Fade-up 등 최소한의 등장 애니메이션 사용
- `prefers-reduced-motion` 대응
- 원본 프로필 사진은 `assets/images/portrait.png` 상대경로로 참조

세부 콘텐츠, 디자인, 공개 범위 및 검수 기준은 최신 `Portfolio_Guideline.md`를 따른다.

---

## 8. 저장소 및 운영 파일

GitHub Pages 운영 기준 파일:

```text
portfolio/
├── index.html
└── assets/
    ├── images/
    │   ├── portrait.png
    │   └── og-image.png
    └── documents/
        ├── Park_Shinyoung_Public_Resume_v1.2.pdf
        └── Park_Shinyoung_Public_Career_Description_v1.2.pdf
```

공식 프로젝트 관리 문서는 아래 두 개만 유지한다.

- `README.md`
- `Portfolio_Guideline.md`

작업 중 생성한 preview 또는 reviewed 파일은 공식 문서가 아니며, 배포 확정 시 운영 파일 `index.html`로 반영한다.

---

## 9. 업데이트 및 배포 절차

1. 최신 README와 Portfolio Guideline을 확인한다.
2. 현재 배포 중인 `index.html`과 최신 검수본을 비교한다.
3. 사용자 승인사항과 공개 범위를 확인한다.
4. 수정본을 로컬에서 검수한다.
5. 운영 파일명을 `index.html`로 적용한다.
6. GitHub 저장소에 업로드하고 커밋한다.
7. GitHub Pages 배포 후 Desktop / Tablet / Mobile을 확인한다.
8. 메뉴·내부 앵커·외부 링크·Resume Download·Contact를 검수한다.
9. 공개 화면과 공식 문서가 일치하는지 확인한다.
10. 구현 상태가 변경되면 README와 Portfolio Guideline을 함께 업데이트한다.

---

## 10. 현재 검수 상태

`v1.3.0` 검수본에서 아래 항목을 확인하였다.

### 콘텐츠

- Flagship Projects 3개 유지
- 7단계 Research Workflow 유지
- Flagship 내부 프로젝트 코드 노출 없음
- 공개용으로 부적합한 제작자·채용 최적화 메타 문구 제거
- Footer 공개범위 문구 간소화

### 기술

- 중복 HTML ID 없음
- 깨진 내부 Anchor 없음
- 빈 링크 없음
- 새창 외부 링크에 `noopener noreferrer` 적용
- HTML 기본 구조 정상
- 원본 프로필 사진 `assets/images/portrait.png` 상대경로 참조로 전환

### 남은 검수

- GitHub Pages에 `v1.3.0` 운영 파일 배포
- 실제 공개 URL에서 Desktop / Tablet / Mobile 화면 확인
- 공개 사이트의 다운로드·외부 링크 재확인

---

## 11. 향후 고도화 항목

현재 구현 이후의 확장은 사용자 승인과 공개 가능 자료 확인 후 진행한다.

- 프로젝트별 공개 가능한 Figure / Poster / 시각자료 보강
- AACR Poster 등 연구 산출물 상세 연결
- 방문 분석 또는 운영 지표 도입
- 검색·공유 메타데이터 추가 고도화
- 필요 시 한국어·영어 이중언어 지원
- 실제 활용 피드백을 반영한 콘텐츠 및 UI 개선

현재 구조와 핵심 메시지를 훼손할 정도의 전면 리디자인은 별도 합의 없이 진행하지 않는다.

---

## 12. 새 대화 또는 작업 환경에서 이어가는 방법

작업 재개 시 아래 세 파일을 우선 확인한다.

1. 최신 `README.md`
2. 최신 `Portfolio_Guideline.md`
3. 현재 운영 또는 최신 검수 `index.html`

판단 우선순위:

1. 사용자의 최신 승인사항
2. 현재 대화
3. 최신 Portfolio Guideline
4. 최신 README
5. 기존 산출물

문서와 실제 웹 구현이 충돌하면 실제 구현 상태와 최신 사용자 승인사항을 확인한 뒤 공식 문서를 동기화한다.

---

## 13. 공식 문서

공식 문서는 아래 두 개만 운영한다.

- `README.md`
- `Portfolio_Guideline.md`

현재 공식 문서 버전: `v3.1.1`
