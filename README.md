# 🇰🇷 한국史記꾼 (Hanguk Sagi-kkun) - React 프론트엔드

AI 기반 맞춤형 한국사 학습 플랫폼  
**필기 이미지 → 요약 → 음성 → 퀴즈 → 오답노트까지!**

---

## 📌 소개

**한국史記꾼**은 한국사능력검정시험 수험생과 성인 학습자를 위한  
AI 기반 학습 서비스입니다.  
본 저장소는 해당 서비스의 **React 기반 프론트엔드** 구현을 담고 있으며,  
사용자가 한국사 학습 콘텐츠를 손쉽게 이용할 수 있도록 직관적인 UI와  
TTS, 문제 생성, 오답노트 기능을 통합 제공하고 있습니다.

---

## 🖥️ 주요 화면 구성

| 탭 | 설명 |
|-----|------|
| `Tab1.jsx` | 필기 이미지 업로드 → OCR + 요약 + TTS 음성 출력 |
| `Tab2.jsx` | AI 자동 문제 생성 → 선택지 풀이 + 해설 |
| `Tab3.jsx`, `Tab3-deep.jsx` | 오답노트 기반 복습 + 재풀이 기능 |
| `today.jsx` | 오늘의 위인 랜덤 팝업 |
| `FooterAudioPlayer.jsx` | 생성된 학습 오디오 재생 UI |

---

## 🔧 기술 스택

- **React.js**
- **JavaScript (ES6+)**
- **SCSS / CSS Modules**
- **Axios** (백엔드 연동용)
- **Gradio 기반 컴포넌트 일부 사용**
- **Creatie 기반 UI 디자인 템플릿**
- **FastAPI 백엔드와 RESTful API 연동**

---

## 🚀 설치 및 실행 방법

```bash
# 1. 프로젝트 클론
git clone https://github.com/your-repo/hanguk-sagikkun.git
cd Korean-History-Study(완성본)

# 2. 패키지 설치
npm install

# 3. 개발 서버 실행
npm start
