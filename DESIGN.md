---
name: 광주소프트웨어마이스터고 코딩테스트 플랫폼
description: 광주소프트웨어마이스터고 학생이 다음 문제와 자신의 성장을 바로 이해하는 코딩테스트 학습 앱
colors:
  primary-teal: "#18C5C7"
  teal-mist: "#95E0E1"
  study-cream: "#FFEAC2"
  progress-amber: "#FFC585"
  growth-green: "#A3D47F"
  surface-tint: "#FAFCFB"
  surface-soft: "#F2F7F6"
  border-soft: "#D7E3E2"
  text-strong: "#203332"
  text-muted: "#5A6F6D"
typography:
  display:
    fontFamily: "Pretendard, Inter, system-ui, sans-serif"
    fontSize: "4rem"
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: "normal"
  headline:
    fontFamily: "Pretendard, Inter, system-ui, sans-serif"
    fontSize: "2rem"
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: "normal"
  title:
    fontFamily: "Pretendard, Inter, system-ui, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 650
    lineHeight: 1.25
    letterSpacing: "normal"
  body:
    fontFamily: "Pretendard, Inter, system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: "normal"
  label:
    fontFamily: "Pretendard, Inter, system-ui, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "normal"
rounded:
  sm: "4px"
  md: "8px"
  lg: "12px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "40px"
components:
  button-primary:
    backgroundColor: "{colors.primary-teal}"
    textColor: "{colors.text-strong}"
    typography: "{typography.label}"
    rounded: "{rounded.md}"
    padding: "12px 18px"
  button-secondary:
    backgroundColor: "{colors.study-cream}"
    textColor: "{colors.text-strong}"
    typography: "{typography.label}"
    rounded: "{rounded.md}"
    padding: "12px 18px"
  chip-progress:
    backgroundColor: "{colors.surface-soft}"
    textColor: "{colors.text-strong}"
    typography: "{typography.label}"
    rounded: "{rounded.sm}"
    padding: "6px 10px"
  card-learning:
    backgroundColor: "{colors.surface-tint}"
    textColor: "{colors.text-strong}"
    rounded: "{rounded.md}"
    padding: "20px"
---

<!-- SEED -->

# Design System: 광주소프트웨어마이스터고 코딩테스트 플랫폼

## 1. Overview

**Creative North Star: "성장 보드"**

이 시스템은 광주소프트웨어마이스터고 학생이 방과 후 교실이나 집에서 노트북으로 문제를 풀고, 오늘의 진도와 다음 행동을 확인하는 장면에서 출발한다. 화면은 밝고 선명해야 하며, 학습이 쌓이고 있다는 감각을 즉시 줘야 한다. 기본 테마는 라이트다. 긴 풀이 시간에도 눈이 피곤하지 않아야 하고, 친구 활동과 성장 지표는 활기를 주되 산만해지면 안 된다.

디자인은 문제은행보다 학습 운영 앱에 가깝다. 첫 화면은 많은 문제를 나열하기보다 오늘의 과제, 이어 풀 문제, 약점 회복, 친구 활동을 스캔 가능한 구조로 보여준다. 교사용 화면도 같은 언어를 공유하되, 학생 경험보다 더 높은 정보 밀도와 빠른 필터링을 우선한다.

**Key Characteristics:**

- 밝은 표면, 명확한 상태, 짧은 행동 문구
- 성장률, 연속 풀이, 취약 유형 회복을 강조하는 학습 피드백
- 청록을 중심으로 한 활기 있는 색상, 따뜻한 보조색으로 과제와 성취 구분
- 반복 사용 화면에서는 장식보다 스캔성, 밀도, 접근성 우선

## 2. Colors

팔레트는 청록을 주축으로 학생 앱의 활기를 만들고, 크림과 앰버로 과제와 성취를 따뜻하게 구분하며, 그린으로 성장과 회복을 표시한다.

### Primary

- **Clear Teal** (`#18C5C7`, `oklch(0.748 0.124 196.1)`): 주요 행동, 현재 학습 흐름, 활성 탭, 중요한 진행 상태에 사용한다.
- **Teal Mist** (`#95E0E1`, `oklch(0.858 0.074 196.9)`): 선택된 필터, 약한 배경 강조, 그래프 보조 영역에 사용한다.

### Secondary

- **Study Cream** (`#FFEAC2`, `oklch(0.944 0.057 83.5)`): 과제 묶음, 예정된 활동, 부담 없는 안내 영역의 배경으로 사용한다.
- **Progress Amber** (`#FFC585`, `oklch(0.862 0.104 68.5)`): 마감 임박, 복습 필요, 풀이 중단 지점처럼 주의가 필요하지만 오류는 아닌 상태에 사용한다.

### Tertiary

- **Growth Green** (`#A3D47F`, `oklch(0.815 0.124 133.0)`): 성장률, 회복된 약점, 연속 풀이, 목표 달성에 사용한다.

### Neutral

- **Surface Tint** (`#FAFCFB`): 기본 앱 배경이다. 순백을 피하고 청록 쪽으로 아주 약하게 기운 표면을 사용한다.
- **Surface Soft** (`#F2F7F6`): 테이블 헤더, 필터 영역, 보조 패널처럼 낮은 층위를 구분할 때 사용한다.
- **Border Soft** (`#D7E3E2`): 카드, 입력 필드, 구분선에 쓰는 기본 경계색이다.
- **Text Strong** (`#203332`): 제목, 본문 핵심 텍스트, 주요 수치에 사용한다.
- **Text Muted** (`#5A6F6D`): 보조 설명, 메타 정보, 시간 정보에 사용한다.

### Named Rules

**The Growth Color Rule.** 초록은 성공을 과장하는 색이 아니라 실제 성장, 회복, 목표 달성에만 쓴다.

**The No Panic Rule.** 오답과 지각 상태는 빨간색에 의존하지 않는다. 텍스트, 아이콘, 정렬, 패턴을 함께 써서 낙인처럼 보이지 않게 한다.

## 3. Typography

**Display Font:** Pretendard with Inter and system-ui fallbacks
**Body Font:** Pretendard with Inter and system-ui fallbacks
**Label/Mono Font:** 코드와 채점 로그가 필요할 때는 JetBrains Mono 또는 ui-monospace 계열을 사용한다.

**Character:** 한글 UI에서 읽기 쉬운 산세리프를 기본으로 한다. 학생용 화면은 제목과 수치에 힘을 주고, 설명문은 짧게 유지한다.

### Hierarchy

- **Display** (700, `4rem`, 1.05): 제품 소개, 온보딩, 학습 요약의 가장 큰 메시지에만 사용한다.
- **Headline** (700, `2rem`, 1.15): 대시보드 주요 섹션 제목과 오늘의 학습 요약에 사용한다.
- **Title** (650, `1.25rem`, 1.25): 과제 카드, 문제 세트, 분석 패널 제목에 사용한다.
- **Body** (400, `1rem`, 1.65): 설명, 피드, 안내 문구에 사용한다. 본문 줄 길이는 65에서 75ch를 넘기지 않는다.
- **Label** (600, `0.875rem`, 1.3): 버튼, 칩, 테이블 헤더, 상태 라벨에 사용한다.

### Named Rules

**The Short Sentence Rule.** 학생에게 보여주는 문장은 한 번에 하나의 행동만 말한다.

**The Number With Meaning Rule.** 큰 숫자는 성장, 제출, 풀이 시간처럼 행동과 연결될 때만 크게 보여준다.

## 4. Elevation

이 시스템은 그림자를 기본 장식으로 쓰지 않는다. 깊이는 배경색의 층위, 얇은 경계선, 충분한 여백, hover 상태의 미세한 이동으로 만든다. 반복 사용되는 학습 화면에서는 표면이 떠 있는 느낌보다 정돈된 정보 구조가 우선이다.

### Shadow Vocabulary

- **Resting Surface** (`box-shadow: none`): 기본 카드, 문제 목록, 과제 묶음에 사용한다.
- **Interactive Lift** (`box-shadow: 0 8px 24px rgba(32, 51, 50, 0.10)`): 클릭 가능한 카드나 드롭다운이 hover 또는 open 상태일 때만 사용한다.
- **Focus Ring** (`0 0 0 3px rgba(24, 197, 199, 0.28)`): 키보드 포커스와 입력 활성 상태에 사용한다.

### Named Rules

**The Flat Until Active Rule.** 표면은 기본적으로 평평하다. 사용자가 선택하거나 열었을 때만 깊이를 얻는다.

## 5. Components

컴포넌트는 학습 상태를 빠르게 읽게 하는 도구다. 둥근 모서리는 8px를 기본으로 하며, 반복 카드 안에 또 다른 카드를 넣지 않는다.

### Buttons

- **Shape:** 기본 8px radius를 사용한다.
- **Primary:** Clear Teal 배경, Text Strong 텍스트, `12px 18px` 패딩을 기본으로 한다.
- **Hover / Focus:** hover는 배경을 약간 어둡게 하고 위치 이동은 1px 이하로 제한한다. focus는 청록 ring을 사용한다.
- **Secondary / Ghost:** Study Cream 또는 투명 배경을 쓰며, 보조 행동과 필터 초기화에 사용한다.

### Chips

- **Style:** Surface Soft 배경, Border Soft 경계, 4px radius를 사용한다.
- **State:** 선택된 칩은 Teal Mist 배경과 Clear Teal 경계로 표시한다. 색상만 바뀌지 않게 체크 아이콘 또는 선택 텍스트를 함께 둔다.

### Cards / Containers

- **Corner Style:** 8px radius를 기본으로 한다.
- **Background:** Surface Tint 또는 Surface Soft를 사용한다.
- **Shadow Strategy:** 기본 상태는 shadow 없이 border로 구분한다. 클릭 가능한 카드는 hover 때만 Interactive Lift를 쓴다.
- **Border:** Border Soft 1px를 기본으로 한다.
- **Internal Padding:** 작은 카드 16px, 학습 요약 카드 20px, 대시보드 주요 패널 24px를 사용한다.

### Inputs / Fields

- **Style:** Surface Tint 배경, Border Soft 1px, 8px radius를 사용한다.
- **Focus:** Clear Teal 경계와 Focus Ring을 함께 사용한다.
- **Error / Disabled:** 오류는 텍스트와 아이콘을 함께 제공한다. 비활성 상태는 불투명도만 낮추지 말고 이유를 짧게 표시한다.

### Navigation

- **Student Navigation:** 오늘의 학습, 문제집, 친구 활동, 랭킹, 성장 분석을 주요 축으로 둔다.
- **Teacher Navigation:** 반 관리, 과제, 제출 현황, 취약 유형, 시험 모드를 주요 축으로 둔다.
- **Active State:** 활성 항목은 Clear Teal 경계나 배경 tint로 표시하고, 텍스트 무게도 함께 올린다.

### Data Displays

- **Growth Graphs:** Growth Green은 실제 개선 지표에만 사용한다. 마감과 복습 필요 상태는 Progress Amber로 분리한다.
- **Ranking:** 순위만 크게 보여주지 않는다. 성장률, 연속 풀이, 과제 완료율을 함께 배치한다.
- **Submission Tables:** 교사용 표는 행 높이를 과하게 키우지 말고 필터와 정렬을 우선한다.

## 6. Do's and Don'ts

### Do

- 오늘 이어 풀 문제, 남은 과제, 회복할 약점을 첫 화면에서 바로 보이게 한다.
- 친구 활동은 작고 빠르게 스캔되는 피드로 제공한다.
- 성장 지표에는 전주 대비, 연속 풀이, 취약 유형 회복처럼 학생이 행동으로 이해할 수 있는 설명을 붙인다.
- 교사용 화면은 학생용보다 정보 밀도를 높이되, 같은 상태 언어와 색상 규칙을 유지한다.
- `prefers-reduced-motion`을 존중하고, 애니메이션은 상태 변화 이해를 돕는 경우에만 사용한다.

### Don't

- 백준을 그대로 복제한 문제은행 중심 UI로 만들지 않는다.
- 순위와 점수만 강조해 상위권 학생만 돋보이게 하지 않는다.
- 학교 행정 시스템처럼 딱딱하고 느린 관리 화면으로 만들지 않는다.
- 배지, 레벨, 효과음을 과하게 앞세우는 게임화에 의존하지 않는다.
- 같은 크기의 아이콘 카드 그리드를 반복해 기능을 나열하지 않는다.
- 색상만으로 정답, 오답, 지각 제출, 취약 유형을 구분하지 않는다.
- 여러 학교에 판매하는 범용 SaaS 도입 문의 페이지처럼 만들지 않는다.
