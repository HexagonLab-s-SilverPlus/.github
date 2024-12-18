# SilverPlus - 어르신 AI 말동무 및 관공서 문서 작성 도우미
<!-- 로고 이미지를 프로젝트에 추가한 경우 경로를 수정하세요 -->

## 프로젝트 소개
**SilverPlus**는 고령화 사회의 노인 복지 권리 증진을 목표로 하는 **AI 기반 어르신 말동무 서비스**와 **관공서 문서 작성 도우미 기능**을 제공하는 통합 플랫폼입니다.  
노년층의 정서적 안정, 사회적 고립 해소, 공공서비스 접근성 향상을 지원하며, 가족 구성원의 부담을 덜고 노인의 삶의 질을 향상시키는 데 기여합니다.

---

## 주요 기능

### 1. 어르신 AI 말동무 서비스
- **음성 대화**: 자연스러운 음성 대화를 통해 정서적 안정 제공.
- **건강 모니터링**: 음성 분석을 통한 정서 및 건강 상태 점검.
- **감정 분석**: 언어 패턴 및 음성 감정 분석으로 우울증, 치매 등 질병 추적.
- **긴급 알림**: 위급 상황 발생 시 보호자 및 담당자에게 즉시 알림 전송.

### 2. 관공서 문서 작성 도우미
- **문서 템플릿 제공**: 자주 사용하는 관공서 문서 템플릿 제공.
- **음성 입력 지원**: TTS와 STT 기술을 활용해 문서를 작성.
- **전자 서명**: 관공서 문서 전송 및 서명을 간소화.
- **관공서 API 연동**: 공공서비스와의 데이터 연동 및 자동 제출.

### 3. 사용자 맞춤 인터페이스
- **어르신 친화 UI/UX**: 고대비, 큰 글씨, 직관적 인터페이스 제공.
- **가족 데이터 공유**: 가족 구성원과 데이터를 공유하여 소통 강화.

---

## 프로젝트 목적 및 의의
- **노년층의 디지털 소외 해소**: 인터넷과 공공서비스 접근성을 높여 디지털 복지를 실현.
- **사회적 고립 문제 해결**: AI를 통한 정서적 지원과 가족과의 데이터 공유로 연결성 강화.
- **노인 복지 권리 증진**: 개인화된 복지 서비스를 제공하여 삶의 질을 향상.

---

## 기술 스택

### **프론트엔드**
- **React.js**: UI 설계 및 구현
- **Redux**: 상태 관리
- **Axios**: API 호출

### **백엔드**
- **Spring Boot**: RESTful API 서버
- **OpenCV, TensorFlow**: 음성 및 영상 데이터 분석
- **PyTorch**: 감정 분석 및 질병 추적

### **데이터베이스**
- **MongoDB**: 사용자 데이터 저장
- **AWS S3**: 음성 및 문서 데이터 저장

### **AI 및 음성 기술**
- **Google Speech-to-Text**
- **Amazon Polly (TTS)**

---

## 주요 화면 및 워크플로우
1. **로그인/회원가입**: OAuth 기반 간편 로그인과 가족 계정 연동.
2. **대화 화면**: AI와의 자연스러운 대화 창 구현.
3. **문서 작성 화면**: 음성으로 작성하고 템플릿을 활용한 문서 편집.

---

## 팀 소개

**팀명**: 육각형 연구소 (Hexagon Lab)  
**의미**: `6명의 유능한 개발자가 다양한 문제를 균형 잡힌 방식으로 해결하는 협력 지향 팀.`

| ![최은영](https://github.com/silver0-stack.png) | ![김홍세](https://github.com/ghdtpwlq.png) | ![임서이](https://github.com/hanadoolyseoi.png) | ![노수진](https://github.com/sujannoh.png) | ![김태장](https://github.com/TJ-kim0514.png) | ![이상무](https://github.com/NickLee-dev.png) |
|-------------|-------------|-------------|-------------|-------------|-------------|
| **최은영 (팀장)** | **김홍세 (부팀장)** | **임서이** | **노수진** | **김태장** | **이상무** |
| - |- | - | - | - | - |



---

## 설치 및 실행

### 클론
```bash
git clone https://github.com/your-repo/SilverPlus.git
cd SilverPlus
```

### 프론트엔드 실행
```bash
cd client
npm install
npm start
```

### 백엔드 실행
```bash
cd server
./mvnw spring-boot:run
```

## 기여 및 문의
### 기여 방법
이 프로젝트에 기여하고 싶다면 `육각형 연구소`에게 문의하세요. 🙌
### 문의
- 팀 이메일: dev.silverplus@gmail.com
