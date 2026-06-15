# TITeng Tech Blog & DevPortal (티아이티이엔지 개발자 포털 & 테크 블로그)

㈜티아이티이엔지(TITeng Co., Ltd.)의 스마트 금융 결제 하드웨어 제품군(카드 리더기, 핀패드, 카드 프린터 등) 및 모바일 무접촉 결제 솔루션인 **tPay NFC 모바일 SDK** 연동 기술을 아우르는 개발자 포털 겸 테크 블로그 웹 사이트 프로젝트입니다.

---

## 🌟 주요 특징 (Key Features)

* **실시간 아티클 탐색**: 카테고리(H/W 엔지니어링, S/W & 결제 플랫폼, 보안 및 인증 규격, 엔지니어링 문화)별 필터링 및 실시간 검색 지원
* **인기 기술 태그 클라우드**: 해시태그(`#NFC`, `#tPay`, `#SRT1356` 등) 기반의 신속한 아티클 다이내믹 필터링
* **인터랙티브 API 플레이그라운드**: 플랫폼별(Android Kotlin, iOS Swift, Windows C#, Embedded C++) tPay NFC SDK 초기화 및 결제 요청 예제 코드 제공 및 실시간 복사 기능
* **아티클 상세 리더 (모달)**: 목차(TOC) 생성, 추천 및 공유, 관련 SDK 리소스 다운로드 연계 기능이 내장된 고품질 모달 기반 글 읽기 도구
* **모던 & 다이나믹 UI**: 다크 모드(Dark Mode) 지원, Tailwind CSS를 적용한 부드러운 트랜지션 및 마이크로 인터랙션 구현

---

## 🛠 기술 스택 (Tech Stack)

* **Core**: HTML5, Vanilla JavaScript
* **Styling**: Tailwind CSS (CDN), Font Awesome Icons
* **Design Pattern**: Single Page Application (SPA) 기반 상태 관리 및 컴포넌트 렌더링

---

## 📂 프로젝트 구조 (Project Structure)

```
TITeng-Korea/
├── .git/               # Git 저장소 설정 폴더
├── index.html          # 메인 페이지 및 비즈니스 로직 (HTML/CSS/JS 통합 파일)
└── README.md           # 프로젝트 안내 문서 (본 파일)
```

---

## 🚀 시작하기 (Getting Started)

본 프로젝트는 별도의 빌드 과정이 필요 없는 정적 HTML 파일로 구성되어 있습니다.

### 1. 로컬에서 실행하기
* **방법 A**: `index.html` 파일을 웹 브라우저에 드래그 앤 드롭하여 즉시 실행합니다.
* **방법 B**: VS Code의 **Live Server** 확장 프로그램을 이용하거나, 아래 명령어로 로컬 개발 서버를 기동하여 접속합니다.
  ```bash
  # npm이 설치된 경우
  npx http-server ./
  ```

### 2. Git 동기화 (Sync)
로컬 변경 사항을 원격 저장소(`https://github.com/TITeng-Korea/TITeng-Korea.git`)에 푸시하려면 다음 단계를 진행합니다.
```bash
git add .
git commit -m "Commit message"
git push origin main
```

---

## 📄 라이선스 및 문의 사항
* **라이선스**: 본 프로젝트 소스코드는 ㈜티아이티이엔지의 자산이며 관련 오픈소스 라이선스 정책을 따릅니다.
* **기술지원**: [support@titeng.co.kr](mailto:support@titeng.co.kr)
* **대표전화**: 032-832-4700
* **공식 홈페이지**: [www.titeng.co.kr](http://www.titeng.co.kr/main/main.php)
