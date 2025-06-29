# 🌐 위기탈출 번역기 앱 프로젝트

## 📘 과목 정보
- **과목명**: 인공지능과 영상
- **학년**: 3학년

## 🧠 프로젝트 개요
MIT App Inventor를 활용하여 다양한 번역 기능(텍스트, 음성, 이미지)을 포함한 **번역기 앱**을 개발.

- UI 구성 및 블록 코딩 기반 앱 제작
- 번역 기능에 Google Translate API, OCR API 사용
- 현지 시간 표시 기능 등 여행 시 활용 가능성을 고려한 설계

## 📝 초기 웹 디자인 구상도
![image](https://github.com/user-attachments/assets/88b48ab9-4df8-4811-b04d-d359eaa85e19)

## 📱 주요 기능 및 구조

### 1. 메인 화면
- **앱 이름**: 위기탈출 번역기
- 버튼 구성:
  - 텍스트 번역
  - 음성 인식 번역
  - 이미지 번역
  - 현지 시간 표시
- 고려사항: 현지 시각은 Google TimeZone API 또는 수동 시차 계산 방식 사용

### 2. 텍스트 번역
- 한국어 → 선택된 언어로 번역
- 사용 API: Google Translate
- API 키 자동 발급 기능 구현
- 다국어 입력 → 다국어 번역 기능 확장 고려

### 3. 음성 인식 번역
- 음성 입력 → 텍스트 변환 → 번역 출력
- SpeechRecognizer 및 TextToSpeech 사용
- 음성 언어 자동 감지 기능 구현

### 4. 이미지(카메라) 번역
- OCR API로 이미지 내 텍스트 추출
- Google Translate API로 번역
- 문제점: 다양한 API의 JSON 구조 해석, API 제약

## ⚙️ 사용한 주요 기술 및 API
- MIT App Inventor
- Google Translate API
- OCR API (텍스트 인식)
- Google TimeZone API (시각 표시)

## 📁 결과물
- 안드로이드 앱 파일: `Translator.apk`
- 앱 디자인, 구조, 주요 기능은 `/screenshots` 폴더 참고 (스크린샷 추가 시)

## ✍️ 프로젝트를 통해 느낀 점
- **노코드 환경**에서도 앱 개발이 가능하다는 점에서 흥미로웠음
- API 한계, JSON 파싱 문제 등 다양한 장애요인을 해결해보며 실무 경험을 간접적으로 체험
- 간단한 프론트엔드 개발 역량을 키울 수 있었으며, 이후 다른 프로젝트에도 응용 가능성을 느낌

---

