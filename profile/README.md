# ⭐ 별 따라 안전 운전 
> 고령 이륜차 운전자를 위한 안전 교육 게임

<img src="/img/logo.png" width="300px" height="150px" title="Team Logo" alt="Logo"></img><br/>
<img src="/img/main_character.png" width="250px" height="250px" title="Main Character" alt="Main Character"></img><br/>

## 프로젝트 개요

> 별 따라 안전 운전은 고령 이륜차 운전자를 대상으로 한 웹 기반 안전 교육 게임입니다. <br>
기존의 지루한 강의식 교육을 벗어나 몰입감 높은 시뮬레이션 게임을 통해 실제적이고 효과적인 안전 교육을 제공합니다.

## 참여 기관 및 파트너

| 기관 | 역할 | 기여 내용 |
|------|------|----------|
| 한양대학교 불가사리팀 | 개발팀 | 게임 설계, 프론트엔드/백엔드 구현 |
| (주)별따러가자 | 기술파트너 | IoT 데이터 연계, 필드 검증 지원 |
| 한국교통안전공단 | 감수기관 | 안전교육 내용 검수, 효과성 검증 |
| 충청남도 예산군청 | 운영파트너 | 시범사업 대상자 모집, 현장 지원 |

## 🔍 사용자 리서치 주요 결과

- **교육 시간**: 5~10분 권장 (고령자 집중력 고려)  
- **조작 방식**: 선택형 인터랙션 선호  
- **보상 체계**: 명예형 보상 효과적 (상장, 인증서)  
- **접근성**: 카카오톡 채널 연동 시 지속 이용 가능성 ↑  

## 타겟 사용자

- **연령**: 60~80세 고령 이륜차 운전자  
- **지역**: 농촌 지역 (예산군 등)  
- **규모**: 500~1,500명 (단계적 확장)  
- **환경**: 집합 교육 시 태블릿 활용  

## 🔬 개발 근거 및 검증

### 실제 사고 데이터 기반 설계
- **예산군 이륜차 사고 분석**: 단독사고 70% 이상 (포트홀, 농수로 낙하)
- **음주운전**이 주요 사고 원인이나 직접적 교육 어려움
- **야간/수확철 사고 집중** → 시간대별 위험도 반영

### 게임화 이론 적용
- **고령층 대상 게임화 연구** 기반 설계
- **적응형 난이도, 명확한 목표, 즉각적 피드백** 구현
- **사회적 요소(명예 보상)** 활용으로 참여도 3배 증가 효과 기대

## 🎯 프로젝트 임팩트

### 교육 혁신
- **참여도 증가**: 기존 PPT 안전교육 대비 높은 참여율 예상  
- **기억 지속성**: 카드 뒤집기, 시나리오 선택을 통한 장기 기억 효과  
- **행동 변화**: 실제 안전 운전 행동 개선 유도

### 사회적 가치
- **의료비 절감**: 고령 이륜차 사고 예방을 통한 사회적 비용 감소
- **안전 문화 확산**: 마을 단위 집단 학습을 통한 지역 안전 규범 형성
- **디지털 포용**: 고령층의 디지털 기기 친숙도 향상

### 측정 지표
- 게임 완료율 및 점수 분포  
- 사용자 만족도 (별점 평가)  
- 교육 전후 주행 데이터 비교 ("별 따러가자" IoT 데이터 활용) 
- 사고 발생률 변화 추적  

## 주요 기능

### 🧭 게임 흐름  
🏠 **시작 화면** → 🎬 **프롤로그** → 🏍️ **주행 시뮬레이션** → 📊 **결과 화면**

### 🎯 5가지 안전 퀘스트

| 퀘스트 주제 | 게임 방식 | 고령자 맞춤 설계 |
|-------------|-----------|------------------|
| 🪖 안전모 착용 | 카드 쌍 맞추기 게임 | 큰 카드, 단순한 패턴 |
| 🕳️ 포트홀 안전 주행 | 상황별 선택 퀘스트 | 직관적 선택지, 명확한 피드백 |
| 🍶 음주 운전 예방 | 막걸리 치우기 게임 | 드래그 동작 최소화 |
| 🍎 과수원 안전 주행 | 상황별 선택 퀘스트 | 농촌 환경 친숙성 |
| 🌙 야간 주행 자제 | 시간 설정 인터랙티브 게임 | 시각적 시간 변화 표현 |

### 🎨 고령층 친화적 UX
- **🖱️ 직관적 UI**: 큰 버튼, 명확한 색상 대비, 단순한 네비게이션
- **🐢 느린 전환**: 고령층 눈높이에 맞춘 화면 전환 속도
- **📖 스토리텔링**: 손자/손녀 캐릭터 반응을 통한 몰입도 높은 학습 제공
- **🔊 음성 지원**: 게임 내 상황에 맞춘 효과음으로 흥미 유도

## 🛠️ 개발 환경

### Frontend
```bash
React 18.2.0
TypeScript 4.9.5
Tailwind CSS 3.3.0
Vite 4.4.5
```

### Backend
```bash
Firebase 9.23.0
Firestore Database
Firebase Hosting
Firebase Authentication (익명 인증)
```

### 버전 관리
```bash
Git Flow 전략 사용
├── main: 프로덕션 배포용
├── feature/*: 기능별 개발 브랜치
└── hotfix/*: 긴급 수정 브랜치
```

### 협업 및 커뮤니케이션
- **프로젝트 관리**: Notion Database 활용
  - 백로그 관리, 스프린트 계획
  - 기능 명세서, API 문서화
- **이슈 관리**: Notion 칸반 보드
  - 버그 트래킹, 기능 요청 관리
  - 우선순위별 라벨링 시스템
- **코드 리뷰**: GitHub Pull Request
- **디자인 협업**: Figma 실시간 협업

## 📊 효과 검증 및 확장성

### 1단계: 시범 운영
- **대상**: 예산군 500-1,500명
- **기간**: 2025년 6월 ~ 8월
- **방식**: 집합교육 시 태블릿 활용

### 2단계: 지역 확대
- **대상**: 충청북도, 양평군 등 농촌지역
- **연계**: 별따러가자 IoT 시스템과 데이터 통합

### 3단계: 대상 확장
- **확장 대상**: 전동보장구, 배달라이더
- **플랫폼**: 웹앱 → 네이티브 앱 전환

## 설치 및 실행 방법

### 요구사항
- Node.js 18.0.0 이상
- npm 또는 yarn

### 설치
```bash
# 저장소 클론
git clone https://github.com/your-username/follow-star-safe-driving.git
cd follow-star-safe-driving

# 의존성 설치
npm install

# 환경 변수 설정
cp .env.example .env.local
# Firebase 설정 정보 입력

# 개발 서버 실행
npm run dev
```

### 빌드 및 배포
```bash
# 프로덕션 빌드
npm run build

# Firebase 배포
npm run deploy
```

## 👥 팀원

| 이름 | 역할 | 담당 업무 | 연락처 |
|------|------|-----------|---------|
| 유지혜 | 팀장, PM | 프로젝트 관리, 사업 기획 | jihyeyu33@hanyang.ac.kr |
| 김소민 | UI/UX Designer | 디자인 시스템, 사용자 경험 설계 | thals304@hanyang.ac.kr |
| 김서현 | Frontend Developer | React 컴포넌트, 게임 로직 구현 | dianwls0326@hanyang.ac.kr |
| 이현호 | Frontend Developer | 상태 관리, 성능 최적화 | kclhh4318@hanyang.ac.kr |
| 이정재 | Backend Developer | Firebase 연동, 데이터 관리 | jjlee9903@hanyang.ac.kr |

## Acknowledgement

본 프로젝트는 **카카오임팩트 테크포임팩트 프로그램**을 통해 개발되었습니다.

<img src="/img/kakao_impact_logo_color.png" width="200px" alt="카카오임팩트 로고">

---

⭐ **이 프로젝트가 도움이 되셨다면 Star를 눌러주세요!**

> 💡 *"안전한 길, 함께 만들어가요"* - 고령 운전자의 안전한 여행을 위한 작은 시작

---

# ⭐ Follow-Star-Safe-Driving
> Safety Education Game for Elderly Motorcycle Drivers

<img src="/img/logo.png" width="300px" height="150px" title="Team Logo" alt="Logo"></img><br/>
<img src="/img/main_character.png" width="250px" height="250px" title="Main Character" alt="Main Character"></img><br/>

## Project Overview

> Follow-Star-Safe-Driving is a web-based safety education game designed for elderly motorcycle drivers. <br>
Breaking away from traditional lecture-style education, it provides practical and effective safety training through immersive simulation games.

## Participating Organizations & Partners

| Organization | Role | Contribution |
|------|------|----------|
| Hanyang University Bulgasari Team | Development Team | Game design, frontend/backend implementation |
| Starpickers Co., Ltd. | Brian Fellow | IoT data integration, field validation support |
| Korea Transportation Safety Authority | Supervisory Organization | Safety education content review, effectiveness verification |
| Yesan County Office, Chungcheongnam-do | Operation Partner | Pilot program participant recruitment, field support |

## 🔍 Key User Research Results

- **Education Duration**: 5-10 minutes recommended (considering elderly concentration span)  
- **Interaction Method**: Preference for selection-based interactions  
- **Reward System**: Honor-based rewards effective (certificates, awards)  
- **Accessibility**: Higher continued usage possibility when integrated with KakaoTalk channels  

## Target Users

- **Age**: 60-80 years old elderly motorcycle drivers  
- **Region**: Rural areas (Yesan County, etc.)  
- **Scale**: 500-1,500 users (phased expansion)  
- **Environment**: Tablet utilization during group education sessions  

## 🔬 Development Foundation & Validation

### Design Based on Actual Accident Data
- **Yesan County Motorcycle Accident Analysis**: Over 70% single-vehicle accidents (potholes, agricultural waterway falls)
- **Drunk driving** as major accident cause, but direct education challenging
- **Night/harvest season accident concentration** → Time-based risk reflection

### Gamification Theory Application
- Design based on **gamification research for elderly populations**
- Implementation of **adaptive difficulty, clear objectives, immediate feedback**
- **Social elements (honor rewards)** utilization expected to triple participation rates

## 🎯 Project Impact

### Educational Innovation
- **Increased Participation**: Higher participation rates expected compared to traditional PPT safety education  
- **Memory Retention**: Long-term memory effects through card flipping and scenario selection  
- **Behavioral Change**: Inducing actual safe driving behavior improvements

### Social Value
- **Medical Cost Reduction**: Decreased social costs through elderly motorcycle accident prevention
- **Safety Culture Expansion**: Formation of regional safety norms through village-level group learning
- **Digital Inclusion**: Improved digital device familiarity among elderly populations

### Measurement Indicators
- Game completion rates and score distribution  
- User satisfaction (star rating evaluation)  
- Pre/post-education driving data comparison (utilizing "Byeolttareogaja" IoT data) 
- Accident occurrence rate change tracking  

## Key Features

### 🧭 Game Flow  
🏠 **Start Screen** → 🎬 **Prologue** → 🏍️ **Driving Simulation** → 📊 **Results Screen**

### 🎯 5 Safety Quests

| Quest Theme | Game Method | Elderly-Friendly Design |
|-------------|-----------|------------------|
| 🪖 Helmet Wearing | Card Matching Game | Large cards, simple patterns |
| 🕳️ Pothole Safe Driving | Situational Choice Quest | Intuitive options, clear feedback |
| 🍶 Drunk Driving Prevention | Rice Wine Removal Game | Minimized drag actions |
| 🍎 Orchard Safe Driving | Situational Choice Quest | Rural environment familiarity |
| 🌙 Night Driving Restraint | Time Setting Interactive Game | Visual time change representation |

### 🎨 Elderly-Friendly UX
- **🖱️ Intuitive UI**: Large buttons, clear color contrast, simple navigation
- **🐢 Slow Transitions**: Screen transition speeds adapted to elderly users
- **📖 Storytelling**: Immersive learning through grandson/granddaughter character reactions
- **🔊 Audio Support**: Interest-inducing sound effects matching in-game situations

## 🛠️ Development Environment

### Frontend
```bash
React 18.2.0
TypeScript 4.9.5
Tailwind CSS 3.3.0
Vite 4.4.5
```

### Backend
```bash
Firebase 9.23.0
Firestore Database
Firebase Hosting
Firebase Authentication (Anonymous Auth)
```

### Version Control
```bash
Git Flow Strategy
├── main: Production deployment
├── feature/*: Feature-specific development branches
└── hotfix/*: Emergency fix branches
```

### Collaboration & Communication
- **Project Management**: Notion Database utilization
  - Backlog management, sprint planning
  - Feature specifications, API documentation
- **Issue Management**: Notion Kanban board
  - Bug tracking, feature request management
  - Priority-based labeling system
- **Code Review**: GitHub Pull Request
- **Design Collaboration**: Figma real-time collaboration

## 📊 Effect Validation & Scalability

### Phase 1: Pilot Operation
- **Target**: 500-1,500 people in Yesan County
- **Period**: June ~ August 2025
- **Method**: Tablet utilization during group education

### Phase 2: Regional Expansion
- **Target**: Rural areas including Chungcheongbuk-do, Yangpyeong-gun
- **Integration**: Data integration with Byeolttareogaja IoT system

### Phase 3: Target Expansion
- **Expansion Target**: Electric mobility aids, delivery riders
- **Platform**: Web app → Native app transition

## Installation & Execution

### Requirements
- Node.js 18.0.0 or higher
- npm or yarn

### Installation
```bash
# Clone repository
git clone https://github.com/your-username/follow-star-safe-driving.git
cd follow-star-safe-driving

# Install dependencies
npm install

# Set environment variables
cp .env.example .env.local
# Enter Firebase configuration information

# Run development server
npm run dev
```

### Build & Deploy
```bash
# Production build
npm run build

# Firebase deployment
npm run deploy
```

## 👥 Team Members

| Name | Role | Responsibilities | Contact |
|------|------|-----------|---------|
| Jihye Yu | Team Leader, PM | Project management, business planning | jihyeyu33@hanyang.ac.kr |
| Somin Kim | UI/UX Designer | Design system, user experience design | thals304@hanyang.ac.kr |
| Seohyun Kim | Frontend Developer | React components, game logic implementation | dianwls0326@hanyang.ac.kr |
| Hyunho Lee | Frontend Developer | State management, performance optimization | kclhh4318@hanyang.ac.kr |
| Jeongjae Lee | Backend Developer | Firebase integration, data management | jjlee9903@hanyang.ac.kr |

## Acknowledgement

This project was developed through the **Kakao Impact Tech for Impact Program**.

<img src="/img/kakao_impact_logo_color.png" width="200px" alt="Kakao Impact Logo">

---

⭐ **If this project helped you, please give us a Star!**

> 💡 *"Creating safe roads together"* - A small beginning for the safe journey of elderly drivers
